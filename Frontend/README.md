# Frontend Contribution Breakdown

This folder presents the Android frontend code organized by primary ownership for each team member.

The frontend was developed collaboratively as a unified Jetpack Compose application. While all components are interconnected, this structure highlights the primary areas each member worked on for clarity in evaluation.

---

## Ashish — UI/UX Development & Frontend Integration

Ashish focused on designing and implementing the user interface using Jetpack Compose, along with integrating frontend screens with backend APIs.

Primary contributions:
- Built all major Jetpack Compose screens
- Designed UI layouts, navigation flow, and user experience
- Implemented Material 3 theming, spacing, and visual consistency
- Developed mood selection UI (quadrant-based interaction)
- Built screens for journal, analytics, music, rooms, chat, and detox features
- Integrated frontend screens with backend APIs (auth, mood, journal, chat, places, music)
- Ensured smooth end-to-end user flow and UI responsiveness

Files included:
- `ui/screens/`
- `ui/theme/`

---

## Kaushik — API Integration, Data Layer & Model Handling

Kaushik worked on connecting the frontend with backend services through structured API and data layers.

Primary contributions:
- Defined API interfaces for backend communication
- Built data models for request/response handling
- Implemented repository layer for managing data flow
- Integrated authentication, mood, journal, chat, and places APIs into frontend
- Ensured proper data transformation and error handling

Files included:
- `data/api/`
- `data/model/`
- `data/repository/`

---

## Vidney — Architecture, Navigation & State Management

Vidney worked on overall app architecture, navigation flow, and state management across screens.

Primary contributions:
- Implemented navigation using NavHost and structured routing
- Built ViewModels using StateFlow for managing UI state
- Managed lifecycle-aware state handling across screens
- Integrated real-time chat state with backend using Socket.io
- Structured app flow and connected UI with data layer

Files included:
- `MainActivity.kt`
- `viewmodel/`

---

## Note

The frontend was developed as a fully integrated application. While responsibilities are divided for clarity, all components are interconnected, and development involved collaboration across UI, data, and architecture layers.
