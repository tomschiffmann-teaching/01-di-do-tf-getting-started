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
- `Commit`: Zusammenfassung der veränderten Dateien unter einem Titel
- `Status`: Welche Dateien haben sich verändert
- `Add`
