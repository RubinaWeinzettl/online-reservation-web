⚠️ Project Status: Archived

This repository is no longer under active development.
It remains public as a portfolio reference for architecture,
service design, and DevOps-related decisions.


# Online Reservation – Web Frontend

**Work in Progress**

This repository contains the **web frontend** for the portfolio project **Online Reservation**.  
It provides the user interface for interacting with the underlying services and serves as a clear separation between presentation (UI) and business logic (backend APIs).

---

## Quick Overview (Scanner-Friendly)

- Web frontend for a service-oriented reservation system  
- Clear separation between frontend and backend  
- Communication exclusively via defined APIs  
- Incremental evolution of frontend technology  
- Portfolio project with a focus on clean architecture and extensibility  

---

## Project Context

The **Online Reservation** project is part of my developer portfolio and represents my deliberate transition from classic web application development towards:

- service-oriented architecture  
- clearly defined interfaces (APIs)  
- decoupled components  
- modern development and deployment practices  

This repository represents the **frontend layer** and can run independently of specific backend implementations, as long as the defined API contracts are respected.

---

## Role of the Web Frontend in the Architecture

The web frontend is responsible for:

- rendering the user interface  
- handling user interaction (forms, validation, feedback)  
- communicating with backend services via HTTP APIs  
- no direct business logic or data persistence  

All domain logic resides entirely within the respective backend services.

---

## Frontend Strategy & Technology

The frontend is developed **intentionally across multiple releases**:

### Release 1 – Rudimentary Frontend

- Implemented using **plain HTML**  
- Focus on:
  - basic user flows
  - clean API integration
  - functional end-to-end testing of the services  
- No complex client-side logic  
- Goal: validate the architecture, not perfect the UI  

### Later Releases – Modern Frontend

- Migration to **React**  
- Expansion towards a component-based architecture  
- Improved user experience and maintainability  
- Clear separation between presentation and application logic  

This approach enables **incremental technical evolution** without changing the backend architecture.

---

## Communication with Services

The frontend communicates exclusively via clearly defined endpoints, for example:

- Auth Service (login, registration, user context)  
- Reservation Service (creating, viewing, and managing reservations)

The exact API specifications can be found in the respective service repositories.

---

## Architectural Principles

- **Separation of Concerns**  
- **API-first approach**  
- **Loose coupling**  
- **Service replaceability**  
- **No direct dependency on databases or internal service logic**

---

## Development Status

**Status: 07 January 2026**

This project is actively under development.  
Structure, features, and technical details may change during the development process.

---

## Purpose of This Repository

- Demonstrate modern frontend integration in a microservice architecture  
- Clear separation between UI and backend  
- Incremental evolution of the chosen technologies  
- Understandable and maintainable project structure  
- Portfolio reference for service-oriented web applications  

---

## Note

This repository is part of a **learning and portfolio project**.  
The focus is on architecture, clarity, and sustainable development — not on feature completeness.
