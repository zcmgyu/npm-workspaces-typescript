## Description

A Typescript monorepo project using Npm Workspaces.
In this monorepo, I'm adding a `shared` package as a dependency in another package.

## Usage

> $ npm install
>
> $ npm run compile

> $ cd packages/main
>
> $ npm run debug

- `compile` command build your project references (packages/main and packages/shared)
- Every time you run change code in `.ts` file, no need to recompile project.


## Refs

https://stackoverflow.com/a/54772741/4642316
