# 🌸 DailySpend — Daily Expenses Tracker

A warm, colorful **Progressive Web App (PWA)** for tracking daily expenses with budget alerts.

## ✨ Features
- 🎨 Warm, colorful design with coral/peach/amber palette
- 💰 Set monthly budget with custom currency (RM, USD, SGD, etc.)
- ⚠️ Budget warning notification at custom threshold (default 80%)
- 📊 Category breakdown charts + daily spending bar chart
- 📋 Full expense history with month navigation
- 📱 **Installable as an app** on iPhone, Android, and desktop — FREE!
- 💾 All data stored locally on your device (100% private, no servers)

## 🚀 Deploy for FREE (Choose One)

### Option 1: Netlify (Easiest, Recommended)
1. Go to [netlify.com](https://netlify.com) and sign up free
2. Drag & drop the entire `expenses-tracker` folder onto the Netlify dashboard
3. Your app is live instantly! Share the link with anyone.

### Option 2: Vercel
1. Install: `npm i -g vercel`
2. Run `vercel` inside this folder
3. Done! Free hosting with HTTPS.

### Option 3: GitHub Pages
1. Create a GitHub repo, upload all files
2. Go to Settings → Pages → Deploy from main branch
3. Free hosting at `yourusername.github.io/repo-name`

## 📱 How Users Install It (No App Store Needed!)
### On iPhone (Safari):
1. Open the app link in Safari
2. Tap the **Share** button (box with arrow)
3. Tap **"Add to Home Screen"**
4. Tap **Add** — done! It appears like a real app icon!

### On Android (Chrome):
1. Open the app link in Chrome
2. Tap the **⋮** menu → **"Add to Home screen"**
3. Or Chrome shows an automatic "Install app" banner

### On Desktop (Chrome/Edge):
1. Visit the link
2. Click the **install icon** in the address bar (➕)
3. Click Install

## 💡 Budget Warning Notifications
- The app asks for notification permission when you save your budget
- When spending reaches your warning threshold (default 80%), you get a notification
- Works even when the app is in the background (after installation)

## 🔒 Privacy
- All data stored in your browser's localStorage
- Nothing sent to any server
- Works offline after first visit

## 📁 Files
- `index.html` — Main app
- `manifest.json` — PWA installability config
- `sw.js` — Service worker (offline support + push notifications)
- `icon-192.png` / `icon-512.png` — App icons
