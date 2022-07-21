# Missing declaration file for "tailwindcss/resolveConfig"

This repo provides a proproduction of the issue indicating that no Typescript types are provided for `tailwindcss/resolveConfig`. Because of this when you try to use the `resolveConfig` method as described in the documentation (https://tailwindcss.com/docs/configuration#referencing-in-java-script) you get the following type error "Could not find a declaration file for module 'tailwindcss/resolveConfig'".

## Reproduction

Trying to run `npm start` or `npm run build` will emit a type error.

Additionally navigating to `src/index.ts` will show an error indication in most text editors (I'm using VSCode)
