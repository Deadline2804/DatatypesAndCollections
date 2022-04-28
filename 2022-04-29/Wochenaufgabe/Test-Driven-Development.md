# Test Driven Development

- Test-First-Ansatz (erst Tests konstruieren, dann Quellcode schreiben)
  - entstanden durch Ken Beck (Begründer von Extreme Programming)
- zyklische Prozesse
  - Tests schreiben, die fehlschlagen
  - nur ausreichend Quellcode schreiben, um die Test zu erfüllen
  - Refactoring
- inkrementelles Vorgehensmodell
  - nach jedem bestandenen Test neuer Quellcode
- Red-Green-Refactor Zyklus
  - 3 Phasenmodell, um TDD mit maximaler Effizienz zu durchlaufen
    - Rote Phase
      - die Rolle des Nutzers
      - Test wird geschreieben -> Überlegungen welche Komponenten notwendig sind
    - Grüne Phase
      - Rolle des Programmierers
      - Versuch, mit so wenig Code wie möglich den Test zu erfüllen
    - Refactoring
      - Code wird aufgeräumt, um für Entwickler verständlicher zu sein/eleganter zu sein
  - Phasen dürfen sich nicht überschneiden
- verschiedene Testarten möglich
  - Unit-Tests
  - Integrationstests

## Behaviour Driven Development

- hat sich aus dem TDD entwickelt
- verhaltensgetriebene Software-Entwicklung
- Verhaltensweise der Software steht vor Richtigkeit des Codes
- kein technisches Verständnis für die Tests notwendig