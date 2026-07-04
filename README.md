# Vancouver & Partners landing page

A one-page GitHub Pages-ready landing site with:

- full-screen autoplay muted video background
- bright luxury-white `Vancouver & Partners` typography
- same-colour hyperlinked ampersand
- no blurred panel behind the logo
- logo reveal 40 seconds after the video begins playing

## Setup

1. Put your licensed aerial footage in `assets/`.
2. Rename the video to `vancouver-aerial.mp4`.
3. Upload the whole folder to a GitHub repository.
4. Enable GitHub Pages from the repository root.
5. Configure your custom domain in GitHub Pages settings and then add the DNS records in GoDaddy.

## Edit timing

In `index.html`, change this line if you want a different reveal timing:

```js
const delayMs = 40000;
```

## Edit typography

The page uses Cormorant Garamond from Google Fonts with Didot/Bodoni/Garamond fallbacks. Adjust `.brand-title` in the `<style>` section to change size, spacing, or weight.
