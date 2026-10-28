# Emerald City TV

A full-screen animated ambient page for a 4K TV, inspired by old green-lit underground Chicago roadways.

## Files
- `index.html` — the webpage and all animation code
- `emerald-city-4k.jpg` — 3840×2160 background image
- `.nojekyll` — tells GitHub Pages to serve the files directly

## Publish with GitHub Pages
1. Create a new GitHub repository, for example `emerald-city-tv`.
2. Upload **all three files** above into the root of the repository.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch **main** and folder **/(root)**, then Save.
6. GitHub will publish a URL like:
   `https://YOURUSERNAME.github.io/emerald-city-tv/`
7. Open that URL in the TV browser and bookmark it.

## Updating an existing installation
If you already uploaded the older version, simply replace `index.html` with this one and commit the change. GitHub Pages can take a minute or two to refresh. If the old page remains cached on the TV, reload the page or append `?v=2` to the URL once.

## Motion in v2
This version intentionally ignores the device's reduced-motion preference because the animation is the purpose of the display. It includes:
- slow camera drift
- broad drifting haze
- two rising steam plumes
- moving wet-road reflection
- occasional fluorescent flicker

No external JavaScript libraries or video streams are required.
