# Reading app

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/codeyam-ai/reading-app?quickstart=1)

A minimalist mobile app for tracking books you want to read, are reading, and have read, with notes and ratings. You can borrow books through Libby or buy them from an indie store (or a larger retailer when needed). "Folio" in the mockups is a placeholder name.

This is the single repo for the project.

**Current stage: design.** We're choosing a visual direction for the home screen from six mockups. No app code has been written yet.

**Built with Flutter.** The app is planned as a [Flutter](https://flutter.dev) app: iOS first, then Android from the same codebase, with a companion website later. The mockups are static HTML used only to pick a visual direction. The chosen direction will become the Flutter app's theme (`ThemeData`, color and type tokens) and widgets. Flutter code will be added to this repo after the design step.

## Design mockups

Every mockup shows the same screen and the same data, so you're only comparing design.

| # | Direction | Approach | Screenshot |
|---|-----------|----------|------------|
| 1 | Margin | Safe · editorial index | [view](.codeyam/design/screenshots/01-n15.png) |
| 2 | Minimalistic | Safe · quiet, single-focus | [view](.codeyam/design/screenshots/02-minimalistic.png) |
| 3 | Penny Press | Safe · featured card plus grid | [view](.codeyam/design/screenshots/03-gummy.png) |
| 4 | Space Odyssey | Bolder · night-reading view | [view](.codeyam/design/screenshots/04-space-odyssey.png) |
| 5 | Neo-Brutalist | Bolder · bookshelf of spines | [view](.codeyam/design/screenshots/05-neo-brutalist.png) |
| 6 | Cover Light | Bolder, custom · cover-colored header | [view](.codeyam/design/screenshots/06-offcatalog.png) |

## Viewing the mockups

**GitHub Codespaces:** click the **Open in GitHub Codespaces** button above, or **Code → Codespaces → Create codespace**. A static server starts on port 8000 and a preview of the gallery (`index.html`) opens. If the preview doesn't open, go to the **Ports** tab and open port 8000.

**Locally:** run `python3 -m http.server 8000` in the repo root and open http://localhost:8000.

Each mockup is a single self-contained HTML file with no scripts. Book covers come from [Open Library](https://openlibrary.org/dev/docs/api/covers). If a cover can't load, a drawn cover with the title shows instead.

## Repo layout

- `index.html`: gallery of the design mockups
- `.codeyam/design/project_mockups/`: the mockups
- `.codeyam/design/design_systems/`: design systems the mockups draw on
- `.codeyam/`: CodeYam editor project config
- `.devcontainer/`: Codespaces setup

## License

MIT. Book cover images belong to their publishers and are loaded from Open Library at view time. They are not included in this repository.
