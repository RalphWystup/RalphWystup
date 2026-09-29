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

## Messen mit Kamera und Sensor

| Arbeit | Worum es geht | |
|:--|:--|:--|
| **Tomatenwächter** | Wann muss gegossen werden? Eine Kamera erkennt hängende Blätter am Excess-Green-Index, ein Raspberry Pi entscheidet | [Seite](https://ralphwystup.github.io/Tomatenwaechter-Bildgestuetzte-Welkeerkennung-mit-ESP32-CAM-und-Raspberry-Pi/) · [Code](https://github.com/RalphWystup/Tomatenwaechter-Bildgestuetzte-Welkeerkennung-mit-ESP32-CAM-und-Raspberry-Pi) |
| **Wärmebild-Fusion mit ESP32-CAM und AMG8833** | Kamerabild und Wärmebild deckungsgleich übereinander, mit 64 Thermoelementen und der Parallaxe zweier Augen | [Seite](https://ralphwystup.github.io/Waermebild-Fusion-mit-ESP32-CAM-und-AMG8833/) · [Code](https://github.com/RalphWystup/Waermebild-Fusion-mit-ESP32-CAM-und-AMG8833) |
| **Automatisch gesteuertes Lichtmikroskop mit KI** | Aufbau, Algorithmen, Fernwartung und ein KI-Fenster — eine Laborstation für Studierende | [Seite](https://ralphwystup.github.io/Automatisch-gesteuertes-Lichtmikroskop-mit-KI/) · [Code](https://github.com/RalphWystup/Automatisch-gesteuertes-Lichtmikroskop-mit-KI) |

## Signale und Diagnose

| Arbeit | Worum es geht | |
|:--|:--|:--|
| **Akustische Rohrdiagnose mit einem dynamischen Netzwerkzwilling** | Von der Impulsantwort zur Erkennung von Seitenrohr und Belag, mit einer überlagerten lernenden Ebene | [Seite](https://ralphwystup.github.io/Akustische-Rohrdiagnose-mit-einem-dynamischen-Netzwerkzwilling/) · [Code](https://github.com/RalphWystup/Akustische-Rohrdiagnose-mit-einem-dynamischen-Netzwerkzwilling) |
| **Wetter-Fernschreiber Siemens T68d** | Der Wetterbericht auf einem Streifenschreiber von 1959: RTTY und ITA2 bei 50 Baud. Die Seite druckt das wirkliche Wetter für einen Ort, den man eingibt | [Seite](https://ralphwystup.github.io/Wetter-Fernschreiber-Siemens-T68d-RTTY-und-ITA2-mit-ESP32/) · [Code](https://github.com/RalphWystup/Wetter-Fernschreiber-Siemens-T68d-RTTY-und-ITA2-mit-ESP32) |

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
