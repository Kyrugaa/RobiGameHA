# Hausaufgabe Robi Game


### Dieses Repository wurde aufgrund der Hausaufgaben für Modul 226a erstellt.

Es enthält einen Java-Code, der bei Ausführung ein Game namens RobiGame startet.
Der Code wurde in der IDE Eclipse geschrieben. Indem man die core.java im build path konfiguriert, ist es möglich bei Ausführung das optische Fenster
von der IDE Processing zu starten und da mit dem Spiel zu interagieren.

#### Die Vorgaben, aus dieser Hausaufgabe 4 Punkte für die LB mitzunehmen waren:
- Die Highscores sollen verwaltet und angezeigt werden.
- Eine top 10 zu erstellen, die die besten 10 Highscores auflistet. Sollten diese ''Rekorde'' übertroffen werden, so wird die Highscore-Liste aktualisiert und den neuen
  Rekordhalter in die Liste aufnehmen.
- Das Projekt mit dessen Quellcode soll auf Github zu finden sein.
- Das Github Reposetory soll eine sinnvolle README.md enthalten mit einer Projektdoku.

Ich hatte von Anfang an wieder Probleme mit Eclipse und dem importieren. Deswegen konnte ich die Vorlage von dem Github unseres Lehrers nur bedingt nutzen.
Was Git und Github betrifft habe ich durch einen Freund viel gelernt und ich versteh jetzt die Wichtigkeit dieser Plattform für Developer.
Was den Code angeht stand ich von Anfang an vor dem Problem, dass ich das Programm nicht ausführen konnte. Alle Fehlermeldungen habe ich behoben aber leider hab ich dieses
''Ant Build'' Problem. 


#### Das Projekt ist in fünf Klassen unterteilt.

Robi.java:                In dieser Klasse wird die Optik der Player(Robi's) designed. 
Food.java:                Hier werden die kleinen Dots, welche den Player zum wachsen bringen und auch Punkte geben erstellt.
RobiGameController.java:  Hier wird die Logik und Steuerung im Spiel definiert.
HighScore.java:           Diese Klasse enthält nur zwei Variablen, da darin auch nur die Getter-Funktionen für den Namen und den Score sind.
HighScoreController.java: Hier wird die Logik und Berechnung der verschiedenen erziehlten Scores verwaltet.
