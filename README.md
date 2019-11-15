# InformatikFlorianTobias

## Stundenprotokolle

### 13.08.19
In unserer allerersten Informatikstunde hat Herr Buhl uns erzählt, wie der Unterricht mit ich allgemein ablaufen wird. Die Schüler sollen sich zusammentun und in Zweiergruppen an einem Halbjahresprojekt arbeiten. Was das für ein Projekt sein soll darf sich jeder frei aussuchen. Wichtig ist nur, dass am Ergebnis eine eigenständige informatische Leistung zu erkennen ist und diese anhand von Stundenprotokollen erkennbar ist, die wir auf der Seite GitHub schreiben. Es ist mehr eigenständiges Arbeiten und autodidaktisches Lernen als Unterricht. Herr Buhl steht zwar immer für Fragen bereit aber unser Wissen sollen wir uns selbst über das Internet, Texte und Tutorials holen.
Als Inspiration wurde uns eine Reihe von Projekten aus dem letzten Jahr gezeigt. Zu jedem Projekt gehört auch eine Projektseite auf der das Projekt vorgestellt und die Funktionsweise erläutert wird.
Wir (Florian und Tobias) haben uns in der ersten Stunde die Projektseiten des letzten Informatikkurses angeschaut. Es gab neben einigen Computerspielen auch die Möglichkeit eine Steuerplatine zu programmieren mit der man Motoren, Servos und LEDs ansteuern kann. Das fanden wir beide sehr interessant und wollten auch etwas damit machen.


### 14.08.19
In unserer zweiten Informatikstunde haben wir uns jeder einen GitHub-Account erstellt und erste Erfahrungen mit dem Programm gemacht. Wir haben ein Tutorial geschaut, konnten aber aufgrund der Lautstärke im Raum kein Wort von dem Gesprochenen verstehen und haben uns von Herrn Buhl zeigen lassen wie man eine Datei erstellt und haben angefangen unseren Stundenblog zu schreiben.

### 15.08.19
In dieser Stunde haben wir uns überlegt, was wir für ein Projekt mit der Steuerplatine, dem „Arduino“ machen könnten. Tobi hatte die Idee eine „Useless-Box“ (nutzlose Box) zu bauen. Eine Kiste mit einem Kippschalter, welche sich beim Umlegen des Schalters öffnet und ihn mit einem Roboterarm wieder auf die Ausgangsposition stellt. Ein endloser Kampf von Mensch gegen Maschine! 
Von Herrn Buhl bekamen wir eine Arduino-Platine. Um diese zu programmieren muss man sie an einen PC anschließen und mit einer dort installierten Software den programmierten Code, den „Sketch“ auf den Arduino übertragen. Wir haben uns in dieser Stunde beide die Arduino-Software aus dem Internet auf unsere Laptops geladen und auf YouTube nach einem Tutorial gesucht.

### 20.08.19
Wir haben eine <a href="https://www.youtube.com/watch?v=0wAY3DYihyg&list=PLAB63281B90FB376E" rel="notfollow">Arduino-Tutorial-Reihe</a> auf YouTube gefunden und haben angefangen diese durchzuarbeiten.

Wir haben eine LED zum leuchten gebracht, indem wir die Schaltung aus dem Video mehr oder weniger nachgebaut und das Sketch abgeschrieben haben. BILD UND ERLÄUTERUNG VON SKETCH UND SCHALTUNG#

![LED Sketch](https://github.com/Florianovic/InformatikFlorianTobias/blob/master/LED%20Sketch.PNG)

![LED](https://github.com/Florianovic/InformatikFlorianTobias/blob/master/simple%20Schaltung%20LED.JPG)

### 21.08.19
Da wir nur ein Arduino zur Verfügung hatten hat Tobias zunächst angefangen ein weiteres <a href="https://funduino.de/anleitung" rel="notfollow">Tutorial</a> durchzuarbeiten.
Florian hat im Internet nach Programen recherchiert, mit denen man ein 3d Modell modellieren kann, da wir uns überlegt haben dass es cool wäre wenn wir unsere Box nach unseren Vorstellungen designen könnten und an die uns vorschwebenden Maße anpassen könnten.
Bei seiner Recherche ist er auf das Programm MatterControl gestoßen mit dem man sich kostenlos und einfach eine 3D Figur designen kann. Das Programm ist sehr übersichtlich und man kann seine Figur auf der Grundlage von einigen einfachen Formen modellieren.
Mit der Grundlage eines Würfels hat er begonnen:

![Mattercontol 1](https://raw.githubusercontent.com/Florianovic/InformatikFlorianTobias/master/Matterhackers%20W%C3%BCrfel.PNG)

Nachdem er sich etwas mit dem Programm vertraut gemacht hat, hat er angefangen die Kiste zu modellieren. Die Maße waren realitätsgleich in Zentimetern angegeben.

![MChohl](https://github.com/Florianovic/InformatikFlorianTobias/blob/master/Matterhackers%20hohle%20Kiste.PNG)


### 22.08.19
In der heutigen Stunde hat Florian die Box weiter modelliert und Kiste und Deckel separat gemacht. Die Idee war, die Box wie eine Art Maul zu machen aus dem eine Zunge kommt und den Schalter umlegt. Tobias hat unterdessen weiter das <a href="https://funduino.de/anleitung" rel="notfollow">Tutorial</a> durchgearbeitet.

### 27.08.19
Florian hat den ersten 3D Entwurf fertig bearbeitet. Leider konnte das Projekt aus irgendeinem Grund nicht exportiert werden und somit keine druckbare Datei erstellt werden. Wir haben versucht das Problem mit Neustarten des Laptops und dem neuen Installieren des Programms zu lösen. Leider ohne Erfolg. Auch auf Tobias Laptop hat das Exportieren nicht funktioniert, woraufhin wir schlussfolgerten, dass das Programm einen Fehler haben musste.

### 28.08.19
Um unser Projekt der Useless-Box umzusetzen, haben wir heute im Technikschrank des Computerraums nach Komponenten gesucht, mit denen wir den Arm zum Betätigen des Kippschalters bewegen können. Wir haben einen Schrittmotor gefunden und uns im Internet einen Bauplan rausgesucht um ihn zu testen. Auch das Sketch haben wir übernommen aber aus irgendeinem Grund funktionierte es nicht.

### 29.08.19
Heute haben wir erneut probiert den Motor zum Laufen zu bekommen. Wir haben unsere Schaltung und unser Sketch noch einmal genau überprüft und keinen Fehler gefunden. Der Motor wurde warm und vibrierte leicht, bewegte sich aber nicht. Durch Zufall merkte Tobi, dass er sich verhakt hatte und nachdem er ihn per Hand ein Stück gedreht hatte lief er von alleine weiter, bis er nach zwei bis drei Durchläufen des Loops wieder hängen blieb. Wir haben noch einen zweiten Motor gefunden, den wir gegen den defekten austauschten und alles funktionierte einwandfrei.

### 11.09.19
Das einfache Ansteuern des Motors funktionierte nun. Um das Ansteuern zu vereinfachen haben wir, auf Anraten von Herrn Buhl, versucht Variablen in den Code einzuarbeiten. Diese sollen bewirken, dass einzelne Schritte des Motors vereinfacht werden und das Skript generell übersichtlicher wird. Leider hat dies nicht ganz funktioniert, wir werden es in der nächsten Stunde noch einmal versuchen.

### 12.09.19
Wir haben heute versucht zwei Motoren an unser Arduino anzuschließen, da wir für unser Projekt neben dem Arm der den Schalter betätigt auch einen Motor brauchen, der den Deckel der Kiste öffnet. Dabei stießen wir auf ein Problem. Der 5Volt Pin am Arduino war nur einmal vorhanden, doch da beide Motoren von ihm Strom beziehen mussten, mussten wir einen weg finden zwei Kabel in den einen Pin zu bekommen.

### 24.09.19
Da wir nun auch mit den Motoren erstmal feststeckten, haben wir uns wieder dem Problem mit dem 3d-Programm zugewendet. Das Exportieren der Datei war immer noch nicht möglich, weshalb wir im Internet nach einer Lösung suchten. Florian stieß dabei auf ein Forum in dem mehrere das gleiche Problem hatten. Einer der Entwickler des Programms hatte darauf geantwortet, dass dieses Problem bekannt sei und es mit dem nächsten Update behoben werden soll. Wir hofften, dass das Update noch vor Abgabe unseres Projekts herauskommen würde.

### 25.09.19 
Da bisher bei allen Teilen für unsere Useless-Box Probleme aufgetaucht waren, haben wir uns heute die letzte Komponente für unser Projekt vorgenommen, die noch fehlte. Den Schalter. Dazu haben wir uns das YouTube Video aus der Arduino-Playlist angeschaut und versucht es nachzubauen. Das ist allerdings auch sofort gescheitert, da es nicht möglich war den Schalter an die vorgesehene Stelle zu platzieren, da unser Steckbrett zu groß war. Wir haben uns überlegt, was wir an die Schrittmotoren bauen könnten um den Schalter auszulösen und kamen zu dem Schluss, dass Servos für diese Aufgabe deutlich besser geeignet waren.
  
### 29.09.19
Aus einem früheren Projekt war ein Roboterarm im Technikschrank in dem mehrere Servos verbaut waren. Nachdem wir uns ein Tutorial für Servos am Arduino angesehen haben, steckten wir die drei Kabel des Servos in 5V, Grd und einen PWM-Pin. Mit einem im Arduino-Programm gespeicherten Sketch haben wir sie angesteuert. Das Ausbauen der Servos wäre allerdings etwas schwierig geworden und da wir uns ohnehin überlegt haben, dass es schade wäre, wenn wir unsere fertige Useless-Box nicht behalten könnten, wollten wir uns die Komponenten selber kaufen. 

### 22.10.19
Da Florians Vater Modellflugzeuge baut und ein paar Servos hatte, reichte ein kleiner Einkauf bei Conradelektronik um einen Arduino, ein paar Kabel, Steckbrett und Schalter zu besorgen. Wir fanden einen Bauplan Bauplan für eine Uselsee-Box im Internet, mit dem wir versuchten alle Komponenten einmal zu verbinden und deren Zusammenspiel somit zu verstehen. Bis auf die an- und abschaltbare Stromquelle bauten wir es nach.

![Bauplan](https://github.com/Florianovic/InformatikFlorianTobias/blob/master/Bauplan.PNG)

### 23.10.19
Da wir alles blind übernommen hatten, und es funktionierte, machten wir uns nun daran das ganze zu verstehen. Da hier beide Servos mit Strom versorgt wurden aber nur ein Kabel aus dem 5V-Pin kam wurde uns klar, dass man die Verteilung des Stroms natürlich über das Steckbrett machen kann. Nach näherer Auseinandersetzung mit der Funktionsweise eines Steckbretts wurde uns klar, dass es einfach ausreichen würde 5V mit der Plus-Spur und Grd mit der Minus-Spur zu verbinden und von dort aus alle Komponenten anzuschließen. Aus dem Sketch wurden wir jedoch absolut nicht schlau. Da alle Randbemerkungen aus asiatischen Schriftzeichen bestanden und das Sketch allgemein so lang war, dass wir komplett den Überblick verloren, gaben wir auf und versuchten erneut die einzelnen Komponenten zu verstehen.


### 24.10.19
Florian schaute sich noch einmal das Tutorial aus der Playlist für Schalter an und übertrug es auf unseren Kippschalter.

![Schalter YT](https://github.com/Florianovic/InformatikFlorianTobias/blob/master/Schalter%20Vorlage%20YT.JPG)

Er baute eine Schaltung mit der man mit Hilfe eines Schalters eine LED an und wieder ausstellt. Dabei war wichtig, dass zwischen der Verbindung vom Schalter und dem Arduino  noch ein Widerstand geschaltet wird, der sog. „pull-down-resistor“, welcher im Schalter-Tutorial erwähnt wurde und von dem uns Herr Buhl erzählt hat. Er ist notwendig um die Restspannung vom Schalter nach der Trennung der Stromverbindung verschwinden zu lassen und führt dabei in die Grd-Spur. Auch der Sketch mit der If-Bedingung schien mit einem Mal ganz logisch. 

![Nachbau](https://github.com/Florianovic/InformatikFlorianTobias/blob/master/Schalter%20mit%20LED.JPG)

![Schalter Sketch](https://github.com/Florianovic/InformatikFlorianTobias/blob/master/Schalter%20Test%20sketch.JPG)

Plötzlich wurde uns klar, dass wir ganz kurz vor dem Ziel standen. Eine ganz einfache Useless-Box zu bauen, die sich ganz einfach immer auf dieselbe Art und Weise ausschaltet. All diese komplizierten Dinge aus dem asiatischen Sketch und die komplizierte Schaltung waren eigentlich total unnötig für das was wir wollten. Wir brauchten keine LED oder eine komplizierte Stromversorgung über das Steckbrett.
Wir mussten einfach nur den Strom vom Akku zum Arduino mit dem ersten Schalter regeln, 5V und Grd mit dem Steckbrett verbinden und dort beide Servos und den Schalter anschließen und mit jeweils einem Kabel zum Arduino führen. Mehr nicht!

### 29.10.19
Heute ist uns aufgefallen, dass wir noch gar keine Projektseite angefangen haben. Wir haben uns nochmal ein Musterbeispiel vom letzten Informatikkurs angesehen und unsere eigene angelegt. Das hat uns sp viel Zeit gekostet, dass wir es gar nicht mehr geschafft haben unseren Plan auszuprobieren.

### 05.11.19
Wir haben es sofort installiert und die Exportfunktion ausprobiert. Es hat funktioniert und wir haben uns übertrieben gefreut.

![Update](https://github.com/Florianovic/InformatikFlorianTobias/blob/master/UPDATE%20ALLAAAAAH.PNG)

Wir suchten einen online-3D-Druck-Shop raus und importierten unsere Datei. Leider musste man sich dafür erst wieder einen Account erstellen und das hat uns einige Zeit gekostet. Als wir dann soweit waren und das Material für unseren druck aussuchen konnten waren wir völlig entsetzt. Die Preisliste sah nämlich so aus:

![Preisliste](https://github.com/Florianovic/InformatikFlorianTobias/blob/master/Brutalste%20Preisliste.PNG)

### 06.11.19
Da wir den Blödsinn mit dem 3D-Druck nun vergessen konnten, fingen wir an unsere Schaltung zu bauen. Als externe Stromversorgung hatte Florian von seinem Vater einen 7.4V Lipo-Akku mitgebracht. Das dazugehörige Adapterkabel für den Arduino hatte er auch bei Conrad gekauft und in das Kabel den ersten Schalter eingelötet. Damit war für die externe Stromversorgung gesogt. Wir haben den 5V Pin des Arduinos nun mit der Plus-Spur des Steckbretts und Grd mit der Minus-Spur verbunden. Anschließend haben wir die Servos an den Strom angeschlossen, indem wir das Braune Kabel mit der Grd-Spur und das rote mit der 5V-Spur verbunden haben. Das Steuerkabel ging dann jeweils in einen PWN-Pin, in diesem Falle in 10 und 11. Der Schalter ging mit einem ende in 5V und mit dem anderen in PIN 13. Dazwischen wieder den Pull-down-resistor.

![fertige Schaltung ganz](https://github.com/Florianovic/InformatikFlorianTobias/blob/master/fertige%20Schaltung%20ganz.JPG)

Der Aufbau war nun fertig, also mussten wir das Sketch schreiben. Wir fingen mit der Servo-Zeile und der Definition des Schalters an. Wir legten die Namen der Servos fest und nannten die Pins im Setup-Teil wobei wir den Schalter als Input-Komponente festlegten, da von ihm aus ja der Schalterzustand abgelesen werden soll. Im Loop-Teil bauten wir dann ganz einfach eine If-Bedingung ein für „buttonPin High“ mit Gradzahlen für beide Servos und „else“ mit anderen Gradzahlen für Beide ein. Dann hatten wir einen zustand für die Servos in beiden Fällen des Schalterzustandes. Nachdem wir noch einige Klammerfehler beheben mussten konnten wir den Sketch auf den Arduino laden und siehe da, es hat funktioniert!!! 

![fertig Sketch](https://github.com/Florianovic/InformatikFlorianTobias/blob/master/Fertiger%20Sketch.PNG)
(dies ist das bereits optimierte Sketch, das Vorherige hatte etwas andere Gradzahlen)


### 11.11.19 Zuahuse
Florian hat zuhause eine Kiste gesucht und zwei Löcher für die Schalter gebohrt. Danach alle Komponenten eingebaut und an beide Servos Holzstücke angebaut. Eine Verlängerung um den Deckel zu öffnen und einen runden Arm um den Schalter zu betätigen. 

![Roboterarme](https://github.com/Florianovic/InformatikFlorianTobias/blob/master/Roboterarme.JPG)

Danach hat er das Sketch so angepasst, dass erst der Deckel aufgeht, dann nach einem delay von 500 der Arm ausfährt und nach Betätigen des Schalters in umgekehrter Reihenfolge in den Anfangszustand geht. Damit war unsere Useless-Box fertig.

![Boxbau1](https://github.com/Florianovic/InformatikFlorianTobias/blob/master/Box%20einbauen.JPG)

![Boxbau fertig](https://github.com/Florianovic/InformatikFlorianTobias/blob/master/feritige%20Box%20Prototyp.JPG)


### 12.11.19
Heute haben wir noch einige Ausbesserungen vorgenommen, da beispielsweise der Arm für den Schalter hüufig abgerutscht ist.
Zuhause hat Florian das Adapterkabel noch etwas gekürzt un einen kleineren Servo für den deckel genommen um etwas Platz zu sparen, da aufgrund der vielen Kabel der deckel oft nicht richtig zu ging. Ebenfalls hat er ein Stück Blei in den Deckel geklebt damit er richtig schließt und einen kleinen Stoffwurm auf den Schalter-Arm geklebt. Als lustige Überraschung, der Holzwurm in der Kiste. Damit war die Useless-Box endgültig fertig.
