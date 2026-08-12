# NEMA CDS Group — First Internal Training Report

A single, self-contained HTML page reporting on the NEMA CDS Group's first internal training (11 August 2026) — training write-up, photo gallery (22 photos, embedded directly in the file), and attendance manifest.

## Files

Just one: `index.html` — everything (styling, photos, content) is bundled inside it. No separate photos folder, no dependencies to manage.

## Uploading to GitHub

1. Create a new repo on GitHub.
2. "Add file" → "Upload files" → select `index.html` → commit to `main`.
3. On [vercel.com/new](https://vercel.com/new) → "Import Git Repository" → pick this repo → Deploy.

Vercel will detect it as a static site automatically — no build settings needed.

## Updating later

Since everything is in one file, any edit (attendance, write-up, adding photos) just means replacing `index.html` in the repo with an updated version and committing again — Vercel auto-redeploys.
