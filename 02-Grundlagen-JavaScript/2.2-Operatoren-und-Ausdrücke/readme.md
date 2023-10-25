# JavaScript-Dokumentation

## Inhaltsverzeichnis

1. [Einführung](#einführung)
2. [Variablen und Datentypen](#variablen-und-datentypen)
   2.1. [Variablen in JavaScript](#variablen-in-javascript)
   2.2. [Operatoren und Ausdrücke](#operatoren-und-ausdrücke)

## 1. Einführung

Hier kommt die Einleitung zur JavaScript-Dokumentation.

## 2. Variablen und Datentypen

### 2.1. Variablen in JavaScript

- Variablen sind ein grundlegendes Konzept in der Programmierung und dienen dazu, Werte oder Daten zu speichern und zu referenzieren.
- In JavaScript können Variablen mit den Schlüsselwörtern `var`, `let` oder `const` deklariert werden.
  - `var` wurde in älteren Versionen von JavaScript verwendet, wird aber heute oft durch `let` oder `const` ersetzt.
  - `let` ermöglicht die Deklaration von Variablen, die später geändert werden können.
  - `const` deklariert Konstanten, deren Wert nach der Initialisierung nicht geändert werden kann.

### 2.2. Operatoren und Ausdrücke

Operatoren sind spezielle Symbole oder Schlüsselwörter, die verwendet werden, um Operationen auf Werten und Variablen durchzuführen. JavaScript unterstützt verschiedene Arten von Operatoren, darunter:

- Arithmetische Operatoren: Diese Operatoren führen mathematische Berechnungen durch.

  - Addition (+), Subtraktion (-), Multiplikation (\*), Division (/), Modulo (%) usw.

- Vergleichsoperatoren: Vergleichsoperatoren werden verwendet, um Werte zu vergleichen und logische Wahrheitswerte zurückzugeben.

  - Gleich (== oder ===), Ungleich (!= oder !==), Größer als (>), Kleiner als (<), usw.

- Logische Operatoren: Diese Operatoren werden verwendet, um logische Ausdrücke zu kombinieren.

  - UND (&&), ODER (||), NICHT (!) usw.

- Zuweisungsoperatoren: Diese Operatoren werden verwendet, um Werte Variablen zuzuweisen.
  - Zuweisung (=), Additionszuweisung (+=), Subtraktionszuweisung (-=), usw.

Ausdrücke bestehen aus einer Kombination von Werten, Variablen und Operatoren, die berechnet werden, um einen Wert zurückzugeben. Hier sind einige Beispiele für Ausdrücke:

```javascript
Arithmetischer Ausdruck:
let result = 10 + 5; // Der Ausdruck 10 + 5 ergibt den Wert 15.

Vergleichsausdruck:
let isGreater = 20 > 10; // Der Ausdruck 20 > 10 ergibt den Wert true.

Logischer Ausdruck:
let isValid = (age > 18) && (hasPermission === true); // Kombinierter logischer Ausdruck.
```

**Operator-Vorrangregeln:**
Operatoren in JavaScript haben verschiedene Vorrangregeln, die festlegen, in welcher Reihenfolge Ausdrücke ausgewertet werden. Es ist wichtig zu verstehen, wie diese Regeln funktionieren, um unerwartetes Verhalten zu vermeiden.

Operatoren und Ausdrücke sind in der Programmierung äußerst nützlich und werden häufig verwendet, um Berechnungen, Vergleiche und logische Entscheidungen zu treffen. Das Verständnis von Operatoren und deren ordnungsgemäße Verwendung ist entscheidend, um effektiven JavaScript-Code zu schreiben.
