# careAssistTool
An OpenSource Software-Tool for Care Assistants without overloaded Software-Functions.
Start development: 06.01.2022
kind of Software: Excel365
database: no - not yet integrated
# Target Group / Target audience:
small companies specializing in care management, not care in the true sense of the word.
# German:
kleine Firmen, die sich auf Pflegedienstleitungen (Haushaltsdienste, Einkaufen, Fahrten zu Ärzten, kleinere Gartentätigkeiten, etc.) spezialisiert haben, keine Pflegeleistungen (Medikamentenvergabe, Blutdruck / Puls messen, Wundverpflegung, etc.) im eigentlichen Sinne

# Abstract:
I have been asked if I could present data of customers in need of care "centrally" in an Excel file, so that the overview is not lost and the customers can always be served on time and on schedule. Over time, this became an increasingly powerful Excel file, which now manages and processes about 200 customer files (Excel files) and employee files.
This currently includes:
-Vacation planning
-Employee sick leave
-hourly availability of customers
-hours overview employees (mini-job, part-time employees)

# Hintergrund des Projektes:
German:
Software: Excel 365
Datenbank-Anbindung: nicht geplant - bis jetzt

ich bin gefragt worden, ob ich Daten von pflegebedürftigen Kunden "zentral" in einer Excel-Datei darstellen könnte, damit die Übersicht nicht verloren geht und die Kunden immer pünktlich und termingerecht bedient werden können. Daraus wurde mit der Zeit eine immer mächtigere Excel-Datei, die mittlerweile ca. 200 Kundenakten (Exceldateien) und Mitarbeiter-Akten verwaltet und bearbeitet.
Dazu gehört aktuell:
-Urlaubsplanung
-Krankheitsstand Mitarbeiter
-Stundenverfügbarkeit der Kunden
-Stundenübersicht Mitarbeiter (Mini-Job, Teilzeitkräfte)

# Entwicklungs-Stand:
- "eigentlich" fertig - wer eine Vorab-Version haben will - einfach melden. Ist ansich auch mit vielen Hilfen/Anleitungen versehen...
Umstellung von Excel nach "echter" Software. Geplant ist eine LOKALE Software-Lösung, via Django und Python in Verbindung mit einer "richtigen" Datenbank, welche lokal im User-Büro installiert und bedient wird. Ein Server, worauf alle (Büro-) Mitarbeiter zugreifen können.

# Geplant ist bisher folgendes:
Kundenakten --> Stammdatenbearbeitung (Pflegegrad, verfügbare Std., Anpassungen bei Änderungen zum Pflegerad, 
Mitarbeiterakten --> Einsatzort, Einsatzgebiet(e), Urlaubsplanung, Krankenstand, Gehalt
Leistungsnachweise --> Drucken, verschicken, scannen und autom. Zuordnung zum Kunden
Abrechnung --> gem. § 39 SGB XI; § 45b SGB XI; § 39 SGB XI, Privatabrechnung, gem. Bewilligung, etc. --> Kundenspezifische Abrechnungen

