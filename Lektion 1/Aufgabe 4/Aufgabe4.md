# Aufgabe 4 - Datentypen und Simples rechnen
## Allgemeines
An dieser Stelle gehen wir auf eine weitere wichtige Besonderheit der Programmierung ein, die Datentypen. Ein Datentyp beschreibt die Art eines Wertes. Wenn wir einen Wert in eine Variable speichern kann dieser entweder eine Zeichenkette (auch String genannt) oder eine Zahl (auch Integer oder Double genannt) sein. Zeichenketten (Strings) erkennt man in der Regel daran, dass sie in Anführungszeichen geschrieben werden. Zahlen hingegen werden ohne Anführungszeichen eingegeben.

```
var1 = "Ich bin ein Text" #Diese Variable enthält eine Zeichenkette
var2 = 24 # Diese Variable enhält eine Zahl
```
Manchmal muss man einen Wert einer Variable in einen anderen umwandeln, so muss man zum Beispiel häufig eine Zeichenkette in eine Zahl umwandeln um damit rechnen zu können.
### Zwischenfrage
```
var 3 = "123"
```
Welchen Typ hat var3


## Aufgabenstellung
Erstelle ein Programm in welches du zwei Zahlen eingeben kannst und die Summe der beiden Zahlen ausgibt

## Benötigte Befehle
```
var = input("FRAGE") #Fragt einen Wert ab uns speichert ihn in der Variable mit dem Namen var. Achtung, die Rückgabe von input() ist immer eine Zeichenkette
print(var) #Gibt den Wert von var aus.
var = int(var) #Wandelt den Wert von var in eine Zahl und speichert sie als var ab.
summe = var1 + var2
```

## Ziel
```
Erste Zahl
EINGABE: 10
Zweite Zahl
EINGABE: 6
16
```
## Optionales
