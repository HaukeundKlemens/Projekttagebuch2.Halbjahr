# Projekttagebuch 2. Halbjahr

[Mittwoch, 11. Januar 2023](#1)

[Dienstag, 17. Januar 2023](#2)

[Mittwoch, 18. Januar 2023](#3)

[Dienstag, 24. Januar 2023](#4)

[Mittwoch, 25. Januar 2023](#5)

[Dienstag, 31. Januar 2023](#6)

[Mittwoch, 1. Februar 2023](#7)

[Mittwoch, 8. Februar 2023](#8)

[Freitag, 10. Februar 2023](#9)

[Mittwoch, 15. Februar 2023](#10)

[Mittwoch, 22. Februar 2023](#11)

[Freitag, 24. Februar 2023](#12)

[Mittwoch, 1. März 2023](#13)

[Freitag, 3. März 2023](#14)

[Mittwoch, 8. März 2023](#15)

[Freitag, 10. März 2023](#16)

[Mittwoch, 15. März 2023](#17)

[Freitag, 17. März 2023](#18)

[Freitag, 24. März 2023](#19)





### <a name="1"></a>Mittwoch, 11. Januar 2023
Heute habe ich damit angefangen, an dem neuen Greenfootprojekt zu arbeiten. Es so soll wahrscheinlich ein Dame Spiel werden. Dazu habe ich schon die vier Spielfiguren gepixelt und das Schachbrett eingefügt.
![image](https://user-images.githubusercontent.com/111414678/211747398-fd8f5111-25e3-4922-9c60-048833a04172.png)

https://www.youtube.com/watch?v=09SViWwRepE

### <a name="2"></a>Dienstag, 17. Januar 2023
Heute habe ich nach einer Methode gesucht,um einen einzelnen Actor aus einer Klasse mit mehreren Einheiten von den anderen Einheiten abzuheben. Das war bisher ohne Erfolg.
Ich habe außerdem einen simplen Bewegungscode eingefügt.
Vielleicht könnte man das über Knöpfe lösen.

### <a name="3"></a>Mittwoch, 18. Januar 2023
In der heutigen Stunde haben wir uns dazu entschieden, doch das Spiel "Schaf und Wolf" zu programmieren. Dazu haben wir schonmal damit angefangen, die Bewegungen für die Spielfiguren einzustellen. Dabei haben wir uns entschieden, dem Wolf die Tasten QWAS und den vier Schafen jeweils ER, TZ, UI und OP für linksoben und rechtsoben zu geben.

### <a name="4"></a>Dienstag, 24. Januar 2023
Wir haben es heute geschafft, dass alle 4 Schafssteine jeweils den Wolf töten, wenn diese auf dem selben Spielfeld stehen. Nächste Stunde wollen wir dann einen Win-Screen für den Wolf erschaffen, der aktiviert wird, wenn dieser auf der obersten Reihe schwarzer Felder steht. Dafür haben wir schon mal schwarze Striche als Actor hinzugefügt, der den Wolf quasi töten soll.
![image](https://user-images.githubusercontent.com/111414678/214286973-ae73ed0b-8841-4400-9360-3f6373477ef0.png)

### <a name="5"></a>Mittwoch, 25. Januar 2023
Heute haben wir zuerst mit Pixelart unsere Spielsteine bearbeitet, sodass man auf ihnen die Tasten erkennen kann, mit welchen man sie steuern kann. Danach haben wir angefangen, ein Win-Screen zu machen. Das hat noch nicht geklappt und wir müssen das Problem nächste Stunde lösen.
![image](https://user-images.githubusercontent.com/111414678/214513105-2148314c-99e1-424f-a26e-dda32e005ff0.png)
![image](https://user-images.githubusercontent.com/111414678/214513180-a4b4e848-d507-47d2-a974-b0fea02724f6.png)

### <a name="6"></a>Dienstag, 31. Januar 2023
In der heutigen Stunde haben wir die erste Viertelstunde damit verbracht, den Computer anzumachen. Scheinbar war die Konfiguration von Microsoft Paint zu viel für den Computer. Danach haben wir ein Problem gelöst, wobei unser Code wegen einer unerklärten Variable nicht funktioniert hat. Das lag im Endeffekt daran, dass wir einen unauffälligen Rechtschreibfehler gemacht haben. Danach hatten wir ein neues Problem, nämlich war auf einmal die Hitbox der Striche, die den Siegesbildschirm aktivieren sollen, zu groß. Dieses Problem konnten wir in der heutigen Stunde nicht lösen.

### <a name="7"></a>Mittwoch, 1. Februar 2023

Heute haben wir versucht, das Problem mit der zu großen Hitbox zu lösen. Dabei haben wir herausgefunden, dass die Hitbox sich verändert, je nachdem, wie viele Pixel das Pixelart eines Actors hat. Deshalb haben wir unser Pixelart so angepasst, dass die Hitbox richtig ist. Daneben haben wir auch überlegt, ein Explosion hinzuzufügen, das haben wir aber dann doch nicht gemacht, aber erstmal trotzdem deaktiviert im Code gelassen. Außerdem haben wir uns Ende der Stunde dazu entschieden, mit weißen Strichen dafür zu sorgen, dass Figuren, die auf weiße Felder kommen, direkt sterben. Damit haben schon angefangen, allerdings gibt es im WeißStrich-Actor scheinbar einen Fehler, der aber nicht gezeigt wird bzw. es steht nur, dass es einen Fehler gibt, aber es ist nichts rot markiert. Das wollen wir nächste Stunde angehen. 

### <a name="8"></a>Mittwoch, 8. Februar 2023
Wir haben in der heutigen Stunde unseren Win-Screen beendet, der funktioniert jetzt. Außerdem haben wir mit den "Weißstrichen" weitergemacht. Diese sollen dafür sorgen, dass Wolf und Schafe nicht aus vorgesehenen Bereich herauskommen. Da gibt es noch Probleme, um die wir uns in den nächsten Stunden kümmern wollen. Auch einen Bildschirm für GameOver wollen wir in den nächsten Stunden machen.
![image](https://user-images.githubusercontent.com/111414678/217473023-afefc599-0c9e-4aa0-add0-5acc0ce77e4b.png)

### <a name="9"></a>Freitag, 10. Februar 2023
Heute haben wir mit Herrn Buhls Hilfe die Schafe alle in einem Actor programmiert. Dazu haben wir mit dem GameOver-Screen weitergemacht. 
Außerdem gab es einen Stromausfall.

### <a name="10"></a>Mittwoch, 15. Februar 2023
Heute war Klemens nicht da. Ich habe die "Weißstriche" eingefügt, was noch nicht komplett funktioniert hat, daran müssen wir nächste Stunde weiterarbeiten.
![image](https://user-images.githubusercontent.com/111414678/218969263-141b7209-e804-4cae-8634-f292ec82bc5f.png)

### <a name="11"></a>Mittwoch, 22. Februar 2023
In der heutigen Stunde haben wir es hinbekommen, dass die Weißstriche überall funktionieren. Das heißt, dass jetzt alle Schafe sterben und der Wolf verliert, sollte er versuchen, das Spielfeld zu verlassen bzw. ein einzelnes Schaf verschwindet dadurch und bei dem Wolf öffnet sich der GameOver-Screen in Form eines großen roten Kreuzes, was bei den Schafen nicht auftaucht, da es ja noch andere gibt und die Schafe dadurch ja noch nicht verloren haben.

### <a name="12"></a>Freitag, 24. Februar 2023
Heute haben wir uns über die Töne, die im Spiel vorkommen sollen, Gedanken gemacht. Außerdem haben wir mit der Projektseite weitergemacht.
Wir haben auch noch eine zweite Welt erschaffen, die von der ersten Welt abgeleitet ist. In dieser wollen wir noch einen weiteren Actor hinzufügen, der die Schwierigkeit erhöhten soll. 
![image](https://user-images.githubusercontent.com/111414678/221173728-d903db31-881e-4b48-a91b-c93a56093fda.png)
REHJTFRQjker


### <a name="13"></a>Mittwoch, 1. März 2023
Wir haben es heute geschafft, dass die zweite Welt funktioniert, indem wir den Gnark dazu gebracht haben, zufällig herumzulaufen und bei Wänden umzukehren.
![image](https://user-images.githubusercontent.com/111414678/222082433-8434c693-43f2-473b-a892-81686b45d43f.png)


### <a name="14"></a>Freitag, 3. März 2023
In der Stunde am Distanzlerntag am letzten Freitag hatten wir es hinbekommen, dass der Gnark fehlerfrei Schafe und Wölfe isst ohne andere Probleme zu machen bzw. so, dass es problemfrei funktioniert.
![image](https://user-images.githubusercontent.com/111414678/222082514-455a2dec-d2ea-4bb5-b194-da22bbbfdc3b.png)
![image](https://user-images.githubusercontent.com/111414678/222082615-973b1efd-5b0f-4366-8eea-8abf2a0f4aee.png)

### <a name="15"></a>Mittwoch, 8. März 2023
Heute haben wir an der Projektseite weitergearbeitet. Wir haben dabei unter anderem ein Register für die Projektseite gemacht.

### <a name="16"></a>Freitag, 10. März 2023
Auch heute haben wir an der Projektseite gearbeitet und uns Gedanken über die Geräusche für WinOver und GameOver gemacht.
Dabei haben wir eine Soundbibliothek mit Geräuschen gefunden, die wir dafür nutzen wollen. Diese wollen wir entweder in der nächsten Stunde oder zuhause in das Spiel einfügen.

### <a name="17"></a>Mittwoch, 15. März 2023
Wir haben in der heutigen Stunde wieder an der Projektseite weitergearbeitet.

### <a name="18"></a>Freitag, 17. März 2023
In der heutigen Stunde haben wir uns Gedanken über die Geräusche von Schaf und Wolf gemacht und zwei passende Geräusche gefunden. Außerdem haben wir bisher erfolglos versucht, eine Methode zu finden, die die Aktoren nach einer Bewegung verschwinden lässt.

### <a name="19"></a>Freitag, 24. März 2023
Auch heute haben wir wieder an der Projektseite gearbeitet. ((((Zusätzlich haben wir auch die Idee gehabt, uns mit Flappy Bird zu beschäftigen.)))))

IDEE: Gnark bewegt sich bei Betätigung einer Taste einmal in eine beliebige Richtung.


ZUERsT: Icons von die Einzelne Actor in ProJektSEite EinfÜGEn
nääääääste stunne: wolf und vlt auch schafsgeräusch aus soundbib abspielen und dadurch ins Spiel einfügen
https://www.videvo.net/de/lizenzfreie-soundeffekte/bibliothek/

Piratenbib: https:yout.com (ube rauskopiern)
