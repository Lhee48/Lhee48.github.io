# Tech Stack
- Bun
- SvelteKit
- TypeScript
- TailwindCSS

## Developing

Once you've created a project and installed dependencies with `bun install` 
start a development server:

```bash
bun --bun run dev -- --open
```

## Building

To build for production, you'll need to add the right SvelteKit adapter.

```bash
bun add -D svelte-adapter-bun
```

Now, change your ```bash svelte.config.js```

```js
import adapter from "svelte-adapter-bun";
```

To create a production version of your app:

```bash
bun run build
```
