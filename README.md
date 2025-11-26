# Achieving Adoption of Solid at Scale

Static microsite for the Solid Symposium 2026 session led by Jesse Wright. It shares the session abstract, participation guidelines, challenge submission form, and organiser details.

## Live site

- **Production**: https://sosy2026-solid-at-scale.jeswr.org/

## Project structure

- `index.html` – single-page layout with hero, scope, submission, organiser, and partners sections.
- `assets/css/styles.css` – Space Grotesk/Inter driven styling, responsive layout rules, and component-level tweaks.
- `assets/images/` – partner logos, Solid branding, and organiser portrait assets.

## Local development

1. Clone the repo: `git clone https://github.com/jeswr/sosy2026-solid-at-scale.git`
2. Open the folder in your editor of choice.
3. Launch a static server (e.g., `npx serve`, `python -m http.server`, or VS Code Live Server) from the repo root.
4. Visit the displayed localhost URL, typically `http://127.0.0.1:8000/` or `http://localhost:3000/`.

## Deployment notes

- Site is built as pure HTML/CSS with no build step, making it suitable for GitHub Pages or any static host.
- The live instance at `sosy2026-solid-at-scale.jeswr.org` is deployed via GitHub Pages behind a custom domain.
- Update `index.html` (and corresponding assets) before pushing to `main`; deployments automatically pick up changes once published.

## Contributing

Please open an issue or pull request describing the change you would like to make. For larger edits (new sections, rewrites), feel free to discuss via issues first.

## License

This project is released under the [MIT License](LICENSE). Feel free to reuse or adapt with attribution per the license terms.
