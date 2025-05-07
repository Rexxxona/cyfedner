# Jednostavna igra pucanja na vanzemaljce napravljena u Pythonu 3 koristeći pygame
==========================================================

* Vanzemaljci imaju različite tipove kretanja u zavisnosti od boja.
* Rakete ubijaju pojedinačne vanzemaljce, a svemirski brod ima neograničenu zalihu.
* Bombe ubijaju sve vanzemaljce na ekranu i retke su, koristite ih mudro.
* Povremeno se pojavljuju pojačanja koja daju dodatne bombe ili štit.
* Pojačanje sa štitom omogućava svemirskom brodu da preživi sudar sa jednim vanzemaljcem.
* Najbolji rezultati se beleže u SQLite bazi podataka.

Kontrole igre
-------------

**MENIJI**

* w/s: pomjeranje kursora
* enter/return: potvrda izbora ili unos rezultata

**IGRA**

* w/a/s/d: pomjeranje svemirskog broda
* space: ispaljivanje rakete
* b: bacanje bombe

Uputstva
------------

Ovaj program zahtijeva [pygame biblioteku](http://www.pygame.org/).  
Možete je instalirati na sledeći način:  

python3 -m pip install pygame --user

Zatim pokrenite program **cyfender_game.py** iz terminala koristeći Python, 
npr.  
python3 cyfender_game.py
