# Dhanashri Mohod | Portfolio

A responsive, single-page personal portfolio built with HTML, CSS, and vanilla JavaScript. It runs directly in a browser and has no build step or backend.

## Run locally

1. Open this folder in VS Code or File Explorer.
2. Open `index.html` in a browser. In VS Code, you can also use the Live Server extension if you prefer a local preview server.
3. The Google Fonts stylesheet is optional; the page uses fallback fonts if you are offline.

## Personalize your portfolio

- Replace `assets/profile-placeholder.svg` with your own image. Keep the same filename, or update the image path and alt text in `index.html`.
- Add your PDF as `assets/Dhanashri-Mohod-Resume.pdf`. The hero's Download resume link already points to that exact path.
- Replace the email and phone placeholders in the Contact section with your real details.
- Replace the LinkedIn and GitHub profile placeholders in `index.html` with your profile links when ready.
- Edit the example project cards and certification placeholder with real information. The sample projects are explicitly marked as examples; the document reminder project is marked in development.
- Update the page title and description in the `<head>` if you change the portfolio focus.

The contact form is a visual demo only. It does not send, store, or transmit form data. Connect a backend or form service before using it to receive messages.

## Publish on Netlify

### Option A: Deploy from a Git repository

1. Create a Git repository for this folder and push it to GitHub, GitLab, or Bitbucket.
2. Sign in to [Netlify](https://www.netlify.com/) and choose **Add new site** then **Import an existing project**.
3. Connect the repository and select the branch to publish.
4. Leave the build command and publish directory empty/default (the site is plain static files at the repository root), then deploy.
5. Use the Netlify site settings to choose a site name or connect a custom domain.

### Option B: Manual deploy

1. Sign in to Netlify and open the Sites page.
2. Drag this project folder, including `assets/`, into the manual deploy area.
3. Wait for the deploy to finish, then open the generated site URL.

## Files

- `index.html`: page content and metadata
- `style.css`: responsive layout, colors, and motion
- `script.js`: mobile menu, scroll reveals, and static form feedback
- `assets/profile-placeholder.svg`: replaceable profile illustration
