# Hugh Williams: Portfolio

My personal portfolio of aerospace and mechanical engineering projects, lab reports and software work.

**Live site:** [hughdwill-byte.github.io](https://hughdwill-byte.github.io)

## Projects featured

**Aerospace**
- Composite Airfoil: design, build and test
- Design-Build-Fly Chuck Glider
- Wind Tunnel labs (aerofoil lift; boundary-layer growth)

**Mechanical & systems**
- Wildfire Detection & Monitoring System
- Lunar Rover: powerpack and solar module
- Wing Box Strength Analysis
- Material Selection for a Range of Applications
- Shape-Memory Alloys
- Moment of Inertia of a Crankshaft
- Study of Projectile Motion
- Project SolarAid: emergency solar generator

**Software**
- [Willow](https://github.com/hughdwill-byte/Calendar-App): shared free-time calendar for iOS ([original build](https://github.com/hughdwill-byte/AFP-App))
- [Study HUD](https://github.com/hughdwill-byte/Study-Assistant): desktop study overlay
- [Poker Assistant](https://github.com/hughdwill-byte/Poker-Assistant): Texas Hold'em decision helper
- [ASX Trading Program](https://github.com/hughdwill-byte/ASX-Trading-Program), [Perceptron](https://github.com/hughdwill-byte/Perceptron), [Spotify DJ Perceptron](https://github.com/hughdwill-byte/Spotify-DJ-Perceptron)
- [Resume Shortlist Formatter](https://github.com/hughdwill-byte/Galvin-Rowley-Resume-Formater)
- Unit Converter UI (MATLAB)

## Structure

| Path | Purpose |
|---|---|
| `index.html` | The whole site in one page. Project cards are rendered from a data array inside the page |
| `*.png` | Project thumbnails |
| `*.pdf` | Full project reports, linked from each card |
| `assets/img/`, `reports/` | Older copies of the thumbnails and reports (not referenced by `index.html`) |
| `Portfolio-for-GitHub/` | Earlier version of the site |

## Development

The site is static HTML with no build step. To add a project, add an entry to the `P` array in `index.html` and put its thumbnail and PDF in the repo root. Pushing to `main` deploys it automatically through GitHub Pages.

To preview locally:

```bash
python3 -m http.server   # then open http://localhost:8000
```
