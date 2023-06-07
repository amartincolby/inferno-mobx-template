# inferno-mobx-template
A starter template for an InfernoJS project using MobX and Parcel.

React's Hooks are essentially obviated when leveraging MobX. The combination of
Inferno and MobX is still smaller than just React, and developers get the
benefits of a fully-featured state management system.

This repo is forward-facing. Yarn PnP is used and all dependencies are
aggressively updated. The development environment is Node 20.

Dependencies never use ^

## To enable Yarn PnP

Install Node 20.x.
run `enable corepack`

## Author's Opinions

- Keep your file structure as flat as possible.
  - Rely on robust, descriptive filenames instead of folders.
  - You don't want forty-two different index.ts files.