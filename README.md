# Learning Typescript

## Installing the Compiler

-TypeScript has an official compiler installed through npm.
```
 npm install typescript --save-dev
```
## create tsconfig.json with the recommended settings
```
 npx tsc --init
```
## an example of more things you could add to the tsconfig.json file:
```
{
  "include": ["src"],
  "compilerOptions": {
    "outDir": "./build"
  }
}
```
You can open the file in an editor to add those options. This will configure the TypeScript compiler to transpile TypeScript files located in the src/ directory of your project, into JavaScript files in the build/ directory.

## The compiler is installed in the node_modules directory and can be run with:

```
 npx tsc
```