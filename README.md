# Lazarus builds (for Castle Game Engine)

Build and package [Lazarus](https://www.lazarus-ide.org/) for usage across [Castle Game Engine](https://castle-engine.io/). Similarly to [castle-fpc](https://github.com/castle-engine/castle-fpc), which compiles FPC packaged to ZIP.

Using [GitHub Actions](https://castle-engine.io/github_actions) and release as [GitHub Releases of the `snapshot` tag](https://github.com/castle-engine/castle-lazarus/releases/tag/snapshot).

Usage:

- We later use these Lazarus builds during _Castle Game Engine_ build process.

- We _do not_ bundle Lazarus with _Castle Game Engine_ itself, for now. (But it is an option in the future, would be useful for people that use [custom components at CGE design-time](https://castle-engine.io/custom_components) as they require to rebuild editor which in turn depends on Lazarus installed.)

The core is a script `build_lazarus` which compiles Lazarus and packages it to ZIP. You can also run it interactively, on your system, to test it.

By [Michalis](https://michalis.xyz/).
