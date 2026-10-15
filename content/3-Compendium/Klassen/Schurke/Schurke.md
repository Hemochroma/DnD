---
Trefferwürfel: W8
PrimärAttribut:
  - Geschicklichkeit
Rettungswürfe:
  - Geschicklichkeit
  - Intelligenz
Rüstung:
  - Leichte
Waffen:
  - Einfache Waffen
  - Leichte Kriegswaffen
  - Finesse Kriegswaffen
Icon: "[[Rogue_logo.png]]"
---

> [!infobox]
> # Roguee
> ![[Rogue_logo.png|120]]
> **Trefferwürfel:** 1W8 pro Stufe
> **Primäres Attribut:** Geschicklichkeit
> **Rettungswürfe:** Geschicklichkeit & Intelligenz
> **Rüstung:** Leichte
> **Waffen:** Einfache Waffen, Kriegswaffen mit der Eigenschaft Leicht oder Finesse
> **Werkzeuge:** Diebeswerkzeug
> **Fähigkeiten:** _Wähle vier aus:_
> - Akrobatik
> - Athletik
> - Einschüchtern
> - Fingerfertigkeit
> - Heimlichkeit
> - Motiv erkennen
> - Nachforschun­gen
> - Täuschen
> - Überzeugen
> - Wahrnehmung

![[z_Assets/classes/Rogue/Rogue.png]]

# Ein Schurke werden ... 

## Als Charakter der 1. Stufe 

- Du erhältst alle Merkmale in der Tabelle „Hauptmerkmale des Schurken“. 
- Du erhältst die Merkmale der 1. Schurkenstufe, die in der Tabelle „Schurkenmerkmale“ aufgeführt sind. 
## Anfangsausrüstung
Du beginnst mit der folgenden Ausrüstung, zusätzlich zu den Ausrüstungen, die durch Ihren Hintergrund gewährt werden:
- Lederrüstung, zwei Dolche, Kurzschwert, Kurzbogen, 20 Pfeile, Köcher, Diebeswerkzeug, Einbrecherausrüstung und 8 GM
- 100 GM
## Als Charakter mit Klassenkombination 

- Du erhältst folgende Merkmale in der Tabelle „Hauptmerkmale des Schurken“: Trefferpunkte‑ würfel, Übung in einer Fertigkeit deiner Wahl von der Fertigkeitenliste des Schurken, Übung im Umgang mit Diebeswerkzeug, Vertrautheit mit leichter Rüstung. 

- Du erhältst die Merkmale der 1. Schurkenstufe, die in der Tabelle „Schurkenmerkmale“ aufgeführt sind. 

# Klassenmerkmale des Schurken 
## Unterklassen

```base
views:
  - type: cards
    name: Tabelle
    filters:
      and:
        - file.inFolder("3-Compendium/Klassen/Schurke/Unterklassen")
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
Als Schurke erhältst du auf den angegebenen Schurkenstufen folgende Klassenmerkmale. Diese Merkmale sind in der Tabelle „Schurkenmerkmale“ aufgeführt. 

| Stufe | Klassenmerkmale                                                                                                                                                                                                                                                                                                | Übungsbonus | Hinterhältiger Angriff |
|:-----:| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |:-----------:|:----------------------:|
|   1   | [[3-Compendium/Klassen/Schurke/Schurke#Diebessprache\|Diebessprache]], [[3-Compendium/Klassen/Schurke/Schurke#Expertise\|Expertise]], [[3-Compendium/Klassen/Schurke/Schurke#Hinterhältiger Angriff\|Hinterhältiger Angriff]], [[3-Compendium/Klassen/Schurke/Schurke#Waffenbeherrschung\|Waffenbeherrschung]] |     +2      |          1W6           |
|   2   | [[3-Compendium/Klassen/Schurke/Schurke#Raffinierte Aktion\|Raffinierte Aktion]]                                                                                                                                                                                                                                |     +2      |          1W6           |
|   3   | Schurken­ Unterklasse, [[3-Compendium/Klassen/Schurke/Schurke#Zielsicher\|Zielsicher]]                                                                                                                                                                                                                         |     +2      |          2W6           |
|   4   | [[3-Compendium/Klassen/Schurke/Schurke#Attributswerterhöhung\|Attributswerterhöhung]]                                                                                                                                                                                                                          |     +2      |          2W6           |
|   5   | [[3-Compendium/Klassen/Schurke/Schurke#Raffinierter Schlag\|Raffinierter Schlag]], [[3-Compendium/Klassen/Schurke/Schurke#Unglaubliches Ausweichen\|Unglaubliches Ausweichen]]                                                                                                                                 |     +3      |          3W6           |
|   6   | [[3-Compendium/Klassen/Schurke/Schurke#Expertise\|Expertise]]                                                                                                                                                                                                                                                  |     +3      |          3W6           |
|   7   | [[3-Compendium/Klassen/Schurke/Schurke#Entrinnen\|Entrinnen]], [[3-Compendium/Klassen/Schurke/Schurke#Verlässliches Talent\|Verlässliches Talent]]                                                                                                                                                             |     +3      |          4W6           |
|   8   | [[3-Compendium/Klassen/Schurke/Schurke#Attributswerterhöhung\|Attributswerterhöhung]]                                                                                                                                                                                                                          |     +3      |          4W6           |
|   9   | Unterklassenmerkmal                                                                                                                                                                                                                                                                                            |     +4      |          5W6           |
|  10   | [[3-Compendium/Klassen/Schurke/Schurke#Attributswerterhöhung\|Attributswerterhöhung]]                                                                                                                                                                                                                          |     +4      |          5W6           |
|  11   | [[3-Compendium/Klassen/Schurke/Schurke#Verbesserter Raffinierter Schlag\|Verbesserter Raffinierter Schlag]]                                                                                                                                                                                                    |     +4      |          6W6           |
|  12   | [[3-Compendium/Klassen/Schurke/Schurke#Attributswerterhöhung\|Attributswerterhöhung]]                                                                                                                                                                                                                          |     +4      |          6W6           |
|  13   | Unterklassenmerkmal                                                                                                                                                                                                                                                                                            |     +5      |          7W6           |
|  14   | [[3-Compendium/Klassen/Schurke/Schurke#Hinterhältige Schläge\|Hinterhältige Schläge]]                                                                                                                                                                                                                          |     +5      |          7W6           |
|  15   | [[3-Compendium/Klassen/Schurke/Schurke#Entschlüpfender Geist\|Entschlüpfender Geist]]                                                                                                                                                                                                                          |     +5      |          8W6           |
|  16   | [[3-Compendium/Klassen/Schurke/Schurke#Attributswerterhöhung\|Attributswerterhöhung]]                                                                                                                                                                                                                          |     +5      |          8W6           |
|  17   | Unterklassenmerkmal                                                                                                                                                                                                                                                                                            |     +6      |          9W6           |
|  18   | [[3-Compendium/Klassen/Schurke/Schurke#Schwer zu fassen\|Schwer zu fassen]]                                                                                                                                                                                                                                    |     +6      |          9W6           |
|  19   | [[3-Compendium/Klassen/Schurke/Schurke#Epische Gabe\|Epische Gabe]]                                                                                                                                                                                                                                            |     +6      |          10W6          |
|  20   | [[3-Compendium/Klassen/Schurke/Schurke#Glückstreffer\|Glückstreffer]]                                                                                                                                                                                                                                          |     +6      |          10W6          |

## Stufe 1
### Diebessprache 

Du hast verschiedene Sprachen in den Gemeinschaften gelernt, in denen du dir deine Schurkentalente zugelegt hast. Du beherrschst die Diebessprache und eine andere Sprache deiner Wahl, die du aus den Sprachentabellen unter „Charaktererstellung“ auswählen kannst. 

### Expertise 

Du erhältst Expertise in zwei Fertigkeiten deiner Wahl, in denen du geübt bist. Fingerfertigkeit und Heimlichkeit werden empfohlen, wenn du in ihnen geübt bist. 

Auf der 6. Schurkenstufe erhältst du Expertise in zwei weiteren Fertigkeiten deiner Wahl, in denen du geübt bist. 

### Hinterhältiger Angriff 

Du weißt, wie man die Ablenkung eines Gegners ausnutzt und subtil zuschlägt. Einmal pro Zug kannst du einer Kreatur, die du mit einem 

Angriffswurf triffst, 1W6 zusätzlichen Schaden zufügen, sofern du beim Wurf im Vorteil bist und eine Finesse‑ oder Fernkampfwaffe einsetzt. Der zusätzliche Schaden ist von der gleichen Art wie der Schaden der Waffe. 

Es ist kein Vorteil beim Angriffswurf erforderlich, wenn mindestens einer deiner Verbündeten sich im Abstand von bis zu 1,5 Metern vom Ziel befindet, sofern der Verbündete nicht kampfunfähig ist und du beim Angriffswurf nicht im Nachteil bist. 

Der zusätzliche Schaden wird erhöht, wenn du weitere Schurkenstufen erhältst, wie in der Spalte „Hinterhältiger Angriff“ der Tabelle „Schurkenmerkmale“ dargestellt. 

### Waffenbeherrschung 

Deine Vertrautheit mit Waffen erlaubt dir, die Meisterschaftseigenschaften zweier Waffenarten deiner Wahl zu verwenden, sofern du Übung im Umgang mit diesen hast, beispielsweise Dolche und Kurzbögen. 

Wann immer du eine lange Rast beendest, kannst du die Art der ausgewählten Waffen ändern. Beispiel: Du könntest beschließen, die Meisterschaftseigenschaft von Krummsäbeln und Kurzschwertern zu verwenden. 

## Stufe 2

### Raffinierte Aktion 

Dank deiner Auffassungsgabe und deiner Beweglichkeit kannst du dich besonders schnell bewegen und rasch handeln. In deinem Zug kannst du eine der folgenden Aktionen als Bonusaktion ausführen: Rückzug, Spurt oder Verstecken. 

## Stufe 3
### Schurken-Unterklasse 

Du erhältst eine Schurken‑Unterklasse deiner Wahl. Die Unterklasse Dieb wird nach der Beschreibung dieser Klasse erläutert. Unterklassen sind Spezialisierungen, die dir auf bestimmten Schurkenstufen Merkmale gewähren. Du erhältst für den Rest deiner Laufbahn alle Merkmale deiner Unterklasse, die zu deiner aktuellen Schurkenstufe oder den niedrigeren Stufen gehören. 

### Zielsicher 

Als Bonusaktion bewirkst du, dass dein nächster Angriffswurf im aktuellen Zug im Vorteil ist. Du kannst dieses Merkmal nur anwenden, wenn du dich in diesem Zug noch nicht bewegt hast. Nach der Bonusaktion beträgt deine Bewegungsrate bis zum Ende des Zugs 0. 
## Stufe 4
### Attributswerterhöhung 

Du erhältst das Talent Attributswerterhöhung (siehe „Talente“) oder ein anderes Talent deiner Wahl, für das du qualifiziert bist. Du erhältst dieses Merkmal auf der 8., 10., 12. und 16. Schurkenstufe erneut. 
## Stufe 5
### Raffinierter Schlag 

Du hast raffinierte Methoden entwickelt, deinen Hinterhältigen Angriff einzusetzen. Wenn du mit diesem Schaden bewirkst, kannst du einen der folgenden Effekte von Raffinierter Schlag hinzufügen. Jeder Effekt hat Würfelkosten in Form der Schadenswürfel für Hinterhältiger Angriff, auf die du verzichten musst, um den Effekt hinzuzufügen. Du musst diese Würfel vor dem Wurf entfernen, und der Effekt tritt auf, sobald der Schaden des Angriffs bewirkt wurde. Beispiel: Wenn du den Gift‑Effekt hinzufügst, entfernst du 1W6 von den Schadenswürfeln des Hinterhältigen Angriffs, bevor du würfelst. 

Wenn ein Effekt von Raffinierter Schlag einen Rettungswurf erfordert, entspricht der SG 8 plus deinem Geschicklichkeitsmodifikator plus deinem Übungsbonus. 

**_Fällen (Kosten: 1W6):_** Wenn das Ziel von höchstens großer Größe ist, muss es einen Geschicklichkeitsrettungswurf bestehen, oder es wird umgestoßen. 

**_Gift (Kosten: 1W6):_** Du fügst deinem Schlag ein Toxin hinzu, welches das Ziel zu einem Konstitutionsrettungswurf zwingt. Misslingt der 

Wurf, so ist die Kreatur eine Minute lang vergiftet. Das vergiftete Ziel wiederholt den Rettungswurf am Ende jedes seiner Züge. Bei einem Erfolg endet der Effekt. 

Du musst eine Giftmischerausrüstung bei dir haben, um diesen Effekt zu bewirken. 

**_Zurückziehen (Kosten: 1W6):_** Sofort nach dem Angriff nutzt du bis zur Hälfte deiner Bewegungsrate, ohne Gelegenheitsangriffe zu provozieren. 

### Unglaubliches Ausweichen 

Trifft dich ein Angreifer, den du sehen kannst, mit einem Angriffswurf, so kannst du eine Reaktion ausführen, um den Schaden des Angriffs zu halbieren (abgerundet). 
## Stufe 7
### Entrinnen 

Du kannst bestimmten Gefahren geschickt ausweichen. Bist du einem Effekt ausgesetzt, der dir einen Geschicklichkeitsrettungswurf erlaubt, um den Schaden zu halbieren, so erleidest du stattdessen bei einem Erfolg gar keinen und bei einem Misserfolg den halben Schaden. Du kannst dieses Merkmal nicht einsetzen, wenn du kampfunfähig bist. 

### Verlässliches Talent 

Wann immer du einen Attributswurf ausführst, der eine deiner Übungen in Fertigkeiten oder im Umgang mit Werkzeug nutzt, kannst du ein W20‑ Ergebnis von 9 oder darunter als 10 werten. 
## Stufe 11
### Verbesserter Raffinierter Schlag 

Wenn du mit Hinterhältiger Angriff Schaden bewirkst, kannst du bis zu zwei der folgenden Effekte von Raffinierter Schlag hinzufügen, sofern du die jeweiligen Würfelkosten bezahlst. 
## Stufe 14
### Hinterhältige Schläge 

Du hast dich in neuen Methoden geübt, deinen Hinterhältigen Angriff auf besonders verschlagene Art auszuführen. Nun stehen folgende Effekte von Raffinierter Schlag zur Auswahl: 

**_Irritieren (Kosten: 2W6):_** Das Ziel muss einen Konstitutionsrettungswurf bestehen, oder es kann in seinem nächsten Zug nur eine der folgenden Handlungen vollziehen: sich bewegen, eine Aktion ausführen oder eine Bonusaktion ausführen. 

**_Lahmlegen (Kosten: 6W6):_** Das Ziel muss einen Konstitutionsrettungswurf bestehen, andernfalls ist es eine Minute lang – oder bis es Schaden erleidet – bewusstlos. Das bewusstlose Ziel wiederholt den Rettungswurf am Ende jedes seiner Züge. Bei einem Erfolg endet der Effekt. 

**_Verdunkeln (Kosten: 3W6):_** Das Ziel muss einen Geschicklichkeitsrettungswurf bestehen, oder es ist bis zum Ende seines nächsten Zugs blind. 

## Stufe 15
### Entschlüpfender Geist 

Dein raffinierter Verstand ist außergewöhnlich schwierig zu kontrollieren. Du erhältst Übung in Weisheits‑ und Charismarettungswürfen. 
## Stufe 18
### Schwer zu fassen 

Du kannst derart gut ausweichen, dass Angreifer kaum noch die Oberhand gegen dich gewinnen. Kein Angriffswurf gegen dich kann im Vorteil sein, solange du nicht kampfunfähig bist. 
## Stufe 19
### Epische Gabe 

Du erhältst ein Epische‑Gabe‑Talent (siehe „Talente“) oder ein anderes Talent deiner Wahl, für das du qualifiziert bist. Gabe des Nachtgeists wird empfohlen. 
## Stufe 20
### Glückstreffer 

Du bist beneidenswert gut darin, Erfolg zu haben, wenn es darauf ankommt. Wenn du bei einer W20‑Prüfung scheiterst, kannst du das Ergebnis in eine 20 verwandeln. 

Du kannst dieses Merkmal erst nach einer kurzen oder langen Rast erneut verwenden. 