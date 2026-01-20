# Your Agent Skill 🧠

> **A Comprehensive Ecosystem of 90+ Specialized AI Agent Personas**  
> *Empowering developers, architects, and creators with specialized AI expertise.*

**Author:** Fakhri Aditia Rahman  
**Repository:** [Your-Agent-Skill](https://github.com/Your-Agent-Skill)

---

## 📋 Overview

**Your Agent Skill** is not just a collection of prompts; it is a meticulously engineered library of over 90 specialized AI agent personas. Each skill is crafted to act as a **Subject Matter Expert (SME)** in a specific domain—from Low-level C programming to SEO Authority Building, from Kubernetes Architecture to Startup Financial Modeling.

This project transforms your AI coding assistant (like GitHub Copilot, Cursor, or custom agents) into a versatile team of experts.

## 🔄 The Complex Agentic Workflow (Alur Kerja Kompleks)

To maximize the potential of these skills, we recommend following a **Multi-Agent Lifecycle** approach. This workflow mimics a real-world software development lifecycle (SDLC) but tailored for AI-augmented teams.

### 1. 🚀 Strategy & Discovery Phase
*Before a single line of code is written.*
- **`business-analyst`**: Define requirements, scope, and user stories.
- **`market-sizing-analysis`** & **`competitive-landscape`**: Validate the product idea.
- **`startup-financial-modeling`**: Plan resources and projections.
- **`planning`** & **`writing-plans`**: Synthesize findings into actionable milestones.

### 2. 🏗️ Architecture & Design Phase
*Establishing the solid foundation.*
- **`architect-review`**: High-level review of the proposed system.
- **`cloud-architect`** & **`hybrid-cloud-architect`**: Design the infrastructure (AWS/Azure/GCP).
- **`database-architect`** & **`postgresql-table-design`**: Design efficient, normalized schemas.
- **`design-system-architect`** & **`ui-designer`**: Define visual language and tokens.
- **`api-documenter`**: Spec out API contracts (OpenAPI/Swagger).

### 3. 💻 Implementation Phase (The "Builders")
*Specialized coding based on the architectural blueprint.*
- **Frontend**: `frontend-developer`, `react-pro` (implied), `ui-designer`.
- **Backend**: `backend-architect`, `golang-pro`, `rust-pro`, `python-pro` (implied), `php-pro`.
- **Mobile**: `mobile-developer`.
- **Specialized**: `blockchain-developer`, `unity-developer`, `senior-iot`.
- **Security Interceptors**: `backend-security-coder`, `frontend-security-coder` (Run these alongside builders).

### 4. ⚔️ Quality Assurance & Security Phase
*Hardening the product.*
- **`code-reviewer`**: Analyzes pull requests for maintainability and style.
- **`security-auditor`** & **`pci-compliance`**: Deep dive security checks.
- **`test-automator`** & **`e2e-testing-patterns`**: Generate Cypress/Playwright suites.
- **`debugger`**: Resolve complex logic errors.

### 5. 📈 Optimization & Growth Phase
*Refining for production and market.*
- **DevOps**: `devops-troubleshooter`, `kubernetes-architect`, `terraform-specialist`.
- **Performance**: `performance-engineer`, `sql-optimization-patterns`, `database-optimizer`.
- **SEO & Content**: `seo-authority-builder`, `seo-structure-architect`, `content-marketer`.

---

## 🧩 Categorized Skills Library

### 🏗️ Architecture & Infrastructure
- `architect-review`
- `backup-architect`
- `cloud-architect`
- `database-architect`
- `kubernetes-architect`
- `terraform-specialist`

### 💻 Development Experts
- **Languages**: `c-pro`, `cpp-pro`, `golang-pro`, `javascript-pro`, `typescript-pro`, `php-pro`, `ruby-pro`, `rust-pro`.
- **Domains**: `senior-iot`, `blockchain-developer`, `game-developer` (Unity), `mobile-developer` (iOS/Android).

### 🛡️ Security & Compliance
- `backend-security-coder`
- `frontend-security-coder`
- `mobile-security-coder`
- `security-auditor`
- `pci-compliance`
- `pfi-compliance` (Billing)

### 📊 Data & Databases
- `database-admin`
- `database-optimizer`
- `sql-pro`
- `sql-optimization-patterns`
- `data-storytelling`

### 🚀 Business & Startup
- `business-analyst`
- `startup-analyst`
- `startup-financial-modeling`
- `startup-metrics-framework`
- `payment-integration` (Stripe/PayPal)

### 📢 SEO & Content Authority
- `seo-authority-builder` (E-E-A-T)
- `seo-keyword-strategist`
- `seo-structure-architect`
- `seo-content-auditor`
- `content-marketer`

---

## 🛠️ Usage

### Quick Start
To activate a specific skill in your agent environment, verify the `.agent/skills` directory exists and reference the skill by name.

```bash
# Example: Using the Senior IoT skill
@senior-iot Help me design an MQTT architecture for 10k devices.
```

### Context Loading
For complex tasks, load multiple complementary skills:

```markdown
User: @backend-architect @security-auditor @sql-pro
Task: Design a high-performance user authentication system.
```
*The Backend Architect designs the structure, Security Auditor ensures checking for vulnerabilities (AuthZ/AuthN), and SQL Pro optimizes the schema.*

---

## 🤝 Contributing

Contributions are welcome! If you have a specialized skill set, please submit a PR adding a new directory in `.agent/skills/` with a `SKILL.md` file following our template.

---

**© 2026 Fakhri Aditia Rahman.** All Rights Reserved.