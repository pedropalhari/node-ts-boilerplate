# node-ts-boilerplate

Boilerplate for starting node.js and typescript servers already with yarn.

It uses `tsc` for typechecking and `swc` for compiling typescript. In that way it compiles much faster and you don't need to treat double errors (as most people use an editor with a typescript server and it already outputs errors).

<sub><sup>note: `swc` is ~10x faster than `tsc`.</sup></sub>

## Installing

`npx degit pedropalhari/node-ts-boilerplate my-project`

## Commands

- `yarn`: install basic dependencies
- `yarn dev`: starts the typescript compiler (`swc`) and type checker (`tsc --noEmit`) on watch mode
- `yarn start`: runs the distributed copy on `dist/index.js`
- `yarn build`: runs `swc` for building

### Extra-commmands

- `yarn typecheck`: typechecks the project using `tsc --noEmit`. Useful for catching bugs that slipped through development.
