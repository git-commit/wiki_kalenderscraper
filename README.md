wiki_kalenderscraper
====================

Kalenderscraper fuer wiki.muc.ccc.de/kalender, Export zu .ics und .json

Exportiert alle Events der Tabelle zu
wiki_kalender.ics

Exportiert das naechste Event zu
nextevent.json
(fuer anzeiger)

python dependencies installieren:

    nix-shell .
  
oder

    pip install -r requirements.txt

oder (Ubuntu):

    apt-get install python3-bs4 python3-icalendar python3-html5lib 
