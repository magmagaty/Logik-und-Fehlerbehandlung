# Logik-und-Fehlerbehandlung (Auswertungen mit WENN, verschachtelter WENN, WENNS, UND/ODER/NICHT sowie WENNFEHLER)
WENN-Formel. Wenn die Bearbeitungsdauer mehr als 180 Minuten beträgt, soll 'SLA verletzt' erscheinen, sonst 'SLA eingehalten'.
Verschachtelten WENN-Formel: > 480 Min = 'Hoch', > 240 Min = 'Mittel', sonst 'Niedrig'.
Dieselbe Klassifizierung dieses Mal mit der WENNS-Funktion statt einer verschachtelten WENN.
'Kritisch', wenn Bearbeitungsdauer > 240 UND Abteilung = 'Reklamation', sonst 'Normal'.  
'Sonderfall', wenn Abteilung = 'Reklamation' ODER 'Eskalation', sonst 'Standardfall'.  
'Erfasst', wenn die Bemerkung NICHT leer ist, sonst 'Fehlt'.

## Screenshots

![Auswertung 1](auswertung1.png)

![Auswertung 2](auswertung2.png)

![Auswertung 3](auswertung3.png)

![Auswertung 4](auswertung4.png)

![Auswertung 5](auswertung5.png)
