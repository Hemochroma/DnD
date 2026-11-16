---
ac: 20
actions:
- desc: Der Lich führt drei Angriffe mit Lähmende Berührung oder Mystische Explosion
    in beliebiger Kombination aus.
  name: 'Mehrfachangriff:'
- desc: '*Nahkampfangriffswurf:* +12, Reichweite 1,5 m. *Treffer:* 15 (3W6+5) Kälteschaden,
    und das Ziel ist bis zum Beginn des nächsten Zugs des Lichs [[3-Compendium/Zustände/Gelähmt|gelähmt]].'
  name: 'Lähmende Berührung:'
- desc: '*Nah- oder Fernkampfangriffswurf:* +12, Reichweite 1,5 m oder Reichweite
    36 m. *Treffer:* 31 (4W12+5) Energieschaden.'
  name: 'Mystische Explosion:'
- desc: 'Der Lich wirkt einen der folgenden Zauber mit Intelligenz als Attribut zum
    Zauberwirken (Zauberrettungswurf-SG 20):


    - **Beliebig oft:** *[[3-Compendium/Zauber/Blitz|Blitz]]* (Version des 5. Grades),
    *[[3-Compendium/Zauber/Feuerball|Feuerball]]* (Version des 5. Grades), *[[3-Compendium/Zauber/Gedanken
    wahrnehmen|Gedanken wahrnehmen]]*, *[[3-Compendium/Zauber/Magie bannen|Magie bannen]]*,
    *[[3-Compendium/Zauber/Magie entdecken|Magie entdecken]]*, *[[3-Compendium/Zauber/Magierhand|Magierhand]]*,
    *[[3-Compendium/Zauber/Taschenspielerei|Taschenspielerei]]*, *[[3-Compendium/Zauber/Unsichtbarkeit|Unsichtbarkeit]]*

    - **Je 2-mal täglich:** *[[3-Compendium/Zauber/Dimensionstür|Dimensionstür]]*,
    *[[3-Compendium/Zauber/Ebenenwechsel|Ebenenwechsel]]*, *[[3-Compendium/Zauber/Tote
    beleben|Tote beleben]]*

    - **Je 1-mal täglich:** *[[3-Compendium/Zauber/Ausspähung|Ausspähung]]*, *[[3-Compendium/Zauber/Finger
    des Todes|Finger des Todes]]*, *[[3-Compendium/Zauber/Kettenblitz|Kettenblitz]]*,
    *[[3-Compendium/Zauber/Wort der Macht Tod|Wort der Macht: Tod]]*'
  name: 'Zauberwirken:'
condition_immunities: Bezaubert, Erschöpft, Gelähmt, Verängstigt, Vergiftet
cr: 21
cr_text: 21 (EP 33.000 oder 41.000 im Hort; ÜB +7)
damage_immunities: Gift, Nekrotisch
damage_resistances: Blitz, Kälte
ep: 33000
gear: Materialkomponentenbeutel
gruppe: Lich
hg: '21'
hit_dice: 42d8+126
hp: 315
hp_text: 315 (42W8+126)
immunities_text: Gift, Nekrotisch; [[3-Compendium/Zustände/Bezaubert|Bezaubert]],
  Erschöpft, [[3-Compendium/Zustände/Gelähmt|Gelähmt]], [[3-Compendium/Zustände/Verängstigt|Verängstigt]],
  [[3-Compendium/Zustände/Vergiftet|Vergiftet]]
initiative: 17
initiative_text: +17 (27)
languages: Alle
layout: Compendio SRD 2024 (Deutsch)
legendary_actions:
- desc: Der Lich wirkt den Zauber *[[3-Compendium/Zauber/Furcht|Furcht]]*. Sein Attribut
    zum Zauberwirken ist dasselbe wie beim Ausführen der Zauberwirken-Aktion. Der
    Lich kann diese Aktion erst nach Beginn seines nächsten Zugs erneut ausführen.
  name: 'Furchteinflößender Blick:'
- desc: '*Konstitutionsrettungswurf:* SG 20; jede Kreatur, die kein Untoter ist und
    die sich in einer Ausströmung von sechs Metern befindet, die vom Lich ausgeht.
    *Misserfolg:* 31 (9W6) nekrotischer Schaden. *Erfolg:* Halber Schaden. *Erfolg
    oder Misserfolg:* Der Lich kann diese Aktion erst nach Beginn seines nächsten
    Zugs erneut ausführen.'
  name: 'Lebensunterbrechung:'
- desc: Der Lich teleportiert sich bis zu 18 Meter weit in einen freien Bereich, den
    er sehen kann, und jede Kreatur im Abstand von bis zu drei Metern vom Bereich,
    den er verlassen hat, erleidet 11 (2W10) nekrotischen Schaden.
  name: 'Tödliches Teleportieren:'
legendary_description: '*Anwendungen legendärer Aktionen: 3 (4 im Hort). Unmittelbar
  nach dem Zug einer anderen Kreatur kann der Lich eine legendäre Aktion ausführen.
  Zu Beginn jedes seiner Züge stehen dem Lich wieder alle ausgeführten legendären
  Aktionen zur Verfügung.*'
modifier: 17
name: Lich
reactions:
- desc: Der Lich wirkt den Zauber *[[3-Compendium/Zauber/Gegenzauber|Gegenzauber]]*
    oder *[[3-Compendium/Zauber/Schild|Schild]]* als Antwort auf den Auslöser des
    Zaubers. Sein Attribut zum Zauberwirken ist dasselbe wie beim Ausführen der Zauberwirken-Aktion.
  name: 'Schutzmagie:'
rk: 20
saves:
- Ges: 10
- Kon: 10
- Int: 12
- Wei: 9
senses: Wahrer Blick 36 m; Passive Wahrnehmung 19
skills_text: Arkane Kunde +19, Geschichte +12, Motiv erkennen +9, Wahrnehmung +9
skillsaves:
- Arkane Kunde: 19
- Geschichte: 12
- Motiv erkennen: 9
- Wahrnehmung: 9
source: SRD
speed: 9 m
srd: criatura/lich
statblock: true
stats:
- 11
- 16
- 16
- 21
- 14
- 16
stats_table: '|   |   | MOD | RW |   |   | MOD | RW |   |   | MOD | RW |

  | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |

  | **Stä** | 11 | +0 | +0 | **Ges** | 16 | +3 | +10 | **Kon** | 16 | +3 | +10 |

  | **Int** | 21 | +5 | +12 | **Wei** | 14 | +2 | +9 | **Cha** | 16 | +3 | +3 |'
tags:
- srd/kreatur
tp: 315
traits:
- desc: Wenn der Lich bei einem Rettungswurf scheitert, kann er beschließen, ihn stattdessen
    zu bestehen.
  name: 'Legendäre Resistenz (4-mal täglich, im Hort 5-mal täglich):'
- desc: Wenn der Lich zerstört wird, ersteht er nach 1W10 Tagen mit allen Trefferpunkten
    wieder auf, sofern er ein Seelengefäß hat. Der neue Körper erscheint in einem
    freien Bereich im Hort des Lichs.
  name: 'Seelengefäß:'
typ: Mittelgroßer Untoter (Magier), neutral böse
type: Mittelgroßer Untoter (Magier), neutral böse
---

# Lich

*Mittelgroßer Untoter (Magier), neutral böse*

## Statistik

- **RK:** 20
- **TP:** 315 (42d8+126)
- **Initiative:** +17
- **Geschwindigkeit:** 9 m
- **Rettungswürfe**: Arkane Kunde +19, Geschichte +12, Motiv erkennen +9, Wahrnehmung +9
- **Immunitäten:** Gift, Nekrotisch
- **Sinne:** Wahrer Blick 36 m; Passive Wahrnehmung 19
- **Sprachen:** Alle
- **HG:** 21 (EP 33.000 oder 41.000 im Hort; ÜB +7)

|||Mod|RW|
|:--:|:--:|:-----:|:----:|
| **STÄ** | 11 | +0 | +0 |
| **GES** | 16 | +3 | +13 |
| **KON** | 16 | +3 | +13 |
| **INT** | 21 | +5 | +17 |
| **WEI** | 14 | +2 | +11 |
| **CHA** | 16 | +3 | +3 |


## Talente

### Legendäre Resistenz (4-mal täglich, im Hort 5-mal täglich):
Wenn der Lich bei einem Rettungswurf scheitert, kann er beschließen, ihn stattdessen zu bestehen.

### Seelengefäß:
Wenn der Lich zerstört wird, ersteht er nach 1W10 Tagen mit allen Trefferpunkten wieder auf, sofern er ein Seelengefäß hat. Der neue Körper erscheint in einem freien Bereich im Hort des Lichs.


## Aktionen

### Mehrfachangriff:
Der Lich führt drei Angriffe mit Lähmende Berührung oder Mystische Explosion in beliebiger Kombination aus.

### Lähmende Berührung:
*Nahkampfangriffswurf:* +12, Reichweite 1,5 m. *Treffer:* 15 (3W6+5) Kälteschaden, und das Ziel ist bis zum Beginn des nächsten Zugs des Lichs [[3-Compendium/Zustände/Gelähmt|gelähmt]].

### Mystische Explosion:
*Nah- oder Fernkampfangriffswurf:* +12, Reichweite 1,5 m oder Reichweite 36 m. *Treffer:* 31 (4W12+5) Energieschaden.

### Zauberwirken:
Der Lich wirkt einen der folgenden Zauber mit Intelligenz als Attribut zum Zauberwirken (Zauberrettungswurf-SG 20):

- **Beliebig oft:** *[[3-Compendium/Zauber/Blitz|Blitz]]* (Version des 5. Grades), *[[3-Compendium/Zauber/Feuerball|Feuerball]]* (Version des 5. Grades), *[[3-Compendium/Zauber/Gedanken wahrnehmen|Gedanken wahrnehmen]]*, *[[3-Compendium/Zauber/Magie bannen|Magie bannen]]*, *[[3-Compendium/Zauber/Magie entdecken|Magie entdecken]]*, *[[3-Compendium/Zauber/Magierhand|Magierhand]]*, *[[3-Compendium/Zauber/Taschenspielerei|Taschenspielerei]]*, *[[3-Compendium/Zauber/Unsichtbarkeit|Unsichtbarkeit]]*
- **Je 2-mal täglich:** *[[3-Compendium/Zauber/Dimensionstür|Dimensionstür]]*, *[[3-Compendium/Zauber/Ebenenwechsel|Ebenenwechsel]]*, *[[3-Compendium/Zauber/Tote beleben|Tote beleben]]*
- **Je 1-mal täglich:** *[[3-Compendium/Zauber/Ausspähung|Ausspähung]]*, *[[3-Compendium/Zauber/Finger des Todes|Finger des Todes]]*, *[[3-Compendium/Zauber/Kettenblitz|Kettenblitz]]*, *[[3-Compendium/Zauber/Wort der Macht Tod|Wort der Macht: Tod]]*



## Legendäre Aktionen

*Anwendungen legendärer Aktionen: 3 (4 im Hort). Unmittelbar nach dem Zug einer anderen Kreatur kann der Lich eine legendäre Aktion ausführen. Zu Beginn jedes seiner Züge stehen dem Lich wieder alle ausgeführten legendären Aktionen zur Verfügung.*

### Furchteinflößender Blick:
Der Lich wirkt den Zauber *[[3-Compendium/Zauber/Furcht|Furcht]]*. Sein Attribut zum Zauberwirken ist dasselbe wie beim Ausführen der Zauberwirken-Aktion. Der Lich kann diese Aktion erst nach Beginn seines nächsten Zugs erneut ausführen.

### Lebensunterbrechung:
*Konstitutionsrettungswurf:* SG 20; jede Kreatur, die kein Untoter ist und die sich in einer Ausströmung von sechs Metern befindet, die vom Lich ausgeht. *Misserfolg:* 31 (9W6) nekrotischer Schaden. *Erfolg:* Halber Schaden. *Erfolg oder Misserfolg:* Der Lich kann diese Aktion erst nach Beginn seines nächsten Zugs erneut ausführen.

### Tödliches Teleportieren:
Der Lich teleportiert sich bis zu 18 Meter weit in einen freien Bereich, den er sehen kann, und jede Kreatur im Abstand von bis zu drei Metern vom Bereich, den er verlassen hat, erleidet 11 (2W10) nekrotischen Schaden.