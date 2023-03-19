# Zeichnen

In diesem Tab der Sidebar befinden sich alle Tools um auf der Karte Objekte einzufügen oder zu zeichnen.

## Zeichen Tools

![](../assets/img/draw-tool-container.png)


#### Bearbeiten

| Symbol                                   | Name       | Tastenkürzel |
|------------------------------------------|------------|--------------|
| ![](../assets/img/edit-move-tool.png)    | Bewegen    | M            |
| ![](../assets/img/edit-edit-tool.png)    | Bearbeiten | E            |
| ![](../assets/img/edit-cut-tool.png)     | Schneiden  | C            |
| ![](../assets/img/edit-bucket-tool.png)  | Einfärben  | F            |
| ![](../assets/img/edit-pipette-tool.png) | Pipette    | P            |
| ![](../assets/img/edit-remove-tool.png)  | Löschen    | ENTF         |
| ![](../assets/img/measure-tool.png)      | Messen     | H            |
| ![](../assets/img/edit-rotate-tool.png)  | Drehen     | B            |

#### Zeichnen

| Symbol                                           | Name           | Tastenkürzel |
|--------------------------------------------------|----------------|--------------|
| ![](../assets/img/draw-rectangle-tool.png)       | Rechteck       | R            |
| ![](../assets/img/draw-circle-tool.png)          | Kreis          | K            |
| ![](../assets/img/draw-circle-2x-tool.png)       | Kreis 2-Punkt  |              |
| ![](../assets/img/draw-circle-3x-tool.png)       | Kreis 3-Punkt  |              |
| ![](../assets/img/draw-gefahrgut-tool.png)       | Gefahrgutzonen | G            |
| ![](../assets/img/draw-distance-circle-tool.png) | Distanz Kreis  | I            |
| ![](../assets/img/draw-polygon-tool.png)         | Polygon        | N            |
| ![](../assets/img/draw-line-tool.png)            | Linie          | L            |
| ![](../assets/img/draw-distance-line-tool.png)   | Distanz Linie  | J            |
| ![](../assets/img/draw-arrow-tool.png)           | Pfeil          | A            |
| ![](../assets/img/draw-freehand-tool.png)        | Freihand       | D            |
| ![](../assets/img/draw-text-tool.png)            | Text           | T            |

Bei **Linie**, **Distanz Linie**, **Polygon**, **Rechteck**, **Pfeil** kann man während dem zeichnen **Shift** gedrückt halten, dann wird im **Ortho-Modus** gezeichnet.

#### Optionen

| Symbol                                                | Name             | Tastenkürzel | Beschreibung                                                                                      |
|-------------------------------------------------------|------------------|--------------|---------------------------------------------------------------------------------------------------|
| ![](../assets/img/draw-option-cancel.png)             | Abbrechen        | ESC          | Bricht das aktuelle Zeichnen ab oder beendet den Bearbeitungsmodus (ohne zurücksetzen).           |
| ![](../assets/img/draw-option-remove-last-vertex.png) | Schritt zurück   | Z            | Entfernt den zuletzt hinzugefügten Punkt einer Linie.                                             |
| ![](../assets/img/draw-option-finish.png)             | Fertig           | ENTER        | Speichert das gezeichnete Objekt.                                                                 |
| ![](../assets/img/draw-option-continure-drawing.png)  | Weiterzeichnen   | W            | Wenn aktiv kann weitergezeichnet werden, ansonsten wird der Zeichenmodus automatisch deaktiviert. |
| ![](../assets/img/draw-option-group-select.png)       | Gruppe auswählen | Y            | Die neu gezeichneten Objekte können automatisch einer Gruppe hinzugefügt werden.                  |
| ![](../assets/img/plus.png)                           | Gruppe erstellen |              | Neue Gruppe erstellen, bei welcher Objekte hinzugefügt werden können.                             |


## Farbauswahl

In der Farbauswahl kann die Füllfarbe und die Linienfarbe definiert werden, sowie weitere Optionen ausgewählt werden.

![](../assets/img/farbauswahl-container.png)

##### Vorschau

![](../assets/img/farbauswahl-vorschau.png)

 - Mit klick auf die (hintere) Vorschau, kann zwischen Linienfarbe und Füllfarbe gewechselt werden.
 - Über das *Verlinkungs*-Symbol wird die Füll- und Liniefarbe gleich gesetzt.
 - Über das *Wechsel*-Symbol kann die Farbe zwischen Füll- und Liniefarbe gewechselt werden.

##### Farbe speichern
![](../assets/img/plus.png)
 - Über das *Plus*-Symbol kann die aktuelle Farbe + Einstellungen als [Farbfeld](#funktionen-farbfelder) gespeichert werden. Nach dem Speichern kann der Name des Farbfelds im Reiter [Funktionen / Farbfelder](#funktionen-farbfelder) angepasst werden.

##### Optionen
![](../assets/img/farbauswahl-optionen.png)

 - Mit klick auf das *Schwarze-* / *Weiße-* Farbfeld, wird die aktuelle Farbe überschrieben.
 - Mit der Checkbox *Strichliert* kann die Linie des Objekts gestrichelt werden.
 - Über das *Farbcodefeld* wird die aktuelle Farbe als Hexidezimal-Code angezeigt und kann auch überschrieben werden.
 - Über den Slider kann die Stärke / Dicke der Linie definiert werden.

##### Muster
![](../assets/img/farbauswahl-muster.png)
 - Es können verschiedene Muster für die Füllung ausgewählt werden.

##### Funktionen / Farbfelder

In diesem Reiter können die vordefinierten oder eigene Farbfelder als aktuelle Farbe gesetzt werden. 

![](../assets/img/farbauswahl-farbfelder-funktionen.png)

Farbfelder können umbenannt oder gelöscht werden.

Es gibt auch vordefinierte Funktion:

| Funktion                            | Beschreibung                                                                                   |
|-------------------------------------|------------------------------------------------------------------------------------------------|
| B-Schlauch                          | Erstellt eine Linie, welche alle 20 Meter ein Label bekommt. ![](../assets/img/b-schlauch.png) |
| C-SChlauch                          | Erstellt eine Linie, welche alle 15 Meter ein Label bekommt. ![](../assets/img/c-schlauch.png) |
| Pumpen-Berechnung \| Relais Leitung | Berechnet die Pumpenstandorte einer Relaisleitung. (Nur in AT möglich) [mehr - TODO](#)        |

## Symbole

Es gibt verschiedene Symbol-Sets. Einige sind genormt andere sind selbst erstellt.

![](../assets/img/symbole-container.png)


In den [Einstellungen - TODO](#) oder über das *Zahnrad*-Symbol kann eingestellt werden, welche Symbol-Sets angezeigt werden sollen.

![](../assets/img/symbol-verwaltung-zeichnen-tab.png)

![](../assets/img/symbol-verwaltung-dialog.png)

## Vorlagen

Es können Vorlagen erstellt werden, damit Objekte mit nur einem Klick an der richtigen Stelle geladen werden können.


![](../assets/img/vorlagen-container.png)

| Symbol                               | Name       | Beschreibung                                                                     |
|--------------------------------------|------------|----------------------------------------------------------------------------------|
| ![](../assets/img/plus.png)          | Hinzufügen | Es wird die aktuelle Karte mit allen Objekten als Vorlage abgespeichert.         |
| ![](../assets/img/symbol-map.png)    | Platzieren | Die Objekte werden auf der Karte hinzugefügt.                                    |
| ![](../assets/img/symbol-edit.png)   | Bearbeiten | Es kann der Name und die 🔑 Sichtbarkeit (Benutzer / Organisation) geändert werden. |
| ![](../assets/img/symbol-cancel.png) | Löschen    | Die Vorlage wird gelöscht.                                                       |

### 🔑 Vorlage speichern / Berechtigung

Wenn man angemeldet ist, wird die Vorlage auf dem Benutzerkonto gespeichert. Es kann zusätzlich eingestellt werden, ob alle User aus der gleichen Organisation die Vorlage auch angzeigt bekommen.

![](../assets/img/vorlage-erstellen-dialog.png)
