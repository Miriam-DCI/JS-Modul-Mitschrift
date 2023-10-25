## 2.7. Ereignisse und Event-Handling

Inhaltsverzeichnis:

- [Ereignisse und Event-Handler](#ereignisse-und-event-handler)
- [HTML-Ereignisattribute](#html-ereignisattribute)
- [Event-Objekt](#event-objekt)
- [Event-Delegation](#event-delegation)
- [Häufig verwendete Ereignisse](#häufig-verwendete-ereignisse)
- [Event-Handling-Praxis](#event-handling-praxis)

### Ereignisse und Event-Handler

- Ereignisse (Events): Ereignisse sind Aktionen oder Zustandsänderungen, die in einer Webanwendung auftreten können, wie z.B. Mausklicks, Tastatureingaben oder das Laden einer Seite.
- Event-Handler: Event-Handler sind JavaScript-Funktionen, die aufgerufen werden, um auf ein bestimmtes Ereignis zu reagieren. Wir werden sehen, wie sie in HTML und JavaScript eingesetzt werden.
- Beispiel: Ein Klick-Ereignis, das ein Pop-up-Fenster öffnet.

### HTML-Ereignisattribute

- HTML-Attribute: In HTML können Ereignisse mit Attributen wie `onclick`, `onmouseover`, usw. definiert werden. Diese Attribute weisen den Event-Handler-Funktionen zu.
- Beispiel: Verwendung des `onclick`-Attributs, um eine Bildergalerie zu durchsuchen.

### Event-Objekt

- Event-Objekt: Das Event-Objekt enthält Informationen über das ausgelöste Ereignis. Wir werden sehen, wie wir auf diese Informationen zugreifen und sie in unserer Event-Handler-Funktion verwenden können.
- Beispiel: Verwendung des Event-Objekts, um die Mausposition bei einem Klick zu ermitteln.

### Event-Delegation

- Event-Delegation: Dieses Konzept ermöglicht es, Event-Handler nicht direkt an einzelne Elemente zu binden, sondern an übergeordnete Container. Wir werden verstehen, warum dies nützlich sein kann.
- Beispiel: Delegation von Klick-Ereignissen für Elemente in einer Liste.

### Häufig verwendete Ereignisse

- Wir werden uns einige häufig verwendete Ereignisse ansehen, wie beispielsweise Mausereignisse (`click`, `mouseover`, `mouseout`), Tastaturereignisse (`keydown`, `keyup`) und das Laden der Seite (`load`).
- Beispiel: Verwendung des `keydown`-Ereignisses, um auf Benutzereingaben zu reagieren.

### Event-Handling-Praxis

- In diesem Abschnitt werden wir praktische Beispiele durchgehen, die zeigen, wie Ereignisbehandlung in realen Webanwendungen eingesetzt wird.
- Beispiel: Ein Formular mit Validierungslogik und Submit-Handling.
