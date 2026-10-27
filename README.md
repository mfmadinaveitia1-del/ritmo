# RITMO · Germany Dance Events

Interactive iPhone-style prototype for discovering salsa (línea & cubana), bachata, kizomba, Brazilian zouk and tango events in 12 German cities.

**Live demo:** https://mfmadinaveitia1-del.github.io/ritmo/

## Features
- City, date and search filters, multi-select dance styles, plus a filter sheet (sort, max price, beginner-friendly)
- Discover sections: Featured, Socials and Dance Festivals
- List view and stylized Germany map
- Favorites, demo tickets and created events saved in the browser (localStorage)
- Share action
- Private owner workspace for managing event sources, with JSON import/export

## Notes
- Hamburg shows **real events** (salsa, bachata, Brazilian zouk, forró) through the end of November 2026, including its weekly socials collected from public listings, each linking to its organizer page. **Dance Festivals** lists real upcoming festivals across Germany (Nov 2026 – May 2027), each linking to its official page. Other cities' socials still use **fictional sample data**; bookings there are simulated and no payments are taken.
- The owner access code is a client-side demo gate only, not real security.
- Single self-contained `index.html`; no build step.
