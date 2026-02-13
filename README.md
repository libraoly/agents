# Personal Coding Agents Workspace

Welcome to your **Personal Coding Agents Workspace**. This repository serves as a centralized hub for managing, developing, and deploying specialized AI agent skills designed to enhance software engineering workflows.

## 🚀 Overview

This workspace is structured to provide AI agents with the necessary context, documentation, and procedural guidance to excel in various programming domains, including frontend frameworks, backend technologies, and development tooling.

## 📂 Project Structure

- `skills/`: Contains specialized agent skills. Each skill folder includes:
  - `SKILL.md`: Core instructions and capabilities of the skill.
  - `references/`: Detailed documentation and best practices.
  - `GENERATION.md` / `SYNC.md`: Metadata for skill management and synchronization.
- `.skill-lock.json`: Dependency and version tracking for installed skills.

## 🛠 Available Skills

| Category | Skills |
| :--- | :--- |
| **Frontend** | Vue, Nuxt, Pinia, Vue Router, VueUse, Tailwind CSS, UnoCSS |
| **Build & Tooling** | Vite, Vitest, Turborepo, pnpm, tsdown |
| **Documentation** | VitePress, Slidev |
| **Guidelines** | Web Design Guidelines, Vue Best Practices, antfu conventions |
| **System** | Skill Creator, Find Skills |

## 📖 How to Use

AI agents in this workspace are configured to:
1. **Understand** the codebase through extensive search and analysis.
2. **Plan** tasks iteratively with user confirmation.
3. **Implement** features following established project conventions.
4. **Verify** changes using built-in testing and linting tools.

## 🛠 Maintenance

To add or update skills, use the provided scripts in `skills/skill-creator/scripts/`:
- `init_skill.py`: Scaffold a new skill.
- `package_skill.py`: Prepare a skill for distribution.
- `quick_validate.py`: Validate skill structure and metadata.

---

*Managed by Gemini CLI Agent.*
