---
Trefferwürfel: W10
PrimärAttribut:
  - Geschicklichkeit
  - Weisheit
Rettungswürfe:
  - Stärke
  - Geschicklichkeit
Rüstung:
  - Leichte
  - Mittelschwere
  - Schilde
Waffen:
  - Einfache Waffen
  - Kriegswaffen
Icon: "[[Ranger_logo.png]]"
---

> [!infobox]
> # Rangere
> ![[Ranger_logo.png|120]]
> **Trefferwürfel:** 1W10 pro Stufe
> **Primäres Attribut:** Geschicklichkeit & Weisheit
> **Rettungswürfe:** Stärke & Geschicklichkeit
> **Rüstung:** Leichte, Mittelschwere, Schilde
> **Waffen:** Einfache Waffen, Kriegswaffen
> **Fähigkeiten:** _Wähle drei aus:_
> - Athletik
> - Heimlichkeit
> - Mit Tierenumgehen
> - Motiv erkennen
> - Nachforschungen
> - Naturkunde
> - Überlebenskunst
> - Wahrnehmung

![[z_Assets/classes/Ranger/Ranger.png]]

# Ein Waldläufer werden ... 

## Als Charakter der 1. Stufe 

- Du erhältst alle Merkmale in der Tabelle „Hauptmerkmale des Waldläufers“. 
- Du erhältst die Merkmale der 1. Waldläuferstufe, die in der Tabelle „Waldläufermerkmale“ aufgeführt sind. 
## Anfangsausrüstung
Du beginnst mit der folgenden Ausrüstung, zusätzlich zu den Ausrüstungen, die durch Ihren Hintergrund gewährt werden:
- Beschlagene Lederrüstung, Krummsäbel, Kurzschwert, Langbogen, 20 Pfeile, Köcher, Druidischer Fokus (Mistelzweig), Entdeckerausrüstung und7 GM 
- 150 GM

## Als Charakter mit Klassenkombination 

- Du erhältst folgende Merkmale in der Tabelle „Hauptmerkmale des Waldläufers“: Trefferpunkte‑ würfel, Übung im Umgang mit Kriegswaffen, Übung in einer Fertigkeit deiner Wahl von der Fertigkeitenliste des Waldläufers, Vertrautheit mit leichter und mittelschwerer Rüstung sowie mit Schilden. 

- Du erhältst die Merkmale der 1. Waldläuferstufe, die in der Tabelle „Waldläufermerkmale“ aufgeführt sind. Bestimme deine verfügbaren Zauberplätze anhand der Regeln zu Klassenkombinationen unter „Charaktererstellung“. 

# Klassenmerkmale des Waldläufers 
## Unterklassen

```base
views:
  - type: cards
    name: Tabelle
    filters:
      and:
        - file.inFolder("3-Compendium/Klassen/Waldläufer/Unterklassen")
        - file.name != "Unterklassen"
    order:
      - file.name
    markers: bullet
    cardSize: 200
    image: note.Icon
    imageAspectRatio: 1
    indentProperties: true

```


## Klassenmerkmale 
Als Waldläufer erhältst du auf den angegebenen Waldläuferstufen folgende Klassenmerkmale. Diese Merkmale sind in der Tabelle „Waldläufermerkmale“ aufgeführt. 

## Waldläufermerkmale 

| Stufe | Klassenmerkmale                                                                                                                                                                                                                     | Übungsbonus | Erzfeind | Vorbereitete Zauber |  1  |  2  |  3  |  4  |  5  |
|:-----:| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |:-----------:|:--------:|:-------------------:|:---:|:---:|:---:|:---:|:---:|
|   1   | [[3-Compendium/Klassen/Waldläufer/Waldläufer#Erzfeind\|Erzfeind]], [[3-Compendium/Klassen/Waldläufer/Waldläufer#Waffenbeherrschung\|Waffenbeherrschung]], [[3-Compendium/Klassen/Waldläufer/Waldläufer#Zauberwirken\|Zauberwirken]] |     +2      |    2     |          2          |  2  |  −  |  −  |  −  |  −  |
|   2   | [[3-Compendium/Klassen/Waldläufer/Waldläufer#Geschickte Erkundung\|Geschickte Erkundung]], [[3-Compendium/Klassen/Waldläufer/Waldläufer#Kampfstil\|Kampfstil]]                                                                      |     +2      |    2     |          3          |  2  |  −  |  −  |  −  |  −  |
|   3   | Waldläufer­ Unterklasse                                                                                                                                                                                                             |     +2      |    2     |          4          |  3  |  −  |  −  |  −  |  −  |
|   4   | [[3-Compendium/Klassen/Waldläufer/Waldläufer#Attributswerterhöhung\|Attributswerterhöhung]]                                                                                                                                         |     +2      |    2     |          5          |  3  |  −  |  −  |  −  |  −  |
|   5   | [[3-Compendium/Klassen/Waldläufer/Waldläufer#Zusätzlicher Angriff\|Zusätzlicher Angriff]]                                                                                                                                           |     +3      |    3     |          6          |  4  |  2  |  −  |  −  |  −  |
|   6   | [[3-Compendium/Klassen/Waldläufer/Waldläufer#Vagabund\|Vagabund]]                                                                                                                                                                   |     +3      |    3     |          6          |  4  |  2  |  −  |  −  |  −  |
|   7   | Unterklassenmerkmal                                                                                                                                                                                                                 |     +3      |    3     |          7          |  4  |  3  |  −  |  −  |  −  |
|   8   | [[3-Compendium/Klassen/Waldläufer/Waldläufer#Attributswerterhöhung\|Attributswerterhöhung]]                                                                                                                                         |     +3      |    3     |          7          |  4  |  3  |  −  |  −  |  −  |
|   9   | [[3-Compendium/Klassen/Waldläufer/Waldläufer#Expertise\|Expertise]]                                                                                                                                                                 |     +4      |    4     |          9          |  4  |  3  |  2  |  −  |  −  |
|  10   | [[3-Compendium/Klassen/Waldläufer/Waldläufer#Unermüdlichkeit\|Unermüdlichkeit]]                                                                                                                                                     |     +4      |    4     |          9          |  4  |  3  |  2  |  −  |  −  |
|  11   | Unterklassenmerkmal                                                                                                                                                                                                                 |     +4      |    4     |         10          |  4  |  3  |  3  |  −  |  −  |
|  12   | [[3-Compendium/Klassen/Waldläufer/Waldläufer#Attributswerterhöhung\|Attributswerterhöhung]]                                                                                                                                         |     +4      |    4     |         10          |  4  |  3  |  3  |  −  |  −  |
|  13   | [[3-Compendium/Klassen/Waldläufer/Waldläufer#Unermüdlicher Jäger\|Unermüdlicher Jäger]]                                                                                                                                             |     +5      |    5     |         11          |  4  |  3  |  3  |  1  |  −  |
|  14   | [[3-Compendium/Klassen/Waldläufer/Waldläufer#Naturschleier\|Naturschleier]]                                                                                                                                                         |     +5      |    5     |         11          |  4  |  3  |  3  |  1  |  −  |
|  15   | Unterklassenmerkmal                                                                                                                                                                                                                 |     +5      |    5     |         12          |  4  |  3  |  3  |  2  |  −  |
|  16   | [[3-Compendium/Klassen/Waldläufer/Waldläufer#Attributswerterhöhung\|Attributswerterhöhung]]                                                                                                                                         |     +5      |    5     |         12          |  4  |  3  |  3  |  2  |  −  |
|  17   | [[3-Compendium/Klassen/Waldläufer/Waldläufer#Präziser Jäger\|Präziser Jäger]]                                                                                                                                                       |     +6      |    6     |         14          |  4  |  3  |  3  |  3  |  1  |
|  18   | [[3-Compendium/Klassen/Waldläufer/Waldläufer#Wildes Gespür\|Wildes Gespür]]                                                                                                                                                         |     +6      |    6     |         14          |  4  |  3  |  3  |  3  |  1  |
|  19   | [[3-Compendium/Klassen/Waldläufer/Waldläufer#Epische Gabe\|Epische Gabe]]                                                                                                                                                           |     +6      |    6     |         15          |  4  |  3  |  3  |  3  |  2  |
|  20   | [[3-Compendium/Klassen/Waldläufer/Waldläufer#Feindestöter\|Feindestöter]]                                                                                                                                                           |     +6      |    6     |         15          |  4  |  3  |  3  |  3  |  2  |

## Stufe 1
### Erzfeind 

Du hast den Zauber _Zeichen des Jägers_ stets vorbereitet. Du kannst ihn zweimal wirken, ohne einen Zauberplatz zu verbrauchen. Du erhältst alle verbrauchten Anwendungen dieser Fähigkeit nach einer langen Rast zurück. 

Die Anzahl möglicher Anwendungen ohne Zauber‑ platz erhöht sich, wenn du bestimmte Waldläufer‑ stufen erreichst, wie in der Spalte „Erzfeind“ der Tabelle „Waldläufermerkmale“ dargestellt. 

### Waffenbeherrschung 

Deine Vertrautheit mit Waffen erlaubt dir, die Meisterschaftseigenschaften zweier Waffenarten deiner Wahl zu verwenden, sofern du Übung im Umgang mit diesen hast, beispielsweise Langbögen und Kurzschwerter. 

Wann immer du eine lange Rast beendest, kannst du die Art der ausgewählten Waffen ändern. Beispiel: Du könntest beschließen, die Meisterschaftseigenschaft von Krummsäbeln und Langschwertern zu verwenden. 

nicht bei der Anzahl von Zaubern, die du mit diesem Merkmal vorbereiten kannst. Ansonsten zählen diese Zauber jedoch als Waldläuferzauber für dich. 

**_Deine vorbereiteten Zauber ändern:_** Wann immer du eine lange Rast beendest, kannst du einen der Zauber auf deiner Liste durch einen anderen Waldläuferzauber ersetzen, für den du Zauber‑ plätze hast. 

**_Attribut zum Zauberwirken:_** Dein Attribut zum Wirken der Waldläuferzauber ist Weisheit. 

**_Zauberfokus:_** Du kannst einen Druidischen Fokus als Zauberfokus für deine Waldläuferzauber verwenden. 


### Zauberwirken 

Du hast gelernt, die magische Essenz der Natur zu kanalisieren, um Zauber zu wirken. Die Regeln zum Zauberwirken findest du unter „Zauber“. Folgende Informationen erklären, wie du diese Regeln mit den Waldläuferzaubern verwendest, die in der Zauberliste des Waldläufers weiter hinten in dieser Klassenbeschreibung aufgeführt sind. 

**_Zauberplätze:_** Die Tabelle „Waldläufermerkmale“ zeigt, wie viele Zauberplätze dir zum Wirken deiner Zauber ab dem 1. Grad zur Verfügung stehen. Du erhältst alle verbrauchten Zauberplätze nach einer langen Rast zurück. 

**_Vorbereitete Zauber ab dem 1. Grad:_** Du bereitest die Liste der Zauber ab dem 1. Grad vor, die dir mit diesem Merkmal zur Verfügung stehen. Wähle zu Beginn zwei Waldläuferzauber des 1. Grades aus. _Fesselnder Schlag_ und _Wunden heilen_ werden empfohlen. 

Die Anzahl der Zauber auf deiner Liste erhöht sich, wenn du weitere Waldläuferstufen erhältst, wie in der Spalte „Vorbereitete Zauber“ der Tabelle „Waldläufermerkmale“ dargestellt. Wann immer sich diese Anzahl erhöht, wählst du zusätzliche Waldläuferzauber aus, bis die Anzahl von Zaubern auf deiner Liste der Anzahl in der Tabelle „Waldläufer‑ merkmale“ entspricht. Der Grad der ausgewählten Zauber muss dem der verfügbaren Zauberplätze entsprechen. Beispiel: Wenn du ein Waldläufer der 5. Stufe bist, kann deine Liste vorbereiteter Zauber sechs Waldläuferzauber des 1. und 2. Grades in beliebiger Kombination enthalten. 

Wenn ein anderes Waldläufermerkmal dir Zauber gibt, die du stets vorbereitet hast, zählen diese Zauber 

## Stufe 2
### Geschickte Erkundung 

Dank deiner Reisen erhältst du die folgenden Vorzüge: 

**_Expertise:_** Wähle eine deiner Fertigkeiten aus, in denen du geübt bist, aber keine Expertise hast. Du erhältst Expertise in dieser Fertigkeit. 

**_Sprachen:_** Du kennst zwei Sprachen deiner Wahl aus den Sprachentabellen unter „Charakterer‑ stellung“. 

### Kampfstil 

Du erhältst ein Kampfstil‑Talent deiner Wahl (siehe „Talente“). Anstatt eins dieser Talente auszuwählen, kannst du dich auch für die Option unten entscheiden. 

**_Druidischer Krieger:_** Du erlernst zwei Druidenzaubertricks deiner Wahl (siehe Liste der Druidenzauber im Abschnitt zur Druidenklasse). _Göttliche Führung_ und _Sternenfunke_ werden empfohlen. Die ausgewählten Zaubertricks zählen für dich als Waldläuferzauber, und dein Attribut zum Wirken dieser Zauber ist Weisheit. Wann immer du eine Waldläuferstufe erhältst, kannst du einen dieser Zaubertricks durch einen anderen Waldläuferzaubertrick ersetzen. 
## Stufe 3
### Waldläufer-Unterklasse 

Du erhältst eine Waldläufer‑Unterklasse deiner Wahl. Die Unterklasse Jäger wird nach der Beschreibung dieser Klasse erläutert. Unterklassen sind Spezialisierungen, die dir auf bestimmten Waldläuferstufen Merkmale gewähren. Du erhältst für den Rest deiner Laufbahn alle Merkmale deiner Unterklasse, die zu deiner aktuellen Waldläuferstufe oder den niedrigeren Stufen gehören. 
## Stufe 4
### Attributswerterhöhung 

Du erhältst das Talent Attributswerterhöhung (siehe „Talente“) oder ein anderes Talent deiner Wahl, für das du qualifiziert bist. Du erhältst dieses Merkmal auf der 8., 12. und 16. Waldläuferstufe erneut. 
## Stufe 5
### Zusätzlicher Angriff 

Du kannst jetzt zweimal angreifen, wenn du in deinem Zug eine Angriffsaktion ausführst. 

**83** Systemreferenzdokument 5.2.1 
## Stufe 6
### Vagabund 

Deine Bewegungsrate erhöht sich um drei Meter, sofern du keine schwere Rüstung trägst. Außerdem hast du eine Kletterbewegungsrate und eine Schwimmbewegungsrate in Höhe deiner Bewegungsrate. 
## Stufe 9
### Expertise 

Wähle zwei deiner Fertigkeiten aus, in denen du geübt bist, aber keine Expertise hast. Du erhältst Expertise in diesen Fertigkeiten. 
## Stufe 10
### Unermüdlichkeit 

Nun helfen dir Urkräfte bei deinen Reisen und gewähren dir folgende Vorzüge: 

**_Temporäre Trefferpunkte:_** Als magische Aktion kannst du dir eine Anzahl von temporären Trefferpunkten in Höhe von 1W8 plus deinem Weisheitsmodifikator verleihen (mindestens 1). Die Anzahl der möglichen Anwendungen dieser Aktion entspricht deinem Weisheitsmodifikator (mindestens einmal). Du erhältst alle verbrauchten Anwendungen nach einer langen Rast zurück. 

**_Erschöpfung verringern:_** Wann immer du eine kurze Rast beendest, wird deine Erschöpfungsstufe (sofern vorhanden) um 1 verringert. 
## Stufe 13
### Unermüdlicher Jäger 

Deine Konzentration auf den Zauber _Zeichen des Jägers_ wird nicht unterbrochen, wenn du Schaden erleidest. 
## Stufe 14
### Naturschleier 

Du beschwörst Geister der Natur, um dich auf magische Art zu verstecken. Als Bonusaktion kannst du dir bis zum Ende deines nächsten Zugs den Zustand Unsichtbar verleihen. 

Die Anzahl der möglichen Anwendungen dieses Merkmals entspricht deinem Weisheitsmodifikator (mindestens einmal). Du erhältst alle verbrauchten Anwendungen nach einer langen Rast zurück. 
## Stufe 17
### Präziser Jäger 

Du bist bei Angriffswürfen gegen die Kreatur, die aktuell von deinem Zauber _Zeichen des Jägers_ markiert ist, im Vorteil. 
## Stufe 18
### Wildes Gespür 

Deine Verbindung mit den Kräften der Natur gewährt dir Blindsicht mit eine Reichweite von neun Metern. 
## Stufe 19
### Epische Gabe 

Du erhältst ein Epische‑Gabe‑Talent (siehe „Talente“) oder ein anderes Talent deiner Wahl, für das du qualifiziert bist. Gabe des Dimensionsreisens wird empfohlen. 
## Stufe 20
### Feindestöter 

Der Schadenswürfel deines Zaubers _Zeichen des Jägers_ ist jetzt ein W10 statt eines W6. 

# Zauberliste des Waldläufers 

In diesem Abschnitt wird die Zauberliste des Waldläufers vorgestellt. Die Zauber sind nach Zaubergrad und dann alphabetisch sortiert, und die Schule der Magie der jeweiligen Zauber ist aufgeführt. In der Spalte „Besonderheit“ bedeutet _K_ , dass der Zauber Konzentration erfordert, _R_ bedeutet, dass es sich um ein Ritual handelt, und _M_ bedeutet, dass eine bestimmte Materialkomponente erforderlich ist. 

## Waldläuferzauber des 1. Grades 

|Zauber|Schule|Beson-derheit|
|---|---|---|
|_Alarm_|Bannmagie|R|
|_Fesselnder Schlag_|Beschwörungsmagie|K|
|_Gift und Krankheit__entdecken_|Erkenntnismagie|K, R|
|_Gute Beeren_|Beschwörungsmagie|−|
|_Lange Schritte_|Verwandlungsmagie|−|
|_Magie entdecken_|Erkenntnismagie|K, R|
|_Mit Tieren sprechen_|Erkenntnismagie|R|
|_Nebelwolke_|Beschwörungsmagie|K|
|_Springen_|Verwandlungsmagie|−|
|_Tierfreundschaft_|Verzauberungsmagie|−|
|_Verstricken_|Beschwörungsmagie|K|
|_Wunden heilen_|Bannmagie|−|
|_Zeichen des Jägers_|Erkenntnismagie|K|



## Waldläuferzauber des 2. Grades 

|Zauber|Schule|Beson-derheit|
|---|---|---|
|_Attribut verbessern_|Verwandlungsmagie|K|
|_Beistand_|Bannmagie|−|
|_Dornenwuchs_|Verwandlungsmagie|K|
|_Dunkelsicht_|Verwandlungsmagie|−|
|_Fallen finden_|Erkenntnismagie|−|
|_Gegenstand aufspüren_|Erkenntnismagie|K|
|_Magische Waffe_|Verwandlungsmagie|−|
|_Rindenhaut_|Verwandlungsmagie|−|
|_Schutz vor Gift_|Bannmagie|−|
|_Schwache Genesung_|Bannmagie|−|
|_Spurloses Gehen_|Bannmagie|K|
|_Stille_|Illusionsmagie|K, R|
|_Tierbote_|Verzauberungsmagie|R|
|_Tiere oder Pflanzen__aufspüren_|Erkenntnismagie|R|
|_Windstoß_|Hervorrufungsmagie|K|


## Waldläuferzauber des 3. Grades 

|Zauber|Schule|Beson-derheit|
|---|---|---|
|_Magie bannen_|Bannmagie|−|
|_Mit Pflanzen sprechen_|Verwandlungsmagie|−|
|_Mit Stein verschmelzen_|Verwandlungsmagie|R|
|_Pflanzenwachstum_|Verwandlungsmagie|−|
|_Schutz vor Energie_|Bannmagie|K|
|_Tageslicht_|Hervorrufungsmagie|−|
|_Tiere beschwören_|Beschwörungsmagie|K|
|_Unauffindbarkeit_|Bannmagie|M|
|_Wasser atmen_|Verwandlungsmagie|R|
|_Wasserwandeln_|Verwandlungsmagie|R|
|_Wiederbeleben_|Nekromantie|M|
|_Windwall_|Hervorrufungsmagie|K|



## Waldläuferzauber des 4. Grades 

|Zauber|Schule|Beson-derheit|
|---|---|---|
|_Bewegungsfreiheit_|Bannmagie|−|
|_Kreatur aufspüren_|Erkenntnismagie|K|
|_Steinhaut_|Verwandlungsmagie|K, M|
|_Tier beherrschen_|Verzauberungsmagie|K|
|_Wesen des Waldes__beschwören_|Beschwörungsmagie|K|



## Waldläuferzauber des 5. Grades 

|Zauber|Schule|Beson-derheit|
|---|---|---|
|_Baumwandeln_|Beschwörungsmagie|K|
|_Einswerden mit der_|Erkenntnismagie|R|
|_Natur_|||
|_Vollständige Genesung_|Bannmagie|M|

