# Terraform Getting Started

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

## Aufgabe:

1. Ihr erstellt einen leeren Ordner bei euch auf dem Computer (nicht in OneDrive)
2. Öffne den leeren Ordner in VSCode
3. Terminal öffnen und `git init`
4. Comitten, reverten , adden etc.
   Tipp: Am besten mit Readme.md und der Nutzung von [Markdown](https://www.markdownguide.org/cheat-sheet/)
