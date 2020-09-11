# node-ts-boilerplate

Boilerplate for starting node.js and typescript servers already with yarn.

**Now using swc**.

## Installing

`npx degit pedropalhari/node-ts-boilerplate my-project`

## Commands

- `yarn`: install basic dependencies
- `yarn start`: runs the distributed copy on `dist/index.js`
- `yarn check`: runs typescript for typechecking (`tsc --noEmit`)
- `yarn dev`: starts the typescript compiler on watch mode (`tsc -w`)
  - in `tsconfig.json` you can set the properties on `outDir` and `rootDir`
