# Words That Feel Like Music

A modern, mobile-first React + Vite creative platform for original Shayari, poetry, quotes and song discovery.

## Run locally

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## Architecture

- `src/main.jsx` — routes, content models, components and interactions.
- `src/styles.css` — responsive visual system.
- Content is currently local arrays, making it straightforward to replace with an API/database later.
- Hash routing keeps the demo dependency-light while remaining easy to migrate to React Router or a backend.

## Included

- Home, Shayari, Poetry, Songs, Search, About and post detail modal.
- 12 original Shayari posts, 8 original poems and 8 song recommendations.
- Category filtering, search, copy-to-clipboard, Web Share API, external song links and responsive navigation.
- No copyrighted song lyrics are included.
