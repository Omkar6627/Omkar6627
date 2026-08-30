<h1 align="center">Omkar Pawar</h1>
<h3 align="center">Full-Stack Software Developer · .NET · Angular · Flutter</h3>

<p align="center">
  Two years building enterprise systems that have to survive real load. I took a query on a
  15-million-row table from <b>30 seconds to 4</b>, led a vector-search integration end to
  end, and built an event pipeline that holds <b>1,000 events a second</b> with a live UI on
  the other side of it.
</p>

<p align="center">
  I care about the unglamorous half: the index that makes the query fast, the audit log that
  makes the workflow trustworthy, the error message that tells you which of two problems you
  actually have. I like the problems that look simple until you read the spec.
</p>

<p align="center">
  <a href="https://linkedin.com/in/omkar66527"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:omkar66527@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://www.leetcode.com/omkar66527"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=flat&logo=leetcode&logoColor=black" alt="LeetCode"/></a>
  <a href="https://www.hackerrank.com/omkar66527"><img src="https://img.shields.io/badge/HackerRank-00EA64?style=flat&logo=hackerrank&logoColor=black" alt="HackerRank"/></a>
</p>

---

## Where I work

**Software Developer — [I2V Systems](https://www.i2vsys.com/)** · Dec 2023 – Present

Full-stack across ASP.NET Core, Angular and Flutter on the company's flagship product.
The work I'd point at:

- **Made a 30-second query take 4 seconds.** A 15M-record PostgreSQL dataset, roughly 7×
  faster, by designing and tuning the indexes rather than throwing hardware at it.
- **Led the Milvus vector database integration** end to end, bringing similarity search
  over large-scale data into the product.
- **Built the real-time pipeline** — RabbitMQ sustaining 1,000 events/second under heavy
  load, streamed to a live UI over SignalR.
- **RTSP/VLC live video** handling for in-app streams and live event processing, across
  both the backend and the Flutter mobile client.
- **Observability with Grafana + Prometheus**, including heatmaps plotting Cartesian
  coordinates over images for spatial analytics.
- **Designed the licensing module** on a modular-monolith + Clean Architecture foundation,
  and hardened the application toward **STQC certification**.

---

## Things I've built

### 💸 [MoneyFlow](https://github.com/Omkar6627/moneyflow) — UPI-first spending tracker

Every UPI app in India buries the send button under insurance, gold and scratch cards, and
none of them answer the only question I have: *where did my money go this month?* MoneyFlow
does one job — pay normally, understand your money afterwards. Twelve Indian languages, a
simple mode built for parents who find every other app hostile, insights you can drill into,
and offline-first sync tested against a year of backlog.

It doubles as an honest write-up of a two-day AI-assisted build — including the part where
UPI intent turned out to be structurally incapable of person-to-person payments, and I had
to go find that out myself. Worth reading if you want to know what vibecoding actually
produces, failures included.

`.NET 10` `Angular 22 (zoneless)` `Ionic` `Capacitor` `PostgreSQL`

### 📸 [Visage](https://github.com/Omkar6627/Visage) — on-device AI photo organiser

Point it at 1,500–3,000 wedding photos: it clusters them by scene, groups them by the people
in them, drops the blurry and eyes-closed frames, and reorganises the actual folders so the
output works in Lightroom, Finder or Explorer.

All ML inference runs **in pure C# through ONNX Runtime** — CLIP, ArcFace, SCRFD — with no
Python and no cloud. The filesystem pipeline is fully reversible: every move is logged and
undoable, with SQLite mirroring disk and live progress over SignalR.

`.NET 6` `ONNX Runtime` `SignalR` `Angular 17` `Electron` `SQLite` `WiX`

### 📊 [FinanceTracker](https://github.com/Omkar6627/FinanceTracker) — multi-tenant finance platform

Individual and Enterprise modes from one codebase. Tenant isolation enforced by EF Core
global query filters, a permission matrix, a transaction approval workflow, and an audit log
of every state change. **66 automated tests.** An account starts as a single user and can
become a company in place, without migrating anything.

`.NET 6` `Clean Architecture` `EF Core` `Angular 17` `Ionic` `PostgreSQL` `JWT`

---

## Earlier work

| Project | What it is | Stack |
|---|---|---|
| [Employee Management](https://github.com/Omkar6627/EmployeeManager) | Employee records, attendance, and salary derived from attendance | Java, Spring Boot |
| [Doctor–Patient Management](https://github.com/Omkar6627/DoctorApp) | Scheduling and records for a healthcare practice | Java, Spring Boot |
| [Blogging API](https://github.com/Omkar6627/BlogPost) | REST API for authoring, storing and serving articles | Java, Spring Boot, MySQL |
| [Expense Tracker](https://github.com/Omkar6627/ExpenseTracker) | First take on personal expense tracking — MoneyFlow is where that idea went | Java, Spring Boot, MySQL |
| [OOPs Projects](https://github.com/Omkar6627/OOPs-projects) | Object-oriented design worked through properly | Java |

---

## What I work with

**Languages** — C# · Java · TypeScript · SQL · Dart

**Backend** — ASP.NET Core · Entity Framework Core · Spring Boot · Hibernate · SignalR ·
REST · Clean Architecture · Modular Monolith · Event-Driven · Multi-Tenancy · RBAC · JWT

**Frontend & Mobile** — Angular · Ionic · Flutter · Capacitor · Electron

**Data & Search** — PostgreSQL · SQL Server · MySQL · SQLite · Milvus (vector similarity)

**Streaming & Messaging** — RabbitMQ · SignalR · RTSP / VLC

**Ops & Tooling** — Docker · Grafana · Prometheus · AWS EC2 · ONNX Runtime · Git

<p align="left">
  <a href="https://dotnet.microsoft.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dotnetcore/dotnetcore-original.svg" alt=".NET" width="38" height="38"/></a>
  <a href="https://learn.microsoft.com/dotnet/csharp/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="C#" width="38" height="38"/></a>
  <a href="https://angular.dev/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/angular/angular-original.svg" alt="Angular" width="38" height="38"/></a>
  <a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="TypeScript" width="38" height="38"/></a>
  <a href="https://flutter.dev/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/flutter/flutter-original.svg" alt="Flutter" width="38" height="38"/></a>
  <a href="https://www.java.com" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="Java" width="38" height="38"/></a>
  <a href="https://spring.io/" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/springio/springio-icon.svg" alt="Spring" width="38" height="38"/></a>
  <a href="https://www.postgresql.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" width="38" height="38"/></a>
  <a href="https://www.rabbitmq.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/rabbitmq/rabbitmq-original.svg" alt="RabbitMQ" width="38" height="38"/></a>
  <a href="https://www.docker.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" alt="Docker" width="38" height="38"/></a>
  <a href="https://grafana.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/grafana/grafana-original.svg" alt="Grafana" width="38" height="38"/></a>
  <a href="https://prometheus.io/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/prometheus/prometheus-original.svg" alt="Prometheus" width="38" height="38"/></a>
  <a href="https://aws.amazon.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="AWS" width="38" height="38"/></a>
  <a href="https://ionicframework.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/ionic/ionic-original.svg" alt="Ionic" width="38" height="38"/></a>
  <a href="https://git-scm.com/" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="Git" width="38" height="38"/></a>
</p>

---

**B.E., Mumbai University** (2021) · **Diploma, MSBTE** (2017)

📄 [Full CV](https://docs.google.com/document/d/1EiV6_VQIpfkeKwtDm2_R8wK4U8dShOK_8QJbhZixXns/preview)

> **Open to backend and full-stack roles.** If you want to see how I think rather than just
> what I've shipped, read the [MoneyFlow write-up](https://github.com/Omkar6627/moneyflow) —
> it documents a two-day build including the parts that failed and why.
