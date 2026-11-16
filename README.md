# Termino

Online appointment booking for solo beauty and wellness professionals
(nails, brows, massage, barber, physiotherapy).

> **Status:** in development

## What it does

Each professional gets their own booking page. Clients choose a service
and a free time slot and receive a confirmation email. The professional
manages services, working hours and appointments in an admin area.

## Planned features (MVP)

- [ ] Registration and login for professionals (JWT, bcrypt)
- [ ] Services with duration and price
- [ ] Working hours, breaks and time off
- [ ] Calculation of free time slots
- [ ] Double-booking protection (database transactions)
- [ ] Public booking page per business (`/business-name`)
- [ ] Confirmation and reminder emails
- [ ] Cancel / reschedule via link from the email
- [ ] German interface, GDPR-friendly (Impressum, Datenschutz)

## Tech stack

- **Frontend:** React, TypeScript, Vite
- **Backend:** Node.js, Express, TypeScript
- **Database:** MySQL
- **Testing:** Vitest, Supertest
- **DevOps:** Docker Compose, GitHub Actions

## Getting started

Setup instructions will be added as the project grows.

## Author

Bohdan Vyhovskyi, [GitHub](https://github.com/Sheluvboog)
