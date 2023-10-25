## 2.4. Funktionen in JavaScript

Inhaltsverzeichnis:

- [Grundlagen von Funktionen](#grundlagen-von-funktionen)
- [Funktionsausdrücke](#funktionsausdrücke)
- [Anonyme Funktionen](#anonyme-funktionen)
- [Funktionsbereich (Scope)](#funktionsbereich-scope)
- [Funktionen als First-Class Citizens](#funktionen-als-first-class-citizens)
- [Funktionskonstruktor](#funktionskonstruktor)
- [Arrow Functions](#arrow-functions)
- [Rekursive Funktionen](#rekursive-funktionen)

Funktionen in JavaScript:

- Funktionen sind in JavaScript wichtige Bausteine, die dazu dienen, wiederholbaren Code zu organisieren und auszuführen.

### Grundlagen von Funktionen

1. Funktionsdeklaration:

   - Mit einer Funktionsdeklaration können Sie eine Funktion definieren.
   - Beispiel:

     ```JavaScript
     if (condition) {
       // Code hier
     }
     ```

2. Funktionsaufruf:

   - Um den Code in einer Funktion auszuführen, rufen Sie die Funktion auf.
   - Beispiel:

     ```JavaScript
     if (condition) {
       // Code hier
     }
     ```

3. Parameter:

   - Funktionen können Parameter akzeptieren, die Werte entgegennehmen, die in der Funktion verwendet werden.
   - Beispiel:

     ```JavaScript
     function add(a, b) {
       return a + b;
     }
     ```

4. Rückgabewerte:

   - Funktionen können Werte mit dem return-Schlüsselwort zurückgeben.
   - Beispiel:

     ```JavaScript
     function add(a, b) {
       return a + b;
     }
     ```

5. Funktionen als Werte:

   - In JavaScript können Funktionen als Werte behandelt und an andere Funktionen übergeben werden.
   - Beispiel:

     ```JavaScript
     const myFunction = function () {
       console.log("Hello from myFunction!");
     };
     ```

### Funktionsausdrücke

- Funktionsausdrücke sind eine Möglichkeit, Funktionen als Werte zu behandeln und flexibel mit ihnen umzugehen.

### Anonyme Funktionen

- Funktionen ohne Namen werden als anonyme Funktionen bezeichnet und können in Variablen gespeichert oder als Argumente an andere Funktionen übergeben werden.

### Funktionsbereich (Scope)

- Funktionen haben einen eigenen Bereich (Scope), in dem Variablen definiert werden.
- Variablen, die innerhalb einer Funktion definiert sind, sind normalerweise nur in dieser Funktion sichtbar.

### Funktionen als First-Class Citizens

- In JavaScript werden Funktionen als First-Class Citizens behandelt, was bedeutet, dass sie wie andere Werte verwendet werden können.

### Funktionskonstruktor

- Neben Funktionsdeklarationen und -ausdrücken können Sie Funktionen auch mit dem Funktionskonstruktor erstellen.

### Arrow Functions

- Arrow Functions sind eine kompaktere Schreibweise für Funktionen und sind in modernem JavaScript weit verbreitet.

### Rekursive Funktionen

- Eine rekursive Funktion ist eine Funktion, die sich selbst aufruft. Sie ist hilfreich, um bestimmte Arten von Problemen zu lösen.

Funktionen sind ein Schlüsselelement in JavaScript und ermöglichen die Organisation von Code, die Wiederverwendbarkeit von Logik und die Abstraktion komplexer Aufgaben. Ein gutes Verständnis von Funktionen ist entscheidend, um JavaScript-Programme effektiv zu schreiben.
