<a href="https://joshuakhooba.com" title="Meet him properly on my site — he follows your cursor over there">
  <img align="right" width="380" src="https://raw.githubusercontent.com/JoshuaKhooba/JoshuaKhooba/main/corgi.svg" alt="Animated corgi mascot typing at a laptop" />
</a>

# Joshua Khooba

[![Typing SVG](https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=20&duration=2600&pause=1000&color=2563EB&center=false&vCenter=true&width=440&height=30&lines=Full-stack+%2B+iOS+engineer;Typed%2C+well-structured+codebases;Open+to+new-grad+roles)](https://git.io/typing-svg)

**Software Engineer** · Full-stack and iOS development · Orlando, FL

B.S. Information Technology, minor in Computer Science — University of Central Florida, May 2026. I build full-stack web applications and native iOS apps, with a focus on typed, well-structured codebases and clean data modeling.

[![Portfolio](https://img.shields.io/badge/Portfolio-joshuakhooba.com-1D4ED8?style=flat-square)](https://joshuakhooba.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-joshua--khooba-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/joshua-khooba/)
[![Email](https://img.shields.io/badge/Email-JoshuaK419%40gmail.com-4B5563?style=flat-square)](mailto:JoshuaK419@gmail.com)

Currently open to new-grad software engineering roles.

<br clear="all" />

---

## Selected Work

Every section below expands. Click a project to see how it was actually built.

<details>
<summary><b>FlowSync</b> — Full-stack project management application</summary>

<br/>

Kanban board with drag-and-drop status transitions, Gantt timeline, and cross-entity search over a normalized seven-model relational schema. Four interchangeable task views — board, list, table, and timeline — all backed by a single cached data layer.

- Status changes fire a `PATCH` and invalidate a cache tag rather than mutating local state, so the client stays a pure projection of server state
- Five priority routes render one reusable page component, keeping filter logic in exactly one place
- Seed script clears and inserts in explicit dependency order so foreign key constraints never fail mid-run
- Cognito is the identity source of truth; the API stores a `cognitoId` and never handles passwords

`TypeScript` `Next.js 14` `Express` `Prisma` `PostgreSQL` `Redux Toolkit Query` `AWS Cognito`

[Repository](https://github.com/JoshuaKhooba/FlowSync)

</details>

<details>
<summary><b>EcoVest</b> — Sustainable investing simulator <i>(live demo)</i></summary>

<br/>

Built in a 12-hour hackathon at UCF. Simulates a $10,000 portfolio across 19 equities and ETFs, then proposes an explainable reallocation toward clean-energy holdings with a generated rationale for every trade.

- Reallocation engine surfaces its reasoning per position rather than returning an opaque score
- Unlocks a green-portfolio yield tier once allocation thresholds are met
- Judged across the Bloomberg FinTech, OneEthos, and Google Gemini tracks

`TypeScript` `Next.js` `Tailwind CSS` `Google Gemini API`

[Repository](https://github.com/JoshuaKhooba/EcoVest) · [Live demo](https://eco-vest-nine.vercel.app/)

</details>

<details>
<summary><b>Train Yard Simulator</b> — Concurrent systems simulation</summary>

<br/>

Models 30 trains as independent threads competing for 10 shared switches across 60 route configurations, driven entirely by CSV input.

- Bounded `ExecutorService` thread pool caps concurrency instead of spawning unbounded threads
- Ordered lock acquisition guarantees deadlock-free scheduling under heavy contention
- Every switch is individually synchronized, so unrelated routes proceed in parallel

`Java` `Concurrency` `ExecutorService` `Thread synchronization`

[Repository](https://github.com/JoshuaKhooba/train-yard-multithreaded-simulator)

</details>

<details>
<summary><b>Disney VIP App</b> — Native iOS reservation manager</summary>

<br/>

MVVM iOS application spanning 15+ views for authentication, reservations, events, and guest check-in, backed by a hosted Postgres service with row-level access rules.

Built after a year inside Disney's VIP operations, where I managed 100+ itineraries a week by hand — the app is the tool I wanted while doing that job.

`Swift` `SwiftUI` `MVVM` `Supabase`

[Repository](https://github.com/JoshuaKhooba/Disney-VIP-App)

</details>

<details>
<summary><b>Space Portfolio</b> — Personal site <i>(powers joshuakhooba.com)</i></summary>

<br/>

Animated 3D starfield rendered with React Three Fiber, scroll-driven motion, and a fully responsive layout.

`TypeScript` `Next.js 14` `Three.js` `React Three Fiber` `Framer Motion`

[Repository](https://github.com/JoshuaKhooba/Space-Portfolio) · [Live site](https://joshuakhooba.com)

</details>

<details>
<summary><b>Three-Tier Web App</b> — Role-based enterprise application</summary>

<br/>

Servlet and JSP application enforcing four distinct database roles, with parameterized statements and stored procedures throughout.

- Separate credentials per role — root, client, data entry, and accountant — enforced at the database layer, not in application code
- `PreparedStatement` and `CallableStatement` used exclusively, so no query is assembled by string concatenation
- Dedicated audit table logs every privileged operation

`Java` `Servlets/JSP` `Tomcat` `MySQL` `JDBC`

[Repository](https://github.com/JoshuaKhooba/three-tier-web-app)

</details>

---

## Technical Skills

| | |
| :-- | :-- |
| **Languages** | TypeScript, JavaScript, Java, Python, Swift, C, SQL |
| **Frontend** | React, Next.js, Tailwind CSS, Redux Toolkit, SwiftUI, Three.js, Framer Motion |
| **Backend** | Node.js, Express, REST API design, Java Servlets/JSP |
| **Data** | PostgreSQL, MySQL, Prisma, Supabase, JDBC, schema design and migrations |
| **Cloud & Tools** | AWS (Cognito, IAM), Vercel, Git, Linux, Docker, Xcode, Figma |

---

## Experience

| Role | Organization | Period |
| :-- | :-- | :-- |
| AI Trainer | LinkedIn (Contract) | Jul 2026 – Present |
| IT Technician | Asurion / uBreakiFix | Mar 2026 – Jun 2026 |
| VIP Operations Intern | The Walt Disney Company | Jan 2025 – Jan 2026 |
| Data Analysis Intern | Orange County Government | Aug 2022 – Jan 2023 |

Full history and detail on [LinkedIn](https://www.linkedin.com/in/joshua-khooba/).

---

## Education & Certifications

**University of Central Florida** — B.S. Information Technology, minor in Computer Science · May 2026

**College of Central Florida** — A.S. Computer Science · May 2022

- [AWS Academy Graduate: Cloud Security Foundations](https://www.credly.com/go/pOJRHvzj) · May 2026
- TestOut IT Fundamentals Pro · Dec 2024 · ID 6-3C6-2FT66

---

## Beyond the Code

<details>
<summary><b>Competitive card games</b> — regional tournament results</summary>

<br/>

I play trading card games at a competitive level and travel for regional events.

| Event | Result |
| :-- | :-- |
| One Piece Card Game — Regional | Top 16 |
| Pokémon TCG — Regional | Top 32 |

Both games reward the same things engineering does: reading an evolving meta, managing limited resources across many turns, and committing to decisions with incomplete information. Deck construction in particular is an optimization problem with a hard constraint — 50-odd slots, and every inclusion costs you another.

</details>

<details>
<summary><b>Tennis and training</b> — UCF Tennis Team</summary>

<br/>

I played on the tennis team at the University of Central Florida and still train regularly. Most mornings start in the gym before anything else does.

Balancing a competitive season against a full CS-minor course load is the main reason I plan work in fixed blocks rather than open-ended stretches.

</details>

<details>
<summary><b>Gardening and cattle</b> — the unexpected one</summary>

<br/>

I garden, and I help raise cattle. It is genuinely the most useful hobby I have for staying sane in this field: the feedback loop is measured in seasons rather than seconds, nothing can be rushed by working harder, and there is no undo. It is a good counterweight to a job where iteration is nearly free.

</details>

<details>
<summary><b>Everything else</b> — parks, travel, board games, and one abandoned career</summary>

<br/>

- **Theme parks** — Disney and Universal annual passholder. This turned into a job and then into an app, so it is no longer strictly a hobby
- **Travel** — I have travelled through much of North and South America
- **Board games** — the heavier and longer the better
- **Anime** — long-running series, which is how I ended up at a One Piece regional
- **Cars** — a persistent interest in sports cars that my budget does not currently share
- **Spicy food** — the actual limiting factor is everyone else at the table
- **Corgis** — I own one, which is why there is a corgi at the top of this page
- **Standup comedy** — the plan if college had not worked out. The material was not good enough, but the timing carried over into presentations

</details>

<details>
<summary><i>Give him a treat</i></summary>

<br/>

<div align="center">
  <img width="420" src="https://raw.githubusercontent.com/JoshuaKhooba/JoshuaKhooba/main/corgi-happy.svg" alt="The corgi, delighted" />
  <br/>
  <sub>He follows your cursor on <a href="https://joshuakhooba.com">joshuakhooba.com</a>.</sub>
</div>

</details>
