# Post 012 - The OS Battle!

**Date Posted:** 12th July 2026
**LinkedIn Post:** [View Post](https://www.linkedin.com/posts/nirav-panchal-3b2a6227b_linux-ubuntu-dualboot-share-7480524663907930112-AyV3/?utm_source=share&utm_medium=member_desktop&rcm=ACoAAERSXbYBBh-aUjGvgdyr18lXWWLdgA7EHro)

---

## Context
Started dual-booting Linux alongside Windows —
assumed it would be a simple, one-time setup process.
Reality turned out far more challenging.

---

## The Struggle — 3 Dual Boot Attempts

| Attempt | What Happened |
|---------|---------------|
| 1st | Accidentally installed Linux onto the Windows boot itself — system ran at peak load, fans screaming. Had to format the entire Windows installation. |
| 2nd | Ubuntu kept freezing after boot. Safely removed it from the dual boot setup. |
| 3rd | Re-installed Ubuntu — started using it, but encountered more freezes and bugs. Used Google AI mode to troubleshoot. |

---

## Root Causes Discovered While Troubleshooting

- System has **2 GPUs** — Linux wasn't able to operate fully
  due to this dual-GPU setup
- Was using an outdated **Ubuntu 2024 version** —
  newer **Ubuntu 26.04** version is now available
- Multiple system-level configuration changes were required:
  - Disabling Intel VMD controller
  - Disabling Secure Boot
  - Disabling Fast Boot
  - Disabling Safe Boot
  - Adjusting Nvidia settings for Linux compatibility

---

## Key Insight — AI-Assisted Troubleshooting
Recognized how AI tools combined with personal effort
can effectively diagnose and solve complex system-level
hardware-OS compatibility issues.

---

## Bigger Reflection

**New opportunities come with new problems.**
Set out to learn Linux — ended up spending 2 days
troubleshooting instead. Reframed this time as
**invested**, not wasted — learned that different
OS environments require different configurations
even on the same hardware.

**Engineering mindset:**
> "Hating one OS and loving another is not the mindset
> an engineer carries. An engineer adapts to new tech
> and opportunities constantly — through new learnings,
> applications, and opportunities."

---

## Moral of the Story
**Learn, Learn, and Learn.**
Knowledge has no limits and does not intend to limit you.

---

## Status
🔄 Linux environment now stable — moving forward with
    actual Linux learning from here.

---