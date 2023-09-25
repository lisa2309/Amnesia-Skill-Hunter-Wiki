# Sprint Meetings
- Dienstags zusammen als Gruppe
# Workflow

### Sprints
In den wöchentlichen Gruppenmeetings wird der bisherige Fortschritt präsentiert und im Anschluss diskutiert. Anschließend werden abgeschlossene Issues aus der Vorwoche in den Dev-Branch gemerged. So können eventuelle Konflikte zusammen schnell gelöst werden. Anschließend wird der weitere Ablauf des Projektes Besprochen. Neue Issues für die kommende Woche werden erstellt und jeder weißt sich diese selbst zu.

Häufig können Issues abhängig von anderen Issues sein. Die betroffenen Mitglieder stehen in dieser Zeit enger in Kontakt via Discord und betreiben evtl. Pair-Programming, um potentielle Fehler zu vermeiden.

Probleme in der Entwicklung werden möglichst frühzeitig kommuniziert.
Dadurch wird versucht zu gewährleisten, dass der Workflow möglichst konstant bis zum Ende des Sprints bestehen bleibt und die Artefakte zeitig fertig werden.

### Issue Board
Jedes Gruppenmitglied weist sich ein Issue zu, und setzt dieses in die Spalte "To Do". Hierdurch teilt das Gruppenmitglied sein Interesse an diesem Issue.
Sobald das Gruppenmitglied das Issue bearbeitet, wird das Issue in die Spalte "In Process" verschoben.
Ist das Issue fertig bearbeitet, wird dieses weiter in die Spalte "To Verify" verschoben und ein Merge-Request erstellt.
Ein weiteres Team-Mitglied überprüft diesen Merge-Request nach Code-Qualität, Funktionalität des Features und Dokumentation und merged die Issue-Branch in den Developing-Branch, wenn alles stimmt.

### Dev Branch
Hier werden alle fertigen Issues und Unteraufgaben gemerged. Der Dev Branch wird nach jedem Merge händisch neu getestet und auftretende Bugs innerhalb des Branches werden gefixt.  
  
Dadurch will das Team vermeiden, dass im Master-Branch fehlerhafte, oder nicht vollständige Features liegen. Aus diesem Grund wird der Dev-Branch erst dann in den Master gemerged, wenn alle Features im Dev-Branch fehlerfrei funktionieren.


# Verwendete Technologien zur Kommunikation
### Discord
- wöchentliche Gruppenmeetings 
- Pair Programming
- spontane Meetings einzelner Gruppenmitglieder