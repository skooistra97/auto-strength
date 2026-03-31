# Auto Strength — Deploy to GitHub Pages

## Step 1: Create a GitHub repo

1. Go to [github.com/new](https://github.com/new)
2. Name it `auto-strength` (or whatever you want)
3. Set it to **Public**
4. Click **Create repository**

## Step 2: Upload the files

On the repo page you just created:

1. Click **"uploading an existing file"** (the link in the quick setup section)
2. Drag in ALL 4 files from the folder you downloaded:
   - `index.html`
   - `manifest.json`
   - `icon-192.png`
   - `icon-512.png`
3. Click **Commit changes**

## Step 3: Enable GitHub Pages

1. Go to your repo's **Settings** tab
2. Click **Pages** in the left sidebar
3. Under "Source", select **Deploy from a branch**
4. Branch: select **main**, folder: **/ (root)**
5. Click **Save**

Wait about 1 minute. Your app will be live at:
```
https://YOUR-USERNAME.github.io/auto-strength/
```

## Step 4: Add to iPhone Home Screen

1. Open the URL above in **Safari** on your iPhone
2. Tap the **Share** button (square with arrow pointing up)
3. Scroll down and tap **Add to Home Screen**
4. Tap **Add**

The app will now launch full-screen with no browser bar, just like a native app.
Your lifts and 1RM data are saved in your phone's browser storage.

## Updating the app later

To make changes, just edit `index.html` directly on GitHub (click the file,
then the pencil icon to edit) and commit. GitHub Pages will redeploy in
about a minute. Hard-refresh on your phone (close the app fully, reopen)
to pick up changes.
