# Wie werden meine Bearbeitungen im Wiki veröffentlicht?
In welchem Format die Texte für dieses Wiki geschrieben werden sollen, steht in dem Artikel ["Richtig Bearbeiten."](./richtig-bearbeiten.md) - hier erfährst du, wie du deine Änderungen allen zur Verfügung stellst.

## Online einzelne Dateien bearbeiten
Der Einsatz des GitHub-Online-Editors zum Bearbeiten von Dateien in einem Repository bietet mehrere Vorteile. Erstens ermöglicht er einen einfachen Zugriff und eine schnelle Bearbeitung der Dateien direkt über den Webbrowser, ohne die Notwendigkeit, lokale Tools zu installieren. Zweitens erleichtert er die Zusammenarbeit, da Änderungen schnell vorgenommen und Pull Requests erstellt werden können, um Änderungsvorschläge den Repository-Besitzern vorzulegen. Drittens entfällt die Notwendigkeit einer lokalen Kopie des Repositories, was Zeit und Aufwand spart, insbesondere für kleinere Änderungen.

1. GitHub-Konto erstellen
Falls du noch kein GitHub-Konto hast, gehe auf https://github.com und erstelle ein neues Konto. Folge den Anweisungen zur Kontoerstellung.

2. Repository besuchen
Gehe zum Repository, das du online bearbeiten möchtest. In deinem Fall lautet der Link [https://github.com/esportheidelberg/ESHD-Docs](https://github.com/esportheidelberg/ESHD-Docs). Öffne diesen Link in deinem Webbrowser.

3. Repository forken
Oben rechts auf der Repository-Seite findest du die Schaltfläche "Fork". Klicke darauf, um eine Kopie des Repositories in deinem eigenen GitHub-Konto zu erstellen. Dadurch erhältst du die Berechtigung, das Repository zu bearbeiten.

4. Datei auswählen
Navigiere im Repository zu der Datei, die du bearbeiten möchtest. Klicke auf den Dateinamen, um die Datei anzuzeigen.

5. Bearbeitungsmodus öffnen
Sobald du die Datei geöffnet hast, findest du oben rechts auf der Dateiansicht einen Stift-Button mit der Aufschrift "Edit this file". Klicke darauf, um den Bearbeitungsmodus zu öffnen.

6. Datei bearbeiten
Im Bearbeitungsmodus kannst du den Inhalt der Datei ändern. Du kannst Text hinzufügen, entfernen oder bearbeiten.

7. Änderungen beschreiben
Unterhalb des Bearbeitungsfensters siehst du ein Eingabefeld mit der Aufschrift "Commit changes". Gib eine aussagekräftige Beschreibung für deine Änderungen ein, um anderen Mitwirkenden zu helfen, den Zweck deiner Änderungen zu verstehen.

8. Änderungen speichern
Sobald du mit deinen Änderungen zufrieden bist, scrolle zum Ende der Seite und klicke auf den grünen Button "Commit changes". Dadurch werden deine Änderungen in deinem geforkten Repository gespeichert.

9. Pull Request erstellen
Nachdem du deine Änderungen gespeichert hast, kehre zum ursprünglichen Repository zurück (https://github.com/esportheidelberg/ESHD-Docs). Du solltest eine Benachrichtigung sehen, die dich auffordert, einen Pull Request zu erstellen. Klicke auf den Link "Compare & pull request" neben der Benachrichtigung.

10. Pull Request abschicken
Überprüfe die Änderungen, die du vorgenommen hast, und gib eine kurze Beschreibung für den Pull Request ein. Sobald alles in Ordnung ist, klicke auf den Button "Create pull request", um den Pull Request abzusenden.

Wenn du nicht selber den Pull Request annehmen kannst, bitte jemanden mit den entsprechenden Rechten, diesen Pull Request für dich zu überprüfen und anzunehmen.

## Einzelne Dateien hochladen

Navigiere zu dem Repository und suche die Datei (meistens ein Bild) heraus, das du gerne hinzufügen möchstest. Das Bild sollte an der langen Kante 1920 Pixel lang sein und max. 700 KB haben, damit die Seiten auch weiter schnell geladen werden können.

1. Datei auswählen
Navigiere im Repository zu dem Ordner, in dem das Bild gespeichert werden soll. Klicke auf den Ordner, um ihn zu öffnen.

2. Datei hinzufügen
Oben rechts in der Ordneransicht findest du die Schaltfläche "Add file". Klicke darauf und wähle "Upload files" aus dem Dropdown-Menü.

3. Datei auswählen
Klicke auf "Choose your files" oder ziehe die gewünschte Bilddatei in den dafür vorgesehenen Bereich. Stelle sicher, dass das Bild den Anforderungen hinsichtlich Größe, Format und Namensschema entspricht.

4. Datei benennen
Sobald die Datei ausgewählt wurde, solltest du sicherstellen, dass sie das richtige Namensschema verwendet. Dies kann von Repository zu Repository unterschiedlich sein. Überprüfe die Dokumentation oder frag andere Mitwirkende nach dem bevorzugten Namensschema.

7. Datei hochladen
Klicke auf "Commit changes" oder einen ähnlichen Button, um die Datei hochzuladen. Wähle eine aussagekräftige Beschreibung für den Commit aus, um andere Mitwirkende über die Änderungen zu informieren.

8. Überprüfen
Gehe sicher, dass das Bild erfolgreich hochgeladen wurde, indem du in den entsprechenden Ordner navigierst und nach der Datei suchst. Du solltest das hinzugefügte Bild sehen können.

**Es ist wichtig, das richtige Namensschema für die Dateien einzuhalten, um die Ordnung im Repository zu gewährleisten und potenzielle Konflikte zu vermeiden. Orientiere dich bei den Dateinamen an den schon vorhandenen Dateien und lasse auf keinen Fall Abstände in den Dateinamen!**

## Offine effizienter bearbeiten (Windows)

1. Git installieren
Lade Git von der offiziellen Website herunter und führe den Installationsprozess aus. Git ist ein Versionskontrollsystem, das zum Herunterladen und Synchronisieren von Repositorys verwendet wird. Du kannst Git von [der offiziellen Webseite](https://git-scm.com) herunterladen.

2. Visual Studio Code installieren
Lade Visual Studio Code von der offiziellen Website herunter und installiere es auf deinem Computer. Visual Studio Code ist ein beliebter plattformübergreifender Texteditor, der viele Funktionen für die Entwicklung und das Bearbeiten von Code bietet. Du kannst Visual Studio Code von [der offiziellen Webseite](https://code.visualstudio.com) herunterladen.

3. Repository klonen
Öffne den Git Bash-Client oder das Terminal auf deinem Computer. Navigiere zu dem Verzeichnis, in dem du das Repository speichern möchtest, indem du den Befehl "cd <Verzeichnispfad>" eingibst. Ersetze "<Verzeichnispfad>" durch den Pfad zu deinem gewünschten Speicherort.

Führe den folgenden Befehl aus, um das Repository zu klonen:

```
git clone <Repository-URL>
```

Ersetze "<Repository-URL>" durch die URL des Repositories, das du bearbeiten möchtest. Zum Beispiel:

```
git clone https://github.com/esportheidelberg/ESHD-Docs.git
```

4. Visual Studio Code öffnen
Öffne Visual Studio Code auf deinem Computer. Klicke auf "File" (Datei) in der Menüleiste und wähle "Open Folder" (Ordner öffnen) aus. Wähle den Ordner aus, in dem das geklonte Repository gespeichert ist, und klicke auf "Open" (Öffnen).

5. Dateien bearbeiten
Navigiere im Visual Studio Code zur gewünschten Datei im Repository-Ordner. Klicke auf die Datei, um sie zu öffnen, und bearbeite sie nach Bedarf. Visual Studio Code bietet eine Vielzahl von Funktionen, um den Bearbeitungsprozess zu erleichtern.

6. Änderungen commiten und pushen
Sobald du deine Änderungen vorgenommen hast, gehe zurück zum Git Bash-Client oder Terminal. Navigiere zum Repository-Verzeichnis, indem du den Befehl "cd <Repository-Verzeichnis>" eingibst.

Führe die folgenden Befehle aus, um deine Änderungen zu commiten und in das Repository hochzuladen:

```
git add .
git commit -m "Beschreibe deine Änderungen hier"
git push origin master
```

Ersetze bei Bedarf "master" durch den Namen des entsprechenden Branches.

Damit hast du erfolgreich deine Änderungen offline bearbeitet und in das GitHub-Repository hochgeladen. Andere Mitwirkende können deine Änderungen sehen und überprüfen.

## Offine effizienter bearbeiten (MacOS)

1. Git installieren
Lade Git von der offiziellen Website herunter und führe den Installationsprozess aus. Git ist ein Versionskontrollsystem, das zum Herunterladen und Synchronisieren von Repositorys verwendet wird. Du kannst Git von https://git-scm.com herunterladen.

2. Visual Studio Code installieren
Lade Visual Studio Code von der offiziellen Website herunter und installiere es auf deinem Computer. Visual Studio Code ist ein beliebter plattformübergreifender Texteditor, der viele Funktionen für die Entwicklung und das Bearbeiten von Code bietet. Du kannst Visual Studio Code von https://code.visualstudio.com herunterladen.

3. Repository klonen
Öffne das Terminal auf deinem Mac, indem du entweder "Terminal" in Spotlight suchst oder zu "Programme -> Dienstprogramme -> Terminal" navigierst.

Navigiere zu dem Verzeichnis, in dem du das Repository speichern möchtest, indem du den Befehl "cd <Verzeichnispfad>" eingibst. Ersetze "<Verzeichnispfad>" durch den Pfad zu deinem gewünschten Speicherort.

Führe den folgenden Befehl aus, um das Repository zu klonen:

```
git clone <Repository-URL>
```

Ersetze "<Repository-URL>" durch die URL des Repositories, das du bearbeiten möchtest. Zum Beispiel:

```
git clone https://github.com/esportheidelberg/ESHD-Docs.git
```

4. Visual Studio Code öffnen
Öffne Visual Studio Code auf deinem Mac. Klicke auf "File" (Datei) in der Menüleiste und wähle "Open" (Öffnen) aus. Wähle den Ordner aus, in dem das geklonte Repository gespeichert ist, und klicke auf "Open" (Öffnen).

5. Dateien bearbeiten
Navigiere im Visual Studio Code zur gewünschten Datei im Repository-Ordner. Klicke auf die Datei, um sie zu öffnen, und bearbeite sie nach Bedarf. Visual Studio Code bietet eine Vielzahl von Funktionen, um den Bearbeitungsprozess zu erleichtern.

6. Änderungen commiten und pushen
Sobald du deine Änderungen vorgenommen hast, öffne das Terminal erneut und navigiere zum Repository-Verzeichnis, indem du den Befehl "cd <Repository-Verzeichnis>" eingibst.

Führe die folgenden Befehle aus, um deine Änderungen zu commiten und in das Repository hochzuladen:

```
git add .
git commit -m "Beschreibe deine Änderungen hier"
git push origin master
```

Ersetze bei Bedarf "master" durch den Namen des entsprechenden Branches.

Damit hast du erfolgreich deine Änderungen offline bearbeitet und in das GitHub-Repository hochgeladen. Andere Mitwirkende können deine Änderungen sehen und überprüfen.

## Authentifizieren bei GitHub
Wenn du beim Push-Versuch nach deinen Zugangsdaten gefragt wirst, wirst du schnell feststellen, das dein Passwort nicht funktioiert: Diese Methode wurde vor einiger Zeit aus Sicherheitsgründen abgeschaltet, Passwörter wurden durch sog. Personal Access Tokens ersetzt. So erstellst du einen, den du anstelle des Passworts eingeben kannst:
1. Generiere einen Personal Access Token
- Gehe zu deinem GitHub-Konto und klicke oben rechts auf dein Profilbild. Wähle dann "Settings" (Einstellungen) aus dem Dropdown-Menü.
- In den Kontoeinstellungen klicke auf den linken Seitenbereich auf "Developer settings" (Entwicklereinstellungen).
- Wähle nun "Personal access tokens" (Persönliche Zugriffstoken) aus der Seitenleiste.
- Klicke auf "Generate new token" (Neues Token generieren).
- Gib einen Namen für das Token ein und wähle die gewünschten Berechtigungen aus. Für das Pushen von Änderungen in Repositories benötigst du mindestens die Berechtigung "repo" oder "public_repo".
- Scrolle nach unten und klicke auf "Generate token" (Token generieren).
- Kopiere das generierte Token. Beachte, dass dies die einzige Gelegenheit ist, das Token anzuzeigen. Speichere es an einem sicheren Ort, da du es später nicht erneut anzeigen kannst.

2. Authentifizierung in der Kommandozeile
- Öffne das Terminal oder die Git-Bash auf deinem Computer.
- Gib den folgenden Befehl ein, um dich bei GitHub zu authentifizieren:

```
git config --global credential.helper store
```

Dieser Befehl speichert deine Anmeldeinformationen dauerhaft, sodass du dich nicht bei jedem Git-Befehl erneut authentifizieren musst.

- Führe anschließend den folgenden Befehl aus und füge dein GitHub-Benutzername und das Personal Access Token ein:

```
git config --global user.name "Dein_GitHub_Benutzername"
git config --global user.password "Dein_Personal_Access_Token"
```

Ersetze "Dein_GitHub_Benutzername" durch deinen GitHub-Benutzernamen und "Dein_Personal_Access_Token" durch das zuvor generierte Personal Access Token.

- Jetzt bist du authentifiziert und kannst Git-Befehle ausführen, die Änderungen in Repositories erfordern, ohne dich jedes Mal erneut anmelden zu müssen.

Wichtiger Hinweis: Bewahre dein Personal Access Token sicher auf und teile es nicht mit anderen. Es ermöglicht den Zugriff auf deine GitHub-Repositorien, daher sollte es vertraulich behandelt werden.