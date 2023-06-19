# LA1600
# Projekt-Dokumentation

Lime : Lucena, Tuma, Spycher, Willi

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
| 09.05.2023| 0.0.1   | Kapitel 1-3 ausgefüllt |
| 16.05.2023| 0.0.2   | Taskbar und Startseite erstellt. |
| 23.05.2023| 0.0.3   | Gesamte Seite haben wir in die 4 Unterseiten Trainer, Tradition, Angebote und Training erstellt und selbstständig jeweils eine bearbeitet.| 
| 30.05.2023| 1.0.1   | Wir haben die User Stories mit den gestelten Anforderungen erweiter und diese dann sofort versucht umzusetzten.|
| 06.06.2023| 1.0.2   |Wir haben die User Stories 15-18 weiter bearbeitet. | 
| 13.06.2023| 1.0.3   | Wir haben die User <stories 15-18 fertig bearbeitet und alles zusammengefügt.|

## 1 Informieren

### 1.1 Ihr Projekt

Wie erstellen eine Website über den Kampfsportverein Nippon Training.

Wir möchten eine Website erstellen, welche die Angebote, Preise und sonstige von dem Verein Nippon Training aufführt. Wir hoffen hierbei die Grundlagen von CSS besser kennenzulernen.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    | Muss            |Funktional| Als User möchte ich, wenn ich den Link öffne auf die Startseite gelangen. |
| 2    | Muss            |Funktional| Als User möchte ich, dass die verschiedenen Kategorien in einer Taskbar aufgelistet sind.|
| 3    | Kann            |Qualität  | Als User möchte ich, dass ich auf der Webseite mehr über die Tradition erfahren.|
| 4    | Kann            |Qualität  | Als User möchte ich, dass es eine Kategorie Wettkampfregeln gibt, damit sich Wettkämpfer und Eltern über die Regeln informieren könenn.|
| 5    | Muss            |Funktional| Als User mächte ich, genauere Infors zu dem Dojo in Urdorf erfahren.|
| 6    | Muss            |Funktional| Als User möchte ich, genauere Infos zu dem Dojo in Dietikon erfahren.|
| 7    | Kann            |Qualität  | Als User möchte ich, dass ich auf der Webseite erfahre, warum ich genau zu diesem Verein gehen soll.|
| 8    | Muss            |Funktional| Als User möchte ich, mehr über die Coaches erfahren.|
| 9    | Muss            |Funktional| Als User möchte ich, die verschiedenen Angebote des Clubs erfahren. |
| 10   | Muss            |Funktional| Als User möchte ich, die Kontaktdaten auf der Website wiederfinden.| 
| 11   | Kann            |Qualität  | Als  User möchte ich einen Home Button um direkt auf die Startseite zu gelangen.|
| 12   | Kann            |Qualität  | Als User möchte ich, verschiedene Optionen für den Farbhintergrund haben.| 
| 13   | Muss            |Funktional| Als User möchte ich, dass Preis und Kurse unter den Angeboten wiederzufinden sind.| 
| 14   | Kann            | Qualität | Als User möchte ich, dass beim Wettkampfreglement in Kata und Kumite unterschieden wird.| 
| 15   | Muss            | Qualität | Als Benutzer möchte ich, dass die verschieden Trainer mit einem Bild dargestellt werden, welches sich verändert, wenn ich darüber hovere. |
| 16   | Muss            | Qualität | Als Benutzer möchte ich, dass das Hamburger-Menu mir nur auf einem kleinen Bildschirm angezeigt wird|
| 17   | Muss            | Qualität|  Als interessierter Konsument möchte ich eine Tabelle sehen, auf welcher ich verschiedene Abos vergleichen kann. Diese sollte sich so verhalten, dass die Zeile, über die ich gerade hovere, besonders hervorgehoben wird.
| 18   | Muss            | Qualität |  Als Benutzer möchte ich auf der Startseite einige motivierende Bilder sehen, welche automatisch wechseln ("carousel").|


✍️ Jede User Story hat eine ganzzahlige Nummer (1, 2, 3 etc.), eine Verbindlichkeit (Muss oder Kann?), und einen Typ (Funktional, Qualität, Rand). Die User Story selber hat folgende Form: *Als ein 🤷‍♂️ möchte ich 🤷‍♂️, damit 🤷‍♂️*.

### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  | Link erhalten, Browser geöffnet|Link in Taskleiste, Enter gedrückt| Website öffnet sich, Startseite wird angezeigt|
| 2.1  | Startseite ist geöffnet| Klick auf das Taskbarzeichen |Die Leiste öffnet sich.|
| 3.1  | Taskleiste ist geöffnet| Klick auf Tradition| Text über Tradition wird angezeigt.|
| 4.1  | Taskleiste ist geöffnet| Klick auf Wettkampfreglement| Wahl für Kumite oder Kata Regeln wird angezeigt.| 
| 5.1  | Taskleiste ist geöffnet| Klick auf Dojo Urdorf| Informationen zum Dojo Urdorf werden angezeigt.| 
| 6.1  | Taskleiste ist geöffnet| Klick auf Dojo Dietikon| Information zum Dojo Dietikon werden angezeigt.|
| 7.1  | Taskleiste ist geöffnet| Klick auf Warum Nippon Training| Argumente für Nippon Training erscheinen.| 
| 8.1  | Taskleiste ist geöffnet| Klick auf Coaches | Coaches erscheinen.|
| 9.1  | Taskleiste ist geöffnet| Klick auf Angebote| Wahl für Preise und Kurse wird angezeigt.| 
| 10.1 | Taskleiste ist geöffnet| Klick auf Kontakt | Kontaktdaten erscheinen.| 
| 11.1 | Wettkampfreglement ist geöffnet| Klick auf Homebutton| Startseite erscheint.| 
| 12.1| Button zum Frabwechseln öffnen| Farbe rot auswählen| Hintergrund wird rot|
| 12.2 | Button zum Frabwechseln öffnen| Farbe schwarz auswählen| Hintergrund wird schwarz| 
| 12.3 | Button zum Frabwechseln öffnen| Farbe weiss auswählen| Hintergrund wird weiss.| 
| 13.1 | Wahl für Kurse oder Preis wird angezeigt| Preis auswählen| Preise werden angezeigt.| 
| 13.2 | Wahl für Kurse oder Preis wird angezeig| Kurse auswählen| Kurse werden angezeigt. | 
| 14.1 | Wahl für Kata oder Kumite wird angezeigt| Kata auswählen| Kataregeln werden angezeigt.|
| 14.2 | Wahl für Kata oder Kumite wird angezeigt| Kumite auswählen| Kumiteregeln werden angezeigt.|
| 15.1 | Startseite ist geöffnet| Feld Personen in der Taskbar auswählen| Alle Trainer werden mit Foto angezeigt|
| 15.2| Seite der Trainer ist geöffnet| Mauszeiger auf ein Bild eines Trainers| Bild wird grösser| 
| 16.1|Startseite ist geöffnet| Umstellem auf kleinen Bildschirm| Hamburger-Menu wird angezeigt|
|16.2 | Seite ist auf kleinem Bildschirm geöffnet| Umstellen auf grossen Bildschirm| Normales Menu erscheint|
| 17.1| Menu ist geöffnet| Angebote auswählen| Angebote erscheinen in einer Tabelle|
| 17.2| Seite mit den Angeboten ist geöffnet| Über eine Zeile mit Preisen hovern| Zeile wird hervorgehoben| 
| 18.1| Link in Taskleiste eingeben| Startseite öffnen| Bilder werden abwechselnd gezeigt| 


### 1.4 Diagramme
![50e1bcba-35b0-4801-9762-958636b5b41f](https://user-images.githubusercontent.com/110892622/237055123-75021b37-bb13-490d-9b7d-bc9e6ec4101b.jpg)
![485ee20e-b9e4-4253-b846-2e4bd3bb46c8](https://user-images.githubusercontent.com/110892622/237055134-8a98a857-bb2c-4d22-baac-add68d8d5ab7.jpg)


## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  |23.05.2023| Cedric Tuma| Programmieren und Design der Startseite|1|
| 2.A  |23.05.2023| Samuel Lucena|  Erstellen Dropdown |      1        |
| 2.B  | 23.05.2023| Elias Spycher| Design Dropdown| 1|
| 3.A  |23.05.2023| Rebecca Willi| Erstellen und programmierem Button Tradition|1|
| 3.B  |23.05.2023 |Rebecca Willi| Erstellen und Design Websitenteil Tradition|1|
| 4.A  |23.05.2023 |Rebecca Willi| Erstellen und programmieren Button Wettkampfreglement|1|
| 5.A  |23.05.2023|Elias Spycher| Erstellen und programmieren Button Dojo Urdorf|1|
| 5.B  |23.05.2023 | Elias Spycher| Erstellen und Design Webseitenteil Dojo Urdorf|1|
| 6.A  |23.05.2023 | Cedric Tuma | Erstellen und programmieren Button Dojo Dietikon|1| 
| 6.B |23.05.2023 |Cedric Tuma | Erstellen und Design Webseitenteil Dojo Dietikon|1|
| 8.A |23.05.2023 |Samuel Lucena| Erstellen und programmieren Button Coaches|1|
| 8.B |23.05.2023| Samuel Lucena| Erstellen und Design Webseitenteil Coaches|1|
| 7.A |23.05.2023| Elias Spycher| Erstellen und programmieren Button Warum Nippon?|1|
| 7.B |23.05.2023| Elias Spycher| Erstellen und Design Webseitenteil Warum Nippon?|1|
| 9.A |23.05.2023| Cedric Tuma | Erstellen und programmieren Button Angebot|1|
| 10.A|23.05.2023| Samuel Lucena| Erstellen und programmieren Button Kontakt|1|
| 10.B|23.05.2023| Samuel Lucena| Erstellen und Design Webseitenteil Kontakt|1|
| 11.A|30.05.2023| Elias Spycher| Erstellen und programmiernen Homebutton|1|
| 12.A|30.05.2023| Cedric Tuma | Erstellen und programmieren Button Hintergrund|1|
| 12.B|30.05.2023| Cedric Tuma | Erstellen und programmieren Farbhintergrund rot|1|
|12.C|30.05.2023| Cedric Tuma | Erstellen und programmieren Farbhintergrund weiss|1|
| 12.D|30.05.2023| Cedric Tuma| Erstellen und Programmieren Farbhintergrund scwarz|1|
| 13.A|30.05.2023| Samuel Lucena| Button zur Wahl zwischen Preis und Kurse erstellen|1|
| 13.B|30.05.2023| Samuel Lucena| Erstellen und Design für Webseitenteil Preis |1|
| 13.C|30.05.2023| Samuel Lucena| Filter für Preis für jeweilige Zeitdauer erstellen|1|
| 13.D|30.05.2023|Elias Spycher | Erstellen Button zur Wahl zwischen Kids und Erwachsenen Kurse|1|
| 13.E|30.05.2023| Elias Spycher| Erstellen und Design Webseitenteil Kids Kurse|1|
| 13.F|30.05.2023| Elias Spycher| Erstellen Filter Kursschwierigkeit Kids Kurse|1|
| 13.G|30.05.2023| Rebecca Willi| Erstellen und Design Erwachsenen Kurse|1|
| 14.A|30.05.2023| Rebecca Willi| Erstellen Button Wahl Kumite Kata|1|
| 14.B|30.05.2023| Rebecca Willi| Filter für Alterskategorein Kumite und Kata erstellen|1|
| 14.C|30.05.2023|Rebecca Willi| Erstellen und Design Webseitenteil Reglement Kumite|1|
| 14.D|30.05.2023| Rebecca Willi| Erstellen und Design Webseitenteil Reglement Kata|1|
| 15.A|13.06.2023| Samuel Lucena| Bilder zu den jeweiligen Trainer einfügen| 1|
| 15.B|13.06.2023| Samuel Lucena| Programmieren des vergrössern der Bilder beim drüber hovern.| 1|
| 16.A|13.06.2023| Cedric Tuma  | Programmieren Hamburger-Menu für kleine Bildschirme| 1| 
| 16.B|13.06.2023| Cedric Tuma  | Programmieren Menu für grosse Bildschirme| 1|
|17.A |13.06.2023|Rebecca Willi | Programmieren des hervorhebens bei der Tabelle|1|
|18.A| 13.06.2023| Elias Spycher| Programmieren "carousel" auf Startseite|1|


Total: 39x 1 = 39x 45Min



## 3 Entscheiden

Informationen zu Dojo und Kontaktdaten sind im Footer.
Arbeitspaket: 5 Footer für Dojo Infos und Kontaktdaten programmieren.
Arbeitspaket 6+ 10 gestrichen.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A | 16.05.2023| Elias Spycher|1|2|
| 2.A| 16.05.2023| Elias Spycher| 1| 3| 
| 2.B| 23.05.2023| Elias Spycher| 1| 3|
|3.A| 23.05.2023| Elias Spycher| 1|1|
|3.B| 23.05.2023| Elias Spycher| 1| 2|
|5.A| 12.06.2023| Rebecca Willi| 1|2|
|8.A| 16.05.2023| Samuel Lucena|1|1
|8.B | 16.05.2023  | Samuel Lucena  |   1      |     2      |
|9.A| 16.05.2023| Rebecca Willi| 1|1|
| 13.B  |16.05.2023 |Rebecca Willi| 1 | 3 |
|13.D| 23.05.2023| Cedric Tuma| 1| 3|
|13.E| 30.052023| Cedric Tuma| 1|3|
|14.A| 23.05.2023| Rebecca Willi| 1|2|
|14.C| 23.05.2023| Rebecca Willi| 1| 3|
|14.D| 30.05.2023| Rebecca Willi| 1|3|
|15.A| 30.05.2023| Samuel Lucena|1|1|
|16.A|06.06.2023| Cedric Tuma| 1|2| 
|17.A|30.05.2023/06.06.2023|Rebecca Willi| 1| 3 |
|18.A|06.06.2023/12.06.2023| Elias Spycher|1|2




## 5 Kontrollieren

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1.1  | 19.06.2023| OK  |   Rebecca Willi     |
| 1.1.2 | 19.06.2023|  OK      |Rebecca Willi|
|2.1.1| 19.06.2023 | NOK(Hamburgermenu immer angezeigt| Rebecca Willi|
|2.1.2| 19.06.2023 | NOK(")| Rebecca Willi| 
| 3.1.1| 19.06.2023| OK| Rebecca Willi| 
|3.1.2| 19.06.2023 | OK | Rebecca Willi|
|4.1| 19.06.2023| Nicht bearbeitet| Rebecca Willi| 
|5.1.1| 19.06.2023| OK| Rebecca Willi|
|5.1.2| 19.06.2023| OK| Rebecca Willi|
|7.1.1| 19.06.2023| Nicht bearbeitet| Rebecca Willi| 
|8.1.1| 19.06.2023| OK| Rebecca Willi| 
|8.1.2| 19.06.2023| OK| Rebecca Willi| 
|9.1.1| 19.06.2023|OK | Rebecca Willi| 
|9.1.2| 19.06.2023| OK | Rebecca Willi|
|10.1| 19.06.2023 | Nicht bearbeitet|Rebecca Willi|
|11.1| 19.06.2023| Nicht bearbeitet| Rebecca Willi|
|12.1| 19.06.2023| Nicht bearbeitet| Rebecca Willi|
|13.1.1| 19.06.2023|NOK (Preise und Kurse unterschidlicher Button im Burgermenu)| Rebecca Willi|
|13.1.2| 19.06.2023|NOK (")| Rebecca Willi|
|13.2.1| 19.06.2023| NOK (")| Rebecca Willi|
|13.2.2| 19.06.2023||NOK (")| Rebecca Willi| 
| 14.1| 19.06.2023| Nicht in fertiges Produkt miteinbezogen.| Rebecca Willi|
| 14.2| 19.06.2023| "| Rebecca Willi|
|15.1.1| 19.06.2023| | Rebecca Willi|
|15.1.2| 19.06.2023| | Rebecca Willi|
|15.2.1|19.06.2023| | Rebecca Willi|
|16.1.1| 19.06.2023|OK|Rebecca Willi|
|16.1.2| 19.06.2023|OK| Rebecca Willi| 
|16.2 | 19.06.2023| Nicht bearbeitet| Rebecca Willi|
| 17.1.1| 19.06.2023| OK| Rebecca Willi|
| 17.1.2| 19.06.2023| OK| Rebecca Willi|
|17.2.1| 19.06.2023| OK | Rebecca Willi|
| 17.2.2| 19.06.2023| OK| Rebecca Willi|
| 18.1.1| 19.06.2023| OK| Rebecca Willi| 
| 18.1.2|19.06.2023| OK| Rebecca Willi|





Getestet mit Edge und Chrome.

Die Webseite erfüllt ihren Zweck. Jedoch gibt es zwischendurch Fehler welche jedoch keine schwierigkeiten darstellen beim Benutzen der Webseite. 

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
