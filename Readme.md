# Terraform Getting Started

3

## Umgebungsvariablen setzen

- Die Umgebuzngsvariablen sind Teil der Session im Terminal/Powershell
- Im AWS Kontext nutzen wir die Env-Variablen, um unseren `AWS_ACCESS_KEY_ID` und `AWS_SECRET_ACCESS_KEY` zu setzen

### Linux

`export AWS_ACCESS_KEY_ID=`

`export AWS_SECRET_ACCESS_KEY=`

`export AWS_DEFAULT_REGION=us-east-1`

### Windows

`$env:AWS_ACCESS_KEY_ID=""`
`$env:AWS_SECRET_ACCESS_KEY=""`
`$env:AWS_DEFAULT_REGION="us-east-1"`

# Git

- Versionskontrollsystem

## Git Dictionary

- `Repository`: Projektmappe (z.B. **01_terraform_getting_started**)
- `.gitignore` Dateu im root Verzeichnis des repositories beschreibt alle Dateien/Verzeichnisse die ignoriert werden sollen

### Commands

`init`: Initalisiert das Repository lokal in dem aktuellen Verzeichnis

- `commit`: Zusammenfassung der veränderten Dateien unter einem Titel
- `status`: Welche Dateien haben sich verändert
- `add`: Fügt Änderungen einem commit hinzu
- `clone`: Lädt sich ein repository herunter
- `push`: Lädt alle commits hoch

## Aufgabe 10.3.26:

1. Ihr erstellt einen leeren Ordner bei euch auf dem Computer (nicht in OneDrive)
2. Öffne den leeren Ordner in VSCode
3. Terminal öffnen und `git init`
4. Comitten, reverten , adden etc.
   Tipp: Am besten mit Readme.md und der Nutzung von [Markdown](https://www.markdownguide.org/cheat-sheet/)

## Aufgabe 12.03.26:

1. Repository über github.com erstellen
2. Leeren ordner unter C:// (nicht OneDrive)
3. Inititalisierung des repositories
4. Die Commands von eurem Github.com Repository verfolgen (Die da stehen wenn das Repo leer ist) --> Am besten per SSH (nicht HTTPS)
5. Readme.md erstellen
6. Ein paar commits machen
7. über die WSL oder PS in einen neuen leeren ordner navigieren
8. Das repository in diesen Ordner clonen
9. Dann eine Änderung in VSCode machen (einen punkt in die Readme.md hinzufügen)
10. Aus der PS oder WSL git pull ausführen (achtet darauf, dass ihr in dem repository seid und nicht noch in dem übergeordneten Ordner)

## Aufgabe 12.03.26 - 2:

11. Erstelle über die VS-Code UI (`git checkout -b <branch-name>`)
12. Eine Änderung auf dem neuen Branch machen (neue Datei)
13. Diese Änderung commiten und Branch publishen/pushen
14. Github.com repository verfolgen und die Änderungen auf den unterschiedlichen Branches betrachten

## Andys Git Link

- ![https://learngitbranching.js.org/?locale=de_DE](https://learngitbranching.js.org/?locale=de_DE)
