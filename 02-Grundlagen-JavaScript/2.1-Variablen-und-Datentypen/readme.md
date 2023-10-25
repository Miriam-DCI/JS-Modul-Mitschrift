# JavaScript-Dokumentation

## Inhaltsverzeichnis

1. [Einführung](#einführung)
2. [Variablen und Datentypen](#variablen-und-datentypen)
   2.1. [Variablen in JavaScript](#variablen-in-javascript)
   2.2. [Datentypen in JavaScript](#datentypen-in-javascript)

## 1. Einführung

Hier kommt die Einleitung zur JavaScript-Dokumentation.

## 2. Variablen und Datentypen

### 2.1. Variablen in JavaScript

- Variablen sind ein grundlegendes Konzept in der Programmierung und dienen dazu, Werte oder Daten zu speichern und zu referenzieren.
- In JavaScript können Variablen mit den Schlüsselwörtern `var`, `let` oder `const` deklariert werden.
  - `var` wurde in älteren Versionen von JavaScript verwendet, wird aber heute oft durch `let` oder `const` ersetzt.
  - `let` ermöglicht die Deklaration von Variablen, die später geändert werden können.
  - `const` deklariert Konstanten, deren Wert nach der Initialisierung nicht geändert werden kann.

### 2.2. Datentypen in JavaScript

JavaScript bietet verschiedene Datentypen, um verschiedene Arten von Daten zu repräsentieren. Hier sind die gängigsten Datentypen:

```javascript
Number: Dieser Datentyp umfasst sowohl Ganzzahlen als auch Fließkommazahlen.
let age = 30; // Ganzzahl
let price = 29.99; // Fließkommazahl

String: Strings repräsentieren Text und werden in einfachen oder doppelten Anführungszeichen erstellt.
let name = "John";
let message = 'Hello, World!';

Boolean: Dieser Datentyp hat nur zwei mögliche Werte: true oder false.
let isApproved = true;
let isStopped = false;

Array: Arrays sind geordnete Listen von Werten. Sie können Werte unterschiedlicher Datentypen enthalten.
let colors = ["red", "green", "blue"];
let scores = [98, 84, 70, 91];

Object: Objekte ermöglichen die Organisation von Daten in Eigenschaften und Werte. Eigenschaften können verschiedene Datentypen haben.
let person = {
  firstName: "Alice",
  lastName: "Johnson",
  age: 25
};
```

**Undefined und Null:**
undefined zeigt an, dass eine Variable deklariert, aber nicht initialisiert wurde. null wird verwendet, um anzuzeigen, dass eine Variable bewusst auf den Wert "null" gesetzt wurde.

```Javascript

let data; // data ist undefined
let emptyValue = null;
```
