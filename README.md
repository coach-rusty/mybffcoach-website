# MyBFF Coach — Website

Static website for MyBFF Coach, a human-centered AI platform built for continuity, trust, and long-term care.

## Project Structure

```
mybffcoach-website/
├── index.html          # Homepage
├── platform.html       # The MyBFF Coach Vision
├── how-it-works.html   # How MyBFF Coach Works
├── why-different.html  # Why We're Different
├── coach-jeff.html     # Coach Jeff: A Closer Look
├── ethics.html         # Ethics, Trust & Responsibility
├── road-ahead.html     # The Road Ahead
├── styles.css          # Global stylesheet
├── README.md           # This file
└── assets/
    ├── logo-mybffcoach.png
    ├── founder-rusty.png
    ├── icons/
    │   ├── mybff-icon-01.png
    │   ├── mybff-icon-02.png
    │   ├── mybff-icon-03.png
    │   └── coach-jeff.png
    └── backgrounds/
        ├── bg-continuity-01.webp
        └── bg-continuity-02.webp
```

## View Locally

Open `index.html` directly in any modern browser:

```bash
open index.html
```

Or use a local server:

```bash
# Python 3
python3 -m http.server 8000

# Then visit http://localhost:8000
```

## Push to GitHub

```bash
cd mybffcoach-website
git init
git add .
git commit -m "Initial commit: MyBFF Coach website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/mybffcoach-website.git
git push -u origin main
```

## Deploy on Vercel

1. Push the repository to GitHub (see above).
2. Go to [vercel.com](https://vercel.com) and sign in with GitHub.
3. Click **"Add New Project"** and import the `mybffcoach-website` repository.
4. Configure:
   - **Framework Preset:** Other
   - **Build Command:** *(leave empty — no build step needed)*
   - **Output Directory:** `.` *(root of the project)*
5. Click **Deploy**.

The site will be live at your Vercel domain within seconds. Vercel will automatically redeploy on every push to `main`.

## Tech Stack

- Static HTML + CSS
- Vanilla JavaScript (mobile navigation only)
- No frameworks or build tools
- Inter font via Google Fonts
- Optimized for GitHub Pages and Vercel static hosting
