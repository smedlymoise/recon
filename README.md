<<<<<<< HEAD
# Recruiter Verify

A single-page tool for checking whether an inbound recruiter (or anyone messaging you) is likely legitimate — a weighted red-flag checklist, a threat-score readout, and quick search links across LinkedIn, Facebook, Instagram, X/Twitter, TikTok, and phone/company lookups.

Everything runs client-side in the browser. No backend, no accounts, no data sent anywhere except the search links you choose to click (which go straight to Google/the platform itself).

## Files

- `index.html` — the whole app (HTML/CSS/JS in one file)
- `manifest.json` — lets phones install it as a home-screen app
- `icon-192.png`, `icon-512.png` — app icons for the home-screen install

## Put it on GitHub

1. Create a new repository on GitHub (e.g. `recruiter-verify`).
2. Upload these four files to it — either drag-and-drop them in the GitHub web UI ("Add file" → "Upload files"), or from a terminal:

   ```bash
   git init
   git add .
   git commit -m "initial commit"
   git branch -M main
   git remote add origin https://github.com/<your-username>/recruiter-verify.git
   git push -u origin main
   ```

## Host it for free with GitHub Pages

1. In your repo, go to **Settings → Pages**.
2. Under "Build and deployment", set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`.
3. Save. GitHub gives you a live URL after a minute or two, usually:
   `https://<your-username>.github.io/recruiter-verify/`

That URL is what you'll use on your phone and anywhere else — same page, from home or out and about, as long as you have internet.

## Install it on your phone (so it opens like an app)

**iPhone (Safari):**
1. Open the GitHub Pages URL in Safari.
2. Tap the Share icon (square with an arrow) → **Add to Home Screen**.
3. Name it, tap Add. It now opens full-screen from your home screen, no browser bar.

**Android (Chrome):**
1. Open the URL in Chrome.
2. Tap the **⋮** menu → **Add to Home screen** (or **Install app** if Chrome offers it directly).
3. Confirm. It'll behave like a normal app icon.

No app store, no install review — it's just your own webpage saved as a shortcut, so it works identically at home and outside.

## Notes / attribution

- The background world map is adapted from the "Simple SVG World Map" by Al MacDonald, edited by Fritz Lekschas, licensed **CC BY-SA 3.0**. If you modify and redistribute this project, keep that attribution.
- This tool scores risk signals and generates search links — it does not verify identity on its own. The one step nothing here replaces: calling the company back on their own published phone number.
=======
# recon
>>>>>>> b20682e89dc70f1b034cef13b91c5ab9b8bd141e
