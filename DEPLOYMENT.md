# KC Dynamic Scheduler — deployments

Two independent, always-on hosts (neither depends on this PC):

1. **GitHub Pages (public, no login needed):** https://hhcwhatnot.github.io/kc-scheduler/
   - Repo: github.com/hhcwhatnot/kc-scheduler (public). Source = `index.html` on `main`.
   - Anyone with the link can open it on any device. To update: edit index.html,
     `git push` — Pages rebuilds automatically in ~1 min.

2. **Claude Artifact (private unless shared):** https://claude.ai/code/artifact/cda56000-2c32-4a11-beb4-8b1c70d8c86d

Both serve the same single-file app. Data is stored per-device in the browser
(localStorage) — it does NOT sync between devices. Admin PIN default `1234`.
