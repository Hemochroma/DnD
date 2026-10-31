---
srd: "criatura/ancient-gold-dragon"
tags:
  - "srd/kreatur"
typ: "Gigantischer Drache (metallisch), rechtschaffen gut"
gruppe: "Golddrachen"
hg: "24"
ep: 62000
rk: 22
tp: 546
initiative: 16
statblock: true
layout: "Compendio SRD 2024 (Deutsch)"
name: "Uralter Golddrache"
type: "Gigantischer Drache (metallisch), rechtschaffen gut"
ac: 22
hp: 546
hit_dice: "28d20+252"
modifier: 16
speed: "12 m, Fliegen 24 m, Schwimmen 12 m"
stats:
  - 30
  - 14
  - 29
  - 18
  - 17
  - 28
initiative_text: "+16 (26)"
hp_text: "546 (28W20+252)"
stats_table: "|   |   | MOD | RW |   |   | MOD | RW |   |   | MOD | RW |\n| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |\n| **Stä** | 30 | +10 | +10 | **Ges** | 14 | +2 | +9 | **Kon** | 29 | +9 | +9 |\n| **Int** | 18 | +4 | +4 | **Wei** | 17 | +3 | +10 | **Cha** | 28 | +9 | +9 |"
skills_text: "Heimlichkeit +9, Motiv erkennen +10, Überzeugen +16, Wahrnehmung +17"
immunities_text: "Feuer"
cr_text: "24 (EP 62.000 oder 75.000 im Hort; ÜB +7)"
saves:
  - Ges: 9
  - Wei: 10
skillsaves:
  - Heimlichkeit: 9
  - "Motiv erkennen": 10
  - Überzeugen: 16
  - Wahrnehmung: 17
damage_immunities: "Feuer"
senses: "Blindsicht 18 m, Dunkelsicht 36 m; Passive Wahrnehmung 27"
languages: "Drakonisch, Gemeinsprache"
cr: 24
traits:
  - name: "Amphibisch:"
    desc: "Der Drache kann Luft und Wasser atmen."
  - name: "Legendäre Resistenz (4-mal täglich, im Hort 5-mal täglich):"
    desc: "Wenn der Drache bei einem Rettungswurf scheitert, kann er beschließen, ihn stattdessen zu bestehen."
actions:
  - name: "Mehrfachangriff:"
    desc: "Der Drache führt drei Zerfetzen-Angriffe aus. Er kann einen Angriff durch einen Einsatz von (A) Zauberwirken ersetzen, um den Zauber *[[3-Compendium/Zauber/Lenkendes Geschoss|Lenkendes Geschoss]]* (Version des 4. Grades) zu wirken, oder (B) Schwächender Odem ersetzen."
  - name: "Zerfetzen:"
    desc: "*Nahkampfangriffswurf:* +17 auf Treffer, Reichweite 4,5 m. *Treffer:* 19 (2W8+10) Hiebschaden plus 9 (2W8) Feuerschaden."
  - name: "Feuerodem (Aufladung 5–6):"
    desc: "*Geschicklichkeitsrettungswurf:* SG 24; jede Kreatur in einem Kegel von 27 Metern. *Misserfolg:* 71 (13W10) Feuerschaden. *Erfolg:* Halber Schaden."
  - name: "Schwächender Odem:"
    desc: "*Stärkerettungswurf:* SG 24; jede Kreatur in einem Kegel von 27 Metern, die derzeit nicht von diesem Odem betroffen ist. *Misserfolg:* Das Ziel ist bei W20-Prüfungen, die auf Stärke basieren, im Nachteil, und es zieht 5 (1W10) von seinen Schadenswürfen ab. Es wiederholt den Rettungswurf am Ende jedes seiner Züge. Bei einem Erfolg endet der Effekt bei ihm. Nach einer Minute besteht es den Rettungswurf automatisch."
  - name: "Zauberwirken:"
    desc: "Der Drache wirkt einen der folgenden Zauber mit Charisma als Attribut zum Zauberwirken, ohne Materialkomponenten zu benötigen (Zauberrettungswurf-SG 24, +16 auf Treffer mit Zauberangriffen):\n\n- **Beliebig oft:** *[[3-Compendium/Zauber/Gestaltwandel|Gestaltwandel]]* (nur in Tier- oder humanoider Gestalt; durch den Zauber werden keine temporären Trefferpunkte erhalten, und zum Aufrechterhalten des Zaubers sind weder Konzentration noch temporäre Trefferpunkte erforderlich), *[[3-Compendium/Zauber/Lenkendes Geschoss|Lenkendes Geschoss]]* (Version des 4. Grades), *[[3-Compendium/Zauber/Magie entdecken|Magie entdecken]]*\n- **Je 1-mal täglich:** *[[3-Compendium/Zauber/Flammenschlag|Flammenschlag]]* (Version des 6. Grades), *[[3-Compendium/Zauber/Wort des Rückrufs|Wort des Rückrufs]]*, *[[3-Compendium/Zauber/Zone der Wahrheit|Zone der Wahrheit]]*"
legendary_description: "*Anwendungen legendärer Aktionen: 3 (4 im Hort). Unmittelbar nach dem Zug einer anderen Kreatur kann der Drache eine legendäre Aktion ausführen. Zu Beginn jedes seiner Züge stehen dem Drachen wieder alle ausgeführten legendären Aktionen zur Verfügung.*"
legendary_actions:
  - name: "Anspringen:"
    desc: "Der Drache legt bis zur Hälfte seiner Bewegungsrate zurück und führt einen Zerfetzen-Angriff aus."
  - name: "Lenkendes Licht:"
    desc: "Der Drache setzt Zauberwirken ein, um den Zauber *[[3-Compendium/Zauber/Lenkendes Geschoss|Lenkendes Geschoss]]* (Version des 4. Grades) zu wirken."
  - name: "Verbannen:"
    desc: "*Charismarettungswurf:* SG 24; eine Kreatur im Abstand von bis zu 36 Metern, die der Drache sehen kann. *Misserfolg:* 24 (7W6) Energieschaden, und das Ziel ist [[3-Compendium/Zustände/Kampfunfähig|kampfunfähig]] und gelangt auf eine harmlose Halbebene, wo es bis zum Beginn des nächsten Zugs des Drachen verbleibt. Dann erscheint es in einem freien Bereich nach Wahl des Drachen im Abstand von bis zu 36 Metern vom Drachen. *Erfolg oder Misserfolg:* Der Drache kann diese Aktion erst nach Beginn seines nächsten Zugs erneut ausführen."
---

> [!srd-ficha] Uralter Golddrache
> *Gigantischer Drache (metallisch), rechtschaffen gut*
>
> **RK** 22 · **Initiative** +16 (26)
>
> **TP** 546 (28W20+252)
>
> **Bewegungsrate** 12 m, Fliegen 24 m, Schwimmen 12 m
>
> |   |   | MOD | RW |   |   | MOD | RW |   |   | MOD | RW |
> | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
> | **Stä** | 30 | +10 | +10 | **Ges** | 14 | +2 | +9 | **Kon** | 29 | +9 | +9 |
> | **Int** | 18 | +4 | +4 | **Wei** | 17 | +3 | +10 | **Cha** | 28 | +9 | +9 |
>
> **Fertigkeiten** Heimlichkeit +9, Motiv erkennen +10, Überzeugen +16, Wahrnehmung +17
>
> **Immunitäten** Feuer
>
> **Sinne** Blindsicht 18 m, Dunkelsicht 36 m; Passive Wahrnehmung 27
>
> **Sprachen** Drakonisch, Gemeinsprache
>
> **HG** 24 (EP 62.000 oder 75.000 im Hort; ÜB +7)

## Merkmale

***Amphibisch:*** Der Drache kann Luft und Wasser atmen.

***Legendäre Resistenz (4-mal täglich, im Hort 5-mal täglich):*** Wenn der Drache bei einem Rettungswurf scheitert, kann er beschließen, ihn stattdessen zu bestehen.

## Aktionen

***Mehrfachangriff:*** Der Drache führt drei Zerfetzen-Angriffe aus. Er kann einen Angriff durch einen Einsatz von (A) Zauberwirken ersetzen, um den Zauber *[[Lenkendes Geschoss|Lenkendes Geschoss]]* (Version des 4. Grades) zu wirken, oder (B) Schwächender Odem ersetzen.

***Zerfetzen:*** *Nahkampfangriffswurf:* +17 auf Treffer, Reichweite 4,5 m. *Treffer:* 19 (2W8+10) Hiebschaden plus 9 (2W8) Feuerschaden.

***Feuerodem (Aufladung 5–6):*** *Geschicklichkeitsrettungswurf:* SG 24; jede Kreatur in einem Kegel von 27 Metern. *Misserfolg:* 71 (13W10) Feuerschaden. *Erfolg:* Halber Schaden.

***Schwächender Odem:*** *Stärkerettungswurf:* SG 24; jede Kreatur in einem Kegel von 27 Metern, die derzeit nicht von diesem Odem betroffen ist. *Misserfolg:* Das Ziel ist bei W20-Prüfungen, die auf Stärke basieren, im Nachteil, und es zieht 5 (1W10) von seinen Schadenswürfen ab. Es wiederholt den Rettungswurf am Ende jedes seiner Züge. Bei einem Erfolg endet der Effekt bei ihm. Nach einer Minute besteht es den Rettungswurf automatisch.

***Zauberwirken:*** Der Drache wirkt einen der folgenden Zauber mit Charisma als Attribut zum Zauberwirken, ohne Materialkomponenten zu benötigen (Zauberrettungswurf-SG 24, +16 auf Treffer mit Zauberangriffen):

- **Beliebig oft:** *[[Gestaltwandel|Gestaltwandel]]* (nur in Tier- oder humanoider Gestalt; durch den Zauber werden keine temporären Trefferpunkte erhalten, und zum Aufrechterhalten des Zaubers sind weder Konzentration noch temporäre Trefferpunkte erforderlich), *[[Lenkendes Geschoss|Lenkendes Geschoss]]* (Version des 4. Grades), *[[Magie entdecken|Magie entdecken]]*
- **Je 1-mal täglich:** *[[Flammenschlag|Flammenschlag]]* (Version des 6. Grades), *[[Wort des Rückrufs|Wort des Rückrufs]]*, *[[Zone der Wahrheit|Zone der Wahrheit]]*

## Legendäre Aktionen

*Anwendungen legendärer Aktionen: 3 (4 im Hort). Unmittelbar nach dem Zug einer anderen Kreatur kann der Drache eine legendäre Aktion ausführen. Zu Beginn jedes seiner Züge stehen dem Drachen wieder alle ausgeführten legendären Aktionen zur Verfügung.*

***Anspringen:*** Der Drache legt bis zur Hälfte seiner Bewegungsrate zurück und führt einen Zerfetzen-Angriff aus.

***Lenkendes Licht:*** Der Drache setzt Zauberwirken ein, um den Zauber *[[Lenkendes Geschoss|Lenkendes Geschoss]]* (Version des 4. Grades) zu wirken.

***Verbannen:*** *Charismarettungswurf:* SG 24; eine Kreatur im Abstand von bis zu 36 Metern, die der Drache sehen kann. *Misserfolg:* 24 (7W6) Energieschaden, und das Ziel ist [[Kampfunfähig|kampfunfähig]] und gelangt auf eine harmlose Halbebene, wo es bis zum Beginn des nächsten Zugs des Drachen verbleibt. Dann erscheint es in einem freien Bereich nach Wahl des Drachen im Abstand von bis zu 36 Metern vom Drachen. *Erfolg oder Misserfolg:* Der Drache kann diese Aktion erst nach Beginn seines nächsten Zugs erneut ausführen.
