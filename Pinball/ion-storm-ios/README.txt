ION STORM PINBALL - iPhone app (Home Screen web app)   version 5

UPDATING THE APP YOU ALREADY INSTALLED
   a. Open your ion-storm repository on github.com.
   b. Click "Add file" > "Upload files". Unzip ion-storm-ios.zip, open the folder,
      and drag in index.html, sw.js and README.txt. Click Commit changes.
      (The icons and fonts folders did not change. Uploading them again is harmless.)
   c. Wait 1-2 minutes for GitHub Pages to update.
   d. On the iPhone, open Ion Storm from the Home Screen once while online.
      The new version loads right away and is saved for offline play.
      If you still see the old table, close the app and open it again.

FIRST-TIME SETUP (if you have not installed it yet)
1. PUT IT ONLINE (free, from a Windows PC)
   a. Sign in at github.com (free account is enough).
   b. Click "+" (top right) > New repository. Name it ion-storm, set it to Public, click Create repository.
   c. On the new repo page click "uploading an existing file".
   d. Unzip ion-storm-ios.zip, open the folder, select EVERYTHING inside it
      (index.html, manifest.webmanifest, sw.js, README.txt and the icons and fonts folders)
      and drag it onto the upload page. Click Commit changes.
      Check that index.html sits at the top level of the repo, not inside another folder.
   e. Go to Settings > Pages. Under "Build and deployment", Source: Deploy from a branch,
      Branch: main, folder: / (root). Click Save.
   f. Wait 1-2 minutes and refresh the Pages settings. Your link appears at the top:
      https://YOUR-USERNAME.github.io/ion-storm/
2. INSTALL ON IPHONE
   a. Open the link in Safari (it must be Safari).
   b. Tap the Share button, then "Add to Home Screen".
      If you see an "Open as Web App" switch, leave it on.
   c. Tap Add. The Ion Storm icon appears on your Home Screen.
   d. Open it from the icon once while online. After that it also works offline.

NOTES
- Sound: if you hear nothing, turn off Silent mode.
- Your best score is saved on the phone, inside the app.
- For future updates: upload the changed files, and in sw.js raise VERSION
  (currently 'ion-storm-v5') to the next number so phones refresh their offline copy.
