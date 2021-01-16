# node-ts-boilerplate

Boilerplate for starting node.js and typescript servers already with yarn.

_Current Node version targeted, v14+._

## Installing

`npx degit pedropalhari/node-ts-boilerplate my-project`

## Commands

- `yarn start`: runs the distributed copy on `dist/index.js`
- `yarn dev`: starts the typescript compiler on watch mode (`tsc -w`)
  - in `tsconfig.json` you can set the properties on `outDir` and `rootDir`
- `yarn build`: builds the code, incrementally
