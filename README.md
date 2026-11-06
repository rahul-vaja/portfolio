# Rahul Vaja — Portfolio

## Open it
- Quick look: double-click `index.html`.
- Proper preview (recommended): in this folder run `python -m http.server` and open http://localhost:8000

## Edit content
Everything lives in the `CONFIG` object near the bottom of `index.html`:
- `resume`: path to a PDF (e.g. `assets/rahul-vaja-resume.pdf`). The Resume link appears once this is set.
- `portrait`: path to a photo (e.g. `assets/img/rahul.jpg`). It's shown in black & white automatically.
- `work[].year`, `work[].dur`: leave them empty to hide them.
- `clips[].title`: titles for the untitled YouTube clips.
- `contact`: add Instagram / YouTube handles. Empty rows are hidden.
- `available`: set it to `false` to hide the "Available for freelance" badge.
- `media.vertical`: set it to `false` for any YouTube video that is 16:9.

## Go live (free)
- Netlify: drag this whole folder onto https://app.netlify.com/drop
- Or Vercel / GitHub Pages. It's a static site with no build step.

## Assets
- `assets/video/` holds the 6 outros, re-encoded to 720p (28 MB → 2 MB total), plus `showreel.mp4`, a 25s montage of the outros.
- `assets/img/` holds clean poster frames.
- `assets/fonts/` has the self-hosted Archivo, Inter and IBM Plex Mono.
- `assets/js/lenis.min.js` provides the smooth scroll.
