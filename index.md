# Anleitung

Eine Auflistung und Beschreibung aller Spielkomponenten in OPT, die von Vanilla abweichen.

- [Reparatur](https://github.com/OperationPandoraTrigger/OPT-Server-Mod/wiki/Anleitung/_edit#reparatur)
- [GPS](https://github.com/OperationPandoraTrigger/OPT-Server-Mod/wiki/Anleitung/_edit#gps)

## Reparatur
v0.0.1(Legacy)

Ermöglicht die Reparatur im Feld von in der Mobilität beeinträchtigten Fhrzeugen

### Feldreparatur
- Möglich, wenn ein für die Mobilität nötiges Teil eines Fahrzeuges kritisch beschädigt ist (> 64%)
- Die Feldreparatur setzt den Schaden aller Mobilitäts-Teile auf 10%, sofern sie mehr Schaden haben
- Die Dauer der Feldreparatur hängt von der Zahl beschädigter Komponenten ab (15-120sec).
- Jedes Fahrzeug kann nur begrenzt oft einer Feldreparatur unterzogen werden (aktuell: ein Mal)
- Die Feldreparatur-Option kann aufgeladen werden, indem eine Komplettreparatur an einem LKW durchgeführt wird
- Spieler auf dem Ingenieur-Slot können als einzige die Feldreparatur unbegrenzt oft anwenden
- Durchführbar über das Mausradmenü, wenn das betroffene Fahrzeug angeschaut wird (zu Fuß)

### Reservekanister
- Wenn einem Fahrzeug der Sprit ausgeht ( < 10%), kann der Reservekanister verwendet werden
- Der Kanister fügt 10% Sprit hinzu
- Jedes Fahrzeug hat nur eine begrenzte Anzahl an Reservekanistern (aktuell: einen)
- Der Reservekanister kann aufgeladen werden, indem eine Komplettreparatur an einem LKW durchgeführt wird
- Spieler auf dem Ingenieur-Slot können als einzige den Reservekanister unbegrenzt oft einsetzen
- Durchführbar über das Mausradmenü, wenn das betroffene Fahrzeug angeschaut wird (zu Fuß)

### Komplettreparatur
- Ist möglich, sobald ein Fahrzeug mehr als 1% Hüllen- oder Teileschaden hat
- Dauert immer eine fixe Zeit (aktuell: 120sec)
- Setzt den Schaden der Hülle sowie aller Teile auf 0%.
- Lädt die Fähigkeit zur Feldreparatur und den Reservekanister auf
- Ein LKW hat nur eine begrenzte Anzahl an Ersatzteilen, kann eine Komplettreparatur also nur begrenzt oft nutzen (aktuell: 10)
- Jede Reparatur (egal wie schwer die Schäden) verbraucht immer eine Ersatzteilladung
- Durchführbar über das Mausradmenü, wenn das betroffene Fahrzeug angeschaut wird (man muss im Rep-LKW sitzen!)



## GPS-System
Stand v0.1.2

### Funktion

Zeigt auf allen Karten (Hauptkarte, Minimap, Beammap, ...) die Positionen verbündeter Spieler.
- Jeder sieht sich selbst
- Jeder sieht alle Einheiten in seiner Gruppe
- Jeder sieht alle Gruppenführer seiner Seite
- Jeder Spieler sieht alle Spieler die auf Revive warten
- Jeder Spieler bekommt angezeigt ob er in einem Fahrzeug sitzt (noch nicht implementiert)
- Gruppenführer sehen alle Spieler seiner Seite
- Verwundete Spieler werden mit einem roten Marker und dem Textzusatz (Verwundet) markiert
- Stabilisierte Spieler werden mit einem orangen Marker und dem Textzusatz (Stabilisiert) markiert

### CBA-Settings (für Spieler)

Addon-Options / OPT / GPS

- Einheitennamen anzeigen (Immer/Nur bei Mouseover)