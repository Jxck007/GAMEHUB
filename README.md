# Calm Play Arcade

A single-page static game hub. No build step, dependencies, or environment variables are required.

## GitHub Pages

1. Create a new GitHub repository.
2. Upload **all files from this folder** to the repository root. `index.html` must not be inside another folder.
3. Commit the files to the `main` branch.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**.
6. Select branch **main**, folder **/(root)**, then save.

The site will be available at:
`https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`

## Vercel

1. Push this folder to a GitHub repository.
2. In Vercel, choose **Add New → Project** and import the repository.
3. Framework Preset: **Other**.
4. Root Directory: leave as `./`.
5. Build Command: leave empty.
6. Output Directory: leave empty.
7. Deploy.

You can also drag this entire folder into the Vercel CLI workflow. The entry file is `index.html`.
