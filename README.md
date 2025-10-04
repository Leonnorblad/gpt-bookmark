# GPT Bookmark Generator

A simple static web app that lets you generate **ChatGPT bookmark templates**.  
With these bookmark templates, you can highlight text or capture the current page URL and instantly inject them into a custom GPT prompt.

---

## ✨ Features

- 📝 Build reusable **prompt templates**
- 🔗 Auto-inserts dynamic variables:
  - `{{page_url}}` → the current page’s URL
  - `{{highlighted_text}}` → any selected text
- ⚙️ Customization options:
  - Bookmark name
  - Model selection (GPT-4, GPT-3.5, o1, etc.)
  - Temporary chat toggle
  - Open in new window or tab
- 📄 100% static — no backend, just a single HTML file
- 🚀 Deployed automatically to **GitHub Pages**

---

## 🔧 Usage

1. Open the [deployed site](https://leonnorblad.github.io/gpt-bookmark/).
2. Type your **prompt template** or click variables to insert them.
3. Adjust advanced options if needed.
4. Click **Generate bookmark template**.
5. Drag the generated bookmarklet link to your bookmarks bar.
6. Use it on any page → it will open ChatGPT with your prompt, filled in with the page context.

---

## 🛠 Development

This project is a single-page static site:

- `index.html` → Main app (editor, variables, bookmarklet generator)
- GitHub Actions workflow automatically builds and deploys on push to `main`

To customize:
- Edit `index.html` directly
- Commit and push → changes will auto-deploy