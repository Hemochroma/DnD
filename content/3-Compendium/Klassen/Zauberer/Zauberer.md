---
Trefferwürfel: W6
PrimärAttribut: Charisma
Rettungswürfe:
  - Charisma
  - Konstitution
Rüstung:
Waffen:
  - Einfache Waffen
Icon: "[[Wizard_logo.png]]"
---

> [!infobox]
> # Sorcerer
> ![[Sorcerer_logo.png|120]]
> **Trefferwürfel:** 1W6 pro Stufe
> **Primäres Attribut:** Charisma
> **Rettungswürfe:** Konstitution & Charisma
> **Rüstung:** _keine_
> **Waffen:** Einfache Waffen
> **Fähigkeiten:** _Wähle zwei aus:_
> - ArkaneKunde
> - Einschüchtern
> - Motiv erkennen
> - Religion
> - Täuschen
> - Überzeugen

![[z_Assets/classes/Sorcerer/Sorcerer.png]]

# Ein Zauberer werden ... 

## Als Charakter der 1. Stufe 

- Du erhältst alle Merkmale in der Tabelle „Hauptmerkmale des Zauberers“. 
- Du erhältst die Merkmale der 1. Zaubererstufe, die in der Tabelle „Zauberermerkmale“ aufgeführt sind. 
## Anfangsausrüstung
Du beginnst mit der folgenden Ausrüstung, zusätzlich zu den Ausrüstungen, die durch Ihren Hintergrund gewährt werden:
- Speer, zwei Dolche, Arkaner Fokus (Kristall), Gewölbeforscherausrüstungund 28 GM
- 50 GM

## Als Charakter mit Klassenkombination 

- Du erhältst die Trefferpunktewürfel, die in der Tabelle „Hauptmerkmale des Zauberers“ aufgeführt sind. 
- Du erhältst die Merkmale der 1. Zaubererstufe, die in der Tabelle „Zauberermerkmale“ aufgeführt sind. Bestimme deine verfügbaren Zauberplätze anhand der Regeln zu Klassenkombinationen unter „Charaktererstellung“. 

# Klassenmerkmale des Zauberers 
## Unterklassen

```base
views:
  - type: cards
    name: Tabelle
    filters:
      and:
        - file.inFolder("3-Compendium/Klassen/Zauberer/Unterklassen")
        - file.name != "Unterklassen"
    order:
      - file.name
    markers: bullet
    cardSize: 200
    image: note.Icon
    imageAspectRatio: 1
    indentProperties: true

```


## Klassenmerkmale 
Als Zauberer erhältst du auf den angegebenen Zaubererstufen folgende Klassenmerkmale. Diese Merkmale sind in der Tabelle „Zauberermerkmale“ aufgeführt. 

## Klassenmerkmale 

| Stufe | Klassenmerkmale                                                                                                                                          | Übungsbonus | Gelernte Pläne | Magische Gegenstände | Zaubertricks | Vorbereitete Zauber | 1   | 2   | 3   | 4   | 5   |
| ----- | -------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------- | -------------- | -------------------- | ------------ | ------------------- | --- | --- | --- | --- | --- |
| 1     | [[3-Compendium/Klassen/Zauberer/Zauberer#Zauberwirken\|Zauberwirken]], [[3-Compendium/Klassen/Zauberer/Zauberer#Intuitive Zauberei\|Intuitive Zauberei]] | +2          |                |                      | 2            | 2                   | 2   | -   | -   | -   | -   |
| 2     | [[3-Compendium/Klassen/Zauberer/Zauberer#Metamagie\|Metamagie]], [[3-Compendium/Klassen/Zauberer/Zauberer#Quelle der Magie\|Quelle der Magie]]           | +2          | 4              | 2                    | 2            | 3                   | 2   | -   | -   | -   | -   |
| 3     | Zauberer ­Unterklasse                                                                                                                                    | +2          | 4              | 2                    | 2            | 4                   | 3   | -   | -   | -   | -   |
| 4     | [[3-Compendium/Klassen/Zauberer/Zauberer#Attributswerterhöhung\|Attributswerterhöhung]]                                                                  | +2          | 4              | 2                    | 2            | 5                   | 3   | -   | -   | -   | -   |
| 5     | [[3-Compendium/Klassen/Zauberer/Zauberer#Zaubereiauffrischung\|Zaubereiauffrischung]]                                                                    | +3          | 4              | 2                    | 2            | 6                   | 4   | 2   | -   | -   | -   |
| 6     | Unterklassenmerkmal                                                                                                                                      | +3          | 5              | 3                    | 2            | 6                   | 4   | 2   | -   | -   | -   |
| 7     | [[3-Compendium/Klassen/Zauberer/Zauberer#Zauberei-Inkarnat\|Zauberei-Inkarnat]]                                                                          | +3          | 5              | 3                    | 2            | 7                   | 4   | 3   | -   | -   | -   |
| 8     | [[3-Compendium/Klassen/Zauberer/Zauberer#Attributswerterhöhung\|Attributswerterhöhung]]                                                                  | +3          | 5              | 3                    | 2            | 7                   | 4   | 3   | -   | -   | -   |
| 9     | −                                                                                                                                                        | +4          | 5              | 3                    | 2            | 9                   | 4   | 3   | 2   | -   | -   |
| 10    | [[3-Compendium/Klassen/Zauberer/Zauberer#Metamagie\|Metamagie]]                                                                                          | +4          | 6              | 4                    | 3            | 9                   | 4   | 3   | 2   | -   | -   |
| 11    | −                                                                                                                                                        | +4          | 6              | 4                    | 3            | 10                  | 4   | 3   | 3   | -   | -   |
| 12    | [[3-Compendium/Klassen/Zauberer/Zauberer#Attributswerterhöhung\|Attributswerterhöhung]]                                                                  | +4          | 6              | 4                    | 3            | 10                  | 4   | 3   | 3   | -   | -   |
| 13    | −                                                                                                                                                        | +5          | 6              | 4                    | 3            | 11                  | 4   | 3   | 3   | 1   | -   |
| 14    | Unterklassenmerkmal                                                                                                                                      | +5          | 7              | 5                    | 4            | 11                  | 4   | 3   | 3   | 1   | -   |
| 15    | −                                                                                                                                                        | +5          | 7              | 5                    | 4            | 12                  | 4   | 3   | 3   | 2   | -   |
| 16    | [[3-Compendium/Klassen/Zauberer/Zauberer#Attributswerterhöhung\|Attributswerterhöhung]]                                                                  | +5          | 7              | 5                    | 4            | 12                  | 4   | 3   | 3   | 2   | -   |
| 17    | [[3-Compendium/Klassen/Zauberer/Zauberer#Metamagie\|Metamagie]]                                                                                          | +6          | 7              | 5                    | 4            | 14                  | 4   | 3   | 3   | 3   | 1   |
| 18    | Unterklassenmerkmal                                                                                                                                      | +6          | 8              | 6                    | 4            | 14                  | 4   | 3   | 3   | 3   | 1   |
| 19    | [[3-Compendium/Klassen/Zauberer/Zauberer#Epische Gabe\|Epische Gabe]]                                                                                    | +6          | 8              | 6                    | 4            | 15                  | 4   | 3   | 3   | 3   | 2   |
| 20    | [[3-Compendium/Klassen/Zauberer/Zauberer#Arkane Vergöttlichung\|Arkane Vergöttlichung]]                                                                  | +6          | 8              | 6                    | 4            | 15                  | 4   | 3   | 3   | 3   | 2   |


## Stufe 1
### Zauberwirken 

Mithilfe deiner intuitiven Magie kannst du Zauber wirken. Die Regeln zum Zauberwirken findest du unter „Zauber“. Folgende Informationen erklären, wie du diese Regeln mit den Zaubererzaubern verwendest, die in der Zauberliste des Zauberers weiter hinten in dieser Klassenbeschreibung aufgeführt sind. 

**_Zaubertricks:_** Du kennst vier Zaubererzaubertricks deiner Wahl. _Explosion der Zauberei_ , _Licht_ , _Schockgriff_ und _Taschenspielerei_ werden empfohlen. Wann immer du eine Zaubererstufe erhältst, kannst du einen deiner Zaubertricks dieses Merkmals durch einen anderen Zaubererzaubertrick deiner Wahl ersetzen. 

Auf der 4. und 10. Zaubererstufe erlernst du jeweils einen weiteren Zaubererzaubertrick deiner Wahl, wie in der Spalte „Zaubertricks“ der Tabelle „Zauberermerkmale“ dargestellt. 

**_Zauberplätze:_** Die Tabelle „Zauberermerkmale“ zeigt, wie viele Zauberplätze dir zum Wirken deiner Zauber ab dem 1. Grad zur Verfügung stehen. Du erhältst alle verbrauchten Zauberplätze nach einer langen Rast zurück. 

**_Vorbereitete Zauber ab dem 1. Grad:_** Du bereitest die Liste der Zauber ab dem 1. Grad vor, die dir mit diesem Merkmal zur Verfügung stehen. Wähle zu Beginn zwei Zaubererzauber des 1. Grades aus. _Brennende Hände_ und _Magie entdecken_ werden empfohlen. 

Die Anzahl der Zauber auf deiner Liste erhöht sich, wenn du weitere Zaubererstufen erhältst, wie in der Spalte „Vorbereitete Zauber“ der Tabelle „Zauberermerkmale“ dargestellt. Wann immer sich diese Anzahl erhöht, wählst du zusätzliche Zauber‑ erzauber aus, bis die Anzahl von Zaubern auf deiner Liste der Anzahl in der Tabelle „Zauberermerkmale“ entspricht. Der Grad der ausgewählten Zauber muss dem der verfügbaren Zauberplätze entsprechen. Beispiel: Wenn du ein Zauberer der 3. Stufe bist, kann deine Liste vorbereiteter Zauber sechs Zaubererzauber des 1. und 2. Grades in beliebiger Kombination enthalten. 

Wenn ein anderes Zauberermerkmal dir Zauber gibt, die du stets vorbereitet hast, zählen diese Zauber nicht bei der Anzahl von Zaubern, die du mit diesem Merkmal vorbereiten kannst. Ansonsten zählen diese Zauber jedoch als Zaubererzauber für dich. 

**_Deine vorbereiteten Zauber ändern:_** Wann immer du eine Zaubererstufe erhältst, kannst du einen der Zauber auf deiner Liste durch einen anderen Zaubererzauber ersetzen, für den du Zauberplätze hast. 

**_Attribut zum Zauberwirken:_** Dein Attribut zum Wirken der Zaubererzauber ist Charisma. 

**_Zauberfokus:_** Du kannst einen arkanen Fokus als Zauberfokus für deine Zaubererzauber verwenden. 

### Intuitive Zauberei 

Ein Ereignis in deiner Vergangenheit hat sein unauslöschliches Zeichen hinterlassen und dich mit schwelender Magie erfüllt. Als Bonusaktion kannst du diese Magie eine Minute lang entfesseln. Während dieser Dauer erhältst du die folgenden Vorzüge: 

- Der Zauberrettungswurf‑SG deiner Zaubererzauber wird um 1 erhöht. 

- Bei den Angriffswürfen der Zaubererzauber, die du wirkst, bist du im Vorteil. 

Du kannst dieses Merkmal zweimal anwenden und erhältst alle verbrauchten Anwendungen nach einer langen Rast zurück. 
## Stufe 2
### Metamagie 

Deine Magie kommt aus deinem Inneren, daher kannst du deine Zauber nach deinen Wünschen ändern. Du erhältst zwei Metamagie‑Optionen deiner Wahl unter „Metamagie‑Optionen“ weiter hinten in der Beschreibung dieser Klasse. Die ausgewählten Optionen verwendest du, um Zauber, die du wirkst, vorübergehend zu ändern. Zum Verwenden einer Option musst du die jeweils angegebene Anzahl von Zaubereipunkten verbrauchen. 

Du kannst nur eine Metamagie‑Option auf einen Zauber anwenden, den du wirkst, sofern bei der jeweiligen Option nicht anders angegeben. 

Wann immer du eine Zaubererstufe erhältst, kannst du eine der Metamagie‑Optionen durch eine ersetzen, die du noch nicht kennst. Auf der 10. und 17. Zaubererstufe erhältst du jeweils zwei weitere Optionen. 

### Quelle der Magie 

Du kannst die Quelle der Magie nutzen, die du in dir trägst. Diese Quelle wird durch Zaubereipunkte repräsentiert, die eine Vielzahl magischer Effekte ermöglichen. 

Du besitzt 2 Zaubereipunkte und erhältst weitere auf höheren Stufen, wie in der Spalte „Zaubereipunkte“ der Tabelle „Zauberermerkmale“ angegeben. Du kannst nicht mehr Zaubereipunkte besitzen, als für deine Stufe in der Tabelle angegeben sind. Du erhältst alle verbrauchten Zaubereipunkte nach einer langen Rast zurück. 

Du kannst deine Zaubereipunkte verwenden, um die Optionen unten sowie andere Merkmale wie Metamagie einzusetzen, welche diese Punkte nutzen. 

**_Zauberplätze in Zaubereipunkte umwandeln:_** Du kannst einen Zauberplatz verbrauchen, um eine Anzahl von Zaubereipunkten in Höhe des Zauberplatzgrades zu erhalten (keine Aktion erforderlich).  

**_Zauberplätze erschaffen:_** Als Bonusaktion kannst du in deinem Zug unverbrauchte Zaubereipunkte in einen Zauberplatz umwandeln. In der Tabelle „Zauberplätze erschaffen“ sind die Kosten von Zauber‑ plätzen bestimmter Grade sowie die zum Umwandeln erforderliche Zaubererstufe angegeben. Du kannst Zauberplätze des höchstens 5. Grades erzeugen. 

Alle mit diesem Merkmal erschaffenen Zauberplätze verschwinden nach einer langen Rast. 

#### Zauberplätze erschaffen 

|Zauberplatz-|Zaubereipunkte-|Min.|
|---|---|---|
|grad|kosten|Zaubererstufe|
|1|2|2|
|2|3|3|
|3|5|5|
|4|6|7|
|5|7|9|


## Stufe 3
### Zauberer-Unterklasse 

Du erhältst eine Zauberer‑Unterklasse deiner Wahl. Die Unterklasse Drakonische Zauberei wird nach der Beschreibung dieser Klasse erläutert. Unterklassen sind Spezialisierungen, die dir auf bestimmten Zaubererstufen Merkmale gewähren. Du erhältst für den Rest deiner Laufbahn alle Merkmale deiner Unterklasse, die zu deiner aktuellen Zaubererstufe oder den niedrigeren Stufen gehören. 
## Stufe 4
### Attributswerterhöhung 

Du erhältst das Talent Attributswerterhöhung (siehe „Talente“) oder ein anderes Talent deiner Wahl, für das du qualifiziert bist. Du erhältst dieses Merkmal auf der 8., 12. und 16. Zaubererstufe erneut. 
## Stufe 5
### Zaubereiauffrischung 

Verbrauchte Zaubereipunkte erhältst du nach einer kurzen Rast zurück, jedoch höchstens eine Anzahl in Höhe der Hälfte deiner Zaubererstufe (abgerundet). Du kannst dieses Merkmal erst nach einer langen Rast erneut verwenden. 
## Stufe 7
### Zauberei-Inkarnat 

Wenn keine Anwendungen von Intuitive Zauberei mehr übrig sind, kannst du diese dennoch einsetzen. Dazu musst du 2 Zaubereipunkte verbrauchen und zum Aktivieren die Bonusaktion ausführen. 

Außerdem kannst du, wenn dein Merkmal Intuitive Zauberei aktiv ist, bei jedem Zauber, den du wirkst, bis zu zwei deiner Metamagie‑Optionen verwenden. 
## Stufe 19
### Epische Gabe 

Du erhältst ein Epische‑Gabe‑Talent (siehe „Talente“) oder ein anderes Talent deiner Wahl, für das du qualifiziert bist. Gabe des Dimensionsreisens wird empfohlen. 
## Stufe 20
### Arkane Vergöttlichung 

Wenn dein Merkmal Intuitive Zauberei aktiv ist, kannst in jedem deiner Züge eine Metamagie‑Option verwenden, ohne Zaubereipunkte zu verbrauchen. 

# Metamagie-Optionen 

Durch dein Merkmal Metamagie sind folgende Optionen verfügbar. Die Optionen werden in alphabetischer Reihenfolge aufgeführt. 

## Bedachter Zauber 

_Kosten: 1 Zaubereipunkt_ 

Wenn du einen Zauber wirkst, der andere Kreaturen zu einem Rettungswurf zwingt, kannst du einige dieser Kreaturen vor der vollen Stärke des Zaubers schützen. Verbrauche dazu einen Zaubereipunkt und wähle eine Anzahl betroffener Kreaturen bis zur Höhe deines Charismamodifikators aus (mindestens eine Kreatur). Eine ausgewählte Kreatur besteht ihren Rettungswurf gegen den Zauber automatisch und erleidet keinen Schaden, wenn sie normalerweise bei einem erfolgreichen Rettungswurf die Hälfte des Schadens erleiden würde. 

## Beschleunigter Zauber 

_Kosten: 2 Zaubereipunkte_ 

Wirkst du einen Zauber mit einem Zeitaufwand von einer Aktion, so kannst du 2 Zaubereipunkte verbrauchen, um den Zeitaufwand in eine Bonusaktion zu ändern. Du kannst einen Zauber nicht auf diese Art verändern, wenn du im aktuellen Zug bereits einen Zauber des mindestens 1. Grades gewirkt hast. Außerdem kannst du im aktuellen Zug keinen Zauber des mindestens 1. Grades wirken, wenn du bereits einen Zauber auf diese Art verändert hast. 

## Gespiegelter Zauber 

_Kosten: 1 Zaubereipunkt_ 

Wenn du einen Zauber wie _Person bezaubern_ wirkst, der mit einem Zauberplatz eines höheren Grades gewirkt werden kann, um auf eine weitere Kreatur zu zielen, kannst du einen Zaubereipunkt verbrauchen, um den effektiven Grad des Zaubers um 1 zu erhöhen. 

## Konzentrierter Zauber 

_Kosten: 2 Zaubereipunkte_ 

Wenn du einen Zauber wirkst, der Kreaturen zu einem Rettungswurf zwingt, kannst du 2 Zaubereipunkte verbrauchen, damit ein Ziel bei Rettungswürfen gegen den Zauber im Nachteil ist. 

## Mächtiger Zauber 

_Kosten: 1 Zaubereipunkt_ 

Wenn du den Schaden eines Zaubers auswürfelst, kannst du einen Zaubereipunkt verbrauchen, um mit einer Anzahl von Schadenswürfeln bis zur Höhe 
 

deines Charismamodifikators (mindestens einem) erneut zu würfeln. In diesem Fall musst du die neuen Ergebnisse verwenden. 

Du kannst Mächtiger Zauber auch dann einsetzen, wenn du beim Wirken des Zaubers schon eine andere Metamagie‑Option verwendet hast. 

## Subtiler Zauber 

_Kosten: 1 Zaubereipunkt_ 

Wenn du einen Zauber wirkst, kannst du einen Zaubereipunkt verbrauchen, um den Zauber ohne Verbal‑, Gesten‑ oder Materialkomponenten (außer Materialkomponenten, die vom Zauber verbraucht werden oder beim Zauber angegebene Kosten haben) zu wirken. 

## Verlängerter Zauber 

_Kosten: 1 Zaubereipunkt_ 

Wenn du einen Zauber mit einer Wirkungsdauer von mindestens einer Minute wirkst, kannst du einen Zaubereipunkt verbrauchen, um die Dauer des Zaubers zu verdoppeln (höchstens 24 Stunden). 

Wenn dieser Zauber Konzentration erfordert, bist du bei allen Rettungswürfen, die du zum Aufrechterhalten dieser Konzentration ausführst, im Vorteil. 

## Verwandelter Zauber 

_Kosten: 1 Zaubereipunkt_ 

Wenn du einen Zauberspruch mit einer Schadensart aus der folgenden Liste wirkst, kannst du einen Zaubereipunkt verbrauchen, um diese Schadensart in eine der anderen aufgeführten zu ändern: Blitz, Feuer, Gift, Kälte, Säure, Schall. 

## Weitreichender Zauber 

_Kosten: 1 Zaubereipunkt_ 

Wenn du einen Zauber mit einer Reichweite von mindestens 1,5 Metern wirkst, kannst du einen Zaubereipunkt verbrauchen, um die Reichweite des Zaubers zu verdoppeln. Wirkst du einen Zauber mit Berührungsreichweite, so kannst du einen Zaubereipunkt verbrauchen, um die Reichweite auf neun Meter zu erhöhen. 

## Zielsuchzauber 

_Kosten: 1 Zaubereipunkt_ 

Wenn der Angriffswurf eines deiner Zauber misslingt, kannst du einen Zaubereipunkt verbrauchen und erneut mit dem W20 würfeln. In diesem Fall musst du das neue Ergebnis verwenden. 

Du kannst Zielsuchzauber auch dann einsetzen, wenn du beim Wirken des Zaubers schon eine andere Metamagie‑Option verwendet hast. 

# Zauberliste des Zauberers 

In diesem Abschnitt wird die Zauberliste des Zauberers vorgestellt. Die Zauber sind nach Zaubergrad und dann alphabetisch sortiert, und die Schule der Magie der jeweiligen Zauber ist aufgeführt. In der Spalte „Besonderheit“ bedeutet _K_ , dass der Zauber Konzentration erfordert, _R_ bedeutet, dass es sich um ein Ritual handelt, und _M_ bedeutet, dass eine bestimmte Materialkomponente erforderlich ist. 

## Zaubertricks (Zaubererzauber des 0. Grades) 

|Zauber|Schule|Beson-derheit|
|---|---|---|
|_Ausbessern_|Verwandlungsmagie|−|
|_Botschaft_|Verwandlungsmagie|−|
|_Einfache Illusion_|Illusionsmagie|−|
|_Elementalismus_|Verwandlungsmagie|−|
|_Explosion der Zauberei_|Hervorrufungsmagie|−|
|_Feuerpfeil_|Hervorrufungsmagie|−|
|_Gift versprühen_|Nekromantie|−|
|_Kalte Hand_|Nekromantie|−|
|_Kältestrahl_|Hervorrufungsmagie|−|
|_Licht_|Hervorrufungsmagie|−|
|_Magierhand_|Beschwörungsmagie|−|
|_Säurespritzer_|Hervorrufungsmagie|−|
|_Schockgriff_|Hervorrufungsmagie|−|
|_Tanzende Lichter_|Illusionsmagie|K|
|_Taschenspielerei_|Verwandlungsmagie|−|
|_Zielsicherer Schlag_|Erkenntnismagie|−|



## Zaubererzauber des 1. Grades 

|Zauber|Schule|Beson-derheit|
|---|---|---|
|_Brennende Hände_|Hervorrufungsmagie|−|
|_Chromatische Kugel_|Hervorrufungsmagie|M|
|_Donnerwoge_|Hervorrufungsmagie|−|
|_Eismesser_|Beschwörungsmagie|−|
|_Falsches Leben_|Nekromantie|−|
|_Federfall_|Verwandlungsmagie|−|
|_Lautloses Trugbild_|Illusionsmagie|K|
|_Magie entdecken_|Erkenntnismagie|K, R|
|_Magierrüstung_|Bannmagie|−|
|_Magisches Geschoss_|Hervorrufungsmagie|−|
|_Nebelwolke_|Beschwörungsmagie|K|
|_Person bezaubern_|Verzauberungsmagie|−|
|_Rascher Rückzug_|Verwandlungsmagie|K|
|_Schild_|Bannmagie|−|



|Zauber|Schule|Beson-derheit|
|---|---|---|
|_Schlaf_|Verzauberungsmagie|K|
|_Schmieren_|Beschwörungsmagie|−|
|_Selbstverkleidung_|Illusionsmagie|−|
|_Sprachen verstehen_|Erkenntnismagie|R|
|_Springen_|Verwandlungsmagie|−|
|_Sprühende Farben_|Illusionsmagie|−|
|_Strahl der Übelkeit_|Nekromantie|−|



|Zauber|Schule|Beson-derheit|
|---|---|---|
|_Furcht_|Illusionsmagie|K|
|_Gasförmige Gestalt_|Verwandlungsmagie|K|
|_Gegenzauber_|Bannmagie|−|
|_Hast_|Verwandlungsmagie|K|
|_Hellsehen_|Erkenntnismagie|K, M|
|_Hypnotisches Muster_|Illusionsmagie|K|
|_Mächtiges Trugbild_|Illusionsmagie|K|
|_Magie bannen_|Bannmagie|−|
|_Schneesturm_|Beschwörungsmagie|K|
|_Schutz vor Energie_|Bannmagie|K|
|_Stinkende Wolke_|Beschwörungsmagie|K|
|_Tageslicht_|Hervorrufungsmagie|−|
|_Vampirgriff_|Nekromantie|K|
|_Verlangsamen_|Verwandlungsmagie|K|
|_Wasser atmen_|Verwandlungsmagie|R|
|_Wasserwandeln_|Verwandlungsmagie|R|
|_Zungen_|Erkenntnismagie|−|



## Zaubererzauber des 2. Grades 

|Zauber|Schule|Beson-derheit|
|---|---|---|
|_Attribut verbessern_|Verwandlungsmagie|K|
|_Blindheit/Taubheit_|Verwandlungsmagie|−|
|_Drachenodem_|Verwandlungsmagie|K|
|_Dunkelheit_|Hervorrufungsmagie|K|
|_Dunkelsicht_|Verwandlungsmagie|−|
|_Einflüsterung_|Verzauberungsmagie|K|
|_Flammenklinge_|Hervorrufungsmagie|K|
|_Flammenkugel_|Hervorrufungsmagie|K|
|_Gedanken wahrnehmen_|Erkenntnismagie|K|
|_Gestalt verändern_|Verwandlungsmagie|K|
|_Klopfen_|Verwandlungsmagie|−|
|_Magische Waffe_|Verwandlungsmagie|−|
|_Nebelschritt_|Beschwörungsmagie|−|
|_Person festhalten_|Verzauberungsmagie|K|
|_Schweben_|Verwandlungsmagie|K|
|_Sengender Strahl_|Hervorrufungsmagie|−|
|_Spiegelbilder_|Illusionsmagie|−|
|_Spinnenklettern_|Verwandlungsmagie|K|
|_Spinnennetz_|Beschwörungsmagie|K|
|_Unsichtbares sehen_|Erkenntnismagie|−|
|_Unsichtbarkeit_|Illusionsmagie|K|
|_Vergrößern/Verkleinern_|Verwandlungsmagie|K|
|_Verschwimmen_|Illusionsmagie|K|
|_Windstoß_|Hervorrufungsmagie|K|
|_Zerbersten_|Hervorrufungsmagie|−|



## Zaubererzauber des 4. Grades 

|Zauber|Schule|Beson-derheit|
|---|---|---|
|_Ätzkugel_|Hervorrufungsmagie|−|
|_Dimensionstür_|Beschwörungsmagie|−|
|_Dürre_|Nekromantie|−|
|_Eissturm_|Hervorrufungsmagie|−|
|_Feuerschild_|Hervorrufungsmagie|−|
|_Feuerwand_|Hervorrufungsmagie|K|
|_Mächtige Unsichtbarkeit_|Illusionsmagie|K|
|_Monster bezaubern_|Verzauberungsmagie|−|
|_Steinhaut_|Verwandlungsmagie|K, M|
|_Tier beherrschen_|Verzauberungsmagie|K|
|_Verbannung_|Bannmagie|K|
|_Verwandlung_|Verwandlungsmagie|K|
|_Verwirrung_|Verzauberungsmagie|K|



## Zaubererzauber des 5. Grades 

Zaubererzauber des 3. Grades
|Zauber|Schule|Besonderheit|
|---|---|---|
|_Arkane Hand__Äußerlichkeiten_|HervorrufungsmagieIllusionsmagie|K−|
|_Blitz_Hervorrufungsmagie|−|_Erschaffung_|Illusionsmagie|−|
|_Feuerball_Hervorrufungsmagie|−|_Gegenstände beleben_|Verwandlungsmagie|K|
|_Fliegen_Verwandlungsmagie|K|_Insektenplage_|Beschwörungsmagie|K|
|_Flimmern_Verwandlungsmagie|−|_Kältekegel_|Hervorrufungsmagie|−|



## Zaubererzauber des 3. Grades 

**90** Systemreferenzdokument 5.2.1 

|Zauber|Schule|Beson-derheit|
|---|---|---|
|_Kreis der Teleportation_|Beschwörungsmagie|M|
|_Monster festhalten_|Verzauberungsmagie|K|
|_Person beherrschen_|Verzauberungsmagie|K|
|_Steinwand_|Hervorrufungsmagie|K|
|_Telekinese_|Verwandlungsmagie|K|
|_Todeswolke_|Beschwörungsmagie|K|



## Zaubererzauber des 6. Grades 

|Zauber|Schule|Beson-derheit|
|---|---|---|
|_Auflösung_|Verwandlungsmagie|−|
|_Böser Blick_|Nekromantie|K|
|_Erde bewegen_|Verwandlungsmagie|K|
|_Fleisch zu Stein_|Verwandlungsmagie|K|
|_Frostsphäre_|Hervorrufungsmagie|−|
|_Kettenblitz_|Hervorrufungsmagie|−|
|_Kugel der_|Bannmagie|K|
|_Unverwundbarkeit_|||
|_Massen-Einflüsterung_|Verzauberungsmagie|−|
|_Sonnenstrahl_|Hervorrufungsmagie|K|
|_Todeskreis_|Nekromantie|M|
|_Wahrer Blick_|Erkenntnismagie|M|



## Zaubererzauber des 7. Grades 

|Zauber|Schule|Beson-derheit|
|---|---|---|
|_Ätherische Gestalten_|Beschwörungsmagie|−|
|_Ebenenwechsel_|Beschwörungsmagie|M|
|_Feuersturm_|Hervorrufungsmagie|−|
|_Finger des Todes_|Nekromantie|−|
|_Regenbogenspiel_|Hervorrufungsmagie|−|
|_Schwerkraft umkehren_|Verwandlungsmagie|K|
|_Spätzündender Feuerball_|Hervorrufungsmagie|K|
|_Teleportieren_|Beschwörungsmagie|−|



## Zaubererzauber des 8. Grades 

|Zauber|Schule|Beson-derheit|
|---|---|---|
|_Erdbeben_|Verwandlungsmagie|K|
|_Flammende Wolke_|Beschwörungsmagie|K|
|_Halbebene_|Beschwörungsmagie|−|
|_Monster beherrschen_|Verzauberungsmagie|K|
|_Sonnenfeuer_|Hervorrufungsmagie|−|
|_Wort der Macht:_|Verzauberungsmagie|−|
|_Betäubung_|||



## Zaubererzauber des 9. Grades 

|Zauber|Schule|Beson-derheit|
|---|---|---|
|_Meteoritenschwarm_|Hervorrufungsmagie|−|
|_Tor_|Beschwörungsmagie|K, M|
|_Wort der Macht: Tod_|Verzauberungsmagie|−|
|_Wunsch_|Beschwörungsmagie|−|
|_Zeitstopp_|Verwandlungsmagie|−|


