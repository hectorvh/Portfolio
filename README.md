# Hector Valdes Hurtado · Portfolio

A single-page portfolio built with WebGL. A rotary dial switches between five sections: projects, about me, experience, tech stack and contact. Each section shows a 3D model that builds from a point cloud to a solid.

## Run

Open `index.html` in a browser. Three.js r128 and the fonts load from a CDN, so you need a network connection. There is no build step.

## Controls

- **Change section:** scroll, use the ← → keys, or swipe the dial.
- **Open details:** press Enter, or click or tap the selected segment. Close with Esc or ✕.
- **Rotate the model:** drag inside the sphere.
- **Mute sound:** use the SFX button in the footer.

You can link straight to a section with `#projects`, `#about`, `#experience`, `#stack` or `#contact`.

## Editing

All content lives in `index.html`:

- **Content:** `SECTIONS`, `PROJECTS`, `EXPERIENCE`, `STACK`, plus `renderAbout()` and `renderContact()`.
- **3D models:** the `BUILD` object.
- **Colours and fonts:** the `:root` tokens.

## Deployment

The page is static, so it runs on any static host. On GitHub Pages:

1. Push the repository to GitHub.
2. In the repository, go to Settings → Pages.
3. Deploy from the `main` branch, root folder.
