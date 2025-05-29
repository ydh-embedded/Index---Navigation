
# 💻 Tech Stack:
![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white) ![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white) ![Windows Terminal](https://img.shields.io/badge/Windows%20Terminal-%234D4D4D.svg?style=for-the-badge&logo=windows-terminal&logoColor=white) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![Linode](https://img.shields.io/badge/linode-00A95C?style=for-the-badge&logo=linode&logoColor=white) ![Azure](https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) ![.Net](https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white) ![Ionic](https://img.shields.io/badge/Ionic-%233880FF.svg?style=for-the-badge&logo=Ionic&logoColor=white) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![SASS](https://img.shields.io/badge/SASS-hotpink.svg?style=for-the-badge&logo=SASS&logoColor=white) ![Symfony](https://img.shields.io/badge/symfony-%23000000.svg?style=for-the-badge&logo=symfony&logoColor=white) ![WordPress](https://img.shields.io/badge/WordPress-%23117AC9.svg?style=for-the-badge&logo=WordPress&logoColor=white) ![Apache](https://img.shields.io/badge/apache-%23D42029.svg?style=for-the-badge&logo=apache&logoColor=white) ![AmazonDynamoDB](https://img.shields.io/badge/Amazon%20DynamoDB-4053D6?style=for-the-badge&logo=Amazon%20DynamoDB&logoColor=white) ![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white) ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) ![Adobe](https://img.shields.io/badge/adobe-%23FF0000.svg?style=for-the-badge&logo=adobe&logoColor=white) ![Adobe InDesign](https://img.shields.io/badge/Adobe%20InDesign-49021F?style=for-the-badge&logo=adobeindesign&logoColor=FF3366) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![Raspberry Pi](https://img.shields.io/badge/-Raspberry_Pi-C51A4A?style=for-the-badge&logo=Raspberry-Pi) ![Trello](https://img.shields.io/badge/Trello-%23026AA7.svg?style=for-the-badge&logo=Trello&logoColor=white) ![Ubiquiti](https://img.shields.io/badge/ubiquiti-%230559C9.svg?style=for-the-badge&logo=ubiquiti&logoColor=white) ![Steam](https://img.shields.io/badge/steam-%23000000.svg?style=for-the-badge&logo=steam&logoColor=white)







# Index---Navigation



<div style="border: 1px solid #ccc; padding: 10px; border-radius: 5px; background: darkcyan; font-family: consolas,Handjet,Englebert, Exo; color: lightgrey; background: black;">

 - [ ] Hallo Freunde der Technik.
   anbei findet Ihr Beispiele zu den Kursen und Modulen die ich an der "iad" in Erfurt absolviert habe
 - [ ] Falls Ihr den Fehler "404 Seite nicht gefunden" bekommt sind die Seiten leider im privaten Repository gelandet 
 - [ ] Verwendet die Beispiele gerne als Anregung aber nicht als fertige Lösung, da dies nicht Ziel dieser Dokumentation ist! 
 - [ ] Beginnt neue Aufgaben und setzt euch Ziele - Das Internet bietet euch Wege diese zu erreichen
 - [ ] Macht Fehler und bleibt am Ball nur daraus lernt man 
 
  
</div>

____________

## WebSites Empfehlungen


- [ ] *udemy* - Online Video Kurse [[Link to Website]](https://www.udemy.com/)
- [ ] *sololearn* - Online Certification [[Link to Website]](https://www.sololearn.com/de/)
- [ ] *readly* - Online Magazine [[Link to Website]](https://de.readly.com/)

- [ ] *w3* - WebSite Validierung [[Link to Website]](https://validator.w3.org/)
- [ ] *w3* - CSS Validierung [[Link to Website]](https://jigsaw.w3.org/css-validator/)

- [ ] *vTiger* - Costumer Relationship Management CRM für KMU und StartUps[[Link to Website]](https://www.vtiger.com/de/)


____________

  

  ![Cert](./JPEG/cert.jpg)




____________



#### elementare Dateitypen in cSharp


| c# - Type | Prefix |  .NET-Framework-Typ | runtime enviromental allocates | Größe der Ganzzahlenwerte |
| --- | --- | --- | --- | --- |
| sbyte     |  |  System.SByte       | [8bits]  |   -128 bis + 127  | 
| byte      |  |  System.Byte        | [8bits]  |     0 bis + 255   |
| char      | cVariable |System.Char | [16bits]  | U+0000 bis U+ffff |
| short     |  |  System.Int16       | [16bits] | -32768 bis +32767 | 
| ushort    |  |  System.UInt16      | [16bits] |     0 bis +65535  |
| int       | iVariable |System.Int32| [32bits] |-2.147.483.648 bis +2.147.483.647 |
| uint      |  |  System.UInt32      | [32bits] |      0 bis +4.294.967.295        |
| long      |  |  System.Int64       | [64bits] | -9.223.372.036.854.775.808 bis +9.223.372.036.854.775.807 |
| ulong     |  |  System.UInt64      | [64bits] |     0 bis +18.446.744.073.709.551.615 |

| c# - Type | Prefix | runtime enviromental allocates |  Range der Gleitkommazahlen | Genauigkeit |
| --- | --- | --- | --- | --- |
| float     | fVariable | [32bits] |  -3,4x10^38 bis 3,4x10^38      |       7 Stellen nach dem Komma  |
| double    | dVariable | [64bits] |  5x10^-324 bis 1,7x10^308      |   15-16 Stellen nach dem Komma  |
| decimal   |  | [128bits] |  -1,0x10^-28 bis +7,9x10^28    |   28-29 Stellen nach dem Komma  |

| c# - Type | Prefix | runtime enviromental allocates |  Wert 1 | wert 2 |
| --- | --- | --- | --- | --- |
| bool      | bVariable | [8bits]  | true | false |

| .NET |  Terminal Befehle | (base) PS C:\working-directory\cSharp-Beginner\beginner\Social_Network_XP35>   | Ausgabe   |
| --- | --- | --- | --- |
|      | dotnet --version   |  | 8.0.401 |
|      | dotnet new console --framework net8.0 --use-program-main --force  |  | [...] |
|      | && dotnet --version > dotnet_version.md |  | [dotnet_version.md] |
|      | dotnet run  |  |  |
|      | | "& 'C:\Windows\Microsoft.NET\Framework\v4.0.30319\msbuild.exe' 16_Bug_Report.csproj /t:Rebuild /fileLoggerParameters:'LogFile=Bug_Errors.md;Verbosity=Diagnostic;Encoding=UTF-8'" | [Bug_Errors.md] |

_________________________

## Backend
  
| Kapitel | PDF | Markdown | PRG |
| --- | --- | --- | --- |
| Python-Compiler | [[ ... ]](https://github.com/ydh-embedded/2024-Summary/blob/main/Backend/python-compiler/2024-03-21---python-compy.pdf)  | [[Privat Link to Markdown Files]](https://github.com/ydh-embedded/2024-Summary/blob/main/Backend/python-compiler/compy.md)   | [[Privat Link to Code Snipped]](https://github.com/ydh-embedded/2024-Summary/blob/main/Backend/python-compiler/com.py)   |
| cSharp-SQL     | [[Privat Link to PDF]](https://github.com/ydh-embedded/Scrum/blob/main/docs/PDF/2024-08-05---vorgehensmodelle.pdf)  | [[Privat Link to Index]](https://github.com/ydh-embedded/2024-Summary/blob/main/Backend/Datenbanken/cSharp---sql/README.md)   | [[Privat Link to Screenshots]](https://github.com/ydh-embedded/2024-Summary/tree/main/Backend/Datenbanken/cSharp---sql/docs/screen)   |
| Python-3.7.16     | [[ ... ]](https://github.com/ydh-embedded/2024-Summary/blob/main/Backend/Python-3.7.16/docs/PDF/2024-07-11---Pyenv-python-enviromental.pdf)  | [[ ... ]](https://github.com/ydh-embedded/2024-Summary/tree/main/Backend/Python-3.7.16/docs)   | [[Privat Link to CodeSnippeds]](https://github.com/ydh-embedded/2024-Summary/tree/main/Backend/Python-3.7.16/docs)   |
| Python     | [[ ... ]](https://github.com/ydh-embedded/2024-Summary/blob/main/Backend/Python/docs/PDF/2024-07-12---Conda.pdf)  | [[Privat Link to Markdown Files]](https://github.com/ydh-embedded/2024-Summary/blob/main/Backend/Python/docs/md/2024-06-28%20Python.md)   | [[ ... ]]()   |
| SQL-Beginners     | [[Privat Link to PDF]](https://github.com/ydh-embedded/Scrum/blob/main/docs/PDF/2024-08-05---vorgehensmodelle.pdf)  | [[Privat Link to Markdown Files]](https://github.com/ydh-embedded/Scrum/blob/main/docs/md/2024-08-05---vorgehensmodelle.md)   | [[Privat Link to Screenshots]](https://github.com/ydh-embedded/Scrum/blob/main/docs/screens/)   |
| cSharp-Beginners     | [[ ... ]](...)  | [[Link to Markdown Files]](https://github.com/ydh-embedded/cSharp-Beginner/tree/main)   | [[ ... ]](...)   |

____________

## Frontend
  
| Kapitel | PDF | Markdown | Screenshoots |
| --- | --- | --- | --- |
| CSS | [[Privat Link to PDF]](https://github.com/ydh-embedded/Scrum/blob/main/docs/PDF/2024-08-05---vorgehensmodelle.pdf)  | [[Privat Link to Markdown Files]](https://github.com/ydh-embedded/Scrum/blob/main/docs/md/2024-08-05---vorgehensmodelle.md)   | [[Privat Link to Screenshots]](https://github.com/ydh-embedded/Scrum/blob/main/docs/screens/)   |
| jdk     | [[ ... ]](https://github.com/ydh-embedded/Scrum/blob/main/docs/PDF/2024-08-05---vorgehensmodelle.pdf)  | [[Privat Link to Markdown Files]](https://github.com/ydh-embedded/Scrum/blob/main/docs/md/2024-08-05---vorgehensmodelle.md)   | [[Privat Link to Screenshots]](https://github.com/ydh-embedded/Scrum/blob/main/docs/screens/)   |
| Java-Fundamentals     | [[Privat Link to PDF]](https://github.com/ydh-embedded/Scrum/blob/main/docs/PDF/2024-08-05---vorgehensmodelle.pdf)  | [[Privat Link to Markdown Files]](https://github.com/ydh-embedded/Scrum/blob/main/docs/md/2024-08-05---vorgehensmodelle.md)   | [[Privat Link to Screenshots]](https://github.com/ydh-embedded/Scrum/blob/main/docs/screens/)   |
| Scrum     | [[Privat Link to PDF]](https://github.com/ydh-embedded/Scrum/blob/main/docs/PDF/2024-08-05---vorgehensmodelle.pdf)  | [[Privat Link to Markdown Files]](https://github.com/ydh-embedded/Scrum/blob/main/docs/md/2024-08-05---vorgehensmodelle.md)   | [[Privat Link to Screenshots]](https://github.com/ydh-embedded/Scrum/blob/main/docs/screens/)   |
| React     | [[ ... ]](https://github.com/ydh-embedded/Scrum/blob/main/docs/PDF/2024-08-05---vorgehensmodelle.pdf)  | [[Privat Link to Markdown Files]](https://github.com/ydh-embedded/Scrum/blob/main/docs/md/2024-08-05---vorgehensmodelle.md)   | [[Privat Link to Screenshots]](https://github.com/ydh-embedded/Scrum/blob/main/docs/screens/)   |
| Type-Script     | [[ ... ]](https://github.com/ydh-embedded/Scrum/blob/main/docs/PDF/2024-08-05---vorgehensmodelle.pdf)  | [[Privat Link to Markdown Files]](https://github.com/ydh-embedded/Scrum/blob/main/docs/md/2024-08-05---vorgehensmodelle.md)   | [[Privat Link to Screenshots]](https://github.com/ydh-embedded/Scrum/blob/main/docs/screens/)   |
| svg     | [[Privat Link to PDF]](https://github.com/ydh-embedded/Scrum/blob/main/docs/PDF/2024-08-05---vorgehensmodelle.pdf)  | [[Privat Link to Markdown Files]](https://github.com/ydh-embedded/Scrum/blob/main/docs/md/2024-08-05---vorgehensmodelle.md)   | [[Privat Link to Screenshots]](https://github.com/ydh-embedded/Scrum/blob/main/docs/screens/)   |
| jquery     |  | [[Link to Markdown Files]](https://github.com/ydh-embedded/nodeJS/blob/main/docs/md/2024-10-22---jQuery.md)   |    |

___________

## Technik

### Tools

| Kapitel | PDF | Markdown | Screenshoots |
| --- | --- | --- | --- |
| Git-Ignore     | [[ ... ]](https://github.com/ydh-embedded/Scrum/blob/main/docs/PDF/2024-08-05---vorgehensmodelle.pdf)  | [[Privat Link to Markdown Files]](https://github.com/ydh-embedded/Scrum/blob/main/docs/md/2024-08-05---vorgehensmodelle.md)   | [[Privat Link to Screenshots]](https://github.com/ydh-embedded/Scrum/blob/main/docs/screens/)   |
| DEV-Tools     | [[Privat Link to PDF]](https://github.com/ydh-embedded/Scrum/blob/main/docs/PDF/2024-08-05---vorgehensmodelle.pdf)  | [[Privat Link to Markdown Files]](https://github.com/ydh-embedded/Scrum/blob/main/docs/md/2024-08-05---vorgehensmodelle.md)   | [[Privat Link to Screenshots]](https://github.com/ydh-embedded/Scrum/blob/main/docs/screens/)   |
| Terminal    | [[ ... ]](https://github.com/ydh-embedded/Scrum/blob/main/docs/PDF/2024-08-05---vorgehensmodelle.pdf)  | [[Privat Link to Markdown Files]](https://github.com/ydh-embedded/Scrum/blob/main/docs/md/2024-08-05---vorgehensmodelle.md)   | [[Privat Link to Screenshots]](https://github.com/ydh-embedded/Scrum/blob/main/docs/screens/)   |
| Biome     | [[ ... ]](https://github.com/ydh-embedded/Scrum/blob/main/docs/PDF/2024-08-05---vorgehensmodelle.pdf)  | [[Privat Link to Markdown Files]](https://github.com/ydh-embedded/Scrum/blob/main/docs/md/2024-08-05---vorgehensmodelle.md)   | [[Privat Link to Screenshots]](https://github.com/ydh-embedded/Scrum/blob/main/docs/screens/)   |
| SSH-Server    | [[Privat Link to PDF]](https://github.com/ydh-embedded/Scrum/blob/main/docs/PDF/2024-08-05---vorgehensmodelle.pdf)  | [[Privat Link to Markdown Files]](https://github.com/ydh-embedded/Scrum/blob/main/docs/md/2024-08-05---vorgehensmodelle.md)   | [[Privat Link to Screenshots]](https://github.com/ydh-embedded/Scrum/blob/main/docs/screens/)   |
| eMail-Server     | [[Privat Link to PDF]](https://github.com/ydh-embedded/Scrum/blob/main/docs/PDF/2024-08-05---vorgehensmodelle.pdf)  | [[Privat Link to Markdown Files]](https://github.com/ydh-embedded/Scrum/blob/main/docs/md/2024-08-05---vorgehensmodelle.md)   | [[Privat Link to Screenshots]](https://github.com/ydh-embedded/Scrum/blob/main/docs/screens/)   |
| SEO     | [[Privat Link to PDF]](https://github.com/ydh-embedded/Scrum/blob/main/docs/PDF/2024-08-05---vorgehensmodelle.pdf)  | [[Privat Link to Markdown Files]](https://github.com/ydh-embedded/Scrum/blob/main/docs/md/2024-08-05---vorgehensmodelle.md)   | [[Privat Link to Screenshots]](https://github.com/ydh-embedded/Scrum/blob/main/docs/screens/)   |
| IT-SEC     | [[Privat Link to PDF]](https://github.com/ydh-embedded/Scrum/blob/main/docs/PDF/2024-08-05---vorgehensmodelle.pdf)  | [[Privat Link to Markdown Files]](https://github.com/ydh-embedded/Scrum/blob/main/docs/md/2024-08-05---vorgehensmodelle.md)   | [[Privat Link to Screenshots]](https://github.com/ydh-embedded/Scrum/blob/main/docs/screens/)   |
| Powershell     | [[Privat Link to PDF]](https://github.com/ydh-embedded/Scrum/blob/main/docs/PDF/2024-08-05---vorgehensmodelle.pdf)  | [[Privat Link to Markdown Files]](https://github.com/ydh-embedded/Scrum/blob/main/docs/md/2024-08-05---vorgehensmodelle.md)   | [[Privat Link to Screenshots]](https://github.com/ydh-embedded/Scrum/blob/main/docs/screens/)   |
| vsCode     | [[Privat Link to PDF]](https://github.com/ydh-embedded/Scrum/blob/main/docs/PDF/2024-08-05---vorgehensmodelle.pdf)  | [[Privat Link to Markdown Files]](https://github.com/ydh-embedded/Scrum/blob/main/docs/md/2024-08-05---vorgehensmodelle.md)   | [[Privat Link to Screenshots]](https://github.com/ydh-embedded/Scrum/blob/main/docs/screens/)   |
| Batch     | [[ ... ]](https://github.com/ydh-embedded/Scrum/blob/main/docs/PDF/2024-08-05---vorgehensmodelle.pdf)  | [[Privat Link to Markdown Files]](https://github.com/ydh-embedded/Scrum/blob/main/docs/md/2024-08-05---vorgehensmodelle.md)   | [[Privat Link to Screenshots]](https://github.com/ydh-embedded/Scrum/blob/main/docs/screens/)   |
| Winget     | [[ ... ]](https://github.com/ydh-embedded/Scrum/blob/main/docs/PDF/2024-08-05---vorgehensmodelle.pdf)  | [[Privat Link to Markdown Files]](https://github.com/ydh-embedded/Scrum/blob/main/docs/md/2024-08-05---vorgehensmodelle.md)   | [[Privat Link to Screenshots]](https://github.com/ydh-embedded/Scrum/blob/main/docs/screens/)   |


#### Cloud-Anwendungen


| Kapitel | PDF | Markdown | Screenshoots |
| --- | --- | --- | --- |
| BitBucket     | [[Privat Link to PDF]](https://github.com/ydh-embedded/Scrum/blob/main/docs/PDF/2024-08-05---vorgehensmodelle.pdf)  | [[Privat Link to Markdown Files]](https://github.com/ydh-embedded/Scrum/blob/main/docs/md/2024-08-05---vorgehensmodelle.md)   | [[Privat Link to Screenshots]](https://github.com/ydh-embedded/Scrum/blob/main/docs/screens/)   |
| Telegram     | [[Privat Link to PDF]](https://github.com/ydh-embedded/Scrum/blob/main/docs/PDF/2024-08-05---vorgehensmodelle.pdf)  | [[Privat Link to Markdown Files]](https://github.com/ydh-embedded/Scrum/blob/main/docs/md/2024-08-05---vorgehensmodelle.md)   | [[Privat Link to Screenshots]](https://github.com/ydh-embedded/Scrum/blob/main/docs/screens/)   |
| Jira     | [[Privat Link to PDF]](https://github.com/ydh-embedded/Scrum/blob/main/docs/PDF/2024-08-05---vorgehensmodelle.pdf)  | [[Privat Link to Markdown Files]](https://github.com/ydh-embedded/Scrum/blob/main/docs/md/2024-08-05---vorgehensmodelle.md)   | [[Privat Link to Screenshots]](https://github.com/ydh-embedded/Scrum/blob/main/docs/screens/)   |
| gitHUB     | [[Privat Link to PDF]](https://github.com/ydh-embedded/Scrum/blob/main/docs/PDF/2024-08-05---vorgehensmodelle.pdf)  | [[Privat Link to Markdown Files]](https://github.com/ydh-embedded/Scrum/blob/main/docs/md/2024-08-05---vorgehensmodelle.md)   | [[Privat Link to Screenshots]](https://github.com/ydh-embedded/Scrum/blob/main/docs/screens/)   |
| GitLab     | [[Privat Link to PDF]](https://github.com/ydh-embedded/Scrum/blob/main/docs/PDF/2024-08-05---vorgehensmodelle.pdf)  | [[Privat Link to Markdown Files]](https://github.com/ydh-embedded/Scrum/blob/main/docs/md/2024-08-05---vorgehensmodelle.md)   | [[Privat Link to Screenshots]](https://github.com/ydh-embedded/Scrum/blob/main/docs/screens/)   |
