# QoL Tools

A plugin-based system tray daemon for personalizing your desktop across macOS and Linux. One install, your rules.

[qol-tray](https://github.com/qol-tools/qol-tray) is the core daemon. It runs a local web UI where you can install plugins, bind hotkeys, and configure everything. Plugins are standalone Rust binaries that extend what your desktop can do.

## Plugins

Plugins live in `plugin-*` repos and are discoverable from the built-in store. Current plugins cover window switching, app launching, keyboard remapping, window management, screen recording, and more.

Want to build one? Start from [plugin-template](https://github.com/qol-tools/plugin-template).

## Shared libraries

The `qol-*` repos are shared Rust crates used across the ecosystem. They compile to both native and WebAssembly where applicable.
