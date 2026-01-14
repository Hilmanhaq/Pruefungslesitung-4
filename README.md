# Portfolioprüfung, Teil 4 (Gruppenpräsentation) – Dokumentation und Code-Qualität Clean Code, Refactoring und Tests – begründet und reflektiert

Dieses Repository bildet das Starterpaket für die Teilprüfung 4(Präsentation: Dokumentation und Code-Qualität Clean Code, Refactoring und Tests – begründet und reflektiert).

## Ziele
1. Codequalität gemeinsam analysieren und erklären kann,
2. Clean-Code-Prinzipien konkret am eigenen Code veranschaulicht,
3. Refactorings zielgerichtet auswählt, priorisiert und begründet,
4. den Zusammenhang zwischen Codequalität, Refactoring und Tests versteht,
5. sowie technische Entscheidungen sachlich verteidigen und reflektieren kann.

## Modulverantwortlichkeiten
• 	models.py – Datenmodell der Person
• 	validation.py – Validierung & Normalisierung von Eingaben
• 	jsonpersistance.py – Laden & Speichern von Daten im JSON-Format
• 	register.py – Geschäftslogik (CRUD)
• 	CLI.py – einfache Kommandozeilenoberfläch

## Clean Code Prinzpien
Das Projekt wurde konsequent nach Clean-Code-Prinzipien überarbeitet:
✔ Single Responsibility Principle
Jedes Modul hat eine klar definierte Aufgabe (Validierung, Persistenz, Registerlogik).
✔ Separation of Concerns
Geschäftslogik, Datenhaltung und Benutzereingaben sind vollständig getrennt.
✔ KISS (Keep It Simple)
Funktionen sind kurz, eindeutig und leicht verständlich.
✔ DRY (Don’t Repeat Yourself)
Normalisierung, Validierung und Persistenzlogik sind zentralisiert und nicht dupliziert.
✔ Meaningful Names
Alle Funktionen und Variablen sind selbsterklärend benannt.

## Refactoring--Fallstudien
1. Auslagerung der Validierung in ein eigenes Modul
2. Trennung der Presistenzschicht
3. Normalisierung vor Validierung



```



## Dokumentation
- Microsoft Word als Schriftliche Dokumentation
