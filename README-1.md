# 🌐 Rashiq V M – Portfolio Website

A modern, fully responsive portfolio website with a hidden Admin Dashboard powered by GitHub API.

---

## 📁 File Structure

```
rashiq-portfolio/
├── index.html          ← Main portfolio website
├── admin.html          ← Admin dashboard (hidden, URL access only)
├── data/
│   ├── profile.json    ← Name, bio, stats
│   ├── skills.json     ← Skill categories
│   ├── experience.json ← Work history
│   ├── projects.json   ← Portfolio projects
│   ├── education.json  ← Education, certifications, languages
│   └── contact.json    ← Contact details
└── assets/
    └── images/         ← Uploaded project images
```

---

## 🚀 Deployment to GitHub Pages

### Step 1 – Create GitHub Repository
1. Go to [github.com](https://github.com) → New repository
2. Name it: `rashiq-portfolio` (or your preferred name)
3. Set to **Public**
4. Click **Create repository**

### Step 2 – Upload Files
Upload ALL files maintaining folder structure, OR use Git:
```bash
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/rashiq-portfolio.git
git push -u origin main
```

### Step 3 – Enable GitHub Pages
1. Repository → **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: **main** → **/ (root)**
4. Save → Your site: `https://YOUR_USERNAME.github.io/rashiq-portfolio`

### Step 4 – Get GitHub Personal Access Token
1. GitHub → Your photo → **Settings**
2. Left sidebar → **Developer settings**
3. **Personal access tokens** → **Tokens (classic)**
4. **Generate new token (classic)**
5. Check scope: ✅ **repo** (full control)
6. Generate → **Copy the token** (shown once!)

### Step 5 – Configure Admin Dashboard
1. Open `https://YOUR_USERNAME.github.io/rashiq-portfolio/admin.html`
2. Login with password: **admin123** (change this!)
3. Go to **GitHub Config** in sidebar
4. Enter: Token, Username, Repo name, Branch (main)
5. Click **Save Config** → **Test Connection**
6. ✅ You're connected!

---

## 🔐 Admin Panel Usage

- **URL**: `/admin.html` (not linked from main site)
- **Default password**: `admin123`
- **Change password**: Settings page

### How edits work:
1. Navigate to any section in the sidebar
2. Edit the fields
3. Click **Save & Push**
4. GitHub API commits the JSON file directly
5. GitHub Pages rebuilds (takes ~30–60 seconds)
6. Visit your live site — changes appear!

---

## 🖼 Image Upload
- Go to **Projects** page in admin
- Drag & drop or click to upload on any project card
- Image is queued, then pushed to `/assets/images/` on Save & Push

---

## ⚙️ Customization

All content is in `/data/*.json` files.
Edit via admin dashboard OR directly in GitHub.

---

## 🌐 Tech Stack
- HTML5 + CSS3 + Vanilla JavaScript
- GitHub API (v3 REST)
- GitHub Pages (free hosting)
- Google Fonts (Syne + DM Sans)
- Zero dependencies, zero backend

---

*Built for Rashiq V M – IT Technician & Network Specialist*
