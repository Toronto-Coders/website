# The Toronto Coders Website

A modern, minimalist website for The Toronto Coders organization built with HTML, CSS, and vanilla JavaScript.

## 🚀 Quick Start

### Prerequisites
- A GitHub account
- A Vercel account (free tier works great!)

## 📦 Deploying to GitHub & Vercel

### Step 1: Push to GitHub

1. **Create a new repository on GitHub:**
   - Go to https://github.com/new
   - Name it something like `toronto-coders-website`
   - Make it Public (so Vercel can access it for free)
   - Don't initialize with README (we already have files)
   - Click "Create repository"

2. **Push your code to GitHub:**
   
   Open your terminal/command prompt in the folder with these files and run:
   
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Toronto Coders website"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/toronto-coders-website.git
   git push -u origin main
   ```
   
   Replace `YOUR-USERNAME` with your actual GitHub username.

### Step 2: Deploy to Vercel

**Option A: Using Vercel Dashboard (Easiest)**

1. Go to https://vercel.com and sign up/login (use GitHub for easy integration)
2. Click "Add New..." → "Project"
3. Import your GitHub repository (`toronto-coders-website`)
4. Vercel will auto-detect it as a static site
5. Click "Deploy"
6. Done! Your site is live at `https://your-project-name.vercel.app`

**Option B: Using Vercel CLI**

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel

# Follow the prompts - accept all defaults
```

### Step 3: Custom Domain (Optional)

1. In Vercel dashboard, go to your project
2. Click "Settings" → "Domains"
3. Add your custom domain
4. Follow DNS configuration instructions

## 📁 File Structure

```
toronto-coders-website/
├── index.html         # Home page
├── projects.html      # Projects showcase
├── team.html          # Team member profiles
├── contribute.html    # Contribution guidelines
└── README.md          # This file
```

## ✨ Features

- **Responsive Design** - Works on all devices
- **Animated Logo** - Changes on scroll
- **GitHub API Integration** - Automatically fetches project and commit stats
- **Smooth Animations** - Modern, professional feel
- **Zero Dependencies** - Pure HTML/CSS/JS

## 🔧 Customization

### Updating Content

All content is in the HTML files. Just edit them directly:

- **Hero Section**: Edit `index.html` line 488-490
- **Team Members**: Edit `index.html` lines 522-534
- **Projects**: Edit `projects.html` to add new projects
- **Contribution Info**: Edit `contribute.html`

### Changing Colors

Colors are defined as CSS variables in each HTML file:

```css
:root {
    --black: #000000;
    --white: #ffffff;
    --grey-dark: #1a1a1a;
    --grey-mid: #404040;
    --grey-light: #808080;
}
```

## 🔄 Updating Your Live Site

After making changes:

```bash
git add .
git commit -m "Description of changes"
git push
```

Vercel will automatically rebuild and deploy! ⚡

## 📊 GitHub Stats Integration

The homepage automatically fetches stats from your GitHub organization:
- Number of projects (repositories)
- Total commits across all repos
- Updates every time someone visits the page

Make sure your GitHub organization is `Toronto-Coders` or update line 589 in `index.html`.

## 🛠️ Tech Stack

- HTML5
- CSS3 (with CSS Grid & Flexbox)
- Vanilla JavaScript
- GitHub API
- Google Fonts (Syne & Space Mono)

## 📝 License

Feel free to use and modify for your own projects!

## 🤝 Contributing

Have suggestions? Feel free to open issues or submit pull requests!

---

Made with ❤️ by The Toronto Coders
