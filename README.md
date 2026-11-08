# Herzfrequenzsensor

Entwicklung einer eigenen Leiterplatte (PCB) zur Messung der Herzfrequenz mit einem optischen Herzfrequenzsensor. Die Schaltung umfasst eine Spannungsregelung sowie eine I²C-Schnittstelle zur Kommunikation mit einem Mikrocontroller.

**Status:** [z. B. Entworfen, Gerber-Dateien erstellt]

## Komponenten

| Bauteil | Funktion |
|---|---|
| ESP32-S3-WROOM-1 | Mikrocontroller |
| AMS1117 | Spannungsregler (5 V → 3,3 V) |
| AP2112K-1.8 | Spannungsregler (3,3 V → 1,8 V) |
| MAX30102 | Optischer Herzfrequenzsensor (I²C) |
| USB-C-Buchse | Stromversorgung und Programmierung |

## Schaltplan
![Schaltplan](Bilder/schaltplan.png)

## Leiterplatte (PCB)
![PCB-Layout](Bilder/pcb.png)

## 3D-Ansicht
![3D-Ansicht](Bilder/3d.png)

## Was ich gelernt habe
1. Entwurf eines Schaltplans und PCB-Layouts mit KiCad
2. Lesen von Datenblättern und Auswahl passender Bauteile
3. Auslegung der Spannungsversorgung (5 V → 3,3 V → 1,8 V)
4. Entwurf einer Platine mit ESP32-S3 und I²C-Sensor
5. Prüfung mit Electrical Rules Check (ERC) und Design Rules Check (DRC)
6. Erzeugen von Gerber-Dateien für die Fertigung
