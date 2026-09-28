# Portfolio Website

A modern, interactive portfolio website featuring:
- Authentication screen with pixel animation
- Interactive terminal interface
- Solar system skill visualization
- Dynamic command system
- Responsive design

## Deployment on GitHub Pages

1. Push this folder to a GitHub repository
2. Go to Settings → Pages → Source: "Deploy from a branch"
3. Select `main` branch, `/ (root)` folder
4. The site will be live at `https://<username>.github.io/<repo-name>/`

## Deployment on Netlify

### Option 1: Drag & Drop (Easiest)
1. Go to [netlify.com](https://netlify.com)
2. Sign up/login
3. Drag this entire folder onto the deploy area

### Option 2: Git Integration
1. Push this folder to GitHub/GitLab/Bitbucket
2. Connect your repository in Netlify
3. Deploy automatically

### Option 3: Netlify CLI
```bash
# Install Netlify CLI
npm install -g netlify-cli

# Login to Netlify
netlify login

# Deploy from this folder
netlify deploy --prod --dir .
```

## Files
- `index.html` - Main landing page (interactive portfolio with terminal)
- `profile.jpg` - Profile image
- Certificate images in JPG format

The site is ready for deployment - all assets are self-contained and paths are deployment-safe.