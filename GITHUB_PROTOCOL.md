# 🛑 GITHUB PROTOCOL: The Law of Sephrit

**Applicable to:** All AI Agents (Vector, Sentinel, Swarm) and Human Operators.

## 1. Repository Roles (The Triad)

| Repo | Role | Write Access? | Content |
| :--- | :--- | :--- | :--- |
| **`openclaw-vault`** | **State & Memory** | ✅ | Backups, Keys (Encrypted), `MEMORY.md`, Skills Library. |
| **`sephwa-inputs`** | **Workspace** | ✅ | Projects (`projects/name/`), Raw Files, Research Notes. |
| **`sephwa-outputs`** | **Deliverables** | ✅ | Final Reports, Architecture Docs, Clean Code Snippets. |

## 2. Commit Standards
Use Conventional Commits:
*   `Feat: Added 3D Viewer`
*   `Fix: Resolved OOM crash`
*   `Docs: Updated Architecture.md`
*   `Backup: Daily Snapshot`

## 3. Branching Strategy
*   **Websites (`sp4cht-com`):** Push to `develop`. `main` is protected (Production).
*   **Docs:** Push to `main` is allowed.
*   **Code:** Use feature branches (`feature/add-login`).

## 4. File Placement
*   **NEVER** put loose files in root. Always use a folder (`docs/`, `scripts/`).
*   **NEVER** commit `.env`, `token.json`, or API keys. (Use `.secrets/` locally).

## 5. Agent Behavior
*   Before creating a file, check `PROJECT_TEMPLATE.md`.
*   Before uploading, **Link** the output in the chat.
