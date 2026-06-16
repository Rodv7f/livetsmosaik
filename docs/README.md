# Live TS Mosaik - GitHub Pages Setup

This folder contains your static WordPress site configured for GitHub Pages hosting.

## Quick Start

1. **Merge the `github-pages-setup` branch to `main`**
   ```bash
   gh pr create --base main --head github-pages-setup
   ```

2. **Enable GitHub Pages**
   - Go to Settings → Pages
   - Source: Deploy from a branch
   - Branch: `main`
   - Folder: `/docs`
   - Click Save

3. **Wait for deployment** (1-2 minutes)

4. **Your site will be live at:**
   ```
   https://rodv7f.github.io/livetsmosaik/
   ```

## To Add Your Full Site

Extract your `simply-static-1-1781557595.zip` file and copy all contents into this `docs/` folder, maintaining the directory structure.

### Expected Structure:
```
docs/
├── index.html
├── .nojekyll
├── README.md
├── css/
├── js/
├── images/
└── other-pages/
    ├── page1/index.html
    ├── page2/index.html
    └── ...
```

## Important Notes

- ⚠️ **This is static HTML only** - WordPress database functionality won't work
- ✅ **All static assets** (CSS, JS, images) will work perfectly
- ✅ **Free HTTPS** provided by GitHub
- ✅ **Custom domain support** available in Settings

## Troubleshooting

### Site not showing?
- Check that GitHub Pages is enabled in Settings → Pages
- Verify the source branch and folder (`main` / `/docs`)
- Wait a few minutes for deployment

### Links not working?
- Ensure relative paths in HTML files are correct
- Check that `index.html` exists in subdirectories if needed

### Need help?
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [GitHub Pages Troubleshooting](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages)
