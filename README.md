# Trip2NewZealand

This site is a static HTML project designed for GitHub Pages.

## Publish to GitHub Pages

1. Push this folder to a GitHub repository.
2. In GitHub, open the repository and go to Settings > Pages.
3. Under Build and deployment, choose Source = GitHub Actions.
4. The workflow in `.github/workflows/deploy-pages.yml` will automatically publish the site.
5. After the workflow finishes, your site will be live at:
   `https://<your-username>.github.io/<your-repository-name>/`

## Notes

- The site uses the root `index.html` file, so no build step is required.
- `.nojekyll` is included to prevent GitHub from processing files with Jekyll.
- If your default branch is not `main`, update the workflow branch name from `main` to your branch name.
