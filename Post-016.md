# Post 016 - Exploring Permissions

**Date Posted:** 3rd August 2026
**LinkedIn Post:** [View Post](https://www.linkedin.com/feed/update/urn:li:activity:7490001891922321410/)

---

## Context
After exploring files and directories, moved on to understanding
how **permissions** are handled in Linux.

**Follow-up on previous issue:** The file path confusion mentioned
earlier is now resolved — worked through it with a dedicated
revision session. ✅

---

## Topics Covered

### Users
An account representing a human operator or an internal
system process that interacts with the OS.
**Types:** Root, Regular, System/Service

### sudo Command
- Stands for **"Super user do"**
- Provides root-level privileges to the user
- ⚠️ Requires caution — careless use can cause root-level
  damage to the system

### The 10-Character String
**Format:** `[file (-) or directory (d)][rwx (owner)][rwx (group)][rwx (other)]`
- `r` = read, `w` = write, `x` = execute
- Defines permissions for owner, group, and other
- **Example:** `drwxrw-r--` → Directory; owner can do all,
  group can read and write, other can only read

### ls -l Command
Used to display the 10-character permission string
of a file or directory.

### chmod Command
Change Mode — used to change and modify security
permissions of a file or directory.

### Executables
Used to execute program files directly from the terminal.

### chown Command
- Used to change the owner of a file or directory
- Root-level step — requires `sudo` to perform

---

## Honest Reflection

**Main focus this week:** Handling permissions carefully —
using or changing permissions randomly can cause system
damage or failure.

**Difficulty faced:** Reading the 10-character string was
initially confusing due to the hyphens. Got familiar with
it after reading multiple examples.

**Reflective question posed to audience:**
*"Have you also worked on permissions? Have you explored
any new stuff from your learnings?"*

---

## Documentation Links
- 📁 [Learning-Linux-Module (command syntax log)](https://github.com/niravp-06/Learning-Linux-Module.git)
- 📁 [Career Path — LinkedIn Documentation](https://github.com/niravp-06/Career-Path---LinkedIn-Documentation.git)

---

## Hashtags Used
`#SystemsEngineer` `#Linux` `#DevOps`

---

## Status
🔄 Continuing Linux module — permissions concept solidified.

---