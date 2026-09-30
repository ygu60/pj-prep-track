# PJ Indoc Prep Tracker

Phase 2 (Oct 5 → Dec 27, 2026) training log for PJ Indoc prep: 12 weeks, 3:1 blocks, with every session pre-filled (Stew Smith PT, TF VooDoo short & heavy rucking, 50-50s, LATA fins, strength).

**Tabs:** Today (log sets, check-in) · Week (summary + review) · IFT (monthly scores vs old Indoc standards) · Tests · Progress (charts) · Plan · Backup (export, restore, GitHub sync).

## Host it (GitHub Pages, free)
1. Create a new repo on GitHub named `pj-prep-tracker` (public, or private if you have Pro).
2. Push this folder:
   ```bash
   git remote add origin https://github.com/<your-username>/pj-prep-tracker.git
   git branch -M main
   git push -u origin main
   ```
   Or on github.com: **Add file → Upload files** and drag in everything in this folder.
3. Repo **Settings → Pages → Build and deployment → Deploy from a branch → `main` / `(root)` → Save**.
4. After ~1 minute it's live at `https://<your-username>.github.io/pj-prep-tracker/`.
5. On your phone, open that link → Share → **Add to Home Screen**. It opens like an app and works offline.

## Sync between devices
Data is saved in each browser. To share one log across phone and laptop:
1. github.com → Settings → Developer settings → Personal access tokens → **Fine-grained** → new token with only **Gists: Read and write**.
2. In the app: **Backup → Sync across devices** → paste the token → **Save & connect**. Do the same on each device.
3. The app keeps your log in a secret gist and pulls the newest copy whenever you open it.

The token is stored only in that browser. Secret gists are unlisted, not encrypted.

## Update the plan
Everything is in `index.html` (the plan is the `PLAN` JSON near the top of the script).
