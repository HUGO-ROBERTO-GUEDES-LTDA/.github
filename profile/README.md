# ## HRGUEDES - Developer Internal Rules ☕️💻

This is the profile repository for the **HRGUEDES** organization. This document serves as the Standardization Guide for all contributors and internal projects.

### 🎯 Our Mission
To deliver robust software with agility, maintaining clean code and secure infrastructure.

---

### 🛠️ Standardization & Governance Guide

To keep our environment organized, all members must follow these guidelines when creating or maintaining repositories:

#### 1. Repository Naming Convention
We use the pattern **[PRODUCT]-[PROJECT-NAME]**. 
Examples:
* `mob-sales-app` (For projects under the MOB product)
* `crm-api-backend` (For projects under the CRM product)
* `web-landing-page`

#### 2. Code Hygiene (Initial Setup)
Every new repository **must mandatory** contain:
* A proper `.gitignore` file for the language/framework being used.
* A `README.md` file explaining how to run the project locally.

#### 3. Security First (Zero Leak Policy) 🔐
It is strictly forbidden to version:
* API Keys, database passwords, or tokens.
* `.env` files or configuration files containing sensitive data.
> **Tip:** Use environment variables on the server and provide an `.env.example` file in the repository.

---

### 🚀 Workflow
1. **Branching:** Use `main` for production and `develop` for integration.
2. **Pull Requests:** All code must be reviewed before merging.
3. **Commits:** Prefer clear messages in Portuguese (or the standard defined for the specific project).

---

### 📞 Contact & Support
If you encounter any infrastructure issues or need access to new tools:

* **CTO / Admin:** [Hugo Guedes]
* **Corporate E-mail:** [hugo.guedes@hrguedes.dev]

---
*HRGUEDES - Turning coffee into digital solutions.*
