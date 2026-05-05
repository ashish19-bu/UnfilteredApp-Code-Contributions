# Backend Contribution Breakdown

This folder presents the backend code organized by primary ownership for each team member. 

The backend was developed collaboratively as a single system, but responsibilities were divided across features. This structure highlights who primarily worked on which parts of the backend while acknowledging integration across modules.

---

## Ashish — Feature Integration & Frontend–Backend Connection

Ashish focused on implementing feature-level backend flows and ensuring smooth integration between the Android frontend and backend APIs.

Primary contributions:
- Mood logging feature flow
- Journal and journal-entry backend features
- End-to-end integration between frontend screens and backend APIs
- Testing and validating user flows across mood, journal, and analytics features

Files included:
- `moodController.js`
- `moodManager.js`
- `moodRoutes.js`
- `journalController.js`
- `journalManager.js`
- `journalRoutes.js`
- `journalEntryController.js`
- `journalEntryManager.js`
- `journalEntryRoutes.js`

---

## Kaushik — Core Backend API, Authentication & Database

Kaushik worked on the foundational backend architecture, authentication system, and database layer.

Primary contributions:
- Express.js backend setup and API structure
- JWT-based authentication and middleware protection
- PostgreSQL schema design using Knex migrations
- Database configuration and connection setup
- API structure for user authentication and secure endpoints

Files included:
- `authController.js`
- `authManager.js`
- `auth.js`
- `db.js`
- `knexfile.js`
- `package.json`
- `package-lock.json`
- `db/` (migrations and seeds)

---

## Vidney — Real-time Chat, Socket.io & Server Architecture

Vidney worked on real-time communication and overall backend wiring.

Primary contributions:
- Socket.io real-time chat implementation
- Chat room and messaging backend flow
- Server setup and application routing structure
- Integration of real-time events with REST APIs

Files included:
- `socket.js`
- `chatController.js`
- `chatManager.js`
- `chatRoutes.js`
- `app.js`
- `index.js`

---

## Note

The backend was built as a fully integrated system. While files are grouped by primary ownership, multiple components interact across modules, and contributions involved collaborative integration and debugging across the entire backend.
