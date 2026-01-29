# Trunk-Based Development Demo

This repository demonstrates **Trunk-Based Development (TBD)** — a modern Git branching strategy focused on simplicity, fast feedback, and continuous integration.

---

## What is Trunk-Based Development?

Trunk-Based Development is a branching strategy where:
- There is **only one long-living branch** called the **trunk** (`main`)
- Developers:
  - Commit **directly to the trunk**, or
  - Create **very short-lived branches** (minutes or hours)
- Code is **merged frequently**
- Feature flags are used instead of long-running branches

---

## Strategy
Work directly on trunk
Small, safe changes are committed directly to `main`.

```bash
git checkout main
git pull origin main
git commit -m "Small change on trunk"
git push origin main

