### Hi, I'm Juan Ignacio 👋

Backend developer focused on **applied AI**: I build the APIs, queues and services that turn messy real-world inputs
(engineering drawings, audio, financial filings) into structured data people can act on.
Software Engineering student at **Universidad Austral** (Buenos Aires, Argentina).

**Stack:** TypeScript · NestJS · Prisma · Kotlin · Spring Boot · Python · FastAPI · PostgreSQL · Docker · GitHub Actions
**AI:** YOLO (object detection) · LLM vision & extraction (Claude) · Whisper · Ollama

---

#### 🔧 Featured work

**LIARD — electrical drawings → bill of materials** · *private repo (client project), 7-person team*
Turns AutoCAD electrical panel drawings (DXF/PDF) into a bill of materials, supplier quotes and purchase orders,
replacing hours of manual counting per panel.
I worked on the detection pipeline: a two-stage **YOLO + Claude vision** service (FastAPI), tiled inference over
large drawings (SAHI + NMS), a grid spatial index that replaced all-vs-all symbol grouping, and the redesign of the
**Postgres-backed job queue** between the NestJS backend and the detector.
`NestJS` `Prisma` `FastAPI` `YOLO` `Claude` `React` `PostgreSQL` `Docker`

**[Bovelez](https://github.com/Bovelez/bovelez) — stock portfolio tracker** · *team of 5*
Users buy/sell stocks validated against SEC EDGAR and track their portfolio with live prices.
I set up the **CI pipeline** (unit + integration tests on GitHub Actions), built the backend auth integration and the
**SEC EDGAR + Yahoo Finance** data providers, and the mobile front-end.
`NestJS` `Prisma` `FastAPI` `React` `Cypress` `GitHub Actions`

**[Snippet Searcher](https://github.com/JVM-austral) — code snippet platform on microservices** · *team of 3*
- [auth-microservice](https://github.com/JVM-austral/auth-microservice): **Auth0 JWT validation** and per-snippet
  **READ/WRITE permissions**
  for the whole platform (main author).
- [PrintScript interpreter](https://github.com/JVM-austral/tp-ingsis-interpreter): lexer, parser, interpreter,
  formatter and linter for a small language, shipped as a CLI.
- [snippet-manager](https://github.com/JVM-austral/snippet-manager) · [snippet-engine](https://github.com/JVM-austral/snippet-engine)
  · infrastructure with Docker Compose + Nginx (main author).
`Kotlin` `Spring Boot` `JPA` `PostgreSQL` `JWT/Auth0` `Docker`

**RivalMatch — find rival teams and schedule matches** · *private repo, team of 4*
Backend auth (Argon2 per OWASP), team management, rival search and match acceptance flow, **WebSockets** and E2E tests
for every endpoint.
`NestJS` `TypeScript` `WebSockets` `React`

#### 🧪 Side projects

- **[siu-notas](https://github.com/juanitorres1/siu-notas)** — monitors my university's student portal (SIU Guaraní)
  and emails me only when there's something new: grades, final exams, credit-earning activities. `Python`
- **[Transcriptor-Audios](https://github.com/Tomas093/Transcriptor-Audios)** — transcribes and summarizes WhatsApp
  voice notes 100% offline with Whisper + a local LLM (contributor). `Go` `Whisper` `Ollama`

---

📫 [LinkedIn](https://www.linkedin.com/in/juan-ignacio-torres-91ba1731b) · [juanignaciot640@gmail.com](mailto:juanignaciot640@gmail.com)

<details>
<summary>🇦🇷 Versión en español</summary>

### Hola, soy Juan Ignacio 👋

Desarrollador backend enfocado en **IA aplicada**: construyo las APIs, colas y servicios que convierten datos del
mundo real (planos de ingeniería, audios, reportes financieros) en información estructurada.
Estudiante de Ingeniería en Informática en la **Universidad Austral** (Buenos Aires).

#### Proyectos destacados

- **LIARD** (privado, proyecto con cliente): convierte planos eléctricos de AutoCAD en listado de materiales,
  cotizaciones y órdenes de compra. Trabajé en el pipeline de detección **YOLO + Claude visión**, la inferencia por
  tiles sobre planos grandes y el rediseño de la **cola de trabajos sobre Postgres**.
- **[Bovelez](https://github.com/Bovelez/bovelez)**: tracker de portafolios de acciones. Armé el **CI** con tests
  unitarios y de integración, la integración de auth y los proveedores de datos **SEC EDGAR + Yahoo Finance**.
- **[Snippet Searcher](https://github.com/JVM-austral)**: plataforma de microservicios en Kotlin/Spring Boot. Autor
  principal del servicio de **auth (JWT de Auth0 + permisos por snippet)** y de la infraestructura; intérprete de PrintScript.
- **RivalMatch** (privado): búsqueda de rivales y partidos entre equipos. Auth, flujo de matches, WebSockets y tests E2E.
- **[siu-notas](https://github.com/juanitorres1/siu-notas)** y
  **[Transcriptor-Audios](https://github.com/Tomas093/Transcriptor-Audios)** como proyectos personales.

📫 [LinkedIn](https://www.linkedin.com/in/juan-ignacio-torres-91ba1731b) · [juanignaciot640@gmail.com](mailto:juanignaciot640@gmail.com)

</details>
