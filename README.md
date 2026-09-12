# Omesh Giri — Portfolio

> A thoughtful, responsive portfolio for a software developer who enjoys turning ideas into useful digital experiences.

This site is built with semantic HTML, modern CSS and dependency-free JavaScript. It is intentionally lightweight, easy to explore and ready to publish as a static site.

## Highlights

- Responsive home, about and projects pages
- Dark/light theme toggle and mobile navigation
- Keyboard-friendly project filters and case-study modal
- Interactive demos that work without a build step

## Featured projects

| Project | What it demonstrates | Demo |
| --- | --- | --- |
| **Flowboard** | Local-first task management with browser persistence | [`Open demo`](projects/flowboard/index.html) |
| **Metricly** | Reporting-period controls and a dependency-free SVG chart | [`Open demo`](projects/metricly/index.html) |
| **Palette Lab** | Palette generation and one-click hex-value copying | [`Open demo`](projects/palette-lab/index.html) |

## Run locally

No package installation or build tooling is required. Clone the repository and open [`index.html`](index.html) in a browser, or serve the folder with any static web server.

## Publish with GitHub Pages

1. Push the repository to GitHub.
2. Open **Settings → Pages**.
3. Choose **Deploy from a branch**, select `main`, and use the `/ (root)` folder.

## Publish with Vercel

Import this repository into Vercel with the project root set to the repository root.
No build command or output directory is required because this is a static site.
The included [`vercel.json`](vercel.json) keeps the page URLs clean while allowing
Vercel to serve the HTML entry points directly.

## Project structure

```text
.
├── index.html       # Landing page
├── about.html       # About, education and contact
├── projects.html    # Filterable project gallery
├── css/             # Site styles and responsive rules
├── js/              # Site and project interactions
└── projects/        # Standalone interactive demos
```

## Personalise

Update the social links and contact details in the HTML files before sharing publicly. If you want a downloadable resume, add the PDF at `assets/resume/Omesh-Giri-Resume.pdf`.

## License

This portfolio is a personal showcase. Reuse the ideas freely, but replace the personal content, images and branding with your own.
