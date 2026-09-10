# Claude Project Notes

This project is a simple static HTML document for sharing project review notes with other people.

## Project structure

- `index.html` — main document content
- `styles.css` — page styling
- `README.md` — onboarding and project summary
- `DEPLOYMENT_GUIDE.md` — step-by-step publishing guide

## How to preview locally

From this folder, run:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Editing guidance

- Keep the page simple and readable.
- Prefer clear headings and concise bullet points.
- Use `index.html` for content and `styles.css` for visual updates.
- Do not add a complex build step unless the project requires it.

## Deploying later

This site is static and can be published without a build system.

Recommended options:

- GitHub Pages
- Netlify
- Vercel

For a public share URL, use a static hosting service and make sure the repository is public or the project is linked to a deployment provider.
