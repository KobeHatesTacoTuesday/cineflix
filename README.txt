CINEFLIX - EASY GITHUB PAGES DEPLOYMENT

1. Go to github.com and create a new repository.
2. Make the repository Public if you are using GitHub Free.
3. Open the repository and choose Add file -> Upload files.
4. Upload index.html and .nojekyll from this folder.
5. Commit the files to the main branch.
6. Open Settings -> Pages.
7. Under Build and deployment, choose Source: Deploy from a branch.
8. Branch: main
9. Folder: /(root)
10. Click Save.
11. When GitHub finishes publishing, your site will be at:
    https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/

IMPORTANT:
- _worker.js is not needed on GitHub Pages.
- GitHub Pages is static hosting, so this version requests TMDB directly in the browser.
- The TMDB API key inside index.html is visible to visitors because static sites cannot hide browser-side secrets.
