# Flash Archiver — Self-Hosting Guide

This guide explains how to set up your own copy of the Flash Archiver tool to upload, preview, and embed SWF files hosted from your personal GitHub Pages site.

## Step 1: Fork the Repository

1. Visit the original repository at: [https://github.com/FlashAdArchiver/swfArchiver](https://github.com/FlashAdArchiver/swfArchiver)  
2. Click the "Fork" button in the top-right corner  
3. Choose your GitHub account  

GitHub will create a forked copy for you at:  
`https://github.com/YOUR_USERNAME/swfArchiver`

## Step 2: Enable GitHub Pages

1. In your forked repository, go to **Settings → Pages**  
2. Under the "Source" section:  
   - Select `main` as the branch  
   - Choose the `/ (root)` folder  
3. Click **Save**

After a few moments, your site will be live at:  
`https://YOUR_USERNAME.github.io/swfArchiver/`

## Step 3: Use the Archiver Tool

1. Open your GitHub Pages site in a browser:  
   `https://YOUR_USERNAME.github.io/swfArchiver/`  
2. Enter your GitHub Personal Access Token in the input field  
   > This token must include `repo` access permissions.  
3. Use the tool interface to:  
   - Upload SWF files to your GitHub repo  
   - View and preview uploaded SWFs  
   - Generate embed code for each SWF  

The embed code will look like:

```
https://YOUR_USERNAME.github.io/swfArchiver/index.html?swf=FILENAME.swf&width=WIDTH&height=HEIGHT
```

> Note: The `swf/` folder will be created automatically the first time you upload a file.

---

## Themes and Customization

- The interface supports multiple selectable themes:  
  - **GeoCities** (retro)  
  - **Bubble** (Frutiger Aero-inspired)  
  - **Dark Glow** (dark 2003-style sci-fi)  
  - **Plain** (minimal)

- Use the **"Themes"** dropdown in the upper-right to switch styles.  
- A toggle next to the Ko-fi button allows you to show or hide the scrolling marquee.  
- The layout remains consistent across all themes.

To customize further, edit:
- `index.html` for structure and labels  
- Inline or linked CSS for colors and branding

All SWFs are served directly via GitHub Pages — no backend required.

---

## Troubleshooting

- If GitHub Pages doesn't load right away, wait a minute and refresh  
- Ensure `index.html` is in the root of your repo  
- Make sure your token is valid and includes the `repo` scope  
- If the page briefly loads unstyled, this is normal and will resolve once the styles load

---

This setup allows you to host your own Flash content securely and independently using only GitHub.
---

This setup allows you to host your own Flash content securely and independently using only GitHub.

**Enjoying this project? [Support me on Ko-fi ☕](https://ko-fi.com/K3K11GA733)**  
