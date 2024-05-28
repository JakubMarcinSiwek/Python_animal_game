.. AnimalSimulator documentation master file, created by
   sphinx-quickstart on Fri Jun 23 13:51:08 2023.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to AnimalSimulator's documentation!
===========================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:

Animal Simulator
================

Animal Simulator to prosta gra, w której gracz troszczy się o swoje wirtualne zwierzątko, dbając o jego potrzeby, takie jak jedzenie, sen i zabawa.

Główne Funkcje
--------------

* Wybór pomiędzy czterema zwierzętami: psem, kotem, królikiem i wężem.
* Nakarmienie zwierzątka różnymi rodzajami jedzenia, które zwiększają poziom najedzenia.
* Zabawa ze zwierzątkiem za pomocą różnych aktywności, które zmniejszają nudę.
* Funkcja spania, która resetuje poziom snu zwierzątka do 0.

Kod
---

Kod został podzielony na trzy główne pliki:

* `main.py` - Główny plik, który uruchamia symulator.
* `app.py` - Zawiera główną klasę aplikacji `AnimalSimulator`.
* `utils.py` - Zawiera funkcje pomocnicze, takie jak `update_values` i `update_stats_labels`.


App
===================
.. automodule:: Projekt.app
   :members:

Utils
===================
.. automodule:: Projekt.utils
   :members:



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
