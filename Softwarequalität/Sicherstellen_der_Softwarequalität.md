# Sicherstellen der Softwarequalität

- verschiedene Modelle und Methoden

## Modelle

### Organisatorische Qualitätsmodelle

- Capability Maturity Model (CMM)
  - Modell zur Bestirmmung des Reifegrades einer Softwareprozesses

### Prozessmodelle

- Capability Maturity Model Integration (CMMI)
  - Familie von Referenzmodellen für unterschiedliche Anwendungsgebiete
  - systematische Aufbereitung bewährter Praktiken
- Rational Unified Process (RUP)
  - Vorgehensmodell zur Softwareentwicklung (Notationssprache UML) + Softwareentwicklungsprogramme
  - Aufteilung der Arbeitsschritte in 9 Disziplinen
    - Unternehmensplan/Geschäftsmodell
    - Spezifikation des Anwendungsmodells
    - Spezifikation der Software-Architektur
    - Realisierung von Softwareschichten
    - Durchführung von Programm-, Modul- und Integrationstests
    - Abnahmetest, Installation, Schulung und Einweisung
    - Konfigurations- und Änderungsmanagement
    - Projektmanagement
    - Entwicklungsumgebung, Werkzeugunterstützung und qualitätssichernde Maßnahmen
- V-Modell
  - Vorgehensmodell, bei dem jeder spezifizierenden Phase eine Testphase zugeordnet ist
- Hardware in the Loop (HIL)
  - Verfahren, bei dem eingebettete Systeme getestet werden, indem ein angepasstes Gegenstück angeschlossen wird

## Methoden

- iterative Softwareentwicklung
  - Vorgehensmodell, bei dem in kleinen Schritten vorgegangen wird
- Spiralmodell
  - Vorgehensmodell, bei dem zyklisch vier Aktivitäten durchlaufen werden
    - Festlegung von Zielen, Identifikation von Alternativen und Beschreibung von Rahmenbedingungen
    - Evaluierung der Alternativen und das Erkennen, Abschätzen und Reduzieren von Risiken, z. B. durch Analysen, Simulationen oder Prototyping
    - Realisierung und Überprüfung des Zwischenprodukts
    - Planung des nächsten Zyklus der Projektfortsetzung
- Refactoring
  - Strukturverbesserung des Quelltextes unter Beibehaltung des beobachtbaren Programmverhaltens
  - Verbesserung von Lesbarkeit, Verständlichkeit, Wartbarkeit und Erweiterbarkeit -> Aufwand für Fehleranalyse und Erweiterungen senken
- Testgetriebene Entwicklung
  - Methode, bei der zuerst die Tests und dann die zu testenden Komponenten erstellt werden

## Softwaretests

- bedeutender Abschnitt der Sotwareentwicklung
- Überprüfung der Software durch verschiedenste Verfahren
- Maßnahmen zur Qualitätssicherung
  - konstruktive Maßnahmen
    - systematische Projektdefinition/Projektzieldefinition
    - detaillierte Anforderungsanalyse
    - Benutzung etablierter Programmierstandards
    - ...
  - analytische Maßnahmen
    - statische Maßnahmen (Überprüfung des Codes vor der Ausführung)
      - Code Reviews
      - Pairprogramming
    - dynamische Maßnahmen (Uberprüfung des Codes bei der Ausführung)
      - strukturorientierter Test (Test auf Basis des Quellcodes)
      - funktionsorientierter Test (Test gegen eine Spezifikation)
      - diversifizierender Test (Vergleich der Testergebnisse verschiedener Versionen)