# CrewKit Consumables

Standalone gels and consumables check app for the truck driver. Part of the CrewKit suite.

- Load the Sunbelt sheet (PDF) or paste the delivery list; gels and consumables are sorted onto two lists.
- Swipe right when a pack is used; it goes on the order list.
- Send the order (Share or Copy), then tap Arrived when the delivery turns up.
- Menu → Report a problem sends the log and the job's data back for fixing.

One self-contained `index.html`. Data stays on the phone (localStorage, key `crewkit-consumables:v1`).
`sw.js` keeps it working offline once opened; `manifest.webmanifest` and the icons make it a Home Screen app.
Served by GitHub Pages from `main`.
