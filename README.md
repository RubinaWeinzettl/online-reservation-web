# Web Frontend

This repository contains the **frontend** for the **Online Reservation** project.

It currently serves as a **lightweight test interface** for validating backend API flows and will later evolve into a full-featured frontend application.

---

## Purpose

The Web Frontend is used to:

- test and validate backend APIs (Auth Service, future API)
- simulate basic user interactions
- provide a simple UI for development and debugging
- serve as a foundation for future frontend development

---

## Current State

- implemented as **static HTML, CSS, and JavaScript**
- no framework dependency
- communicates directly with backend services via HTTP (REST)

---

## Tech Stack

- HTML5
- CSS3
- JavaScript (vanilla)
- Nginx (for serving static files)
- Docker

---

## Architecture (current)

- static frontend served via **Nginx**
- communicates with backend services:
  - Auth Service (Java / Jakarta EE)
  - future API (TBA)
- no build step required

---

## Features (current)

- simple login form
- manual API interaction
- basic request/response visualization
- minimal UI for testing authentication flow

---

## Planned Evolution

The frontend will be extended and gradually replaced by a modern framework:

### Future Frontend

- migration to **Angular (TypeScript)**
- role-based UI (business vs. customer)
- improved UX and navigation
- structured state management
- integration with full backend API

---

## Project Structure

```text
web/
│
├── index.html
├── css/
├── js/
├── nginx/
│   └── default.conf
└── Dockerfile
```
## Getting Started

### Prerequisites

- Docker

---

### Run locally

docker build -t web-frontend .
docker run -p 8080:80 web-frontend

Then open:
http://localhost:8080

---

## Configuration

- API endpoints are currently configured directly in JavaScript
- may be externalized later (e.g. environment variables or config files)

---

## Development Notes

- intentionally kept simple for fast iteration
- no framework overhead
- used primarily as a development and debugging tool
- will coexist with Angular frontend during transition phase

---

## Related Repositories

- Overview:  
  https://github.com/RubinaWeinzettl/online-reservation-overview

- Auth Service (Java):  
  https://github.com/RubinaWeinzettl/online-reservation-auth-java

---

## Status

🚧 Work in progress – currently a minimal test frontend, planned to evolve into Angular-based UI
