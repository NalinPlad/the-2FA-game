# The 2FA Game

An Astro site with a browser-based 2FA game.

## Development

```sh
npm install
npm run dev
```

Open http://localhost:8000. Edit `src/pages/index.astro` to change the page,
styles, or game script. Astro updates the browser automatically when you save.
The game script stays inline to preserve its existing browser behavior.

## Production

```sh
npm run build
npm run preview
```

Deploy the generated `dist/` directory to your static host. Files in `public/`,
including the custom-domain `CNAME`, are copied into the build output.

Astro 7.3 supports the project's Node.js 22.14 environment. The dependency
stays on the 7.3 release line because newer Astro releases require newer Node.js.
