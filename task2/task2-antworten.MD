# Das ist eine Wiederholung der objektorientierten Konzepte.

Bitte versuche als Übung alles in Markdown zu beantworten. Hier ist ein [Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

1. Was ist das Ziel der Objektorientierung?
 * OOP hat gegenüber der prozedualen Programmierung mehrerer Vorteile z.B: bietet eine klare Struktur für Programme; es wird die Wiederholung von Codes reduziert; erleichtert das Verwalten, Ändern und Debuggen eines Codes; ermöglicht die Erstellung vollständig wiederverwendbarer Anwendungen; 
 OOP bedeutet das Programm in viele kleine Teilbereiche zu zerlegen, die man separat bearbeiten und später wieder zusammenpassen kann.
 
2. Gibt es OOP nur in Java?
 * Nein, OOP gibt es auch in z.B. Python, C++, Visual Basic .NET,  Ruby, ...

3. Was ist der Unterschied zwischen Objekt und Klasse?
 * Eine Klasse ist eine Vorlage für ein Objekt - ein Objekt ist eine Instanz einer Klasse.
 Die Klasse stellt die Bauanleitung für ein Objekt dar - Java sieht vor, dass der Klassenname auch gleich der Dateiname ist.

4. Wie erzeuge ich eine neue Instanz? (Welches Schlüsselwort gibt es dafür)
 * Das Objekt muss erst einmal mit "new" erstellt werden.

5. Was bedeutet das Schlüsselwort `static` und wo kann es überall verwendet werden?
 * static ist objektunabhängig; Die Attribute und Methoden gehören zur Klasse, nicht zu einem Objekt!

6. Wozu dient die Vererbung?
 * zur Codewiederverwendung - Verwendung von Attributen und Methoden einer vorhandenen Klasse, wenn eine neue Klasse erstellt wird!

7. Kann in Java von mehreren Klassen geerbt werden? Wenn ja wie?
 * Das Konzept der Vererbung ist in Java auf Einfachvererbung begrenzt, d.h. eine neue Klasse kann max von einer andere Klasse abgeleitet werden. 

8. Welche Vererbungshierarchien kennst du? (Ein Bild reicht aus)
  * Subklasse (Kindklasse, Unterklasse, Childklasse) - Die Klasse, die von einer anderen Klasse erbt; (Spezialisierung der Basisklasse)
  Superklasse (Elternklasse, Basisklasse, Oberklasse) - die Klasse, von der geerbt wird; (übergeordnet)
  Schlüsselwort "extends" um von einer Klasse zu erben!
  Bsp: Säugetier - Mensch - Fuß

9. Was bedeutet Casten und wie ist die Syntax in Java dafür?
  * Casten = Typecasting = Typumwandlung: Umwandlung eines Datentyps in einen anderen primitiven Datentyp.
Bsp. implizite Casten: int wert = 10; long wert2 = 20; wert2 = wert;
Bsp. explizite Casten: int wert = 10; float wert2 = 20; wert = (int) wert2;

10. Was ist der Unterschied zwischen explizieten und implizieten Typecasting?
 * Die implizite Typumwandlung (Typecasting) findet automatisch bei der Zuweisung statt (geht nur von einem niederwertigen Datentyp in einen höherwertigen Datentyp z.b.
 von int in long) 
Die explizite Typumwandlung (Typecasting) erfolgt durch einen sogenannten cast-Operator. Hier wird von einem höherwertigen Datentyp in einen niederwertigen
Datentyp umgewandelt - hier muss dem cast Operator explizit der Datentyp angegeben werden. 

11. Erkläre die folgenden Schlüsselwörter: `super`, `this`
 * super: bezieht sich auf die Objekte der Oberklasse - wird verwendet um Methoden der Oberklasse aufzurufen und auf den Konstruktor der Oberklasse zuzugreifen.
 this: Referenzierung auf die aktuelle Instanz der Klasse in der man sich gerade befindet; über this kann auf alle Variable und Methoden der Instanz zugegriffen werden.
 
12. Für was dient der `instanceof` Operator. Gib ein sinnvolles Beispiel.
 * instanceof prüft, ob ein Objekt eine Instanz einer bestimmten Klasse ist. Der Rückgabewert ist etweder true oder false.
 ---
 Eclipse bietet auch Markdown unterstützung inklusive Preview. Für die Verwendung muss kein Plugin installiert werden.
