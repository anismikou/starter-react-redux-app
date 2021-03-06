## Overview

A webpack and React based minimal app with :

-   Development mode supports HMR for easy inspection of code changes
-   Support for Redux, React Router and styled-components
-   Jest/Enzyme testing
-   GitLab CI configuration
-   Normalize.css reset

Written in Typescript and formatted using ESLint and Prettier

## Installation

Fork the repository and run `npm ci` on the folder in your terminal. Build your app on top!

## NPM Commands

### App Controls

-   npm start : Builds in dev mode (DevTools and HMR enabled) and starts a local server
-   npm run build : Build the app in the /dist folder in production mode

### Testing

-   npm run lint : Runs ESLint validation
-   npm run test : Runs Jest validation
-   npm run coverage : Runs Jest validation with codebase coverage output
-   npm run update-snapshots : Updates Jest snapshots

### Utility

-   npm run analyze-json : Analyzes webpack bundle (size and placement of modules) and serves results on a local server
-   npm run analyze-lines : Analyzes repo by lines per extension (node_modules excluded)
