# Lazarus builds (for Castle Game Engine)

The purpose of this repo is to package [Lazarus](https://www.lazarus-ide.org/) for various usage across [Castle Game Engine](https://castle-engine.io/) build tools. Similarly to [cge-fpc](https://github.com/castle-engine/cge-fpc), which compiles FPC packaged to ZIP.

Using [GitHub Actions](https://castle-engine.io/github_actions) and release as [GitHub Releases](https://github.com/castle-engine/cge-lazarus/releases/tag/snapshot).

Right now all we really needed are Lazarus builds, as zip, for [Raspberry Pi](https://www.raspberrypi.org/):

- 32-bit Raspberry Pi, meaning _Linux / Arm_.

    Just like [Castle Game Engine supported systems](https://castle-engine.io/download#_system_requirements), this Lazarus build is guaranteed to work on _Raspberry Pi OS (Debian)_ >= _bullseye_.

- 64-bit Raspberry Pi, meaning _Linux / Aarch64_.

    Just like [Castle Game Engine supported systems](https://castle-engine.io/download#_system_requirements), this Lazarus build is guaranteed to work on _Raspberry Pi OS (Debian)_ >= _bookworm_ due to requiring more modern GLIBC.

    These builds should also work on PineTab2 and other [Pine64](https://pine64.org/) devices using _Linux / Aarch64_.

They are built using [arm-runner GitHub action](https://github.com/pguyot/arm-runner-action).

By [Michalis](https://michalis.xyz/).