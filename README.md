# Mohammad Shafi Hossain — Portfolio

Personal portfolio site, built as plain HTML/CSS/JS with no build step. Hosted on GitHub Pages.

## Files

- `index.html` — the whole site (styles and scripts inline)
- `assets/profile.jpg` — portrait
- `assets/CV_Mohammad_Shafi_Hossain.pdf` — downloadable CV
- `.nojekyll` — tells GitHub Pages to serve files as-is

## Publish on GitHub Pages

1. Sign in to GitHub as **shafi-hossain** and create a **new public repository** named exactly
   `shafi-hossain.github.io`. Leave "Add a README" unticked.
2. On the new repo page click **uploading an existing file**, then drag in `index.html`, `README.md`,
   `.nojekyll` and the `assets` folder. Click **Commit changes**.
   (Hidden files: on macOS press Cmd+Shift+. in Finder to see `.nojekyll`. It's optional.)
3. Go to **Settings → Pages**. Under *Build and deployment*, set Source to **Deploy from a branch**,
   branch **main**, folder **/ (root)**, and save.
4. Wait 1–2 minutes, then open https://shafi-hossain.github.io/

## Updating

- **New CV:** replace `assets/CV_Mohammad_Shafi_Hossain.pdf` with a file of the same name.
- **New photo:** replace `assets/profile.jpg` (square, at least 360×360).
- **Text:** edit `index.html`; each section is marked with an `id` (`about`, `experience`, `work`,
  `skills`, `credentials`, `contact`).
- **Career chart:** roles are listed in the `roles` array near the bottom of `index.html`.
  `l` is the step height (seniority, 1–5).
- Years of experience and the footer year update automatically.
