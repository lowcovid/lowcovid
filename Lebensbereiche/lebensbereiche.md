
# Lebensbereiche

## I) Übergeordnete Lebensbereiche

|ID|Name|Beschreibung|Standardsortierung
|---|---|---|---:|
l.privat | Privat | | 10000
l.unterwegs | Unterwegs | | 20000
l.arbeit | Arbeit | | 30000
... | | |

ToDo: mögliche weitere Lebensbereiche

- Privat zu Hause
- Unterwegs
  - Auto
  - Öffentliche Verkehrsmittel
  - Bahn Fernverkehr
  - Fernbus
  - Flugzeug
  - Fähre
- Arbeit
- Kita
- Grundschule
- Weiterführende Schule
- Einkaufen
- Gastronomie
- Übernachtungsgewerbe
- Reisen
- Tagesausflüge
- Breitensport (in der Gruppe), Indoor vs Outdoor
- Individualsport, Indoor vs Outdoor
- Spitzensport, Indoor vs Outdoor
- Kultur und Events (< 1000 Zuschauer)
- Großereignisse (> 1000 Zuschauer)
- Religion
- ...


#### <ins>Spaltenbeschreibung</ins>

##### ID

Die ID wird sinnvoll frei vergeben.

##### Standardsortierung

Standardmäßig wird nach den wichtigsten Lebensbereichen sortiert, die durchschnittlich am meisten Zeit in Anspruch nehmen.


## II) Untergliederung der Lebensbereiche

### Privat [l.privat.*]

_-keine Untergliederung-_



### Unterwegs [l.unterwegs.*]
|ID|Name|Beschreibung|Standardsortierung
|---|---|---|---:|
l.unterwegs.auto | Auto | | 21000
l.unterwegs.oepnv | Öffentliche Verkehrsmittel | | 21001
... | ||

ToDo


#### <ins>Spaltenbeschreibung</ins>

##### ID

Die ID wird sinnvoll frei vergeben. 
Als Prefix wird die ID des übergeordneten Lebensbereichs verwendet.


##### Standardsortierung

Die Standardsortierung wird sinnvoll festgelegt.

