qwik-app

A simple [Qwik][10] demo app

[![MIT license](https://img.shields.io/badge/License-MIT-brightgreen.svg)](LICENSE)
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.0-4baaaa.svg)][2]
[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)][5]
[![Editor Config](https://img.shields.io/badge/Editor%20Config-1.0.1-crimson.svg)][4]
[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg)][3]

## Install

  ```sh
  git clone https://github.com/roalcantara/qwik-app
  ```

### Dependencies

- [git][6]
- [gitlint][7]
- [pre-commit][8]
- [pnpm][9]

## Usage

- `pnpm start` uses [Vite's development server][11] to server-side render (SSR) the output
- `pnpm preview` creates a production build of the client modules and run a local server (a convenience to locally preview a production build)
- `pnpm build` uses Typescript to run a type check on the source code and generates client and server modules
- `pnpm qwik add` adds additional [integrations][12]

## Project Structure

This project is using Qwik with [QwikCity](https://qwik.builder.io/qwikcity/overview/). QwikCity is just an extra set of tools on top of Qwik to make it easier to build a full site, including directory-based routing, layouts, and more.

Inside your project, you'll see the following directory structure:

```
├── public/
│   └── ...
└── src/
    ├── components/
    │   └── ...
    └── routes/
        └── ...
```

- `src/routes`: Provides the directory based routing, which can include a hierarchy of `layout.tsx` layout files, and an `index.tsx` file as the page. Additionally, `index.ts` files are endpoints. Please see the [routing docs](https://qwik.builder.io/qwikcity/routing/overview/) for more info.

- `src/components`: Recommended directory for components.

- `public`: Any static assets, like images, can be placed in the public directory. Please see the [Vite public directory](https://vitejs.dev/guide/assets.html#the-public-directory) for more info.

## Acknowledgements

- [Standard Readme][5]
- [Conventional Commits][7]
- [Qwik][10]
- [Vite][11]
- [Unveiling Qwik 1.0][13]

## Contributing

- Bug reports and pull requests are welcome on [GitHub][0]
- Do follow [Editor Config][4] rules.
- Do follow [Git lint][7] rules.
- Everyone interacting in the project’s codebases, issue trackers, chat rooms and mailing lists is expected to follow the [Contributor Covenant][2] code of conduct.

## License

The project is available as open source under the terms of the [MIT][1] [License](LICENSE)

[0]: https://github.com/roalcantara/qwik-app
[1]: https://opensource.org/licenses/MIT "Open Source Initiative"
[2]: https://contributor-covenant.org "A Code of Conduct for Open Source Communities"
[3]: https://conventionalcommits.org "Conventional Commits"
[4]: https://editorconfig.org "EditorConfig"
[5]: https://github.com/RichardLitt/standard-readme "Standard Readme"
[6]: https://git-scm.com "Git"
[7]: https://jorisroovers.com/gitlint "git commit message linter"
[8]: https://pre-commit.com "A framework for managing and maintaining multi-language pre-commit hooks"
[9]: https://pnpm.io "pnpm: Fast, disk space efficient package manager"
[10]: https://qwik.io "Qwik"
[11]: https://vitejs.dev "Vite"
[12]: https://qwik.builder.io/qwikcity/guides/static-site-generation "Qwik Integrations and deployment"
[13]: https://youtu.be/NjKOAbWqOM4 "Unveiling Qwik 1.0"
