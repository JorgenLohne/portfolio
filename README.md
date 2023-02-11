# Jørgen Lohne website

## 📙 About

Personal website / portofolio built using [Astro](https://astro.build/) and [TailwindCSS](https://tailwindcss.com/)

## ⚙ Tech stack

This project uses Astro components, styling is done with TailwindCSS and code formating is done by prettier.

## 🚀 Project Structure

Using the standard Astro project structure, you'll see the following folders and files:

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Card.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                | Action                                           |
| :--------------------- | :----------------------------------------------- |
| `npm install`          | Installs dependencies                            |
| `npm run dev`          | Starts local dev server at `localhost:3000`      |
| `npm run build`        | Build your production site to `./dist/`          |
| `npm run preview`      | Preview your build locally, before deploying     |
| `npm run astro ...`    | Run CLI commands like `astro add`, `astro check` |
| `npm run astro --help` | Get help using the Astro CLI                     |

## 🎓 Helpfull links

[Astro Documentaion](https://docs.astro.build)

[Tailwind Documentation](https://tailwindcss.com/docs/installation)

[Tailwind Cheat Sheet](https://tailwindcomponents.com/cheatsheet/)
