# EdRoberson.com V1

A simple static site designed for free hosting on GitHub Pages.

## Before publishing
1. Replace the LinkedIn placeholder URL in `index.html` with your actual LinkedIn profile URL.
2. Replace the photo placeholder with your own image if desired.
3. Review the email address in the contact button.
4. Edit any copy you want to refine.

## Publish with GitHub Pages
1. Create a public GitHub repository, for example `edroberson.com`.
2. Upload all files and folders from this package.
3. Open **Settings > Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose **main** and **/(root)**.
6. Save.
7. Add `www.edroberson.com` as the custom domain after the preview site is working.
8. Update DNS at GoDaddy using GitHub's current custom-domain instructions.

## Add a real photo
Replace the placeholder `div` in the hero section with:

```html
<img class="hero-photo" src="assets/ed-roberson.jpg" alt="Ed Roberson">
```

Then add this to `assets/styles.css`:

```css
.hero-photo {
  display: block;
  width: 100%;
  aspect-ratio: 4 / 5;
  object-fit: cover;
}
```

Place the image file at `assets/ed-roberson.jpg`.

## Notes
This version intentionally has no database, no WordPress, no paid hosting dependency, and no build step.
