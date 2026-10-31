---
srd: "criatura/mummy-lord"
tags:
  - "srd/kreatur"
typ: "Kleiner oder mittelgroßer Untoter (Kleriker), rechtschaffen böse"
gruppe: "Mumien"
hg: "15"
ep: 13000
rk: 17
tp: 187
initiative: 10
statblock: true
layout: "Compendio SRD 2024 (Deutsch)"
name: "Mumienfürst"
type: "Kleiner oder mittelgroßer Untoter (Kleriker), rechtschaffen böse"
ac: 17
hp: 187
hit_dice: "25d8+75"
modifier: 10
speed: "9 m"
stats:
  - 18
  - 10
  - 17
  - 11
  - 19
  - 16
initiative_text: "+10 (20)"
hp_text: "187 (25W8+75)"
stats_table: "|   |   | MOD | RW |   |   | MOD | RW |   |   | MOD | RW |\n| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |\n| **Stä** | 18 | +4 | +4 | **Ges** | 10 | +0 | +0 | **Kon** | 17 | +3 | +3 |\n| **Int** | 11 | +0 | +5 | **Wei** | 19 | +4 | +9 | **Cha** | 16 | +3 | +3 |"
skills_text: "Geschichte +5, Religion +5, Wahrnehmung +9"
immunities_text: "Gift, Nekrotisch; [[3-Compendium/Zustände/Bezaubert|Bezaubert]], Erschöpft, [[3-Compendium/Zustände/Gelähmt|Gelähmt]], [[3-Compendium/Zustände/Verängstigt|Verängstigt]], [[3-Compendium/Zustände/Vergiftet|Vergiftet]]"
cr_text: "15 (EP 13.000 oder 15.000 im Hort; ÜB +5)"
saves:
  - Int: 5
  - Wei: 9
skillsaves:
  - Geschichte: 5
  - Religion: 5
  - Wahrnehmung: 9
damage_vulnerabilities: "Feuer"
damage_immunities: "Gift, Nekrotisch"
condition_immunities: "Bezaubert, Erschöpft, Gelähmt, Verängstigt, Vergiftet"
senses: "Wahrer Blick 18 m; Passive Wahrnehmung 19"
languages: "Gemeinsprache und drei weitere Sprachen"
cr: 15
traits:
  - name: "Legendäre Resistenz (3-mal täglich, im Hort 4-mal täglich):"
    desc: "Wenn die Mumie bei einem Rettungswurf scheitert, kann sie beschließen, ihn stattdessen zu bestehen."
  - name: "Magieresistenz:"
    desc: "Die Mumie ist bei Rettungswürfen gegen Zauber und andere magische Effekte im Vorteil."
  - name: "Untote Genesung:"
    desc: "Wenn die Mumie zerstört wird, ihr Herz jedoch noch intakt ist, erhält sie nach 24 Stunden einen neuen Körper, der mit allen Trefferpunkten aufersteht. Der neue Körper erscheint in einem freien Bereich im Hort der Mumie. Das Herz ist ein winziger Gegenstand, besitzt eine RK von 17, 10 Trefferpunkte und ist gegen alle Schadensarten bis auf Feuerschaden immun."
actions:
  - name: "Mehrfachangriff:"
    desc: "Die Mumie führt einen Fäulnisfaust- oder einen Negative-Energie-kanalisieren-Angriff aus und setzt Fürchterliches Starren ein."
  - name: "Fäulnisfaust:"
    desc: "*Nahkampfangriffswurf:* +9, Reichweite 1,5 m. *Treffer:* 15 (2W10+4) Wuchtschaden plus 10 (3W6) nekrotischer Schaden. Wenn das Ziel eine Kreatur ist, wird es verflucht. Das verfluchte Ziel kann keine Trefferpunkte zurückerhalten, es erhält durch eine lange Rast keine Vorzüge, und sein Trefferpunktemaximum wird alle 24 Stunden um 10 (3W6) verringert. Wenn die Trefferpunkte einer Kreatur durch diesen Angriff auf 0 sinken, stirbt die Kreatur und zerfällt zu Staub."
  - name: "Negative Energie kanalisieren:"
    desc: "*Fernkampfangriffswurf:* +9, Reichweite 18 m. *Treffer:* 25 (6W6+4) nekrotischer Schaden."
  - name: "Fürchterliches Starren:"
    desc: "*Weisheitsrettungswurf:* SG 17; eine Kreatur im Abstand von bis zu 18 Metern von der Mumie, die von der Mumie gesehen werden kann. *Misserfolg:* 25 (6W6+4) psychischer Schaden, und das Ziel ist bis zum Beginn des nächsten Zugs der Mumie [[3-Compendium/Zustände/Gelähmt|gelähmt]]."
  - name: "Zauberwirken:"
    desc: "Die Mumie wirkt einen der folgenden Zauber mit Weisheit als Attribut zum Zauberwirken, ohne Materialkomponenten zu benötigen (Zauberrettungswurf-SG 17, +9 auf Treffer mit Zauberangriffen):\n\n- **Beliebig oft:** *[[3-Compendium/Zauber/Magie bannen|Magie bannen]]*, *[[3-Compendium/Zauber/Thaumaturgie|Thaumaturgie]]*\n- **Je 1-mal täglich:** *[[3-Compendium/Zauber/Insektenplage|Insektenplage]]* (Version des 7. Grades), *[[3-Compendium/Zauber/Leid|Leid]]*, *[[3-Compendium/Zauber/Tote beleben|Tote beleben]]*"
reactions:
  - name: "Wirbelwind aus Sand:"
    desc: "*Auslöser:* Die Mumie wird von einem Angriffswurf getroffen. *Antwort:* Die Mumie fügt ihrer RK gegen diesen Angriff 2 hinzu, sodass der Angriff möglicherweise misslingt, und sie teleportiert sich bis zu 18 Meter weit in einen freien Bereich, den sie sehen kann. Jede Kreatur ihrer Wahl im Abstand von bis zu 1,5 Metern von ihrem Zielbereich, die von ihr gesehen werden kann, ist bis zum Ende des nächsten Zugs der Mumie [[3-Compendium/Zustände/Blind|blind]]."
legendary_description: "*Anwendungen legendärer Aktionen: 3 (4 im Hort). Unmittelbar nach dem Zug einer anderen Kreatur kann die Mumie eine legendäre Aktion ausführen. Zu Beginn jedes ihrer Züge stehen der Mumie wieder alle ausgeführten legendären Aktionen zur Verfügung.*"
legendary_actions:
  - name: "Nekrotischer Schlag:"
    desc: "Die Mumie führt einen Fäulnisfaust- oder einen Negative-Energie-kanalisieren-Angriff aus."
  - name: "Schreckensbefehl:"
    desc: "Die Mumie wirkt den Zauber *[[3-Compendium/Zauber/Befehl|Befehl]]* (Version des 2. Grades). Ihr Attribut zum Zauberwirken ist dasselbe wie beim Ausführen der Zauberwirken-Aktion. Die Mumie kann diese Aktion erst nach Beginn ihres nächsten Zugs erneut ausführen."
  - name: "Starren:"
    desc: "Die Mumie setzt Fürchterliches Starren ein. Die Mumie kann diese Aktion erst nach Beginn ihres nächsten Zugs erneut ausführen."
---

> [!srd-ficha] Mumienfürst
> *Kleiner oder mittelgroßer Untoter (Kleriker), rechtschaffen böse*
>
> **RK** 17 · **Initiative** +10 (20)
>
> **TP** 187 (25W8+75)
>
> **Bewegungsrate** 9 m
>
> |   |   | MOD | RW |   |   | MOD | RW |   |   | MOD | RW |
> | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
> | **Stä** | 18 | +4 | +4 | **Ges** | 10 | +0 | +0 | **Kon** | 17 | +3 | +3 |
> | **Int** | 11 | +0 | +5 | **Wei** | 19 | +4 | +9 | **Cha** | 16 | +3 | +3 |
>
> **Fertigkeiten** Geschichte +5, Religion +5, Wahrnehmung +9
>
> **Anfälligkeiten** Feuer
>
> **Immunitäten** Gift, Nekrotisch; [[Bezaubert|Bezaubert]], Erschöpft, [[Gelähmt|Gelähmt]], [[Verängstigt|Verängstigt]], [[Vergiftet|Vergiftet]]
>
> **Sinne** Wahrer Blick 18 m; Passive Wahrnehmung 19
>
> **Sprachen** Gemeinsprache und drei weitere Sprachen
>
> **HG** 15 (EP 13.000 oder 15.000 im Hort; ÜB +5)

## Merkmale

***Legendäre Resistenz (3-mal täglich, im Hort 4-mal täglich):*** Wenn die Mumie bei einem Rettungswurf scheitert, kann sie beschließen, ihn stattdessen zu bestehen.

***Magieresistenz:*** Die Mumie ist bei Rettungswürfen gegen Zauber und andere magische Effekte im Vorteil.

***Untote Genesung:*** Wenn die Mumie zerstört wird, ihr Herz jedoch noch intakt ist, erhält sie nach 24 Stunden einen neuen Körper, der mit allen Trefferpunkten aufersteht. Der neue Körper erscheint in einem freien Bereich im Hort der Mumie. Das Herz ist ein winziger Gegenstand, besitzt eine RK von 17, 10 Trefferpunkte und ist gegen alle Schadensarten bis auf Feuerschaden immun.

## Aktionen

***Mehrfachangriff:*** Die Mumie führt einen Fäulnisfaust- oder einen Negative-Energie-kanalisieren-Angriff aus und setzt Fürchterliches Starren ein.

***Fäulnisfaust:*** *Nahkampfangriffswurf:* +9, Reichweite 1,5 m. *Treffer:* 15 (2W10+4) Wuchtschaden plus 10 (3W6) nekrotischer Schaden. Wenn das Ziel eine Kreatur ist, wird es verflucht. Das verfluchte Ziel kann keine Trefferpunkte zurückerhalten, es erhält durch eine lange Rast keine Vorzüge, und sein Trefferpunktemaximum wird alle 24 Stunden um 10 (3W6) verringert. Wenn die Trefferpunkte einer Kreatur durch diesen Angriff auf 0 sinken, stirbt die Kreatur und zerfällt zu Staub.

***Negative Energie kanalisieren:*** *Fernkampfangriffswurf:* +9, Reichweite 18 m. *Treffer:* 25 (6W6+4) nekrotischer Schaden.

***Fürchterliches Starren:*** *Weisheitsrettungswurf:* SG 17; eine Kreatur im Abstand von bis zu 18 Metern von der Mumie, die von der Mumie gesehen werden kann. *Misserfolg:* 25 (6W6+4) psychischer Schaden, und das Ziel ist bis zum Beginn des nächsten Zugs der Mumie gelähmt.

***Zauberwirken:*** Die Mumie wirkt einen der folgenden Zauber mit Weisheit als Attribut zum Zauberwirken, ohne Materialkomponenten zu benötigen (Zauberrettungswurf-SG 17, +9 auf Treffer mit Zauberangriffen):

- **Beliebig oft:** *[[Magie bannen|Magie bannen]]*, *[[Thaumaturgie|Thaumaturgie]]*
- **Je 1-mal täglich:** *[[Insektenplage|Insektenplage]]* (Version des 7. Grades), *[[Leid|Leid]]*, *[[Tote beleben|Tote beleben]]*

## Reaktionen

***Wirbelwind aus Sand:*** *Auslöser:* Die Mumie wird von einem Angriffswurf getroffen. *Antwort:* Die Mumie fügt ihrer RK gegen diesen Angriff 2 hinzu, sodass der Angriff möglicherweise misslingt, und sie teleportiert sich bis zu 18 Meter weit in einen freien Bereich, den sie sehen kann. Jede Kreatur ihrer Wahl im Abstand von bis zu 1,5 Metern von ihrem Zielbereich, die von ihr gesehen werden kann, ist bis zum Ende des nächsten Zugs der Mumie [[Blind|blind]].

## Legendäre Aktionen

*Anwendungen legendärer Aktionen: 3 (4 im Hort). Unmittelbar nach dem Zug einer anderen Kreatur kann die Mumie eine legendäre Aktion ausführen. Zu Beginn jedes ihrer Züge stehen der Mumie wieder alle ausgeführten legendären Aktionen zur Verfügung.*

***Nekrotischer Schlag:*** Die Mumie führt einen Fäulnisfaust- oder einen Negative-Energie-kanalisieren-Angriff aus.

***Schreckensbefehl:*** Die Mumie wirkt den Zauber *[[Befehl|Befehl]]* (Version des 2. Grades). Ihr Attribut zum Zauberwirken ist dasselbe wie beim Ausführen der Zauberwirken-Aktion. Die Mumie kann diese Aktion erst nach Beginn ihres nächsten Zugs erneut ausführen.

***Starren:*** Die Mumie setzt Fürchterliches Starren ein. Die Mumie kann diese Aktion erst nach Beginn ihres nächsten Zugs erneut ausführen.
