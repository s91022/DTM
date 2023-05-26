# Value By Alpha Maps in QGIS

## Datenquelle (Geometrie & Wahlergebnisse)
[Bundestagswahl 2021](https://www.bundeswahlleiterin.de/bundestagswahlen/2021/ergebnisse.html)
Tabelle (Kerg) mit Wahlergebnisse bereinigen:
![Screenshot 2023-05-26 095620](https://github.com/s91022/DTM/assets/134683960/e7ebb2cf-0af0-43da-b9d4-e2bbfa965468)

##QGIS

1,) Vergleich SPD vs. CDU Stimmenstärkstere Partei regelparsiert darstellen
```
"SPD > "CDU"
```
```
"SPD < "CDU"
```

2) Eben "Alpha" ergenzen auf Symbolebene 1 setzen
![Screenshot 2023-05-26 104752](https://github.com/s91022/DTM/assets/134683960/c841ab81-d4a7-4f67-b6c1-2b9a3e0cd79e)

3.) Regel für Ebne "Alpha": über " Einfache Füllung" unter " Füllfarbe" > Datenbasierte "Übersteuerung" > "Bearbeiten"
![Screenshot 2023-05-26 105840](https://github.com/s91022/DTM/assets/134683960/6310d3bd-2fae-4eb0-9d81-5adafdce159f)

4.) Statt einen festen Alpha-Wert, wird dieser wertebasiert aus einem anderen Atributt für jede Bezugseinheit berechnet
![Screenshot 2023-05-26 111238](https://github.com/s91022/DTM/assets/134683960/315b64d7-64ad-4a20-823d-91e9e7fcf520)
