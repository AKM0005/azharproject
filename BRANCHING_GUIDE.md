# 🌿 EarthwormX - Development Branch Guide

## 🎯 Overview

Your website now has **TWO separate versions**:

### 🟢 Main Website (Production)
```
gs/
├── index.html     ← Live/Production version
└── about.html     ← Live/Production version
```
**Purpose**: Your actual website that goes live  
**Safety**: Protected from experimental changes  

### 🔵 Development Branch (Testing)
```
gs/dev-branch/
├── index.html     ← Test version (has [DEV] in title)
└── about.html     ← Test version (has [DEV] in title)
```
**Purpose**: Safe space to experiment and test  
**Safety**: Changes here don't affect main website  

---

## 🚀 How It Works

### Visual Workflow

```
┌─────────────────────┐
│   Main Website      │  ← Your real website
│   (Production)      │     Always safe!
└─────────────────────┘
         │
         │ Copy to create dev →
         ↓
┌─────────────────────┐
│  Dev Branch         │  ← Make changes here
│  (Testing)          │     Experiment freely!
└─────────────────────┘
         │
         │ If happy with changes →
         ↓
┌─────────────────────┐
│   Main Website      │  ← Copy changes back
│   (Updated)         │     when satisfied
└─────────────────────┘
```

---

## 📋 Step-by-Step Usage

### Step 1: Open the Dev Version to Test
```
🖱️ Right-click: dev-branch/index.html
   → Open with → Your Browser

You'll see [DEV] in the browser tab title
```

### Step 2: Make Your Changes
Tell me what you want to try:
- "Change the hero section background in dev"
- "Add a new section to dev-branch"
- "Try different colors in dev"
- "Test a new layout in dev-branch"

**I'll only edit the dev-branch files!**

### Step 3: Test Everything
- Open `dev-branch/index.html` in browser
- Click all links
- Test on phone/tablet
- Check if you like the changes

### Step 4A: Like the Changes? → Promote to Main
Tell me:
- ✅ "Apply dev changes to main"
- ✅ "Copy dev to production"
- ✅ "Promote dev-branch to main"

### Step 4B: Don't Like the Changes? → Keep Main As-Is
- Just ignore the dev-branch
- Try different changes
- Or reset and start fresh

---

## 💡 Example Scenarios

### Scenario 1: Testing New Colors
```
You: "In dev-branch, change primary color to darker green"
Me: ✏️ Edits dev-branch/index.html only

You: *Opens dev-branch/index.html in browser*
You: "I like it! Apply to main"
Me: ✅ Copies changes to main website

Result: Main website now has new colors
```

### Scenario 2: Don't Like Changes
```
You: "In dev, make the text much larger"
Me: ✏️ Edits dev-branch files

You: *Opens dev-branch/index.html*
You: "Too big, I don't like it"
Me: 🚫 Leaves main website untouched

Result: Main website stays exactly as it was
```

### Scenario 3: Multiple Experiments
```
You: "In dev, try layout A"
Me: ✏️ Edits dev-branch

You: "Not great. Reset dev and try layout B"
Me: 🔄 Resets dev, then edits for layout B

You: "Much better! Copy to main"
Me: ✅ Copies layout B to main

Result: You tested safely, main gets best version
```

---

## 🎨 Common Use Cases

### 1. Color Scheme Testing
```
"In dev-branch, try a blue-green color scheme"
→ Test in browser
→ If good: "Apply to main"
→ If bad: "Try another color scheme in dev"
```

### 2. Layout Changes
```
"In dev, move the contact form above testimonials"
→ Test the flow
→ If good: "Copy dev to main"
→ If bad: Main website unchanged
```

### 3. Content Experiments
```
"In dev, add a new 'Our Team' section"
→ Review the section
→ Get feedback from others
→ When ready: "Promote to main"
```

### 4. A/B Testing Ideas
```
"In dev, try version A of hero text"
→ Take screenshot
→ "Reset dev and try version B"
→ Take screenshot
→ Compare both
→ "Apply [chosen version] to main"
```

---

## 🛠️ Useful Commands

### When Talking to Me:

| What You Want | What to Say |
|---------------|-------------|
| Make a change in dev | "In dev-branch, change [X]" |
| Test multiple ideas | "Try [A] in dev, if I don't like it try [B]" |
| Promote to main | "Apply dev changes to main website" |
| Start fresh | "Reset dev-branch to match main" |
| Compare versions | "Show differences between main and dev" |
| See both versions | "Open both main and dev in browser" |

### Manual Terminal Commands:

**View current folder structure:**
```bash
cd /Users/akhil/Documents/cursor-projects/gs
ls -la
ls -la dev-branch/
```

**Apply dev to main (when satisfied):**
```bash
cp dev-branch/index.html index.html
cp dev-branch/about.html about.html
```

**Reset dev (start over):**
```bash
cp index.html dev-branch/index.html
cp about.html dev-branch/about.html
```

**See what changed:**
```bash
diff index.html dev-branch/index.html
```

---

## ⚠️ Important Reminders

### ✅ DO:
- Make all experimental changes in `dev-branch/`
- Test thoroughly before promoting to main
- Try multiple ideas safely
- Keep main website unchanged until satisfied
- Ask me to edit dev-branch files

### ❌ DON'T:
- Edit main files for experiments (use dev-branch!)
- Forget which version you're viewing in browser
- Promote untested changes to main
- Delete dev-branch folder (keep it for future experiments)

---

## 🔍 How to Tell Which Version You're Viewing

### Browser Tab Title:
- **Main**: `EARTHWORMX - Restoring Earth...`
- **Dev**: `[DEV] EARTHWORMX - Restoring Earth...`

### File Path in Browser:
- **Main**: `.../gs/index.html`
- **Dev**: `.../gs/dev-branch/index.html`

---

## 🎓 Pro Tips

1. **Always specify "dev" or "dev-branch"** when asking for changes
2. **Take screenshots** of dev changes you like
3. **Test on multiple devices** before promoting
4. **Get feedback** from others using dev version
5. **Keep a backup** of main before big changes
6. **Use dev for learning** new techniques risk-free

---

## 📞 Quick Reference

| Goal | Action |
|------|--------|
| Experiment safely | Edit `dev-branch/` files |
| View test version | Open `dev-branch/index.html` |
| Like the changes | Tell me: "Apply dev to main" |
| Don't like changes | Main stays safe, try again in dev |
| Start over | Tell me: "Reset dev-branch" |
| Compare versions | Open both in separate browser tabs |

---

## ✨ Benefits of This Setup

✅ **Safe Experimentation**: Try anything without risk  
✅ **Easy Rollback**: Main website stays protected  
✅ **Compare Versions**: See old vs new side-by-side  
✅ **Client Preview**: Show dev version for approval  
✅ **Learning Friendly**: Break things and learn  
✅ **Professional Workflow**: Like having staging environment  

---

## 🎉 You're All Set!

**Current Setup:**
- ✅ Main website ready (with greenish color scheme)
- ✅ Dev branch created (identical copy for testing)
- ✅ Dev files marked with [DEV] in title
- ✅ Both versions independent

**Next Steps:**
1. Want to try something? → "In dev-branch, try [X]"
2. Like the result? → "Apply dev to main"
3. Don't like it? → Try something else in dev

**Your main website is safe and will only change when you explicitly approve it!** 🛡️

---

*Happy experimenting! 🌱*

