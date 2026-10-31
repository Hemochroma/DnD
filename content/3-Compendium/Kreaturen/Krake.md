---
srd: "criatura/kraken"
tags:
  - "srd/kreatur"
typ: "Gigantische Monstrosität (Titan), chaotisch böse"
gruppe: "Krake"
hg: "23"
ep: 50000
rk: 18
tp: 481
initiative: 14
statblock: true
layout: "Compendio SRD 2024 (Deutsch)"
name: "Krake"
type: "Gigantische Monstrosität (Titan), chaotisch böse"
ac: 18
hp: 481
hit_dice: "26d20+208"
modifier: 14
speed: "9 m, Schwimmen 36 m"
stats:
  - 30
  - 11
  - 26
  - 22
  - 18
  - 20
initiative_text: "+14 (24)"
hp_text: "481 (26W20+208)"
stats_table: "|   |   | MOD | RW |   |   | MOD | RW |   |   | MOD | RW |\n| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |\n| **Stä** | 30 | +10 | +17 | **Ges** | 11 | +0 | +7 | **Kon** | 26 | +8 | +15 |\n| **Int** | 22 | +6 | +6 | **Wei** | 18 | +4 | +11 | **Cha** | 20 | +5 | +5 |"
skills_text: "Geschichte +13, Wahrnehmung +11"
immunities_text: "Blitz, Kälte; [[3-Compendium/Zustände/Festgesetzt|Festgesetzt]], [[3-Compendium/Zustände/Gelähmt|Gelähmt]], [[3-Compendium/Zustände/Gepackt|Gepackt]], [[3-Compendium/Zustände/Verängstigt|Verängstigt]]"
cr_text: "23 (EP 50.000 oder 62.000 im Hort; ÜB +7)"
saves:
  - Stä: 17
  - Ges: 7
  - Kon: 15
  - Wei: 11
skillsaves:
  - Geschichte: 13
  - Wahrnehmung: 11
damage_immunities: "Blitz, Kälte"
condition_immunities: "Festgesetzt, Gelähmt, Gepackt, Verängstigt"
senses: "Wahrer Blick 36 m; Passive Wahrnehmung 21"
languages: "Versteht Abyssisch, Celestisch, Infernalisch und Urtümlich, kann jedoch nicht sprechen; Telepathie auf 36 m"
cr: 23
traits:
  - name: "Amphibisch:"
    desc: "Der Krake kann Luft und Wasser atmen."
  - name: "Belagerungsmonster:"
    desc: "Der Krake fügt Gegenständen und Gebäuden doppelten Schaden zu."
  - name: "Legendäre Resistenz (4-mal täglich, im Hort 5-mal täglich):"
    desc: "Wenn der Krake bei einem Rettungswurf scheitert, kann er beschließen, ihn stattdessen zu bestehen."
actions:
  - name: "Mehrfachangriff:"
    desc: "Der Krake führt zwei Tentakelangriffe aus und setzt Blitzschlag, Schleudern oder Verschlucken ein."
  - name: "Tentakel:"
    desc: "*Nahkampfangriffswurf:* +17, Reichweite 9 m. *Treffer:* 24 (4W6+10) Wuchtschaden. Das Ziel wird von einem der zehn Tenakel [[3-Compendium/Zustände/Gepackt|gepackt]] (Flucht-SG 20). Solange es gepackt bleibt, ist es außerdem [[3-Compendium/Zustände/Festgesetzt|festgesetzt]]."
  - name: "Blitzschlag:"
    desc: "*Geschicklichkeitsrettungswurf:* SG 23; eine Kreatur im Abstand von bis zu 36 Metern vom Kraken, die er sehen kann. *Misserfolg:* 33 (6W10) Blitzschaden. *Erfolg:* Halber Schaden."
  - name: "Schleudern:"
    desc: "Der Krake schleudert eine Kreatur von höchstens großer Größe, die er [[3-Compendium/Zustände/Gepackt|gepackt]] hält, in einen Bereich im Abstand von bis zu 18 Metern von sich, den er sehen kann und der sich nicht in der Luft befindet. *Geschicklichkeitsrettungswurf:* SG 25; die geworfene Kreatur und jede Kreatur im Zielbereich. *Misserfolg:* 18 (4W8) Wuchtschaden, und das Ziel wird umgestoßen und hat den Zustand [[3-Compendium/Zustände/Liegend|Liegend]]. *Erfolg:* Nur halber Schaden."
  - name: "Verschlucken:"
    desc: "*Geschicklichkeitsrettungswurf:* SG 25; eine Kreatur, die vom Kraken [[3-Compendium/Zustände/Gepackt|gepackt]] wurde (der Krake kann bis zu vier Kreaturen verschlucken). *Misserfolg:* 23 (3W8+10) Stichschaden. Wenn das Ziel von höchstens großer Größe ist, wird es verschluckt und ist dann nicht mehr gepackt. Eine verschluckte Kreatur ist [[3-Compendium/Zustände/Festgesetzt|festgesetzt]], hat vollständige Deckung gegen Angriffe sowie andere Effekte von außerhalb des Kraken und erleidet zu Beginn jedes ihrer Züge 24 (7W6) Säureschaden.\n\nErleidet der Krake durch eine verschluckte Kreatur in einem einzigen Zug mindestens 50 Schaden, so muss er am Ende des Zugs einen SG-25-Konstitutionsrettungswurf bestehen, oder er würgt alle verschluckten Kreaturen wieder aus. Diese fallen in Bereiche im Abstand von bis zu drei Metern vom Kraken und haben den Zustand [[3-Compendium/Zustände/Liegend|Liegend]]. Wenn der Krake stirbt, sind die verschluckten Kreaturen nicht mehr festgesetzt und können aus dem Kadaver entkommen. Sie verbrauchen dabei 4,5 Meter Bewegung und haben danach den Zustand Liegend."
legendary_description: "*Anwendungen legendärer Aktionen: 3 (4 im Hort). Unmittelbar nach dem Zug einer anderen Kreatur kann der Kraken eine legendäre Aktion ausführen. Zu Beginn jedes seiner Züge stehen dem Kraken wieder alle ausgeführten legendären Aktionen zur Verfügung.*"
legendary_actions:
  - name: "Giftige Tinte:"
    desc: "*Konstitutionsrettungswurf:* SG 23; jede Kreatur in einer Ausströmung von 4,5 Metern, die vom Kraken ausgeht, während er sich unter Wasser befindet. *Misserfolg:* Das Ziel ist bis zum Ende des nächsten Zugs des Kraken [[3-Compendium/Zustände/Blind|blind]] und [[3-Compendium/Zustände/Vergiftet|vergiftet]]. Der Krake nutzt dann seine Bewegungsrate. *Erfolg oder Misserfolg:* Der Krake kann diese Aktion erst nach Beginn seines nächsten Zugs erneut ausführen."
  - name: "Sturmblitz:"
    desc: "Der Krake setzt Blitzschlag ein."
---

> [!srd-ficha] Krake
> *Gigantische Monstrosität (Titan), chaotisch böse*
>
> **RK** 18 · **Initiative** +14 (24)
>
> **TP** 481 (26W20+208)
>
> **Bewegungsrate** 9 m, Schwimmen 36 m
>
> |   |   | MOD | RW |   |   | MOD | RW |   |   | MOD | RW |
> | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
> | **Stä** | 30 | +10 | +17 | **Ges** | 11 | +0 | +7 | **Kon** | 26 | +8 | +15 |
> | **Int** | 22 | +6 | +6 | **Wei** | 18 | +4 | +11 | **Cha** | 20 | +5 | +5 |
>
> **Fertigkeiten** Geschichte +13, Wahrnehmung +11
>
> **Immunitäten** Blitz, Kälte; [[Festgesetzt|Festgesetzt]], [[Gelähmt|Gelähmt]], [[Gepackt|Gepackt]], [[Verängstigt|Verängstigt]]
>
> **Sinne** Wahrer Blick 36 m; Passive Wahrnehmung 21
>
> **Sprachen** Versteht Abyssisch, Celestisch, Infernalisch und Urtümlich, kann jedoch nicht sprechen; Telepathie auf 36 m
>
> **HG** 23 (EP 50.000 oder 62.000 im Hort; ÜB +7)

## Merkmale

***Amphibisch:*** Der Krake kann Luft und Wasser atmen.

***Belagerungsmonster:*** Der Krake fügt Gegenständen und Gebäuden doppelten Schaden zu.

***Legendäre Resistenz (4-mal täglich, im Hort 5-mal täglich):*** Wenn der Krake bei einem Rettungswurf scheitert, kann er beschließen, ihn stattdessen zu bestehen.

## Aktionen

***Mehrfachangriff:*** Der Krake führt zwei Tentakelangriffe aus und setzt Blitzschlag, Schleudern oder Verschlucken ein.

***Tentakel:*** *Nahkampfangriffswurf:* +17, Reichweite 9 m. *Treffer:* 24 (4W6+10) Wuchtschaden. Das Ziel wird von einem der zehn Tenakel gepackt (Flucht-SG 20). Solange es gepackt bleibt, ist es außerdem festgesetzt.

***Blitzschlag:*** *Geschicklichkeitsrettungswurf:* SG 23; eine Kreatur im Abstand von bis zu 36 Metern vom Kraken, die er sehen kann. *Misserfolg:* 33 (6W10) Blitzschaden. *Erfolg:* Halber Schaden.

***Schleudern:*** Der Krake schleudert eine Kreatur von höchstens großer Größe, die er gepackt hält, in einen Bereich im Abstand von bis zu 18 Metern von sich, den er sehen kann und der sich nicht in der Luft befindet. *Geschicklichkeitsrettungswurf:* SG 25; die geworfene Kreatur und jede Kreatur im Zielbereich. *Misserfolg:* 18 (4W8) Wuchtschaden, und das Ziel wird umgestoßen und hat den Zustand [[Liegend|Liegend]]. *Erfolg:* Nur halber Schaden.

***Verschlucken:*** *Geschicklichkeitsrettungswurf:* SG 25; eine Kreatur, die vom Kraken gepackt wurde (der Krake kann bis zu vier Kreaturen verschlucken). *Misserfolg:* 23 (3W8+10) Stichschaden. Wenn das Ziel von höchstens großer Größe ist, wird es verschluckt und ist dann nicht mehr gepackt. Eine verschluckte Kreatur ist festgesetzt, hat vollständige Deckung gegen Angriffe sowie andere Effekte von außerhalb des Kraken und erleidet zu Beginn jedes ihrer Züge 24 (7W6) Säureschaden.

Erleidet der Krake durch eine verschluckte Kreatur in einem einzigen Zug mindestens 50 Schaden, so muss er am Ende des Zugs einen SG-25-Konstitutionsrettungswurf bestehen, oder er würgt alle verschluckten Kreaturen wieder aus. Diese fallen in Bereiche im Abstand von bis zu drei Metern vom Kraken und haben den Zustand Liegend. Wenn der Krake stirbt, sind die verschluckten Kreaturen nicht mehr festgesetzt und können aus dem Kadaver entkommen. Sie verbrauchen dabei 4,5 Meter Bewegung und haben danach den Zustand Liegend.

## Legendäre Aktionen

*Anwendungen legendärer Aktionen: 3 (4 im Hort). Unmittelbar nach dem Zug einer anderen Kreatur kann der Kraken eine legendäre Aktion ausführen. Zu Beginn jedes seiner Züge stehen dem Kraken wieder alle ausgeführten legendären Aktionen zur Verfügung.*

***Giftige Tinte:*** *Konstitutionsrettungswurf:* SG 23; jede Kreatur in einer Ausströmung von 4,5 Metern, die vom Kraken ausgeht, während er sich unter Wasser befindet. *Misserfolg:* Das Ziel ist bis zum Ende des nächsten Zugs des Kraken [[Blind|blind]] und [[Vergiftet|vergiftet]]. Der Krake nutzt dann seine Bewegungsrate. *Erfolg oder Misserfolg:* Der Krake kann diese Aktion erst nach Beginn seines nächsten Zugs erneut ausführen.

***Sturmblitz:*** Der Krake setzt Blitzschlag ein.
