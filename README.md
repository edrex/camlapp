Camlapp is a proof-of-concept browser-based Camlistore client app.

## Goals

- Build a browser-based app for Camlistore, which supports searching, listing with thumbnails, and listening for new results.
- Split the app up into modules, and factor out any reuseful functionality into libraries.

## Questions:

- Can a Typescript app be easily broken into modules? Can those modules be redistributed on NPM? [Looks like yes](http://blog.charto.net/node-js/Publishing-TypeScript-based-modules-on-npm/).
- Contracts for interoperable UI elements and shared services? Polymer, Dependency injection, React, ES modules?
- What is the most sane way to load stuff, particularly Typescript? System.js unpacked mode, Closure compiler, Rollup? 

## Other open ended stuff

- Think about signed JS app+library code delivery into camlistore (user signs an "install" claim)
