# Venture project: Basics

```sh
yarn install
```

## 🚀 Project Structure

Inside of the project, you'll see the following folders and files:

```
└── 📁venture
    └── 📁.vscode
        └── extensions.json
        └── launch.json
    └── README.md
    └── astro.config.mjs
    └── package.json
    └── 📁public
        └── favicon.svg
    └── 📁src
        └── 📁components
            └── Button.astro
            └── Card.astro
            └── Container.astro
            └── Link.astro
            └── 📁navigation
                └── MenuIcon.astro
                └── MenuItems.astro
                └── Navigation.astro
                └── navbar.astro
        └── env.d.ts
        └── 📁pages
            └── 404.astro
            └── index.astro
    └── tailwind.config.mjs
    └── tsconfig.json
    └── yarn.lock
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                | Action                                           |
| :--------------------- | :----------------------------------------------- |
| `yarn install`         | Installs dependencies                            |
| `yarn dev`             | Starts local dev server at `localhost:4321`      |
| `yarn build`           | Build your production site to `./dist/`          |
| `yarn preview`         | Preview your build locally, before deploying     |
| `yarn astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `yarn astro -- --help` | Get help using the Astro CLI                     |

