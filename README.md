# 🏛️ OlympGit — Hall of GitFame

Welcome, **initiate**.  
You now stand before **OlympGit**, home of the Git Immortals.  
All who master branching, pulls, and conflict-slaying earn eternal glory in the
**Hall of GitFame**.

> **Your Trial:**  
> Place your name **at the very top** of `HALL_OF_GITFAME.md`.  
> But beware: merge conflicts lurk in these halls. The **Hydra of Lerna** (our
> GitHub Action) grows a new head the instant you open a Pull Request, pushing
> its own line above yours.  
> Conquer the Hydra, resolve the conflict, and merge—only then will your name be
> etched in gold.

---

## 📂 Repository Layout

| Path | Purpose |
|------|---------|
| `olympgit` | Sacred branch that holds `HALL_OF_GITFAME.md` |
| `HALL_OF_GITFAME.md` | The scroll where Immortals are listed — **edit me** |
| `.github/workflows/summon-hydra.yml` | The Hydra that spawns merge conflicts |

---

## ⚔️ The Trials of Git — Opening Moves

| # | Trial | Command / Action |
|---|-------|------------------|
| 1 | **Enter Olympus** | `git clone <repo-url>` |
| 2 | **Branch for Glory** | `git checkout -b add-<your-name>`<br>*(replace `<your-name>` with your actual git username)* |
| 3 | **Inscribe Your First Mark** | Edit **`HALL_OF_GITFAME.md`** and add your line *at the very top*. |
| 4 | **Seal the Offering** | `git add HALL_OF_GITFAME.md`<br>`git commit -m "feat: add <Your Name> to Hall of GitFame"`<br>`git push origin add-<your-name>` |
| 5 | **Present Your Petition to the Gods** | Open a Pull Request:<br>• **Base:** `olympgit`<br>• **Compare:** `add-<your-name>`<br>• Title: `🏛️ Feat: Add <Your Name> to the Hall of GitFame` |

> 🗝️ *What lies beyond?*  
> After Trial 5, the Hydra awakens; a new scroll will guide you through
conflict-slaying and final ascension.
