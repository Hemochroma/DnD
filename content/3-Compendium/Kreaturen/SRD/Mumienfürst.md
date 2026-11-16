---
ac: 17
actions:
- desc: Die Mumie führt einen Fäulnisfaust- oder einen Negative-Energie-kanalisieren-Angriff
    aus und setzt Fürchterliches Starren ein.
  name: 'Mehrfachangriff:'
- desc: '*Nahkampfangriffswurf:* +9, Reichweite 1,5 m. *Treffer:* 15 (2W10+4) Wuchtschaden
    plus 10 (3W6) nekrotischer Schaden. Wenn das Ziel eine Kreatur ist, wird es verflucht.
    Das verfluchte Ziel kann keine Trefferpunkte zurückerhalten, es erhält durch eine
    lange Rast keine Vorzüge, und sein Trefferpunktemaximum wird alle 24 Stunden um
    10 (3W6) verringert. Wenn die Trefferpunkte einer Kreatur durch diesen Angriff
    auf 0 sinken, stirbt die Kreatur und zerfällt zu Staub.'
  name: 'Fäulnisfaust:'
- desc: '*Fernkampfangriffswurf:* +9, Reichweite 18 m. *Treffer:* 25 (6W6+4) nekrotischer
    Schaden.'
  name: 'Negative Energie kanalisieren:'
- desc: '*Weisheitsrettungswurf:* SG 17; eine Kreatur im Abstand von bis zu 18 Metern
    von der Mumie, die von der Mumie gesehen werden kann. *Misserfolg:* 25 (6W6+4)
    psychischer Schaden, und das Ziel ist bis zum Beginn des nächsten Zugs der Mumie
    [[3-Compendium/Zustände/Gelähmt|gelähmt]].'
  name: 'Fürchterliches Starren:'
- desc: 'Die Mumie wirkt einen der folgenden Zauber mit Weisheit als Attribut zum
    Zauberwirken, ohne Materialkomponenten zu benötigen (Zauberrettungswurf-SG 17,
    +9 auf Treffer mit Zauberangriffen):


    - **Beliebig oft:** *[[3-Compendium/Zauber/Magie bannen|Magie bannen]]*, *[[3-Compendium/Zauber/Thaumaturgie|Thaumaturgie]]*

    - **Je 1-mal täglich:** *[[3-Compendium/Zauber/Insektenplage|Insektenplage]]*
    (Version des 7. Grades), *[[3-Compendium/Zauber/Leid|Leid]]*, *[[3-Compendium/Zauber/Tote
    beleben|Tote beleben]]*'
  name: 'Zauberwirken:'
condition_immunities: Bezaubert, Erschöpft, Gelähmt, Verängstigt, Vergiftet
cr: 15
cr_text: 15 (EP 13.000 oder 15.000 im Hort; ÜB +5)
damage_immunities: Gift, Nekrotisch
damage_vulnerabilities: Feuer
ep: 13000
gruppe: Mumien
hg: '15'
hit_dice: 25d8+75
hp: 187
hp_text: 187 (25W8+75)
immunities_text: Gift, Nekrotisch; [[3-Compendium/Zustände/Bezaubert|Bezaubert]],
  Erschöpft, [[3-Compendium/Zustände/Gelähmt|Gelähmt]], [[3-Compendium/Zustände/Verängstigt|Verängstigt]],
  [[3-Compendium/Zustände/Vergiftet|Vergiftet]]
initiative: 10
initiative_text: +10 (20)
languages: Gemeinsprache und drei weitere Sprachen
layout: Compendio SRD 2024 (Deutsch)
legendary_actions:
- desc: Die Mumie führt einen Fäulnisfaust- oder einen Negative-Energie-kanalisieren-Angriff
    aus.
  name: 'Nekrotischer Schlag:'
- desc: Die Mumie wirkt den Zauber *[[3-Compendium/Zauber/Befehl|Befehl]]* (Version
    des 2. Grades). Ihr Attribut zum Zauberwirken ist dasselbe wie beim Ausführen
    der Zauberwirken-Aktion. Die Mumie kann diese Aktion erst nach Beginn ihres nächsten
    Zugs erneut ausführen.
  name: 'Schreckensbefehl:'
- desc: Die Mumie setzt Fürchterliches Starren ein. Die Mumie kann diese Aktion erst
    nach Beginn ihres nächsten Zugs erneut ausführen.
  name: 'Starren:'
legendary_description: '*Anwendungen legendärer Aktionen: 3 (4 im Hort). Unmittelbar
  nach dem Zug einer anderen Kreatur kann die Mumie eine legendäre Aktion ausführen.
  Zu Beginn jedes ihrer Züge stehen der Mumie wieder alle ausgeführten legendären
  Aktionen zur Verfügung.*'
modifier: 10
name: Mumienfürst
reactions:
- desc: '*Auslöser:* Die Mumie wird von einem Angriffswurf getroffen. *Antwort:* Die
    Mumie fügt ihrer RK gegen diesen Angriff 2 hinzu, sodass der Angriff möglicherweise
    misslingt, und sie teleportiert sich bis zu 18 Meter weit in einen freien Bereich,
    den sie sehen kann. Jede Kreatur ihrer Wahl im Abstand von bis zu 1,5 Metern von
    ihrem Zielbereich, die von ihr gesehen werden kann, ist bis zum Ende des nächsten
    Zugs der Mumie [[3-Compendium/Zustände/Blind|blind]].'
  name: 'Wirbelwind aus Sand:'
rk: 17
saves:
- Int: 5
- Wei: 9
senses: Wahrer Blick 18 m; Passive Wahrnehmung 19
skills_text: Geschichte +5, Religion +5, Wahrnehmung +9
skillsaves:
- Geschichte: 5
- Religion: 5
- Wahrnehmung: 9
source: SRD
speed: 9 m
srd: criatura/mummy-lord
statblock: true
stats:
- 18
- 10
- 17
- 11
- 19
- 16
stats_table: '|   |   | MOD | RW |   |   | MOD | RW |   |   | MOD | RW |

  | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |

  | **Stä** | 18 | +4 | +4 | **Ges** | 10 | +0 | +0 | **Kon** | 17 | +3 | +3 |

  | **Int** | 11 | +0 | +5 | **Wei** | 19 | +4 | +9 | **Cha** | 16 | +3 | +3 |'
tags:
- srd/kreatur
tp: 187
traits:
- desc: Wenn die Mumie bei einem Rettungswurf scheitert, kann sie beschließen, ihn
    stattdessen zu bestehen.
  name: 'Legendäre Resistenz (3-mal täglich, im Hort 4-mal täglich):'
- desc: Die Mumie ist bei Rettungswürfen gegen Zauber und andere magische Effekte
    im Vorteil.
  name: 'Magieresistenz:'
- desc: Wenn die Mumie zerstört wird, ihr Herz jedoch noch intakt ist, erhält sie
    nach 24 Stunden einen neuen Körper, der mit allen Trefferpunkten aufersteht. Der
    neue Körper erscheint in einem freien Bereich im Hort der Mumie. Das Herz ist
    ein winziger Gegenstand, besitzt eine RK von 17, 10 Trefferpunkte und ist gegen
    alle Schadensarten bis auf Feuerschaden immun.
  name: 'Untote Genesung:'
typ: Kleiner oder mittelgroßer Untoter (Kleriker), rechtschaffen böse
type: Kleiner oder mittelgroßer Untoter (Kleriker), rechtschaffen böse
---

# Mumienfürst

*Kleiner oder mittelgroßer Untoter (Kleriker), rechtschaffen böse*

## Statistik

- **RK:** 17
- **TP:** 187 (25d8+75)
- **Initiative:** +10
- **Geschwindigkeit:** 9 m
- **Rettungswürfe**: Geschichte +5, Religion +5, Wahrnehmung +9
- **Immunitäten:** Gift, Nekrotisch
- **Sinne:** Wahrer Blick 18 m; Passive Wahrnehmung 19
- **Sprachen:** Gemeinsprache und drei weitere Sprachen
- **HG:** 15 (EP 13.000 oder 15.000 im Hort; ÜB +5)

|||Mod|RW|
|:--:|:--:|:-----:|:----:|
| **STÄ** | 18 | +4 | +4 |
| **GES** | 10 | +0 | +0 |
| **KON** | 17 | +3 | +3 |
| **INT** | 11 | +0 | +5 |
| **WEI** | 19 | +4 | +13 |
| **CHA** | 16 | +3 | +3 |


## Talente

### Legendäre Resistenz (3-mal täglich, im Hort 4-mal täglich):
Wenn die Mumie bei einem Rettungswurf scheitert, kann sie beschließen, ihn stattdessen zu bestehen.

### Magieresistenz:
Die Mumie ist bei Rettungswürfen gegen Zauber und andere magische Effekte im Vorteil.

### Untote Genesung:
Wenn die Mumie zerstört wird, ihr Herz jedoch noch intakt ist, erhält sie nach 24 Stunden einen neuen Körper, der mit allen Trefferpunkten aufersteht. Der neue Körper erscheint in einem freien Bereich im Hort der Mumie. Das Herz ist ein winziger Gegenstand, besitzt eine RK von 17, 10 Trefferpunkte und ist gegen alle Schadensarten bis auf Feuerschaden immun.


## Aktionen

### Mehrfachangriff:
Die Mumie führt einen Fäulnisfaust- oder einen Negative-Energie-kanalisieren-Angriff aus und setzt Fürchterliches Starren ein.

### Fäulnisfaust:
*Nahkampfangriffswurf:* +9, Reichweite 1,5 m. *Treffer:* 15 (2W10+4) Wuchtschaden plus 10 (3W6) nekrotischer Schaden. Wenn das Ziel eine Kreatur ist, wird es verflucht. Das verfluchte Ziel kann keine Trefferpunkte zurückerhalten, es erhält durch eine lange Rast keine Vorzüge, und sein Trefferpunktemaximum wird alle 24 Stunden um 10 (3W6) verringert. Wenn die Trefferpunkte einer Kreatur durch diesen Angriff auf 0 sinken, stirbt die Kreatur und zerfällt zu Staub.

### Negative Energie kanalisieren:
*Fernkampfangriffswurf:* +9, Reichweite 18 m. *Treffer:* 25 (6W6+4) nekrotischer Schaden.

### Fürchterliches Starren:
*Weisheitsrettungswurf:* SG 17; eine Kreatur im Abstand von bis zu 18 Metern von der Mumie, die von der Mumie gesehen werden kann. *Misserfolg:* 25 (6W6+4) psychischer Schaden, und das Ziel ist bis zum Beginn des nächsten Zugs der Mumie [[3-Compendium/Zustände/Gelähmt|gelähmt]].

### Zauberwirken:
Die Mumie wirkt einen der folgenden Zauber mit Weisheit als Attribut zum Zauberwirken, ohne Materialkomponenten zu benötigen (Zauberrettungswurf-SG 17, +9 auf Treffer mit Zauberangriffen):

- **Beliebig oft:** *[[3-Compendium/Zauber/Magie bannen|Magie bannen]]*, *[[3-Compendium/Zauber/Thaumaturgie|Thaumaturgie]]*
- **Je 1-mal täglich:** *[[3-Compendium/Zauber/Insektenplage|Insektenplage]]* (Version des 7. Grades), *[[3-Compendium/Zauber/Leid|Leid]]*, *[[3-Compendium/Zauber/Tote beleben|Tote beleben]]*



## Legendäre Aktionen

*Anwendungen legendärer Aktionen: 3 (4 im Hort). Unmittelbar nach dem Zug einer anderen Kreatur kann die Mumie eine legendäre Aktion ausführen. Zu Beginn jedes ihrer Züge stehen der Mumie wieder alle ausgeführten legendären Aktionen zur Verfügung.*

### Nekrotischer Schlag:
Die Mumie führt einen Fäulnisfaust- oder einen Negative-Energie-kanalisieren-Angriff aus.

### Schreckensbefehl:
Die Mumie wirkt den Zauber *[[3-Compendium/Zauber/Befehl|Befehl]]* (Version des 2. Grades). Ihr Attribut zum Zauberwirken ist dasselbe wie beim Ausführen der Zauberwirken-Aktion. Die Mumie kann diese Aktion erst nach Beginn ihres nächsten Zugs erneut ausführen.

### Starren:
Die Mumie setzt Fürchterliches Starren ein. Die Mumie kann diese Aktion erst nach Beginn ihres nächsten Zugs erneut ausführen.