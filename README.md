# node-ts-boilerplate

Boilerplate for starting node.js and typescript servers already with yarn.

_Current Node version targeted, v14+._

## Installing

`npx degit pedropalhari/node-ts-boilerplate my-project`

## Commands

- `yarn start`: runs the `index.ts` file using `tsm` and source maps from Node (using `--enable-source-maps`)
- `yarn dev`: starts the typescript compiler on watch mode and without emitting any JS files (`tsc -w --noEmit`)
  - in `tsconfig.json` you can set the properties on `outDir` and `rootDir`
- `yarn build:js`: builds the code, incrementally
