### 3.3. Ändern von DOM-Elementen

Inhaltsverzeichnis:

- [Ändern von Textinhalten](#ändern-von-textinhalten)
- [Ändern von Attributen](#ändern-von-attributen)
- [Ändern von CSS-Stilen](#ändern-von-css-stilen)
- [Hinzufügen und Entfernen von Klassen](#hinzufügen-und-entfernen-von-klassen)
- [Ändern von HTML-Inhalten](#ändern-von-html-inhalten)
- [Erstellen und Hinzufügen neuer Elemente](#erstellen-und-hinzufügen-neuer-elemente)
- [Entfernen von Elementen](#entfernen-von-elementen)

#### 3.3.1. Ändern von Textinhalten

- Definition: Das Ändern von Textinhalten in HTML-Elementen, wie Überschriften, Absätzen und Span-Elementen.
- Beispiel: Aktualisieren des Textinhalts eines HTML-Elements.
  ```JavaScript
  const heading = document.getElementById('main-heading');
  heading.textContent = 'Neuer Titel';
  ```

#### 3.3.2. Ändern von Attributen

- Definition: Das Aktualisieren von Attributen von HTML-Elementen, z.B., src für Bilder oder href für Links.
- Beispiel: Ändern des Bildquellenattributs (src) eines Bildes.
  ```JavaScript
  const image = document.getElementById('my-image');
  image.src = 'neues-bild.jpg';
  ```

#### 3.3.3. Ändern von CSS-Stilen

- Definition: Das Ändern von CSS-Stilen, wie Farben, Schriftgröße und Positionierung von Elementen.
- Beispiel: Anpassen des Hintergrundfarbstils eines HTML-Elements.
  ```JavaScript
  const element = document.getElementById('styled-box');
  element.style.backgroundColor = 'lightblue';
  ```

#### 3.3.4. Hinzufügen und Entfernen von Klassen

- Definition: Das Hinzufügen oder Entfernen von CSS-Klassen, um das Erscheinungsbild von Elementen zu ändern.
- Beispiel: Hinzufügen einer CSS-Klasse zu einem Element.
  ```JavaScript
  const element = document.getElementById('my-element');
  element.classList.add('neue-klasse');
  ```

#### 3.3.5. Ändern von HTML-Inhalten

- Definition: Das Aktualisieren des HTML-Inhalts eines Elements, einschließlich des Einsetzens neuer Elemente.
- Beispiel: Hinzufügen eines neuen Absatzes zu einem div-Element.
  ```JavaScript
  const container = document.getElementById('content-container');
  container.innerHTML = '<p>Neuer Absatz</p>';
  ```

#### 3.3.6. Erstellen und Hinzufügen neuer Elemente

- Definition: Das dynamische Erstellen von HTML-Elementen und das Hinzufügen zu einem Dokument.
- Beispiel: Erstellen eines neuen div-Elements und Hinzufügen zum Dokument.
  ```JavaScript
  const newDiv = document.createElement('div');
  newDiv.textContent = 'Neues Element';
  document.body.appendChild(newDiv);
  ```

#### 3.3.7. Entfernen von Elementen

- Definition: Das Entfernen von HTML-Elementen aus dem DOM.
- Beispiel: Entfernen eines bestimmten Elements aus dem Dokument.
  ```JavaScript
  const elementToRemove = document.getElementById('element-to-remove');
  elementToRemove.parentNode.removeChild(elementToRemove);
  ```
