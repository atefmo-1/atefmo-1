<h1 align="center">Hey, I'm Atef 👋</h1>

<p align="center">
  I build AI products end to end: talk to the users, decide what to build, write the code, ship it, measure it.<br/>
  CS + Information Science at UNC Chapel Hill '27 · Morehead-Cain Scholar · grew up in Sharqia, Egypt 🇪🇬
</p>

<p align="center">
  <a href="https://www.atefmohamed.com"><img src="https://img.shields.io/badge/portfolio-atefmohamed.com-000000?style=for-the-badge&logo=vercel&logoColor=white" /></a>
  <a href="https://linkedin.com/in/mohamedatefali"><img src="https://img.shields.io/badge/LinkedIn-connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:mohamedatefali18@gmail.com"><img src="https://img.shields.io/badge/email-say_hello-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

---

### 🚀 Reloco: an F-1 co-pilot for international students · [reloco.app](https://reloco.app) · [case study](https://www.atefmohamed.com/projects/reloco)

A live web app I built solo that turns an international student's visa rules, taxes and paperwork into one ordered plan, with an AI assistant that knows their situation.

- **Planning engine:** deterministic, resolves 49 typed tasks from date anchors and a dependency graph, streamed to the client as NDJSON. Guarded by 300+ Vitest tests.
- **AI assistant:** a streaming tool-use agent on the Claude API with prompt caching. Rules stay in code; the model only reads and explains, and every citation is validated before a student sees it.
- **Evals I wrote:** 85/85 Ask cases (including scams and prompt injection) at ~1¢ a question; document reading 196/196 fields with structured outputs; models chosen by eval, not by vibe.
- **Security, because it holds passports:** AES-256-GCM field-level encryption, row-level security across 15 Postgres migrations, per-request CSP nonces, Sentry with personal data stripped, 2 security reviews.

`Next.js` · `TypeScript` · `React` · `Supabase Postgres` · `Claude API` · `Vercel` · `Vitest` · `Zod`

Code: [atefmo-1/reloco](https://github.com/atefmo-1/reloco)

### 💼 Experience

- **Well:** Product Manager Intern. Built a production Salesforce ↔ Claude integration over MCP, plus a 27-skill library rolled out to 50 people (88% weekly active, 94% reported time savings).
- **Ethos:** Product & Analytics Intern. Debugged the SQL behind 30+ analytics dashboards; designed an RBAC model with engineering.
- **MNIPL:** Product Development Intern. Led tech and design on a home energy-audit web app, 0 to 1, now live across Minnesota.

### 🛠️ Toolbox

**Languages:** TypeScript, JavaScript, Python, SQL, Java, C/C++
**Web & data:** React, Next.js, Node.js, Tailwind CSS, PostgreSQL, Supabase, Snowflake
**AI:** Claude API (tool use, structured outputs, prompt caching), MCP, LLM evals, Claude Code
**Shipping:** Vercel, Sentry, Vitest, Git

---

<p align="center"><i>I've been the new person in the room a lot. Turns out that's most of building: knowing what to ask.</i></p>
