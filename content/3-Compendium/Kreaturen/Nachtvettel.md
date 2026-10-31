---
srd: criatura/night-hag
tags:
  - srd/kreatur
typ: Mittelgroßer Unhold, neutral böse
gruppe: Nachtvettel
hg: "5"
ep: 1800
rk: 17
tp: 112
initiative: 5
statblock: true
layout: Compendio SRD 2024 (Deutsch)
name: Nachtvettel
type: Mittelgroßer Unhold, neutral böse
ac: 17
hp: 112
hit_dice: 15d8+45
modifier: 5
speed: 9 m
stats:
  - 18
  - 15
  - 16
  - 16
  - 14
  - 16
initiative_text: +5 (15)
hp_text: 112 (15W8+45)
stats_table: |-
  |   |   | MOD | RW |   |   | MOD | RW |   |   | MOD | RW |
  | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
  | **Stä** | 18 | +4 | +4 | **Ges** | 15 | +2 | +2 | **Kon** | 16 | +3 | +3 |
  | **Int** | 16 | +3 | +3 | **Wei** | 14 | +2 | +2 | **Cha** | 16 | +3 | +3 |
skills_text: Heimlichkeit +5, Motiv erkennen +5, Täuschen +6, Wahrnehmung +5
immunities_text: "[[Bezaubert|Bezaubert]]"
cr_text: 5 (EP 1.800; ÜB +3)
skillsaves:
  - Heimlichkeit: 5
  - Motiv erkennen: 5
  - Täuschen: 6
  - Wahrnehmung: 5
damage_resistances: Feuer, Kälte
damage_immunities: Bezaubert
senses: Dunkelsicht 36 m; Passive Wahrnehmung 15
languages: Abyssisch, Gemeinsprache, Infernalisch, Urtümlich
cr: 5
traits:
  - name: "Magieresistenz:"
    desc: Die Vettel ist bei Rettungswürfen gegen Zauber und andere magische Effekte im Vorteil.
  - name: "Seelenbeutel:"
    desc: |-
      Die Vettel hat einen Seelenbeutel. Wenn sie diesen Beutel bei sich hat, kann sie ihre Albtraumspuk-Aktion ausführen.

      Der Beutel besitzt eine RK von 15, 20 TP und ist gegen alle Schadensarten resistent. Wenn seine Trefferpunkte auf 0 sinken, zerfällt der Beutel zu Staub. Wird der Beutel zerstört, so werden alle Seelen befreit, die er enthält. Die Vettel kann nach sieben Tagen einen neuen Beutel erzeugen.
  - name: "Zirkelmagie:"
    desc: "Wenn die Vettel sich im Abstand von bis zu neun Metern von mindestens zwei Vettel-Verbündeten befindet, kann sie einen der folgenden Zauber mit dem normalen Zeitaufwand und Intelligenz als Attribut zum Zauberwirken wirken, ohne Materialkomponenten zu benötigen (Zauberrettungswurf-SG 14): *[[3-Compendium/Zauber/Ausspähung|Ausspähung]]*, *[[3-Compendium/Zauber/Gegenstand aufspüren|Gegenstand aufspüren]]*, *[[3-Compendium/Zauber/Identifizieren|Identifizieren]]*, *[[3-Compendium/Zauber/Unsichtbarer Diener|Unsichtbarer Diener]]*, *[[3-Compendium/Zauber/Vertrauten finden|Vertrauten finden]]* oder *[[3-Compendium/Zauber/Vorahnung|Vorahnung]]*. Die Vettel muss eine lange Rast beenden, ehe sie dieses Merkmal erneut verwenden kann, um den Zauber zu wirken."
actions:
  - name: "Mehrfachangriff:"
    desc: Die Vettel führt zwei Klauenangriffe aus.
  - name: "Klauen:"
    desc: "*Nahkampfangriffswurf:* +7, Reichweite 1,5 m. *Treffer:* 13 (2W8+4) Hiebschaden."
  - name: "Albtraumspuk (1-mal täglich; Seelenbeutel erforderlich):"
    desc: |-
      Auf der Ätherebene wirkt die Vettel den Zauber *[[3-Compendium/Zauber/Traum|Traum]]*. Ihr Attribut zum Zauberwirken ist dasselbe wie beim Ausführen der Zauberwirken-Aktion. Nur die Vettel kann als Bote des Zaubers fungieren, und das Ziel muss eine Kreatur auf der materiellen Ebene sein, die von der Vettel gesehen werden kann. Der Zauber misslingt und ist vergeudet, wenn das Ziel unter dem Effekt eines der Zauber *[[3-Compendium/Zauber/Schutz vor Gut und Böse|Schutz vor Gut und Böse]]* oder *[[3-Compendium/Zauber/Schutzkreis|Schutzkreis]]* steht.

      Wenn das Ziel durch den Zauber *[[3-Compendium/Zauber/Traum|Traum]]* Schaden erleidet, wird das Trefferpunktemaximum des Ziels um eine Anzahl in Höhe dieses Schadens verringert. Tötet der Zauber das Ziel, so wird dessen Seele im Seelenbeutel der Vettel gefangen, und das Ziel kann erst von den Toten auferweckt werden, wenn seine Seele befreit wird.
  - name: "Zauberwirken:"
    desc: |-
      Die Vettel wirkt einen der folgenden Zauber mit Intelligenz als Attribut zum Zauberwirken, ohne Materialkomponenten zu benötigen (Zauberrettungswurf-SG 14):

      - **Beliebig oft:** *Körperlosigkeit*, *[[3-Compendium/Zauber/Magie entdecken|Magie entdecken]]*, *[[3-Compendium/Zauber/Magisches Geschoss|Magisches Geschoss]]* (Version des 4. Grades)
      - **Je 2-mal täglich:** *[[3-Compendium/Zauber/Ebenenwechsel|Ebenenwechsel]]* (nur auf sich selbst), *[[3-Compendium/Zauber/Tödliches Phantom|Tödliches Phantom]]*
bonus_actions:
  - name: "Gestaltwandeln:"
    desc: Die Vettel nimmt die Gestalt eines Humanoiden von höchstens mittelgroßer Größe oder wieder ihre wahre Gestalt an. Seine Spielwerte sind abgesehen von der Größe in allen Gestalten gleich. Ausrüstung, die er trägt oder hält, wird nicht verwandelt.
---

> [!srd-ficha] Nachtvettel
> *Mittelgroßer Unhold, neutral böse*
>
> **RK** 17 · **Initiative** +5 (15)
>
> **TP** 112 (15W8+45)
>
> **Bewegungsrate** 9 m
>
> |   |   | MOD | RW |   |   | MOD | RW |   |   | MOD | RW |
> | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
> | **Stä** | 18 | +4 | +4 | **Ges** | 15 | +2 | +2 | **Kon** | 16 | +3 | +3 |
> | **Int** | 16 | +3 | +3 | **Wei** | 14 | +2 | +2 | **Cha** | 16 | +3 | +3 |
>
> **Fertigkeiten** Heimlichkeit +5, Motiv erkennen +5, Täuschen +6, Wahrnehmung +5
>
> **Resistenzen** Feuer, Kälte
>
> **Immunitäten** [[Bezaubert|Bezaubert]]
>
> **Sinne** Dunkelsicht 36 m; Passive Wahrnehmung 15
>
> **Sprachen** Abyssisch, Gemeinsprache, Infernalisch, Urtümlich
>
> **HG** 5 (EP 1.800; ÜB +3)

## Merkmale

***Magieresistenz:*** Die Vettel ist bei Rettungswürfen gegen Zauber und andere magische Effekte im Vorteil.

***Seelenbeutel:*** Die Vettel hat einen Seelenbeutel. Wenn sie diesen Beutel bei sich hat, kann sie ihre Albtraumspuk-Aktion ausführen.

Der Beutel besitzt eine RK von 15, 20 TP und ist gegen alle Schadensarten resistent. Wenn seine Trefferpunkte auf 0 sinken, zerfällt der Beutel zu Staub. Wird der Beutel zerstört, so werden alle Seelen befreit, die er enthält. Die Vettel kann nach sieben Tagen einen neuen Beutel erzeugen.

***Zirkelmagie:*** Wenn die Vettel sich im Abstand von bis zu neun Metern von mindestens zwei Vettel-Verbündeten befindet, kann sie einen der folgenden Zauber mit dem normalen Zeitaufwand und Intelligenz als Attribut zum Zauberwirken wirken, ohne Materialkomponenten zu benötigen (Zauberrettungswurf-SG 14): *[[Ausspähung|Ausspähung]]*, *[[Gegenstand aufspüren|Gegenstand aufspüren]]*, *[[Identifizieren|Identifizieren]]*, *[[Unsichtbarer Diener|Unsichtbarer Diener]]*, *[[Vertrauten finden|Vertrauten finden]]* oder *[[Vorahnung|Vorahnung]]*. Die Vettel muss eine lange Rast beenden, ehe sie dieses Merkmal erneut verwenden kann, um den Zauber zu wirken.

## Aktionen

***Mehrfachangriff:*** Die Vettel führt zwei Klauenangriffe aus.

***Klauen:*** *Nahkampfangriffswurf:* +7, Reichweite 1,5 m. *Treffer:* 13 (2W8+4) Hiebschaden.

***Albtraumspuk (1-mal täglich; Seelenbeutel erforderlich):*** Auf der Ätherebene wirkt die Vettel den Zauber *[[Traum|Traum]]*. Ihr Attribut zum Zauberwirken ist dasselbe wie beim Ausführen der Zauberwirken-Aktion. Nur die Vettel kann als Bote des Zaubers fungieren, und das Ziel muss eine Kreatur auf der materiellen Ebene sein, die von der Vettel gesehen werden kann. Der Zauber misslingt und ist vergeudet, wenn das Ziel unter dem Effekt eines der Zauber *[[Schutz vor Gut und Böse|Schutz vor Gut und Böse]]* oder *[[Schutzkreis|Schutzkreis]]* steht.

Wenn das Ziel durch den Zauber *[[Traum|Traum]]* Schaden erleidet, wird das Trefferpunktemaximum des Ziels um eine Anzahl in Höhe dieses Schadens verringert. Tötet der Zauber das Ziel, so wird dessen Seele im Seelenbeutel der Vettel gefangen, und das Ziel kann erst von den Toten auferweckt werden, wenn seine Seele befreit wird.

***Zauberwirken:*** Die Vettel wirkt einen der folgenden Zauber mit Intelligenz als Attribut zum Zauberwirken, ohne Materialkomponenten zu benötigen (Zauberrettungswurf-SG 14):

- **Beliebig oft:** *Körperlosigkeit*, *[[Magie entdecken|Magie entdecken]]*, *[[Magisches Geschoss|Magisches Geschoss]]* (Version des 4. Grades)
- **Je 2-mal täglich:** *[[Ebenenwechsel|Ebenenwechsel]]* (nur auf sich selbst), *[[Tödliches Phantom|Tödliches Phantom]]*

## Bonusaktionen

***Gestaltwandeln:*** Die Vettel nimmt die Gestalt eines Humanoiden von höchstens mittelgroßer Größe oder wieder ihre wahre Gestalt an. Seine Spielwerte sind abgesehen von der Größe in allen Gestalten gleich. Ausrüstung, die er trägt oder hält, wird nicht verwandelt.
