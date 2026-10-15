---
Trefferwürfel: W8
PrimärAttribut:
  - Weisheit
Rettungswürfe:
  - Weisheit
  - Charisma
Rüstung:
  - Leichte
  - Mittelschwere
  - Schilde
Waffen:
  - Einfache Waffen
Icon: "[[Cleric_logo.png]]"
---

> [!infobox]
> # Clerice
> ![[Cleric_logo.png|120]]
> **Trefferwürfel:** 1W8 pro Stufe
> **Primäres Attribut:** Weisheit
> **Rettungswürfe:** Weisheit & Charisma
> **Rüstung:** Leichte, Mittelschwere, Schilde
> **Waffen:** Einfache Waffen
> **Fähigkeiten:** _Wähle zwei aus:_
> - Geschichte
> - Heilkunde
> - Motiv erkennen
> - Religion
> - Überzeugen

![[z_Assets/classes/Cleric/Cleric.png]]

# Ein Kleriker werden ... 

## Als Charakter der 1. Stufe 

- Du erhältst alle Merkmale in der Tabelle „Hauptmerkmale des Klerikers“. 
- Du erhältst die Merkmale der 1. Klerikerstufe, die in der Tabelle „Klerikermerkmale“ aufgeführt sind. 
## Anfangsausrüstung
Du beginnst mit der folgenden Ausrüstung, zusätzlich zu den Ausrüstungen, die durch Ihren Hintergrund gewährt werden:
- Kettenhemd, Schild, Streitkolben, Heiliges Symbol, Priesterausrüstung und 7 GM
- 110 GM
## Als Charakter mit Klassenkombination 

- Du erhältst folgende Merkmale in der Tabelle „Hauptmerkmale des Klerikers“: Trefferpunkte‑ würfel, Vertrautheit mit leichter und mittelschwerer Rüstung sowie mit Schilden. 
- Du erhältst die Merkmale der 1. Klerikerstufe, die in der Tabelle „Klerikermerkmale“ aufgeführt sind. Bestimme deine verfügbaren Zauberplätze anhand der Regeln zu Klassenkombinationen unter „Charaktererstellung“. 

# Klassenmerkmale des Klerikers 
## Unterklassen

```base
views:
  - type: cards
    name: Tabelle
    filters:
      and:
        - file.inFolder("3-Compendium/Klassen/Kleriker/Unterklassen")
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
Als Kleriker erhältst du auf den angegebenen Klerikerstufen folgende Klassenmerkmale. Diese Merkmale sind in der Tabelle „Klerikermerkmale“ aufgeführt. 

| Stufe | Klassenmerkmale                                                                                                                                        | Übungsbonus | Göttliche Macht | Zaubertricks | Vorbereitete Zauber | 1   |  2  |  3  |  4  |  5  |  6  |  7  |  8  |  9  |
|:-----:| ------------------------------------------------------------------------------------------------------------------------------------------------------ |:-----------:|:---------------:|:------------:|:-------------------:| --- |:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|   1   | [[3-Compendium/Klassen/Kleriker/Kleriker#Zauberwirken\|Zauberwirken]], [[3-Compendium/Klassen/Kleriker/Kleriker#Göttliche Ordnung\|Göttliche Ordnung]] |     +2      |        −        |      3       |          4          | 2   |  −  |  −  |  −  |  −  |  −  |  −  |  −  |  -  |
|   2   | [[3-Compendium/Klassen/Kleriker/Kleriker#Göttliche Macht fokussieren\|Göttliche Macht fokussieren]]                                                    |     +2      |        2        |      3       |          5          | 3   |  −  |  −  |  −  |  −  |  −  |  −  |  −  |  -  |
|   3   | Kleriker­Unterklasse                                                                                                                                   |     +2      |        2        |      3       |          6          | 4   |  2  |  −  |  −  |  −  |  −  |  −  |  −  |  -  |
|   4   | [[3-Compendium/Klassen/Kleriker/Kleriker#Attributswerterhöhung\|Attributswerterhöhung]]                                                                |     +2      |        2        |      4       |          7          | 4   |  3  |  −  |  −  |  −  |  −  |  −  |  −  |  -  |
|   5   | [[3-Compendium/Klassen/Kleriker/Kleriker#Untote versengen\|Untote versengen]]                                                                          |     +3      |        2        |      4       |          9          | 4   |  3  |  2  |  −  |  −  |  −  |  −  |  −  |  -  |
|   6   | Unterklassenmerkmal                                                                                                                                    |     +3      |        3        |      4       |         10          | 4   |  3  |  3  |  −  |  −  |  −  |  −  |  −  |  -  |
|   7   | [[3-Compendium/Klassen/Kleriker/Kleriker#Gesegnete Schläge\|Gesegnete Schläge]]                                                                        |     +3      |        3        |      4       |         11          | 4   |  3  |  3  |  1  |  −  |  −  |  −  |  −  |  -  |
|   8   | [[3-Compendium/Klassen/Kleriker/Kleriker#Attributswerterhöhung\|Attributswerterhöhung]]                                                                |     +3      |        3        |      4       |         12          | 4   |  3  |  3  |  2  |  −  |  −  |  −  |  −  |  -  |
|   9   | −                                                                                                                                                      |     +4      |        3        |      4       |         14          | 4   |  3  |  3  |  3  |  1  |  −  |  −  |  −  |  -  |
|  10   | [[3-Compendium/Klassen/Kleriker/Kleriker#Göttliche Intervention\|Göttliche Intervention]]                                                              |     +4      |        3        |      5       |         15          | 4   |  3  |  3  |  3  |  2  |  −  |  −  |  −  |  -  |
|  11   | −                                                                                                                                                      |     +4      |        3        |      5       |         16          | 4   |  3  |  3  |  3  |  2  |  1  |  −  |  −  |  -  |
|  12   | [[3-Compendium/Klassen/Kleriker/Kleriker#Attributswerterhöhung\|Attributswerterhöhung]]                                                                |     +4      |        3        |      5       |         16          | 4   |  3  |  3  |  3  |  2  |  1  |  −  |  −  |  -  |
|  13   | −                                                                                                                                                      |     +5      |        3        |      5       |         17          | 4   |  3  |  3  |  3  |  2  |  1  |  1  |  −  |  -  |
|  14   | [[3-Compendium/Klassen/Kleriker/Kleriker#Verbesserte Gesegnete Schläge\|Verbesserte Gesegnete Schläge]]                                                |     +5      |        3        |      5       |         17          | 4   |  3  |  3  |  3  |  2  |  1  |  1  |  −  |  -  |
|  15   | −                                                                                                                                                      |     +5      |        3        |      5       |         18          | 4   |  3  |  3  |  3  |  2  |  1  |  1  |  1  |  -  |
|  16   | [[3-Compendium/Klassen/Kleriker/Kleriker#Attributswerterhöhung\|Attributswerterhöhung]]                                                                |     +5      |        3        |      5       |         18          | 4   |  3  |  3  |  3  |  2  |  1  |  1  |  1  |  -  |
|  17   | Unterklassenmerkmal                                                                                                                                    |     +6      |        3        |      5       |         19          | 4   |  3  |  3  |  3  |  2  |  1  |  1  |  1  |  1  |
|  18   | −                                                                                                                                                      |     +6      |        4        |      5       |         20          | 4   |  3  |  3  |  3  |  3  |  1  |  1  |  1  |  1  |
|  19   | [[3-Compendium/Klassen/Kleriker/Kleriker#Epische Gabe\|Epische Gabe]]                                                                                  |     +6      |        4        |      5       |         21          | 4   |  3  |  3  |  3  |  3  |  2  |  1  |  1  |  1  |
|  20   | [[3-Compendium/Klassen/Kleriker/Kleriker#Mächtige Göttliche Intervention\|Mächtige Göttliche Intervention]]                                            |     +6      |        4        |      5       |         22          | 4   |  3  |  3  |  3  |  3  |  2  |  2  |  1  |  1  |

## Stufe 1
### Zauberwirken 

Du hast gelernt, durch Gebete und Meditation Zauber zu wirken. Die Regeln zum Zauberwirken findest du unter „Zauber“. Folgende Informationen erklären, wie du diese Regeln mit den Kleriker‑ zaubern verwendest, die in der Zauberliste des Klerikers weiter hinten in dieser Klassen‑ beschreibung aufgeführt sind. 

**_Zaubertricks:_** Du beherrschst drei Zaubertricks deiner Wahl aus der Zauberliste des Klerikers. _Göttliche Führung_ , _Heilige Flamme_ und _Thaumaturgie_ werden empfohlen. 

Wann immer du eine Klerikerstufe erhältst, kannst du einen deiner Zaubertricks mit einem anderen Zaubertrick deiner Wahl aus der Zauberliste des Klerikers ersetzen. 

Wenn du die 4. und 10. Klerikerstufe erreichst, erlernst du einen weiteren Zaubertrick deiner Wahl aus der Zauberliste des Klerikers, wie in der Spalte „Zaubertricks“ der Tabelle „Klerikermerkmale“ dargestellt. 

**_Zauberplätze:_** Die Tabelle „Klerikermerkmale“ zeigt, wie viele Zauberplätze dir zum Wirken deiner Zauber ab dem 1. Grad zur Verfügung stehen. Du erhältst alle verbrauchten Zauberplätze nach einer langen Rast zurück. 

**_Vorbereitete Zauber ab dem 1. Grad:_** Du bereitest die Liste der Zauber ab dem 1. Grad vor, die dir mit diesem Merkmal zur Verfügung stehen. Wähle zu Beginn vier Zauber des 1. Grades aus der Zauberliste des Klerikers aus. _Lenkendes Geschoss_ , _Schild des Glaubens_ , _Segnen_ und _Wunden heilen_ werden empfohlen. 

Die Anzahl der Zauber auf deiner Liste erhöht sich, wenn du weitere Klerikerstufen erhältst, wie in der Spalte „Vorbereitete Zauber“ der Tabelle „Klerikermerkmale“ dargestellt. Wann immer sich diese Anzahl erhöht, wählst du zusätzliche Zauber aus der Zauberliste des Klerikers aus, bis die Anzahl von Zaubern auf deiner Liste der Anzahl entspricht, die in der Tabelle aufgeführt ist. Der Grad der ausgewählten Zauber muss dem der verfügbaren Zauberplätze entsprechen. Beispiel: Wenn du ein Kleriker der 3. Stufe bist, kann deine Liste vorbereiteter Zauber sechs Zauber des 1. und 2. Grades in beliebiger Kombination enthalten. 

Wenn ein anderes Klerikermerkmal dir Zauber gibt, die du stets vorbereitet hast, zählen diese Zauber nicht bei der Anzahl von Zaubern, die du mit diesem Merkmal vorbereiten kannst. Ansonsten zählen diese Zauber jedoch als Klerikerzauber für dich. 

**_Deine vorbereiteten Zauber ändern:_** Wann immer du eine lange Rast beendest, kannst du deine Liste vorbereiteter Zauber ändern und beliebige Zauber von der Liste mit anderen Klerikerzaubern ersetzen, für die du Zauberplätze hast. 

**_Attribut zum Zauberwirken:_** Dein Attribut zum Wirken der Klerikerzauber ist Weisheit. 

**_Zauberfokus:_** Du kannst ein heiliges Symbol als Zauberfokus für deine Klerikerzauber verwenden. 

### Göttliche Ordnung 

Du hast dich nach deiner Wahl einer der folgenden heiligen Rollen verschrieben. 

**_Beschützer:_** Du wurdest für den Kampf ausgebildet, daher hast du Übung im Umgang mit Kriegswaffen und Vertrautheit mit schwerer Rüstung. 

**_Thaumaturg:_** Du kennst einen zusätzlichen Zaubertrick aus der Zauberliste des Klerikers. Außerdem gibt dir deine mystische Verbindung mit dem Göttlichen einen Bonus auf deine Intelligenz‑ würfe (Arkane Kunde oder Religion). Dieser Bonus entspricht deinem Weisheitsmodifikator (mindestens +1). 
## Stufe 2
### Göttliche Macht fokussieren 

Du kannst göttliche Energie direkt von den Äußeren Ebenen kanalisieren, um magische Effekte zu wirken. Du beginnst mit zwei solchen Effekten: Göttlicher Funke und Untote vertreiben (beide unten beschrieben). Wann immer du Göttliche Macht fokussieren dieser Klasse einsetzt, wählst du aus, welchen Effekt von Göttliche Macht fokussieren dieser Klasse du bewirkst. Auf höheren Klerikerstufen erhältst du zusätzliche Optionen für Effekte. 

Du kannst Göttliche Macht fokussieren dieser Klasse zweimal anwenden. Wenn du eine kurze Rast beendest, erhältst du eine verbrauchte Anwendung zurück. Du erhältst alle verbrauchten Anwendungen nach einer langen Rast zurück. Wenn du bestimmte Klerikerstufen erreichst, erhältst du zusätzliche Anwendungen, wie in der Spalte „Göttliche Macht fokussieren“ der Tabelle „Klerikermerkmale“ dargestellt. 

Wenn ein Effekt von Göttliche Macht fokussieren einen Rettungswurf erfordert, entspricht der SG dem Zauberrettungswurf‑SG des Merkmals Zauberwirken dieser Klasse. 

**_Göttlicher Funke:_** Als magische Aktion richtest du dein heiliges Symbol auf eine andere Kreatur im Abstand von bis zu neun Metern von dir, die du sehen kannst, und fokussierst göttliche Energie auf sie. Würfle mit 1W8 und füge deinen Weisheitsmodifikator hinzu. Nach deiner Wahl stellt die Kreatur entweder Trefferpunkte in Höhe des Gesamtergebnisses wieder her, oder sie ist zu einem Konstitutionsrettungswurf gezwungen. Misslingt der Wurf, so erleidet die Kreatur gleißenden oder nekrotischen Schaden (nach deiner Wahl) in Höhe des Gesamtergebnisses. Bei einem erfolgreichen Rettungswurf erleidet die Kreatur halb so viel Schaden (abgerundet). 

Du würfelst mit jeweils einem zusätzlichen W8, wenn du die 7. (2W8), die 13. (3W8) und die 18. (4W8) Klerikerstufe erreicht hast. 

**_Untote vertreiben:_** Als magische Aktion präsentierst du dein heiliges Symbol und rügst untote Kreaturen. Jeder Untote deiner Wahl im Abstand von bis zu neun Metern von dir muss einen Weisheitsrettungswurf ausführen. Misslingt der Wurf, so ist die Kreatur eine Minute lang verängstigt und kampfunfähig. Während dieser Dauer versucht sie in ihren Zügen, sich so weit wie möglich von dir zu entfernen. Dieser Effekt endet vorzeitig, wenn die Kreatur Schaden erleidet, wenn du kampfunfähig wirst oder wenn du stirbst. 
## Stufe 3
### Kleriker-Unterklasse 

Du erhältst eine Kleriker‑Unterklasse deiner Wahl. Die Unterklasse Domäne des Lebens wird nach der Beschreibung dieser Klasse erläutert. Unterklassen sind Spezialisierungen, die dir auf bestimmten Klerikerstufen Merkmale gewähren. Du erhältst für den Rest deiner Laufbahn alle Merkmale deiner Unterklasse, die zu deiner aktuellen Klerikerstufe oder den niedrigeren Stufen gehören. 
## Stufe 4
### Attributswerterhöhung 

Du erhältst das Talent Attributswerterhöhung (siehe „[[Talente]]“) oder ein anderes Talent deiner Wahl, für das du qualifiziert bist. Du erhältst dieses Merkmal auf der 8., 12. und 16. Klerikerstufe erneut. 
## Stufe 5
### Untote versengen 

Wann immer du Untote vertreiben einsetzt, kannst du mit einer Anzahl von W8 in Höhe deines Weisheitsmodifikators (mindestens 1W8) würfeln. Jeder Untote, dessen Rettungswurf gegen diesen Einsatz von Untote vertreiben misslingt, erleidet gleißenden Schaden in Höhe des Gesamtergebnisses. Dieser Schaden beendet nicht den Effekt von Untote vertreiben. 
## Stufe 7
### Gesegnete Schläge 

Göttliche Macht erfüllt dich im Kampf. Du erhältst eine der folgenden Optionen nach deiner Wahl (wenn du eine der Optionen von einer Kleriker‑ Unterklasse aus einem älteren Buch erhältst, verwende nur die Option, die du für dieses Merkmal auswählst). 

**_Göttlicher Schlag:_** Einmal in jedem deiner Züge kannst du, wenn du eine Kreatur bei einem Angriffswurf mit einer Waffe triffst, dem Ziel zusätzlich 1W8 gleißenden oder nekrotischen Schaden (nach deiner Wahl) zufügen. 

**_Verstärkte Zaubertricks:_** Füge dem Schaden, den du mit Klerikerzaubertricks bewirkst, deinen Weisheitsmodifikator hinzu. 
## Stufe 10
### Göttliche Intervention 

Du kannst deine Gottheit oder dein Pantheon anrufen, damit sie beziehungsweise es in deinem Sinne eingreift. Wähle als magische Aktion einen beliebigen Klerikerzauber des höchstens 5. Grades aus, den zu wirken keine Reaktion erfordert. Als Teil derselben Aktion wirkst du diesen Zauber, ohne einen Zauberplatz zu verbrauchen oder Materialkomponenten zu benötigen. Du kannst dieses Merkmal erst nach einer langen Rast erneut verwenden. 
## Stufe 14
### Verbesserte Gesegnete Schläge
Die Option, die du für Gesegnete Schläge ausgewählt hast, wird mächtiger. 

**_Göttlicher Schlag:_** Der zusätzliche Schaden deines Göttlichen Schlags ist auf 2W8 erhöht. 

**_Verstärkte Zaubertricks:_** Wenn du einen Klerikerzaubertrick wirkst und einer Kreatur damit Schaden zufügst, kannst du dir selbst oder einer anderen Kreatur im Abstand von bis zu 18 Metern von dir Lebenskraft geben, die eine Anzahl von temporären Trefferpunkten in doppelter Höhe deines Weisheitsmodifikators gewährt. 
## Stufe 19
### Epische Gabe 

Du erhältst ein Epische‑Gabe‑Talent (siehe „[[Talente]]“) oder ein anderes Talent deiner Wahl, für das du qualifiziert bist. Gabe des Schicksals wird empfohlen. 
## Stufe 20
### Mächtige Göttliche Intervention 

Du kannst um noch mächtigere göttliche Intervention bitten. Wenn du dein Merkmal Göttliche Intervention einsetzt, kannst du den Zauber _Wunsch_ auswählen. In diesem Fall kannst du Göttliche Intervention erst nach 2W4 langen Rasten erneut einsetzen. 

# Zauberliste des Klerikers 

In diesem Abschnitt wird die Zauberliste des Klerikers vorgestellt. Die Zauber sind nach Zaubergrad und dann alphabetisch sortiert, und die Schule der Magie der jeweiligen Zauber ist aufgeführt. In der Spalte „Besonderheit“ bedeutet _K_ , dass der Zauber Konzentration erfordert, _R_ bedeutet, dass es sich um ein Ritual handelt, und _M_ bedeutet, dass eine bestimmte Materialkomponente erforderlich ist. 

## Zaubertricks (Klerikerzauber des 0. Grades) 

|Zauber|Schule|Beson-derheit|
|---|---|---|
|_Ausbessern_|Verwandlungsmagie|−|
|_Göttliche Führung_|Erkenntnismagie|K|
|_Heilige Flamme_|Hervorrufungsmagie|−|
|_Licht_|Hervorrufungsmagie|−|

|Zauber|Schule|Beson-derheit|Zauber|Schule|Beson-derheit|
|---|---|---|---|---|---|
|_Thaumaturgie_|Verwandlungsmagie|−|_Schwache Genesung_|Bannmagie|−|
|_Verschonung der_|Nekromantie|−|_Stille_|Illusionsmagie|K, R|
|_Sterbenden_|||_Vorahnung_|Erkenntnismagie|R, M|
|_Widerstand_|Bannmagie|K|_Waffe des Glaubens_|Hervorrufungsmagie|K|
||||_Zone der Wahrheit_|Verzauberungsmagie|−|



## Klerikerzauber des 1. Grades 

|Zauber|Schule|Beson-derheit|Klerikerzauber des|3. Grades|Beson-|
|---|---|---|---|---|---|
|_Befehl_|Verzauberungsmagie|−|Zauber|Schule|derheit|
|_Gift und Krankheit_|Erkenntnismagie|K, R|_Fluch brechen_|Bannmagie|−|
|_entdecken_|||_Fluch_|Nekromantie|K|
|_Gutes und Böses__entdecken_|Erkenntnismagie|K|_Glyphe des Schutzes_|Bannmagie|M|
|_Heilendes Wort_|Bannmagie|−|_Hellsehen_|Erkenntnismagie|K, M|
||||_Leuchtfeuer der_|Bannmaie|K|
|_Heiligtum_|Bannmagie|−|_Hoffnung_|g||
|_Lenkendes Geschoss_|Hervorrufungsmagie|−|_Magie bannen_|Bannmagie|−|
|_Magie entdecken_|Erkenntnismagie|K, R|_Massen-Heilendes Wort_|Bannmagie|−|
|_Nahrung und Wasser__ii_|Verwandlungsmagie|R|_Mit Stein verschmelzen_|Verwandlungsmagie|R|
|_rengen_|||_Mit Toten sprechen_|Nekromantie|−|
|_Schild des Glaubens_|Bannmagie|K||||
|_Schutz vor Gut und Böse_|Bannmagie|K, M|_Nahrung und Wasser__erschaffen_|Beschwörungsmagie|−|
|_Segnen_|Verzauberungsmagie|K, M|_Schutz vor Energie_|Bannmagie|K|
|_Verderben_|Verzauberungsmagie|K|_Schutzgeister_|Beschwörungsmagie|K|
|_Wasser erschaffen oder__zerstören_|Verwandlungsmagie|−|_Schutzkreis_|Bannmagie|M|
|_Wunden heilen_|Bannmagie|−|_Tageslicht_|Hervorrufungsmagie|−|
||||_Tote beleben_|Nekromantie|−|
|_Wunden verursachen_|Nekromantie|−||||
||||_Verständigung_|Erkenntnismagie|−|
|lerikerzauber des 2|. Grades||_Wasserwandeln_|Verwandlungsmagie|R|
|||Beson-|_Wiederbeleben_|Nekromantie|M|
|Zauber|Schule|derheit|_Zungen_|Erkenntnismagie|−|



## Klerikerzauber des 2. Grades 

|Zauber|Schule|Beson-derheit|
|---|---|---|
|_Attribut verbessern_|Verwandlungsmagie|K|
|_Beistand_|Bannmagie|−|
|_Blindheit/Taubheit_|Verwandlungsmagie|−|
|_Dauerhafte Flamme_|Hervorrufungsmagie|M|
|_Fallen finden_|Erkenntnismagie|−|
|_Gebet der Heilung_|Bannmagie|−|
|_Gefühle besänftigen_|Verzauberungsmagie|K|
|_Gegenstand aufspüren_|Erkenntnismagie|K|
|_Person festhalten_|Verzauberungsmagie|K|
|_Sanfte Ruhe_|Nekromantie|R, M|
|_Schutz vor Gift_|Bannmagie|−|
|_Schützendes Band_|Bannmagie|M|



## Klerikerzauber des 4. Grades 

|Zauber|Schule|Beson-derheit|
|---|---|---|
|_Aura des Lebens_|Bannmagie|K|
|_Bewegungsfreiheit_|Bannmagie|−|
|_Hüter des Glaubens_|Beschwörungsmagie|−|
|_Kreatur aufspüren_|Erkenntnismagie|K|
|_Stein formen_|Verwandlungsmagie|−|
|_Todesschutz_|Bannmagie|−|
|_Verbannung_|Bannmagie|K|
|_Wasser kontrollieren_|Verwandlungsmagie|K|
|_Weissagung_|Erkenntnismagie|R, M|


## Klerikerzauber des 5. Grades 

|Zauber|Schule|Beson-derheit|
|---|---|---|
|_Ansteckung_|Nekromantie|−|
|_Ausspähung_|Erkenntnismagie|K, M|
|_Bindung der Ebenen_|Bannmagie|M|
|_Flammenschlag_|Hervorrufungsmagie|−|
|_Geas_|Verzauberungsmagie|−|
|_Gutes und Böses bannen_|Bannmagie|K|
|_Heiliges Gespräch_|Erkenntnismagie|R|
|_Insektenplage_|Beschwörungsmagie|K|
|_Massen-Wunden heilen_|Bannmagie|−|
|_Sagenkunde_|Erkenntnismagie|M|
|_Tote erwecken_|Nekromantie|M|
|_Vollständige Genesung_|Bannmagie|M|
|_Weihen_|Bannmagie|M|



## Klerikerzauber des 6. Grades 

|Zauber|Schule|Beson-derheit|
|---|---|---|
|_Heilung_|Bannmagie|−|
|_Heldenmahl_|Beschwörungsmagie|M|
|_Klingenbarriere_|Hervorrufungsmagie|K|
|_Leid_|Nekromantie|−|
|_Sonnenstrahl_|Hervorrufungsmagie|K|
|_Untote erschaffen_|Nekromantie|M|
|_Verbündeter aus den_|Beschwörungsmagie|−|
|_Ebenen_|||
|_Wahrer Blick_|Erkenntnismagie|M|
|_Weg finden_|Erkenntnismagie|K, M|
|_Wort des Rückrufs_|Beschwörungsmagie|−|
|_Zutritt verwehren_|Bannmagie|R, M|



## Klerikerzauber des 7. Grades 

|Zauber|Schule|Beson-derheit|
|---|---|---|
|_Ätherische Gestalten_|Beschwörungsmagie|−|
|_Auferstehung_|Nekromantie|M|
|_Celestisches Wesen_|Beschwörungsmagie|K|
|_beschwören_|||
|_Ebenenwechsel_|Beschwörungsmagie|M|
|_Feuersturm_|Hervorrufungsmagie|−|
|_Göttliches Wort_|Hervorrufungsmagie|−|
|_Regeneration_|Verwandlungsmagie|−|
|_Symbol_|Bannmagie|M|



## Klerikerzauber des 8. Grades 

|Zauber|Schule|Beson-derheit|
|---|---|---|
|_Antimagisches Feld_|Bannmagie|K|
|_Erdbeben_|Verwandlungsmagie|K|
|_Heilige Aura_|Bannmagie|K, M|
|_Sonnenfeuer_|Hervorrufungsmagie|−|
|_Wetterkontrolle_|Verwandlungsmagie|K|



## Klerikerzauber des 9. Grades 

|Zauber|Schule|Beson-derheit|
|---|---|---|
|_Astrale Projektion_|Nekromantie|M|
|_Massen-Heilung_|Bannmagie|−|
|_Tor_|Beschwörungsmagie|K, M|
|_Wahre Auferstehung_|Nekromantie|M|
|_Wort der Macht: Heilung_|Verzauberungsmagie|−|
