# 🔧 Development Branch - EarthwormX

This is your **experimental/testing branch** where you can make changes without affecting the main website.

## 📁 Folder Structure

```
gs/
├── index.html              ← MAIN/PRODUCTION website
├── about.html              ← MAIN/PRODUCTION website
├── README.md
├── SETUP_GUIDE.txt
└── dev-branch/             ← THIS FOLDER (for testing)
    ├── index.html          ← TEST version
    ├── about.html          ← TEST version
    └── README-DEV.md       ← This file
```

## 🎯 How to Use This Branch

### 1. Make Changes Here
- Edit files in the `dev-branch/` folder
- Try new colors, layouts, content, etc.
- Test everything thoroughly

### 2. Test Your Changes
- Open `dev-branch/index.html` in your browser
- Check all features work
- Test on mobile and desktop

### 3. When Happy with Changes
**Option A: Manual Copy**
```bash
# From the gs/ folder:
cp dev-branch/index.html index.html
cp dev-branch/about.html about.html
```

**Option B: Tell me what worked**
- Just tell me "apply dev changes to main" and I'll copy them over

### 4. If You Don't Like the Changes
- Simply delete or ignore the dev-branch folder
- Your main website stays untouched!

## 🔄 Workflow Examples

### Example 1: Testing New Colors
```
1. Edit dev-branch/index.html (change color palette)
2. Open dev-branch/index.html in browser
3. Like it? → Copy to main
4. Don't like it? → Revert or try again
```

### Example 2: Trying Different Content
```
1. Edit dev-branch/about.html (new services section)
2. Test it thoroughly
3. Show it to others for feedback
4. Satisfied? → Copy to main
```

## 🚀 Quick Commands

### Create a Fresh Dev Branch
```bash
cd /Users/akhil/Documents/cursor-projects/gs
cp index.html dev-branch/index.html
cp about.html dev-branch/about.html
```

### Apply Dev Changes to Main (when ready)
```bash
cd /Users/akhil/Documents/cursor-projects/gs
cp dev-branch/index.html index.html
cp dev-branch/about.html about.html
```

### Reset Dev Branch (start over with current main)
```bash
cd /Users/akhil/Documents/cursor-projects/gs
rm -rf dev-branch/*
cp index.html dev-branch/index.html
cp about.html dev-branch/about.html
```

### Compare Main vs Dev
```bash
# See what changed
diff index.html dev-branch/index.html
diff about.html dev-branch/about.html
```

## ⚠️ Important Notes

1. **Main website is safe**: Changes in `dev-branch/` don't affect main files
2. **Test thoroughly**: Always test dev changes before copying to main
3. **Keep backups**: If you like current main, maybe save a backup before overwriting
4. **Links between pages**: Make sure `about.html` links still work (they link to `index.html`)

## 🎨 Use Cases for Dev Branch

- **Trying new color schemes**
- **Testing layout changes**
- **Experimenting with new sections**
- **Adding/removing features**
- **Testing on different devices**
- **Getting feedback before going live**
- **Learning without breaking production**

## 💡 Pro Tips

1. **Always open dev files from the dev-branch folder**
2. **Use descriptive comments** when making experimental changes
3. **Test everything** before promoting to main
4. **Take screenshots** of what you like
5. **Don't forget** to update both index and about if needed

## 🆘 Need Help?

**To make changes in dev:**
- "Edit dev-branch/index.html to change [X]"

**To promote changes to main:**
- "Copy dev-branch changes to main website"

**To reset and start over:**
- "Reset dev-branch to match main website"

**To compare:**
- "Show me differences between main and dev"

---

**Current Status**: Dev branch created with copies of main website (with greenish color scheme)

**Last Updated**: October 19, 2025

**Safe to experiment**: ✅ Yes! Your main website is protected.

