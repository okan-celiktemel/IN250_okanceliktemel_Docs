## Aufgabe 1

### Repository in Github anlegen

### Auf Github Website anmelden und ein neues Repository eröffnen.

## Aufgabe 2

### Um ein Repository zu klonen, habe ich den Repository-Link auf GitHub kopiert und in Vs Code unter "Repository klonen" in das Suchfeld eingefügt. Zuvor habe ich einen Ordner für das Repository erstellt.

## Aufgabe 3

### Ich habe den Cheatsheet im Moodle heruntergeladen und kopiert und in den geklonten Repository Ordner eingefügt. Danach habe ich es mit fälschlicherweise mit der Nchricht Screen shots anstatt mit Initial commit commitet.

## Aufgabe 4

### Ich habe im VS Code unter Dateien in meinem Repository eine Datei namens .gitignore erstellt. Danach habe ich eine weitere Datei mit dem Namen logGeheimeBankInformationen.txt erstellt. In der .gitignore-Datei habe ich den Eintrag logGeheimeBankInformationen.txt hinzugefügt. Anschließend habe ich im Terminal den Befehl git status ausgeführt und folgende Antwort erhalten: Untracked files:(use "git add <file>..." to include in what will be committed) .gitignore logGeheimeBankInformationen.txt Das bedeutet, dass die Datei logGeheimeBankInformationen.txt nicht mehr getrackt wird. Änderungen an dieser Datei werden also nicht im Repository verfolgt.

## Aufgabe 5

### Remote-Origin ist eingerichtet Als ich versucht habe, den Remote-Origin hinzuzufügen, hat Git mir gesagt: "remote origin already exists". Das bedeutet, mein lokales Repository ist bereits mit dem GitHub-Repository verknüpft, und alles ist korrekt eingestellt.

### Mein lokales Repository ist aktuell

### Ich habe mit git fetch die neuesten Änderungen vom Remote-Repository geholt und mit git pull überprüft, ob es etwas Neues gibt. Git hat mir gesagt: "Already up to date" – mein lokales Repository ist also auf dem neuesten Stand.

### Branches sind verknüpft

### Mein lokaler Haupt-Branch (main) ist mit dem Haupt-Branch auf GitHub (origin/main) verbunden. Änderungen, die ich mache und hochlade (git push), landen direkt auf GitHub.

## Aufgabe 6

### Git ist ein Werkzeug, das in der Softwareentwicklung genutzt wird, um die Arbeit an Projekten besser zu organisieren und sicherzustellen, dass nichts verloren geht. Es bietet mehrere Vorteile, die gerade bei größeren Projekten oder bei der Zusammenarbeit im Team besonders wichtig sind:

### 1. Versionskontrolle: Git speichert jede Änderung, die an einem Projekt vorgenommen wird. Falls etwas schiefgeht, kann man jederzeit zu einer früheren Version zurückkehren.

### 2. Zusammenarbeit: Mehrere Personen können gleichzeitig am gleichen Projekt arbeiten, ohne sich gegenseitig zu behindern. Git sorgt dafür, dass Änderungen automatisch zusammengeführt werden können.

### 3. Datensicherheit: Wenn Änderungen auf einen Remote-Server wie GitHub hochgeladen werden, sind sie auch dann noch sicher, wenn der lokale Computer beschädigt oder verloren geht.

### Angenommen, es kommt zu einem Notfall, z. B. einem Feuer. Wenn die Arbeit auf dem Computer nicht mit Git hochgeladen wurde, könnten alle Änderungen verloren gehen. Um dies zu vermeiden, sollten folgende Schritte befolgt werden:

### 1. Git Commit: Änderungen lokal speichern. Damit wird ein "Schnappschuss" des aktuellen Stands des Projekts erstellt.

### 2. Git Push: Die lokal gespeicherten Änderungen werden auf GitHub hochgeladen. Dadurch sind die Änderungen auch dann noch verfügbar, wenn der Computer nicht mehr nutzbar ist.

### 3. Wenn die 2 Punkte erfüllt sind erst dann darf man die Flucht ergreifen :)
