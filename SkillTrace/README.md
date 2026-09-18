# SkillTrace UI

Vite + React + TypeScript interface for SkillTrace.

## Run locally

```bash
npm install
npm run dev
```

## Deploy to GitHub Pages

This repository includes `.github/workflows/deploy.yml`.

1. Push the project to the `main` branch.
2. On GitHub, open **Settings → Pages**.
3. Under **Build and deployment → Source**, select **GitHub Actions**.
4. Open the **Actions** tab and wait for **Deploy SkillTrace to GitHub Pages** to finish.
5. The site will be available at `https://<username>.github.io/<repository>/`.

The Vite build uses relative asset paths so project-site URLs such as `/SkillTrace/` work correctly.
