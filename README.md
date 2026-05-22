# startcomputer
Startcomputer voor de WAW

## Proces flow

START
 ↓
ORANGE (20s)
 ↓
5 min signaal
 ↓
KLASSE 1
  - 4 min
  - 1 min
  - piezo 10s
  - START (lang signaal)
 ↓
KLASSE 2
 ↓


# Install nodered
https://nodered.org/docs/getting-started/windows



Rules om code mee te genereren. Getest en werkt.

Digitale Poort 2: Schakelaar
Digitale Poort 9: gele led
Digitale Poort 5: blauwe led
Digitale Poort 4: Piezo met toon frequentie 2000

Regels:
Stap a. Als ik op de knop druk start het proces. 
Als ik nog een keer op de knop druk stop het proces en ga terug naar stap a.
Stap 1: Op minuut 0 toon van 2 seconden
Stap 3: Op minuut 1 toon van 1 seconden en zet blauwe led aan.
Stap 4: Op minuut 4 toon van 1 seconden en zet blauwe led uit.
Stap 5: Op 4 minuten en 50 seconden, tel 10 seconden waarbij de gele led op iedere seconde heel even knippert.
Stap 6: Op 5 minuten toon van 2 seconden.
Stap 7: Zet timer terug op minuut 0 en ga naar stap 2.
