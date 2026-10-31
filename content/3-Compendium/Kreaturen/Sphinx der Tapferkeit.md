---
srd: "criatura/sphinx-of-valor"
tags:
  - "srd/kreatur"
typ: "Großes celestisches Wesen, rechtschaffen neutral"
gruppe: "Sphinxe"
hg: "17"
ep: 18000
rk: 17
tp: 199
initiative: 12
statblock: true
layout: "Compendio SRD 2024 (Deutsch)"
name: "Sphinx der Tapferkeit"
type: "Großes celestisches Wesen, rechtschaffen neutral"
ac: 17
hp: 199
hit_dice: "19d10+95"
modifier: 12
speed: "12 m, Fliegen 18 m"
stats:
  - 22
  - 10
  - 20
  - 16
  - 23
  - 18
initiative_text: "+12 (22)"
hp_text: "199 (19W10+95)"
stats_table: "|   |   | MOD | RW |   |   | MOD | RW |   |   | MOD | RW |\n| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |\n| **Stä** | 22 | +6 | +6 | **Ges** | 10 | +0 | +6 | **Kon** | 20 | +5 | +11 |\n| **Int** | 16 | +3 | +9 | **Wei** | 23 | +6 | +12 | **Cha** | 18 | +4 | +4 |"
skills_text: "Arkane Kunde +9, Religion +15, Wahrnehmung +12"
immunities_text: "Psychisch; [[3-Compendium/Zustände/Bezaubert|Bezaubert]], [[3-Compendium/Zustände/Verängstigt|Verängstigt]]"
cr_text: "17 (EP 18.000 oder 20.000 im Hort; ÜB +6)"
saves:
  - Ges: 6
  - Kon: 11
  - Int: 9
  - Wei: 12
skillsaves:
  - "Arkane Kunde": 9
  - Religion: 15
  - Wahrnehmung: 12
damage_resistances: "Gleißend, Nekrotisch"
damage_immunities: "Psychisch"
condition_immunities: "Bezaubert, Verängstigt"
senses: "Wahrer Blick 36 m; Passive Wahrnehmung 22"
languages: "Celestisch, Gemeinsprache"
cr: 17
traits:
  - name: "Legendäre Resistenz (3-mal täglich, im Hort 4-mal täglich):"
    desc: "Wenn die Sphinx bei einem Rettungswurf scheitert, kann sie beschließen, ihn stattdessen zu bestehen."
  - name: "Undurchschaubar:"
    desc: "Ohne ihre Erlaubnis kann keine Magie die Sphinx aus der Ferne beobachten oder ihre Gedanken erkennen. Weisheitswürfe (Motiv erkennen) zum Ermitteln ihrer Absichten oder ihrer Aufrichtigkeit sind im Nachteil."
actions:
  - name: "Mehrfachangriff:"
    desc: "Die Sphinx führt zwei Klauenangriffe aus und setzt Brüllen ein."
  - name: "Klauen:"
    desc: "*Nahkampfangriffswurf:* +12, Reichweite 1,5 m. *Treffer:* 20 (4W6+6) Hiebschaden."
  - name: "Brüllen (3-mal täglich):"
    desc: "Die Sphinx stößt ein magisches Brüllen aus. Wann immer sie brüllt, hat das Brüllen einen anderen Effekt, wie unten beschrieben (die Sequenz wird nach einer langen Rast zurückgesetzt):\n\n- **Erstes Brüllen:** *Weisheitsrettungswurf:* SG 20; jeder Gegner in einer Ausströmung von 150 Metern, die von der Sphinx ausgeht. *Misserfolg:* Das Ziel ist eine Minute lang [[3-Compendium/Zustände/Verängstigt|verängstigt]].\n- **Zweites Brüllen:** *Weisheitsrettungswurf:* SG 20; jeder Gegner in einer Ausströmung von 150 Metern, die von der Sphinx ausgeht. *Misserfolg:* Das Ziel ist [[3-Compendium/Zustände/Gelähmt|gelähmt]] und wiederholt den Rettungswurf am Ende jedes seiner Züge. Bei einem Erfolg endet der Effekt bei ihm. Nach einer Minute besteht es den Rettungswurf automatisch.\n- **Drittes Brüllen:** *Konstitutionsrettungswurf:* SG 20; jeder Gegner in einer Ausströmung von 150 Metern, die von der Sphinx ausgeht. *Misserfolg:* 44 (8W10) Schallschaden, und das Ziel wird umgestoßen und hat den Zustand [[3-Compendium/Zustände/Liegend|Liegend]]. *Erfolg:* Nur halber Schaden."
  - name: "Zauberwirken:"
    desc: "Die Sphinx wirkt einen der folgenden Zauber mit Weisheit als Attribut zum Zauberwirken, ohne Materialkomponenten zu benötigen (Zauberrettungswurf-SG 20):\n\n- **Beliebig oft:** *[[3-Compendium/Zauber/Gutes und Böses entdecken|Gutes und Böses entdecken]]*, *[[3-Compendium/Zauber/Thaumaturgie|Thaumaturgie]]*\n- **Je 1-mal täglich:** *[[3-Compendium/Zauber/Heldenmahl|Heldenmahl]]*, *[[3-Compendium/Zauber/Magie bannen|Magie bannen]]*, *[[3-Compendium/Zauber/Magie entdecken|Magie entdecken]]*, *[[3-Compendium/Zauber/Vollständige Genesung|Vollständige Genesung]]*, *[[3-Compendium/Zauber/Zone der Wahrheit|Zone der Wahrheit]]*"
legendary_description: "*Anwendungen legendärer Aktionen: 3 (4 im Hort). Unmittelbar nach dem Zug einer anderen Kreatur kann die Sphinx eine legendäre Aktion ausführen. Zu Beginn jedes ihrer Züge stehen der Sphinx wieder alle ausgeführten legendären Aktionen zur Verfügung.*"
legendary_actions:
  - name: "Arkanes Umherstreifen:"
    desc: "Die Sphinx kann sich bis zu neun Meter weit in einen freien Bereich teleportieren, den sie sehen kann, und dort einen Klauenangriff ausführen."
  - name: "Gewicht der Jahre:"
    desc: "*Konstitutionsrettungswurf:* SG 16; eine Kreatur im Abstand von bis zu 36 Metern von der Sphinx, die von der Sphinx gesehen werden kann. *Misserfolg:* Das Ziel erhält eine Erschöpfungsstufe. Solange das Ziel Erschöpfungsstufen hat, erscheint es 3W10 Jahre älter. *Erfolg oder Misserfolg:* Die Sphinx kann diese Aktion erst nach Beginn ihres nächsten Zugs erneut ausführen."
---

> [!srd-ficha] Sphinx der Tapferkeit
> *Großes celestisches Wesen, rechtschaffen neutral*
>
> **RK** 17 · **Initiative** +12 (22)
>
> **TP** 199 (19W10+95)
>
> **Bewegungsrate** 12 m, Fliegen 18 m
>
> |   |   | MOD | RW |   |   | MOD | RW |   |   | MOD | RW |
> | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
> | **Stä** | 22 | +6 | +6 | **Ges** | 10 | +0 | +6 | **Kon** | 20 | +5 | +11 |
> | **Int** | 16 | +3 | +9 | **Wei** | 23 | +6 | +12 | **Cha** | 18 | +4 | +4 |
>
> **Fertigkeiten** Arkane Kunde +9, Religion +15, Wahrnehmung +12
>
> **Resistenzen** Gleißend, Nekrotisch
>
> **Immunitäten** Psychisch; [[Bezaubert|Bezaubert]], [[Verängstigt|Verängstigt]]
>
> **Sinne** Wahrer Blick 36 m; Passive Wahrnehmung 22
>
> **Sprachen** Celestisch, Gemeinsprache
>
> **HG** 17 (EP 18.000 oder 20.000 im Hort; ÜB +6)

## Merkmale

***Legendäre Resistenz (3-mal täglich, im Hort 4-mal täglich):*** Wenn die Sphinx bei einem Rettungswurf scheitert, kann sie beschließen, ihn stattdessen zu bestehen.

***Undurchschaubar:*** Ohne ihre Erlaubnis kann keine Magie die Sphinx aus der Ferne beobachten oder ihre Gedanken erkennen. Weisheitswürfe (Motiv erkennen) zum Ermitteln ihrer Absichten oder ihrer Aufrichtigkeit sind im Nachteil.

## Aktionen

***Mehrfachangriff:*** Die Sphinx führt zwei Klauenangriffe aus und setzt Brüllen ein.

***Klauen:*** *Nahkampfangriffswurf:* +12, Reichweite 1,5 m. *Treffer:* 20 (4W6+6) Hiebschaden.

***Brüllen (3-mal täglich):*** Die Sphinx stößt ein magisches Brüllen aus. Wann immer sie brüllt, hat das Brüllen einen anderen Effekt, wie unten beschrieben (die Sequenz wird nach einer langen Rast zurückgesetzt):

- **Erstes Brüllen:** *Weisheitsrettungswurf:* SG 20; jeder Gegner in einer Ausströmung von 150 Metern, die von der Sphinx ausgeht. *Misserfolg:* Das Ziel ist eine Minute lang verängstigt.
- **Zweites Brüllen:** *Weisheitsrettungswurf:* SG 20; jeder Gegner in einer Ausströmung von 150 Metern, die von der Sphinx ausgeht. *Misserfolg:* Das Ziel ist [[Gelähmt|gelähmt]] und wiederholt den Rettungswurf am Ende jedes seiner Züge. Bei einem Erfolg endet der Effekt bei ihm. Nach einer Minute besteht es den Rettungswurf automatisch.
- **Drittes Brüllen:** *Konstitutionsrettungswurf:* SG 20; jeder Gegner in einer Ausströmung von 150 Metern, die von der Sphinx ausgeht. *Misserfolg:* 44 (8W10) Schallschaden, und das Ziel wird umgestoßen und hat den Zustand [[Liegend|Liegend]]. *Erfolg:* Nur halber Schaden.

***Zauberwirken:*** Die Sphinx wirkt einen der folgenden Zauber mit Weisheit als Attribut zum Zauberwirken, ohne Materialkomponenten zu benötigen (Zauberrettungswurf-SG 20):

- **Beliebig oft:** *[[Gutes und Böses entdecken|Gutes und Böses entdecken]]*, *[[Thaumaturgie|Thaumaturgie]]*
- **Je 1-mal täglich:** *[[Heldenmahl|Heldenmahl]]*, *[[Magie bannen|Magie bannen]]*, *[[Magie entdecken|Magie entdecken]]*, *[[Vollständige Genesung|Vollständige Genesung]]*, *[[Zone der Wahrheit|Zone der Wahrheit]]*

## Legendäre Aktionen

*Anwendungen legendärer Aktionen: 3 (4 im Hort). Unmittelbar nach dem Zug einer anderen Kreatur kann die Sphinx eine legendäre Aktion ausführen. Zu Beginn jedes ihrer Züge stehen der Sphinx wieder alle ausgeführten legendären Aktionen zur Verfügung.*

***Arkanes Umherstreifen:*** Die Sphinx kann sich bis zu neun Meter weit in einen freien Bereich teleportieren, den sie sehen kann, und dort einen Klauenangriff ausführen.

***Gewicht der Jahre:*** *Konstitutionsrettungswurf:* SG 16; eine Kreatur im Abstand von bis zu 36 Metern von der Sphinx, die von der Sphinx gesehen werden kann. *Misserfolg:* Das Ziel erhält eine Erschöpfungsstufe. Solange das Ziel Erschöpfungsstufen hat, erscheint es 3W10 Jahre älter. *Erfolg oder Misserfolg:* Die Sphinx kann diese Aktion erst nach Beginn ihres nächsten Zugs erneut ausführen.
