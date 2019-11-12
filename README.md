# Phone company site
Projekt für Test im UI Modul

- Schreib das HTML und CSS für die abgebildete Seite
- Die Seite soll responsive sein und sich auf unterschiedlichen Bildschirmbreiten entsprechend der Abbildungen verhalten.

## Anforderungen HTML
- Die Seite soll auf dem Handy bzw. im DevTools-Simulator nicht kleiner skaliert/kleiner gezoomt werden.
- Einrückung der Kinder-Elemente im Code
- Korrekte Dateipfade
- Beschreibende Klassen- oder ID-Namen für Elemente vergeben
## Anforderungen CSS
- Selektoren so speizifisch schreiben, dass unabsichtliche Auswirkungen auf andere Teile der Seite vermieden werden.
- Kein float zum Anordnen von Block-Elementen
- Style-Werte, die sowieso standardmäßig vom Browser gesetzt werden, nicht im CSS deklarieren.

![](drafts/mobile.JPG)
![](drafts/tablet.JPG)
![](drafts/desktop.JPG)
![](drafts/desktop-button-hover.JPG)

###   25/60 Punkten
#### Punktabzüge für:
- [x] (25) Elemente passen sich nicht an Fensterbreite an
```
- Zusätzlich ist die Anordnung der Formularfelder in keiner Fensterbreite richtig
- In allen Fensterbreiten fehlt Abstand zwischen Text und linkem Fensterrand
```
- [x] (5) Tags nicht geschlossen oder falsch verschachtelt
```diff
- In UL fürfen nur LI stehen, da der Tag ausschließlich für Listen benutzt wird
```
- [_] (5) Block-Tag in Inline-Tag
- [_] (5) Kinder-Tags im Code nicht eingerückt
- [_] (10) Zweckfremde Tags verwendet
- [x] (5) Fehlende essetielle Tags (z.B. Meta-Tags)
```diff
- Um die Formularelemente fehlt ein form-Tag
```
- [_] (5) Falsche Datei-Pfade
- [_] (10) CSS-Selektoren, die bei Änderungen im HTML sehr leicht fehlschlagen können
- [_] (5) Fehlende essentielle Tag-Attribute
