# W901
Grundlagen des Linux / Unix Betriebsystems kennenlernen

![](images/cover.jpg)

## Administratives

Das Modul wird regulär benotet. „Die Zeugnisnoten widerspiegeln den individuellen Leistungsstand in einem Fach, so objektiv und absolut wie möglich. Der Zeugnisnote sollten pro Fach mindestens drei voneinander unabhängige Notenwerte zugrunde liegen und auch dokumentiert sein (schriftliche Prüfungen, Kriterienraster, Protokolle etc.).“ siehe orgweb: http://orgweb.tbz.ch/handbuch/berufliche-grundbildung/23-unterrichtsdurchfuehrung.aspx

Es gilt die Anwesenheitspflicht von 80%. Bei zu vielen Absenzen folgt ein Gespräch mit dem Lehrbetrieb. Bitte beachten, dass Abwesenheiten wegen ÜK’ s nicht gezählt werden. Der ÜK Besuch geht vor.

Das Modul erscheint im Zeugnis unten rechts unter „zusätzlich besuchte Module“. Die Note zählt NICHT zum Qualifikationsverfahren.

## Modulinhalt

Der Kursinhalt ist, je nach Vorwissen, an folgenden LPI Examen ausgerichtet:

| LPI Beschreibung | Modul Unterlagen | Beispiel |
|------------------|------------------|----------|
| [Linux Essentials Exam 010](https://www.lpi.org/our-certifications/exam-010-objectives) | [E010](https://github.com/w901-fr19-mi/E010) | [myE010](https://github.com/w901-fr19-mi/myE010) |
| [Exam 701: DevOps Tools Engineer](https://www.lpi.org/our-certifications/exam-701-objectives) | [E701](https://github.com/w901-fr19-mi/E701) | [myE701](https://github.com/w901-fr19-mi/myE701) |

und kann von jedem Lehrenden, individuell mit seinem Wissenstand abgestimmt werden.

Beispiele wie ein Fahrplan und die Dokumention des Lern- und Entwicklungsprozesses aussehen kann, siehe Spalte Beispiele. Diese Beispiele können für die Erstellung der eigenen Dokumentation mittels `fork` (siehe Beispieldokumentation) kopiert werden.

## Auftrag

Als Lernprodukt wird

* **eine Dokumention des Lern- und Entwicklungsprozesses mit Ausgesuchten Unterkapiteln aus einem oder beiden LPI Examen** 

erwartet. 

Die Unterkapitel hat sich der Lehrnende, am Anfang des Moduls, selber als Fahrplan zusammenzustellen.

Beispiel: Exam 010

| Datum | behandelte Unterrichtsinhalte: | Gewichtung |
| -------- | ------ | ---------- |
| 15.05.19 | 1.1 Linux Evolution and Popular Operating Systems<br>1.3 Open Source Software and Licensing | 2 + 2 |
| 22.05.19 | 2.1 Command Line Basics<br>2.3 Using Directories and Listing Files<br>2.4 Creating, Moving and Deleting Files  | 2 + 3 + 2 |
| 29.05.19 | 3.2 Searching and Extracting Data from Files<br>3.3 Turning Commands into a Script | 3 + 4 | 
...
|          | Total Punkte | mindestens 24 |
etc.

Das Datum für die LB1 (26.06.19) ist fix und kann nicht verschoben werden.

Die Dokumentation des Lern- und Entwicklungsprozesses hat folgenden Aufbau:

### Kapitel: 2.1 Command Line Basics (Status: Entwurf | in Arbeit | Abgeschlossen)

**Weight**: 3 (Wert aus Exam 010)

**Beschreibung** des Unterkapitels, z.B. Basiswissen um mit der Kommandozeile von Linux zu arbeiten.

**Tagesziele**, z.B. Aufbau des Wissen über die Shell. 

**Vorgehen**, z.B. Installation einer Ubuntu Linux Umgebung. Durcharbeiten ...., Dokumentation der einzelnen Befehle in ...

**Beispiele und Arbeitsergebnisse**

* Starten der Shell: bash bzw. Einloggen.
* Einfache 'mein Befehl' lösen Variablen nicht auf.
* Doppelte " lösen Variablen auf.

**Fazit und Aussicht**, z.B. Die Durcharbeitung von ... gab mir einen Einblick in die Shell. Das nächste Mal will ich diese im Kapitel ... vertiefen.

## LBs

### LB1 - Theoretische Prüfung (Gewichtung 40 %)

Es sind insgesamt 12 Fragen.

Hilfsmittel 1 A4 Blatt mit eigenen Notizen (keine Kopie)

Prüfungsthemen: 
* Standard Linux Befehle und deren Funktion, z.B. `tar`, `ps`, ...
* Eigenschaften von Linux, z.B. alles ist eine D..., besteht aus kl...en Programmen, ...
* Fragen zu Open Source Lizenzen, z.B. GPL ist ein Copy... Lizenz

Zu jeder Frage gibt es drei Antwortmöglichkeiten, eine ist richtig.

## LB2 - Dokumention des Lern- und Entwicklungsprozesses (60 %)

Die Anzahl erarbeitete Kapitel und deren Gewichtung (**Weight:**) bestimmen die LB2 Punkte und damit die Note.

Um die volle Punktzahl eines Kapitels zu erlangen, wird eine Aufstellung, wie oben aufgezeigt, erwartet.

Die Gewichtung (Punktzahl) eines Kapitels kann erhöht werden, durch folgende Eigenschaften der Umsetzung:
* Kreativität
* Komplexität
* Umfang
* Umsetzung eigener Ideen

Die Dokumention des Lern- und Entwicklungsprozesses wird pro Abgegebenem Kapitel bewertet und erfolgt jedesmal wenn ein Lehrender ein Kapitel als "Abgeschlossen" einträgt.

Die Dokumentation erfolgt auf "github.com" in Form eines eigenes Projektes. Dazu wird eines der zwei Beispielprojekte mittels `fork` kopiert.
