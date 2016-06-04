A proof-of-concept Camlistore browser app.
It should support searching, listing results, and listening for updates.

## Questions this is meant to help answer

### Packaging

  - What is the most sane way to distribute libraries? NPM is probably the most convenient for people.
  - Demontrate a vendoring workflow in the main app.
  - What's the most sane way to load stuff? System.js unpacked mode? Closure compiler or Rollup? 

### Code

  - We like the TypeScript?
  - UI element encapsulation? It should be possible to encapsulate an element entirely, including any CSS, images, etc.
    - Polymer, React?
  - Shared caching/transports?
