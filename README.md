# UnfilteredApp Code Contributions

This repository provides a structured breakdown of code contributions for the **UnfilteredApp** project.

The original application (frontend + backend) was developed collaboratively as a single integrated system. However, since development and final commits were performed through shared environments and centralized pushes, the raw Git commit history does not fully reflect individual contributions.

To address this, this repository organizes the final codebase by responsibility, allowing clear review of each team member’s work.

---

## Repository Structure

```text
Frontend/
   ├── Ashish_UI_UX/
   ├── Kaushik_API_Data_Integration/
   └── Vidney_Architecture_Stateflow/

Backend/
   ├── Ashish_Backend_Integration/
   ├── Kaushik_Backend_Core_API/
   └── Vidney_Realtime_Chat_Stateflow/

```
---
## Frontend Overview

The frontend is an Android application built using Jetpack Compose with a structured architecture separating UI, data, and state management.

- UI/UX screens and design components  
- API integration and data handling  
- Navigation, ViewModels, and state management  

Detailed contributions are documented inside the Frontend/ folder.

---

## Backend Overview

The backend is built using Node.js, Express.js, and PostgreSQL (NeonDB) with support for real-time communication using Socket.io.

- Authentication and secure API endpoints  
- Mood logging, journaling, and analytics features  
- Real-time chat rooms and messaging  
- Database schema using Knex migrations and seeds  

Detailed contributions are documented inside the Backend/ folder.

---

## Contribution Summary

### Ashish
- UI/UX development using Jetpack Compose  
- Frontend–backend integration across features  
- Mood, journal, analytics, music, and user flow implementation  

### Kaushik
- Backend core architecture and API development  
- Authentication system and database schema  
- API integration layer in frontend  

### Vidney
- Application architecture and state management  
- Navigation and ViewModel structure  
- Real-time chat implementation using Socket.io  

---

## Note on Contribution Review

Each team member worked on this project with clear responsibilities, and everyone completed their assigned part. The project was developed collaboratively, with frontend, backend, API integration, and real-time features all depending on each other.

Earlier in the project, we were not fully aware that Git commits needed to be separated by individual team members, so some commits were made from shared or centralized accounts. After asking for clarification on Piazza, we understood that individual contribution visibility was important.

We initially considered using separate branches in the main working repository, but modifying the working app structure caused instability and risked breaking the final running version. To avoid affecting the submitted working application, we created this separate contribution-review repository.

This repository does not replace the main project repository. It is only meant to clearly organize and show each team member’s code contributions by responsibility.
