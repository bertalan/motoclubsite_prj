# GitHub Pages Configuration Guide

This document provides step-by-step instructions for configuring GitHub Pages to view the theme examples.

## Quick Setup (5 minutes)

### 1. Enable GitHub Pages

1. Go to your repository's **Settings** page:
   - URL: https://github.com/bertalan/motoclubsite_prj/settings

2. Click on **Pages** in the left sidebar
   - Or directly: https://github.com/bertalan/motoclubsite_prj/settings/pages

3. Under **"Build and deployment"** section:
   - **Source**: Select `Deploy from a branch`
   - **Branch**: Select `main`
   - **Folder**: Select `/ (root)`

4. Click **Save**

5. Wait 1-2 minutes for GitHub to build and deploy your site

### 2. Access Your Live Themes

Once deployed, your themes will be accessible at:

- **Main Gallery**: https://bertalan.github.io/motoclubsite_prj/
- **Velocity Theme**: https://bertalan.github.io/motoclubsite_prj/theme_examples/velocity/
- **Heritage Theme**: https://bertalan.github.io/motoclubsite_prj/theme_examples/heritage/
- **Terra Theme**: https://bertalan.github.io/motoclubsite_prj/theme_examples/terra/
- **Zen Theme**: https://bertalan.github.io/motoclubsite_prj/theme_examples/zen/
- **Clubs Theme**: https://bertalan.github.io/motoclubsite_prj/theme_examples/clubs/
- **Tricolore Theme**: https://bertalan.github.io/motoclubsite_prj/theme_examples/tricolore/

## Files Included for GitHub Pages

This repository includes the following files to support GitHub Pages:

1. **`.nojekyll`** - Tells GitHub Pages not to process files with Jekyll
2. **`index.html`** - Landing page with theme gallery and navigation
3. **`theme_examples/*/index.html`** - Individual theme demo pages

## Troubleshooting

### Pages not showing up?

- Check that you've selected the correct branch (`main`) and folder (`/ (root)`)
- Wait a few minutes - initial deployment can take 2-5 minutes
- Check the "Actions" tab for any deployment errors

### Images or styles not loading?

- All theme files use CDN resources (Tailwind, Bootstrap, Google Fonts)
- No additional assets or build steps are required
- If using custom assets in the future, ensure paths are relative

### Custom Domain (Optional)

If you want to use a custom domain instead of `bertalan.github.io/motoclubsite_prj/`:

1. Go to Settings → Pages
2. Add your custom domain under "Custom domain"
3. Configure DNS records as instructed by GitHub
4. See [GitHub's custom domain documentation](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)

## Additional Resources

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [About GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages)
- [Theme Examples README](theme_examples/README.md)
