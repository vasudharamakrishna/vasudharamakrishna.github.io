# Personal academic website

A one-page site for GitHub Pages: plain HTML and CSS, with no build step and nothing to install.

## What to edit first

Everything you need to change is in `index.html`, marked with `<!-- EDIT -->` comments:

1. **Name**: already set to Vasudha Ramakrishna.
2. **Email**: the `mailto:` link.
3. **Photo**: put a square photo in the `assets` folder named exactly `photo.jpg`. The page already points to it.
4. **CV**: add your CV to this folder as `cv.pdf`. The download button already points to it.
5. **Intro**: finish the sentence about Y-RISE.
6. **Abstracts**: paste each abstract between the empty `<p></p>` tags under its paper. The Abstract link appears once there is text.
   To link a draft, put the PDF in a `papers` folder (for example `papers/heart-sellers.pdf`) and add `<a href="papers/heart-sellers.pdf">PDF</a>` under its title.
7. **Teaching**: not on the site yet; ask to have a section added back when you have your course list.

## Publish it on GitHub Pages

1. Sign in to GitHub and create a new **public** repository named exactly `YOUR-USERNAME.github.io`.
2. On the new repository page, click **uploading an existing file** and drag in everything in this folder:
   `index.html`, `.nojekyll`, `README.md`, the `assets` folder, and `cv.pdf` once you've added it. Click **Commit changes**.
   (`.nojekyll` is hidden on Mac and Windows: on a Mac, press Cmd+Shift+. in Finder to show it. The site still works without it.)
3. Go to **Settings > Pages**. Under "Build and deployment", set **Source** to *Deploy from a branch*, then pick branch `main` and folder `/ (root)`, and click **Save**.
4. After a minute or two, the site is live at `https://YOUR-USERNAME.github.io`.

To update the site later, edit `index.html` on GitHub (the pencil icon) or upload a new `cv.pdf`. Changes go live within about a minute.

## Using your own domain (optional)

Under **Settings > Pages > Custom domain**, enter the domain and follow GitHub's DNS instructions.
