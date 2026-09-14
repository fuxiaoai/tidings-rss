# Tidings asset provenance

The product screenshots in this directory are the official, version-controlled Tidings website assets copied from `tidings-web/public/assets/screenshots/` on 2026-07-28. They show real Tidings interface captures; no synthetic UI was generated for this repository.

The import preview at `../tidings-import-news-research.png` is generated separately by `tools/capture_tidings_import.cjs`. That script launches the local Tidings application with an isolated temporary profile, imports the published News and Research OPML files through the production IPC path, waits for live refresh results, and captures the resulting application window.

`freshrss-sync-zh.webp` and `global-search-zh.webp` are Chinese product screenshots supplied for the README on 2026-08-20. They were converted from PNG to WebP without content edits.

`podcast-player-zh.png`, `reading-highlight-ai-zh.png`, and `reading-notes-zh.png` are Chinese product screenshots supplied by the maintainer on 2026-09-14 for the September feature update. They are copied from the supplied PNG files without conversion or content edits. Both README languages use these same Chinese interface captures.

Tidings product assets remain subject to the Tidings product's own rights. The catalog metadata and repository-maintained files are released under CC0-1.0.
