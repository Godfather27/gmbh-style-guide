---
category: 'Methologien'
title: 'Dateistruktur'
---

In der Datei app.scss sollen allgemeine Sachen stehen.
In dieser sollen die zusätzlichen Dateien importiert werden, welche beim Buildprozess zusammengeführt werden.

Zusätzliche Dateien sind in Routen oder Komponenten gegliedert.

In den Dateien der Routen werden Hauptansichten definiert und Layout zwischen Komponenten definiert.
Layout und Design das Inhalt von Komponenten betreffen, befindet sich in der zugehörigen Komponentendatei.

## Beispiel:

### Routen:
- Route: /order
- Beschreibung: Bestellansicht für den Kellner
- Datei: order.scss

### Komponenten: 
- category-selection
- Beschreibung: Ist die Auswahl zwischen den verschieden Kategorien
- Datei: category-selection.scss
