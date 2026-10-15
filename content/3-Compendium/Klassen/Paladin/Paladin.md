---
Trefferwürfel: W10
PrimärAttribut:
  - Stärke
  - Charisma
Rettungswürfe:
  - Weisheit
  - Charisma
Rüstung:
  - Leichte
  - Mittelschwere
  - Schwere
  - Schilde
Waffen:
  - Einfache Waffen
  - Kriegswaffen
Icon: "[[Paladin_logo.png]]"
---

> [!infobox]
> # Paladine
> ![[Paladin_logo.png|120]]
> **Trefferwürfel:** 1W10 pro Stufe
> **Primäres Attribut:** Stärke & Charisma
> **Rettungswürfe:** Weisheit & Charisma
> **Rüstung:** Leichte, Mittelschwere, Schwere, Schilde
> **Waffen:** Einfache Waffen, Kriegswaffen
> **Fähigkeiten:** _Wähle zwei aus:_
> - Athletik
> - Einschüchtern
> - Heilkunde
> - Motiv erkennen
> - Religion
> - Überzeugen

![[z_Assets/classes/Paladin/Paladin.png]]

# Ein Paladin werden ... 

## Als Charakter der 1. Stufe 

- Du erhältst alle Merkmale in der Tabelle „Hauptmerkmale des Paladins“. 
- Du erhältst die Merkmale der 1. Paladinstufe, die in der Tabelle „Paladinmerkmale“ aufgeführt sind. 
## Anfangsausrüstung
Du beginnst mit der folgenden Ausrüstung, zusätzlich zu den Ausrüstungen, die durch Ihren Hintergrund gewährt werden:
- Kettenpanzer, Schild, Langschwert, sechs Wurfspeere, Heiliges Symbol, Priesterausrüstung und 9 GM 
- 150 GM
## Als Charakter mit Klassenkombination 

- Du erhältst folgende Merkmale in der Tabelle „Hauptmerkmale des Paladins“: Trefferpunkte‑ würfel, Übung im Umgang mit Kriegswaffen, Vertrautheit mit leichter und mittelschwerer Rüstung sowie mit Schilden. 

- Du erhältst die Merkmale der 1. Paladinstufe, die in der Tabelle „Paladinmerkmale“ aufgeführt sind. Bestimme deine verfügbaren Zauberplätze anhand der Regeln zu Klassenkombinationen unter „Charaktererstellung“. 

# Klassenmerkmale des Paladins 
## Unterklassen

```base
views:
  - type: cards
    name: Tabelle
    filters:
      and:
        - file.inFolder("3-Compendium/Klassen/Paladin/Unterklassen")
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
Als Paladin erhältst du auf den angegebenen Paladinstufen folgende Klassenmerkmale. Diese Merkmale sind in der Tabelle „Paladinmerkmale“ aufgeführt. 

## Paladinmerkmale 

| Stufe | Klassenmerkmale                                                                                                                                                                                                           | Übungsbonus | Göttliche Macht | Vorbereitete Zauber |  1  |  2  |  3  |  4  |  5  |
|:-----:| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |:-----------:|:---------------:|:-------------------:|:---:|:---:|:---:|:---:|:---:|
|   1   | [[3-Compendium/Klassen/Paladin/Paladin#Handauflegen\|Handauflegen]], [[3-Compendium/Klassen/Paladin/Paladin#Waffenbeherrschung\|Waffenbeherrschung]], [[3-Compendium/Klassen/Paladin/Paladin#Zauberwirken\|Zauberwirken]] |     +2      |        −        |          2          |  2  |  −  |  −  |  −  |  −  |
|   2   | [[3-Compendium/Klassen/Paladin/Paladin#Kampfstil\|Kampfstil]], [[3-Compendium/Klassen/Paladin/Paladin#Paladin Niederstrecken\|Paladin Niederstrecken]]                                                                    |     +2      |        −        |          3          |  2  |  −  |  −  |  −  |  −  |
|   3   | [[3-Compendium/Klassen/Paladin/Paladin#Göttliche Macht fokussieren\|Göttliche Macht fokussieren]], Paladin­ Unterklasse                                                                                                   |     +2      |        2        |          4          |  3  |  −  |  −  |  −  |  −  |
|   4   | [[3-Compendium/Klassen/Paladin/Paladin#Attributswerterhöhung\|Attributswerterhöhung]]                                                                                                                                     |     +2      |        2        |          5          |  3  |  −  |  −  |  −  |  −  |
|   5   | [[3-Compendium/Klassen/Paladin/Paladin#Treues Reittier\|Treues Reittier]], [[3-Compendium/Klassen/Paladin/Paladin#Zusätzlicher Angriff\|Zusätzlicher Angriff]]                                                            |     +3      |        2        |          6          |  4  |  2  |  −  |  −  |  −  |
|   6   | [[3-Compendium/Klassen/Paladin/Paladin#Aura des Schutzes\|Aura des Schutzes]]                                                                                                                                             |     +3      |        2        |          6          |  4  |  2  |  −  |  −  |  −  |
|   7   | Unterklassenmerkmal                                                                                                                                                                                                       |     +3      |        2        |          7          |  4  |  3  |  −  |  −  |  −  |
|   8   | [[3-Compendium/Klassen/Paladin/Paladin#Attributswerterhöhung\|Attributswerterhöhung]]                                                                                                                                     |     +3      |        2        |          7          |  4  |  3  |  −  |  −  |  −  |
|   9   | [[3-Compendium/Klassen/Paladin/Paladin#Gegner verdammen\|Gegner verdammen]]                                                                                                                                               |     +4      |        2        |          9          |  4  |  3  |  2  |  −  |  −  |
|  10   | [[3-Compendium/Klassen/Paladin/Paladin#Aura der Tapferkeit\|Aura der Tapferkeit]]                                                                                                                                         |     +4      |        2        |          9          |  4  |  3  |  2  |  −  |  −  |
|  11   | [[3-Compendium/Klassen/Paladin/Paladin#Gleißende Schläge\|Gleißende Schläge]]                                                                                                                                             |     +4      |        3        |         10          |  4  |  3  |  3  |  −  |  −  |
|  12   | [[3-Compendium/Klassen/Paladin/Paladin#Attributswerterhöhung\|Attributswerterhöhung]]                                                                                                                                     |     +4      |        3        |         10          |  4  |  3  |  3  |  −  |  −  |
|  13   | −                                                                                                                                                                                                                         |     +5      |        3        |         11          |  4  |  3  |  3  |  1  |  −  |
|  14   | [[3-Compendium/Klassen/Paladin/Paladin#Erquickende Berührung\|Erquickende Berührung]]                                                                                                                                     |     +5      |        3        |         11          |  4  |  3  |  3  |  1  |  −  |
|  15   | Unterklassenmerkmal                                                                                                                                                                                                       |     +5      |        3        |         12          |  4  |  3  |  3  |  2  |  −  |
|  16   | [[3-Compendium/Klassen/Paladin/Paladin#Attributswerterhöhung\|Attributswerterhöhung]]                                                                                                                                     |     +5      |        3        |         12          |  4  |  3  |  3  |  2  |  −  |
|  17   | −                                                                                                                                                                                                                         |     +6      |        3        |         14          |  4  |  3  |  3  |  3  |  1  |
|  18   | [[3-Compendium/Klassen/Paladin/Paladin#Aura-Ausdehnung\|Aura-Ausdehnung]]                                                                                                                                                 |     +6      |        3        |         14          |  4  |  3  |  3  |  3  |  1  |
|  19   | [[3-Compendium/Klassen/Paladin/Paladin#Epische Gabe\|Epische Gabe]]                                                                                                                                                       |     +6      |        3        |         15          |  4  |  3  |  3  |  3  |  2  |
|  20   | Unterklassenmerkmal                                                                                                                                                                                                       |     +6      |        3        |         15          |  4  |  3  |  3  |  3  |  2  |

## Stufe 1
### Handauflegen 

Deine gesegnete Berührung kann Wunden heilen. Du hast einen Vorrat an Heilkraft, der nach einer langen Rast aufgefüllt wird. Mit diesem Vorrat kannst du das Fünffache deiner Paladinstufe an Trefferpunkten wiederherstellen. 

Als Bonusaktion kannst du eine Kreatur (auch dich selbst) berühren und Kraft aus deinem Vorrat an Heilkraft ziehen, um bei der Kreatur höchstens so viele Trefferpunkte wiederherzustellen, wie noch im Vorrat vorhanden sind. 

Du kannst auch 5 Trefferpunkte aus dem Vorrat an Heilkraft verbrauchen, um den Zustand Vergiftet von der Kreatur zu entfernen. Diese Punkte werden nicht als Trefferpunkte der Kreatur wiederhergestellt. 

### Waffenbeherrschung 

Deine Vertrautheit mit Waffen erlaubt dir, die Meisterschaftseigenschaften zweier Waffenarten deiner Wahl zu verwenden, sofern du Übung im Umgang mit diesen hast, beispielsweise Langschwerter und Wurfspeere. 

Wann immer du eine lange Rast beendest, kannst du die Art der ausgewählten Waffen ändern. Beispiel: Du könntest beschließen, die Meisterschaftseigen‑ schaft von HellePaladinen und Flegeln zu verwenden. 

### Zauberwirken 

Du hast gelernt, durch Gebete und Meditation Zauber zu wirken. Die Regeln zum Zauberwirken findest du unter „Zauber“. Folgende Informationen erklären, wie du diese Regeln mit den Paladin‑ zaubern verwendest, die in der Zauberliste des Paladins weiter hinten in dieser Klassenbeschrei‑ bung aufgeführt sind. 

**_Zauberplätze:_** Die Tabelle „Paladinmerkmale“ zeigt, wie viele Zauberplätze dir zum Wirken deiner Zauber ab dem 1. Grad zur Verfügung stehen. Du erhältst alle verbrauchten Zauberplätze nach einer langen Rast zurück. 

**_Vorbereitete Zauber ab dem 1. Grad:_** Du bereitest die Liste der Zauber ab dem 1. Grad vor, die dir mit diesem Merkmal zur Verfügung stehen. Wähle zu Beginn zwei Paladinzauber des 1. Grades aus. _Heldenmut_ und _Sengendes Niederstrecken_ werden empfohlen. 

Die Anzahl der Zauber auf deiner Liste erhöht sich, wenn du weitere Paladinstufen erhältst, wie in der Spalte „Vorbereitete Zauber“ der Tabelle „Paladinmerkmale“ dargestellt. Wann immer sich diese Anzahl erhöht, wählst du zusätzliche Paladin‑ zauber aus, bis die Anzahl von Zaubern auf deiner Liste der Anzahl in der Tabelle „Paladinmerkmale“ entspricht. Der Grad der ausgewählten Zauber muss dem der verfügbaren Zauberplätze entsprechen. Beispiel: Wenn du ein Paladin der 5. Stufe bist, kann deine Liste vorbereiteter Zauber sechs Paladinzauber des 1. und 2. Grades in beliebiger Kombination enthalten. 

Wenn ein anderes Paladinmerkmal dir Zauber gibt, die du stets vorbereitet hast, zählen diese Zauber nicht bei der Anzahl von Zaubern, die du mit diesem Merkmal vorbereiten kannst. Ansonsten zählen diese Zauber jedoch als Paladinzauber für dich. 

**_Deine vorbereiteten Zauber ändern:_** Wann immer du eine lange Rast beendest, kannst du einen der Zauber auf deiner Liste durch einen anderen Paladinzauber ersetzen, für den du Zauberplätze hast. 

**_Attribut zum Zauberwirken:_** Dein Attribut zum Wirken der Paladinzauber ist Charisma. 

**_Zauberfokus:_** Du kannst ein heiliges Symbol als Zauberfokus für deine Paladinzauber verwenden. 
## Stufe 2
### Kampfstil 

Du erhältst ein Kampfstil‑Talent deiner Wahl (Talente siehe „Talente“). Anstatt eins dieser Talente auszuwählen, kannst du dich auch für die Option unten entscheiden. 

**_Gesegneter Krieger:_** Du erlernst zwei Kleriker‑ zaubertricks deiner Wahl (eine Liste der Kleriker‑ zauber findest du im Abschnitt zur Klerikerklasse). _Göttliche Führung_ und _Heilige Flamme_ werden empfohlen. Die ausgewählten Zaubertricks zählen für dich als Paladinzauber, und dein Attribut zum Wirken dieser Zauber ist Charisma. Wann immer du eine Paladinstufe erhältst, kannst du einen dieser Zaubertricks durch einen anderen Kleriker‑ zaubertrick ersetzen. 

### Paladin Niederstrecken

Du hast den Zauber _Göttliches Niederstrecken_ stets vorbereitet. Du kannst diesen Zauber wirken, ohne einen Zauberplatz zu verbrauchen, kannst ihn aber erst nach einer langen Rast erneut auf diese Art wirken. 
## Stufe 3
### Göttliche Macht fokussieren 

Du kannst göttliche Energie direkt von den Äußeren Ebenen kanalisieren, um magische Effekte zu wirken. Du beginnst mit einem solchen Effekt: Göttliches Gespür (unten beschrieben). Andere Paladinmerkmale verleihen dir zusätzliche Effektoptionen bei Göttliche Macht fokussieren. Wann immer du Göttliche Macht fokussieren dieser Klasse einsetzt, wählst du aus, welchen Effekt dieser Klasse du bewirkst. 

Du kannst Göttliche Macht fokussieren dieser Klasse zweimal anwenden. Wenn du eine kurze Rast beendest, erhältst du eine verbrauchte Anwendung zurück. Du erhältst alle verbrauchten Anwendungen nach einer langen Rast zurück. Du erhältst eine zusätzliche Anwendung, wenn du die 11. Paladinstufe erreichst. 

Wenn ein Effekt von Göttliche Macht fokussieren einen Rettungswurf erfordert, entspricht der SG dem Zauberrettungswurf‑SG des Merkmals Zauberwirken dieser Klasse. 

**_Göttliches Gespür:_** Als Bonusaktion kannst du dein Bewusstsein öffnen, um celestische Wesen, Unholde und Untote zu erkennen. In den nächsten zehn Minuten – oder bis du kampfunfähig wirst – kennst du den Ort von jeder Kreatur dieser Typen im Abstand von bis zu 18 Metern von dir, und du erkennst den jeweiligen Kreaturentyp. Innerhalb der gleichen Reichweite erkennst du auch Orte und Gegenstände, die geweiht oder entweiht wurden, als würdest du den Zauber _Weihen_ wirken. 

### Heilige Waffe 

Wenn du die Angriffsaktion ausführst, kannst du eine Anwendung von Göttliche Macht fokussieren verbrauchen, um eine Nahkampfwaffe, die du hältst, mit positiver Energie zu versehen. Deinen Angriffswürfen mit dieser Waffe fügst du zehn Minuten lang – oder bis du dieses Merkmal erneut einsetzt – deinen Charismamodifikator hinzu (mindestens +1), und bei jedem Treffer mit der Waffe bewirkst du ihre normale Schadensart oder gleißenden Schaden. 

Außerdem spendet die Waffe in einem Radius von sechs Metern helles Licht und in einem Radius von weiteren sechs Metern dämmriges Licht. 

Du kannst diesen Effekt vorzeitig beenden (keine Aktion erforderlich). Der Effekt endet auch, wenn du die Waffe nicht trägst. 

### Schwurzauber der Hingabe 

Dank der Magie deines Schwurs hast du stets bestimmte Zauber vorbereitet. Wenn du die in der Tabelle „Schwurzauber der Hingabe“ angegebenen Paladinstufen erreichst, hast du fortan stets die aufgeführten Zauber vorbereitet. 

### Paladin-Unterklasse 

Du erhältst eine Paladin‑Unterklasse deiner Wahl. Die Unterklasse Schwur der Hingabe wird nach der Beschreibung dieser Klasse erläutert. Unterklassen sind Spezialisierungen, die dir auf bestimmten Paladinstufen Merkmale gewähren. Du erhältst für den Rest deiner Laufbahn alle Merkmale deiner Unterklasse, die zu deiner aktuellen Paladinstufe oder den niedrigeren Stufen gehören. 

#### deinen schwur brechen 

Paladine versuchen, sich nach den höchsten Verhaltensstandards zu richten, doch selbst die Tugendhaftesten können scheitern. Manchmal werden Paladine ihren Schwüren nicht gerecht. 

Wenn ein Paladin seinen Schwur gebrochen hat, ersucht er üblicherweise um Absolution, leistet als Zeichen der Buße eine Nachtwache oder legt eine Fastenzeit ein. Nach einem Vergebungsritual ist dem Paladin ein Neuanfang möglich. 

Bricht dein Paladin seinen Schwur allerdings reuelos, so sprich mit deinem SL. Dein Paladin sollte wahrscheinlich eine geeignetere Unterklasse auswählen oder sogar seine Klasse wechseln. 

## Stufe 4
### Attributswerterhöhung 

Du erhältst das Talent Attributswerterhöhung (siehe „Talente“) oder ein anderes Talent deiner Wahl, für das du qualifiziert bist. Du erhältst dieses Merkmal auf der 8., 12. und 16. Paladinstufe erneut. 
## Stufe 5
### Zusätzlicher Angriff 

Du kannst jetzt zweimal angreifen, wenn du in deinem Zug eine Angriffsaktion ausführst. 

### Treues Reittier 

Du kannst ein außerweltliches Reittier herbeirufen. Du hast den Zauber _Reittier finden_ stets vorbereitet. 

Du kannst den Zauber auch einmal wirken, ohne einen Zauberplatz zu verbrauchen. Diese Fähigkeit erhältst du nach einer langen Rast zurück. 
## Stufe 6
### Aura des Schutzes 

Du hast eine nicht sichtbare beschützende Aura in einer Ausströmung von drei Metern, die von dir ausgeht. Die Aura ist inaktiv, solange du kampfunfähig bist. 

Du und deine Verbündeten in der Aura erhaltet einen Bonus in Höhe deines Charismamodifikators (mindestens +1) auf Rettungswürfe. 

Wenn ein anderer Paladin anwesend ist, kann eine Kreatur nur von jeweils einer Aura des Schutzes (nach ihrer Wahl) profitieren. 
## Stufe 9
### Gegner verdammen 

Als magische Aktion kannst du eine Anwendung von Göttliche Macht fokussieren dieser Klasse verbrauchen, um Gegnern gehörige Ehrfurcht einzuflößen. Wenn du dein heiliges Symbol oder deine heilige Waffe präsentierst, kannst du auf eine Anzahl von Kreaturen in Höhe deines Charisma modifikators (mindestens eine Kreatur) im Abstand von bis zu 18 Metern von dir zielen, die du sehen kannst. Jedes Ziel muss einen Weisheitsrettungswurf bestehen, oder es ist eine Minute lang – oder bis es Schaden erleidet – verängstigt. Solange es auf diese Art verängstigt ist, kann es in seinen Zügen nur eine der folgenden Handlungen ausführen: sich bewegen, eine Aktion ausführen, eine Bonusaktion ausführen. 
## Stufe 10
### Aura der Tapferkeit 

Du und deine Verbündeten innerhalb deiner Aura des Schutzes seid gegen den Zustand Verängstigt immun. Wenn ein verängstigter Verbündeter die Aura betritt, hat der Zustand keine Wirkung auf ihn, solange er sich innerhalb der Aura aufhält. 
## Stufe 11
### Gleißende Schläge 

Deine Schläge haben jetzt übernatürliche Macht. Wenn du ein Ziel mit einer Nahkampfwaffe oder einem waffenlosen Angriff triffst, erleidet es zusätzlich 1W8 gleißenden Schaden. 
## Stufe 14
### Erquickende Berührung 

Wenn du Handauflegen auf eine Kreatur wirkst, kannst du zusätzlich mindestens einen der folgenden Zustände von der Kreatur entfernen: Betäubt, Bezaubert, Blind, Gelähmt, Taub oder Verängstigt. Du musst für jeden dieser Zustände, den du entfernen willst, 5 Trefferpunkte aus dem Vorrat an Heilkraft von Handauflegen verbrauchen. Diese Punkte werden nicht als Trefferpunkte der Kreatur wiederhergestellt. 
## Stufe 18
### Aura-Ausdehnung 

Deine Aura des Schutzes ist nun eine Ausströmung von neun Metern. 
## Stufe 19
### Epische Gabe 

Du erhältst ein Epische‑Gabe‑Talent (siehe „Talente“) oder ein anderes Talent deiner Wahl, für das du qualifiziert bist. Gabe des Wahren Blicks wird empfohlen. 

# Zauberliste des Paladins 

In diesem Abschnitt wird die Zauberliste des Paladins vorgestellt. Die Zauber sind nach Zaubergrad und dann alphabetisch sortiert, und die Schule der Magie der jeweiligen Zauber ist aufgeführt. In der Spalte „Besonderheit“ bedeutet _K_ , dass der Zauber Konzentration erfordert, _R_ bedeutet, dass es sich um ein Ritual handelt, und _M_ bedeutet, dass eine bestimmte Materialkomponente erforderlich ist. 

## Paladinzauber des 1. Grades 

|Zauber|Schule|Beson-derheit|
|---|---|---|
|_Befehl_|Verzauberungsmagie|−|
|_Gift und Krankheit__entdecken_|Erkenntnismagie|K, R|
|_Göttliche Gunst_|Verwandlungsmagie|−|
|_Göttliches__Niederstrecken_|Hervorrufungsmagie|−|
|_Gutes und Böses__entdecken_|Erkenntnismagie|K|
|_Heldenmut_|Verzauberungsmagie|K|
|_Magie entdecken_|Erkenntnismagie|K, R|
|_Nahrung und Wasser__reinigen_|Verwandlungsmagie|R|
|_Schild des Glaubens_|Bannmagie|K|
|_Schutz vor Gut und Böse_|Bannmagie|K, M|
|_Segnen_|Verzauberungsmagie|K, M|
|_Sengendes__Niederstrecken_|Hervorrufungsmagie|−|
|_Wunden heilen_|Bannmagie|−|



## Paladinzauber des 2. Grades 

| Zauber             | Schule         | Beson-derheit |
| ---------------------- | ------------------ | ------------------------- |
| _Beistand_             | Bannmagie          | −                         |
| _Gebet der Heilung_    | Bannmagie          | −                         |
| _Gegenstand aufspüren_ | Erkenntnismagie    | K                         |
| _Magische Waffe_       | Verwandlungsmagie  | −                         |
| _Reittier finden_      | Beschwörungsmagie  | −                         |
| _Sanfte Ruhe_          | Nekromantie        | R, M                      |
| _Schutz vor Gift_      | Bannmagie          | −                         |
| _Schützendes Band_     | Bannmagie          | M                         |
| _Schwache Genesung_    | Bannmagie          | −                         |
| _Strahlendes_          | Verwandlungsmagie  | K                         |
| _Niederstrecken_       |                    |                           |
| _Zone der Wahrheit_    | Verzauberungsmagie | −                         |



## Paladinzauber des 3. Grades 

|Zauber|Schule|Beson-derheit|
|---|---|---|
|_Fluch brechen_|Bannmagie|−|
|_Magie bannen_|Bannmagie|−|
|_Nahrung und Wasser__erschaffen_|Beschwörungsmagie|−|
|_Schutzkreis_|Bannmagie|M|
|_Tageslicht_|Hervorrufungsmagie|−|
|_Wiederbeleben_|Nekromantie|M|



## Paladinzauber des 4. Grades 

|Zauber|Schule|Beson-derheit|
|---|---|---|
|_Aura des Lebens_|Bannmagie|K|
|_Kreatur aufspüren_|Erkenntnismagie|K|
|_Todesschutz_|Bannmagie|−|
|_Verbannung_|Bannmagie|K|


## Paladinzauber des 5. Grades 

|Zauber|Schule|Beson-derheit|
|---|---|---|
|_Geas_|Verzauberungsmagie|−|
|_Gutes und Böses bannen_|Bannmagie|K|
|_Tote erwecken_|Nekromantie|M|
|_Vollständige Genesung_|Bannmagie|M|
