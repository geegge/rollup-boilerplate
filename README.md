# rollup-boilerplate

boilerplate-code for building a javascript-library

## Featues

-   [rollup.js](https://rollupjs.org) for bundling
-   [prettier](https://prettier.io/) and [eslint](https://eslint.org/) for code-style
-   [babel](https://babeljs.io/) for transpiling
-   [Jest](https://jestjs.io/) for testing
-   [nodemon](https://github.com/remy/nodemon) for a nicer development workflow

## Get started

-   install node-modules with:
    `npm install`

-   you can recompile your library on the fly by using:
    `npm run dev-rollup`
    and check out `./dev/index.html` with a browser (adapt it to your needs)
-   or a little bit more convenient run `npm run dev` and let nodemon run your lib.
    (adapt `./dev/dev.js` to your needs)

-   for testing run `npm test`

-   for building your final lib: `npm run build`

Heavily inspired by:
[https://github.com/algolia/rollup-jest-boilerplate](https://github.com/algolia/rollup-jest-boilerplate)
and
[https://github.com/rollup/rollup-starter-lib](https://github.com/rollup/rollup-starter-lib)
Thanks!
