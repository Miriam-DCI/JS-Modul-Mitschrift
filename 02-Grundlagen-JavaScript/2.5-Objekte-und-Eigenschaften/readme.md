## 2.5. Objekte und Eigenschaften

Inhaltsverzeichnis:

- [Objekt-Basisstruktur](#objekt-basisstruktur)
- [Zugriff auf Eigenschaften](#zugriff-auf-eigenschaften)
- [Objektmethoden](#objektmethoden)
- [Objektiteration](#objektiteration)
- [Objekterstellung](#objekterstellung)
- [Objektverkettung (Object Destructuring)](#objektverkettung-object-destructuring)
- [Objektklonen](#objektklonen)
- [Vererbung in Objekten](#vererbung-in-objekten)

Objekte in JavaScript:

- Objekte sind eine der grundlegenden Datenstrukturen in JavaScript und ermöglichen die Organisation von Daten in Form von Schlüssel-Wert-Paaren.

### Objekt-Basisstruktur

- Ein Objekt besteht aus Schlüssel (auch Eigenschaften genannt) und den zugehörigen Werten.
- Beispiel:

```JavaScript
const person = {
firstName: "John",
lastName: "Doe",
age: 30,
};
```

### Zugriff auf Eigenschaften

- Sie können auf die Eigenschaften eines Objekts zugreifen, indem Sie den Punkt-Operator verwenden oder indem Sie die Klammern-Schreibweise verwenden.
- Beispiel:

```JavaScript
console.log(person.firstName); // "John"
console.log(person["lastName"]); // "Doe"
```

### Objektmethoden

- Objekte können auch Funktionen (Methoden) als Eigenschaften haben.
- Beispiel:

```JavaScript
const car = {
brand: "Toyota",
model: "Camry",
startEngine: function () {
console.log("Engine started.");
},
};
```

### Objektiteration

- Sie können durch die Eigenschaften eines Objekts iterieren, indem Sie Schleifen wie for...in verwenden.
- Beispiel:

```JavaScript
for (const key in person) {
console.log(key, person[key]);
}
```

### Objekterstellung

- Sie können Objekte entweder direkt mithilfe von geschweiften Klammern erstellen oder den Konstruktor Object verwenden.

### Objektverkettung (Object Destructuring)

- Objektverkettung ist eine Methode zur Extraktion von Werten aus Objekten und zur Zuweisung dieser Werte zu Variablen.
- Beispiel:

```JavaScript
const { firstName, lastName } = person;
```

### Objektklonen

- Beim Kopieren von Objekten sollten Sie darauf achten, dass Sie nicht nur die Referenz kopieren, sondern eine tiefe Kopie erstellen, um unerwartete Seiteneffekte zu vermeiden.

### Vererbung in Objekten

- Sie können Objekte erben, indem Sie das Prinzip der Vererbung verwenden.

Objekte sind vielseitig und spielen eine zentrale Rolle in JavaScript. Sie werden verwendet, um Daten und Funktionen in einer einzigen Einheit zu organisieren und bieten eine flexible Möglichkeit zur Modellierung von Entitäten in einer Anwendung.
