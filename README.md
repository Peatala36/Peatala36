- 👋 Hi, I’m @Peatala36
- 👀 I’m interested in programming, railways and how to combine the two interests



git Anleitung für Git
=====================

Projekt lokal abspeichern
-------------------------
Öffne das Terminal
Wechsle in das git-Verzeichnis: cd git
Prüfe den Status: git status
Falls alle Dateien im Homeverzeichnis angezeigt werden: git init
Prüfe erneut den Status: git status

Kopiere ein Projekt in das Verzeichnis: git clone https://github.com/Peatala36/[...].git

Wechsle in das kopierte Verzeichnis: cd [...]

Führe die Änderungen durch


Projekt hochladen
-----------------
Prüfe den Status: git status
Die geänderte Datei sollte in rot dargestellt werden
Füge die geänderte Datei zu: git add [...].py
Bei der erneuten Status-Abfrage sollte die Datei nun grün angezeigt werden

Kommentiere Deine Änderung: git commit -m "..." [...].py

Datei hochladen: git push


Projektdateien aus github updaten
---------------------------------
Wenn das Remote-Repository Commits enthält, die lokal nicht vorhanden sind, muss folgender Befehl ausgeführt werden: git pull

evtl. auch: git pull https://github.com/Peatala36/[...].git
