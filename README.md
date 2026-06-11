[README.md](https://github.com/user-attachments/files/28822333/README.md)
# My Money — Personal Mobile App

A minimalist personal money tracker that installs to your phone like a native app.

## Deploy to GitHub Pages (free, 5 minutes)

### Step 1 — Create a GitHub account
Go to https://github.com and sign up if you don't have an account.

### Step 2 — Create a new repository
1. Click the **+** icon → **New repository**
2. Name it: `mymoney` (or anything you like)
3. Set it to **Public**
4. Click **Create repository**

### Step 3 — Upload the files
1. On your new repo page, click **uploading an existing file**
2. Drag and drop ALL files from this folder:
   - `index.html`
   - `manifest.json`
   - `sw.js`
3. Click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Go to your repo **Settings** → **Pages** (left sidebar)
2. Under **Source**, select **Deploy from a branch**
3. Choose branch: **main**, folder: **/ (root)**
4. Click **Save**
5. Wait ~60 seconds, then your app is live at:
   `https://YOUR_USERNAME.github.io/mymoney/`

### Step 5 — Install on your phone

**On Android (Chrome):**
1. Open the URL in Chrome
2. Tap the ⋮ menu → **Add to Home screen**
3. Tap **Add** — done!

**On iPhone (Safari):**
1. Open the URL in Safari (must be Safari)
2. Tap the Share button (box with arrow)
3. Scroll down → **Add to Home Screen**
4. Tap **Add** — done!

The app now appears on your home screen and opens full-screen, no browser bar.

---

## Adding app icons (optional)

The app works without icons, but if you want a custom icon:
1. Create a 512×512 PNG image
2. Save copies as `icon-192.png` (192×192) and `icon-512.png` (512×512)
3. Upload them to your GitHub repo

---

## Notes
- All data is stored locally on your device (localStorage)
- Works offline after first load
- Currency is set to BDT (৳) — edit `index.html` and replace `৳` with your symbol if needed
