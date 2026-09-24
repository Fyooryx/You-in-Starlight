# You in Starlight ♡

> An interactive, mobile-first romantic experience written in HTML, CSS, and vanilla JavaScript.

**Live demo:** Deploy this repository to Vercel and connect your production domain.

## ✦ About

**You-in-Starlight** is a single-page interactive experience built around a small animated universe:

- Canvas-based starfield
- Constellation animation
- Particle-built heart
- Floating hearts and tap effects
- Typewriter message reveal
- Optional Web Audio sound effects
- Touch / pointer interaction
- Replay and pause handling
- Reduced-motion support for accessibility

The project has **no framework and no runtime dependency installation**. It is designed to run as a static website.

## ✦ Project Structure

```text
You-in-Starlight/
├── index.html      # Main application
├── README.md       # Project documentation
├── LICENSE         # MIT license
└── .gitignore      # Local/tooling files excluded from Git
```

## ✦ Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Canvas 2D API
- Web Audio API
- Pointer Events API

No build step is required.

## ✦ Run Locally

Because this is a static site, you can open `index.html` directly in a browser.

For a local HTTP server, any static file server works. Example with Python:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## ✦ Deploy to Vercel

1. Push the repository to GitHub.
2. In Vercel, create a new project and import **Fyooryx/You-in-Starlight**.
3. Keep the project root as the repository root.
4. No framework or build command is required for this static site.
5. Deploy.

Vercel can serve static sites without a framework or build step. A lowercase root `index.html` is used as the homepage entry point.

## ✦ Browser Notes

The experience uses modern browser APIs:

- Canvas 2D for rendering
- Pointer Events for touch / mouse input
- Web Audio for optional sound
- `prefers-reduced-motion` for reduced animation settings

Sound is intentionally opt-in and starts after user interaction, which follows normal browser autoplay restrictions.

## ✦ License

This project is licensed under the **MIT License**. See [LICENSE](LICENSE).

---

Made with starlight. ✦
