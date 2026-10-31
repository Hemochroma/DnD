---
srd: "criatura/vampire"
tags:
  - "srd/kreatur"
typ: "Kleiner oder mittelgroßer Untoter, rechtschaffen böse"
gruppe: "Vampire"
hg: "13"
ep: 10000
rk: 16
tp: 195
initiative: 14
statblock: true
layout: "Compendio SRD 2024 (Deutsch)"
name: "Vampir"
type: "Kleiner oder mittelgroßer Untoter, rechtschaffen böse"
ac: 16
hp: 195
hit_dice: "23d8+92"
modifier: 14
speed: "12 m, Klettern 12 m"
stats:
  - 18
  - 18
  - 18
  - 17
  - 15
  - 18
initiative_text: "+14 (24)"
hp_text: "195 (23W8+92)"
stats_table: "|   |   | MOD | RW |   |   | MOD | RW |   |   | MOD | RW |\n| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |\n| **Stä** | 18 | +4 | +4 | **Ges** | 18 | +4 | +9 | **Kon** | 18 | +4 | +9 |\n| **Int** | 17 | +3 | +3 | **Wei** | 15 | +2 | +7 | **Cha** | 18 | +4 | +9 |"
skills_text: "Heimlichkeit +9, Wahrnehmung +7"
cr_text: "13 (EP 10.000 oder 11.500 im Hort; ÜB +5)"
saves:
  - Ges: 9
  - Kon: 9
  - Wei: 7
  - Cha: 9
skillsaves:
  - Heimlichkeit: 9
  - Wahrnehmung: 7
damage_resistances: "Nekrotisch"
senses: "Dunkelsicht 36 m; Passive Wahrnehmung 17"
languages: "Gemeinsprache und zwei weitere Sprachen"
cr: 13
traits:
  - name: "Legendäre Resistenz (3-mal täglich, im Hort 4-mal täglich):"
    desc: "Wenn der Vampir bei einem Rettungswurf scheitert, kann er beschließen, ihn stattdessen zu bestehen."
  - name: "Neblige Flucht:"
    desc: "Wenn die Trefferpunkte des Vampirs außerhalb seines Ruheplatzes auf 0 sinken, nutzt der Vampir Gestaltwandeln, um zu Nebel zu werden (keine Aktion erforderlich). Wenn er sich nicht verwandeln kann, wird er zerstört.\n\nMit 0 Trefferpunkten in Nebelgestalt kann er sich nicht in seine Vampirgestalt zurückverwandeln und muss innerhalb der nächsten zwei Stunden seinen Ruheplatz erreichen, oder er wird zerstört. Nach der Rückkehr an seinen Ruheplatz verwandelt er sich in seine Vampirgestalt und ist [[3-Compendium/Zustände/Gelähmt|gelähmt]], bis er Trefferpunkte zurückerhält, und nachdem er eine Stunde dort verbracht hat, erhält er 1 Trefferpunkt zurück."
  - name: "Spinnenklettern:"
    desc: "Der Vampir kann ohne Attributswürfe schwierige Oberflächen erklimmen und sich an Decken entlang bewegen."
  - name: "Vampirschwächen:"
    desc: "Der Vampir hat folgende Schwächen:\n\n- **Zutritt verwehren:** Der Vampir kann keine Behausung betreten, ohne von einem der Bewohner eingeladen worden zu sein.\n- **Fließendes Wasser:** Der Vampir erleidet 20 Säureschaden, wenn er seinen Zug in fließendem Wasser beendet.\n- **Holzpflock ins Herz:** Wird dem Vampir eine Waffe ins Herz getrieben, die Stichschaden bewirkt, während er [[3-Compendium/Zustände/Kampfunfähig|kampfunfähig]] ist und sich an seinem Ruheplatz aufhält, ist er [[3-Compendium/Zustände/Gelähmt|gelähmt]], bis die Waffe entfernt wird.\n- **Sonnenlicht:** Der Vampir erleidet 20 gleißenden Schaden, wenn er seinen Zug im Sonnenlicht beginnt. Im Sonnenlicht ist er bei Angriffs- und Attributswürfen im Nachteil."
actions:
  - name: "Mehrfachangriff (nur Vampirgestalt):"
    desc: "Der Vampir führt zwei Grabesschlag-Angriffe aus und setzt Biss ein."
  - name: "Grabesschlag (nur Vampirgestalt):"
    desc: "*Nahkampfangriffswurf:* +9, Reichweite 1,5 m. *Treffer:* 8 (1W8+4) Wuchtschaden plus 7 (2W6) nekrotischer Schaden. Wenn das Ziel eine Kreatur von höchstens großer Größe ist, wird es von einer der beiden Hände [[3-Compendium/Zustände/Gepackt|gepackt]] (Flucht-SG 14)."
  - name: "Biss (nur Fledermaus- oder Vampirgestalt):"
    desc: "*Konstitutionsrettungswurf:* SG 17; eine Kreatur im Abstand von bis zu 1,5 Metern, die bereitwillig, [[3-Compendium/Zustände/Festgesetzt|festgesetzt]], [[3-Compendium/Zustände/Gepackt|gepackt]] oder [[3-Compendium/Zustände/Kampfunfähig|kampfunfähig]] ist. *Misserfolg:* 6 (1W4+4) Stichschaden plus 13 (3W8) nekrotischer Schaden. Das Trefferpunktemaximum des Ziels wird um eine Anzahl in Höhe des erlittenen nekrotischen Schadens verringert, und der Vampir erhält Trefferpunkte in Höhe dieses Betrags zurück. Ein Humanoide, dessen Trefferpunkte durch diesen Schaden auf 0 sinken und der dann begraben wird, erhebt sich beim nächsten Sonnenaufgang als **[[3-Compendium/Kreaturen/Vampirbrut|Vampirbrut]]** und untersteht der Kontrolle des Vampirs."
bonus_actions:
  - name: "Bezaubern (Aufladung 5–6):"
    desc: "Der Vampir wirkt den Zauber *[[3-Compendium/Zauber/Person bezaubern|Person bezaubern]]* mit Charisma als Attribut zum Zauberwirken, ohne Zauberkomponenten zu benötigen (Zauberrettungswurf-SG 17). Der Zauber wirkt 24 Stunden lang. Das [[3-Compendium/Zustände/Bezaubert|bezauberte]] Ziel lässt sich bereitwillig vom Vampir beißen, der Schaden beendet denn Zauber nicht. Nach Ende des Zaubers weiß das Ziel, dass es vom Vampir bezaubert wurde."
  - name: "Gestaltwandeln:"
    desc: "Wenn der Vampir sich nicht im Sonnenlicht oder in fließendem Wasser befindet, kann er sich in eine winzige Fledermaus (Bewegungsrate 1,5 m, Flugbewegungsrate 9 m) oder eine mittelgroße Nebelwolke (Bewegungsrate 1,5 m, Flugbewegungsrate 6 m (Schweben)) verwandeln oder seine Vampirgestalt annehmen. Alles, was er trägt, verwandelt sich mit ihm.\n\nIn Fledermausgestalt kann der Vampir nicht sprechen. Seine Spielwerte sind abgesehen von Größe und Bewegungsrate unverändert.\n\nIn Nebelgestalt kann der Vampir keine Aktionen ausführen, nicht sprechen und nicht mit Gegenständen interagieren. Er hat kein Gewicht und kann den Bereich eines Feindes betreten und dort stoppen. Sofern Luft durch einen Bereich strömen kann, kann der Nebel diesen Bereich ebenfalls passieren, jedoch keine Flüssigkeiten durchdringen. Er ist gegen alle Schadensarten resistent, abgesehen von durch Sonnenlicht erlittenen Schaden."
legendary_description: "*Anwendungen legendärer Aktionen: 3 (4 im Hort). Unmittelbar nach dem Zug einer anderen Kreatur kann der Vampir eine legendäre Aktion ausführen. Zu Beginn jedes seiner Züge stehen dem Vampir wieder alle ausgeführten legendären Aktionen zur Verfügung.*"
legendary_actions:
  - name: "Betören:"
    desc: "Der Vampir wirkt den Zauber *[[3-Compendium/Zauber/Befehl|Befehl]]* mit Charisma als Attribut zum Zauberwirken, ohne Zauberkomponenten zu benötigen (Zauberrettungswurf-SG 17). Der Vampir kann diese Aktion erst nach Beginn seines nächsten Zugs erneut ausführen."
  - name: "Untoter Schlag:"
    desc: "Der Vampir legt bis zur Hälfte seiner Bewegungsrate zurück und führt einen Grabesschlag-Angriff aus."
---

> [!srd-ficha] Vampir
> *Kleiner oder mittelgroßer Untoter, rechtschaffen böse*
>
> **RK** 16 · **Initiative** +14 (24)
>
> **TP** 195 (23W8+92)
>
> **Bewegungsrate** 12 m, Klettern 12 m
>
> |   |   | MOD | RW |   |   | MOD | RW |   |   | MOD | RW |
> | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
> | **Stä** | 18 | +4 | +4 | **Ges** | 18 | +4 | +9 | **Kon** | 18 | +4 | +9 |
> | **Int** | 17 | +3 | +3 | **Wei** | 15 | +2 | +7 | **Cha** | 18 | +4 | +9 |
>
> **Fertigkeiten** Heimlichkeit +9, Wahrnehmung +7
>
> **Resistenzen** Nekrotisch
>
> **Sinne** Dunkelsicht 36 m; Passive Wahrnehmung 17
>
> **Sprachen** Gemeinsprache und zwei weitere Sprachen
>
> **HG** 13 (EP 10.000 oder 11.500 im Hort; ÜB +5)

## Merkmale

***Legendäre Resistenz (3-mal täglich, im Hort 4-mal täglich):*** Wenn der Vampir bei einem Rettungswurf scheitert, kann er beschließen, ihn stattdessen zu bestehen.

***Neblige Flucht:*** Wenn die Trefferpunkte des Vampirs außerhalb seines Ruheplatzes auf 0 sinken, nutzt der Vampir Gestaltwandeln, um zu Nebel zu werden (keine Aktion erforderlich). Wenn er sich nicht verwandeln kann, wird er zerstört.

Mit 0 Trefferpunkten in Nebelgestalt kann er sich nicht in seine Vampirgestalt zurückverwandeln und muss innerhalb der nächsten zwei Stunden seinen Ruheplatz erreichen, oder er wird zerstört. Nach der Rückkehr an seinen Ruheplatz verwandelt er sich in seine Vampirgestalt und ist [[Gelähmt|gelähmt]], bis er Trefferpunkte zurückerhält, und nachdem er eine Stunde dort verbracht hat, erhält er 1 Trefferpunkt zurück.

***Spinnenklettern:*** Der Vampir kann ohne Attributswürfe schwierige Oberflächen erklimmen und sich an Decken entlang bewegen.

***Vampirschwächen:*** Der Vampir hat folgende Schwächen:

- **Zutritt verwehren:** Der Vampir kann keine Behausung betreten, ohne von einem der Bewohner eingeladen worden zu sein.
- **Fließendes Wasser:** Der Vampir erleidet 20 Säureschaden, wenn er seinen Zug in fließendem Wasser beendet.
- **Holzpflock ins Herz:** Wird dem Vampir eine Waffe ins Herz getrieben, die Stichschaden bewirkt, während er [[Kampfunfähig|kampfunfähig]] ist und sich an seinem Ruheplatz aufhält, ist er gelähmt, bis die Waffe entfernt wird.
- **Sonnenlicht:** Der Vampir erleidet 20 gleißenden Schaden, wenn er seinen Zug im Sonnenlicht beginnt. Im Sonnenlicht ist er bei Angriffs- und Attributswürfen im Nachteil.

## Aktionen

***Mehrfachangriff (nur Vampirgestalt):*** Der Vampir führt zwei Grabesschlag-Angriffe aus und setzt Biss ein.

***Grabesschlag (nur Vampirgestalt):*** *Nahkampfangriffswurf:* +9, Reichweite 1,5 m. *Treffer:* 8 (1W8+4) Wuchtschaden plus 7 (2W6) nekrotischer Schaden. Wenn das Ziel eine Kreatur von höchstens großer Größe ist, wird es von einer der beiden Hände [[Gepackt|gepackt]] (Flucht-SG 14).

***Biss (nur Fledermaus- oder Vampirgestalt):*** *Konstitutionsrettungswurf:* SG 17; eine Kreatur im Abstand von bis zu 1,5 Metern, die bereitwillig, [[Festgesetzt|festgesetzt]], gepackt oder kampfunfähig ist. *Misserfolg:* 6 (1W4+4) Stichschaden plus 13 (3W8) nekrotischer Schaden. Das Trefferpunktemaximum des Ziels wird um eine Anzahl in Höhe des erlittenen nekrotischen Schadens verringert, und der Vampir erhält Trefferpunkte in Höhe dieses Betrags zurück. Ein Humanoide, dessen Trefferpunkte durch diesen Schaden auf 0 sinken und der dann begraben wird, erhebt sich beim nächsten Sonnenaufgang als **[[Vampirbrut|Vampirbrut]]** und untersteht der Kontrolle des Vampirs.

## Bonusaktionen

***Bezaubern (Aufladung 5–6):*** Der Vampir wirkt den Zauber *[[Person bezaubern|Person bezaubern]]* mit Charisma als Attribut zum Zauberwirken, ohne Zauberkomponenten zu benötigen (Zauberrettungswurf-SG 17). Der Zauber wirkt 24 Stunden lang. Das [[Bezaubert|bezauberte]] Ziel lässt sich bereitwillig vom Vampir beißen, der Schaden beendet denn Zauber nicht. Nach Ende des Zaubers weiß das Ziel, dass es vom Vampir bezaubert wurde.

***Gestaltwandeln:*** Wenn der Vampir sich nicht im Sonnenlicht oder in fließendem Wasser befindet, kann er sich in eine winzige Fledermaus (Bewegungsrate 1,5 m, Flugbewegungsrate 9 m) oder eine mittelgroße Nebelwolke (Bewegungsrate 1,5 m, Flugbewegungsrate 6 m (Schweben)) verwandeln oder seine Vampirgestalt annehmen. Alles, was er trägt, verwandelt sich mit ihm.

In Fledermausgestalt kann der Vampir nicht sprechen. Seine Spielwerte sind abgesehen von Größe und Bewegungsrate unverändert.

In Nebelgestalt kann der Vampir keine Aktionen ausführen, nicht sprechen und nicht mit Gegenständen interagieren. Er hat kein Gewicht und kann den Bereich eines Feindes betreten und dort stoppen. Sofern Luft durch einen Bereich strömen kann, kann der Nebel diesen Bereich ebenfalls passieren, jedoch keine Flüssigkeiten durchdringen. Er ist gegen alle Schadensarten resistent, abgesehen von durch Sonnenlicht erlittenen Schaden.

## Legendäre Aktionen

*Anwendungen legendärer Aktionen: 3 (4 im Hort). Unmittelbar nach dem Zug einer anderen Kreatur kann der Vampir eine legendäre Aktion ausführen. Zu Beginn jedes seiner Züge stehen dem Vampir wieder alle ausgeführten legendären Aktionen zur Verfügung.*

***Betören:*** Der Vampir wirkt den Zauber *[[Befehl|Befehl]]* mit Charisma als Attribut zum Zauberwirken, ohne Zauberkomponenten zu benötigen (Zauberrettungswurf-SG 17). Der Vampir kann diese Aktion erst nach Beginn seines nächsten Zugs erneut ausführen.

***Untoter Schlag:*** Der Vampir legt bis zur Hälfte seiner Bewegungsrate zurück und führt einen Grabesschlag-Angriff aus.
