# ROSAS | Rose Ann T. Tantiado Portfolio

A static portfolio website built using HTML, CSS and JavaScript. Ready for GitHub Pages. No build tools or package installation required.

## Publish with GitHub Pages

1. Sign in to GitHub and create a **public** repository, for example `rosas-portfolio`.
2. Upload the **contents** of this folder to the root of the repository. Keep `index.html` at the root, and preserve the `images/` and `videos/` folders.
3. Commit the files to the `main` branch.
4. In the repository, open **Settings > Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/ (root)`, and click **Save**.
6. Your website will be published at `https://YOUR-USERNAME.github.io/rosas-portfolio/` once GitHub Pages reports deployment completed.

## Customize

- Edit the text and layout in `index.html`.
- Your professional portrait is already included as `images/rose-ann.jpg` and linked in the hero section. Replace this image file to update the portrait later.
- For project images, add `images/project-website.jpg`, `images/project-email.jpg`, `images/project-social.jpg`, `images/project-video.jpg`, `images/project-funnel.jpg`, and `images/project-flyer.jpg`. Sample graphics appear when files are missing.
- To use your own hero background, find the `.hero::before` background-image URL in `index.html` and replace it with `url('images/hero-background.jpg')` after adding the image.
- To show video samples, add MP4 files to the `videos/` folder and use the HTML `<video controls>` element in your project card or a dedicated section. Avoid committing files larger than GitHub's standard file limits. For large videos, use a hosted video embed instead.
- The header and footer logo files are in `images/`.

## Notes

- This website uses Google Fonts and a remote office photo, so those assets require internet access.
- All links to email and phone use the contact details provided for this portfolio.
- Project previews are sample slots until replaced with actual completed work.
- No server-side features or database are necessary.
