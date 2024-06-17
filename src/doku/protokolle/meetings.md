# Meetings - TeamC2

* **Projektname:** ParkBlazer
* **Product Owner:** Tim Röckemann, Marvin Petschulat, Jan-Ole Löffler, Timo Haverich, Edwin Dik, Bent Schöne, Mattis Wellenbüscher
* [Link zum Source Code Repository](https://github.com/TeamC2-Softwareprojekt)


--- 


## Weekly-Meeting: 06.05.2024 (Protokollant: Timo Haverich)
### Teilnehmer:
- Tim Röckemann
- Marvin Petschulat,
- Jan-Ole Löffler
- Timo Haverich
- Edwin Dik
- Bent Schöne 
- Mattis Wellenbüscher

### Agenda:
- Einrichtung einer Entwicklungsumgebung mit Kotlin für das ParkBlazer-Projekt.
- Diskussion über alternative Frameworks für die Entwicklung.
- Auswahl eines geeigneten Frameworks und Initialisierung des Projekts.

### Besprechung:
**Einrichtung der Entwicklungsumgebung mit Kotlin:**
Wir begannen das Meeting mit dem Versuch, eine Entwicklungsumgebung für unser ParkBlazer-Projekt mit Kotlin aufzusetzen. Trotz unserer Bemühungen und einiger Fortschritte stießen wir auf verschiedene Herausforderungen, darunter Kompatibilitätsprobleme und eine steile Lernkurve für einige Teammitglieder. Angesichts dieser Hindernisse beschlossen wir, alternative Ansätze zu prüfen.

**Diskussion über alternative Frameworks:**
Angesichts der Schwierigkeiten bei der Einrichtung der Kotlin-Umgebung begannen wir, alternative Frameworks für die Entwicklung zu diskutieren. Nach eingehender Analyse und Diskussion entschieden wir uns für das Ionic Framework aufgrund seiner sehr einfach einzurichtenden plattformübergreifenden Unterstützung, seiner umfangreichen Community und seiner Benutzerfreundlichkeit.

**Auswahl und Initialisierung des Ionic-Projekts:**
Nachdem wir uns für das Ionic Framework entschieden hatten, initialisierten wir umgehend ein Ionic-Projekt. Wir führten eine kurze Schulung durch, um sicherzustellen, dass alle Teammitglieder mit den Grundlagen vertraut sind, und jeder konnte das Projekt erfolgreich auf seinem PC zum Laufen bringen. Dies ermöglichte es uns, einen reibungslosen Start in die Entwicklung zu gewährleisten.

### Nächste Schritte:
- Vertiefung der Kenntnisse im Ionic Framework durch Selbststudium.
- Beginn der eigentlichen Entwicklung von ParkBlazer unter Verwendung des Ionic Frameworks.
- Regelmäßige Updates und Fortschrittsberichte in den kommenden Weekly-Meetings.

### Schlussbemerkung:
Das Meeting war entscheidend für die reibungslose Fortsetzung unseres Projekts. Die Entscheidung für das Ionic Framework verspricht eine effiziente Entwicklung von ParkBlazer. Wir sind zuversichtlich, dass wir mit dieser neuen Richtung unser Ziel erreichen werden.


--- 


## Weekly-Meeting: 08.05.2024 (Protokollant: Timo Haverich)
### Teilnehmer:
- Tim Röckemann
- Timo Haverich
- Edwin Dik
- Bent Schöne 
- Mattis Wellenbüscher

### Agenda:
- Zuweisung von Aufgaben und Verantwortlichkeiten im Team gemäß der technischen Spezifikation 
- Überprüfung des Fortschritts

### Besprechung:
**Verantwortlichkeiten der Implementierung:**
- Authentifizierung / Benutzerprofil: (Timo), Jan-Ole Löffler, Tim Röckemann
- Parkplatz aus DB in Karte anzeigen (Markierung): (Timo), Marvin Petschulat, Mattis Wellenbüscher
- Suche (Umkreis) und anzeige der Parkplätze in Liste: (Timo), Edwin Dik, Bent Schöne

Alle Teams können unabhängig voneinander die ersten Implementierungen vornehmen. Timo Haverich ist als Backend-Developer in allen Teams, damit die Schnittstelle zur DB gewährleistet wird. Alle Teams sollen zunächst Issues im Kanban Board erstellen. Die nächste Besprechung soll am 13.05.2024 stattfinden.

### Nächste Schritte:
- Implementierung der ersten Funktionalitäten im Client und auf dem Server.
- Issues und Milestones erstellen.
- Besprechung am 13.05.2024.

### Schlussbemerkung:
Die heutige Besprechung hat wichtige Fortschritte in Bezug auf die Zuweisung von Aufgaben und Verantwortlichkeiten im Team erzielt. Wir haben klare Verantwortlichkeiten für die Implementierung verschiedener Funktionen definiert und sind bereit, unabhängig voneinander mit den ersten Umsetzungen zu beginnen. Die Priorisierung der Authentifizierung und des Benutzerprofils, der Anzeige von Parkplätzen auf der Karte sowie der Suchfunktion und Anzeige von Parkplätzen in einer Liste wurde festgelegt. Timo Haverich wird als Backend-Developer in allen Teams eingebunden, um die Schnittstelle zur Datenbank sicherzustellen. Als nächste Schritte werden die Implementierung der ersten Funktionalitäten, das Erstellen von Issues und Milestones sowie die Vorbereitung auf die nächste Besprechung am 13.05.2024 durchgeführt.


--- 


## Weekly-Meeting: 13.05.2024 (Protokollant: Timo Haverich)
### Teilnehmer:
- Tim Röckemann
- Marvin Petschulat
- Timo Haverich
- Edwin Dik
- Bent Schöne 
- Mattis Wellenbüscher
- Jan-Ole Löffler

### Agenda:
- Besprechung der Fortschritte der Aufgaben
- Klärung von Fragen
- Planung der nächsten Schritte
- Besprechung von Problemen

### Besprechung:
- Vorstellung aller Implementierungen
    - Bent und Edwin präsentierten ihre Arbeit an der Parkplatzliste.
    - Marvin stellte seine Kartenimplementierung mit Markern vor.
    - Timo gab einen Überblick über den Stand der Serverentwicklung.

Nach der Vorstellung der Implementierungen diskutierten wir die noch offenen Punkte und die nächsten Schritte.

### Nächste Schritte:
- Server-Bereitstellung: Implementierung der Funktionalitäten zur Anzeige von Parkplätzen mit allen relevanten Informationen, Erstellung und Löschung von Parkplätzen, Implementierung von Login und Registrierung.
- Dynamische Befüllung der Karte mit Markern, um Parkplätze anzuzeigen.
- Dynamische Befüllung der Liste mit Markern, um Parkplätze anzuzeigen.
- Verknüpfung der Liste und der Karte, um eine nahtlose Benutzererfahrung zu gewährleisten.

### Schlussbemerkung:
Nach einer produktiven Besprechung sind wir mit einem klaren Fahrplan für die nächsten Schritte ausgestattet. Jeder hat seine Implementierung vorgestellt, was zu einem umfassenden Verständnis des aktuellen Standes geführt hat. Die Fortschritte von Bent und Edwin bei der Parkplatzliste sowie Marvins Arbeit an der Kartenimplementierung wurden präsentiert. Timos Fortschritte bei der Serverentwicklung sind ebenfalls vorgestellt worden.

Wir haben identifiziert, dass die Priorität nun auf der Server-Bereitstellung liegt, gefolgt von der dynamischen Befüllung der Karte und Liste mit Markern. Zusätzlich ist es wichtig, die beiden Darstellungsformen miteinander zu verknüpfen, um eine nahtlose Benutzererfahrung zu gewährleisten.


--- 


## Weekly-Meeting: 20.05.2024 (Protokollant: Timo Haverich)
### Teilnehmer:
- Tim Röckemann
- Marvin Petschulat
- Timo Haverich
- Edwin Dik
- Bent Schöne 
- Jan-Ole Löffler
- Mattis Wellenbüscher

### Agenda:
- Besprechung der Fortschritte der Aufgaben
- Klärung von Fragen
- Planung der nächsten Schritte
- Besprechung von Problemen
- Pull Requests erstellen

### Besprechung:
- **Vorstellung aller Implementierungen:**
    - **Bent und Edwin:** Präsentierten ihren Fortschritt bei der Entwicklung der Parkplatzliste, inklusive neuer Funktionen und Bugfixes.
    - **Marvin:** Stellte die fortgeschrittene Kartenimplementierung vor, die jetzt Marker aus der Datenbank dynamisch einbindet.
    - **Timo, Tim, Ole:** Gab einen detaillierten Überblick über den aktuellen Stand der Serverentwicklung und der Datenbankintegration, einschließlich der neuesten Performance-Optimierungen.

### Nächste Schritte:
- Durchführung von Code Reviews für die eingereichten Pull Requests.
- Bearbeitung und Behebung von Feedback aus den Code Reviews.
- Zusammenführen (Mergen) der verschiedenen Entwicklungen in den Hauptbranch.
- Detaillierte Planung der nächsten Aufgaben, basierend auf den aktuellen Projektanforderungen und den Fortschritten der letzten Woche.

### Schlussbemerkung:
Das Meeting war produktiv und zielorientiert. Die Fortschritte in den verschiedenen Bereichen sind vielversprechend, und die nächsten Schritte wurden klar definiert. Wir sind zuversichtlich, dass wir durch die Zusammenarbeit und das kontinuierliche Feedback die Projektziele effizient erreichen werden. Bitte stellt sicher, dass alle offenen Fragen und Unklarheiten zeitnah geklärt werden, um Verzögerungen zu vermeiden. 


--- 


## Weekly-Meeting: 28.05.2024 (Protokollant: Timo Haverich)

### Teilnehmer:
- Tim Röckemann
- Marvin Petschulat
- Timo Haverich
- Edwin Dik
- Bent Schöne 
- Jan-Ole Löffler
- Mattis Wellenbüscher

### Agenda:
- Besprechung der nächsten Aufgaben
- Fortschritt der laufenden Projekte
- Klärung aufgetretener Probleme

### Besprechung:
- Marvin präsentierte den aktuellen Fortschritt bei der Entwicklung der Kartenfunktionalität. Es wurden wichtige Meilensteine erreicht, die die weitere Arbeit erleichtern.
- Bent berichtete über den Fortschritt bei der Listenfunktion. Er hob die Implementierung wichtiger Features hervor, die die Benutzerfreundlichkeit deutlich verbessern.
- Es wurde beschlossen, sich an der AirBnB-Anwendung als Vorlage zu orientieren, um bewährte Design- und Funktionsmuster zu übernehmen.
- Die aktuellen Pull Requests werden zeitnah gemergt, um die neuesten Änderungen und Verbesserungen im Code zu integrieren.
- Die Aufgabenverteilung für die nächsten Schritte wurde festgelegt, um die Effizienz im Team zu maximieren.

### Nächste Schritte:
- **Edwin, Bent**: Implementierung eines Filtersystems für die Liste, um die Suche nach spezifischen Einträgen zu erleichtern.
- **Tim, Ole**: Entwicklung und Verfeinerung der Benutzerprofil-Funktionalität, einschließlich der Verwaltung persönlicher Daten und Präferenzen.
- **Marvin, Mattis**: Platzierung von Markern auf der Karte durch Klick, sowie die Nutzung des aktuellen Standorts zur besseren Benutzererfahrung.
- **Timo**: Optimierung des Server Deployments, Sicherstellung eines konsistenten Datenbankzustands für Testzwecke, Implementierung von Passwort-Hashing und Verbesserung der Datenbankverbindungen.

### Schlussbemerkung:
Das Meeting war sehr produktiv und alle Teilnehmer haben klar umrissene Aufgaben für die kommende Woche erhalten. Durch die gute Zusammenarbeit und den regen Austausch konnten wichtige Fortschritte erzielt werden. Die Orientierung an bewährten Vorlagen wie AirBnB wird helfen, die Anwendung weiter zu verbessern und die Nutzererfahrung zu optimieren. Das Team blickt zuversichtlich auf die nächsten Schritte und freut sich auf die weiteren Entwicklungen.


--- 


## Weekly-Meeting: 03.06.2024 (Protokollant: Timo Haverich)

### Teilnehmer:
- Tim Röckemann
- Marvin Petschulat
- Timo Haverich
- Edwin Dik
- Jan-Ole Löffler
- Mattis Wellenbüscher
- Bent Schöne 


### Agenda:
- Besprechung der nächsten Aufgaben
- Fortschritt der laufenden Projekte
- Klärung aufgetretener Probleme

### Besprechung:
- Jeder stellt seine Fortschritte vor
- Aufgabenverteilung für die Woche zur Erreichung des MVP
- Implementierung und Durchführung von Tests

### Nächste Schritte:
- Bearbeitung der Aufgaben zur Fertigstellung des MVP

### Schlussbemerkung:
Die Besprechung verlief produktiv und zielgerichtet. Die definierten Aufgaben und nächsten Schritte wurden klar kommuniziert, sodass alle Teammitglieder wissen, was in der kommenden Woche zu tun ist.


--- 


## MVP-Meeting: 06.06.2024 (Protokollant: Timo Haverich)

### Teilnehmer:
- Tim Röckemann
- Marvin Petschulat
- Timo Haverich
- Edwin Dik
- Jan-Ole Löffler
- Bent Schöne 
- Mattis Wellenbüscher

### Agenda:
- Fortschritte besprechen
- Issues erstellen

### Besprechung:
- Tim, Ole: Passwort-Zurücksetzen, Logout-Fehler beheben
- Timo: Parkplatz-Detailseite
- Mattis: Parkplätze anlegen durch auf Map klicken
- Bent: Filter erweitern
- Edwin: Anlegen von privaten Parkplätzen

### Nächste Schritte:
- Pull requests erstellen
- Code reviews
- Mergen der Branches

### Schlussbemerkung:
Die Besprechung verlief produktiv und zielgerichtet. Die definierten Aufgaben und nächsten Schritte wurden klar kommuniziert, sodass alle Teammitglieder wissen, was in der kommenden Woche zu tun ist.


--- 


## MVP-Meeting: 17.06.2024 (Protokollant: Timo Haverich)

### Teilnehmer:
- Tim Röckemann
- Marvin Petschulat
- Timo Haverich
- Edwin Dik
- Jan-Ole Löffler
- Mattis Wellenbüscher

### Agenda:
- Ergebnisse der Bearbeitungsphase vorstellen
- Nächste Aufgaben besprechen 

### Besprechung:
- Vorstellung der Implementierungen
    - **Marvin, Mattis:** Parkplatz anlegen durch klick auf die Karte und anbinden einer Country-Selector API, JWT Verifizierung eigebunden
    - **Tim, Ole:** Implementierung Passwort-Vergessen Seite
    - **Timo:** Implementierung einer Cloudinary-API zur Speicherung von Bildern in einer cloud und einer Parkplatzdetailseite mit Review-Funktion
    - **Bent, Ole:** Erstellung von Privaten Parkplätzen und Finalisierung des Filters


### Nächste Schritte:
- Pull requests
- Code reviews
- Mergen der Branches

### Schlussbemerkung:
Die Besprechung verlief produktiv und zielgerichtet. Die definierten Aufgaben und nächsten Schritte wurden klar kommuniziert, sodass alle Teammitglieder wissen, was in der kommenden Woche zu tun ist.

