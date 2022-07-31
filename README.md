# preact-express-starter

(Not yet finished, see "todo" section)

Starter app that builds a Preact single page application, bundled with an
express application. [Featured on Awesome Preact](https://github.com/preactjs/awesome-preact)

Adapted in part from the official [Preact typescript template](https://github.com/preactjs-templates/typescript). Includes

-   PWA + offline support with service workers (part of template)
-   Code splitting on routes / opt in on components (part of template)
-   Express API with shared response types
-   Sass typescript class support
-   Docker support
-   [preact-testing-library](https://github.com/testing-library/preact-testing-library) over the enzyme default

## ToDo

-   Add UI Component Unit Tests
-   Add Cypress Integration Test
-   Add Express
-   Add Express Unit Tests

## Improvements

-   routes need to be default exports, it's eh to have half of the react components
    be default exports, and the others named exports. Would like more manual
    control over how code splitting functions
-

## Notes

-   Why preact over react? - [link](https://preactjs.com/)

## CLI Commands

-   `npm run dev`: Run a development, HMR server for the preact app.

-   `npm run serve`: Run a production-like server for the preact app.

-   `npm run build`: Production-ready build for the preact app.

-   `npm run lint`: Pass TypeScript files using ESLint

-   `npm run test`: Run Jest test suite

For detailed explanation on how preact things work, checkout the [CLI Readme](https://github.com/developit/preact-cli/blob/master/README.md).
