# 🔥 Camina & Schmid SMR – ESPHome CAN Logger

## 🇩🇪 Deutsch

Dieses Projekt beschäftigt sich mit dem Auslesen und Analysieren der CAN-Bus-Kommunikation einer Camina & Schmid SMR Abbrandsteuerung.

Ziel ist es, die Kommunikation der Steuerung besser zu verstehen, relevante Daten auszulesen und diese über ESPHome und MQTT in Home Assistant zur Verfügung zu stellen.

Das Projekt befindet sich aktuell in der Entwicklung. Einige CAN-Nachrichten konnten bereits identifiziert und erste Werte wie Abbrandtemperatur, Klappenstellung und Betriebsphase dekodiert werden.

### Funktionen
- CAN-Bus-Datenerfassung über ESP32-C3
- Aufzeichnung von Standard- und Extended-CAN-Frames
- Anzeige der CAN-Rohdaten
- Analyse und Dekodierung ausgewählter CAN-Nachrichten
- Erfassung von Temperatur- und Klappenwerten
- MQTT-Übertragung der Daten
- Integration in Home Assistant
- ESPHome-Webserver zur Diagnose

### Projektstatus

🧪 Aktive Entwicklung – weitere CAN-IDs und Datenstrukturen müssen noch untersucht und verifiziert werden.

### Mithelfen und verbessern

Ich freue mich über jede Unterstützung, Hinweise, Ideen und Verbesserungsvorschläge.

Besonders interessant sind:
- Weitere entschlüsselte CAN-Nachrichten
- Verbesserung der bisherigen Dekodierung
- Unterstützung bei der Analyse der CAN-Daten
- Ideen für zusätzliche Sensoren und Funktionen

Auch eigene Erfahrungen mit Camina & Schmid Abbrandsteuerungen sind herzlich willkommen!

**Hinweis:** Dieses Projekt ist ein privates Entwicklungsprojekt und steht in keiner offiziellen Verbindung zu Camina & Schmid.

---

## 🇬🇧 English

This project focuses on reading and analyzing the CAN bus communication of a Camina & Schmid SMR combustion control system.

The goal is to better understand the controller's communication, extract relevant data and make it available in Home Assistant using ESPHome and MQTT.

The project is still under active development. Some CAN messages have already been identified, and initial values such as combustion temperature, damper position and operating phase have been decoded.

Contributions, ideas and improvements are very welcome!

**Disclaimer:** This is an independent community project and is not officially affiliated with Camina & Schmid.
