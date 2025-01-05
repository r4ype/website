# Quic Start a dev server

```sh
pnpm install
pnpm dev
```

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/r4ype/website)
[![Open with CodeSandbox](https://assets.codesandbox.io/github/button-edit-lime.svg)](https://codesandbox.io/p/sandbox/github/r4ype/website)
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/r4ype/website)

> 🌸 **check out this website at:** https://pawrsa.vercel.app/

## 🚀 Project Structure

heres some important files:

```text
/
├── public/
│   └── *.svg
│       *.jpg
├── src/
│   ├── components/
│   │   └── about.astro
│   │       skills.astro
│   └── pages/
│       └── index.astro
│   styles/
│   └── global.css
└── package.json
```

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command              | Action                                           |
| :------------------- | :----------------------------------------------- |
| `pnpm install`       | Installs dependencies                            |
| `pnpm dev`           | Starts local dev server at `localhost:4321`      |
| `pnpm run build`     | Build your production site to `./dist/`          |
| `pnpm run preview`   | Preview your build locally, before deploying     |
| `pnpm run astro ...` | Run CLI commands like `astro add`, `astro check` |
