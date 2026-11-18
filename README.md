# JARVIS Build 001 — R0 starter

This is a local-first progressive web app starter for Android and desktop.

## What works now
- Business/project list
- Income and expense records in ZAR
- Task list with completion state
- Dashboard totals
- AI handoff: opens ChatGPT with a prepared prompt (uses ChatGPT separately; no API integration)
- Offline app shell after first load on a supported HTTPS host

## Important limitations
- Data is saved in the browser's localStorage on this device/browser. It is not synced or backed up automatically.
- This does not have unrestricted Android permissions, background autonomy, payment access, or direct access to other apps.
- ChatGPT handoff is not an embedded AI API. No income is guaranteed.
- Export/backup and secure account sync should be added before relying on this for important business records.

## Free setup using GitHub Pages
1. On the laptop, open https://github.com and create a free account or sign in.
2. Create a new public repository named `jarvis-command-centre`.
3. Upload `index.html`, `manifest.webmanifest`, `sw.js`, and `icon.svg` from this folder to the repository root.
4. In the repository, open **Settings → Pages**.
5. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
6. Wait for GitHub Pages to publish. Your site URL will be shown in the Pages section.
7. Open that URL in Chrome on your Android phone. Use Chrome's menu → **Install app** or **Add to Home screen**.
8. Keep the URL private if you later add sensitive information. This first version has no login or cloud security.

## First test
Add a project, record a small test income (then delete it), add a task and mark it complete. Check the dashboard totals.

## Next build
Add data export/import backup, business-specific notes, monthly reports, then carefully scoped Android integrations. Never store passwords, banking PINs, or one-time codes in this app.
