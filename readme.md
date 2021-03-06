![Cover Art](https://alain.xyz/blog/raw-webgpu/assets/cover.jpg)

# πΊ WebGPU Seed

[![License][license-img]][license-url]
[![Unit Tests][travis-img]][travis-url]

A WebGPU repo you can use to get started with your own renderer.

- [π³ Codepen Example](https://codepen.io/alaingalvan/pen/GRgvLGw)

- [π¬ Blog Post](https://alain.xyz/blog/raw-webgpu)

## Setup

First install:

- [Git](https://git-scm.com/)

- [Node.js](https://nodejs.org/en/)

- A Text Editor such as [Visual Studio Code](https://code.visualstudio.com/).

Then type the following in any terminal your such as [VS Code's Integrated Terminal](https://code.visualstudio.com/docs/editor/integrated-terminal).

```bash
# π Clone the repo
git clone https://github.com/alaingalvan/webgpu-seed

# πΏ go inside the folder
cd webgpu-seed

# π¨ Start installing dependencies, building, and running at localhost:8080
npm start
```

> Refer to [this blog post on designing web libraries and apps](https://alain.xyz/blog/designing-a-web-app) for more details on Node.js, packages, etc.

## Project Layout

As your project becomes more complex, you'll want to separate files and organize your application to something more akin to a game or renderer, check out this post on [game engine architecture](https://alain.xyz/blog/game-engine-architecture) and this one on [real time renderer architecture](https://alain.xyz/blog/realtime-renderer-architectures) for more details.

```bash
ββ π node_modules/   # πΆ Dependencies
β  ββ π gl-matrix      # β Linear Algebra
β  ββ π ...            # π Other Dependencies (TypeScript, Webpack, etc.)
ββ π src/            # π Source Files
β  ββ π index.html     #  π Main HTML file
β  ββ π renderer.ts    # πΊ Triangle Renderer
ββ π .gitignore      # ποΈ Ignore certain files in git repo
ββ π package.json    # π¦ Node Package File
ββ π license.md      # βοΈ Your License (Unlicense)
ββ πreadme.md        # π Read Me!
```


[license-img]: https://img.shields.io/:license-unlicense-blue.svg?style=flat-square
[license-url]: https://unlicense.org/
[travis-img]: https://img.shields.io/travis/com/alaingalvan/webgpu-seed.svg?style=flat-square
[travis-url]:https://www.travis-ci.com/github/alaingalvan/webgpu-seed
