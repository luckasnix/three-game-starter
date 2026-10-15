# Three.js Game Starter

A TypeScript starter for 3D game development using Three.js, Vite, and Tauri. Run in the browser or build for desktop.

## 🛠️ Built with

- [TypeScript](https://www.typescriptlang.org) keeps game code typed and maintainable.
- [Node.js](https://nodejs.org) provides the development runtime.
- [pnpm](https://pnpm.io) manages dependencies and runs project scripts.
- [Vite](https://vite.dev) runs the development server and creates production web builds.
- [Three.js](https://threejs.org) provides the 3D rendering foundation.
- [Three.js Gamepad Controls](https://github.com/luckasnix/three-gamepad-controls#readme) provides gamepad input for gameplay and integrates with Three.js controls.
- [Rapier](https://rapier.rs) handles 3D physics simulation.
- [Tauri](https://v2.tauri.app) runs and packages the game as a desktop application.

## 🚀 Getting started

Install [Node.js](https://nodejs.org) and [pnpm](https://pnpm.io/installation) using the versions specified in [`.nvmrc`](./.nvmrc) and [`package.json`](./package.json), respectively. Run the following commands from the project root.

Install dependencies:

```bash
pn install
```

Start the web development server:

```bash
pn dev
```

Create a production web build:

```bash
pn build
```

Preview the production web build locally:

```bash
pn preview
```

The development server is available at [http://localhost:1420](http://localhost:1420).

To run or build the desktop application, also install Rust and the dependencies for your operating system by following the [Tauri prerequisites](https://v2.tauri.app/start/prerequisites/).

Run the desktop application in development:

```bash
pn tauri dev
```

Create a production desktop build:

```bash
pn tauri build
```

## 📄 License

Licensed under the [MIT License](./LICENSE.md).
