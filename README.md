# Hokkaido in Winter — GitHub Pages itinerary

A mobile-friendly, single-file website for a February 16–25, 2027 Hokkaido trip. It includes daily itineraries, transportation strategy, food priorities, Google Maps links, a booking checklist, and print/PDF support.

## Publish on GitHub Pages

1. Create a new GitHub repository, such as `hokkaido-2027`.
2. Upload `index.html` and `.nojekyll` to the repository root (you can upload this README too).
3. In the repository go to **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
5. After publication, your site is usually at `https://YOUR-USERNAME.github.io/hokkaido-2027/`. Publication can take a few minutes.

## Edit the trip

Open `index.html` in any editor. Near the bottom, look for `const days`, `const food`, `const transfers`, and `const bookings`. Edit those arrays and commit changes; GitHub Pages will republish.

The checkboxes in the booking checklist use your browser's `localStorage`. They do **not** sync across devices and will reset in a different browser or private mode. The HTML does not include personal booking confirmation numbers or credentials. Do not put those on a public GitHub Pages site.

## Planning notes

- All dates and times are in **Japan Standard Time**.
- Activities marked **Verify** require a fresh check of February 2027 operating hours, reservations or transport schedules. The example transport times come from published winter service patterns but have **not** been ticketed.
- The Feb 18 Biei day can be swapped with Feb 19 to accommodate tour availability.
- Hakodate after Feb 25 is deliberately not planned yet.
- External links require a connection, but the itinerary itself loads offline once the HTML file is saved.

## Local preview

Double-click `index.html`, or run `python3 -m http.server 8000` inside this folder and open `http://localhost:8000`.
