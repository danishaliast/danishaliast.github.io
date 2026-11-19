# Danish Ali — Academic Website

A responsive, static academic website designed for GitHub Pages.

## 1. Publish on GitHub Pages

1. Sign in to GitHub as **danishaliast**.
2. Create a **public** repository named exactly:
   `danishaliast.github.io`
3. Upload the contents of this folder (not the enclosing ZIP file) to the repository root.
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch **main** and folder **/(root)**, then click **Save**.
7. Wait a few minutes and visit:
   https://danishaliast.github.io/

If your GitHub username differs from `danishaliast`, change the repository name and the address to match the actual username.

## 2. Personalise before or after publishing

### Replace the profile image
Replace `assets/images/profile-placeholder.svg` with your own portrait named `profile.jpg`, then edit the image line in `index.html` to:
`<img src="assets/images/profile.jpg" alt="Danish Ali">`

Use a professional head-and-shoulders photograph, ideally square or portrait orientation.

### Add your CV
Create the folder `assets/documents/` if necessary and upload your PDF named exactly `CV.pdf`.
The CV link in the website already points to `assets/documents/CV.pdf`.

### Add your email and academic profile links
In `index.html`, search for:
- `YOUR-EMAIL@example.com`
- `Add your email address`
- `https://scholar.google.com/`
- `https://orcid.org/`
- `https://www.researchgate.net/`

Replace these placeholders with your real email and profile URLs.

### Review academic details
The site includes the two 2023 journal publications and education details currently available. Please verify author order, journal details, DOI links, and all biographical information before treating the website as a formal academic record. Add any further publications, current position, teaching assignments, and talks only after confirming the details.

## 3. Updating the site

Edit `index.html` directly on GitHub using the pencil icon, or upload revised files. Every commit to the `main` branch triggers a new GitHub Pages deployment.

## 4. Technical notes

- No build tools, package installation, or backend are required.
- The site uses plain HTML, CSS, and JavaScript.
- Google Fonts are loaded from Google Fonts; the page remains readable with system-font fallbacks if they are unavailable.
- The site is responsive and includes mobile navigation.
