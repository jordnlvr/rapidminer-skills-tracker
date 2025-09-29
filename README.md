# RapidMiner Skills Tracker

Professional skills coverage matrix for the RapidMiner Tech Team.

## 🚀 Quick Setup

### Step 1: Add Files to GitHub
1. Go to your repo: https://github.com/jordnlvr/rapidminer-skills-tracker
2. Click **Add file** → **Create new file**
3. Name it `index.html` and paste the content from the `index.html` artifact
4. Click **Commit changes**
5. Repeat for `team-data.json` (paste content from the JSON artifact)

### Step 2: View Your Site
- Your tracker will be live at: `https://jordnlvr.github.io/rapidminer-skills-tracker`
- Give it 1-2 minutes after first commit to go live

### Step 3: Embed in Notion
1. In Notion, type `/embed`
2. Paste your GitHub Pages URL
3. Resize the embed to fit your page
4. Done!

---

## 📝 How to Update Data

### Option 1: Edit on GitHub (Easy)
1. Go to your repo
2. Click on `team-data.json`
3. Click the pencil icon (Edit)
4. Make changes (see examples below)
5. Click **Commit changes**
6. Refresh your tracker page - changes appear instantly!

### Option 2: Tell Claude
Just say: "Update Faisal's AI Studio score to 4" and I'll give you the updated JSON to paste.

---

## 📊 Example Data Updates

### Update a skill level:
```json
{
  "name": "Faisal",
  "skills": {
    "aiStudio": 4  ← Change this number (0-5)
  }
}
```

### Add a new team member:
```json
{
  "name": "New Person",
  "role": "Data Scientist",
  "skills": {
    "dataScience": 4,
    "analytics": 3
  },
  "industries": {
    "primary": "Healthcare",
    "secondary": "Finance"
  }
}
```

### Add a new skill:
1. Add to `skillDefinitions`:
```json
{
  "key": "newSkill",
  "label": "New Skill Name",
  "category": "product"  ← or "technical"
}
```
2. Add to team members who have it:
```json
{
  "name": "Faisal",
  "skills": {
    "newSkill": 3
  }
}
```

---

## ✨ Features

- **Interactive Dashboard** - Visual coverage analysis
- **Gap Analysis** - Automatically identifies critical skill gaps
- **Excel Export** - Download professional reports with one click
- **Color-Coded Matrix** - Easy-to-read skill levels
- **Responsive Design** - Works on any device
- **Live Updates** - Just edit the JSON file and refresh

---

## 🎯 Skill Level Guide

- **0** = No Experience (Red)
- **1** = Beginner (Orange)
- **2** = Advanced Beginner (Yellow)
- **3** = Competent (Blue)
- **4** = Proficient (Green)
- **5** = Expert (Dark Green)

---

## 💾 For Your Boss: Spreadsheet Version

The **Export to Excel** button creates a professional multi-sheet workbook with:
- Executive Dashboard
- Full Skills Matrix
- Coverage Analysis
- Skill Definitions

Just click the button and download!

---

## 🔧 Troubleshooting

**Tracker not loading?**
- Make sure both `index.html` and `team-data.json` are in the root of your repo
- Check that GitHub Pages is enabled (Settings → Pages)
- Wait 1-2 minutes after first commit

**Export button not working?**
- Make sure you're viewing the live GitHub Pages URL (not github.com/...)
- Try a different browser if issues persist

**Need help updating data?**
- Just ask Claude: "Update [person]'s [skill] to [level]"
- Or edit the JSON file directly on GitHub

---

## 📧 Questions?

Just ask Claude for help! I can:
- Update any data
- Add new skills or people
- Fix any issues
- Generate the updated JSON for you to paste

---

Built with ❤️ for Will Ma's Tech Team