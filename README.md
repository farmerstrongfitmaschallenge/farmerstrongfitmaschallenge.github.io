# Farm Fitmas Challenge leaderboard

Leaderboard page for the Farmer Strong Farm Fitmas Challenge (2 Nov to 12 Dec 2026).

`index.html` reads the **Web feed** tab of the Farm Fitmas Google Sheet, published to the web as CSV
(names and points only), and refreshes every 5 minutes. Nothing to build or run: GitHub Pages serves the file as it is.

- Overall board: everyone with points, top 3 on a podium. Ties share a place.
- This week: the current week's top 10 (`WEEKLY_TOP` in the script).
- "Updated" comes from the sheet's last change; "Classes counted up to" from the latest class in the last TeamUp upload.
- The points list under "How to earn points" is plain HTML: edit it if the values change.
