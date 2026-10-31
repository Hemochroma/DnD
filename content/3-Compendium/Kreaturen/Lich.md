---
srd: "criatura/lich"
tags:
  - "srd/kreatur"
typ: "Mittelgroßer Untoter (Magier), neutral böse"
gruppe: "Lich"
hg: "21"
ep: 33000
rk: 20
tp: 315
initiative: 17
statblock: true
layout: "Compendio SRD 2024 (Deutsch)"
name: "Lich"
type: "Mittelgroßer Untoter (Magier), neutral böse"
ac: 20
hp: 315
hit_dice: "42d8+126"
modifier: 17
speed: "9 m"
stats:
  - 11
  - 16
  - 16
  - 21
  - 14
  - 16
initiative_text: "+17 (27)"
hp_text: "315 (42W8+126)"
stats_table: "|   |   | MOD | RW |   |   | MOD | RW |   |   | MOD | RW |\n| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |\n| **Stä** | 11 | +0 | +0 | **Ges** | 16 | +3 | +10 | **Kon** | 16 | +3 | +10 |\n| **Int** | 21 | +5 | +12 | **Wei** | 14 | +2 | +9 | **Cha** | 16 | +3 | +3 |"
skills_text: "Arkane Kunde +19, Geschichte +12, Motiv erkennen +9, Wahrnehmung +9"
immunities_text: "Gift, Nekrotisch; [[3-Compendium/Zustände/Bezaubert|Bezaubert]], Erschöpft, [[3-Compendium/Zustände/Gelähmt|Gelähmt]], [[3-Compendium/Zustände/Verängstigt|Verängstigt]], [[3-Compendium/Zustände/Vergiftet|Vergiftet]]"
gear: "Materialkomponentenbeutel"
cr_text: "21 (EP 33.000 oder 41.000 im Hort; ÜB +7)"
saves:
  - Ges: 10
  - Kon: 10
  - Int: 12
  - Wei: 9
skillsaves:
  - "Arkane Kunde": 19
  - Geschichte: 12
  - "Motiv erkennen": 9
  - Wahrnehmung: 9
damage_resistances: "Blitz, Kälte"
damage_immunities: "Gift, Nekrotisch"
condition_immunities: "Bezaubert, Erschöpft, Gelähmt, Verängstigt, Vergiftet"
senses: "Wahrer Blick 36 m; Passive Wahrnehmung 19"
languages: "Alle"
cr: 21
traits:
  - name: "Legendäre Resistenz (4-mal täglich, im Hort 5-mal täglich):"
    desc: "Wenn der Lich bei einem Rettungswurf scheitert, kann er beschließen, ihn stattdessen zu bestehen."
  - name: "Seelengefäß:"
    desc: "Wenn der Lich zerstört wird, ersteht er nach 1W10 Tagen mit allen Trefferpunkten wieder auf, sofern er ein Seelengefäß hat. Der neue Körper erscheint in einem freien Bereich im Hort des Lichs."
actions:
  - name: "Mehrfachangriff:"
    desc: "Der Lich führt drei Angriffe mit Lähmende Berührung oder Mystische Explosion in beliebiger Kombination aus."
  - name: "Lähmende Berührung:"
    desc: "*Nahkampfangriffswurf:* +12, Reichweite 1,5 m. *Treffer:* 15 (3W6+5) Kälteschaden, und das Ziel ist bis zum Beginn des nächsten Zugs des Lichs [[3-Compendium/Zustände/Gelähmt|gelähmt]]."
  - name: "Mystische Explosion:"
    desc: "*Nah- oder Fernkampfangriffswurf:* +12, Reichweite 1,5 m oder Reichweite 36 m. *Treffer:* 31 (4W12+5) Energieschaden."
  - name: "Zauberwirken:"
    desc: "Der Lich wirkt einen der folgenden Zauber mit Intelligenz als Attribut zum Zauberwirken (Zauberrettungswurf-SG 20):\n\n- **Beliebig oft:** *[[3-Compendium/Zauber/Blitz|Blitz]]* (Version des 5. Grades), *[[3-Compendium/Zauber/Feuerball|Feuerball]]* (Version des 5. Grades), *[[3-Compendium/Zauber/Gedanken wahrnehmen|Gedanken wahrnehmen]]*, *[[3-Compendium/Zauber/Magie bannen|Magie bannen]]*, *[[3-Compendium/Zauber/Magie entdecken|Magie entdecken]]*, *[[3-Compendium/Zauber/Magierhand|Magierhand]]*, *[[3-Compendium/Zauber/Taschenspielerei|Taschenspielerei]]*, *[[3-Compendium/Zauber/Unsichtbarkeit|Unsichtbarkeit]]*\n- **Je 2-mal täglich:** *[[3-Compendium/Zauber/Dimensionstür|Dimensionstür]]*, *[[3-Compendium/Zauber/Ebenenwechsel|Ebenenwechsel]]*, *[[3-Compendium/Zauber/Tote beleben|Tote beleben]]*\n- **Je 1-mal täglich:** *[[3-Compendium/Zauber/Ausspähung|Ausspähung]]*, *[[3-Compendium/Zauber/Finger des Todes|Finger des Todes]]*, *[[3-Compendium/Zauber/Kettenblitz|Kettenblitz]]*, *[[3-Compendium/Zauber/Wort der Macht Tod|Wort der Macht: Tod]]*"
reactions:
  - name: "Schutzmagie:"
    desc: "Der Lich wirkt den Zauber *[[3-Compendium/Zauber/Gegenzauber|Gegenzauber]]* oder *[[3-Compendium/Zauber/Schild|Schild]]* als Antwort auf den Auslöser des Zaubers. Sein Attribut zum Zauberwirken ist dasselbe wie beim Ausführen der Zauberwirken-Aktion."
legendary_description: "*Anwendungen legendärer Aktionen: 3 (4 im Hort). Unmittelbar nach dem Zug einer anderen Kreatur kann der Lich eine legendäre Aktion ausführen. Zu Beginn jedes seiner Züge stehen dem Lich wieder alle ausgeführten legendären Aktionen zur Verfügung.*"
legendary_actions:
  - name: "Furchteinflößender Blick:"
    desc: "Der Lich wirkt den Zauber *[[3-Compendium/Zauber/Furcht|Furcht]]*. Sein Attribut zum Zauberwirken ist dasselbe wie beim Ausführen der Zauberwirken-Aktion. Der Lich kann diese Aktion erst nach Beginn seines nächsten Zugs erneut ausführen."
  - name: "Lebensunterbrechung:"
    desc: "*Konstitutionsrettungswurf:* SG 20; jede Kreatur, die kein Untoter ist und die sich in einer Ausströmung von sechs Metern befindet, die vom Lich ausgeht. *Misserfolg:* 31 (9W6) nekrotischer Schaden. *Erfolg:* Halber Schaden. *Erfolg oder Misserfolg:* Der Lich kann diese Aktion erst nach Beginn seines nächsten Zugs erneut ausführen."
  - name: "Tödliches Teleportieren:"
    desc: "Der Lich teleportiert sich bis zu 18 Meter weit in einen freien Bereich, den er sehen kann, und jede Kreatur im Abstand von bis zu drei Metern vom Bereich, den er verlassen hat, erleidet 11 (2W10) nekrotischen Schaden."
---

> [!srd-ficha] Lich
> *Mittelgroßer Untoter (Magier), neutral böse*
>
> **RK** 20 · **Initiative** +17 (27)
>
> **TP** 315 (42W8+126)
>
> **Bewegungsrate** 9 m
>
> |   |   | MOD | RW |   |   | MOD | RW |   |   | MOD | RW |
> | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
> | **Stä** | 11 | +0 | +0 | **Ges** | 16 | +3 | +10 | **Kon** | 16 | +3 | +10 |
> | **Int** | 21 | +5 | +12 | **Wei** | 14 | +2 | +9 | **Cha** | 16 | +3 | +3 |
>
> **Fertigkeiten** Arkane Kunde +19, Geschichte +12, Motiv erkennen +9, Wahrnehmung +9
>
> **Resistenzen** Blitz, Kälte
>
> **Immunitäten** Gift, Nekrotisch; [[Bezaubert|Bezaubert]], Erschöpft, [[Gelähmt|Gelähmt]], [[Verängstigt|Verängstigt]], [[Vergiftet|Vergiftet]]
>
> **Ausrüstung** Materialkomponentenbeutel
>
> **Sinne** Wahrer Blick 36 m; Passive Wahrnehmung 19
>
> **Sprachen** Alle
>
> **HG** 21 (EP 33.000 oder 41.000 im Hort; ÜB +7)

## Merkmale

***Legendäre Resistenz (4-mal täglich, im Hort 5-mal täglich):*** Wenn der Lich bei einem Rettungswurf scheitert, kann er beschließen, ihn stattdessen zu bestehen.

***Seelengefäß:*** Wenn der Lich zerstört wird, ersteht er nach 1W10 Tagen mit allen Trefferpunkten wieder auf, sofern er ein Seelengefäß hat. Der neue Körper erscheint in einem freien Bereich im Hort des Lichs.

## Aktionen

***Mehrfachangriff:*** Der Lich führt drei Angriffe mit Lähmende Berührung oder Mystische Explosion in beliebiger Kombination aus.

***Lähmende Berührung:*** *Nahkampfangriffswurf:* +12, Reichweite 1,5 m. *Treffer:* 15 (3W6+5) Kälteschaden, und das Ziel ist bis zum Beginn des nächsten Zugs des Lichs gelähmt.

***Mystische Explosion:*** *Nah- oder Fernkampfangriffswurf:* +12, Reichweite 1,5 m oder Reichweite 36 m. *Treffer:* 31 (4W12+5) Energieschaden.

***Zauberwirken:*** Der Lich wirkt einen der folgenden Zauber mit Intelligenz als Attribut zum Zauberwirken (Zauberrettungswurf-SG 20):

- **Beliebig oft:** *[[Blitz|Blitz]]* (Version des 5. Grades), *[[Feuerball|Feuerball]]* (Version des 5. Grades), *[[Gedanken wahrnehmen|Gedanken wahrnehmen]]*, *[[Magie bannen|Magie bannen]]*, *[[Magie entdecken|Magie entdecken]]*, *[[Magierhand|Magierhand]]*, *[[Taschenspielerei|Taschenspielerei]]*, *[[Unsichtbarkeit|Unsichtbarkeit]]*
- **Je 2-mal täglich:** *[[Dimensionstür|Dimensionstür]]*, *[[Ebenenwechsel|Ebenenwechsel]]*, *[[Tote beleben|Tote beleben]]*
- **Je 1-mal täglich:** *[[Ausspähung|Ausspähung]]*, *[[Finger des Todes|Finger des Todes]]*, *[[Kettenblitz|Kettenblitz]]*, *[[Wort der Macht Tod|Wort der Macht: Tod]]*

## Reaktionen

***Schutzmagie:*** Der Lich wirkt den Zauber *[[Gegenzauber|Gegenzauber]]* oder *[[3-Compendium/Zauber/Schild|Schild]]* als Antwort auf den Auslöser des Zaubers. Sein Attribut zum Zauberwirken ist dasselbe wie beim Ausführen der Zauberwirken-Aktion.

## Legendäre Aktionen

*Anwendungen legendärer Aktionen: 3 (4 im Hort). Unmittelbar nach dem Zug einer anderen Kreatur kann der Lich eine legendäre Aktion ausführen. Zu Beginn jedes seiner Züge stehen dem Lich wieder alle ausgeführten legendären Aktionen zur Verfügung.*

***Furchteinflößender Blick:*** Der Lich wirkt den Zauber *[[Furcht|Furcht]]*. Sein Attribut zum Zauberwirken ist dasselbe wie beim Ausführen der Zauberwirken-Aktion. Der Lich kann diese Aktion erst nach Beginn seines nächsten Zugs erneut ausführen.

***Lebensunterbrechung:*** *Konstitutionsrettungswurf:* SG 20; jede Kreatur, die kein Untoter ist und die sich in einer Ausströmung von sechs Metern befindet, die vom Lich ausgeht. *Misserfolg:* 31 (9W6) nekrotischer Schaden. *Erfolg:* Halber Schaden. *Erfolg oder Misserfolg:* Der Lich kann diese Aktion erst nach Beginn seines nächsten Zugs erneut ausführen.

***Tödliches Teleportieren:*** Der Lich teleportiert sich bis zu 18 Meter weit in einen freien Bereich, den er sehen kann, und jede Kreatur im Abstand von bis zu drei Metern vom Bereich, den er verlassen hat, erleidet 11 (2W10) nekrotischen Schaden.
