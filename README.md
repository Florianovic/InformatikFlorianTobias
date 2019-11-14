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
Wir haben eine Arduino-Tutorial-Reihe auf YouTube gefunden und haben angefangen diese durchzuarbeiten.
https://www.youtube.com/watch?v=0wAY3DYihyg&list=PLAB63281B90FB376E
Wir haben eine LED zum leuchten gebracht, indem wir die Schaltung aus dem Video mehr oder weniger nachgebaut und das Sketch abgeschrieben haben. BILD UND ERLÄUTERUNG VON SKETCH UND SCHALTUNG

### 21.08.19
Da wir nur ein Arduino zur Verfügung hatten hat Tobias zunächst angefangen das Tutorial durchzuarbeiten.
Florian hat im Internet nach Programen recherchiert, mit denen man ein 3d Modell modellieren kann, da wir uns überlegt haben dass es cool wäre wenn wir unsere Box nach unseren Vorstellungen designen könnten und an die uns vorschwebenden Maße anpassen könnten.
Bei seiner Recherche ist er auf das Programm MatterControl gestoßen mit dem man sich kostenlos und einfach eine 3D Figur designen kann. Das Programm ist sehr übersichtlich und man kann seine Figur auf der Grundlage von einigen einfachen Formen modellieren.
Mit der Grundlage eines Würfels hat er begonnen:
![Mattercontol 1](https://raw.githubusercontent.com/Florianovic/InformatikFlorianTobias/master/Matterhackers%20W%C3%BCrfel.PNG)

Nachdem er sich etwas mit dem Programm vertraut gemacht hat, hat er angefangen die Kiste zu modellieren. Die Maße waren realitätsgleich in Zentimetern angegeben und er modellierte eine Kiste mit den Maßen: (kommt noch, ich muss mich grad über das Update freuen)


### 22.08.19
In der heutigen Stunde hat Florian die Box weiter modelliert und Kiste und Deckel separat gemacht. Die Idee war, die Box wie eine Art Maul zu machen aus dem eine Zunge kommt und den Schalter umlegt. Tobias hat unterdessen 


??weiter das Programm durchgearbeitet. Tobi was hast du da gemacht?

### 27.08.19
Florian hat den ersten 3D Entwurf fertig bearbeitet. Leider konnte das Projekt aus irgendeinem Grund nicht exportiert werden und somit keine druckbare Datei erstellt werden. Wir haben versucht das Problem mit Neustarten des Laptops und dem neuen Installieren des Programms zu lösen. Leider ohne Erfolg. Auch auf Tobias Laptop hat das Exportieren nicht funktioniert, woraufhin wir schlussfolgerten, dass das Programm einen Fehler haben musste.

### 28.08.19
Um unser Projekt der Useless-Box umzusetzen, haben wir heute im Technikschrank des Computerraums nach Komponenten gesucht, mit denen wir den Arm zum Betätigen des Kippschalters bewegen können. Wir haben einen Schrittmotor gefunden und uns im Internet einen Bauplan rausgesucht um ihn zu testen. Auch das Sketch haben wir übernommen aber aus irgendeinem Grund funktionierte es nicht.

### 29.08.19
Heute haben wir erneut probiert den Motor zum Laufen zu bekommen. Wir haben unsere Schaltung und unser Sketch noch einmal genau überprüft und keinen Fehler gefunden. Der Motor wurde warm und vibrierte leicht, bewegte sich aber nicht. Durch Zufall merkte Tobi, dass er sich verhakt hatte und nachdem er ihn per Hand ein Stück gedreht hatte lief er von alleine weiter, bis er nach zwei bis drei Durchläufen des Loops wieder hängen blieb. Wir haben noch einen zweiten Motor gefunden, den wir gegen den defekten austauschten und alles funktionierte einwandfrei.

### 11.09.19
Das einfache Ansteuern des Motors funktionierte nun. Um aber gezielt die Bewegung ausführen zu können, die wir für unser Projekt brauchten musste es uns gelingen die genaue Einstellung des Motors festzulegen. Die wollten wir durch den Einbau von Variablen erreichen. WAS IST DAS??

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

### 23.10.19
versuchen schalter einzubauen
Bauplan gesucht
komplett nachgebaut funzt

### 24.10.19
Geforkten Github Text mit beiden Accounts verbunden, weiter geschrieben
geschaut wie man Bilder einfügen kann

![Bauplan](https://github.com/Florianovic/InformatikFlorianTobias/blob/master/Bauplan.PNG)

pill down resistor?

### 29.10.19
Projektseite angefangen alla, Musterbeispiel angeschaut

### 05.11.19
Das Upsate für Mattercontrol wurde released, direkt gegönnt, bug is behoben, hart gefreut, Export funzt, online shop sacht 10000€

### 06.11.19
DER DURBRUCH! wir haben alle Komponenten zusamengefügt. Fern von allen Plänen und nur ufgrund undser bishergen Erfahrungen haben wir das Steckbrett verstanden (Teilung am 5V-Pin ist bullshit) stattdessen einfach + und - Spur am Steckbrett mit 5V und Grd vorbunden. Beide Servos an Strom angeschlossen und mit Arduino verbunden. Im scetch definiert und ausprobiert. FUNKTIONIERT!! Schalter dazugebaut mit Entladung durch Widerstand und auch in Scetch reingeschrieben. Ausprobiert und nach einigen Klamerfehlern ging es. Durch Schalter ließe sich beide Servos ansteuern und auch bei Stromversuorgung durch Baterie ha alls funktioniert. Das Grundgerüst ist fertig! ab jetzt alles in eine Kiste packen, Kram fertig schreiben, Scetch optimieren und fertig ist der Bums!

### 11.11.19 Zuahuse
Kiste gefunden und alle Komponenten eingebaut. In die Kiste zwei Löcher für die Schlter gebohrt, Steckbrett und Arduino rein, verkabeln, Servos rein und verkabeln, Akku rein und an Arduino anschließen, Schalter anschließen, alles rein, sodass es psst und feddich 

### 12.11.19
Box optimiert (Arm abgeschliffen) weil der Arm ab und zu abgerutscht ist
Website und Protokoll weiter geschrieben.
