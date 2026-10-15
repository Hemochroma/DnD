---
Trefferwürfel: W10
PrimärAttribut:
  - Stärke
Rettungswürfe:
  - Stärke
  - Konstitution
Rüstung:
  - Leichte
  - Mittelschwere
  - Schwere
  - Schilde
Waffen:
  - Einfache Waffen
  - Kriegswaffen
Icon: "[[Fighter_logo.png]]"
---

> [!infobox]
> # Fightere
> ![[Fighter_logo.png|120]]
> **Trefferwürfel:** 1W10 pro Stufe
> **Primäres Attribut:** Stärke
> **Rettungswürfe:** Stärke & Geschicklichkeit
> **Rüstung:** Leichte, Mittelschwere, Schwere, Schilde
> **Waffen:** Einfache Waffen, Kriegswaffen
> **Werkzeuge:** Drei Muskinstrumente deiner Wahl
> **Fähigkeiten:** _Wähle zwei aus:_
> - Akrobatik
> - Athletik
> - Einschüchtern
> - Geschichte
> - Mit Tierenumgehen
> - Motiv erkennen
> - Überlebenskunst
> - Überzeugen
> - Wahrnehmung

![[z_Assets/classes/Fighter/Fighter.png]]

# Ein Kämpfer werden ... 

## Als Charakter der 1. Stufe 

- Du erhältst alle Merkmale in der Tabelle „Hauptmerkmale des Kämpfers“. 
- Du erhältst die Merkmale der 1. Kämpferstufe, die in der Tabelle „Kämpfermerkmale“ aufgeführt sind. 
## Anfangsausrüstung
Du beginnst mit der folgenden Ausrüstung, zusätzlich zu den Ausrüstungen, die durch Ihren Hintergrund gewährt werden:
- Kettenpanzer, Zweihandschwert, Flegel, acht Wurfspeere, Gewölbeforscherausrüstungund, 4 GM 
- Beschlagene Lederrüstung, Krummsäbel, Kurzschwert, Langbogen, 20 Pfeile, Köcher, Gewölbeforscherausrüstungund 11 GM
- 155 GM
## Als Charakter mit Klassenkombination 

- Du erhältst folgende Merkmale in der Tabelle „Hauptmerkmale des Kämpfers“: Trefferpunkte‑ würfel, Übung im Umgang mit Kriegswaffen, Vertrautheit mit leichter und mittelschwerer Rüstung sowie mit Schilden. 
- Du erhältst die Merkmale der 1. Kämpferstufe, die in der Tabelle „Kämpfermerkmale“ aufgeführt sind. 

# Klassenmerkmale des Kämpfers 
## Unterklassen

```base
views:
  - type: cards
    name: Tabelle
    filters:
      and:
        - file.inFolder("3-Compendium/Klassen/Kämpfer/Unterklassen")
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
Als Kämpfer erhältst du auf den angegebenen Kämpferstufen folgende Klassenmerkmale. Diese Merkmale sind in der Tabelle „Kämpfermerkmale“ aufgeführt. 

| Stufe | Klassenmerkmale                                                                                                                                                                                                         | Übungsbonus | Durchschnaufen | Waffenbeherrschung |
|:-----:| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |:-----------:|:--------------:|:------------------:|
|   1   | [[3-Compendium/Klassen/Kämpfer/Kämpfer#Kampfstil\|Kampfstil]], [[3-Compendium/Klassen/Kämpfer/Kämpfer#Durchschnaufen\|Durchschnaufen]], [[3-Compendium/Klassen/Kämpfer/Kämpfer#Waffenbeherrschung\|Waffenbeherrschung]] |     +2      |       2        |         3          |
|   2   | [[3-Compendium/Klassen/Kämpfer/Kämpfer#Taktisches Verständnis\|Taktisches Verständnis]], [[3-Compendium/Klassen/Kämpfer/Kämpfer#Tatendrang\|Tatendrang]] (einmalig)                                                     |     +2      |       2        |         3          |
|   3   | Kämpfer ­Unterklasse                                                                                                                                                                                                    |     +2      |       2        |         3          |
|   4   | [[3-Compendium/Klassen/Kämpfer/Kämpfer#Attributswerterhöhung\|Attributswerterhöhung]]                                                                                                                                   |     +2      |       3        |         4          |
|   5   | [[3-Compendium/Klassen/Kämpfer/Kämpfer#Taktikwechsel\|Taktikwechsel]], [[3-Compendium/Klassen/Kämpfer/Kämpfer#Zusätzlicher Angriff\|Zusätzlicher Angriff]]                                                              |     +3      |       3        |         4          |
|   6   | [[3-Compendium/Klassen/Kämpfer/Kämpfer#Attributswerterhöhung\|Attributswerterhöhung]]                                                                                                                                   |     +3      |       3        |         4          |
|   7   | Unterklassenmerkmal                                                                                                                                                                                                     |     +3      |       3        |         4          |
|   8   | [[3-Compendium/Klassen/Kämpfer/Kämpfer#Attributswerterhöhung\|Attributswerterhöhung]]                                                                                                                                   |     +3      |       3        |         4          |
|   9   | [[3-Compendium/Klassen/Kämpfer/Kämpfer#Taktischer Meister\|Taktischer Meister]], [[3-Compendium/Klassen/Kämpfer/Kämpfer#Unbeugsamkeit\|Unbeugsamkeit]] (eine Anwendung)                                                 |     +4      |       3        |         4          |
|  10   | Unterklassenmerkmal                                                                                                                                                                                                     |     +4      |       4        |         5          |
|  11   | [[3-Compendium/Klassen/Kämpfer/Kämpfer#Zwei zusätzliche Angriffe\|Zwei zusätzliche Angriffe]]                                                                                                                           |     +4      |       4        |         5          |
|  12   | [[3-Compendium/Klassen/Kämpfer/Kämpfer#Attributswerterhöhung\|Attributswerterhöhung]]                                                                                                                                   |     +4      |       4        |         5          |
|  13   | [[3-Compendium/Klassen/Kämpfer/Kämpfer#Angriffsstudien\|Angriffsstudien]], [[3-Compendium/Klassen/Kämpfer/Kämpfer#Unbeugsamkeit\|Unbeugsamkeit]] (zwei Anwendungen)                                                     |     +5      |       4        |         5          |
|  14   | [[3-Compendium/Klassen/Kämpfer/Kämpfer#Attributswerterhöhung\|Attributswerterhöhung]]                                                                                                                                   |     +5      |       4        |         5          |
|  15   | Unterklassenmerkmal                                                                                                                                                                                                     |     +5      |       4        |         5          |
|  16   | [[3-Compendium/Klassen/Kämpfer/Kämpfer#Attributswerterhöhung\|Attributswerterhöhung]]                                                                                                                                   |     +5      |       4        |         6          |
|  17   | [[3-Compendium/Klassen/Kämpfer/Kämpfer#Tatendrang\|Tatendrang]] (zwei Anwendungen), [[3-Compendium/Klassen/Kämpfer/Kämpfer#Unbeugsamkeit\|Unbeugsamkeit]] (drei Anwendungen)                                            |     +6      |       4        |         6          |
|  18   | Unterklassenmerkmal                                                                                                                                                                                                     |     +6      |       4        |         6          |
|  19   | [[3-Compendium/Klassen/Kämpfer/Kämpfer#Epische Gabe\|Epische Gabe]]                                                                                                                                                     |     +6      |       4        |         6          |
|  20   | [[3-Compendium/Klassen/Kämpfer/Kämpfer#Drei zusätzliche Angriffe\|Drei zusätzliche Angriffe]]                                                                                                                           |     +6      |       4        |         6          |
## Stufe 1
### Durchschnaufen 

Du hast einen gewissen Vorrat an körperlicher und geistiger Ausdauer zur Verfügung. Als Bonusaktion kannst du Trefferpunkte in Höhe von 1W10 plus deiner Kämpferstufe zurückerhalten. 

Du kannst dieses Merkmal zweimal anwenden. Nach einer kurzen Rast erhältst du eine verbrauchte Anwendung zurück. Nach einer langen Rast erhältst du alle verbrauchten Anwendungen zurück. 

Wenn du bestimmte Kämpferstufen erreichst, erhältst du mehr Anwendungen dieses Merkmals, wie in der Spalte „Durchschnaufen“ der Tabelle „Kämpfermerkmale“ dargestellt. 

### Kampfstil 

Du hast deine Kampfkünste verfeinert und erhältst ein Kampfstil‑Talent deiner Wahl (siehe „[[Talente]]“). Verteidigung wird empfohlen. 

Wann immer du eine Kämpferstufe erhältst, kannst du das ausgewählte Talent durch ein anderes Kampfstil‑Talent ersetzen. 

### Waffenbeherrschung 

Deine Vertrautheit mit Waffen gestattet dir, die Meisterschaftseigenschaften dreier Arten von einfachen Waffen oder Kriegswaffen deiner Wahl zu verwenden. Wann immer du eine lange Rast 

beendest, kannst du Waffenübungen ausführen und eine dieser Waffenentscheidungen ändern. 

Wenn du bestimmte Kämpferstufen erreichst, erhältst du das Attribut zum Verwenden der Meisterschaftseigenschaften von mehr Waffenarten, wie in der Spalte „Waffenbeherrschung“ der Tabelle „Kämpfermerkmale“ dargestellt. 
## Stufe 2
### Taktisches Verständnis 

Du hast auf dem Schlachtfeld sowie anderswo einen ausgeprägten Sinn für Taktik. Wenn du bei einem Attributswurf scheiterst, kannst du eine Anwendung von Durchschnaufen verbrauchen, um einen Erfolg anzustreben. Anstatt Trefferpunkte zurückzuerhalten, würfelst du mit 1W10, fügst das Ergebnis dem Attributswurf hinzu und machst so aus dem Misserfolg möglicherweise einen Erfolg. Misslingt der Wurf dennoch, so wird diese Anwendung von Durchschnaufen nicht verbraucht. 

### Tatendrang 

Du kannst kurzzeitig deine normalen Grenzen überwinden. In deinem Zug kannst du eine zusätzliche Aktion (außer der magischen Aktion) ausführen. 

Du kannst dieses Merkmal erst nach einer kurzen oder langen Rast erneut verwenden. Ab 17. Stufe kannst du Tatendrang zweimal vor einer Rast, jedoch nur einmal pro Zug einsetzen. 
## Stufe 3
### Kämpfer-Unterklasse 

Du erhältst eine Kämpfer‑Unterklasse deiner Wahl. Die Unterklasse Champion wird nach der Beschreibung dieser Klasse erläutert. Unterklassen sind Spezialisierungen, die dir auf bestimmten Kämpferstufen Merkmale gewähren. Du erhältst für den Rest deiner Laufbahn alle Merkmale deiner Unterklasse, die zu deiner aktuellen Kämpferstufe oder den niedrigeren Stufen gehören. 
## Stufe 4
### Attributswerterhöhung 

Du erhältst das Talent Attributswerterhöhung (siehe „[[Talente]]“) oder ein anderes Talent deiner Wahl, für das du qualifiziert bist. Du erhältst dieses Merkmal auf der 6., 8., 12., 14. und 16. Kämpferstufe erneut. 
## Stufe 5
### Taktikwechsel 

Wann immer du Durchschnaufen mit einer Bonus‑ aktion aktivierst, kannst du bis zur Hälfte deiner Bewegungsrate nutzen, ohne Gelegenheitsangriffe zu provozieren. 

### Zusätzlicher Angriff 

Du kannst jetzt zweimal angreifen, wenn du in deinem Zug eine Angriffsaktion ausführst. 
## Stufe 9
### Taktischer Meister 

Wenn du mit einer Waffe angreifst, deren Meister‑ schaftseigenschaft du nutzen kannst, so kannst du die Eigenschaft bei diesem Angriff durch eine der Eigenschaften Auslaugen, Stoßen oder Verlangsa‑ men ersetzen. 

### Unbeugsamkeit 

Wenn du bei einem Rettungswurf scheiterst, kannst du ihn mit einem Bonus in Höhe deiner Kämpferstufe erneut ausführen. In diesem Fall musst du das neue Ergebnis verwenden und kannst das Merkmal erst nach einer langen Rast erneut verwenden. 

Du kannst dieses Merkmal ab der 13. Stufe zweimal vor einer langen Rast und ab der 17. Stufe dreimal vor einer langen Rast anwenden. 
## Stufe 11
### Zwei zusätzliche Angriffe 

Du kannst jetzt dreimal angreifen, wenn du in deinem Zug eine Angriffsaktion ausführst. 
## Stufe 13
### Angriffsstudien 

Du studierst deine Gegner und lernst aus jedem Angriff, den du ausführst. Wenn du bei einem Angriffswurf gegen eine Kreatur scheiterst, bist du bei deinem nächsten Angriffswurf gegen diese Kreatur vor Ende deines nächsten Zugs im Vorteil. 
## Stufe 19
### Epische Gabe 

Du erhältst ein Epische‑Gabe‑Talent (siehe „[[Talente]]“) oder ein anderes Talent deiner Wahl, für das du qualifiziert bist. Gabe der Kampffertigkeit wird empfohlen. 
## Stufe 20
### Drei zusätzliche Angriffe 

Du kannst jetzt viermal angreifen, wenn du in deinem Zug eine Angriffsaktion ausführst. 