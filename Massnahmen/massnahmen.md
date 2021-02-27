
# Maßnahmen

## I) Übergeordnete Maßnahmenkategorien

|ID|Name|Beschreibung|Standardsortierung|
|---|---|---|---:|
m.abtandsregeln | Abstandsregeln | | 10000
m.maskenpflicht | Maskenpflicht | | 20000
... |


ToDo: Mögliche weitere Maßnahmenkategorien und deren Ausprägungen

- Maskenpflicht
- Abstand halten
- Handhygiene
- Durchlüftung
- Testungen
- Schulmodi (präsenz, wechsel, digital)
- Kitamodi (voll, notfall)
- Kapazitätsbeschränkungen
- Registrierung  
- Mobilitätsbeschränkungen zwischen den Gebieten
  - Um die Mobilität zwischen den Gebieten für bestimmte Zielgruppen zu vereinfachen, können individuelle Gebietszuweisungen erfolgen, (z.B. "Home Zone", "Co Zone", "Work Zone" für Pendler).
  - Transitregelung
- Mobilitätsbeschränkungen innerhalb der Gebiete
  - Subclustering: Unterteilung der Gebiete zur besseren Analyse
- Ausgangssperren (Uhrzeit von bis)
- Schließungen (offen, geschlossen)
- Dokumentationsempfehlungen (z.B. Kontakttagebuch)
- ...

#### <ins>Spaltenbeschreibung</ins>

##### ID

Die ID wird sinnvoll frei vergeben.


##### Standardsortierung

Die Standardsortierung wird sinnvoll festgelegt.



## II) Ausprägungen der Maßnahmen innerhalb der Kategorien

### Maskenpflicht [m.maskenpflicht.*]
|ID|Name|Beschreibung|Maßnahmentyp|Grad der Wirksamkeit (Standardsortierung)
|---|---|---|---|---:|
m.maskenpflicht.alltag.empfehlung | Alltagsmasken | | Empfehlung | 21001
m.maskenpflicht.op.empfehlung | OP-Masken | | Empfehlung | 21002
m.maskenpflicht.ffp.empfehlung | FFP-Masken | | Empfehlung | 21003
m.maskenpflicht.alltag.gebot | Alltagsmasken | | Gebot | 22001
m.maskenpflicht.op.gebot | OP-Masken | | Gebot | 22002
m.maskenpflicht.ffp.gebot | FFP-Masken | | Gebot | 22003
... | ||

ToDo

#### <ins>Spaltenbeschreibung</ins>

##### ID

Die ID wird sinnvoll frei vergeben.
Als Prefix wird die ID der übergeordneten Maßnahmenkategorie verwendet.


##### Maßnahmentyp

Mögliche Maßnahmentypen werden zuvor standardisiert und enumeriert:

Information|Empfehlung|Gebot|Verbot|...

##### Grad der Wirksamkeit (Standardsortierung)

Die Standardsortierung erfolgt nach dem zu erwartenden Grad der Wirksamkeit. 
