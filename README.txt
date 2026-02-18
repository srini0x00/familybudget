# FamilyBudget PWA — Now with Backup & Restore!

## NEW FEATURES
✅ Full backup/restore - Transfer ALL data between phones instantly
✅ CSV export per month - Keep monthly records

## Quick Deploy — GitHub Pages (Recommended)

1. Create account at github.com
2. New repository → name: "familybudget" → Public → Create
3. Upload all 4 files from this folder
4. Settings → Pages → Source: "main" branch → Save
5. Your URL: https://YOUR-USERNAME.github.io/familybudget
6. iPhone: Open in Safari → Share → Add to Home Screen ✓

## How to Use Backup & Restore

### Creating a Backup (Old Phone)
1. Open app → History tab
2. Tap "💾 Backup" button
3. Downloads: FamilyBudget_Backup_2025-02-18.json
4. Save to iCloud Drive or email yourself

### Restoring on New Phone
1. Install app on new phone (same GitHub URL)
2. Open app → History tab
3. Tap "📥 Restore" button
4. Select your .json backup file
5. Confirm → ALL data restored instantly!

### Monthly CSV Backups (Already Built-In)
1. History tab → Select month
2. Tap "⬇ CSV" button
3. Downloads monthly data as spreadsheet
4. Use this for Excel updates or record-keeping

## Files in This Folder
- index.html   — The app (now with backup/restore!)
- sw.js        — Service worker (offline mode)
- manifest.json — PWA settings
- icon.svg     — App icon

## Updating Your GitHub-Hosted App
1. Go to: github.com/YOUR-USERNAME/familybudget
2. Click "index.html" → pencil icon (Edit)
3. Copy content from the NEW index.html in this folder
4. Paste to replace everything
5. Commit changes → App updates automatically!

## Alternative Hosting Options

### Netlify Drop (2 minutes, no account)
1. Go to: app.netlify.com/drop
2. Drag entire FamilyBudget folder
3. Get instant URL → Open in Safari → Add to Home Screen

### Google Drive (1 minute, but limited)
1. Upload index.html to Drive
2. Share → Anyone with link → Copy link
3. Open in Safari → May need to click "Download" first
Note: No offline mode with this method
