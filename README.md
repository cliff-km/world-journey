# World Journey

Worldbuilding tools built around MidJourney and GPT.

The hyptothesis of this project is that you might often want to contrain your generated images so that they fit together in one world. This means aligning them by setting constraints, thematic constraints, and stylistic constraints. You could achieve this manually by sticking to the same artists, appending common keywords, etc., but it can become very tedious and troublesome.

To solve this problem, these tools aim to help you define your worlds into sets of GPT directives that can be used to pre-process MidJourney prompts so that GPT will handle the style, thematic, and stylistic constraints.

It uses things I learned from working on https://github.com/cliff-km/prompt-journey

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```bash
# create a new project in the current directory
npm create svelte@latest

# create a new project in my-app
npm create svelte@latest my-app
```

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.
