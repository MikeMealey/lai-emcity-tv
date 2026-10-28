# Emerald City — Office TV Ambient Page

A tiny static website designed for a 16:9 office TV. It uses a 4K background image with subtle CSS-only motion: drifting haze, a slow wet-road sheen, and occasional fluorescent flicker.

## Publish with GitHub Pages

1. Sign in to GitHub and create a new repository. A name like `emerald-city-tv` works well.
2. Upload these files to the repository root:
   - `index.html`
   - `emerald-city-4k.jpg`
   - `.nojekyll`
3. Commit the files.
4. Open the repository's **Settings**.
5. Choose **Pages** in the left sidebar.
6. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
7. Choose branch **main** and folder **/(root)**, then click **Save**.
8. GitHub will show the published URL when deployment is ready. It will normally look like:
   `https://YOUR-USERNAME.github.io/emerald-city-tv/`
9. Open that URL in the TV's web browser and bookmark it.

## TV notes

- The page fills the entire browser window and has no controls or text overlays.
- If the TV browser has an option to hide its address/navigation bar, enable it.
- If the browser sleeps or reloads tabs automatically, check the TV's energy-saving and browser settings.
- The motion is intentionally slow so it can remain on all day without drawing attention.

## Customize motion

Everything is in `index.html`. The most useful values to tweak are:

- `hazeDrift 44s` — fog speed
- `roadSheen 29s` — reflection movement
- `fluorescentFlicker 23s` — rough flicker cycle
- `.haze { opacity: 0.25; }` — fog strength
- `.sheen { opacity: 0.18; }` — reflection strength

No server-side code or JavaScript is required.
