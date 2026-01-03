<div align="center">

# Ashley Leslie  
**Senior Software Engineer** · End-to-End Delivery · Systems Thinking · UI/UX Clarity · Integrations · AI (pragmatic)

<a href="https://asleslie.com/en">
  <img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-asleslie.com-111111?style=for-the-badge">
</a>
<a href="https://www.linkedin.com/in/ashley-leslie-335842275/">
  <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Ashley%20Leslie-111111?style=for-the-badge&logo=linkedin">
</a>
<a href="mailto:ashleysamleslie0503@gmail.com">
  <img alt="Email" src="https://img.shields.io/badge/Email-ashleysamleslie0503%40gmail.com-111111?style=for-the-badge&logo=gmail">
</a>

</div>

<p align="center">
  <a href="#signature-work">Signature work</a> ·
  <a href="#how-i-design">How I design</a> ·
  <a href="#how-i-deliver">How I deliver</a> ·
  <a href="#toolbox">Toolbox</a>
</p>

---

I ship production software end-to-end: clarify the workflow, design boundaries and contracts, build UI + APIs, integrate external services, and keep it stable once it’s live.

My UI/UX focus isn’t “pretty screens” — it’s **clarity**: intuitive flows, strong defaults, and interfaces that explain themselves (especially in workflow-heavy apps).

Most of my professional work lives in private repos (company GitLab / self-hosted), so GitHub here is intentionally light.  
The deeper context is on my portfolio.

<br/>

## Signature work

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>Training Management Platform</h3>
      Led a platform from scratch that replaced spreadsheet coordination with a real workflow:
      lifecycle processes, automated reminders, structured feedback flows, and Microsoft ecosystem integration —
      including <b>Single Sign-On (SSO)</b> via <b>Microsoft Entra ID</b> and Microsoft Graph integrations.
      <br/><br/>
      <sub><b>Angular</b> · <b>Java</b> · <b>SSO (Entra ID)</b> · <b>Microsoft Graph</b> · <b>Azure</b></sub>
    </td>
    <td width="50%" valign="top">
      <h3>Quote / Offer Automation Tool</h3>
      Built a system that turns customer Excel quote requests (often 2–3k semi-structured rows) into a structured, reviewable offer.
      Each row is normalized and evaluated against internal product/pricing data — including a vector database where embeddings
      (from a large text embedding model) enable semantic matching when inputs are inconsistent.
      The workflow is designed around uncertainty: confidence signals, fallbacks, and a UI optimized for fast human verification.
      <br/><br/>
      <sub><b>PostgreSQL</b> · <b>Vector DB</b> · <b>Embeddings</b> · <b>TypeScript</b> · <b>Java</b></sub>
    </td>
  </tr>

  <tr>
    <td width="50%" valign="top">
      <h3>Internal AI Assistant (Department rollout)</h3>
      Deployed an internal AI assistant for selected departments, backed by a vector database fed with curated company knowledge.
      It supports internal discovery and Q&A across documentation and structured context (e.g., organizational structure / hierarchy),
      while respecting restricted access.
      <br/><br/>
      <sub><b>Azure AI Foundry</b> · <b>Vector DB</b> · <b>LLM APIs</b> · <b>React</b></sub>
    </td>
    <td width="50%" valign="top">
      <h3>Modernization & Reliability</h3>
      Kept long-lived services healthy: upgrades, migrations, quality gates, tests, and reducing issues flagged by scanners —
      the work that prevents “small problems” from becoming incidents later.
      <br/><br/>
      <sub><b>Java</b> · <b>CI/CD</b> · <b>Testing</b> · <b>Code Quality</b></sub>
    </td>
  </tr>
</table>

<br/>

## How I design

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>Systems thinking</h3>
      I design for change and production reality:
      clear responsibilities, explicit API contracts (OpenAPI), migration-friendly data,
      and failure-aware behavior (timeouts/retries where appropriate, predictable errors, safe defaults).
      <br/><br/>
      I aim for systems that stay understandable months later — not just “working today”.
    </td>
    <td width="50%" valign="top">
      <h3>UI/UX clarity</h3>
      I like UIs that reduce cognitive load:
      predictable state, good naming, sensible defaults, and flows that guide the user without needing a manual.
      <br/><br/>
      Especially strong in workflow-heavy internal tools (forms, lifecycle states, review steps, edge cases).
    </td>
  </tr>
</table>

<br/>

## How I deliver

- Align early, write decisions down, keep feedback loops short.
- De-risk the unknowns first (integrations, permissions, data quality, rollout).
- Prefer sustainable engineering: observable systems, useful docs, and guardrails that help teams move faster.

<br/>

<details>
  <summary><b>How I use AI</b></summary>
  <br/>
  <b>AI-assisted development</b>: daily driver depending on environment —
  Claude Code for deep iteration/refactoring, and GitHub Copilot in VS Code where it’s standard.
  Always paired with human review + tests as the backstop.
  <br/><br/>
  <b>AI in products</b>: I integrate LLM APIs when they solve a real problem — and design for permissions,
  privacy, fallbacks, and audits.
  <br/><br/>
  <sub><b>Claude / Anthropic</b> · <b>GitHub Copilot</b> · <b>LLM APIs</b> · <b>Guardrails</b></sub>
</details>

<br/>

## Toolbox

<details open>
  <summary><b>Tech I use a lot</b></summary>
  <br/>
  <b>Backend</b>: Java · Spring · REST · WebSockets · OpenAPI/Swagger<br/>
  <b>Frontend</b>: Angular (primary) · TypeScript · React · workflow-heavy UI<br/>
  <b>Data</b>: PostgreSQL · SQL Server · Oracle · Liquibase · Vector similarity search<br/>
  <b>Cloud/Integrations</b>: Azure · Microsoft Graph · Microsoft Entra ID · SSO<br/>
  <b>Quality/Delivery</b>: Docker · Kubernetes · CI/CD · SonarQube · JUnit · Mockito<br/>
  <b>Daily drivers</b>: IntelliJ IDEA · VS Code<br/>
</details>

<br/>

<div align="center">
  <sub><b>Based near Braunschweig, Germany</b> · Remote-first · Hybrid nearby · Relocation if supported</sub><br/>
  <i>Portfolio & case studies: <a href="https://asleslie.com/en">asleslie.com</a></i>
</div>
