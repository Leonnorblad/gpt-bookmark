# gpt-bookmark

A simple static website hosted on GitHub Pages.

## Setup

This repository is configured to automatically deploy to GitHub Pages using GitHub Actions.

### How to Enable GitHub Pages

1. Go to your repository settings
2. Navigate to "Pages" in the left sidebar
3. Under "Build and deployment":
   - Source: Select "GitHub Actions"
4. The workflow will automatically deploy your site when you push to the `main` branch

### Accessing Your Site

Once deployed, your site will be available at:
`https://<your-username>.github.io/gpt-bookmark/`

### Editing the Content

- The main HTML file is `index.html`
- Edit this file to customize your website content
- Push changes to the `main` branch to update the live site

### File Structure

- `index.html` - Main HTML file for your website
- `.github/workflows/static.yml` - GitHub Actions workflow for deployment