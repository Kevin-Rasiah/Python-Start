# Tic-Tac-Toe in Python

Ein interaktives, konsolenbasiertes Tic-Tac-Toe-Spiel für zwei Spieler, entwickelt in Python. Dieses Projekt ist mein erstes Projekt was ich zuhause(Python) und nicht in der Schule(Java) geschrieben habe. 

---

## Features
- Interaktive Steuerung: Spieler X und Spieler O wechseln sich rundenbasiert ab
- Intelligente Zug-Validierung: Bereits besetzte Felder werden erkannt und Falscheingaben abgefangen
- Automatische Gewinnprüfung: Das Spiel prüft nach jedem Zug alle horizontalen, vertikalen und diagonalen Reihen auf einen Sieger
- Unentschieden-Erkennung: Wenn das Spielfeld voll ist, ohne dass ein Spieler gewonnen hat, endet das Spiel unentschieden

---

## Technische Umsetzung
Das Spiel wurde modular aufgebaut, um sauberen Coe zu garantieren:
1. erstelle_brett(): Initialisiert die 3x3-Spielfeldmatrix
2. drucke_brett(): Formatiert und visualisiert das Spielfeld in der Konsole
3. mache_zug(): Verarbeitet die Spielerkoordinaten und validiert das Zielfeld
4. pruefe_gewonnen(): Algorithmus zur Überprüfung aller Gewinnkonstellationen
5. pruefe_unentschieden(): Kontrolliert, ob noch freie Felder vorhanden sind

---

## Schwachstellen:
- Steuerung: Die Spieler müssen Zeilen und Spalten auswählen => schöner wäre eine per Klicken gewünschtes Feld auswählen zu können
- Optik: mit "|" und "---" sieht das Spiel sehr primitiv aus => schöner wäre ein cleanes Design mit durchgezogenen Linien


## Spielstart
Um das Spiel zu starten, führe die Datei einfach in der Konsole aus