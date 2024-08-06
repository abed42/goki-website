# Goki website

![goki-website-screenshot](/public/goki-website-screenshot.png?version%3D1722984804526)

## 🎨 Designs

Check out the figma [design here](https://www.figma.com/design/5K1sShH1TgFUI3jPdn4nAE/Goki--minimal-website?node-id=0-1&t=Cqfj3iShJEP1WuGD-0)

## 🚀 Project Structure

```text
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

If you use yarn, run
| Command | Action |
| :------------------------ | :----------------------------------------------- |
| `yarn` | Installs dependencies |
| `yarn dev` | Starts local dev server at `localhost:4321` |
| `yarn build` | Build your production site to `./dist/` |
| `yarn preview` | Preview your build locally, before deploying |
| `yarn astro ...` | Run CLI commands like `astro add`, `astro check` |
| `yarn astro -- --help` | Get help using the Astro CLI |

For the npm users, run
| Command | Action |
| :------------------------ | :----------------------------------------------- |
| `npm install` | Installs dependencies |
| `npm run dev` | Starts local dev server at `localhost:4321` |
| `npm run build` | Build your production site to `./dist/` |
| `npm run preview` | Preview your build locally, before deploying |
| `npm run astro ...` | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI |

## 👀 Noob?

Check out the [astro documentation here](https://docs.astro.build)
