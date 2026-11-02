# Tiga Hari Gym — offline app (PWA)

Upload everything in this folder to your GitHub Pages repo (keep the folder structure:
`index.html`, `manifest.webmanifest`, `sw.js`, `icons/`, `fonts/`, `vendor/`).

## Install on your phone
- **iPhone (Safari):** open the link → Share → *Add to Home Screen*.
- **Android (Chrome):** open the link → ⋮ menu → *Install app* / *Add to Home screen*.

Open it once while online; after that it works with no signal.

## Your data
- Logs are saved on the phone only. Deleting the app deletes the log.
- Use *Muat turun sandaran (.json)* now and then; *Import sandaran* restores it
  (also works to move logs from the Claude version of the app).

## Updating the app later
After uploading changed files, open `sw.js` and bump `VERSION` (e.g. `thg-v2`),
so phones pick up the new version.
