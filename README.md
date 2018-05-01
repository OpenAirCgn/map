# map

Allgemeine Informationen können main.html entnommen werden.

TODOs wären:
* Code reorganisieren
* Überschreitung stündlicher Mittelwert der letzten 7 Tage
* Überschreitung täglicher Mittelwert der letzten 7 Tage
* Anpassung API Rest für LANUV Daten
  * Weitere Stationswerte anzeigen
  * Nur Ausgabe eines Zeitstemples
* Timesilder für die letzten 7 Tage (bzw. 9 Tage minus 2 wegen der LANUV Daten, die immer etwas zurück datieren)
  * PostGIS Datenbank aufsetzen
  * Serverkomponente aufsetzen (Jede Stunde: Mittelwerte, Maximum, Anzahl Überschreitungen vom Schwellenwert )
