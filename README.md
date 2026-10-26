# Folio design mockups

Six design directions for the home screen of **Folio**, a minimalist iOS app for tracking books you want to read, are reading, and have read, with notes and ratings. You can borrow books through Libby or buy them from an indie store.

Every mockup shows the same screen and the same data, so you're only comparing design.

| # | Direction | Approach | Screenshot |
|---|-----------|----------|------------|
| 1 | Margin | Safe · editorial index | [view](screenshots/01-n15.png) |
| 2 | Minimalistic | Safe · reading-log ledger | [view](screenshots/02-minimalistic.png) |
| 3 | Penny Press | Safe · featured card plus grid | [view](screenshots/03-gummy.png) |
| 4 | Space Odyssey | Bolder · night-reading view | [view](screenshots/04-space-odyssey.png) |
| 5 | Neo-Brutalist | Bolder · bookshelf of spines | [view](screenshots/05-neo-brutalist.png) |
| 6 | Cover Light | Bolder, custom · cover-colored header | [view](screenshots/06-offcatalog.png) |

## Viewing

**GitHub Codespaces:** click **Code → Codespaces → Create codespace**. A static server starts on port 8000 and a preview of the gallery (`index.html`) opens. If the preview doesn't open, go to the **Ports** tab and open port 8000.

**Locally:** run `python3 -m http.server 8000` and open http://localhost:8000.

Each mockup is a single self-contained HTML file in `mockups/` with no scripts. Book covers come from [Open Library](https://openlibrary.org/dev/docs/api/covers). If a cover can't load, a drawn cover with the title shows instead.

## License

MIT. Book cover images belong to their publishers and are loaded from Open Library at view time. They are not included in this repository.
