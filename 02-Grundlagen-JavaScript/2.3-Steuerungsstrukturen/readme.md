## 2.3. Steuerungsstrukturen

Steuerungsstrukturen in JavaScript sind entscheidend für die Kontrolle des Programmflusses und die Ausführung von Anweisungen. JavaScript unterstützt verschiedene Arten von Steuerungsstrukturen, darunter:

- [Bedingte Anweisungen (if, else if, else)](#bedingte-anweisungen-if-else-if-else)
- [Schleifen (for, while, do-while)](#schleifen-for-while-do-while)
- [Schalteranweisungen (switch)](#schalteranweisungen-switch)
- [Sprunganweisungen (break, continue)](#sprunganweisungen-break-continue)
- [Funktionen](#funktionen)
- [Fehlerbehandlung (try, catch, throw)](#fehlerbehandlung-try-catch-throw)

### Bedingte Anweisungen (if, else if, else)

Bedingte Anweisungen ermöglichen es, Anweisungen basierend auf einer Bedingung auszuführen oder zu überspringen. Hier sind Beispiele:

```JavaScript
if (condition) {
// Code wird ausgeführt, wenn die Bedingung wahr ist.
} else if (anotherCondition) {
// Code wird ausgeführt, wenn die erste Bedingung falsch und die zweite Bedingung wahr ist.
} else {
// Code wird ausgeführt, wenn keine der Bedingungen wahr ist.
}
```

### Schleifen (for, while, do-while)

Schleifen ermöglichen die wiederholte Ausführung von Anweisungen, bis eine bestimmte Bedingung erfüllt ist. Hier sind Beispiele:

#### for-Schleife

```JavaScript

for (let i = 0; i < 5; i++) {
// Code wird 5 Mal ausgeführt.
}

```

#### while-Schleife

```JavaScript
while (condition) {
// Code wird wiederholt ausgeführt, solange die Bedingung wahr ist.
}
```

#### do-while-Schleife

```JavaScript
do {
// Code wird mindestens einmal ausgeführt und dann wiederholt, solange die Bedingung wahr ist.
} while (condition);
```

### Schalteranweisungen (switch)

Die Schalteranweisung ermöglicht es, verschiedene Codeblöcke basierend auf verschiedenen Werten auszuführen. Hier ist ein Beispiel:

```JavaScript
switch (value) {
case 1:
// Code für den Fall, dass value 1 ist.
break;
case 2:
// Code für den Fall, dass value 2 ist.
break;
default:
// Code für den Fall, dass kein Case übereinstimmt.
}
```

### Sprunganweisungen (break, continue)

Sprunganweisungen werden verwendet, um den normalen Ausführungsfluss zu ändern. break wird verwendet, um aus einer Schleife oder Schalteranweisung auszubrechen. continue wird verwendet, um den aktuellen Schleifendurchlauf zu überspringen und mit dem nächsten fortzufahren.

### Funktionen

Funktionen ermöglichen die Organisation von Code in wiederverwendbare Einheiten. Sie können auch Parameter akzeptieren und Werte zurückgeben. Hier ist ein Beispiel:

```JavaScript
function add(a, b) {
return a + b;
}
```

### Fehlerbehandlung (try, catch, throw)

Die Fehlerbehandlung ermöglicht das Abfangen und Behandeln von Ausnahmen und Fehlern im Code. Die try-catch-Anweisungen werden verwendet, um Ausnahmen abzufangen und spezifischen Code zur Fehlerbehandlung auszuführen.

Steuerungsstrukturen sind entscheidend, um komplexe Logik in JavaScript zu implementieren und den Programmfluss zu steuern. Ein Verständnis dieser Strukturen ist unerlässlich, um effiziente und gut strukturierte Programme zu schreiben.
