<div align="center">
  <h1>
    👌
    <br>
    Awesome Web Development Resources
  </h1>

![](https://badgen.net/github/last-commit/mrmartineau/awesome-web-dev-resources)

</div>

<details>
  <summary>Table of contents</summary>
<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [General resources](#general-resources)
  - [Finding npm packages](#finding-npm-packages)
- [🎨 CSS](#-css)
  - [CSS-in-JS](#css-in-js)
- [JavaScript](#javascript)
  - [Useful JS links](#useful-js-links)
  - [Framework agnostic packages](#framework-agnostic-packages)
    - [General utilities](#general-utilities)
    - [Async](#async)
    - [Node](#node)
    - [Responsive](#responsive)
    - [Media and Images](#media-and-images)
      - [Image services](#image-services)
    - [Date](#date)
    - [Scrolling](#scrolling)
    - [Carousels](#carousels)
    - [Animation](#animation)
    - [Web workers](#web-workers)
    - [Immutable](#immutable)
    - [Typography](#typography)
    - [Polyfills](#polyfills)
  - [⚛️ React](#-react)
    - [React-specific libs:](#react-specific-libs)
    - [React patterns](#react-patterns)
    - [State management](#state-management)
    - [Server-rendered React](#server-rendered-react)
    - [Static site generators](#static-site-generators)
    - [Microservices/Serverless](#microservicesserverless)
  - [TypeScript](#typescript)
- [Code bundlers](#code-bundlers)
- [Command Line, Terminal and shells](#command-line-terminal-and-shells)
  - [Creating CLI apps](#creating-cli-apps)
  - [CLI apps](#cli-apps)
- [Tooling](#tooling)
  - [Package management and publishing](#package-management-and-publishing)
  - [Commit hooks](#commit-hooks)
- [Testing](#testing)
  - [Code formatting and linting](#code-formatting-and-linting)
- [Progressive Web Apps](#progressive-web-apps)
- [Code Sandboxes](#code-sandboxes)
- [APIs](#apis)
- [JSON](#json)
- [HTML](#html)
- [SVG/Image Media compression](#svgimage-media-compression)
- [SVG](#svg)
- [Conversions and unicode](#conversions-and-unicode)
- [Features and feature detection](#features-and-feature-detection)
- [Performance](#performance)
  - [Performance testing and monitoring](#performance-testing-and-monitoring)
- [Design](#design)
- [Design Systems and documentation](#design-systems-and-documentation)
- [Accessibility (A11y)](#accessibility-a11y)
  - [A11y tools and resources:](#a11y-tools-and-resources)
    - [A11y Chrome extensions](#a11y-chrome-extensions)
- [DevOps](#devops)
  - [Continuous integration](#continuous-integration)
  - [Hosting](#hosting)
  - [Domains](#domains)
- [Design](#design-1)
  - [Typography](#typography-1)
- [IDEs and Text Editors](#ides-and-text-editors)
  - [VSCode](#vscode)
  - [Programming fonts](#programming-fonts)
  - [Code colour schemes](#code-colour-schemes)
- [Regular expressions](#regular-expressions)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

</details>

# General resources

- [Devdocs.io](http://devdocs.io/) - Fast, offline, and free documentation browser for developers. Search 100+ docs in one web app: HTML, CSS, JavaScript, PHP, Ruby, Python, Go, C, C++…
- [DevHints](https://devhints.io/) - cheatsheets for many web technologies
- [Carbon](<https://carbon.now.sh/?bg=rgba(171,%20184,%20195,%201)&t=seti&l=auto&ds=true&wc=true&wa=true&pv=32px&ph=32px&ln=false>) - use this to share images of your code in presentations etc
- [Badgen](https://badgen.net/) ![](https://badgen.net/badge/add/flare)
- [Shields.io](https://shields.io/) - ![](https://img.shields.io/badge/add-flare-green.svg?style=flat-square) to your documentation/readmes
- [Git Flight Rules](https://github.com/k88hudson/git-flight-rules) - A guide for astronauts (now, programmers using Git) about what to do when things go wrong.

## Finding npm packages

- [pika](https://www.pikapkg.com/) a searchable catalog of modern "module" packages on npm
- [npms](https://npms.io/) A better and open source search for node packages
- [emma](https://github.com/maticzav/emma-cli) - 📦 Terminal assistant to find and install node packages
- [npmvet](https://github.com/harksys/npmvet) - A simple CLI tool for vetting npm package versions

Use [Bundlephobia](https://bundlephobia.com/) to see the cost of any npm packages

Use [Snyk](https://snyk.io) to find any security vulnerabilities for any npm package. Search their database here: `https://snyk.io/vuln/npm:{package}` e.g. https://snyk.io/vuln/npm:react

# 🎨 CSS

- [CSS Tricks "Complete Guide to Flexbox"](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [CSS Tricks "Complete Guide to Grid"](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [Cubic bezier curve creator](http://cubic-bezier.com/#.17,.67,.83,.67)
- [Ceaser](http://matthewlein.com/ceaser/) - Cubic bezier curve generator
- [CSS Triggers](https://csstriggers.com/) - find out what CSS properties trigger Paint/Layout/Composite renders
- [Fluid-responsive font-size calculator](https://websemantics.uk/tools/responsive-font-calculator/) - To scale typography smoothly across viewport widths.
- [Browserhacks](http://browserhacks.com/) - Browserhacks is an extensive list of browser specific CSS and JavaScript hacks from all over the interwebs
- [Absolute centering](https://codepen.io/shshaw/full/gEiDt) - useful techniques for absolute centering in CSS

## CSS-in-JS

- [styled-components](https://styled-components.com) - CSS-in-JS for React
- [Emotion](http://emotion.sh/) - CSS-in-JS library
- [design-system-utils](https://github.com/mrmartineau/design-system-utils) - Design system framework for modern front-end projects
- [polished](https://polished.js.org/) - A lightweight toolset for writing styles in JavaScript
- [styled-by](https://github.com/brunobertolini/styled-by) Simple and powerful lib to handle styled props in your components

# JavaScript

## Useful JS links

- [JS module import/export syntax](https://stackoverflow.com/a/34842087/91359)
- [JavaScript Event KeyCodes](http://keycode.info/)
- [JavaScript Visualizer](https://tylermcginnis.com/javascript-visualizer/)
- [Does it mutate?](https://doesitmutate.xyz/)
- [jsPerf](https://jsperf.com/) - JavaScript performance playground
- [modern-js-cheatsheet](https://github.com/mbeaudru/modern-js-cheatsheet)

## Framework agnostic packages

### General utilities

- [Lodash](https://lodash.com) - A modern JavaScript utility library delivering modularity, performance & extras.
- [Just](https://github.com/angus-c/just) - A library of dependency-free utilities that do just do one thing (like Lodash but smaller)
  - Install each util independently
  - Read the [tradeoffs document](https://github.com/angus-c/just/blob/master/TRADEOFFS.md) to see if Lodash is better
- [tiny-get](https://github.com/NickGard/tiny-get) - A minimal-weight lodash.get equivalent utility
- [auto-bind](https://github.com/sindresorhus/auto-bind) - Automatically bind methods to their class instance
- [liteready](https://github.com/nicbell/liteready) - A lightweight DOM ready.
- [passport](https://github.com/jaredhanson/passport) - Simple, unobtrusive authentication for Node.js
- [attach.js](http://nicbell.github.io/attach.js/) - Attach.js removes dependancy on messy CSS selectors when attaching JavaScript to the page. Very useful for non-React/Angular/SPA projects
- [gator](https://github.com/ccampbell/gator) - Gator is a Javascript event delegation library
- [get-size](https://github.com/desandro/get-size) - Get the size of elements
- [length.js](https://github.com/appalaszynski/length.js) - Library for length units conversion
- [action-outside](https://github.com/saschageyer/action-outside) - Invoke a callback function when clicked or tabbed outside one or multiple DOM elements
- [select-dom](https://github.com/bfred-it/select-dom) - Lightweight `querySelector`/`All` wrapper that outputs an Array
- [memoizee](https://github.com/medikoo/memoizee) - Complete memoize/cache solution for JavaScript
- [memoize-one](https://github.com/alexreardon/memoize-one) A memoization library which only remembers the latest invocation
- [kind-of](https://github.com/jonschlinkert/kind-of) - Get the native JavaScript type of a value, fast.
- [iterare](https://github.com/felixfbecker/iterare) - Array methods + ES6 Iterators =
- [eases](https://github.com/mattdesl/eases) - a grab-bag of modular easing equations
- [normalizr](https://github.com/paularmstrong/normalizr) - Normalizes nested JSON according to a schema
- [lazy-value](https://github.com/sindresorhus/lazy-value) - Create a lazily evaluated value
- [mitt](https://github.com/developit/mitt) - Tiny 200 byte functional event emitter / pubsub.
- [text-mask](https://github.com/text-mask/text-mask) - Input mask for React, Angular, Ember, Vue, & plain JavaScript
- [fast-equals](https://github.com/planttheidea/fast-equals) - A blazing fast equality comparison, either shallow or deep
- [fast-copy](https://github.com/planttheidea/fast-copy) - A blazing fast deep object copier
- [compute-scroll-into-view](https://github.com/stipsan/compute-scroll-into-view) Utility for calculating what should be scrolled, how it's scrolled is up to you
- [arr](https://github.com/lukeed/arr) A collection of tiny, highly performant Array.prototype alternatives
- [timedstorage](https://github.com/fuhton/timedstorage) A library for storing and expiring objects in window.localstorage
- [left-pad](https://github.com/stevemao/left-pad) - String left pad
- [dont-go](https://github.com/tiaanduplessis/dont-go) - A small client-side library with zero dependencies to change the title and/or favicon of the page when it is inactive

### Async

- [axios](https://github.com/axios/axios) - Promise based HTTP client for the browser and node.js
- [cross-fetch](https://github.com/lquixada/cross-fetch) - Universal WHATWG Fetch API for Node, Browsers and React Native
- [awaity](https://github.com/asfktz/Awaity.js) - A functional, lightweight alternative to bluebird.js, built with `async` / `await` in mind
- [loadjs](https://github.com/muicss/loadjs) A tiny async loader / dependency manager for modern browsers (789 bytes)

### Node

- [Express](https://expressjs.com)
- [nodebestpractices](https://github.com/i0natan/nodebestpractices) - The largest Node.JS best practices list. Curated from the top ranked articles and always updated
- [dumper.js](https://github.com/zeeshanu/dumper.js) A better and pretty variable inspector for your Node.js applications

### Responsive

- [responsive-watch](https://github.com/pauldijou/responsive-watch) - Watch some media queries and react when they change

### Media and Images

- [images-loaded](https://github.com/awcross/images-loaded) - Wait for images to load using promises. No dependencies.
- [lazysizes](https://github.com/aFarkas/lazysizes) - High performance and SEO friendly lazy loader for images (responsive and normal), iframes and more, that detects any visibility changes triggered through user interaction, CSS or JavaScript without configuration.

#### Image services

- [sharp](https://github.com/lovell/sharp) High performance Node.js image processing, the fastest module to resize JPEG, PNG, WebP and TIFF images. Uses the libvips library.
- [IMGIX](https://www.imgix.com/) - Real-time image processing and image CDN

### Date

- [date-fns](https://date-fns.org/) - Modern JavaScript date utility library
- [tinydate](https://github.com/lukeed/tinydate) - A tiny (337B) reusable date formatter. Extremely fast!
- [tinytime](https://github.com/aweary/tinytime) - ⏰ A straightforward date and time formatter in <1kb

### Scrolling

- [scroll-watcher](https://github.com/jonataswalker/scroll-watcher)
- [scrolldir](https://github.com/dollarshaveclub/scrolldir) - Leverage Vertical Scroll Direction with CSS

### Carousels

- [Flickity](https://flickity.metafizzy.co/)
- [Swiper](http://idangero.us/swiper/)

### Animation

- [Popmotion](https://github.com/Popmotion/popmotion) Simple animation libraries for delightful user interfaces
- [ramjet](https://github.com/Rich-Harris/ramjet) Morph DOM elements from one state to another with smooth animations and transitions
- [anime](https://github.com/juliangarnier/anime) JavaScript Animation Engine
- [GSAP](https://greensock.com/) the standard for JavaScript HTML5 animation | GreenSock

### Web workers

- [workerize](https://github.com/developit/workerize) - Run a module in a Web Worker
- [greenlet](https://github.com/developit/greenlet) - Move an async function into its own thread. A simplified single-function version of workerize.

### Immutable

- [immer](https://github.com/mweststrate/immer) - Create the next immutable state tree by simply modifying the current tree
- [unchanged](https://github.com/planttheidea/unchanged) - A tiny, fast, unopinionated handler for updating JS objects and arrays immutably
- [seamless-immutable](https://github.com/rtfeldman/seamless-immutable) - Immutable data structures for JavaScript which are backwards-compatible with normal JS Arrays and Objectsseamless-immutable`

### Typography

- [fitty](https://github.com/rikschennink/fitty) - Makes text fit perfectly

### Polyfills

- [resize-observer-polyfill](https://github.com/que-etc/resize-observer-polyfill) A polyfill for the Resize Observer API

## ⚛️ React

[reactjs.org](https://reactjs.org)

- [create-react-app](https://github.com/facebook/create-react-app) Create React apps with no build configuration
  - [react-app-rewired](https://github.com/timarney/react-app-rewired) Override create-react-app webpack configs without ejecting
- [react-bits](https://github.com/vasanthk/react-bits) ✨ React patterns, techniques, tips and tricks ✨

### React-specific libs:

- [react-powerplug](https://github.com/renatorib/react-powerplug) - Renderless Containers
- [formik](https://github.com/jaredpalmer/formik) - Build forms in React, without the tears 😭
- [react-router](https://github.com/ReactTraining/react-router) Declarative routing for React
- [Reach Router](https://reach.tech/router)
- [react-fns](https://react-fns.netlify.com/) - React Components for common Web APIs
- [react-portal](https://github.com/tajo/react-portal) - React component for transportation of modals, lightboxes, loading bars... to document.body
- [react-ideal-image](https://github.com/stereobooster/react-ideal-image) 🖼️ An Almost Ideal React Image Component
- [react-adopt](https://github.com/pedronauck/react-adopt) Compose render props components like a pro
- [downshift](https://github.com/paypal/downshift)
- [react-loadable](https://github.com/jamiebuilds/react-loadable) A higher order component for loading components with promises
- [react-portal](https://github.com/tajo/react-portal) React component for transportation of modals, lightboxes, loading bars... to document.body
- [js-lingui: 🌍📖](https://github.com/lingui/js-lingui) - A readable, automated, and optimized (5 kb) internationalization (Intl / i18n) for JavaScript
- [react-mq](https://github.com/u-wave/react-mq) - Barebones CSS media query component for React, ~560 bytes
- [react-media](https://github.com/ReactTraining/react-media) - CSS media queries for React. This is SSR compatible as well.

### React patterns

- [Hooks.Guide](https://www.hooks.guide/) - Collection of React hooks curated by the community
- [useHooks](https://usehooks.com/) - Easy to understand React Hook recipes

### State management

- [redux](https://github.com/reduxjs/redux) Predictable state container for JavaScript apps
  - [reselect](https://github.com/reduxjs/reselect) Selector library for Redux
  - [redux-saga](https://github.com/redux-saga/redux-saga) An alternative side effect model for Redux apps
    - [redux-saga-routines](https://github.com/afitiskin/redux-saga-routines) Routines for redux-saga
  - [redux-thunk](https://github.com/reduxjs/redux-thunk) Thunk middleware for Redux
  - [awesome-redux](https://github.com/brillout/awesome-redux) Catalog of Redux Libraries & Learning Material
- [parket](https://github.com/ForsakenHarmony/parket) - A library to manage application state, heavily inspired by mobx-state-tree
- [unstated](https://github.com/jamiebuilds/unstated) State so simple, it goes without saying
- [mergeState](https://github.com/zhujinxuan/mergeState) How to Stop Worrying and Use Nested Object/Array in React/Redux States

### Server-rendered React

- [Next.js](https://nextjs.org/) ([repo](https://github.com/zeit/next.js)) - Framework for server-rendered or statically-exported React apps
  - [next-plugins](https://github.com/zeit/next-plugins)

### Static site generators

- [gatsby: ⚛️📄🚀](https://github.com/gatsbyjs/gatsby) - Blazing fast static site generator for React

### Microservices/Serverless

- [micro](https://github.com/zeit/micro)
  - [awesome-micro](https://github.com/amio/awesome-micro)

## TypeScript

[typescriptlang.org](https://www.typescriptlang.org/)

- [What's new in TypeScript](https://github.com/Microsoft/TypeScript/wiki/What's-new-in-TypeScript) · Microsoft/TypeScript Wiki
- [TypeScript Deep Dive](https://basarat.gitbooks.io/typescript/)
- [TypeScript Evolution](https://blog.mariusschulz.com/series/typescript-evolution) | Marius Schulz
- [JSON to Typescript Interface](https://transform.now.sh/json-to-ts-interface/)
- [react-typescript-cheatsheet](https://github.com/sw-yx/react-typescript-cheatsheet) - a cheatsheet for react users using typescript with react for the first (or nth!) time

# Code bundlers

- [Webpack](https://webpack.js.org/) - script/asset bundler
  - [Webpack recipes](https://github.com/mrmartineau/webpack-recipes)
  - [ifdef-loader](https://github.com/nippur72/ifdef-loader) - Webpack loader for JavaScript/TypeScript conditional compilation
- [Parcel](https://parceljs.org/) - Blazing fast, zero configuration web application bundler
- [microbundle](https://github.com/developit/microbundle) - Zero-configuration bundler for tiny modules
- [rollup.js](https://rollupjs.org/guide/en) - Rollup is a module bundler for JavaScript
- [ncc](https://github.com/zeit/ncc) - Node.js Compiler Collection. Simple CLI for compiling a Node.js module into a single file, together with all its dependencies, gcc-style.

# Command Line, Terminal and shells

[Fish shell](https://fishshell.com/) - The user-friendly command line shell

- [my fish_config](https://github.com/mrmartineau/fish-config/blob/master/fish/config.fish)

## Creating CLI apps

- [gluegun](https://github.com/infinitered/gluegun) - A delightful toolkit for building Node-powered CLIs
- [inquirer](https://github.com/SBoudrias/Inquirer.js) - A collection of common interactive command line user interfaces
- [commander](https://github.com/tj/commander.js) - node.js command-line interfaces made easy
- [sade](https://github.com/lukeed/sade) - Sade is a small but powerful tool for building command-line interface (CLI) applications for Node.js that are fast, responsive, and helpful!

## CLI apps

- [hub](https://hub.github.com/) - hub is an extension to command-line git that helps you do everyday GitHub tasks without ever leaving the terminal
- [serve](https://github.com/zeit/serve) - Static file serving and directory listing
- [awesome-cli-apps](https://github.com/agarrharr/awesome-cli-apps) - A curated list of command line apps
- [SpaceVim](https://github.com/SpaceVim/SpaceVim) - A community-driven modular vim distribution - The ultimate vim configuration

# Tooling

## Package management and publishing

- [np](https://github.com/sindresorhus/np) - A better `npm publish`
- [size-limit](https://github.com/ai/size-limit) - Prevent JS libraries bloat. If you accidentally add a massive dependency, Size Limit will throw an error
- [bundlesize](https://github.com/siddharthkp/bundlesize) - Keep your bundle size in check
- [nps](https://github.com/kentcdodds/nps) All the benefits of npm scripts without the cost of a bloated package.json and limits of json
- [Dependabot](https://dependabot.com/) - Dependabot creates pull requests to keep your dependencies secure and up-to-date
- [npm-config](https://github.com/npm/npm/blob/1fa9169ac9687f0be4156574279a968a48dd2458/doc/misc/npm-config.md) (docs) - More than you probably want to know about npm configuration
- [patch-package](https://github.com/ds300/patch-package) - Fix broken node modules with no fuss 📦👌

## Commit hooks

- [husky](https://github.com/typicode/husky) - Git hooks made easy
- [lint-staged: 🚫💩](https://github.com/okonet/lint-staged) — Run linters on git staged files

# Testing

- [Jest](https://facebook.github.io/jest/) - Delightful JavaScript Testing
  - [majestic](https://github.com/Raathigesh/majestic) - Zero config UI for Jest
- [Cypress](https://cypress.io) - end-to-end testing
  - [cypress-testing-library](https://github.com/kentcdodds/cypress-testing-library) 🐅 Simple and complete custom Cypress commands and utilities that encourage good testing practices
- [dom-testing-library](https://github.com/kentcdodds/dom-testing-library) 🐙 Simple and complete DOM testing utilities that encourage good testing practices
- [react-testing-library: 🐐 Simple and complete React DOM testing utilities that encourage good testing practices.](https://github.com/kentcdodds/react-testing-library)
- [Chance](https://github.com/chancejs/chancejs) - Random generator helper for JavaScript
- [faker.js](https://github.com/Marak/faker.js) generate massive amounts of fake data in Node.js and the browser
- [nock](https://github.com/nock/nock) HTTP server mocking and expectations library for Node.js
- [Stryker Mutator](http://stryker-mutator.io/)

## Code formatting and linting

- [Prettier](https://prettier.io/)
  - [precise-commits](https://github.com/nrwl/precise-commits) - Painlessly apply Prettier by only formatting lines you have modified anyway!
  - [pretty-quick](https://github.com/azz/pretty-quick) - Runs Prettier on your changed files
- [Eslint](https://eslint.org)
  - [eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) - ESLint plugin for prettier formatting
  - [eslint-config-prettier](https://github.com/prettier/eslint-config-prettier) - Turns off all rules that are unnecessary or might conflict with Prettier
  - [eslint-plugin-react](https://github.com/yannickcr/eslint-plugin-react) - React specific linting rules for ESLint

# Progressive Web Apps

- [Workbox](https://developers.google.com/web/tools/workbox/) & ([repo](https://github.com/GoogleChrome/workbox)) - JavaScript libraries for Progressive Web Apps

# Code Sandboxes

- [CodeSandbox](https://codesandbox.io/) - CodeSandbox is perfect for React demo apps
- [Codepen](http://codepen.io/) - Codepen is perfect for non-React front-end demos and prototypes
- [CodeShare](http://codeshare.io/) - Codeshare is useful for collaborating on a single file if devs are not in the same room
- [Glitch](https://glitch.com/)
- [GraphQL Playground](https://www.graphqlbin.com)

# APIs

- [Postman](https://www.getpostman.com/) - used to develop, test and monitor APIs
- [MockAPI](http://www.mockapi.io/) - create a mock API
- [jsonbin](https://jsonbin.org/) - A personal JSON store as a RESTful service
- [test-cors.org](http://www.test-cors.org/)
- [Reqres](https://reqres.in/) - A hosted REST-API ready to respond to your AJAX requests

# JSON
- [JSON generator](https://next.json-generator.com/) - generate a lot of custom JSON for your app/site
- [JSON Editor Online](https://jsoneditoronline.org/) - view/edit JSON in a better format
- [fx](https://github.com/antonmedv/fx) - Command-line tool and terminal JSON viewer 🔥

# HTML

- [github.com/joshbuchea/HEAD](https://github.com/joshbuchea/HEAD) the definitive resource for everything that _could_ go in the head of your document
- [MetaTags.io](https://metatags.io/) — Preview, Edit and Generate
- [HEY META](https://www.heymeta.com/) - Website Meta Tag Check
- [Rich Link Preview](https://richpreview.com/)

# SVG/Image Media compression

- [Squoosh](https://squoosh.app/)
- [SVGOMG](https://jakearchibald.github.io/svgomg/) - SVGO's Missing GUI

# SVG

- [flubber](https://github.com/veltman/flubber) - Tools for smoother shape animations

# Conversions and unicode

- [Transform](https://transform.now.sh/) All important transforms at one place ⭐️⭐️⭐️ this is so useful
- [SVGR](https://svgr.now.sh/) The SVG to JSX transformer
- [svg2jsx](https://svg2jsx.herokuapp.com/)
- [JSON to JavaScript object literal | Online Tool](https://json-to-js.com/)
- [Unminify JS, CSS and HTML Code](https://unminify.com/)
- [Multi-Encoder](https://encoder.internetwache.org/#tab_uni)
- [Unicode code converter](https://r12a.github.io/app-conversion/)

# Features and feature detection

- [Can I Use...](https://caniuse.com/) - Browser support tables for modern web technologies (HTML5, CSS3, JavaScript etc)
- [JavaScript compatibility table](http://kangax.github.io/compat-table/es6/)

# Performance

- [Bundlephobia](https://bundlephobia.com/) - find the cost of adding a npm package to your bundle

## Performance testing and monitoring

- [WebPageTest](https://www.webpagetest.org/)
- [Lighthouse](https://developers.google.com/web/tools/lighthouse/)
- [Calibre](https://calibreapp.com/) web performance monitoring
- [Website Speed Test Image Analysis Tool](https://webspeedtest.cloudinary.com/) by Cloudinary

# Design

- [Subtract Guides - Simple Rules for Designing Web & Mobile Forms](https://subtract.design/entry/forms)

# Design Systems and documentation

- [Storybook](https://storybook.js.org/) UI dev environment you'll love to use
- [react-styleguidist](https://github.com/styleguidist/react-styleguidist) - Isolated React component development environment with a living style guide
- [Docusaurus](https://docusaurus.io/) Easy to Maintain Open Source Documentation Websites
- [Docz](https://www.docz.site/)
- [design-system-utils](https://github.com/mrmartineau/design-system-utils) - Design system framework for modern front-end projects

# Accessibility (A11y)

Accessibility is an extremely important part of any web project. While the SOW, functional spec or user-stories might not directly mention a11y, it is up to each developer to ensure that best efforts are made to make our websites as accessible as possible.

## A11y tools and resources:

- [Interactive WCAG](http://code.viget.com/interactive-wcag/) guidelines - cheatsheet for A, AA & AAA
- [awesome-a11y](https://github.com/brunopulis/awesome-a11y) - massive list of a11y-related resources & information
- [tenon.io](https://tenon.io/) - a11y tester
- [a11yproject.com/checklist.html](http://a11yproject.com/checklist.html) - a11y checklist
- [a11yproject.com](http://a11yproject.com/) - a11y resources
- [w3.org/WAI/ER/tools/](https://www.w3.org/WAI/ER/tools/) - list of a11y tools from the W3C
- [allyjs.io](https://allyjs.io/index.html) - JavaScript library to help modern web applications with accessibility concerns by making accessibility simpler
- [Four principles of Accessibility](https://www.w3.org/TR/UNDERSTANDING-WCAG20/intro.html#introduction-fourprincs-head)
- [Aria landmarks example](https://w3c.github.io/aria-practices/examples/landmarks/index.html)
- [A11y Style-guide](http://a11y-style-guide.com/style-guide/) - markup examples and best practices
- [Inclusive Components](https://inclusive-components.design/) - A blog trying to be a pattern library. All about designing inclusive web interfaces, piece by piece.
- [Color contrast checker](http://leaverou.github.io/contrast-ratio/)
- [Accessible color palette builder](https://toolness.github.io/accessible-color-matrix/) - An prototype to help designers build accessible color palettes
- [Practical ARIA Examples](http://heydonworks.com/practical_aria_examples/)
- [Nutrition Cards for Accessible Components A11Y Expectations](https://davatron5000.github.io/a11y-nutrition-cards/)
- [Web Accessibility Tutorials](https://www.w3.org/WAI/tutorials/) - Guidance on how to create websites that meet WCAG

### A11y Chrome extensions

- [Color Contrast Analyzer](https://chrome.google.com/webstore/detail/color-contrast-analyzer/dagdlcijhfbmgkjokkjicnnfimlebcll)
- [NoCoffee](https://chrome.google.com/webstore/detail/nocoffee/jjeeggmbnhckmgdhmgdckeigabjfbddl) - has options for testing color blindness and other sight-related issues

# DevOps

## Continuous integration

- [CircleCI](https://circleci.com) - Paid.
- [Bitrise](https://bitrise.com) - Paid. For iOS/Android apps
- [Travis CI](https://travisci.com) - Free for open-source

## Hosting

- [now](https://zeit.co/now)

## Domains

- [iwantmyname](https://iwantmyname.com/)

# Design

## Typography

- [Modular Scale](http://modularscale.com/)
- [Adaptive Modular Scale](https://codepen.io/getflourish/full/vXqewy/)
- [Type Scale - A Visual Calculator](http://type-scale.com/)

# IDEs and Text Editors

## VSCode

- [My VS Code extensions](https://gist.github.com/mrmartineau/28ef03c53275ea468e470532d6d20449)
- [My preferences](https://gist.github.com/mrmartineau/ea3b428124bc1e31cd46dfa55469d781)

## Programming fonts

- [Input: Fonts for Code](http://input.fontbureau.com/)
- [IBM Plex Mono](https://www.ibm.com/plex/)
- [FiraCode: Monospaced font with programming ligatures](https://github.com/tonsky/FiraCode)
- [fantasque-sans: A font family with a great monospaced variant for programmers.](https://github.com/belluzj/fantasque-sans)

## Code colour schemes

- [Ayu (Mirage)](https://marketplace.visualstudio.com/items?itemName=teabyii.ayu)
- [Dracula](https://draculatheme.com/visual-studio-code/) A dark theme for Visual Studio Code and 50+ apps
- [Oceanic Next Theme](https://marketplace.visualstudio.com/items?itemName=gerane.Theme-OceanicNext)
- [🌌 Night Owl](https://github.com/sdras/night-owl-vscode-theme) A VS Code dark theme for contrast for nighttime coding
- [Nord](https://marketplace.visualstudio.com/items?itemName=arcticicestudio.nord-visual-studio-code)
- [VSCodeThemes](https://vscodethemes.com/)

# Regular expressions

- [Regex101](https://regex101.com/) Online regex tester and debugger: PHP, PCRE, Python, Golang and JavaScript

---

> If you think there are better alternatives, or that there should be something added to the list, please [create an issue](https://github.com/mrmartineau/awesome-web-dev-resources/issues/new) or [create a pull request](https://github.com/mrmartineau/awesome-web-dev-resources/pulls)
