### Relevant contents of dataset:
- If game was rated (Boolean True or False)
- Zeitpunkt des Spiels
- Anzahl der Züge
- Spielausgang ('mate', 'resign', 'outoftime', 'draw')
- Gewinner des Spiels ('white', 'black', 'draw')
- Zeitkontrolle (-begrenzung) des Spiels
- Namen und Rating der Spieler
- Genaue Abfolge der Spielzüge
- Erföffnungs-ID (Eco) und Name
- Anzahl Züge in Eröffnung

### Ideen für Auswertungen:
Immer überlegen, ob nur rated Spiele analysiert werden und welche Zeitkontrolle (z.B. nur Schnellschach)
- Wie viel Prozent der Spiele hat weiß/schwarz/remis gewonnen?
- Was sind die beliebtesten Eröffnungszüge und beliebtesten Eröffnungen?
  - Abhängigkeit vom Rating der Spieler
  - Auswirkung auf Siegchancen (je nach Rating, je nach Zeitkontrolle
- Veränderung des Ratings bestimmer Spieler über Zeit
  - Abhängigkeit Startrating und Zeit zwischen Spielen
# - In wie viel Prozent der Spiele wurde en passant gespielt? 
  - Anteil, in wie vielen en passant möglich war
  - Abhänigkeit vom Rating der Spieler
  - Dies sollte der Hauptteil der Analyse sein ;)
- ...
