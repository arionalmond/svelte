# svelte

This is a generated project, I deleted the generated `README.md` and replaced it with this. The generated was outdated for this process of generating the project..  

[Svelte Docs](https://learn.svelte.dev/tutorial/welcome-to-svelte)  

## Generating Project

`% npm init svelte`
```
Need to install the following packages:
create-svelte@6.3.11
Ok to proceed? (y) y

> npx
> create-svelte

create-svelte version 6.3.11

┌  Welcome to SvelteKit!
│
◇  Where should we create your project?
│    (hit Enter to use current directory)
│
◇  Which Svelte app template?
│  SvelteKit demo app
│
◇  Add type checking with TypeScript?
│  Yes, using TypeScript syntax
│
◇  Select additional options (use arrow keys/space bar)
│  Add ESLint for code linting, Add Prettier for code formatting, Add Playwright for
browser testing, Add Vitest for unit testing
│
└  Your project is ready!

Install more integrations with:
  npx svelte-add

Next steps:
  1: npm install
  2: git init && git add -A && git commit -m "Initial commit" (optional)
  3: npm run dev -- --open

To close the dev server, hit Ctrl-C

Stuck? Visit us at https://svelte.dev/chat

```

## Next Steps
git init before npm install, https://github.com/arionalmond/svelte  
- [x] npm install
- [x] npm run dev -- --open


## Prod Build
- update adapter to [adapter-node](https://kit.svelte.dev/docs/adapter-node)  
- update code in `svelte.config.js` to use node adapter  
- `npm install dotenv`  
- add `.env` file and some env vars  
- `node --env-file=.env build`  
- [deploy](https://kit.svelte.dev/docs/adapter-node#deploying)  
- `npm ci --omit dev`