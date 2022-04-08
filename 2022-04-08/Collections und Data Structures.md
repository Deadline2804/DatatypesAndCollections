# Collections und Data Structures

## Data Struture

- ist die Art und Weise, Daten zu speichern und zu organisieren
- teilt sich auf in primitiv (primitive Datentypen) und nicht primitiv
- nicht primitiv in Linear (Collections) und nicht linear (Tree, Graph)

## Collection

- Data Structures, die ein oder mehrere Elemente eines Typen enthalten

## Arten von Collections

- Collection
  - Collection ohne wirklichen Datentyp; Elemente werden als Typ Objekt gespeichert
    - ArrayList
    - Hashtable
    - Queue
    - Stack
- Collections.Generic
  - Collection mit Elementen vom Typ T
    - Dictionary<TKey, TValue>;
    - List\<T>;
    - Queue\<T>;
    - SortedList<TKey, TValue>;
    - Stack\<T>;
- Collection.Concurrent
  - Collection die von mehreren Threads gleichzeitig benutzt werden
    - ConcurrentQueue\<T>;
    - ConcurrentStack\<T>;
    - ConcurrentDictionary<TKey, TValue>;

## Einsatzgebiete

- Sequenzielle Liste; Element nach Auslesen gelöscht:
  - Queue
  - Stack
- bestimmte Reihenfolge bei der Ausgabe (FIFO, LIFO, random)
  - Queue (FIFO)
  - Stack (LIFO)
  - LinkedList (Top-Down, Bottom-Up)
- Zugriff auf Elemente
  - per Index
    - ArrayList
    - List
  - per Schlüssel
    - Hashtable
    - Dictionary
  - per Index oder Schlüssel
    - SortedList

- Menge an Werten in Element
  - Ein Wert pro Element
    - IList
  - Ein Schlüssel und ein Wert
    - IDictionary
  - Eingebette Schlüssel
    - KeyedCollection
  - Ein Schlüssel, Mehrere Werte
    - NameValueCollection
- andere Reihenfolge als beim Eintragen
  - Hashtable
    - sortiert nach Hashwert
  - SortedList, SortedDictionary
    - sortiert nach Schlüssel
  - ArrayList, List
    - Sort() Methode

## Geschwindigkeit

| **Collection**       | **Leseperfomance**      | **Schreibperfomance** |
| -------------------- | ----------------------- | --------------------- |
| **Dictionary**       | O(1)                    | O(1)                  |
| **SortedDictionary** | O(log n)                | O(log n)              |
| SortedList           | O(log n)                | O(n)                  |
| **List**             | Index: O(1); Value O(n) | O(n)                  |
| **LinkedList**       | O(n)                    | O(1)                  |
| **HashSet**          | O(1)                    | O(1)                  |
| **SortedSet**        | O(log n)                | O()log n              |
| **Stack**            | O(1)                    | O()1                  |
| **Queue**            | O(1)                    | O(1)                  |