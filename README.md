# Money Buddy - Personal Finance Tracker PWA

A cheerful personal finance tracking app that works as a Progressive Web App (PWA) with offline support and persistent data storage.

## 📱 Features
- Track income, investments, expenses, work hours, and todos
- Beautiful candy/bubble aesthetic with dark mode
- Data persists in localStorage (survives browser restarts)
- Works offline once installed
- Add to home screen for app-like experience

---

## 🚀 Setup Instructions (GitHub Pages)

### Step 1: Create a GitHub Account (if you don't have one)
1. Go to [github.com](https://github.com)
2. Click "Sign up" and create a free account

### Step 2: Create a New Repository
1. Once logged in, click the **+** icon in the top right → **New repository**
2. Name it: `money-buddy` (or any name you like)
3. Make sure **Public** is selected (required for free GitHub Pages)
4. Check ✅ **Add a README file**
5. Click **Create repository**

### Step 3: Upload the App Files
1. In your new repository, click **Add file** → **Upload files**
2. Drag and drop ALL these files:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.svg`
   - `icon-512.svg`
3. Scroll down and click **Commit changes**

### Step 4: Enable GitHub Pages
1. Go to your repository's **Settings** (tab at the top)
2. In the left sidebar, click **Pages**
3. Under "Source", select **Deploy from a branch**
4. Under "Branch", select **main** and **/ (root)**
5. Click **Save**
6. Wait 1-2 minutes for deployment

### Step 5: Get Your App URL
1. After a minute, refresh the Settings → Pages page
2. You'll see: "Your site is live at `https://YOUR-USERNAME.github.io/money-buddy/`"
3. Click that link to open your app!

### Step 6: Add to Home Screen (iOS)
1. Open the URL in Safari on your iPhone/iPad
2. Tap the **Share** button (square with arrow)
3. Scroll down and tap **Add to Home Screen**
4. Name it "Money Buddy" and tap **Add**
5. Now use the app from your home screen!

---

## 📦 Files Included

| File | Purpose |
|------|---------|
| `index.html` | The main app (all code is here) |
| `manifest.json` | PWA configuration (name, icons, colors) |
| `sw.js` | Service Worker for offline caching |
| `icon-192.svg` | App icon (192x192) |
| `icon-512.svg` | App icon (512x512) |

---

## 💾 Data Storage

Your financial data is stored in your browser's **localStorage**. This means:
- ✅ Data persists between sessions
- ✅ Data survives browser restarts
- ✅ Works offline
- ⚠️ Data is specific to this device/browser
- ⚠️ Clearing browser data will erase your data

**Tip:** Use the Backup feature (⬇️ icon) to export your data regularly!

---

## 🔧 Troubleshooting

**App not updating?**
- Clear your browser cache, or
- In Safari: Settings → Safari → Clear History and Website Data

**Data disappeared?**
- Did you clear browser data?
- Are you using Private/Incognito mode? (data won't persist)
- Restore from a backup if you have one

**Icons not showing on home screen?**
- This is sometimes an iOS quirk
- The app will still work fine

---

## 📄 License

Free to use for personal purposes.
