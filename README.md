# jiho-jeong.github.io

Personal academic homepage — plain HTML/CSS/JS, no build step.

## Deploy
1. Copy `index.html`, `profile.jpg`, `README.md` into the `jiho-jeong.github.io` repo root.
2. `git add . && git commit -m "Initial site" && git push`
3. Repo → Settings → Pages → Source: `Deploy from a branch` / `main` / `/ (root)`.
4. Wait ~1 min → https://jiho-jeong.github.io/

## Editing
All content lives in the `const DATA = {...}` block at the bottom of `index.html`
(publications, projects, patents, experience, links). Edit there; no need to touch the HTML.

- `cvPdf: "cv.pdf"` → drop a `cv.pdf` in the repo root to get a CV button.
- `orcid: "https://orcid.org/..."` → adds an ORCID button.
- Publication `doi` fields empty → no DOI button; fill in when known.
