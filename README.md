# Links Vault

A responsive personal bookmark manager built with React, TypeScript, Vite, and plain CSS. Links are saved in the browser's local storage.

## Run locally

```sh
npm install
npm run dev
```

Build and check the production app with:

```sh
npm run build
npm run lint
```

## Deploy to GitHub Pages

The GitHub Actions workflow in `.github/workflows/deploy.yml` builds and deploys the app whenever changes are pushed to `main`.

1. Push this project to a GitHub repository.
2. In the repository, open **Settings → Pages** and choose **GitHub Actions** as the build and deployment source.
3. Push to `main` or manually run the **Deploy to GitHub Pages** workflow.

Vite selects the correct base path from the GitHub repository name during the workflow build.
