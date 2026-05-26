# My Projects Homepage

A simple, clean portfolio page to showcase your projects.

## Getting Started

### Customize Your Projects

Edit `index.html` and replace the example project cards with your own:
- Update the `href="#"` to link to your project repositories
- Change the project titles and descriptions
- Modify the technology tags

### Local Preview

Open `index.html` in your browser to preview locally.

## Deploy to GitHub Pages

### 1. Create a GitHub Repository

1. Go to [github.com/new](https://github.com/new)
2. Create a new repository named `username.github.io` (replace `username` with your GitHub username)
   - This makes it deploy automatically to `https://username.github.io`
   - Alternatively, name it anything and enable Pages in settings
3. Do NOT initialize with README/gitignore yet

### 2. Push Your Code

In PowerShell, run these commands in this directory:

```powershell
# Initialize git if not already done
git init

# Add remote (replace YOUR_USERNAME and REPO_NAME)
git remote add origin https://github.com/YOUR_USERNAME/REPO_NAME.git

# Add all files
git add .

# Create initial commit
git commit -m "Initial commit: portfolio homepage"

# Push to GitHub (it will prompt for credentials)
git branch -M main
git push -u origin main
```

### 3. Enable GitHub Pages (if not auto-enabled)

1. Go to your repository on GitHub
2. Click **Settings** → **Pages**
3. Under "Build and deployment", select:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
4. Click **Save**

Your site will be live in a few moments at:
- `https://YOUR_USERNAME.github.io` (if using username.github.io repo)
- `https://YOUR_USERNAME.github.io/REPO_NAME` (if using a different repo name)

## Structure

```
.
├── index.html      # Main page
├── style.css       # Styling
└── README.md       # This file
```

## Tips

- Keep the HTML and CSS simple for fast loading
- Update project links to point to your GitHub repositories or live demos
- You can add more styling or JavaScript as needed
- GitHub Pages supports custom domains if you own one
