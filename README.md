### 👉 Alle Arbeiten auf einer Seite: **[ralphwystup.github.io](https://ralphwystup.github.io/)**

Lehr- und Laborarbeiten zur Elektrotechnik: jede als eigenes Repositorium, jede mit einem
Manuskript, das die Herleitung geschlossen zeigt, und mit einer Seite, die im Browser rechnet.
Die Seiten laufen ohne Netz, ohne Installation und ohne Anmeldung — ein Klick auf „Seite", und
man kann die Schieber selbst bewegen.

Alle Arbeiten entstanden mit KI und Agent (Claude Code, Anthropic).

## Regelung und Mechatronik

| Arbeit | Worum es geht | |
|:--|:--|:--|
| **Segway-Regelung mit ESP32 und Schrittmotoren** | Das inverse Pendel: Strecke hergeleitet, Regler in vier Schichten ausgelegt, Laborversuch mit bewegtem Modell | [Seite](https://ralphwystup.github.io/Segway-Regelung-mit-ESP32-und-Schrittmotoren/) · [Code](https://github.com/RalphWystup/Segway-Regelung-mit-ESP32-und-Schrittmotoren) |
| **Wasserstandsregelung mit optischer Füllhöhenerkennung** | Eine Kamera misst die Füllhöhe, ein PI-Regler hält sie: Bildauswertung, Streckenmodell, geschlossener Kreis | [Seite](https://ralphwystup.github.io/Wasserstandsregelung-mit-optischer-Fuellhoehenerkennung/) · [Code](https://github.com/RalphWystup/Wasserstandsregelung-mit-optischer-Fuellhoehenerkennung) |

## Elektrische Maschinen und Felder

| Arbeit | Worum es geht | |
|:--|:--|:--|
| **Induktivitäten einer PMSM aus der Geometrie berechnen** | Eine Maschine hat je Achse zwei Induktivitäten, und sie sind verschieden. Wer die falsche nimmt, rechnet bei Sättigung um Faktoren daneben | [Seite](https://ralphwystup.github.io/Induktivit-ten-einer-PMSM-aus-Geometrie-berechnen/) · [Code](https://github.com/RalphWystup/Induktivit-ten-einer-PMSM-aus-Geometrie-berechnen) |
| **Elektromagnetische Feldsimulation** | Eine zweidimensionale Feldgleichung mit einer gewöhnlichen Netzwerkberechnung lösen: vom Gebiet zur Netzliste und zurück | [Seite](https://ralphwystup.github.io/Elektromagnetische-Feldsimulation/) · [Code](https://github.com/RalphWystup/Elektromagnetische-Feldsimulation) |

## Schaltungen und Bauelemente

| Arbeit | Worum es geht | |
|:--|:--|:--|
| **Schaltungssimulation nichtlinearer Differentialgleichungssysteme** | Erweiterte Knotenanalyse, Newton-Raphson und Euler am Beispiel der B4-Brücke mit belastetem RC-Glied | [Seite](https://ralphwystup.github.io/Schaltungssimulation-von-nichtlinearen-Differentialgleichungssystemen/) · [Code](https://github.com/RalphWystup/Schaltungssimulation-von-nichtlinearen-Differentialgleichungssystemen) |
| **Transistoren, der Transistortester und die daraus erzeugten Modelle** | Von der Messung zum eigenen Berechnungsverfahren: Kennlinien messen, Gummel-Poon-Parameter bestimmen, und mit einem eigenen Löser ganze Schaltungen rechnen | [Seite](https://ralphwystup.github.io/Transistoren-Transistortester-und-daraus-erzeugte-Modelle/) · [Code](https://github.com/RalphWystup/Transistoren-Transistortester-und-daraus-erzeugte-Modelle) |
| **Kennlinienschreiber für Transistoren** | Ein selbstgebauter Messplatz nimmt Kennlinienfelder auf: zwei Digital-Analog-Umsetzer, vier Analog-Digital-Umsetzer, eine Kaskade aus zwei Reglern | [Seite](https://ralphwystup.github.io/Kennlinienschreiber-fuer-Transistoren-mit-ESP32-und-BJT-Modell/) · [Code](https://github.com/RalphWystup/Kennlinienschreiber-fuer-Transistoren-mit-ESP32-und-BJT-Modell) |

## Messen mit Kamera und Sensor

| Arbeit | Worum es geht | |
|:--|:--|:--|
| **Tomatenwächter** | Wann muss gegossen werden? Eine Kamera erkennt hängende Blätter am Excess-Green-Index, ein Raspberry Pi entscheidet | [Seite](https://ralphwystup.github.io/Tomatenwaechter-Bildgestuetzte-Welkeerkennung-mit-ESP32-CAM-und-Raspberry-Pi/) · [Code](https://github.com/RalphWystup/Tomatenwaechter-Bildgestuetzte-Welkeerkennung-mit-ESP32-CAM-und-Raspberry-Pi) |
| **Wärmebild-Fusion mit ESP32-CAM und AMG8833** | Kamerabild und Wärmebild deckungsgleich übereinander, mit 64 Thermoelementen und der Parallaxe zweier Augen | [Seite](https://ralphwystup.github.io/Waermebild-Fusion-mit-ESP32-CAM-und-AMG8833/) · [Code](https://github.com/RalphWystup/Waermebild-Fusion-mit-ESP32-CAM-und-AMG8833) |
| **Automatisch gesteuertes Lichtmikroskop mit KI** | Aufbau, Algorithmen, Fernwartung und ein KI-Fenster — eine Laborstation für Studierende | [Seite](https://ralphwystup.github.io/Automatisch-gesteuertes-Lichtmikroskop-mit-KI/) · [Code](https://github.com/RalphWystup/Automatisch-gesteuertes-Lichtmikroskop-mit-KI) |
| **Mikroskop-Autofokus mit Servo am Raspberry Pi 5** | Ein USB-Mikroskop wird von einem Servo über ein Zahnradpaar scharf gestellt. Hardware-PWM gegen das Zittern, 4,6° Getriebespiel immer von unten angefahren, der Gipfel als Parabel bestimmt | [Seite](https://ralphwystup.github.io/Mikroskop-Autofokus-mit-Servo-am-Raspberry-Pi-5/) · [Code](https://github.com/RalphWystup/Mikroskop-Autofokus-mit-Servo-am-Raspberry-Pi-5) |
| **Salzkrebszucht überwachen: Raspberry Pi 5 und Jetson mit YOLO** | Eine Artemia-Zucht unter dem Mikroskop: der Pi hält scharf, zeigt und verfolgt, der Jetson lernt aus von Hand bewerteten Bildern ein YOLOv8-Modell und zählt mit. Mit Lernseite, Livebild mit Rahmen und Lernkurve | [Seite](https://ralphwystup.github.io/Salzkrebszucht-ueberwachen-Mikroskopkamera-mit-motorischem-Autofokus-Raspberry-Pi-5-und-Jetson-YOLO/) · [Code](https://github.com/RalphWystup/Salzkrebszucht-ueberwachen-Mikroskopkamera-mit-motorischem-Autofokus-Raspberry-Pi-5-und-Jetson-YOLO) |
| **Analoganzeige optisch lesen** | Ein Zeigerinstrument ablesen, ohne es zu verändern: Skala und Zeiger werden in jedem Bild neu gefunden, ohne festen Drehpunkt und ohne Einlernen | [Seite](https://ralphwystup.github.io/Analoganzeige-optisch-lesen-mit-ESP32-S3/) · [Code](https://github.com/RalphWystup/Analoganzeige-optisch-lesen-mit-ESP32-S3) |

## Signale und Diagnose

| Arbeit | Worum es geht | |
|:--|:--|:--|
| **Akustische Rohrdiagnose mit einem dynamischen Netzwerkzwilling** | Von der Impulsantwort zur Erkennung von Seitenrohr und Belag, mit einer überlagerten lernenden Ebene | [Seite](https://ralphwystup.github.io/Akustische-Rohrdiagnose-mit-einem-dynamischen-Netzwerkzwilling/) · [Code](https://github.com/RalphWystup/Akustische-Rohrdiagnose-mit-einem-dynamischen-Netzwerkzwilling) |
| **Die Telegraphengleichung: vom Feld zum Impuls auf der Leitung** | Von den Maxwellschen Gleichungen zur Wellengleichung und vom Ersatzschaltbild zum Impuls, der auf der Leitung läuft, sich spiegelt und überlagert — mit Laborversuch | [Seite](https://ralphwystup.github.io/Telegraphengleichung-Impuls-auf-der-Leitung/) · [Code](https://github.com/RalphWystup/Telegraphengleichung-Impuls-auf-der-Leitung) |
| **Feldbustechnologie: Modbus RTU am praktischen Beispiel** | Ein Feldbusmodul von der ersten Frage an — unter welcher Adresse antwortet es? — bis zum laufenden Betrieb: Register lesen und schreiben, Prüfsumme, Zeitverhalten | [Seite](https://ralphwystup.github.io/Feldbustechnologie-Modbus-RTU/) · [Code](https://github.com/RalphWystup/Feldbustechnologie-Modbus-RTU) |
| **Wetter-Fernschreiber Siemens T68d** | Der Wetterbericht auf einem Streifenschreiber von 1959: RTTY und ITA2 bei 50 Baud. Die Seite druckt das wirkliche Wetter für einen Ort, den man eingibt | [Seite](https://ralphwystup.github.io/Wetter-Fernschreiber-Siemens-T68d-RTTY-und-ITA2-mit-ESP32/) · [Code](https://github.com/RalphWystup/Wetter-Fernschreiber-Siemens-T68d-RTTY-und-ITA2-mit-ESP32) |

## Methode und Erkenntnis

| Arbeit | Worum es geht | |
|:--|:--|:--|
| **Wie eine KI lokale Hard- und Software steuert** | Ein Agent auf einem Server steuert Geräte und Programme, die woanders stehen — ohne einen einzigen offenen Port. Der Arbeitsplatz holt sich die Aufträge, statt dass jemand sich zu ihm verbindet. Mit lauffähigem Bausatz | [Seite](https://ralphwystup.github.io/KI-steuert-lokale-Hardware-ueber-eine-Bruecke/) · [Code](https://github.com/RalphWystup/KI-steuert-lokale-Hardware-ueber-eine-Bruecke) |
| **Strömungsrechnung als Kirchhoffsches Netzwerk** | Die Navier-Stokes-Gleichungen als Netzwerk gelesen: Zelle wird Knoten, Fläche wird Zweig. Geprüft an der Wirbelstraße hinter dem Zylinder gegen den Schäfer-Turek-Vergleichsfall | [Seite](https://ralphwystup.github.io/Stroemung-als-Kirchhoffsches-Netzwerk/) · [Code](https://github.com/RalphWystup/Stroemung-als-Kirchhoffsches-Netzwerk) |
| **Kurs-Agent: eine lokale KI schreibt, prüft und flasht Programme** | Ein Kurspaket in einem Ordner: ein Sprachmodell auf dem eigenen Rechner schreibt MicroPython für einen ESP32, prüft es und überträgt es auf das Brett — ohne Konto und ohne Internetzugang | [Seite](https://ralphwystup.github.io/Kurs-Agent-Lokale-KI-schreibt-prueft-und-flasht-Programme-ESP32-als-Beispiel/) · [Code](https://github.com/RalphWystup/Kurs-Agent-Lokale-KI-schreibt-prueft-und-flasht-Programme-ESP32-als-Beispiel) |
| **Levitation als Ingenieursaufgabe** | Was müsste ein Vorgang leisten, wenn die Berichte über die schwebenden Heiligen zuträfen? Prämisse annehmen, Folgen rechnen — heraus kommt eine Spezifikation mit neun Anforderungen | [Seite](https://ralphwystup.github.io/Levitation-als-Ingenieursaufgabe/) · [Code](https://github.com/RalphWystup/Levitation-als-Ingenieursaufgabe) |

## Wie die Arbeiten aufgebaut sind

Jede folgt demselben Muster, damit man sich nicht neu zurechtfinden muss:

* **Eine Seite** als einzelne HTML-Datei — Simulation, Messblatt und die ganze Dokumentation darin.
  Sie lädt nichts nach und läuft auch auf einem Rechner ohne Internetzugang.
* **Ein Manuskript** als Markdown, daraus gesetzt als PDF und DOCX. Herleitungen geschlossen, jede
  Zahl gerechnet oder gemessen, alles von Hand nachrechenbar.
* **Ein Prüfplan** mit einer Schranke je Kriterium und dem Ergebnis der letzten Prüfung. Die Seiten
  werden im echten Browser geprüft, nicht nur im Kopf.
* **Die Programme** dazu: Firmware, Auswertung, Messdaten.

## Lizenz

Alle Arbeiten stehen unter der MIT-Lizenz.
