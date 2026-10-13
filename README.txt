RUPEE LEDGER - upload these files to GitHub (all in the main folder, not inside a sub-folder)

  index.html   icon-192.png   icon-512.png   icon-maskable-512.png
  manifest.webmanifest   sw.js   .nojekyll

Steps (full guide was given in chat):
 1. github.com -> sign up / sign in -> "+" -> New repository
    Name: money-tracker   Visibility: Public   -> Create repository
 2. Click "uploading an existing file", drag in ALL files from this folder
    (if .nojekyll is hidden on your device, you can skip it), then "Commit changes".
 3. Settings -> Pages -> Source: "Deploy from a branch" -> Branch: main, folder: / (root) -> Save.
 4. After 1-2 minutes open  https://YOUR-USERNAME.github.io/money-tracker/
 5. In Chrome on your phone: menu (three dots) -> "Install app" (or "Add to Home screen").

To update later: upload the new index.html (replace) and change VERSION in sw.js
(for example rupee-ledger-v1 -> rupee-ledger-v2) so phones pick up the new version.
