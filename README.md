#  Smart Fleet Management System

A full-stack, microservices-based platform for managing vehicle fleets, drivers, and routes
---

## Overview

This system enables logistics companies or fleet managers to:

- Manage vehicles and their status
- Assign drivers and view their availability
- Plan and track routes
- Monitor fleet performance in real-time

Built using **Java (Spring Boot)**, **Angular/React**, **PostgreSQL**, **MongoDB**, and **Docker** with optional advanced features like **WebSockets**, **Reactive Streams**, and **Prometheus** monitoring.


---

## Tech Stack

| Layer        | Technology |
|--------------|------------|
| Frontend     | React, Tailwind CSS / Material UI |
| Backend      | Java 17, Spring Boot (REST APIs) |
| Auth         | Spring Security, JWT |
| Databases    | PostgreSQL, MongoDB |
| DevOps       | Docker, GitHub Actions, Docker Compose |
| Monitoring   | Prometheus + Grafana |
| Testing      | JUnit, Mockito |
| CI/CD        | GitHub Actions |

---

## Roadmap

- [x] Project structure and repository setup
- [ ] JWT-based authentication service
- [ ] Vehicle management microservice
- [ ] Driver management microservice
- [ ] Frontend dashboard (login, vehicle, driver UI)
- [ ] CI/CD pipeline setup
- [ ] MongoDB + route service for tracking
- [ ] Real-time GPS updates with WebSockets 
- [ ] Prometheus + Grafana integration

---

## Authentication

- JWT-based login system
- Role-based access (admin, operator)
- Secure endpoints via Spring Security

---

## Testing Strategy

- Unit testing with **JUnit**
- Integration testing with **Spring Test**
- Frontend testing with **Jest/Cypress** *(TBD)*

---

## CI/CD

GitHub Actions pipeline to automate:

- Linting
- Unit tests
- Docker build
- Deployment steps *(to be configured)*

---

## Deployment

To be deployed via:

- Docker Compose (for local dev)
- Azure / AWS (cloud deployment)
- Infrastructure as Code

---

## Contributions

This project is open for learning collaboration! Feel free to fork, suggest improvements, or submit PRs.

---

## License

This project is licensed under the MIT License.



