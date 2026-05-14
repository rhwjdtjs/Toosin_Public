# 📘 Development Guide

This document defines the collaboration workflow for the **TEAM NIRIZ Development Team** and the **GitHub Desktop** usage rules for the **TOOSIN** project.
A game client developer joined on May 11th, and we follow a structured collaboration process.

---

## 🖥️ GitHub Desktop Workflow

We use **GitHub Desktop**'s GUI to maintain a clear and simple workflow.

### 1. Branch Strategy
* **`main`**: **"Stable Production"**. Merge only when an MVP stage is fully completed.
* **`dev`**: **"Working Bench"**. All features are merged here first.
* **`Patch_VerXXXX`**: **"Actual Working Branch"**. Branch out from `dev` and merge back after completion.
  * **MUST use the version format.** (e.g., `Patch_Ver0082`, `Patch_Ver0090`)
  * For special tasks like documentation, use the `Document` branch.

### 2. Step-by-Step Workflow

#### Step 1: Sync (Before Starting)
1. Open **GitHub Desktop**.
2. Set **Current Branch** to `dev` and click **Pull origin** to sync.

#### Step 2: Issue Creation (Project Planning)
1. Before starting work, create an issue using the templates in **`C:\Toosin\.github\ISSUE_TEMPLATE`**.
2. Clearly define the goal, sub-tasks, and acceptance criteria.

#### Step 3: New Branch
1. Go to **Branch** -> **New Branch**.
2. Name: **`Patch_VerXXXX`** (e.g., `Patch_Ver0082`).

#### Step 4: Code & Commit
1. **Summary**: Briefly describe the work and click **Commit to Patch_VerXXXX**.

#### Step 5: PR Creation (Code Review)
1. Use the `Pull Request document form.md` template when creating a PR.
2. Title format: `[MVP-X] Task Name`. Include `Closes #IssueNumber`.

#### Step 6: Peer Review & Merge
1. Receive an **Approve** from a team member before merging into `dev`.
2. After merge, switch back to `dev` in Desktop and **Pull origin** to sync.
3. Delete the used `Patch_VerXXXX` branch via **Delete**.

---

## 📝 Commit Convention

| Tag | Description | Example |
| :--- | :--- | :--- |
| **feat** | New feature | `feat: add 3-hit combo attack` |
| **fix** | Bug fix | `fix: character movement during attack` |
| **docs** | Documentation | `docs: update roadmap` |
| **style** | Formatting/Cleanup | `style: fix indentation` |
| **refactor**| Code restructuring | `refactor: optimize stat management` |
| **chore** | Configuration/Meta | `chore: update UE project settings` |
