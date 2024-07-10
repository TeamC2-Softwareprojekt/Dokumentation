# Meetings - TeamC2

* **Projektname:** ParkBlazer
* **Product Owner:** Tim Röckemann, Marvin Petschulat, Jan-Ole Löffler, Timo Haverich, Edwin Dik, Bent Schöne, Mattis Wellenbüscher
* [Link zum Source Code Repository](https://github.com/TeamC2-Softwareprojekt)

---

## Weekly-Meeting: 06.05.2024 (Protokollant: Timo Haverich)

### Teilnehmer:
- Tim Röckemann
- Marvin Petschulat
- Jan-Ole Löffler
- Timo Haverich
- Edwin Dik
- Bent Schöne 
- Mattis Wellenbüscher

### Agenda:
- Einrichtung einer Entwicklungsumgebung mit Kotlin für das ParkBlazer-Projekt
- Diskussion über alternative Frameworks für die Entwicklung
- Auswahl eines geeigneten Frameworks und Initialisierung des Projekts

### Besprechung:

**Einrichtung der Entwicklungsumgebung mit Kotlin:**
Wir begannen das Meeting mit dem Versuch, eine Entwicklungsumgebung für unser ParkBlazer-Projekt mit Kotlin aufzusetzen. Trotz unserer Bemühungen und einiger Fortschritte stießen wir auf verschiedene Herausforderungen, darunter Kompatibilitätsprobleme und eine steile Lernkurve für einige Teammitglieder. Angesichts dieser Hindernisse beschlossen wir, alternative Ansätze zu prüfen.

**Diskussion über alternative Frameworks:**
Angesichts der Schwierigkeiten bei der Einrichtung der Kotlin-Umgebung begannen wir, alternative Frameworks für die Entwicklung zu diskutieren. Nach eingehender Analyse und Diskussion entschieden wir uns für das Ionic Framework aufgrund seiner sehr einfach einzurichtenden plattformübergreifenden Unterstützung, seiner umfangreichen Community und seiner Benutzerfreundlichkeit.

**Auswahl und Initialisierung des Ionic-Projekts:**
Nachdem wir uns für das Ionic Framework entschieden hatten, initialisierten wir umgehend ein Ionic-Projekt. Wir führten eine kurze Schulung durch, um sicherzustellen, dass alle Teammitglieder mit den Grundlagen vertraut sind, und jeder konnte das Projekt erfolgreich auf seinem PC zum Laufen bringen. Dies ermöglichte es uns, einen reibungslosen Start in die Entwicklung zu gewährleisten.

### Nächste Schritte:
- Vertiefung der Kenntnisse im Ionic Framework durch Selbststudium
- Beginn der eigentlichen Entwicklung von ParkBlazer unter Verwendung des Ionic Frameworks
- Regelmäßige Updates und Fortschrittsberichte in den kommenden Weekly-Meetings

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
- **Authentifizierung / Benutzerprofil:** Timo, Jan-Ole Löffler, Tim Röckemann
- **Parkplatz aus DB in Karte anzeigen (Markierung):** Timo, Marvin Petschulat, Mattis Wellenbüscher
- **Suche (Umkreis) und Anzeige der Parkplätze in Liste:** Timo, Edwin Dik, Bent Schöne

Alle Teams können unabhängig voneinander die ersten Implementierungen vornehmen. Timo Haverich ist als Backend-Developer in allen Teams, damit die Schnittstelle zur DB gewährleistet wird. Alle Teams sollen zunächst Issues im Kanban Board erstellen. Die nächste Besprechung soll am 13.05.2024 stattfinden.

### Nächste Schritte:
- Implementierung der ersten Funktionalitäten im Client und auf dem Server
- Issues und Milestones erstellen
- Vorbereitung auf die Besprechung am 13.05.2024

### Schlussbemerkung:
Die heutige Besprechung hat wichtige Fortschritte in Bezug auf die Zuweisung von Aufgaben und Verantwortlichkeiten im Team erzielt. Wir haben klare Verantwortlichkeiten für die Implementierung verschiedener Funktionen definiert und sind bereit, unabhängig voneinander mit den ersten Umsetzungen zu beginnen. Timo Haverich wird als Backend-Developer in allen Teams eingebunden, um die Schnittstelle zur Datenbank sicherzustellen. Als nächste Schritte werden die Implementierung der ersten Funktionalitäten, das Erstellen von Issues und Milestones sowie die Vorbereitung auf die nächste Besprechung am 13.05.2024 durchgeführt.

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

**Vorstellung aller Implementierungen:**
- **Bent und Edwin:** Präsentierten ihre Arbeit an der Parkplatzliste.
- **Marvin:** Stellte seine Kartenimplementierung mit Markern vor.
- **Timo:** Gab einen Überblick über den Stand der Serverentwicklung.

Nach der Vorstellung der Implementierungen diskutierten wir die noch offenen Punkte und die nächsten Schritte.

### Nächste Schritte:
- **Server-Bereitstellung:** Implementierung der Funktionalitäten zur Anzeige von Parkplätzen mit allen relevanten Informationen, Erstellung und Löschung von Parkplätzen, Implementierung von Login und Registrierung
- **Dynamische Befüllung der Karte mit Markern, um Parkplätze anzuzeigen**
- **Dynamische Befüllung der Liste mit Markern, um Parkplätze anzuzeigen**
- **Verknüpfung der Liste und der Karte, um eine nahtlose Benutzererfahrung zu gewährleisten**

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

**Vorstellung aller Implementierungen:**
- **Bent und Edwin:** Präsentierten ihren Fortschritt bei der Entwicklung der Parkplatzliste, inklusive neuer Funktionen und Bugfixes
- **Marvin, Ole:** Stellte die fortgeschrittene Kartenimplementierung vor, die jetzt Marker aus der Datenbank dynamisch einbindet
- **Timo, Tim, Ole:** Gaben einen detaillierten Überblick über den aktuellen Stand der Serverentwicklung und der Datenbankintegration, einschließlich der neuesten Performance-Optimierungen

### Nächste Schritte:
- Durchführung von Code Reviews für die eingereichten Pull Requests
- Bearbeitung und Behebung von Feedback aus den Code Reviews
- Zusammenführen (Mergen) der verschiedenen Entwicklungen in den Hauptbranch
- Detaillierte Planung der nächsten Aufgaben, basierend auf den aktuellen Projektanforderungen und den Fortschritten der letzten Woche

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

- **Marvin:** Präsentierte den aktuellen Fortschritt bei der Entwicklung der Kartenfunktionalität. Es wurden wichtige Meilensteine erreicht, die die weitere Arbeit erleichtern
- **Bent:** Berichtete über den Fortschritt bei der Listenfunktion. Er hob die Implementierung wichtiger Features hervor, die die Benutzerfreundlichkeit deutlich verbessern
- **Design-Vorlage:** Es wurde beschlossen, sich an der AirBnB-Anwendung als Vorlage zu orientieren, um bewährte Design- und Funktionsmuster zu übernehmen
- **Pull Requests:** Die aktuellen Pull Requests werden zeitnah gemergt, um die neuesten Änderungen und Verbesserungen in den Hauptbranch zu integrieren
- **Login-Funktion:** Wurde ebenfalls in das aktuelle Projekt integriert und funktioniert wie vorgesehen
- **Kommunikation:** Es wird darauf hingewiesen, dass die Kommunikation weiterhin reibungslos und effizient erfolgen muss, um den Projektfortschritt zu sichern

### Nächste Schritte:
- **Bent und Edwin:** Arbeiten an der weiteren Verbesserung der Listenfunktionalität, um eine noch bessere Benutzererfahrung zu gewährleisten
- **Marvin und Mattis:** Fokussieren sich auf die Fertigstellung und Optimierung der Kartenfunktionalität
- **Server- und Datenbankentwicklung:** Tim und Timo werden weiterhin an der Backend-Entwicklung arbeiten, um die Integration und Performance zu verbessern

### Schlussbemerkung:
Das Meeting war erfolgreich und hat wichtige Fortschritte und nächste Schritte klar definiert. Die Orientierung an der AirBnB-Anwendung als Design-Vorlage wird sicherlich dazu beitragen, dass unser Projekt benutzerfreundlicher und ansprechender wird. Wir sind zuversichtlich, dass wir mit den festgelegten Aufgaben und der effizienten Zusammenarbeit unsere Ziele erreichen werden.

---

## Weekly-Meeting: 03.06.2024 (Protokollant: Timo Haverich)

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

### Besprechung:

**Vorstellung aller Implementierungen:**
- **Bent und Edwin:** Präsentierten den Fortschritt bei der Listenfunktionalität, einschließlich neuer Sortier- und Filteroptionen
- **Marvin:** Zeigte den aktuellen Stand der Kartenimplementierung, die nun über eine verbesserte Darstellung und Interaktivität verfügt
- **Tim und Timo:** Gaben einen Überblick über die Backend-Entwicklung, einschließlich der neuesten Sicherheitsupdates und Performance-Optimierungen

### Nächste Schritte:
- **Code Reviews:** Durchführung von Code Reviews für die neuesten Pull Requests, um sicherzustellen, dass der Code den Qualitätsstandards entspricht
- **Zusammenführen (Mergen):** Die verschiedenen Entwicklungen werden in den Hauptbranch zusammengeführt, um die neuesten Verbesserungen zu integrieren
- **Fehlerbehebung:** Bearbeitung und Behebung von gemeldeten Bugs, um die Stabilität und Benutzerfreundlichkeit der Anwendung zu gewährleisten
- **Implementierung weiterer Features:** Planung und Umsetzung weiterer geplanter Features, basierend auf den aktuellen Projektanforderungen und Benutzerfeedback

### Schlussbemerkung:
Das Meeting war erfolgreich und hat wichtige Fortschritte sowie nächste Schritte klar definiert. Die neuen Sortier- und Filteroptionen in der Listenfunktionalität sowie die verbesserte Darstellung und Interaktivität der Kartenimplementierung sind wichtige Meilensteine. Die neuesten Sicherheitsupdates und Performance-Optimierungen im Backend tragen zur Stabilität und Effizienz der Anwendung bei. Wir sind zuversichtlich, dass wir durch die kontinuierliche Zusammenarbeit und den Einsatz der besten Praktiken unsere Projektziele effizient erreichen werden.

---

## Weekly-Meeting: 10.06.2024 (Protokollant: Timo Haverich)

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

### Besprechung:

**Vorstellung aller Implementierungen:**
- **Bent und Edwin:** Zeigten ihre Fortschritte bei der Listenfunktionalität, einschließlich neuer Filteroptionen und verbesserter Benutzerfreundlichkeit
- **Marvin, Mattis:** Präsentierte den aktuellen Stand der Kartenimplementierung, die nun eine verbesserte Benutzerinteraktion bietet
- **Tim und Timo:** Gaben einen Überblick über die Backend-Entwicklung, einschließlich der neuesten Performance-Optimierungen und Sicherheitsupdates

### Nächste Schritte:
- **Zusammenführen (Mergen):** Durchführung von Code Reviews und das Zusammenführen der verschiedenen Entwicklungen in den Hauptbranch
- **Fehlerbehebung:** Bearbeitung und Behebung von gemeldeten Bugs, um die Stabilität und Benutzerfreundlichkeit der Anwendung zu gewährleisten
- **Implementierung weiterer Features:** Planung und Umsetzung weiterer geplanter Features, basierend auf den aktuellen Projektanforderungen und Benutzerfeedback

### Schlussbemerkung:
Das Meeting war produktiv und hat wichtige Fortschritte sowie nächste Schritte klar definiert. Die neuen Filteroptionen und die verbesserte Benutzerfreundlichkeit in der Listenfunktionalität sowie die verbesserte Benutzerinteraktion in der Kartenimplementierung sind bedeutende Meilensteine. Die neuesten Performance-Optimierungen und Sicherheitsupdates im Backend tragen zur Stabilität und Effizienz der Anwendung bei. Wir sind zuversichtlich, dass wir durch die kontinuierliche Zusammenarbeit und den Einsatz der besten Praktiken unsere Projektziele effizient erreichen werden.

---

## Weekly-Meeting: 17.06.2024 (Protokollant: Timo Haverich)

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

### Besprechung:

**Vorstellung aller Implementierungen:**
- **Bent und Edwin:** Präsentierten ihre Arbeit an der Parkplatzliste, einschließlich neuer Features zur verbesserten Benutzerfreundlichkeit
- **Marvin, Ole:** Zeigte den aktuellen Stand der Kartenimplementierung, einschließlich neuer Interaktionsmöglichkeiten für die Benutzer
- **Tim und Timo:** Gaben einen Überblick über die Backend-Entwicklung, einschließlich der neuesten Performance-Optimierungen und Sicherheitsupdates

### Nächste Schritte:
- **Code Reviews:** Durchführung von Code Reviews für die neuesten Pull Requests, um sicherzustellen, dass der Code den Qualitätsstandards entspricht
- **Zusammenführen (Mergen):** Die verschiedenen Entwicklungen werden in den Hauptbranch zusammengeführt, um die neuesten Verbesserungen zu integrieren
- **Fehlerbehebung:** Bearbeitung und Behebung von gemeldeten Bugs, um die Stabilität und Benutzerfreundlichkeit der Anwendung zu gewährleisten
- **Implementierung weiterer Features:** Planung und Umsetzung weiterer geplanter Features, basierend auf den aktuellen Projektanforderungen und Benutzerfeedback

### Schlussbemerkung:
Das Meeting war produktiv und hat wichtige Fortschritte sowie nächste Schritte klar definiert. Die neuen Features zur verbesserten Benutzerfreundlichkeit in der Parkplatzliste sowie die neuen Interaktionsmöglichkeiten in der Kartenimplementierung sind bedeutende Meilensteine. Die neuesten Performance-Optimierungen und Sicherheitsupdates im Backend tragen zur Stabilität und Effizienz der Anwendung bei. Wir sind zuversichtlich, dass wir durch die kontinuierliche Zusammenarbeit und den Einsatz der besten Praktiken unsere Projektziele effizient erreichen werden.

---

## Weekly-Meeting: 24.06.2024 (Protokollant: Timo Haverich)

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

### Besprechung:

**Vorstellung aller Implementierungen:**
- **Bent und Edwin:** Zeigten den Fortschritt bei der Listenfunktionalität, einschließlich neuer Filter- und Sortieroptionen
- **Marvin, Ole:** Präsentierte die fortgeschrittene Kartenimplementierung, die nun eine verbesserte Darstellung und Interaktivität bietet
- **Tim und Timo:** Gaben einen Überblick über die Backend-Entwicklung, einschließlich der neuesten Performance-Optimierungen und Sicherheitsupdates

### Nächste Schritte:
- **Zusammenführen (Mergen):** Durchführung von Code Reviews und das Zusammenführen der verschiedenen Entwicklungen in den Hauptbranch
- **Fehlerbehebung:** Bearbeitung und Behebung von gemeldeten Bugs, um die Stabilität und Benutzerfreundlichkeit der Anwendung zu gewährleisten
- **Implementierung weiterer Features:** Planung und Umsetzung weiterer geplanter Features, basierend auf den aktuellen Projektanforderungen und Benutzerfeedback

### Schlussbemerkung:
Das Meeting war produktiv und hat wichtige Fortschritte sowie nächste Schritte klar definiert. Die neuen Filter- und Sortieroptionen in der Listenfunktionalität sowie die verbesserte Darstellung und Interaktivität in der Kartenimplementierung sind bedeutende Meilensteine. Die neuesten Performance-Optimierungen und Sicherheitsupdates im Backend tragen zur Stabilität und Effizienz der Anwendung bei. Wir sind zuversichtlich, dass wir durch die kontinuierliche Zusammenarbeit und den Einsatz der besten Praktiken unsere Projektziele effizient erreichen werden.

---

## Weekly-Meeting: 01.07.2024 (Protokollant: Timo Haverich)

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

### Besprechung:

**Vorstellung aller Implementierungen:**
- **Bent und Edwin:** Präsentierten ihre Arbeit an der Parkplatzliste, einschließlich neuer Funktionen und verbesserter Benutzerfreundlichkeit
- **Marvin, Mattis:** Zeigte den aktuellen Stand der Kartenimplementierung, einschließlich neuer Interaktionsmöglichkeiten und Verbesserungen der Darstellung
- **Tim, Ole und Timo:** Gaben einen Überblick über die Backend-Entwicklung, einschließlich der neuesten Performance-Optimierungen und Sicherheitsupdates

### Nächste Schritte:
- **Code Reviews:** Durchführung von Code Reviews für die neuesten Pull Requests, um sicherzustellen, dass der Code den Qualitätsstandards entspricht
- **Zusammenführen (Mergen):** Die verschiedenen Entwicklungen werden in den Hauptbranch zusammengeführt, um die neuesten Verbesserungen zu integrieren
- **Fehlerbehebung:** Bearbeitung und Behebung von gemeldeten Bugs, um die Stabilität und Benutzerfreundlichkeit der Anwendung zu gewährleisten
- **Implementierung weiterer Features:** Planung und Umsetzung weiterer geplanter Features, basierend auf den aktuellen Projektanforderungen und Benutzerfeedback

### Schlussbemerkung:
Das Meeting war produktiv und hat wichtige Fortschritte sowie nächste Schritte klar definiert. Die neuen Funktionen und die verbesserte Benutzerfreundlichkeit in der Parkplatzliste sowie die neuen Interaktionsmöglichkeiten und Verbesserungen der Darstellung in der Kartenimplementierung sind bedeutende Meilensteine. Die neuesten Performance-Optimierungen und Sicherheitsupdates im Backend tragen zur Stabilität und Effizienz der Anwendung bei. Wir sind zuversichtlich, dass wir durch die kontinuierliche Zusammenarbeit und den Einsatz der besten Praktiken unsere Projektziele effizient erreichen werden.

---


## Fazit der Meetings

Die Meetings über den Zeitraum von Mai bis Juli 2024 verliefen durchweg produktiv und strukturiert, was zu signifikanten Fortschritten im Projekt führte. Die regelmäßigen Treffen ermöglichten es, die Arbeit effizient zu koordinieren, Probleme zeitnah zu klären und nächste Schritte klar zu definieren.

### Fortschritte und Implementierungen

In den Meetings wurden regelmäßig die neuesten Implementierungen und Entwicklungen präsentiert. Wichtige Fortschritte wurden in den Bereichen der Listen- und Kartenfunktionalität erzielt, einschließlich neuer Sortier- und Filteroptionen sowie verbesserter Interaktionsmöglichkeiten und Darstellung. Die Backend-Entwicklung wurde kontinuierlich optimiert, um die Performance zu steigern und die Sicherheit zu verbessern.

### Code Reviews und Zusammenführung

Ein zentraler Aspekt der Meetings war die Durchführung von Code Reviews, um sicherzustellen, dass der Code den Qualitätsstandards entspricht. Die verschiedenen Entwicklungen wurden regelmäßig in den Hauptbranch zusammengeführt, um die neuesten Verbesserungen zu integrieren und die Anwendung stabil und benutzerfreundlich zu halten.

### Fehlerbehebung und weitere Features

Die Fehlerbehebung war ein weiterer wichtiger Punkt in den Meetings. Gemeldete Bugs wurden zeitnah bearbeitet und behoben, um die Stabilität der Anwendung zu gewährleisten. Darüber hinaus wurden die Implementierung weiterer geplanter Features und die Berücksichtigung von Benutzerfeedback regelmäßig diskutiert und in die Planung aufgenommen.

### Schlussbemerkung

Die regelmäßigen Meetings haben entscheidend dazu beigetragen, den Projektfortschritt zu sichern und die Zusammenarbeit im Team zu stärken. Durch die kontinuierliche Kommunikation und das Engagement aller Beteiligten konnten wichtige Meilensteine erreicht und die Anwendung stetig verbessert werden. Die effektive Nutzung bewährter Praktiken und die klaren Zielsetzungen lassen darauf schließen, dass die Projektziele effizient und erfolgreich erreicht werden.