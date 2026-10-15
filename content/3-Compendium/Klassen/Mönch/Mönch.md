---
Trefferwürfel: W8
PrimärAttribut:
  - Geschicklichkeit
  - Weisheit
Rettungswürfe:
  - Stärke
  - Geschicklichkeit
Rüstung:
  - Keine
Waffen:
  - Einfache Waffen
  - Leichte Kriegswaffen
Icon: "[[Monk_logo.png]]"
---

> [!infobox]
> # Monke
> ![[Monk_logo.png|120]]
> **Trefferwürfel:** 1W8 pro Stufe
> **Primäres Attribut:** Geschicklichkeit, Weisheit
> **Rettungswürfe:** Stärke & Geschicklichkeit
> **Rüstung:** _keine_
> **Waffen:** Einfache Waffen, Leichte Kriegswaffen
> **Werkzeuge:** _Wähle eine Art von Handwerkszeug oder ein Musikinstrument
> **Fähigkeiten:** _Wähle zwei aus:_
> - Akrobatik
> - Athletik
> - Geschichte
> - Heimlich­keit
> - Motiv erkennen
> - Religion

![[z_Assets/classes/Monk/Monk.png]]
# Ein Mönch werden ... 

## Als Charakter der 1. Stufe 

- Du erhältst alle Merkmale in der Tabelle „Hauptmerkmale des Mönchs“. 
- Du erhältst die Merkmale der 1. Mönchsstufe, die in der Tabelle „Mönchsmerkmale“ aufgeführt sind. 
## Anfangsausrüstung
Du beginnst mit der folgenden Ausrüstung, zusätzlich zu den Ausrüstungen, die durch Ihren Hintergrund gewährt werden:
- Speer, fünf Dolche, Handwerkszeug oder Musikinstrument, Entdeckeraus­rüstung und 11 GM
- 50 GM

## Als Charakter mit Klassenkombination 

- Du erhältst das Merkmal Trefferpunktewürfel aus der Tabelle „Hauptmerkmale des Mönchs“. 
- Du erhältst die Merkmale der 1. Mönchsstufe, die in der Tabelle „Mönchsmerkmale“ aufgeführt sind. 

# Klassenmerkmale des Mönchs 
## Unterklassen

```base
views:
  - type: cards
    name: Tabelle
    filters:
      and:
        - file.inFolder("3-Compendium/Klassen/Mönch/Unterklassen")
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
Als Mönch erhältst du auf den angegebenen Mönchsstufen folgende Klassenmerkmale. Diese Merkmale sind in der Tabelle „Mönchsmerkmale“ aufgeführt. 

| Stufe | Klassenmerkmale                                                                                                                                                                                                                             | Übungsbonus | Kampfkünste | Fokuspunkte | Ungerüstete Bewegung |
|:-----:| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |:-----------:|:-----------:|:-----------:|:--------------------:|
|   1   | [[3-Compendium/Klassen/Mönch/Mönch#Kampfkünste\|Kampfkünste]], [[3-Compendium/Klassen/Mönch/Mönch#Ungerüstete Verteidigung\|Ungerüstete Verteidigung]]                                                                                      |     +2      |     1W6     |      −      |          −           |
|   2   | [[3-Compendium/Klassen/Mönch/Mönch#Mönchsfokus\|Mönchsfokus]], [[3-Compendium/Klassen/Mönch/Mönch#Ungerüstete Bewegung\|Ungerüstete Bewegung]], [[3-Compendium/Klassen/Mönch/Mönch#Unglaublicher Stoffwechsel\|Unglaublicher Stoffwechsel]] |     +2      |     1W6     |      2      |         +3 m         |
|   3   | [[3-Compendium/Klassen/Mönch/Mönch#Angriffe umleiten\|Angriffe umleiten]], Mönch ­Unterklasse                                                                                                                                               |     +2      |     1W6     |      3      |         +3 m         |
|   4   | [[3-Compendium/Klassen/Mönch/Mönch#Attributswerterhöhung\|Attributswerterhöhung]], [[3-Compendium/Klassen/Mönch/Mönch#Sturz abfedern\|Sturz abfedern]]                                                                                      |     +2      |     1W6     |      4      |         +3 m         |
|   5   | [[3-Compendium/Klassen/Mönch/Mönch#Betäubender Schlag\|Betäubender Schlag]], [[3-Compendium/Klassen/Mönch/Mönch#Zusätzlicher Angriff\|Zusätzlicher Angriff]]                                                                                |     +3      |     1W8     |      5      |         +3 m         |
|   6   | [[3-Compendium/Klassen/Mönch/Mönch#Mächtige Schläge\|Mächtige Schläge]], Unterklassenmerkmal                                                                                                                                                |     +3      |     1W8     |      6      |        +4,5 m        |
|   7   | [[3-Compendium/Klassen/Mönch/Mönch#Entrinnen\|Entrinnen]]                                                                                                                                                                                   |     +3      |     1W8     |      7      |        +4,5 m        |
|   8   | [[3-Compendium/Klassen/Mönch/Mönch#Attributswerterhöhung\|Attributswerterhöhung]]                                                                                                                                                           |     +3      |     1W8     |      8      |        +4,5 m        |
|   9   | [[3-Compendium/Klassen/Mönch/Mönch#Akrobatische Bewegung\|Akrobatische Bewegung]]                                                                                                                                                           |     +4      |     1W8     |      9      |        +4,5 m        |
|  10   | [[3-Compendium/Klassen/Mönch/Mönch#Erhöhter Fokus\|Erhöhter Fokus]], [[3-Compendium/Klassen/Mönch/Mönch#Selbstwiederherstellung\|Selbstwiederherstellung]]                                                                                  |     +4      |     1W8     |     10      |         +6 m         |
|  11   | Unterklassenmerkmal                                                                                                                                                                                                                         |     +4      |    1W10     |     11      |         +6 m         |
|  12   | [[3-Compendium/Klassen/Mönch/Mönch#Attributswerterhöhung\|Attributswerterhöhung]]                                                                                                                                                           |     +4      |    1W10     |     12      |         +6 m         |
|  13   | [[3-Compendium/Klassen/Mönch/Mönch#Energie umleiten\|Energie umleiten]]                                                                                                                                                                     |     +5      |    1W10     |     13      |         +6 m         |
|  14   | [[3-Compendium/Klassen/Mönch/Mönch#Der disziplinierte überlebende\|Der disziplinierte überlebende]]                                                                                                                                         |     +5      |    1W10     |     14      |        +7,5 m        |
|  15   | [[3-Compendium/Klassen/Mönch/Mönch#Perfekter Fokus\|Perfekter Fokus]]                                                                                                                                                                       |     +5      |    1W10     |     15      |        +7,5 m        |
|  16   | [[3-Compendium/Klassen/Mönch/Mönch#Attributswerterhöhung\|Attributswerterhöhung]]                                                                                                                                                           |     +5      |    1W10     |     16      |        +7,5 m        |
|  17   | Unterklassenmerkmal                                                                                                                                                                                                                         |     +6      |    1W12     |     17      |        +7,5 m        |
|  18   | [[3-Compendium/Klassen/Mönch/Mönch#Überlegene Verteidigung\|Überlegene Verteidigung]]                                                                                                                                                       |     +6      |    1W12     |     18      |         +9 m         |
|  19   | [[3-Compendium/Klassen/Mönch/Mönch#Epische Gabe\|Epische Gabe]]                                                                                                                                                                             |     +6      |    1W12     |     19      |         +9 m         |
|  20   | [[3-Compendium/Klassen/Mönch/Mönch#Körper und Geist\|Körper und Geist]]                                                                                                                                                                     |     +6      |    1W12     |     20      |         +9 m         |


## Stufe 1
### Kampfkünste 

Deine Vertrautheit mit Kampfkünsten lässt dich folgende Kampfstile mit waffenlosen Angriffen sowie mit Mönchswaffen beherrschen: 

- Einfache Nahkampfwaffen 

- Nahkampf‑Kriegswaffen mit der Eigenschaft Leicht 

Du erhältst folgende Vorzüge, wenn du unbewaffnet bist oder nur Mönchswaffen verwendest und weder Rüstung noch Schild trägst: 

**_Waffenloser Bonusangriff:_** Du kannst als Bonusaktion einen waffenlosen Angriff ausführen. 

**_Kampfkünste-Würfel:_** Bei waffenlosen Angriffen oder im Kampf mit Mönchswaffen kannst du mit 1W6 statt mit dem normalen Schadenswürfel würfeln. Dieser Würfel verändert sich auf höheren Mönchsstufen, wie in der Spalte „Kampfkünste“ der Tabelle „Mönchsmerkmale“ aufgeführt. 

**_Geschickte Angriffe:_** Du kannst für deine Angriffs‑ und Schadenswürfe mit waffenlosen Angriffen oder Mönchswaffen deinen Geschicklichkeitsmodifikator statt des Stärkemodifikators verwenden. Außerdem kannst du, wenn du die Packen‑ oder die Stoßen‑Option deines waffenlosen Angriffs verwendest, deinen Geschicklichkeitsmodifikator statt des Stärkemodifikators verwenden, um den Rettungswurf‑SG zu bestimmen. 

### Ungerüstete Verteidigung 

Solange du weder Rüstung noch Schild trägst, entspricht deine Basis‑Rüstungsklasse 10 plus deinem Geschicklichkeitsmodifikator plus deinem Weisheitsmodifikator. 
## Stufe 2
### Mönchsfokus 

Dein Fokus und deine Vertrautheit mit Kampfkünsten gestatten dir, eine Quelle außergewöhnlicher Energie in dir selbst zu nutzen. Diese Energie wird durch Fokuspunkte repräsentiert. Deine Mönchsstufe bestimmt die Anzahl deiner Punkte, die in der Spalte „Fokuspunkte“ der Tabelle „Mönchsmerkmale“ aufgeführt sind. 

Du kannst diese Punkte verbrauchen, um bestimmte Mönchsmerkmale einzusetzen oder zu verstärken. Zu Beginn kennst du drei solche Merkmale: Geduldige Verteidigung, Schlaghagel und Windschritt (jeweils unten beschrieben). 

Wenn du einen Fokuspunkt verbrauchst, ist er nicht mehr verfügbar. Du erhältst verbrauchte Fokuspunkte nach einer kurzen oder langen Rast zurück. 

Manche Merkmale, die Fokuspunkte verwenden, erfordern, dass das Ziel einen Rettungswurf ausführt. Der Rettungswurf‑SG entspricht 8 plus deinem Weisheitsmodifikator plus deinem Übungsbonus. 

**_Schlaghagel:_** Du kannst 1 Fokuspunkt verbrauchen, um zwei waffenlose Angriffe als Bonusaktion auszuführen. 

**_Geduldige Verteidigung:_** Du kannst die Rückzug‑ Aktion als Bonusaktion ausführen. Alternativ kannst du 1 Fokuspunkt verbrauchen, um sowohl die Rückzug‑ als auch die Ausweichaktion als Bonusaktion auszuführen. 

**_Windschritt:_** Du kannst die Spurt‑Aktion als Bonusaktion ausführen. Alternativ kannst du 1 Fokuspunkt verbrauchen, um sowohl die 

Rückzug‑ als auch die Spurt‑Aktion als Bonusaktion auszuführen, und deine Sprungdistanz ist in diesem Zug verdoppelt. 

### Ungerüstete Bewegung 

Deine Bewegungsrate erhöht sich um drei Meter, sofern du weder Rüstung noch Schild trägst. Dieser Bonus erhöht sich, wenn du bestimmte Mönchsstufen erreichst, wie in der Tabelle „Mönchsmerkmale“ angegeben. 

### Unglaublicher Stoffwechsel 

Wenn du die Initiative auswürfelst, kannst du alle verbrauchten Fokuspunkte zurückerhalten. Würfle dazu mit deinem Kampfkünste-Würfel. Du erhältst eine Anzahl von Trefferpunkten in Höhe deiner Mönchsstufe plus des Ergebnisses zurück. 

Du kannst dieses Merkmal erst nach einer langen Rast erneut verwenden. 
## Stufe 3
### Angriffe umleiten 

Wenn ein Angriffswurf dich trifft und dir Hieb‑, Stich‑ oder Wuchtschaden zufügt, kannst du eine Reaktion ausführen, um den Gesamtschaden des Angriffs zu verringern. Die Verringerung entspricht 1W10 plus deinem Geschicklichkeitsmodifikator plus deiner Mönchsstufe. 

Wird der Schaden auf 0 verringert, so kannst du 1 Fokuspunkt verbrauchen, um einen Teil der Angriffsenergie umzuleiten. Wenn der Angriff ein Nahkampfangriff war, wähle dazu eine Kreatur im Abstand von bis zu 1,5 Metern von dir aus, die du sehen kannst. Wenn der Angriff ein Fernkampfangriff war, wähle eine Kreatur im Abstand von bis zu 18 Metern von dir aus, die du sehen kannst und die nicht über vollständige Deckung verfügt. Diese Kreatur muss einen Geschicklichkeitsrettungswurf bestehen, oder sie erleidet Schaden in Höhe von zwei Würfen mit deinem Kampfkünste-Würfel plus deinem Geschicklichkeitsmodifikator. Die Schadensart entspricht der des Angriffs. 

### Mönch-Unterklasse
Du erhältst eine Mönch‑Unterklasse deiner Wahl. Die Unterklasse Krieger der Offenen Hand wird nach der Beschreibung dieser Klasse erläutert. Unterklassen sind Spezialisierungen, die dir auf bestimmten Mönchsstufen Merkmale gewähren. Du erhältst für den Rest deiner Laufbahn alle Merkmale deiner Unterklasse, die zu deiner aktuellen Mönchsstufe oder den niedrigeren Stufen gehören. 
## Stufe 4
### Attributswerterhöhung 

Du erhältst das Talent Attributswerterhöhung (siehe „Talente“) oder ein anderes Talent deiner Wahl, für das du qualifiziert bist. Du erhältst dieses Merkmal auf der 8., 12. und 16. Mönchsstufe erneut. 

**71** Systemreferenzdokument 5.2.1 

### Sturz abfedern 

Wenn du stürzt, kannst du eine Reaktion ausführen, um den Sturzschaden um einen Betrag in Höhe des Fünffachen deiner Mönchsstufe zu verringern. 
## Stufe 5
### Betäubender Schlag 

Einmal pro Zug kannst du, wenn du eine Kreatur mit einer Mönchswaffe oder einem waffenlosen Angriff triffst, 1 Fokuspunkt verbrauchen, um einen Betäubenden Schlag zu versuchen. Das Ziel muss einen Konstitutionsrettungswurf ausführen. Misslingt der Wurf, so ist das Ziel bis zum Beginn deines nächsten Zugs betäubt. Bei einem erfolgreichen Rettungswurf ist die Bewegungsrate des Ziels bis zum Beginn deines nächsten Zugs halbiert, und der nächste Angriffswurf gegen das Ziel während dieser Dauer ist im Vorteil. 

### Zusätzlicher Angriff 

Du kannst jetzt zweimal angreifen, wenn du in deinem Zug eine Angriffsaktion ausführst. 
## Stufe 6
### Mächtige Schläge 

Wann immer du mit deinem waffenlosen Angriff Schaden bewirkst, kannst du damit auch Energie‑ schaden oder die normale Schadensart (nach deiner Wahl) bewirken. 
## Stufe 7
### Entrinnen 

Bist du einem Effekt ausgesetzt, der dir einen Geschicklichkeitsrettungswurf erlaubt, um den Schaden zu halbieren, so erleidest du stattdessen bei einem Erfolg gar keinen und bei einem Misserfolg den halben Schaden. 

Du erhältst den Vorzug dieses Merkmals nicht, wenn du kampfunfähig bist. 
## Stufe 9
### Akrobatische Bewegung 

Sofern du weder Rüstung noch Schild trägst, erhältst du die Fähigkeit, dich in deinem Zug an vertikalen Oberflächen oder auf Flüssigkeiten zu bewegen, ohne zu stürzen. 
## Stufe 10
### Erhöhter Fokus 

Geduldige Verteidigung, Schlaghagel und Windschritt erhalten folgende Vorzüge. 

**_Schlaghagel:_** Du kannst 1 Fokuspunkt ver‑ brauchen, um Schlaghagel einzusetzen und damit drei waffenlose Angriffe statt zwei auszuführen. 

**_Geduldige Verteidigung:_** Wenn du einen Fokus‑ punkt verbrauchst, um Geduldige Verteidigung einzusetzen, erhältst du eine Anzahl von temporären Trefferpunkten in Höhe von zwei Würfen mit deinem Kampfkünste-Würfel. 

**_Windschritt:_** Wenn du einen Fokuspunkt verbrauchst, um Windschritt einzusetzen, kannst du eine bereitwillige Kreatur im Abstand von bis zu 1,5 Metern von dir und von höchstens großer 

Größe auswählen. Diese Kreatur bewegt sich bis zum Ende deines Zugs mit dir. Die Bewegung der Kreatur provoziert keine Gelegenheitsangriffe. 

### Selbstwiederherstellung 

Durch schiere Willenskraft kannst du am Ende jedes deiner Züge einen der folgenden Zustände von dir selbst entfernen: Bezaubert, Verängstigt oder Vergiftet. 

Außerdem erhältst du keine Erschöpfungsstufen, wenn du keine Nahrung und keine Flüssigkeit zu dir nimmst. 
## Stufe 13
### Energie umleiten 

Du kannst jetzt dein Merkmal Angriffe umleiten auch gegen Angriffe einsetzen, die eine beliebige andere Schadensart als Hieb‑, Stich‑ oder Wuchtschaden bewirken. 
## Stufe 14
### Der disziplinierte Überlebende 

Deine körperliche und mentale Disziplin gibt dir Übung in allen Rettungswürfen. 

Außerdem kannst du, wann immer du bei einem Rettungswurf scheiterst, 1 Fokuspunkt verbrauchen, um erneut zu würfeln. In diesem Fall musst du das neue Ergebnis verwenden. 
## Stufe 15
### Perfekter Fokus 

Wenn du die Initiative auswürfelst und nicht Unglaublicher Stoffwechsel verwendest, erhältst du verbrauchte Fokuspunkte zurück, bis du 4 davon hast, sofern du höchstens 3 Punkte hast. 
## Stufe 18
### Überlegene Verteidigung 

Zu Beginn deines Zugs kannst du 3 Fokuspunkte verbrauchen, um dich eine Minute lang – oder bis du kampfunfähig wirst – vor Schaden zu schützen. In dieser Zeit bist du gegen alle Schadensarten außer Energieschaden resistent. 
## Stufe 19
### Epische Gabe 

Du erhältst ein Epische‑Gabe‑Talent (siehe „Talente“) oder ein anderes Talent deiner Wahl, für das du qualifiziert bist. Gabe des Unwiderstehlichen Angriffs wird empfohlen. 
## Stufe 20
### Körper und Geist 

Du hast Körper und Geist auf neue Höhen weiter‑ entwickelt. Deine Werte für Geschicklichkeit und Weisheit werden um 4 erhöht (auf höchstens 25). 