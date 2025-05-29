# 🎓 Index & Navigation - iad Erfurt Kurse

> **Hinweis:** Diese Repository enthält Beispiele und Materialien aus meinen Kursen an der "iad" in Erfurt.  
> ⚠️ Bei einem "404 Fehler" befinden sich die Repositories möglicherweise im privaten Bereich.

## 📋 Verwendungshinweise

- ✅ **Nutzen Sie die Beispiele als Anregung**
- ❌ **Nicht als fertige Lösung verwenden**
- 🎯 **Setzen Sie sich eigene Ziele**
- 🚀 **Lernen Sie aus Fehlern**
- 💪 **Bleiben Sie am Ball**

## 🚀 Quick Start Guide

### 📋 Repository-Checkliste für neue Projekte
- [ ] README.md erstellen
- [ ] .gitignore hinzufügen
- [ ] LICENSE festlegen
- [ ] Branch-Strategie definieren
- [ ] Issues/Projects einrichten

### 🔍 Repository finden
```bash
# Alle Repositories anzeigen
git clone https://github.com/ydh-embedded/[REPO-NAME].git

# Mit GitHub CLI
gh repo list ydh-embedded
```

---

## 🔗 Nützliche Online-Ressourcen

| Plattform | Beschreibung | Link |
|-----------|--------------|------|
| **Udemy** | Online Video Kurse | [🌐 Zur Website](https://www.udemy.com/) |
| **SoloLearn** | Online Zertifizierung | [🌐 Zur Website](https://www.sololearn.com/de/) |
| **Readly** | Online Magazine | [🌐 Zur Website](https://de.readly.com/) |
| **W3C Validator** | HTML Validierung | [🌐 Zur Website](https://validator.w3.org/) |
| **W3C CSS Validator** | CSS Validierung | [🌐 Zur Website](https://jigsaw.w3.org/css-validator/) |
| **vTiger CRM** | Customer Relationship Management | [🌐 Zur Website](https://www.vtiger.com/de/) |

---

## 💻 C# Referenz-Tabellen

### 🔢 Ganzzahl-Datentypen

| Type | Prefix | .NET Framework Typ | Bits | Wertebereich |
|------|--------|--------------------|------|--------------|
| `sbyte` | - | System.SByte | 8 | -128 bis +127 |
| `byte` | - | System.Byte | 8 | 0 bis +255 |
| `char` | `c` | System.Char | 16 | U+0000 bis U+ffff |
| `short` | - | System.Int16 | 16 | -32.768 bis +32.767 |
| `ushort` | - | System.UInt16 | 16 | 0 bis +65.535 |
| `int` | `i` | System.Int32 | 32 | -2.147.483.648 bis +2.147.483.647 |
| `uint` | - | System.UInt32 | 32 | 0 bis +4.294.967.295 |
| `long` | - | System.Int64 | 64 | -9.223.372.036.854.775.808 bis +9.223.372.036.854.775.807 |
| `ulong` | - | System.UInt64 | 64 | 0 bis +18.446.744.073.709.551.615 |

### 🔢 Gleitkomma-Datentypen

| Type | Prefix | Bits | Wertebereich | Genauigkeit |
|------|--------|------|--------------|-------------|
| `float` | `f` | 32 | -3,4×10³⁸ bis 3,4×10³⁸ | 7 Stellen |
| `double` | `d` | 64 | 5×10⁻³²⁴ bis 1,7×10³⁰⁸ | 15-16 Stellen |
| `decimal` | - | 128 | -1,0×10⁻²⁸ bis +7,9×10²⁸ | 28-29 Stellen |

### ✅ Boolean-Datentyp

| Type | Prefix | Bits | Werte |
|------|--------|------|-------|
| `bool` | `b` | 8 | `true`, `false` |

---

## 🛠️ .NET Terminal-Befehle

| Befehl | Beschreibung | Beispiel-Ausgabe |
|---------|--------------|------------------|
| `dotnet --version` | Zeigt .NET Version | `8.0.401` |
| `dotnet new console --framework net8.0 --use-program-main --force` | Erstellt neue Konsolen-App | Projekt erstellt |
| `dotnet run` | Führt das Projekt aus | - |
| `dotnet build` | Kompiliert das Projekt | - |

### 🔧 MSBuild Befehle

```bash
# Rebuild mit Fehler-Logging
& 'C:\Windows\Microsoft.NET\Framework\v4.0.30319\msbuild.exe' ProjectName.csproj /t:Rebuild /fileLoggerParameters:'LogFile=Build_Errors.md;Verbosity=Diagnostic;Encoding=UTF-8'
```

---

## 📁 Repository-Übersicht

### 🎯 Hauptprojekte

| Repository | Beschreibung | Technologie | Status | Link |
|------------|--------------|-------------|--------|------|
| **Index---Navigation** | Kurs-Navigation und Referenzen | Markdown | ✅ Aktiv | [📂 Repo](https://github.com/ydh-embedded/Index---Navigation) |
| **ydh-embedded** | Profil-Repository | - | ✅ Aktiv | [📂 Repo](https://github.com/ydh-embedded/ydh-embedded) |

### 💻 Öffentliche Repos

| Repository | Beschreibung | Hauptsprache | Schwierigkeitsgrad | Link |
|------------|--------------|--------------|-------------------|------|
| **C# Grundlagen** | C# Einführungsprojekte | C# | 🟢 Beginner | [📂 Repo](#) |
| **Web Development** | Frontend/Backend Projekte | HTML/CSS/JS | 🟡 Intermediate | [📂 Repo](#) |
| **Python Scripts** | Automation & Tools | Python | 🟢 Beginner | [📂 Repo](#) |
| **Database Projects** | SQL & NoSQL Projekte | SQL | 🟡 Intermediate | [📂 Repo](#) |

### 🎓 Kurs-spezifische Repositories

| Kurs/Modul | Repository Name | Technologie | Semester | Link |
|------------|-----------------|-------------|----------|------|
| **Programmierung I** | prog1-exercises | C# | WS 2023/24 | [📂 Repo](#) |
| **Web-Entwicklung** | web-dev-projects | HTML/CSS/JS | SS 2024 | [📂 Repo](#) |
| **Datenbanken** | database-basics | SQL/MySQL | WS 2024/25 | [📂 Repo](#) |
| **Software Engineering** | software-eng | C#/.NET | SS 2025 | [📂 Repo](#) |

### 🔧 Tools & Utilities

| Tool | Zweck | Sprache | Typ | Link |
|------|-------|---------|-----|------|
| **Config Files** | Entwicklungsumgebung | Various | Config | [📂 Repo](#) |
| **Scripts** | Automatisierung | Bash/PowerShell | Tools | [📂 Repo](#) |
| **Templates** | Projekt-Vorlagen | Various | Templates | [📂 Repo](#) |

### 📊 Repository-Statistiken

```
Gesamtanzahl Repositories: [Anzahl]
Hauptsprachen: C#, Python, JavaScript, HTML/CSS
Letzte Aktivität: [Datum]
```

---

## 🤝 Beitrag leisten

Haben Sie Verbesserungsvorschläge oder gefunden Fehler? 
- 🐛 [Issue erstellen](../../issues)
- 🔀 [Pull Request senden](../../pulls)

---

## 📞 Kontakt

Bei Fragen zu den Projekten oder Kursinhalten können Sie gerne Kontakt aufnehmen.

---

*Letzte Aktualisierung: $(date)*