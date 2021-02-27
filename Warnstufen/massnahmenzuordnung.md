


# Zurordnung von Maßnahmen zu Warnstufen und Lebensbereichen


## 1) Zuordnung zur Warnstufe

|ID|Warnstufe|Maßnahme_ID|Lebensbereich_ID| Version_ID|
|---|---|---|---|---:|
10001 | 1 | m.maskenpflicht.alltag.gebot | l.unterwegs.oepnv | 2021.02.2
... |

ToDo


#### <ins>Spaltenbeschreibung</ins>

##### ID

Die ID wird sinnvoll frei vergeben.

##### Warnstufe

Warnstufe oder Warnstufe_ID als Zahl.

##### Maßnahme_ID

ID der zugeordneten Maßnahme gemäß Spezifikation.

##### Lebensbereich_ID

ID des betroffenen Lebensbereiches gemäß Spezifikation.

##### Version_ID

ID der Version einer #lowcovid Strategie für diese Zuordnung.



## 2) Sonderfall: Bedingte Maßnahmen für Gebiete mit besonderen Charakteristiken

Optionale zusätzliche Gebietsparameterbedingung(en) für zugeordneten Maßnahmen, z.B. für 

- Touristische Gebiete
- Grenzgebiete
- Pendlergebiete

<ins>_Beispiel einer bedingten Zuordnung_</ins>

|ID|Warnstufe|Maßnahme_ID|Lebensbereich_ID| Gebietsparameterbedingung (optional) | Version_ID|
|---|---|---|---|---|---:|
10001 | 1 | m.maskenpflicht.alltag.pflicht | l.unterwegs.auto | [gp.pendlergebiet == true] | 2021.02.2
... |

ToDo


#### <ins>Spaltenbeschreibung</ins>

zusätzliche Spalte:

##### Gebietsparameterbedingung

Formulierung der zusätzlichen gebietsparameterbasierten Bedingung(en) mittels geeigneter Syntax. 
ToDo



## 3) Sonderfall: Personalisierte Maßnahmen

Optionale zusätzliche Personenparameterbedingung(en) für zugeordneten Maßnahmen, z.B. zur

- Berücksichtigung des Impfstatus
- Berücksichtigung des Wohnsitzes

<ins>_Beispiel einer bedingten Zuordnung_</ins>

|ID|Warnstufe|Maßnahme_ID|Lebensbereich_ID| Personenparameterbedingung (optional) | Version_ID|
|---|---|---|---|---|---:|
10001 | 1 | m.maskenpflicht.alltag.pflicht | l.unterwegs.auto | [my.impfstatus.vollstaendig != true] | 2021.02.2
... |

ToDo


#### <ins>Spaltenbeschreibung</ins>

zusätzliche Spalte:

##### Personenparameterbedingung

Formulierung der zusätzlichen parameterbasierten Bedingung(en) mittels geeigneter Syntax.
ToDo
