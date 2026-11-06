# Pocket Playground

Single-file browser games hub (`index.html`, no build step). Live at https://laspapas1212.github.io/pocket-playground/ via GitHub Pages from `main`.

## Rules

- **After every change, commit and push to GitHub (`origin main`)** so the live site updates. The owner asked for this to always happen; don't wait to be asked.
- Every game registers with `game({...})` and gets an `api` whose listeners/timers/loops are cleaned up automatically on restart. Use `api.on/after/every/loop` instead of raw `addEventListener`/`setTimeout`.
- Tile grids use `gridN()` (`minmax(0,1fr)`) so cells never change size.
