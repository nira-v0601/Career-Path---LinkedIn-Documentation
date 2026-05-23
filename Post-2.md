# Post 002 - Deep Dive into Commits

**Date Posted:** 07-05-2026
**LinkedIn Post:** [View Post](https://www.linkedin.com/posts/nirav-panchal-3b2a6227b_gitgithub-git-github-share-7458115395422552065-c_ty/?utm_source=share&utm_medium=member_desktop&rcm=ACoAAERSXbYBBh-aUjGvgdyr18lXWWLdgA7EHro)
---

## Learning Period
28 April 2026 – 06 May 2026

---

## Core Insight
Previously thought every change demands a new commit.
That understanding got corrected through this phase of learning.

---

## Topics Covered

### 1. git reset (Undoing Commits)
Used for undoing committed changes. Three modes:

| Command | What it Does | Risk Level |
|---------|-------------|------------|
| `git reset --soft` | Revokes commit, keeps changes in staging area | Safe |
| `git reset --mixed` | Revokes commit + unstages changes | Moderate |
| `git reset --hard` | Deletes commit + all file changes permanently | ⚠️ Dangerous |

---

### 2. git log --oneline
````git log --oneline```
Displays commit history with short commit hashes.
Useful for quickly navigating through commit history.

---

### 3. git commit --amend
Used to edit the previous commit without creating a new one.
- Can edit the commit message
- Can add/modify files into the previous commit

**Key clarity gained:** Not every change needs a new commit.
Amend handles minor additions/corrections cleanly.

---

### 4. git cherry-pick
```git cherry-pick <commit hash>```
Copies a specific commit from one branch to another.

**Real world analogy:**
- Project split across branches
- Person-2 needs Feature-4 from Person-3's branch
- Instead of merging entire branch, cherry-picks only that commit

---

## Honest Reflection
Encountered a **merge conflict** while practicing cherry-pick.
Merge conflicts not yet studied — decided to practice more
before moving forward rather than rushing through confusion.

---

## Status
🔄 Practicing and refining before progressing further.

---
```

---
