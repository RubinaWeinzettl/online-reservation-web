# Online Reservierung – Web Frontend

**Work in Progress**

Dieses Repository enthält das **Web-Frontend** für das Portfolio-Projekt **Online Reservierung**.  
Es stellt die Benutzeroberfläche für die Interaktion mit den dahinterliegenden Services bereit und fungiert als klare Trennung zwischen Darstellung (UI) und Businesslogik (Backend-APIs).

---

## Kurzüberblick (Scannerfreundlich)

- Web-Frontend für ein serviceorientiertes Reservierungssystem  
- Klare Trennung von Frontend und Backend  
- Kommunikation ausschließlich über definierte APIs  
- Schrittweiser Ausbau der Frontend-Technologie  
- Portfolio-Projekt mit Fokus auf saubere Architektur und Erweiterbarkeit  

---

## Projektkontext

Das Projekt **Online Reservierung** ist Teil meines Developer-Portfolios und markiert meine bewusste Weiterentwicklung von klassischem Web Application Development hin zu:

- serviceorientierter Architektur  
- klar definierten Schnittstellen (APIs)  
- entkoppelten Komponenten  
- moderner Entwicklungs- und Deployment-Praxis  

Dieses Repository bildet die **Frontend-Schicht** und ist unabhängig von konkreten Backend-Implementierungen lauffähig, solange die API-Verträge eingehalten werden.

---

## Rolle des Web-Frontends in der Architektur

Das Web-Frontend ist verantwortlich für:

- Darstellung der Benutzeroberfläche  
- Benutzerinteraktion (Formulare, Validierung, Feedback)  
- Kommunikation mit den Backend-Services über HTTP-APIs  
- Keine direkte Businesslogik oder Datenpersistenz  

Die fachliche Logik liegt vollständig in den jeweiligen Backend-Services.

---

## Frontend-Strategie & Technologie

Die Entwicklung des Frontends erfolgt **bewusst in mehreren Releases**:

### Release 1 – Rudimentäres Frontend

- Umsetzung mit **klassischem HTML**  
- Fokus auf:
  - grundlegende Benutzerflüsse
  - saubere API-Anbindung
  - funktionale End-to-End-Tests der Services
- Keine komplexe Client-Logik  
- Ziel: Architektur validieren, nicht UI perfektionieren  

### Spätere Releases – Modernes Frontend

- Umstieg auf **React**  
- Ausbau zu einer komponentenbasierten Architektur  
- Verbesserte User Experience und Wartbarkeit  
- Klare Trennung zwischen Präsentations- und Anwendungslogik  

Dieser Ansatz ermöglicht eine **schrittweise technische Weiterentwicklung**, ohne die Backend-Architektur zu verändern.

---

## Kommunikation mit den Services

Das Frontend kommuniziert ausschließlich über klar definierte Endpoints, z. B.:

- Auth-Service (Login, Registrierung, Benutzerkontext)
- Reservierungs-Service (Anlegen, Anzeigen, Verwalten von Reservierungen)

Die genaue API-Spezifikation befindet sich in den jeweiligen Service-Repositories.

---

## Architekturprinzipien

- **Separation of Concerns**  
- **API-First-Ansatz**  
- **Lose Kopplung**  
- **Austauschbarkeit von Services**  
- **Keine direkte Abhängigkeit von Datenbanken oder interner Service-Logik**

---

## Entwicklungsstand

**Stand: 07.01.2026**

Dieses Projekt befindet sich aktiv in Entwicklung.  
Struktur, Features und technische Details können sich während des Entwicklungsprozesses ändern.

---

## Ziel dieses Repositories

- Demonstration moderner Frontend-Integration in eine Microservice-Architektur  
- Saubere Trennung zwischen UI und Backend  
- Schrittweise Weiterentwicklung der eingesetzten Technologien  
- Verständliche, wartbare Projektstruktur  
- Portfolio-Referenz für serviceorientierte Webanwendungen  

---

## Hinweis

Dieses Repository ist Teil eines **Lern- und Portfolio-Projekts**.  
Der Fokus liegt auf Architektur, Verständlichkeit und nachhaltiger Entwicklung – nicht auf Feature-Vollständigkeit.
