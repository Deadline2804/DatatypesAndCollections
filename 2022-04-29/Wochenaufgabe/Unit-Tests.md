# Unit-Tests

## Was wird getestet?

- Test der einzelnen Module (in sich abgeschlossene Codeabschnitte mit einer Funktion, je nach Definition unterschiedliche Größe)

## Benennung der Tests

- keine festen Naming-Conventions für Unit-Tests
- z.B
  - MethodName_StateUnderTest_ExpectedBehavior
  - test[FeatureBeingTested]
  - Should_ExpectedBehavior_When_StateUnderTest
  - Given_Preconditions_When_StateUnderTest_Then_ExpectedBehavior

## Aufbau, Organisation der Tests

- AAA-Regel
  - Arrange
    - Startsitutation des Tests definieren
      - Komponente erzeugen und initialisieren
      - Mocks erzeugen, initialisieren und definieren
      - Variablen setzen
  - Act
    - Ausführung der Aktion die getestet wird
      - besteht nur aus einem Ausruf
  - Assert
    - Überprüfung, ob das gewünschte Ergebnis erzielt wurde
      - nur ein einzelnes fachliches Ergebnis wird kontrolliert
        - mehrere Asserts auch möglich, wenn diese zum Ergebnis gehören