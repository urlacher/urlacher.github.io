# Übungsaufgabe 02 - HTML

Ihre Webseite soll aus einer Home-Page/Landing Page (index.html) bestehen von welcher man durch Hyperlinks auf die anderen Webpages der Seite gelangt.

- [x] Erstellen Sie mindestens drei Seiten (inklusive der Landing Page), die miteinander verlinkt sind.
- [x] Erstellen Sie eine CSS-Datei, die eine rudimentäre visuelle Gestaltung der Website durchführt.
- [x] Webpages und das Style Sheet müssen mit relativen Links verlinkt sein.


## Zu verwendende HTML Elemente/Attribute

Diese Auflistung beschreibt die Mindestanforderung an HTML-Elementen, die Ihre Website beinhalten soll. Sie dürfen natürlich mehr Elemente inkludieren.

- [x] Mindestens zwei Unterschiedliche Überschriften.
- [x] Mindestens einen Paragraphen mit Text.
- [x] Mindestens ein Bild, dessen Breite sich mit der Größe des Browserfensters anpasst.
- [x] Bild als Link zu einer internen oder externen Seite
- [x] Mindestens ein externer Link der in einem neuen Tab/Fenster geöffnet wird
- [x] Eine verschachtelte Liste (mindestens zwei Ebenen) oder eine Tabelle
- [x] Ein iFrame oder eine Videodatei oder eine Audiodatei
- [x] div oder span
- [x] Mindestens zwei semantische Elemente
    * < header > : definiert eine Überschrift für ein Dokument oder einen Abschnitt.
    * < nav > : definiert einen Container für Navigationslinks.
    * < main >: für Inhalte, die nur auf dieser Seite verfügbar sind.
    * < section > : definiert einen Abschnitt in einem Dokument.
    * < article > : definiert einen unabhängigen, in sich geschlossenen Artikel.
    * < aside > : enthält Inhalte, die nicht in direktem Zusammenhang mit dem Hauptinhalt stehen, aber zusätzliche Informationen liefern
    * < footer > : definiert eine Fußzeile für ein Dokument oder einen Abschnitt.

Zusätzlich müssen folgende Attribute mindestens vorkommen:
- [x] Mindestens einmal das Attribut id.
- [x] Mindestens einmal das Attribut class.


## Zu verwendende CSS Eigenschaften

Erstellen Sie ein externes CSS-File (mystyle.css), welches die gesamte Style Information beinhaltet.
Es dürfen keine Style-Anweisungen im HTML File vorkommen. Diese Auflistung beschreibt die Mindestanforderung an CSS Elementen, die Ihr Stylesheet beinhalten soll. Sie dürfen natürlich mehr Elemente inkludieren

- [x] Benutzen Sie die Eigenschaften color bzw. background-color mindestens ein mal
- [x] Stellen Sie die Schriftfamilie für h1 bis h6 Überschriften auf Verdana um, mit jeder verfügbaren Sansserif-Schrift als Backup.
- [x] Setzen Sie die Schriftart für die Überschriften h1 bis h6 auf fett.
- [x] Setzt die Schriftfamilie für normalen Text im Text auf Georgia, mit beliebigen verfügbare Serifenschrift als Backup.


# Übungsaufgabe 03 - CSS

## Aufgabe
Erweitern Sie Ihre existierende Website um folgende Inhalte/Elemente:
- [ ] Versuchen Sie die Website möglichst barrierefrei zu machen durch z.B. kontrastreiche Farbkombinationen, Alternativ Text für Bilder,...
    - [ ] Kontrastreiche Frabkombinationen
    - [ ] Alternativ Text für Bilder
    - [ ] Alternativ Text für Videos
    - [ ] Relative Längeneinheiten
- [ ] Erstellen Sie ein Column Layout mit Hilfe von Flexbox welches folgende Teile beinhaltet:
    - [ ] Header
    - [ ] Navigationbar (ohne Dropdown Menü)
    - [ ] Content im Column Layout (mindestens auf einer Seite 2-Columns)
- [ ] Verwenden Sie mindestens einmal einen Selektor Combinator
    * **descendant selector (space)** 
    `div p { background-color: silver; }` # Alle Paragraphen p in div
    * **child selector (>)**
    `div>p { color: red; }` # Alle p in die direkt in div liegen
    * **adjacent sibling selector (+)**
    `div+p { background-color: powderblue; }` # An div angrenzender Paragraph p in
    * **general sibling selector (~)**
    `div~p { color: purple; }` # Alle p die div folgen
- [ ] Verwenden Sie mindestens einmal die Eigenschaft position
    * **static** 
        ➤ HTML-Elemente werden standardmäßig statisch positioniert.
        ➤ Element wird entsprechend dem normalen Seitenfluss positioniert
        ➤ Statisch positionierte Elemente werden von den Eigenschaften top, down, left und right nicht beeinflusst.
    * **relative**
        ➤ Element wird relativ zu seiner normalen Position positioniert.
        ➤ top, down, left und right definieren wie das Element im Bezug steht zu seiner normalen Position
        ➤ Andere Inhalte werden nicht so angepasst, dass sie in eine vom Element hinterlassene Lücke passen.
    * **fixed**
        ➤ ist relativ zum Ansichtsfenster positioniert, d.h. es bleibt immer an der gleichen Stelle, auch wenn die Seite gescrollt wird.
        ➤ fixiertes Element hinterlässt keine Lücke auf der Seite, auf der es sich normalerweise befinden würde.
    * **absolute**
        ➤ wird relativ zum nächstgelegenen positionierten Vorgänger positioniert (anstatt relativ zum Ansichtsfenster, wie fixed).
        ➤ “positionierter" Vorgänger: Element dessen Position nicht static ist
        ➤ Wenn kein positionierter Vorgänger: dann ist der Dokumentenkörper der Vorgänger und das Element bewegt sich beim Blättern der Seite mit.
    * **sticky**
        ➤ Position eines Elements mit Position sticky basierend auf der Scrollposition
        ➤ Schaltet je nach Scrollposition zwischen relative und fixed
        ➤ relative positioniert bis eine gegebene Offsetposition im Ansichtsfenster erreicht ist
        ➤ fixed danach




### WC3 konforme HTML/CSS-Dateien

Überprüfen Sie vor der Abgabe Ihre Website, dass die HTML und CSS Dokumente valide 1 sind.
Verwenden Sie hierfür folgende Validators (file upload):
- [ ] HTML: (https://validator.w3.org/)  
Character Encoding: (detect automatically)\
Document Type: (detect automatically)

- [ ] "CSS:" (http://jigsaw.w3.org/css-validator/)  
Profile: CSS Level 3\
Medium: All\
Warnings: Normal report\
Vendor Extensions: Default
