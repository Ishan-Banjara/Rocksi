# Rocksi (OBJ Loader Fork)

> **This is a fork of [Rocksi by ndahn](https://github.com/ndahn/Rocksi); a free, browser-based robot arm simulator for educational use. All credit for the original simulator goes to the original author. This fork adds native OBJ + MTL + texture loader support as a contribution back to the educational community.

## About the Original Rocksi

Rocksi is an incredible piece of educational software built by [ndahn](https://github.com/ndahn) for the Robokind Foundation in Germany. It runs entirely in a web browser and lets students program a 3D robot arm visually — no installation, no registration, completely free. 

- 🌐 Official version: https://ndahn.github.io/
- 📖 Source: https://github.com/ndahn/Rocksi
- 📜 License: MIT

## What This Fork Adds

Only one focused change: the "Custom object..." loader now supports `.obj` + `.mtl` + texture images in addition to `.stl`. Everything else is identical to upstream.

### Why This Fork Exists

After noticing that the custom object loader only supported STL files (which lack color/texture data), I extended it to support OBJ with full material support, then submitted the change upstream as a pull request.

**If the upstream PR is merged, this version url will be removed.**

## Accessibility
🔗 https://YOUR-USERNAME.github.io/Rocksi/

## Credits
- **Original simulator**: ndahn and contributors (MIT License)
- **OBJ loader extens