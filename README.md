# Piyush Nagpal / The Workbench

An interactive 3D portfolio about embedded systems, firmware, connected devices, and the objects behind the work.

**Site address after launch:** https://its-me-piyush.github.io/

Explore a rover, an AstroNav phone, an oscilloscope, a satellite, experience badges, a cup of chai, and a fifteen-pixel NeoPixel Defence setup. Every object opens a project or background story.

## Explore

- Click an object or use the numbered controls to open its story.
- Enable **Look Around** to rotate and zoom the desk, then **Reset View** to return.
- Use **Show Labels** on larger screens to identify objects.
- Click the chai to switch the desk’s warm lighting.
- The **Bench Index** offers a direct route to the stories.
- Download the resume or follow GitHub, LinkedIn, and email links.

The scene objects are interactive illustrations. Project descriptions identify built work, prototypes, and work in progress.

## Stack

HTML, CSS, JavaScript ES modules, Three.js, and OrbitControls. No package installation, build step, backend, API keys, account login, or external JavaScript CDN is required to run this site.

## Run locally

Serve this folder over HTTP. Do not open `index.html` by double-clicking it; browsers restrict ES modules on `file://` URLs.

Windows, with Python installed:

```powershell
py -m http.server 8000
```

macOS / Linux, with Python installed:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000/ in a modern browser. Stop the server with Ctrl+C. The 3D scene requires WebGL; if it is unavailable, use the object buttons and Bench Index to read the stories.

## Publish on GitHub Pages

See [START_HERE.md](./START_HERE.md) for repository settings, browser upload instructions, and troubleshooting. The intended repository is **its-me-piyush/its-me-piyush.github.io**.

Publish from **main / (root)**. The `.nojekyll` file keeps this a plain static site.

## Files and editing

| File | Purpose |
| :--- | :--- |
| `index.html` | Page layout, styles, project text, drawer behavior, links |
| `workbench.js` | 3D models, lighting, textures, controls, animation |
| `Piyush-Nagpal-Resume.pdf` | Downloadable resume |
| `monkey-trademark.png` | Personal signature and favicon |
| `vendor/` | Three.js, OrbitControls, and their license |
| `.nojekyll` | Bypasses Jekyll processing for branch publishing |
| `START_HERE.md` | Launch guide and repository metadata |
| `THIRD_PARTY_NOTICES.md` | Dependency attribution |

Project content is stored in the `artifacts` object in `index.html`. Replace the resume with the same filename to update it. Update dates and current-work descriptions as projects progress. Commit changes to `main` to trigger another Pages deployment.

## Attribution

Three.js and OrbitControls are distributed under the MIT license. Their license is retained in [vendor/LICENSE](./vendor/LICENSE). Personal branding, portfolio text, and the resume are separate from that dependency license.

[GitHub](https://github.com/its-me-piyush) · [LinkedIn](https://www.linkedin.com/in/piyush-nagpal/) · [Email](mailto:piyushnagpal777@gmail.com)
