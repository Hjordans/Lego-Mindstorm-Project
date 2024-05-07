# Lego Mindstorm Project
 ## Anleitung  
  ### Kleine Einleitung mit Anleitung um Scratch einzurichten und die Bauanleitung für den Robohund von Lego
   Als Erstes muss man den Robohund zusammen bauen, dafür braucht man die [Bauanleitung](https://assets.education.lego.com/v3/assets/blt293eea581807678a/blt074d025a1a1eccd9/5f8801e41189001a2dc76d4d/ev3-model-core-set-puppy.pdf?locale=de-de "Link zur Bauanleitung") von Lego.  
   Danach sollte man Scratch Link installieren.  
   Damit wird der Lego Controller mit dem Scratch Projekt verbunden.  
   Die [Anleitung](https://scratch.mit.edu/ev3 "Link zur Anleitung") von Scratch ist sehr hilfreich.  
   So sieht der Controller aus:  
   ![Controller Bild oben](https://github.com/Hjordans/Lego-Mindstorm-Project/blob/main/Lego-Controller-oben.png "Bild vom Controller von oben") 
   ![Controller Bild unten](https://github.com/Hjordans/Lego-Mindstorm-Project/blob/main/Lego-Controller-unten.png "Bild vom Controller von unten")  
   Oben sind die Anschlüsse A, B, C und D und unten 1, 2, 3 und 4.

   ### Anschlüsse und ihre Funktionen
   Der Robohund, den ich mit dem Lego gebaut habe, hat acht Anschlüsse, mit fünf Anschlüssen ist er mit dem Controller verbunden.  
   Ich nenne die ab jetzt A, C, D, 1 und 4 im Folgenden beschreibe ich, was die einzelnen Anschlüsse machen.
   
   + **A:** Anschluss für den Motor des hinteren rechten Beins.
		+ Bewegung des Beins nach vorne und hinten.
   + **C:** Anschluss für den Motor des Kopfes.
		+ Bewegt den Kopf nach oben und unten.
   + **D:** Anschluss für den Motor des hinteren linken Beins.
		+ Bewegt das Bein nach vorne und hinten.
   + **1:** Anschluss für den Knopf auf dem Rücken.
		+ Aktivierung einer programmierbaren Funktion durch Drücken des Knopfes.
   + **4:** Anschluss des Farbsensors.
		+ Erkennung von sieben Farben und Helligkeitsmessung.
   
   **Wichtig:** Die Funktionen hängen von den Einstellungen mittels der Scratch Programmierung ab.

   ### Das Scratch Projekt
   Bei Scratch habe ich den Hund so programmiert, dass er den Kopf nach unten und oben bewegen kann  
   wenn die Pfeiltasten nach unten und oben gedrückt werden.  
   (Nach unten, wenn man die Pfeiltaste nach unten drückt, nach oben, wenn man die Pfeiltaste nach oben drückt.)  
   
   Außerdem wenn er „Gestreichelt wird“ (Der Knopf auf dem Rücken gedrückt wird) freut er sich.  
   Der Kopf wird dann insgesamt viermal nach unten und oben bewegt.

   Der letzte Trick ist, dass er die Beine bewegen kann, mit der Pfeiltaste nach rechts bewegt er diese nach vorne.  
   Mit der Pfeiltaste nach links bewegt er seine Beine nach hinten.  
   Ich habe Grenzwerte programmiert, da er sonst hinfällt und es nicht mehr funktioniert. 
   Er hat dann nicht mehr genug Kraft, um aufzustehen.  
   
   **Achtung:** Bitte die Beine nicht manuell bewegen, weil die Chance besteht, dass es die Grenzwerte kaputt macht.  
   
   Die Grenzwerte sind manuell festgelegte Werte, die fest sind und nicht Variable, daher kann es sein, dass er dadurch wieder hinfallen kann. 
