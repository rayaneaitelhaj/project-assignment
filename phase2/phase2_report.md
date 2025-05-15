# Phase 2 Report – Basic Structure and Main Functionalities

## Project Name: WorkHub Dashboard
## Author: Rayane

---

## 🔹 Environment
The project is currently developed locally using VS Code.  
Deployment will be done to a cloud platform (e.g. Vercel or Render) in the next phase.

---

## 🔹 Backend
- **Framework**: Node.js with Express
- **Routing**:
  - `/login` – handles login form
  - `/dashboard` – displays main dashboard content
- Server serves both static files and HTML content.
- Error handling with middleware (e.g. 404 page and fallback)

---

## 🔹 Frontend
- HTML + CSS + JavaScript
- Structured UI with:
  - Navigation bar
  - Schedule section
  - Chat section
  - News section
- React or other frontend framework can be used later for interactivity

---

## 🔹 Database
- Currently no database in use
- Plan to integrate **PostgreSQL** in the next phase for storing users, messages, and schedules

---

## 🔹 Functionalities Implemented
- Login screen (UI only)
- Dashboard layout with:
  - Weekly schedule preview
  - Chat input (no backend yet)
  - News section
- Navigation between sections (Home, Schedule, Messages, Clock In)

---

## 🧱 Project Structure


---

## 🧪 Testing and Error Handling
- Basic error handling implemented:
  - Unknown routes return a 404 page
  - Server errors logged in console
- Testing plan:
  - Manual testing with test users
  - Unit tests with Jest (planned in Phase 3)

---

## 💻 UI and Interaction
- UI is based on a clean dashboard design
- Navigation is simple and intuitive
- Visuals include:
  - Schedule layout
  - Chat box with input + send
  - News section for updates

See prototype drawing in [UI.md](../phase1/UI.md)

---

## 📌 Notes
- All functions are clearly separated into folders/modules
- Code is well-commented and easy to follow
- PostgreSQL integration and deployment to cloud are planned next

---


