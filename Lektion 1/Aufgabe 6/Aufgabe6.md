# Aufgabe 6 - Ein Würfel
## Allgemeines
Nachdem wir schon die ersten Rechnungen durcheführt haben, schauen wir uns als nächstes zufällige Zahlen an. Dafür wollen wir einen digitalen Würfel erstellen.

## Aufgabenstellung
Erstelle ein Programm welches eine zufällige Zahl zwischen 1 und 6 ausgibt.
Hinweis: Um eine zufällige Zahl zu erstellen müssen wir die Bibliothek "random" importieren. Das machen wir indem wir ganz oben in unserem Programm folgendes eingeben:
```
import random
```
Hinweis2: Da die zufällige Zahl eine Zahl ist, wir für die Ausgabe aber eine Zeichenkette benötigen muss man sie nochmal umwandeln (ähnlich wie die Zeichenkette in eine Zahl in den letzten Aufgaben)
## Benötigte Befehle
```
print(var) #Gibt den Wert von var aus.
print("TEXT" + var) #Gibt die Zeichenkette "TEXT" und dann den Wert von var in der selben Zeile aus.
zufall = random.randint(0,9) #Generiert eine zufällige Zahl zwischen 0 und 9 und speichert sie in der Variable zufall
zufall = str(zufall) #Wandelt den Wert von zufall in eine Zeichenkette um.
```

## Ziel
```
Der Würfel zeigt: 
```
## Optionales
