# Open Shelf

A small personal directory of open-source apps. It is a static site, so it runs on GitHub Pages without a build step or external dependencies.

## Publish with GitHub Pages

1. Create a GitHub repository. For a personal homepage, name it `<your-username>.github.io`.
2. Add these files to the repository and push the `main` branch.
3. In the repository, open **Settings → Pages** and set the source to **GitHub Actions**.
4. The included workflow deploys the site whenever you push to `main`. The published address appears under **Settings → Pages** and in the workflow run.

## Make it yours

Edit the `apps` list near the end of `index.html` to add, remove, or update an app. Each entry has a display name, category, short description, project website, and source-code URL. Favorites are stored in the visitor's browser using local storage.

The app directory is an independent selection; each project retains its own name, code, and license. Follow the linked project pages for current license details.
