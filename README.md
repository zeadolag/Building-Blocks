# Body Builder

A training, food and budget tracker that runs in the browser and can be added to your phone's home screen.

- **Train:** your weekly split, sets and reps, drop sets, supersets, a rest timer, warm-ups, stretches and a how-to for each exercise
- **Eat:** meals by slot, a food calculator with about 80 ingredients, a meal builder, and calorie and protein targets
- **Body:** weight log with weekly averages, and a calculator for calorie and protein targets
- **Spend:** products by store, with weekly, two-week and monthly costs

Everything is stored on your own device (in the browser's local storage). Nothing is sent to a server, and every user has their own data. Use **Settings → Download backup** to keep a copy.

## Open it

https://zeadolag.github.io/Building-Blocks/

On iPhone: open it in Safari, tap **Share → Add to Home Screen**.
On Android: open it in Chrome, tap **⋮ → Add to Home screen** (or **Install app**).

## Files

| File | What it is |
|---|---|
| `index.html` | The whole app: layout, styles and code in one file |
| `manifest.webmanifest` | App name, colours and icons for the home screen |
| `sw.js` | Service worker that saves the app so it opens offline |
| `icons/` | App icons |

When you change `index.html`, also bump `VERSION` in `sw.js` so phones load the new version.
