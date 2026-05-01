# Amy's Fitness Tracker — Deployment Guide

## What you're deploying
A Progressive Web App (PWA). Once live, Amy opens the URL in Safari or Chrome,
taps **"Add to Home Screen"**, and it installs like a real app — full-screen,
no browser bar, works offline, data saved on-device.

---

## Step 1 — Create a GitHub account
1. Go to **github.com** and sign up (free)
2. Confirm your email address

---

## Step 2 — Create a new repository
1. Click the **+** icon → **New repository**
2. Name it exactly: `amy-fitness` (or anything you like)
3. Set it to **Public**
4. Leave everything else unchecked
5. Click **Create repository**

---

## Step 3 — Upload the files
1. On the new repo page, click **"uploading an existing file"**
2. Drag and drop ALL of these files/folders:
   ```
   index.html
   manifest.json
   sw.js
   icons/          ← drag the whole folder
     icon-192.png
     icon-512.png
     favicon.png
   ```
3. Scroll down, click **Commit changes**

---

## Step 4 — Enable GitHub Pages
1. Go to your repo → **Settings** → **Pages** (left sidebar)
2. Under **Source**, select **Deploy from a branch**
3. Branch: **main** · Folder: **/ (root)**
4. Click **Save**
5. Wait ~60 seconds, then refresh — you'll see your live URL:
   `https://YOUR-USERNAME.github.io/amy-fitness/`

---

## Step 5 — Install on Amy's phone

### iPhone (Safari required — Chrome won't show the install prompt)
1. Open Safari and navigate to the URL
2. Tap the **Share** button (box with arrow at the bottom)
3. Scroll down → **Add to Home Screen**
4. Name it "Amy Fit" → **Add**
5. The app icon appears on the home screen — tap it to launch full-screen

### Android (Chrome)
1. Open Chrome and navigate to the URL
2. Chrome shows a banner: **"Add Amy Fit to Home Screen"** — tap it
   - If the banner doesn't appear: tap ⋮ menu → **Add to Home Screen**
3. The app icon appears — tap to launch full-screen

---

## Updating the app
When a new version of the HTML file is built:
1. Go to your GitHub repo
2. Click on `index.html` → pencil icon (Edit)
3. Select all, paste the new content → **Commit changes**
4. The next time Amy opens the app with internet, it auto-updates in the background

Or drag-and-drop the new file via the GitHub web UI to replace it.

---

## Data & privacy
- All data (workouts, Pokédex, weights) is stored **only on Amy's device** in `localStorage`
- Nothing is sent to any server
- GitHub only hosts the app code, not any personal data

---

## Troubleshooting
| Problem | Fix |
|---|---|
| White screen on load | Wait 10s and refresh — GitHub Pages takes a moment to go live |
| App doesn't show "Add to Home Screen" on iPhone | Must use Safari, not Chrome |
| Data disappeared | Check if private/incognito mode is on — localStorage doesn't persist there |
| App doesn't update | Close and reopen — the SW updates in the background |
