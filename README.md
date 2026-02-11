# web-app
web-app-test
# Hi there, I'm Punit 👋

Manager - Projects @ Cognizant | Frontend Developer | GenAI Enthusiast  
Building modern web apps with **React + Next.js**, automation with **GitHub Actions**, and scalable serverless on **AWS**.

[Portfolio](https://your-portfolio-url.com) · [LinkedIn](https://linkedin.com/in/your-profile) · [Twitter/X](https://x.com/your-handle) · [Email](mailto:your.email@example.com)

---

## 🚀 About Me
- 💼 Experience in Agile delivery, UI/UX, and component-driven development
- 🧠 Learning & using **GitHub Copilot** and **Copilot Chat** for code review/workflows
- ⚙️ Building **GenAI-driven productivity tools** and internal accelerators
- 🧩 Love architecting reusable systems and design‑system components
- 🌱 Currently exploring: **Next.js App Router**, **Server Actions**, **RSC**, **AI Agents**

---

## 🛠️ Tech Stack

**Frontend:** HTML, CSS, JavaScript (ES6+), TypeScript  
**Frameworks:** React, Next.js (App Router), Vite  
**Styling:** Tailwind CSS, MUI, Styled Components  
**Testing:** Jest, React Testing Library, Cypress  
**Data & APIs:** REST, GraphQL, SWR/React Query  
**Build & DevOps:** Git, GitHub Actions, Vercel, Netlify, Docker  
**Cloud:** AWS (Lambda, API Gateway, DynamoDB, S3, CloudFront)  
**GenAI:** GitHub Copilot, OpenAI API, Prompt Engineering

---

## 📌 Featured Projects

### 1) Simple2Know – Internal Tool Accelerator
A full‑stack **Next.js + AWS serverless** platform for automated content workflows.

- 🔗 **Live:** https://your-demo-link.com  
- 🧩 **Stack:** Next.js, Tailwind, Lambda, DynamoDB, S3  
- 🎯 **Highlights:** Content pipelines, role-based auth, CI/CD with GitHub Actions  
- 📄 **Repo:** https://github.com/your-username/simple2know

---

### 2) Agile Productivity Dashboard
GenAI‑assisted dashboard for **Agile metrics** (velocity, lead time, burndown).

- 🔗 **Live:** https://your-demo-link.com  
- 🧩 **Stack:** React, Recharts, Node.js, JWT Auth  
- 🧠 **AI:** Copilot‑assisted code generation & insights  
- 📄 **Repo:** https://github.com/your-username/agile-productivity-dashboard

---

### 3) React Components Collection
Production‑ready, accessible UI components with tests and stories.

- 🔗 **Docs:** https://your-docs-link.com  
- 🧩 **Stack:** React, TypeScript, Storybook, Jest, RTL  
- 🧪 **Quality:** 95% coverage, ESLint + Prettier + Husky  
- 📄 **Repo:** https://github.com/your-username/react-components-collection

---

## 🧭 Open Source & Contributions
- 🛠️ PRs: docs fixes, UI refinements, unit tests
- 📄 Issues: accessibility, performance improvements
- 🔍 Areas: React patterns, Next.js best practices, DevEx tooling

---

## 🧪 Testing & Quality
- ✅ Unit tests with **Jest + React Testing Library**  
- 🧪 E2E tests with **Cypress**  
- 🧹 Static analysis: **ESLint**, **TypeScript**  
- 🧰 Pre-commit hooks (Husky) and **lint-staged**

---

## ⚙️ CI/CD & Automation (GitHub Actions)
- 🚀 Auto‑deploy to **Vercel** on `main`  
- 🧪 Run test suite, lint, and type‑check on every PR  
- 🧼 Auto‑format and enforce conventional commits

```yaml
# .github/workflows/ci.yml (excerpt)
name: CI
on:
  pull_request:
  push:
    branches: [ main ]
jobs:
  build-and-test:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: actions/setup-node@v4
        with:
          node-version: 20
      - run: npm ci
      - run: npm run lint && npm run typecheck
      - run: npm test -- --ci