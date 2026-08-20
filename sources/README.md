# Sources

Raw, immutable clips. Drop things here. Never edit files once saved.

## How to add a source

**Option 1 — URL in chat:**
Paste a link and say "ingest this." Claude fetches it, extracts what matters, updates the wiki,
and saves the raw content here automatically.

**Option 2 — Save a file here manually:**
Use a browser extension (MarkDownload, Obsidian Web Clipper, etc.) to save a page as markdown.
Drop it in this folder with the naming format: YYYY-MM-DD-short-title.md
Then say "ingest [filename]" and Claude does the rest.

## What happens on ingest

Claude reads the source, updates relevant wiki pages, updates index.md if needed, and appends
to log.md. The raw file stays here untouched as the source of truth.
