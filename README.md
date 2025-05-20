# 🏃‍♂️ Zentra

**Zentra** ist eine leichtgewichtige Projekt- und Aufgabenverwaltungs-App – inspiriert von Jira, fokussiert auf Entwicklerteams.  
Das MVP bietet grundlegende Projekt- & Issue-Verwaltung mit Benutzerrollen, JWT-Authentifizierung und einem modernen Angular-Frontend.

---

## 🔧 Features

- 🔐 Benutzer-Registrierung & Login (JWT-Auth)
- 🧑‍🤝‍🧑 Projekte mit Mitgliedern
- 🪪 Rollen: Admin / User
- 📝 Aufgaben (Issues) pro Projekt mit:
  - Titel, Beschreibung
  - Status (To Do, In Progress, Done)
  - Priorität (Low, Medium, High)
  - Zuweisung an Projekt-Mitglied
- 🧭 Angular-Frontend mit Auth-Guard und dynamischem Routing

---

## 🧱 Tech Stack

### Backend
- Java 21
- Spring Boot 3
- Spring Security (JWT)
- Spring Data JPA
- PostgreSQL / H2
- MapStruct (optional)

### Frontend
- Angular 18
- Angular Material / PrimeNG
- RxJS
- AuthGuard & Interceptor für Token Handling

---

