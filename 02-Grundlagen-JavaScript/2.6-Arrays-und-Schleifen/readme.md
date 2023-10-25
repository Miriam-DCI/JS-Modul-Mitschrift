## 2.6. Arrays und Schleifen

Inhaltsverzeichnis:

- [Arrays in JavaScript](#arrays-in-javascript)
- [Array-Erstellung](#array-erstellung)
- [Zugriff auf Array-Elemente](#zugriff-auf-array-elemente)
- [Array-Methoden](#array-methoden)
- [Array-Iteration](#array-iteration)
- [Schleifen in JavaScript](#schleifen-in-javascript)
- [1. for-Schleife](#1-for-schleife)
- [2. while-Schleife](#2-while-schleife)
- [3. do...while-Schleife](#3-do-while-schleife)
- [4. for...in-Schleife](#4-for-in-schleife)
- [5. for...of-Schleife](#5-for-of-schleife)
- [Zusätzliche Schleifenmethoden für Arrays](#zusätzliche-schleifenmethoden-für-arrays)
- [6. Kontrolle innerhalb von Schleifen - break und continue](#6-kontrolle-innerhalb-von-schleifen---break-und-continue)
- [7. Asynchrone Iteration mit for await ... of](#7-asynchrone-iteration-mit-for-await--of)

### Arrays in JavaScript

- Ein Array ist eine geordnete Liste von Werten, die in einer einzigen Variablen gespeichert sind. In JavaScript können Arrays Werte verschiedener Datentypen enthalten.

### Array-Erstellung

- Arrays können erstellt werden, indem Sie Werte in eckigen Klammern [...] auflisten.
- Beispiel:

```JavaScript
const fruits = ["Apple", "Banana", "Cherry"];
```

### Zugriff auf Array-Elemente

- Auf die Elemente eines Arrays kann mithilfe von Indexnummern zugegriffen werden. Das Indexieren beginnt bei 0.
- Beispiel:

```JavaScript
console.log(fruits[0]); // "Apple"
console.log(fruits[2]); // "Cherry"
```

### Array-Methoden

- JavaScript bietet eine Vielzahl von Array-Methoden, mit denen Sie Operationen auf Arrays durchführen können. Dazu gehören Methoden wie push, pop, shift, unshift, splice, slice, und viele mehr.
- Beispiel:

```JavaScript
fruits.push("Orange"); // Fügt ein Element am Ende hinzu.
fruits.pop(); // Entfernt das letzte Element.
```

### Array-Iteration

- Sie können mithilfe von for-Schleifen leicht durch die Elemente eines Arrays iterieren und Operationen auf jedem Element ausführen.
- Beispiel:

```JavaScript
for (let i = 0; i < fruits.length; i++) {
console.log(fruits[i]);
// Hier können Sie weitere Operationen mit jedem Element durchführen.
}
```

### Schleifen in JavaScript

Schleifen sind wichtige Kontrollstrukturen in der Programmierung, die es ermöglichen, Codeblöcke mehrmals auszuführen. JavaScript bietet verschiedene Arten von Schleifen, die je nach den Anforderungen verwendet werden können.

#### 1. for-Schleife

- for-Loop: Führt einen Codeblock eine bestimmte Anzahl von Malen aus.

```JavaScript
for (Initialisierung; Bedingung; Schritt) {
// Code, der bei jedem Schleifendurchlauf ausgeführt wird
}
```

- Initialisierung: Hier wird eine Variable initialisiert, normalerweise ein Zähler.
- Bedingung: Die Schleife wird ausgeführt, solange diese Bedingung wahr ist.
- Schritt: Nach jedem Durchlauf wird dieser Schritt ausgeführt.

#### 2. while-Schleife

- while-Loop: Führt einen Codeblock aus, solange eine bestimmte Bedingung wahr ist.

```JavaScript
while (Bedingung) {
// Code, der solange die Bedingung wahr ist, ausgeführt wird
}
```

#### 3. do...while-Schleife

- do...while-Loop: Führt einen Codeblock aus, solange eine bestimmte Bedingung wahr ist. Der Codeblock wird mindestens einmal ausgeführt, bevor die Bedingung überprüft wird.

```JavaScript
do {
// Code, der mindestens einmal ausgeführt wird
} while (Bedingung);
```

#### 4. for...in-Schleife

- for...in-Loop: Iteriert über die Eigenschaften eines Objekts.

```JavaScript
for (const property in object) {
// Code, der für jede Eigenschaft im Objekt ausgeführt wird
}
```

#### 5. for...of-Schleife

- for...of-Loop: Iteriert über die Elemente einer Liste.

```JavaScript
for (const element of iterable) {
// Code, der für jedes Element im Iterable ausgeführt wird
}
```

#### Zusätzliche Schleifenmethoden für Arrays

- JavaScript bietet zusätzliche Array-Methoden wie forEach, map, filter, reduce, every, some, und find, um Operationen auf Arrays durchzuführen.

#### 6. Kontrolle innerhalb von Schleifen - break und continue

- Die break-Anweisung unterbricht die Schleife vorzeitig, während die continue-Anweisung den aktuellen Schleifendurchlauf überspringt.

#### 7. Asynchrone Iteration mit for await ... of

- Diese Schleifenform wird verwendet, um asynchron über awaitable Objekte zu iterieren.

Mit diesen Kontrollstrukturen und Schleifenarten können Sie vielfältige Aufgaben in JavaScript bewältigen und die Logik in Ihren Programmen steuern. Falls Sie weitere Fragen oder Informationen benötigen, stehe ich gerne zur Verfügung.
