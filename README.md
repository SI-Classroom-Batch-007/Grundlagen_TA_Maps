<h1 align="center">Grundlagen der Programmierung</h1>
<h3 align="center">Maps</h3>
<br>

#### Beschreibung:

Heute haben wir das Thema Maps kennengelernt.

Das Wort Maps kommt dabei nicht von Google Maps, sondern kommt aus der englischen 
Sprache und steht für Abbildungen. In einer Abbildung zeigt etwas
(z.B. ein Schlüssel) auf etwas anderes (z.B. einem Wert).


#### Hinweise zur Bearbeitung:

- Löse die Aufgaben programmatisch (D.h. schreibe Code, um auf die Lösung zu kommen).
- Achte auf einen sauberen Quellcode, insbesondere Einrückungen sind wichtig!
- Achte bei Strings genau auf die Schreibweise, man kann hier sehr leicht Tippfehler machen!
- Wenn ihr Hilfe braucht, könnt ihr euch am Code aus der Aufgabe 1 orientieren
oder jederzeit die Tutoren fragen.
- Viel Erfolg und natürlich viel Spaß!

---

<details>
<summary> <b> Aufgabe 1 - Map Beispiele </b> </summary>

Heute hast du in der Vorlesung Maps und MutableMaps kennengelernt.
Eine Map ist eine Anordnung von Paaren (englisch: entry).
Ein Paar besteht dabei aus einem Schlüssel (englisch: key) und einem Wert (englisch: value).  
- Schaue dir die Datei in Aufgabe1 an und versuche diese zu verstehen. 
- Setze einen Breakpoint in Zeile 6 und führe den Code im Debug-Modus Zeile für Zeile aus. 

**Modul für die Aufgabe:** *Aufgabe1*  
**Datei für die Aufgabe:** *01_MapBeispiele.kt*

</details>

---

<details>
<summary> <b> Aufgabe 2 - Map selber erstellen </b> </summary>

In dieser Aufgabe üben wir das Erstellen von Maps.  
Wenn ihr Hilfe braucht, schaut euch in Aufgabe1 an, wie eine Map bzw. 
eine MutableMap erstellt wurde.  
 
- Vervollständige zuerst die map `telefonNummerListe`, sodass sie zu Beginn diese Paare hat:
```
"Peter" -> 2487503
"Bernd" -> 3465081
"Ludolf" -> 3985292
```

- Vervollständige nun die map mit dem Namen `emailListe`, sodass der Schlüssel 
vom Typ String und der Wert vom Typ String ist. Zusätzlich soll die Map zu Beginn diese Paare haben:
```
"Peter" -> "peter123@gmail.com"
"Sabrina" -> "sabi-cool@gmx.de"
"Tobi" -> "titantobi@gamer.net"
```


**Modul für die Aufgabe:** *Aufgabe2*  
**Datei für die Aufgabe:** *2_MapsAnlegen.kt*


</details>

---

<details>
<summary> <b> Aufgabe 3 - MutableMap </b> </summary>


a) Erstelle eine Map über Waren und ihren Preisen.
- Erstelle eine Map, der Schlüssel ist vom Typ String und
  der Wert ist vom Typ Double.
- Die Map soll initial (also zu Beginn) mit folgenden Paaren gefüllt sein:  
```
"Schokolade" -> 1.99  
"Banane" -> 0.29  
"Yoghurt" -> 0.49  
"Müsli" -> 2.99
```
b) Erstelle eine MutableMap über Personennamen und ihren Lieblingstieren.
- Erstelle eine Map, der Schlüssel ist vom Typ String und
  der Wert ist vom Typ String.
- Die Map soll initial mit folgenden Paaren gefüllt sein:  
``` 
"Berta" -> "Hunde"  
"Frank" -> "Katzen"  
"Luis" -> "Hunde"  
"Sylvia" -> "Eulen"
```

c) Erstelle eine Map über Hausnummern und der Hausfarbe.
- Erstelle eine Map, der Schlüssel ist vom Typ Int und 
  der Wert ist vom Typ String.
- Die Map soll initial mit folgenden Paaren gefüllt sein:  
```
  12 -> "Rot"  
  45 -> "Blau"  
  23 -> "Gelb"  
  28 -> "Grün"  
```
**Modul für die Aufgabe:** *Aufgabe3*  
**Datei für die Aufgabe:** *3_MapsAnlegen.kt*
</details>


---

<details>
<summary> <b> Aufgabe 4 - Werte erhalten </b>
</summary>

In dieser Aufgabe geht es darum, wie man Werte aus einer Map erhält.
Oftmals hat man einen Schlüssel (key) gegeben und möchte den Wert (value) 
haben, auf den der Schlüssel zeigt.

a) Gegeben ist folgende Map:  
```
      "Berta" -> "Hunde"  
      "Frank" -> "Katzen"  
      "Luis" -> "Mäuse"  
      "Sylvia" -> "Eulen"
      "Hans" -> "Fau"
```

Die Map mappt von Person zu ihrem Lieblingstier. Schreibe sie in die Datei. 
Verwende die Index[] Schreibweise, 
wie in Aufgabe 1 oder in der Vorlesung gezeigt, um folgende Werte auszugeben.
- Was ist das Lieblingstier von Frank?
- Was ist das Lieblingstier von Sylvia? 
- Was ist das Lieblingstier von Hans?

b) Gegeben ist folgende Map:  
Die Map mappt von Hausnummer zu Hausfarbe.
```
12 -> "Rot"  
45 -> "Blau"  
23 -> "Gelb"  
28 -> "Grün"  
36 -> "Lila"  
92 -> "Rosa"  
```
- Erstelle eine geeignete Map mit den genannten Paaren.
- Lese den Wert aus der Map aus und weise ihn einer Variable zu,   
gib dann die Variable in der Konsole aus.
- Verwende in deiner Lösung die Index[] Schreibweise, um folgende Werte auszugeben.
  - Welche Hausfarbe hat das Haus mit der Nummer 28? 
  - Welche Hausfarbe hat das Haus mit der Nummer 45?
  - Welche Hausfarbe hat das Haus mit der Nummer 81?

**Modul für die Aufgabe:** *Aufgabe4*  
**Datei für die Aufgabe:** *4_WerteAbfragen.kt*

</details>

---

<details>
<summary> <b> Aufgabe 5 - Werte hinzufügen </b>
</summary>

a) Gegeben ist eine MutableMap, die jeder Person ihr Lieblingstier zuweist..

- Füge der MutableMap die folgenden Paare hinzu.
  - "Tim" -> "Schildkröte"
  - "Fabian" -> "Papagei"
  - "Jannik" -> "Schlange"

b)   
Was passiert, wenn du der MutableMap das Paar "Bernd" -> "Igel" hinzufügst?
Was passiert, wenn du der MutableMap das Paar "Luis" -> "Mäuse" hinzufügst?

c)

- Es ist wieder eine Mutable Map gegeben. 
Diese Map gib uns das Ergebnis einer Zahl als Potenz mit verschiedenen Exponenten.  
Füge dieser Map nun die 3 nächsten Paare hinzu. 
Anschließend drucke die fertige Map auf der Konsole aus.

- Wie sieht das Ergebnis aus, wenn du den Wert der Zahl änderst? 

**Modul für die Aufgabe:** *Aufgabe5*  
**Datei für die Aufgabe:** *5_WerteHinzufügen.kt*

</details>

---
<details>
<summary> <b> Aufgabe 6 - Werte ändern </b>
</summary>

Wir können auch die Werte bereits vorhandener Paare ändern.
Schreibe deine Lösungen in die Datei für diese Aufgabe.

a) Gegeben ist folgende MutableMap:  
Die MutableMap mappt von einer Person zu ihrem Lieblingstier.

- Löse die folgenden Teilaufgaben:
  - Ändere den Wert des Paares "Berta" -> "Hunde" zu "Berta" -> "Esel"
  - Ändere den Wert des Paares "Sylvia" -> "Eulen" zu "Sylvia" -> "Pferde"
  - Ändere den Wert des Paares "Frank" -> "Katzen" zu "Frank" -> "Spechte"
  - Ändere den Wert des Paares "Luis" -> "Mäuse" zu "Luis" -> "Spechte"

b) Fragen:
- Kann eine Map oder MutableMap diese zwei Paare enthalten?  
    "Berta" -> "Hunde"    
    "Berta" -> "Katzen"
  - Falls nein, was müsste man ändern, damit es möglich ist?

**Modul für die Aufgabe:** *Aufgabe6*  
**Datei für die Aufgabe:** *6_WerteHinzufügen.kt*
</details>

---
<details>
<summary> <b> Aufgabe 7 - Paare löschen </b>
</summary>

In dieser Aufgabe geht es um das Löschen von Paaren in Maps.

Gegeben ist folgende MutableMap:  
Die MutableMap mappt von einer Person zu ihrem Lieblingstier.

a)
- Löse die folgenden Teilaufgaben:
  - Verwende den Schlüssel "Frank", um das Paar "Frank" -> "Katzen" aus der MutableMap zu löschen.
  - Verwende den Schlüssel "Hans", um das Paar "Hans" -> "Fau" aus der MutableMap zu löschen.
  - Gebe die MutableMap aus. Die MutableMap sollte jetzt nur noch aus den folgenden Einträgen bestehen:  
```
  "Berta" -> "Hunde"  
  "Luis" -> "Mäuse"  
  "Sylvia" -> "Eulen"
```

b)
- Verwende jetzt den Schlüssel "Luis" und den Wert "Mäuse" um das Paar 
"Luis" -> "Mäuse" aus der MutableMap zu entfernen.  
Weise den Rückgabewert der .remove()-Funktion einer Variable zu und gib diese Variable in der Konsole aus.

- Verwende jetzt die Funktion remove(schlüssel, wert)
(in der Vorlesung dargestellt als remove(key, value)) mit folgenden 
Schlüssel "Frank" und Wert "Mäuse". Weise den Rückgabewert einer Variable zu und gib 
diese Variable in der Konsole aus.
  - Was wird ausgegeben? Und wieso?

**Modul für die Aufgabe:** *Aufgabe7*  
**Datei für die Aufgabe:** *7_PaareLöschen.kt*
</details>

---

<details>
<summary> <b> Aufgabe 8 - Schlüssel und Werte </b> </summary>

a)

Gegeben ist die folgende Map, die Fahrzeuge zu ihrer Geschwindigkeit in Km/h mappt:

    "Auto" -> 120.5
    "Flugzeug" -> 755.2
    "Fahrrad" -> 22.0
    "Tretroller" -> 15.7

- Erstelle eine passende Map, die initial die genannten Paare besitzt.
- Weise alle Schlüssel einer Variable zu und gib die Variable in der Konsole aus.
- Weise alle Werte einer Variable zu und gib die Variable in der Konsole aus.
- Stimmen die ausgegebenen Schlüssel und Werte mit denen der Map überein?
- Wende die entsprechende Konvertierungsfunktion an, um die Schlüssel und Werte als Listen abzuspeichern.
Du kannst dafür gerne die oben-erstellten Variablen anpassen.


b) 

- Benutze eine Listenfunktion, um die höchste Geschwindigkeit aus den Werten abzulesen. 
Speichere dir diesen Wert in einer Variable ab.
- Verwende eine Listenfunktion, um den Index von dieser Geschwindigkeit in der Werteliste zu finden. 
- Setze den gefundenen Index ein, um das entsprechende Fahrzeug auf der Konsole auszugeben. 

**Modul für die Aufgabe:** *Aufgabe8*  
**Datei für die Aufgabe:** *8_SchluesselUndWerte.kt*
</details>


---
