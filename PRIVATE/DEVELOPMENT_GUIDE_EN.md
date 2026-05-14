# 📘 Development Guide

This document defines the collaboration workflow for the **TEAM NIRIZ Development Team** and the **GitHub Desktop** usage rules for the **TOOSIN** project.

---

## 🖥️ GitHub Desktop Workflow

We actively use the **GitHub Desktop** GUI for development to maintain a clear and simple workflow.

### 1. Branch Strategy

We maintain stability while keeping the structure simple.

* **`main`**: **"Production Ready"**. Only merge here when an MVP stage is fully completed.
* **`dev`**: **"Development Stage"**. Features are integrated here after completion.
* **`feature/*`**: **"Feature Work"**. Branch out from `dev`, develop the feature, and merge back into `dev`.
  * e.g., `feature/parry-system`, `feature/ai-learning`

### 2. Step-by-Step Workflow

#### Step 1: Sync (Before Starting Work)
1. Open **GitHub Desktop**.
2. Ensure **Current Branch** is `dev`.
3. Click **Fetch origin** and **Pull origin** to sync with the latest remote changes.

#### Step 2: New Branch
1. Go to **Branch** -> **New Branch**.
2. Name: `feature/task-name` (e.g., `feature/guard-logic`).
3. Click **Create Branch**.

#### Step 3: Code & Commit
1. Write code in Unreal Engine/IDE and save.
2. View changed files in the left panel of GitHub Desktop.
3. **Summary (Required)**: Briefly describe the work (e.g., `feat: implement right-click block logic`).
4. Click **Commit to feature/...**.

#### Step 4: Push & PR
1. Click **Publish branch** (or **Push origin**).
2. Click **Create Pull Request** to open the PR on GitHub.

#### Step 5: PR & Review
1. Use the Pull Request template.
2. Include `Closes #IssueNumber` to link relevant issues.
3. Once approved, merge into `dev`.
4. Delete the local `feature` branch after merging.

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

---

## 📁 Naming Convention (UE5 Standard)

* **Classes**: Use `TS` (Toosin) prefix.
  * `ATSCharacter` (Actor)
  * `UTSGameInstance` (UObject)
* **Variables**: PascalCase
  * `CurrentHealth`, `MaxStamina`, `bIsAttacking` (Boolean uses 'b')
* **Functions**: Start with a verb
  * `CalculateDamage()`, `PlayAttackMontage()`

---

### ⚠️ Caution

* **DO NOT commit directly to `main`.**
* **Always Push** before finishing work for the day to ensure backups.
