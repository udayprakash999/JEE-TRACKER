# JEE-TRACKER (JEE Main 2027 Revision & Practice Tracker)

A focused, client-side revision and practice tracker built for **JEE Main 2027** preparation across Physics, Chemistry, and Mathematics.

## Key Features

- **Organized Multi-View Workspace**: Switch cleanly between **Chapters**, **Urgent & Stats**, and **Backup & Sync** instead of scrolling through everything at once.
- **Revision & Practice Tracking**: Track `Rev 1`, `Rev 2`, and `Rev 3` (with automatic revision dates), **PYQs** completion + solved question counts, **COMPLETED** status, and per-chapter quick notes.
- **ROI & Urgency Filtering/Sorting**: Filter by subject, class (`11th` / `12th`), status, or ROI/tag, and sort by **Highest ROI First** or **Most Urgent / Overdue**.
- **Purple Dark & Light Modes**: Toggle between dark and light purple themes persisted in `localStorage`.
- **JSON Backup & Restore + Tab-Close Guard**: Export and restore `.json` backups (with merge/overwrite support) in case `localStorage` is cleared, backed by an always-on tab-close warning.

## Hosting on GitHub Pages

1. Add `index.html` and `README.md` to the root of the repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**, choose your main branch and `/ (root)`, then save.
4. Your app will be available at `https://<your-username>.github.io/JEE-TRACKER/`.

## Data & Privacy Note

All chapter progress, revision dates, notes, and theme preferences are stored locally in your browser's `localStorage`. Export a `.json` backup regularly—especially before clearing browser data or switching between `file://` and your hosted GitHub Pages URL.
