# 12v PitStop Website

## How to go live on 12vpitstop.in

### Step 1 — Create GitHub repository
1. Go to github.com → New repository
2. Name it: `12vpitstop`
3. Set to Public → Create

### Step 2 — Upload all files
1. Click "uploading an existing file"
2. Drag all files from this folder including hidden files (.nojekyll, CNAME, .github folder)
3. Commit message: "Launch website"

### Step 3 — Enable GitHub Pages
1. Repository → Settings → Pages
2. Source: GitHub Actions
3. Auto-deploys on every push

### Step 4 — Connect 12vpitstop.in
Add these DNS records at your domain registrar:

| Type  | Name | Value                |
|-------|------|----------------------|
| A     | @    | 185.199.108.153      |
| A     | @    | 185.199.109.153      |
| A     | @    | 185.199.110.153      |
| A     | @    | 185.199.111.153      |
| CNAME | www  | yourusername.github.io |

### Step 5 — Enable HTTPS
Settings → Pages → Enforce HTTPS ✓