# AI Teaching Field Guide

Faculty guides for teaching and learning with AI, built on the Digital Education
Council frameworks, for every department in UNC Charlotte's College of
Humanities & Earth and Social Sciences.

## Publish on GitHub Pages
1. Upload everything in this folder (`index.html`, `sw.js`, `manifest.webmanifest`, `icons/`, `slides/`) to the root of a repository.
2. In the repository: Settings, then Pages, then Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
3. The site appears at `https://<your-username>.github.io/<repository-name>/` within a minute or two.

## Install it as an app
Once it's on GitHub Pages, anyone can install it from the site:
- **Chrome or Edge (Mac or Windows):** click **Install app** in the site's menu bar, or the install icon at the right of the address bar.
- **Safari on Mac:** File, then Add to Dock.
- **iPhone or iPad:** Share, then Add to Home Screen.

The app opens in its own window, works offline after the first visit, and updates itself the next time it's opened online after you upload a new build.

## Updating
This folder is generated. Edit the files in `hub/`, run `python3 hub/build-github.py`,
and upload the whole folder again.
