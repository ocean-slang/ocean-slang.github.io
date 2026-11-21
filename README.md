# Sarah E. Lang – personal website

Plain HTML + CSS

## Files

```
index.html        Home page
research.html     Research topics (photo + description for each)
cv.html           Full CV as a web page
mentorship.html   NASA SARP + other mentorship
fieldwork.html    Cruises, photos, media
css/style.css     ALL styling for every page (colors, fonts, spacing)
images/           Photos and figures
files/            Downloadable files (CV PDF)
.nojekyll         Tells GitHub Pages NOT to run Jekyll (keep this file)
```

## Editing

- **Preview:** double-click any `.html` file to open it in your browser. Save your edit, then refresh the page.
- **Text:** open the `.html` file in a text editor (VS Code is a good free one) and change the words between the tags.
- **Placeholders:** search for `Insert description here` and `[Optional` to find every spot you still need to write.
- **Colors:** the top of `css/style.css` has a short list of color variables (`--deep`, `--ocean`, `--teal`, `--kelp`, ...). Change a hex code there and the whole site updates.
- **Fonts:** headings use EB Garamond (the free web version of Garamond). Body text uses Proxima Nova, which is a paid Adobe font. Until you add it, visitors see Montserrat, a free look-alike. To get real Proxima Nova: in Adobe Fonts (often free through a university Adobe Creative Cloud license), add Proxima Nova to a "web project". Then paste the `<link rel="stylesheet" href="https://use.typekit.net/XXXXXX.css">` line it gives you into the `<head>` of each page.
- **Home banner billows:** `images/kh-billows.svg` is one repeating tile from a Kelvin–Helmholtz vortex-sheet roll-up simulation. Resize it with `background-size` under `.banner-kh .kh` in the CSS.
- **Photos:** put the image in `images/` and change the `src="images/..."` path. On the Research page, `object-fit: contain` in the CSS shows each whole figure. Change it to `cover` to fill and crop the frame instead.
- **Adding a page:** copy an existing page, rename it, change its content, and add a link to it in the `<nav class="site-nav">` block **on every page**. The menu is copied into each page because there's no build step.
- **Updating the CV:** edit `cv.html` directly, and replace `files/CV_Lang_Sarah.pdf` with your newest PDF.

## Publishing on GitHub Pages (ocean-slang.github.io)

1. Back up the old site, for example on a new branch called `old-jekyll-site`.
2. On the main branch, delete the old Jekyll files and copy in everything from this folder, including the hidden `.nojekyll` file.
3. Commit and push. In the repo's **Settings → Pages**, the source should be "Deploy from a branch" → `main` / `(root)`.
   If it's set to "GitHub Actions" (the al-folio theme uses that), switch it to "Deploy from a branch".
4. After a minute or two the new site is live at https://ocean-slang.github.io
