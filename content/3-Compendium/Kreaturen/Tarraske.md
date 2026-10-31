---
srd: "criatura/tarrasque"
tags:
  - "srd/kreatur"
typ: "Gigantische Monstrosität (Titan), gesinnungslos"
gruppe: "Tarraske"
hg: "30"
ep: 155000
rk: 25
tp: 697
initiative: 18
statblock: true
layout: "Compendio SRD 2024 (Deutsch)"
name: "Tarraske"
type: "Gigantische Monstrosität (Titan), gesinnungslos"
ac: 25
hp: 697
hit_dice: "34d20+340"
modifier: 18
speed: "18 m, Graben 12 m, Klettern 18 m"
stats:
  - 30
  - 11
  - 30
  - 3
  - 11
  - 11
initiative_text: "+18 (28)"
hp_text: "697 (34W20+340)"
stats_table: "|   |   | MOD | RW |   |   | MOD | RW |   |   | MOD | RW |\n| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |\n| **Stä** | 30 | +10 | +10 | **Ges** | 11 | +0 | +9 | **Kon** | 30 | +10 | +10 |\n| **Int** | 3 | −4 | +5 | **Wei** | 11 | +0 | +9 | **Cha** | 11 | +0 | +9 |"
skills_text: "Wahrnehmung +9"
immunities_text: "Feuer, Gift; [[3-Compendium/Zustände/Bezaubert|Bezaubert]], [[3-Compendium/Zustände/Gelähmt|Gelähmt]], [[3-Compendium/Zustände/Taub|Taub]], [[3-Compendium/Zustände/Verängstigt|Verängstigt]], [[3-Compendium/Zustände/Vergiftet|Vergiftet]]"
cr_text: "30 (EP 155.000; ÜB +9)"
saves:
  - Ges: 9
  - Int: 5
  - Wei: 9
  - Cha: 9
skillsaves:
  - Wahrnehmung: 9
damage_resistances: "Hieb, Stich, Wucht"
damage_immunities: "Feuer, Gift"
condition_immunities: "Bezaubert, Gelähmt, Taub, Verängstigt, Vergiftet"
senses: "Blindsicht 36 m; Passive Wahrnehmung 19"
languages: "−"
cr: 30
traits:
  - name: "Belagerungsmonster:"
    desc: "Die Tarraske fügt Gegenständen und Gebäuden doppelten Schaden zu."
  - name: "Legendäre Resistenz (6-mal täglich):"
    desc: "Wenn die Tarraske bei einem Rettungswurf scheitert, kann sie beschließen, ihn stattdessen zu bestehen."
  - name: "Magieresistenz:"
    desc: "Die Tarraske ist bei Rettungswürfen gegen Zauber und andere magische Effekte im Vorteil."
  - name: "Reflektierender Panzer:"
    desc: "Wenn die Tarraske Ziel des Zaubers *[[3-Compendium/Zauber/Magisches Geschoss|Magisches Geschoss]]* oder eines Zaubers wird, der einen Fernkampfangriffswurf erfordert, würfle mit 1W6. Bei einer **1–5** ist die Tarraske nicht betroffen. Bei einer **6** ist die Tarraske nicht betroffen und wirft den Zauber zurück, sodass der Zauberwirker zum Ziel wird."
actions:
  - name: "Mehrfachangriff:"
    desc: "Die Tarraske führt einen Bissangriff oder drei andere Angriffe aus, wobei sie Klauen oder Schwanz in beliebiger Kombination einsetzt."
  - name: "Biss:"
    desc: "*Nahkampfangriffswurf:* +19, Reichweite 4,5 m. *Treffer:* 36 (4W12+10) Stichschaden, und das Ziel wird [[3-Compendium/Zustände/Gepackt|gepackt]] (Flucht-SG 20). Das gepackte Ziel ist [[3-Compendium/Zustände/Festgesetzt|festgesetzt]] und kann sich nicht teleportieren."
  - name: "Klauen:"
    desc: "*Nahkampfangriffswurf:* +19, Reichweite 4,5 m. *Treffer:* 28 (4W8+10) Hiebschaden."
  - name: "Schwanz:"
    desc: "*Nahkampfangriffswurf:* +19, Reichweite 9 m. *Treffer:* 23 (3W8+10) Wuchtschaden. Wenn das Ziel eine Kreatur von höchstens riesiger Größe ist, wird es umgestoßen und hat den Zustand [[3-Compendium/Zustände/Liegend|Liegend]]."
  - name: "Donnerndes Brüllen (Aufladung 5–6):"
    desc: "*Konstitutionsrettungswurf:* SG 27; alle Kreaturen sowie Gegenstände, die nicht getragen oder gehalten werden, in einem Kegel von 45 Metern. *Misserfolg:* 78 (12W12) Schallschaden, und das Ziel ist bis zum Ende seines nächsten Zugs [[3-Compendium/Zustände/Taub|taub]] und [[3-Compendium/Zustände/Verängstigt|verängstigt]]. *Erfolg:* Nur halber Schaden."
bonus_actions:
  - name: "Verschlucken:"
    desc: "*Stärkerettungswurf:* SG 27; eine Kreatur von höchstens großer Größe, die von der Tarraske [[3-Compendium/Zustände/Gepackt|gepackt]] wurde (die Tarraske kann bis zu sechs Kreaturen verschlucken). *Misserfolg:* Das Ziel wird verschluckt und ist dann nicht mehr gepackt. Eine verschluckte Kreatur ist [[3-Compendium/Zustände/Blind|blind]] und [[3-Compendium/Zustände/Festgesetzt|festgesetzt]] und kann nicht teleportieren. Sie hat vollständige Deckung gegen Angriffe und andere Effekte von außerhalb der Tarraske und erleidet zu Beginn jedes Zugs der Tarraske 56 (16W6) Säureschaden.\n\nErleidet die Tarraske durch eine verschluckte Kreatur in einem einzigen Zug mindestens 60 Schaden, so muss sie am Ende des Zugs einen SG-20-Konstitutionsrettungswurf bestehen, oder sie würgt alle verschluckten Kreaturen wieder aus. Diese fallen in Bereiche im Abstand von bis zu drei Metern von der Tarraske und haben den Zustand [[3-Compendium/Zustände/Liegend|Liegend]]. Wenn die Tarraske stirbt, sind die verschluckten Kreaturen nicht mehr festgesetzt und können aus dem Kadaver entkommen. Sie verbrauchen dabei sechs Meter Bewegung und haben danach den Zustand Liegend."
legendary_description: "*Anwendungen legendärer Aktionen: 3. Unmittelbar nach dem Zug einer anderen Kreatur kann die Tarraske eine legendäre Aktion ausführen. Zu Beginn jedes ihrer Züge stehen der Tarraske wieder alle ausgeführten legendären Aktionen zur Verfügung.*"
legendary_actions:
  - name: "Ansturm:"
    desc: "Die Tarraske legt bis zur Hälfte ihrer Bewegungsrate zurück und führt einen Klauen- oder einen Schwanzangriff aus."
  - name: "Weltenerschütternde Bewegung:"
    desc: "Die Tarraske nutzt ihre Bewegungsrate. Am Ende dieser Bewegung erzeugt die Tarraske in einer Ausströmung von 18 Metern, die von ihr ausgeht, eine unmittelbare Schockwelle. Kreaturen in diesem Bereich verlieren die Konzentration, und Kreaturen von höchstens mittelgroßer Größe stürzen, sodass sie den Zustand [[3-Compendium/Zustände/Liegend|Liegend]] haben. Die Tarraske kann diese Aktion erst nach Beginn ihres nächsten Zugs erneut ausführen."
---

> [!srd-ficha] Tarraske
> *Gigantische Monstrosität (Titan), gesinnungslos*
>
> **RK** 25 · **Initiative** +18 (28)
>
> **TP** 697 (34W20+340)
>
> **Bewegungsrate** 18 m, Graben 12 m, Klettern 18 m
>
> |   |   | MOD | RW |   |   | MOD | RW |   |   | MOD | RW |
> | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
> | **Stä** | 30 | +10 | +10 | **Ges** | 11 | +0 | +9 | **Kon** | 30 | +10 | +10 |
> | **Int** | 3 | −4 | +5 | **Wei** | 11 | +0 | +9 | **Cha** | 11 | +0 | +9 |
>
> **Fertigkeiten** Wahrnehmung +9
>
> **Resistenzen** Hieb, Stich, Wucht
>
> **Immunitäten** Feuer, Gift; [[Bezaubert|Bezaubert]], [[Gelähmt|Gelähmt]], [[Taub|Taub]], [[Verängstigt|Verängstigt]], [[Vergiftet|Vergiftet]]
>
> **Sinne** Blindsicht 36 m; Passive Wahrnehmung 19
>
> **Sprachen** −
>
> **HG** 30 (EP 155.000; ÜB +9)

## Merkmale

***Belagerungsmonster:*** Die Tarraske fügt Gegenständen und Gebäuden doppelten Schaden zu.

***Legendäre Resistenz (6-mal täglich):*** Wenn die Tarraske bei einem Rettungswurf scheitert, kann sie beschließen, ihn stattdessen zu bestehen.

***Magieresistenz:*** Die Tarraske ist bei Rettungswürfen gegen Zauber und andere magische Effekte im Vorteil.

***Reflektierender Panzer:*** Wenn die Tarraske Ziel des Zaubers *[[Magisches Geschoss|Magisches Geschoss]]* oder eines Zaubers wird, der einen Fernkampfangriffswurf erfordert, würfle mit 1W6. Bei einer **1–5** ist die Tarraske nicht betroffen. Bei einer **6** ist die Tarraske nicht betroffen und wirft den Zauber zurück, sodass der Zauberwirker zum Ziel wird.

## Aktionen

***Mehrfachangriff:*** Die Tarraske führt einen Bissangriff oder drei andere Angriffe aus, wobei sie Klauen oder Schwanz in beliebiger Kombination einsetzt.

***Biss:*** *Nahkampfangriffswurf:* +19, Reichweite 4,5 m. *Treffer:* 36 (4W12+10) Stichschaden, und das Ziel wird [[Gepackt|gepackt]] (Flucht-SG 20). Das gepackte Ziel ist [[Festgesetzt|festgesetzt]] und kann sich nicht teleportieren.

***Klauen:*** *Nahkampfangriffswurf:* +19, Reichweite 4,5 m. *Treffer:* 28 (4W8+10) Hiebschaden.

***Schwanz:*** *Nahkampfangriffswurf:* +19, Reichweite 9 m. *Treffer:* 23 (3W8+10) Wuchtschaden. Wenn das Ziel eine Kreatur von höchstens riesiger Größe ist, wird es umgestoßen und hat den Zustand [[Liegend|Liegend]].

***Donnerndes Brüllen (Aufladung 5–6):*** *Konstitutionsrettungswurf:* SG 27; alle Kreaturen sowie Gegenstände, die nicht getragen oder gehalten werden, in einem Kegel von 45 Metern. *Misserfolg:* 78 (12W12) Schallschaden, und das Ziel ist bis zum Ende seines nächsten Zugs taub und verängstigt. *Erfolg:* Nur halber Schaden.

## Bonusaktionen

***Verschlucken:*** *Stärkerettungswurf:* SG 27; eine Kreatur von höchstens großer Größe, die von der Tarraske gepackt wurde (die Tarraske kann bis zu sechs Kreaturen verschlucken). *Misserfolg:* Das Ziel wird verschluckt und ist dann nicht mehr gepackt. Eine verschluckte Kreatur ist [[Blind|blind]] und festgesetzt und kann nicht teleportieren. Sie hat vollständige Deckung gegen Angriffe und andere Effekte von außerhalb der Tarraske und erleidet zu Beginn jedes Zugs der Tarraske 56 (16W6) Säureschaden.

Erleidet die Tarraske durch eine verschluckte Kreatur in einem einzigen Zug mindestens 60 Schaden, so muss sie am Ende des Zugs einen SG-20-Konstitutionsrettungswurf bestehen, oder sie würgt alle verschluckten Kreaturen wieder aus. Diese fallen in Bereiche im Abstand von bis zu drei Metern von der Tarraske und haben den Zustand Liegend. Wenn die Tarraske stirbt, sind die verschluckten Kreaturen nicht mehr festgesetzt und können aus dem Kadaver entkommen. Sie verbrauchen dabei sechs Meter Bewegung und haben danach den Zustand Liegend.

## Legendäre Aktionen

*Anwendungen legendärer Aktionen: 3. Unmittelbar nach dem Zug einer anderen Kreatur kann die Tarraske eine legendäre Aktion ausführen. Zu Beginn jedes ihrer Züge stehen der Tarraske wieder alle ausgeführten legendären Aktionen zur Verfügung.*

***Ansturm:*** Die Tarraske legt bis zur Hälfte ihrer Bewegungsrate zurück und führt einen Klauen- oder einen Schwanzangriff aus.

***Weltenerschütternde Bewegung:*** Die Tarraske nutzt ihre Bewegungsrate. Am Ende dieser Bewegung erzeugt die Tarraske in einer Ausströmung von 18 Metern, die von ihr ausgeht, eine unmittelbare Schockwelle. Kreaturen in diesem Bereich verlieren die Konzentration, und Kreaturen von höchstens mittelgroßer Größe stürzen, sodass sie den Zustand Liegend haben. Die Tarraske kann diese Aktion erst nach Beginn ihres nächsten Zugs erneut ausführen.
