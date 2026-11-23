# Kanban Parts System

Browser-based parts list, status board and kanban card printing. Open the page in Chrome or Edge, press **Choose Shared Folder**, and pick the shared Kanban System folder on the network drive. All parts data (`kanban-data.json`) and photos stay on that drive; this repo holds only the page.

- **Parts**: search, filter, edit, drawings and related variants
- **Board**: drag parts between statuses
- **Print queue**: bundled by paper color, 4 cards per sheet, double-sided (flip on long edge)
- **To Do**: what needs attention
- **Admin**: add `#admin` to the web address (archive and restore, lists, backup, Excel export)

Never commit `kanban-data.json`, images or backups (they are in `.gitignore`).
