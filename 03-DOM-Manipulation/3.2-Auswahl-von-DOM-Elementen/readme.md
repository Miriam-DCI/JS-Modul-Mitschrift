### 3.2. Auswahl von DOM-Elementen

Inhaltsverzeichnis:

- [getElementById-Methode](#getelementbyid-methode)
- [getElementsByClassName-Methode](#getelementsbyclassname-methode)
- [getElementsByTagName-Methode](#getelementsbytagname-methode)
- [querySelector-Methode](#queryselector-methode)
- [querySelectorAll-Methode](#queryselectorall-methode)
- [Referenz auf Elternelemente und Kinder](#referenz-auf-elternelemente-und-kinder)

#### 3.2.1. getElementById-Methode

- Definition: Diese Methode ermöglicht den Zugriff auf ein Element anhand seiner eindeutigen ID.
- Beispiel: Abrufen eines HTML-Elements mit einer bestimmten ID und Ändern des Inhalts.
  ```JavaScript
  const header = document.getElementById('header');
  header.textContent = 'Neuer Header-Text';
  ```

#### 3.2.2. getElementsByClassName-Methode

- Definition: Mit dieser Methode können Elemente anhand ihrer Klasse ausgewählt werden.
- Beispiel: Auswahl aller Elemente mit einer bestimmten Klasse und Anwendung von Änderungen.
  ```JavaScript
  const elements = document.getElementsByClassName('box');
  for (const element of elements) {
    element.style.backgroundColor = 'lightblue';
  }
  ```

#### 3.2.3. getElementsByTagName-Methode

- Definition: Diese Methode ermöglicht die Auswahl von Elementen anhand ihres HTML-Tags.
- Beispiel: Abrufen von Elementen, die denselben HTML-Tag verwenden, und Anwenden von Aktionen.
  ```JavaScript
  const paragraphs = document.getElementsByTagName('p');
  for (const paragraph of paragraphs) {
    paragraph.style.fontWeight = 'bold';
  }
  ```

#### 3.2.4. querySelector-Methode

- Definition: Diese Methode ermöglicht die Auswahl von Elementen anhand von CSS-Selektoren.
- Beispiel: Verwendung von CSS-Selektoren zur Auswahl und Modifikation von Elementen.
  ```JavaScript
  const firstElement = document.querySelector('.box:first-of-type');
  firstElement.style.border = '2px solid red';
  ```

#### 3.2.5. querySelectorAll-Methode

- Definition: Mit dieser Methode können mehrere Elemente anhand von CSS-Selektoren ausgewählt werden.
- Beispiel: Auswahl mehrerer Elemente und Anwendung von Änderungen.
  ```JavaScript
  const listItems = document.querySelectorAll('ul#myList li');
  listItems.forEach(item => item.style.color = 'green';
  ```

#### 3.2.6. Referenz auf Elternelemente und Kinder

- Definition: Hier lernen wir, wie man von einem Element zu seinen Eltern- oder Kinderelementen navigiert.
- Beispiel: Navigieren durch die Elementstruktur, um bestimmte Elemente zu finden und anzupassen.
  ```JavaScript
   const childElement = document.querySelector('.child');
   const parentElement = childElement.parentElement;
   const firstChild = parentElement.firstElementChild;
  ```
