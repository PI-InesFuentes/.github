<p align="center">
  <img src="./nudo-banner.svg" alt="Nudo: workshop bookings tied to their materials" width="100%">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-in_design-A21313?style=flat-square" alt="Status: in design">
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/Laravel_13-FF2D20?style=flat-square&logo=laravel&logoColor=white" alt="Laravel 13">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Cloud_Run-4285F4?style=flat-square&logo=googlecloud&logoColor=white" alt="Google Cloud Run">
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" alt="Supabase">
</p>

### 🧵 What is Nudo?

**Nudo** is my Intermodular Project for the Web Application Development program (DAW): a web app for **small craft workshops**, such as ceramics studios, painting academies, candle makers or knitting shops.

In these businesses, seats and materials are tracked separately and by hand, through Instagram DMs, WhatsApp, notebooks and spreadsheets. That leads to double bookings, wasted or missing material, and cancellations that never free anything up. Nudo connects both:

- **Booking a seat reserves its material**, and cancelling returns it to stock.
- **No seat or no material means no booking**, even when two people try to take the last one at the same time.
- **Students pick their materials when they book** (glaze colour, candle scent...) and see any extra cost before confirming.
- **Instructors know in advance** who is coming and what each person chose.
- **Owners get one shared stock** across all workshops, with low-stock alerts and a full history.

It is planned as a **B2B SaaS**: each studio signs up as its own business, with its data kept separate from the others.

### 🛠️ How it will be built

| Layer | Choice | Why |
|---|---|---|
| Frontend | React · Vite · React Router | The booking screen updates live as materials are picked |
| Backend | Laravel 13 · Sanctum | Auth, roles, validation and DB transactions with row locking, built in |
| Database | PostgreSQL | Strongly related data that needs integrity and transactions |
| API | REST · JSON over HTTPS | Clear separation between client and server |
| Deploy | Google Cloud Run + Supabase (EU) | Free tiers that cover the demo with three sample studios |
| Testing env | Ubuntu Server + Tailscale | Private HTTPS access from my own devices |

### 🗺️ Roadmap

| Phase | Status |
|---|---|
| 1 · [Need analysis & proposal](https://github.com/PI-InesFuentes/2do-Fase1-Necesidad-y-propuesta-proyecto) | ✅ Done |
| 2 · [Design & feasibility](https://github.com/PI-InesFuentes/2do-Fase2-Diseno-y-viabilidad-proyecto) | ✅ Done |
| 3 · Data model, API routes and UI design | ⏳ Next |
| 4 · Backend & persistence | ⬜ |
| 5 · Frontend | ⬜ |
| 6 · Integration & testing | ⬜ |
| 7 · Deployment, docs & defence | ⬜ |

<details>
<summary><b>📚 First year (2025/2026): where it started</b></summary>
<br>

In first year I built a generic **resource booking system** across several course modules, all collected in **[1ro-Proyecto-Centralizado](https://github.com/PI-InesFuentes/1ro-Proyecto-Centralizado)**.

| Layer | Deliverable | Stack |
|---|---|---|
| 🗄️ Data | [E/R model](https://github.com/PI-InesFuentes/1ro-Entrega1-BRD-Modelo-E-R) → [Relational model](https://github.com/PI-InesFuentes/1ro-Entrega3-BD-Diseno-logico-El-modelo-relacional) → [Physical SQL](https://github.com/PI-InesFuentes/1ro-Entrega5-BD-Diseno-fisico-El-modelo-fisico-en-SQL) | MariaDB / MySQL |
| 🔌 API | [REST API design](https://github.com/PI-InesFuentes/1ro-Entrega7-Diseno-de-API-REST-para-tu-sistema-de-reservas) | OpenAPI 3.0 · Swagger UI |
| ☕ Backend | [Booking CRUD](https://github.com/PI-InesFuentes/1ro-Entrega9-PROGRAMACION-CRUD-Reservas) | Java 21 · JDBC · MVC + DAO |
| 🎨 Frontend | [Consultancy website](https://github.com/PI-InesFuentes/1ro-Entrega6-LMSGI-Web-Consultora-HTML-CSS) | HTML5 · CSS3 |
| 🛠️ Ops | [XAMPP setup](https://github.com/PI-InesFuentes/1ro-Entrega2-SI-Instalacion-Entorno-de-trabajo-con-XAMPP) · [NAS backups](https://github.com/PI-InesFuentes/1ro-Entrega8-COPIA-DE-SEGURIDAD-COLABORATIVA-EN-NAS) · [Git & GitHub](https://github.com/PI-InesFuentes/1ro-Entrega4-EDE-Repositorio-de-GitHub) | XAMPP · NAS · Git |

</details>

### 👩‍💻 Author

**Inés Fuentes Martínez**, UX/UI Designer & Front-End Developer
[GitHub](https://github.com/lylyam) · [LinkedIn](https://www.linkedin.com/in/ines-fuentes-martinez/)
