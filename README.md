# Gibran BANHAKEIA — Portfolio

Personal portfolio site for **Gibran Banhakeia**, an OSINT professional specializing in
linguistic analysis and frontend development, focused on language engineering, OSINT tooling,
and tactical applications.

Built with React, TypeScript, and Vite. Themed in Moroccan green and red.

**Contact:** vrgibran@protonmail.com

---

## Chapters

1. **Profile** — OSINT, linguistic analysis, frontend development
2. **Drone Software** — reconstructing navigation-only interfaces into multi-capability platforms
3. **Mapping & GIS** — modernizing tactical GIS with immersive 3D location analysis
4. **Translation** — AI-assisted analysis, geographic detection, risk terminology, contextual translation
5. **Data Visualization** — matrix-style environments for pattern analysis and reporting
6. **Contact**

---

## Run locally

```bash
npm install
npm run dev
```

Then open the URL printed in the terminal (usually `http://localhost:5173`).

## Build

```bash
npm run build
```

The production site is written to `dist/`.

---

## Editing content

**Permanent edits** live in `src/data.ts`:

- `operator` — your name, email, role, specialties, and photo path
- `slides` — the title, body text, and tags for each chapter

**Quick edits** can be made in the browser: open the **INDEX** panel (top right, or press
`F1`) and choose **EDIT CONTENT**. Those changes are saved to that browser only and do not
modify the source files.

## Replacing the photo

Replace `public/images/gibran.png` with your own image, keeping the same filename.
The portrait is automatically graded to match the site palette, so a photo on either a light
or dark background will blend in.

## Keyboard shortcuts

| Key | Action |
| --- | --- |
| `F1` or `O` | Open / close the chapter index |
| `F2` or `F` | Toggle Signal Lens (image clarity) |
| `↑` / `↓` | Move between chapters |
| `Esc` | Close any open panel |

---

## Deploying to GitHub Pages

This repo includes a workflow at `.github/workflows/deploy.yml` that builds and publishes
the site automatically.

1. Push the project to a GitHub repository.
2. In the repository, go to **Settings → Pages**.
3. Under **Source**, select **GitHub Actions**.
4. Push to `main`. The site publishes at
   `https://<your-username>.github.io/<repository-name>/`.

All asset paths are relative, so the site works correctly both at a domain root and inside a
repository subfolder.
