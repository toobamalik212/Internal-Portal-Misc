# Step-by-Step Deployment Guide

This project is a static web document. That means you can edit the HTML and CSS and publish it without needing a build pipeline.

## 1. Open the project

Open the folder in VS Code and make sure you are in the project root.

## 2. Preview locally

Run a local web server:

```bash
cd /Users/tooba.malik/Desktop/misc-portal-review
python3 -m http.server 8000
```

Then browse to:

```text
http://localhost:8000
```

## 3. Edit the document

Update the content in `index.html`.

Use `styles.css` to change colors, spacing, layout, typography, and responsiveness.

## 4. Save and review changes

Check the page in the browser after each update.

Keep it simple and professional, especially if you plan to share it with others.

## 5. Put the project into Git

If you want to deploy it online, initialize a Git repository:

```bash
git init
git add .
git commit -m "Initial commit"
```

## 6. Push to GitHub

Create a repository on GitHub and then run:

```bash
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git
git push -u origin main
```

## 7. Deploy with GitHub Pages

1. Open the GitHub repository.
2. Go to Settings.
3. Click Pages.
4. Under Source, choose Deploy from a branch.
5. Choose the `main` branch and root folder.
6. Save.
7. GitHub will give you a public URL.

## 8. Deploy with Netlify

1. Go to https://www.netlify.com
2. Click Add new site.
3. Choose Import an existing project.
4. Connect your GitHub repository.
5. Use the default settings for a static site.
6. Deploy.

## 9. Deploy with Vercel

1. Go to https://vercel.com
2. Import your repository.
3. Vercel will detect the static site automatically.
4. Keep the default settings.
5. Deploy and share the live URL.

## 10. Share the final link

Once the site is live, share the URL with teammates, stakeholders, or other people.

## 11. Optional: custom domain

If you want a branded link:

- set up a custom domain in Netlify, Vercel, or GitHub Pages
- update DNS settings as instructed by the provider

## Notes

This is a good choice for a simple internal or external document because it does not require a backend, database, or build system.
