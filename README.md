# JΓΈrgen Lohne website

## π About

A very WIP Personal website / portofolio built using [Astro](https://astro.build/) and [TailwindCSS](https://tailwindcss.com/)

## β Tech stack

This project uses Astro components, styling is done with TailwindCSS and code formating is done by prettier.

## π Project Structure

Using the standard Astro project structure, you'll see the following folders and files:

```
/
βββ public/
β   βββ favicon.svg
βββ src/
β   βββ components/
β   β   βββ Card.astro
β   βββ layouts/
β   β   βββ Layout.astro
β   βββ pages/
β       βββ index.astro
βββ package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## π§ Commands

All commands are run from the root of the project, from a terminal:

| Command                | Action                                           |
| :--------------------- | :----------------------------------------------- |
| `npm install`          | Installs dependencies                            |
| `npm run dev`          | Starts local dev server at `localhost:3000`      |
| `npm run build`        | Build your production site to `./dist/`          |
| `npm run preview`      | Preview your build locally, before deploying     |
| `npm run astro ...`    | Run CLI commands like `astro add`, `astro check` |
| `npm run astro --help` | Get help using the Astro CLI                     |

## π Helpfull links

[Astro Documentaion](https://docs.astro.build)

[Tailwind Documentation](https://tailwindcss.com/docs/installation)

[Tailwind Cheat Sheet](https://tailwindcomponents.com/cheatsheet/)
