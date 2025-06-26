# Rehearsal Scheduler

Automatically schedules band rehearsals, sends reminders, tracks attendance, and suggests optimal rehearsal times.

## Features
- Schedule management (view, create, edit)
- Attendance tracking
- Reminders and notifications (email/SMS)
- RSVP/availability
- Resource sharing
- Mobile responsive
- Role-based access

## Tech Stack
- Front-end: React.js
- Back-end: Node.js (Express)
- Database: PostgreSQL

## Setup
1. Clone the repository.
2. Install dependencies in `/server` and `/client`.
3. Create a `.env` file with DB and API credentials.
4. Run database migrations (see `/migrations`).
5. Start back-end (`npm run start` in `/server`), then front-end (`npm run start` in `/client`).

See [Google Docs Project Plan](https://docs.google.com/document/d/1LyrZ1aDPePbzEppcgSiNRAvihDAMDSRWoRgmC2Q9Oqo/edit) for detailed architecture, schema, and design.