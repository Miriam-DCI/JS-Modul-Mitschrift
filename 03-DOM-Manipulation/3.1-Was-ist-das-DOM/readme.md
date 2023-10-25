## 3. DOM-Manipulation (Document Object Model)

Inhaltsverzeichnis:

- [Was ist das DOM?](#was-ist-das-dom)
- [DOM-Zugriff und -Manipulation](#dom-zugriff-und-manipulation)
- [Ereignisse im DOM](#ereignisse-im-dom)
- [DOM-Manipulation in der Praxis](#dom-manipulation-in-der-praxis)
- [DOM-Manipulationstools](#dom-manipulationstools)

### 3.1. Was ist das DOM?

- DOM-Definition: Das Document Object Model ist eine Programmierschnittstelle für HTML- und XML-Dokumente. Es stellt die Struktur der Dokumente als Baum dar, wodurch JavaScript auf den Inhalt zugreifen und ihn ändern kann.
- DOM-Baum: Der DOM-Baum besteht aus Elementen, Attributen und Textknoten, die die Struktur einer Webseite darstellen.
- Beispiel - Visualisierung des DOM-Baums (HTML-Code):
  ```html
  <html>
    <head>
      <title>Beispiel</title>
    </head>
    <body>
      <h1>Willkommen</h1>
      <p>Dies ist ein einfaches Beispiel.</p>
    </body>
  </html>
  ```

### 3.2. DOM-Zugriff und -Manipulation

- Zugriff auf Elemente: Wir werden sehen, wie man DOM-Elemente anhand von IDs, Klassen, Tags und anderen Selektoren auswählen kann.
- Änderungen vornehmen: Wir lernen, wie man den Textinhalt eines Elements ändert, Attribute aktualisiert, CSS-Stile anpasst und neue Elemente zum DOM hinzufügt.
- Beispiel - Zugriff auf Elemente und Änderungen vornehmen:
  JavaScript
  const title = document.getElementById('title');
  title.textContent = 'Neuer Titel';
  const newParagraph = document.createElement('p');
  newParagraph.textContent = 'Dies ist ein neuer Absatz.';
  document.body.appendChild(newParagraph);

### 3.3. Ereignisse im DOM

- DOM-Ereignisse: Das DOM ermöglicht das Hinzufügen von Event-Listenern zu Elementen, um auf Ereignisse wie Klicks, Tastatureingaben und das Laden der Seite zu reagieren.
- Beispiel - Event-Listener hinzufügen:
  ```JavaScript
  const button = document.getElementById('myButton');
  button.addEventListener('click', () => {
    alert('Button wurde geklickt!');
  });
  ```

```
### 3.4. DOM-Manipulation in der Praxis

- In diesem Abschnitt werden wir praktische Beispiele durchgehen, die zeigen, wie das DOM in realen Webanwendungen manipuliert wird.
- Beispiel - Interaktives Formular mit Validierung: Erstellen eines Formulars, das überprüft, ob Felder ausgefüllt sind, bevor es gesendet wird.

### 3.5. DOM-Manipulationstools

- DOM-Manipulationsbibliotheken: Es gibt Bibliotheken wie jQuery, die die DOM-Manipulation vereinfachen und beschleunigen.
- Browser-Entwicklungswerkzeuge: Die Entwicklertools moderner Browser sind hilfreiche Werkzeuge zur Untersuchung und Manipulation des DOMs.
- Beispiel - Verwendung von Browser-Entwicklungswerkzeugen: Demonstration der Verwendung von Entwicklertools zum Inspektieren und Debuggen des DOMs.

Das Document Object Model ist ein wesentliches Konzept in der Webentwicklung und ermöglicht die Interaktion mit und Manipulation von Webseiteninhalten. Diese Beispiele bieten einen fundierten Einstieg in das DOM und zeigen, wie JavaScript verwendet wird, um Webseiten dynamischer zu gestalten.
```
