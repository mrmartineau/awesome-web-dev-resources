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

- [General resources](#general-resources)
- [CSS](#css)
  - [CSS-in-JS](#css-in-js)
- [JavaScript](#javascript)
  - [Framework agnostic packages](#framework-agnostic-packages)
    - [General utilities](#general-utilities)
    - [Async](#async)
    - [Node](#node)
    - [Responsive](#responsive)
    - [Media and Images](#media-and-images)
    - [Date](#date)
    - [Scrolling](#scrolling)
    - [Carousels](#carousels)
    - [Web workers](#web-workers)
    - [Immutable](#immutable)
    - [Typography](#typography)
    - [Polyfills](#polyfills)
  - [React](#react)
    - [React-specific libs:](#react-specific-libs)
    - [State management](#state-management)
    - [Server-rendered React](#server-rendered-react)
    - [Static site generators](#static-site-generators)
  - [Microservices/Serverless](#microservices-serverless)
  - [Code bundlers](#code-bundlers)
- [Design Systems](#design-systems)
- [Testing](#testing)
- [Progressive Web Apps](#progressive-web-apps)
- [Code Sandboxes](#code-sandboxes)
- [APIs](#apis)
- [HTML](#html)
- [SVG](#svg)
- [Conversions and unicode](#conversions-and-unicode)
- [Tooling](#tooling)
  - [Package management and publishing](#package-management-and-publishing)
  - [Commit hooks](#commit-hooks)
  - [Code formatting and linting](#code-formatting-and-linting)
- [Features and feature detection](#features-and-feature-detection)
- [Performance](#performance)
  - [Performance testing and monitoring](#performance-testing-and-monitoring)
- [Accessibility (A11y)](#accessibility-a11y)
  - [A11y tools and resources:](#a11y-tools-and-resources)
    - [A11y Chrome extensions](#a11y-chrome-extensions)
    - [A11y Sketch plugins](#a11y-sketch-plugins)
- [DevOps](#devops)
  - [Continuous integration](#continuous-integration)
  - [Hosting](#hosting)
  - [Domains](#domains)
- [Design](#design)
  - [Typography](#typography)
- [Programming fonts](#programming-fonts)
- [Responsive](#responsive)
- [Inspiration](#inspiration)
- [Learning](#learning)
- [SEO](#seo)
- [Animation](#animation)
- [Regular expressions](#regular-expressions)

</details>

# General resources

- [Devdocs.io](http://devdocs.io/) - Fast, offline, and free documentation browser for developers. Search 100+ docs in one web app: HTML, CSS, JavaScript, PHP, Ruby, Python, Go, C, C++…
- [DevHints](https://devhints.io/) - cheatsheets for many web technologies
- [Carbon](<https://carbon.now.sh/?bg=rgba(171,%20184,%20195,%201)&t=seti&l=auto&ds=true&wc=true&wa=true&pv=32px&ph=32px&ln=false>) - use this to share images of your code in presentations etc
- [Badgen](https://badgen.net/) ![](https://badgen.net/badge/add/flare)
- [Shields.io](https://shields.io/) - ![](https://img.shields.io/badge/add-flare-green.svg?style=flat-square) to your documentation/readmes
- [JSON generator](https://next.json-generator.com/) - generate a lot of custom JSON for your app/site
- [JSON Editor Online](https://jsoneditoronline.org/) - view/edit JSON in a better format
- [Git Flight Rules](https://github.com/k88hudson/git-flight-rules) - A guide for astronauts (now, programmers using Git) about what to do when things go wrong.

# CSS

- [CSS Tricks "Complete Guide to Flexbox"](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [CSS Tricks "Complete Guide to Grid"](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [Cubic bezier curve creator](http://cubic-bezier.com/#.17,.67,.83,.67)
- [Ceaser](http://matthewlein.com/ceaser/) - Cubic bezier curve generator
- [CSS Triggers](https://csstriggers.com/) - find out what CSS properties trigger Paint/Layout/Composite renders
- [Fluid-responsive font-size calculator](https://websemantics.uk/tools/responsive-font-calculator/) - To scale typography smoothly across viewport widths.
- [Browserhacks](http://browserhacks.com/) - Browserhacks is an extensive list of browser specific CSS and JavaScript hacks from all over the interwebs
- [Absolute centering](https://codepen.io/shshaw/full/gEiDt) - useful techniques for absolute centering in CSS

## CSS-in-JS

- [Emotion](http://emotion.sh/) - CSS-in-JS library
- [styled-components](https://styled-components.com) - CSS-in-JS for React
  - `yarn add styled-components` / `npm i -S styled-components`
- [design-system-utils](https://github.com/mrmartineau/design-system-utils) - Design system framework for modern front-end projects
  - `yarn add design-system-utils` / `npm i -S design-system-utils`
- [polished](https://polished.js.org/) - A lightweight toolset for writing styles in JavaScript
- [styled-by](https://github.com/brunobertolini/styled-by) Simple and powerful lib to handle styled props in your components

# JavaScript

Use [Bundlephobia](https://bundlephobia.com/) to see the cost of any npm packages

Use [Snyk](https://snyk.io) to find any security vulnerabilities for any npm package. Search their database here: `https://snyk.io/vuln/npm:{package}` e.g. https://snyk.io/vuln/npm:react

## Useful JS links

- [JS module import/export syntax](https://stackoverflow.com/a/34842087/91359)

## Framework agnostic packages

### General utilities

- [Lodash](https://lodash.com) - A modern JavaScript utility library delivering modularity, performance & extras.
  - `yarn add lodash` / `npm i -S lodash`
- [Just](https://github.com/angus-c/just) - A library of dependency-free utilities that do just do one thing (like Lodash but smaller)
  - Install each util independently
  - Read the [tradeoffs document](https://github.com/angus-c/just/blob/master/TRADEOFFS.md) to see if Lodash is better
- [auto-bind](https://github.com/sindresorhus/auto-bind) - Automatically bind methods to their class instance
  - `yarn add auto-bind` / `npm i -S auto-bind`
- [object-get](https://github.com/75lb/object-get) - Access nested property values at any depth with a simple expression
  - `yarn add object-get` / `npm i -S object-get`
- [liteready](https://github.com/nicbell/liteready) - A lightweight DOM ready.
  - `yarn add lite-ready` / `npm i -S lite-ready`
- [passport](https://github.com/jaredhanson/passport) - Simple, unobtrusive authentication for Node.js
  - `yarn add passport` / `npm i -S passport`
- [attach.js](http://nicbell.github.io/attach.js/) - Attach.js removes dependancy on messy CSS selectors when attaching JavaScript to the page. Very useful for non-React/Angular/SPA projects
  - `yarn add attach.js` / `npm i -S attach.js`
- [gator](https://github.com/ccampbell/gator) - Gator is a Javascript event delegation library
  - `yarn add gator` / `npm i -S gator`
- [get-size](https://github.com/desandro/get-size) - Get the size of elements
  - `yarn add get-size` / `npm i -S get-size`
- [length.js](https://github.com/appalaszynski/length.js) - Library for length units conversion
  - `yarn add length.js` / `npm i -S length.js`
- [action-outside](https://github.com/saschageyer/action-outside) - Invoke a callback function when clicked or tabbed outside one or multiple DOM elements
  - `yarn add action-outside` / `npm i -S action-outside`
- [select-dom](https://github.com/bfred-it/select-dom) - Lightweight `querySelector`/`All` wrapper that outputs an Array
  - `yarn add select-dom` / `npm i -S select-dom`
- [memoizee](https://github.com/medikoo/memoizee) - Complete memoize/cache solution for JavaScript
  - `yarn add memoizee` / `npm i -S memoizee`
- [memoize-one](https://github.com/alexreardon/memoize-one) A memoization library which only remembers the latest invocation
- [kind-of](https://github.com/jonschlinkert/kind-of) - Get the native JavaScript type of a value, fast.
  - `yarn add kind-of` / `npm i -S kind-of`
- [iterare: Array methods + ES6 Iterators =](https://github.com/felixfbecker/iterare)
  - `yarn add iterare` / `npm i -S iterare`
  - `yarn add mergestate` / `npm i -S mergestate`
- [eases: a grab-bag of modular easing equations](https://github.com/mattdesl/eases)
- [normalizr: Normalizes nested JSON according to a schema](https://github.com/paularmstrong/normalizr)
- [lazy-value: Create a lazily evaluated value](https://github.com/sindresorhus/lazy-value)
- [mitt: 🥊 Tiny 200 byte functional event emitter / pubsub.](https://github.com/developit/mitt)
- [text-mask: Input mask for React, Angular, Ember, Vue, & plain JavaScript](https://github.com/text-mask/text-mask)
- [fast-equals: A blazing fast equality comparison, either shallow or deep](https://github.com/planttheidea/fast-equals)
- [fast-copy: A blazing fast deep object copier](https://github.com/planttheidea/fast-copy)
- [compute-scroll-into-view](https://github.com/stipsan/compute-scroll-into-view) Utility for calculating what should be scrolled, how it's scrolled is up to you
- [arr: A collection of tiny, highly performant Array.prototype alternatives](https://github.com/lukeed/arr)
- [timedstorage](https://github.com/fuhton/timedstorage) A library for storing and expiring objects in window.localstorage

### Async

- [axios](https://github.com/axios/axios) - Promise based HTTP client for the browser and node.js
  - `yarn add axios` / `npm i -S axios`
- [cross-fetch](https://github.com/lquixada/cross-fetch) - Universal WHATWG Fetch API for Node, Browsers and React Native
  - `yarn add cross-fetch` / `npm i -S cross-fetch`
- [awaity](https://github.com/asfktz/Awaity.js) - A functional, lightweight alternative to bluebird.js, built with `async` / `await` in mind
  - `yarn add awaity` / `npm i -S awaity`
- [loadjs: A tiny async loader / dependency manager for modern browsers (789 bytes)](https://github.com/muicss/loadjs)

### Node

- [Express](https://expressjs.com)
- [nodebestpractices](https://github.com/i0natan/nodebestpractices) - The largest Node.JS best practices list. Curated from the top ranked articles and always updated
- [dumper.js: A better and pretty variable inspector for your Node.js applications](https://github.com/zeeshanu/dumper.js)

### Responsive

- [responsive-watch](https://github.com/pauldijou/responsive-watch) - Watch some media queries and react when they change
  - `yarn add responsive-watch` / `npm i -S responsive-watch`

### Media and Images

- [images-loaded](https://github.com/awcross/images-loaded) - Wait for images to load using promises. No dependencies.
  - `yarn add images-loaded` / `npm i -S images-loaded`
- [lazysizes](https://github.com/aFarkas/lazysizes) - High performance and SEO friendly lazy loader for images (responsive and normal), iframes and more, that detects any visibility changes triggered through user interaction, CSS or JavaScript without configuration.
  - `yarn add lazysizes` / `npm i -S lazysizes`

#### Image services

- [sharp](https://github.com/lovell/sharp) High performance Node.js image processing, the fastest module to resize JPEG, PNG, WebP and TIFF images. Uses the libvips library.
- [IMGIX](https://www.imgix.com/) - Real-time image processing and image CDN

### Date

- [dayjs](https://github.com/xx45/dayjs) - Fast 2KB immutable date library alternative to Moment.js with the same modern API
  - `yarn add dayjs` / `npm i -S dayjs`
- [date-fns](https://date-fns.org/) - Modern JavaScript date utility library
  - `yarn add date-fns` / `npm i -S date-fns`
- [tinydate](https://github.com/lukeed/tinydate) - A tiny (337B) reusable date formatter. Extremely fast!
- [tinytime](https://github.com/aweary/tinytime) - ⏰ A straightforward date and time formatter in <1kb

### Scrolling

- [scroll-watcher](https://github.com/jonataswalker/scroll-watcher)
  - `yarn add flickity` / `npm i -S flickity`
- [scrolldir](https://github.com/dollarshaveclub/scrolldir) - Leverage Vertical Scroll Direction with CSS
  - `yarn add scrolldir` / `npm i -S scrolldir`

### Carousels

- [Flickity](https://flickity.metafizzy.co/)
  - `yarn add flickity` / `npm i -S flickity`
- [Swiper](http://idangero.us/swiper/)
  - `yarn add swiper` / `npm i -S swiper`

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
  - `yarn add immer` / `npm install -S immer`
- [unchanged](https://github.com/planttheidea/unchanged) - A tiny, fast, unopinionated handler for updating JS objects and arrays immutably
  - `yarn add unchanged` / `npm install -S unchanged`
- [seamless-immutable](https://github.com/rtfeldman/seamless-immutable) - Immutable data structures for JavaScript which are backwards-compatible with normal JS Arrays and Objects
  - `yarn add seamless-immutable` / `npm install -S seamless-immutable`

### Typography

- [fitty](https://github.com/rikschennink/fitty) - Makes text fit perfectly
  - `yarn add fitty` / `npm install -S fitty`

### Polyfills

- [que-etc/resize-observer-polyfill](https://github.com/que-etc/resize-observer-polyfill) A polyfill for the Resize Observer API

## React

- [create-react-app](https://github.com/facebook/create-react-app) Create React apps with no build configuration
  - [react-app-rewired](https://github.com/timarney/react-app-rewired) Override create-react-app webpack configs without ejecting
- [react-bits](https://github.com/vasanthk/react-bits) ✨ React patterns, techniques, tips and tricks ✨

### React-specific libs:

- [react-powerplug: Renderless Containers](https://github.com/renatorib/react-powerplug)
- [formik](https://github.com/jaredpalmer/formik) - Build forms in React, without the tears 😭
  - `yarn add formik` / `npm i -S formik`
- [react-router: Declarative routing for React](https://github.com/ReactTraining/react-router)
- [Reach Router](https://reach.tech/router)
- [react-fns](https://react-fns.netlify.com/) - React Components for common Web APIs
  - `yarn add react-fns` / `npm i -S react-fns`
- [react-portal](https://github.com/tajo/react-portal) - React component for transportation of modals, lightboxes, loading bars... to document.body
  - `yarn add react-portal` / `npm i -S react-portal`
- [react-ideal-image: 🖼️ An Almost Ideal React Image Component](https://github.com/stereobooster/react-ideal-image)
- [react-adopt: Compose render props components like a pro](https://github.com/pedronauck/react-adopt)
- [downshift](https://github.com/paypal/downshift)
- [react-loadable: A higher order component for loading components with promises.](https://github.com/jamiebuilds/react-loadable)
- [react-portal: React component for transportation of modals, lightboxes, loading bars... to document.body](https://github.com/tajo/react-portal)

### State management

- [redux: Predictable state container for JavaScript apps](https://github.com/reduxjs/redux)
  - `yarn add react-redux` / `npm i -S react-redux`
  - [reselect: Selector library for Redux](https://github.com/reduxjs/reselect)
  - [redux-saga: An alternative side effect model for Redux apps](https://github.com/redux-saga/redux-saga)
  - [redux-thunk: Thunk middleware for Redux](https://github.com/reduxjs/redux-thunk)
  - [awesome-redux: Catalog of Redux Libraries & Learning Material](https://github.com/brillout/awesome-redux)
- [parket](https://github.com/ForsakenHarmony/parket) - A library to manage application state, heavily inspired by mobx-state-tree
  - `yarn add parket` / `npm i -S parket`
- [unstated: State so simple, it goes without saying](https://github.com/jamiebuilds/unstated)
- [mergeState: How to Stop Worrying and Use Nested Object/Array in React/Redux States](https://github.com/zhujinxuan/mergeState)

### Server-rendered React

- [next.js](https://github.com/zeit/next.js) - Framework for server-rendered or statically-exported React apps
  - `yarn add next react react-dom` / `npm install -S next react react-dom`
  - [next-plugins](https://github.com/zeit/next-plugins)
- [after.js](https://github.com/jaredpalmer/after.js) - If Next.js and React Router had a baby...

### Static site generators

- [gatsby: ⚛️📄🚀 Blazing fast static site generator for React](https://github.com/gatsbyjs/gatsby)

# Microservices/Serverless

- [micro](https://github.com/zeit/micro)
  - [awesome-micro](https://github.com/amio/awesome-micro)

# Code bundlers

- [Webpack](https://webpack.js.org/) - script/asset bundler
  - [Webpack recipes](https://github.com/mrmartineau/webpack-recipes)
  - [ifdef-loader](https://github.com/nippur72/ifdef-loader) - Webpack loader for JavaScript/TypeScript conditional compilation
- [Parcel](https://parceljs.org/) - Blazing fast, zero configuration web application bundler
- [microbundle](https://github.com/developit/microbundle) - Zero-configuration bundler for tiny modules
- [rollup.js](https://rollupjs.org/guide/en) - Rollup is a module bundler for JavaScript

# Design Systems and documentation

- [Storybook](https://storybook.js.org/) UI dev environment you'll love to use
- [react-styleguidist](https://github.com/styleguidist/react-styleguidist) - Isolated React component development environment with a living style guide
- [Docusaurus](https://docusaurus.io/) Easy to Maintain Open Source Documentation Websites
- [Docz](https://www.docz.site/)
- [design-system-utils](https://github.com/mrmartineau/design-system-utils) - Design system framework for modern front-end projects

# Testing

- [Jest](https://facebook.github.io/jest/) - Delightful JavaScript Testing
  - `yarn add jest` / `npm i -S jest`
  - [majestic](https://github.com/Raathigesh/majestic) - Zero config UI for Jest
- [Cypress](https://cypress.io) - end-to-end testing
  - [cypress-testing-library](https://github.com/kentcdodds/cypress-testing-library) 🐅 Simple and complete custom Cypress commands and utilities that encourage good testing practices
- [dom-testing-library](https://github.com/kentcdodds/dom-testing-library) 🐙 Simple and complete DOM testing utilities that encourage good testing practices
- [react-testing-library: 🐐 Simple and complete React DOM testing utilities that encourage good testing practices.](https://github.com/kentcdodds/react-testing-library)
- [Chance](https://github.com/chancejs/chancejs) - Random generator helper for JavaScript
- [faker.js](https://github.com/Marak/faker.js) generate massive amounts of fake data in Node.js and the browser
- [nock](https://github.com/nock/nock) HTTP server mocking and expectations library for Node.js

# Progressive Web Apps

- [Workbox](https://developers.google.com/web/tools/workbox/) & [workbox (repo): 📦 Workbox: JavaScript libraries for Progressive Web Apps](https://github.com/GoogleChrome/workbox)

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

# HTML

- [github.com/joshbuchea/HEAD](https://github.com/joshbuchea/HEAD) the definitive resource for everything that _could_ go in the head of your document

# SVG

- [SVGOMG](https://jakearchibald.github.io/svgomg/) - SVGO's Missing GUI
- [flubber](https://github.com/veltman/flubber) - Tools for smoother shape animations
  - `yarn add flubber` / `npm i -S flubber`

# Conversions and unicode

- [Transform](https://transform.now.sh/) All important transforms at one place ⭐️⭐️⭐️ this is so useful
- [SVGR](https://svgr.now.sh/) The SVG to JSX transformer
- [svg2jsx](https://svg2jsx.herokuapp.com/)
- [JSON to JavaScript object literal | Online Tool](https://json-to-js.com/)
- [Unminify JS, CSS and HTML Code](https://unminify.com/)
- [Multi-Encoder](https://encoder.internetwache.org/#tab_uni)
- [Unicode code converter](https://r12a.github.io/app-conversion/)

# Tooling

## Package management and publishing

- [np](https://github.com/sindresorhus/np) - A better `npm publish`
- [size-limit](https://github.com/ai/size-limit) - Prevent JS libraries bloat. If you accidentally add a massive dependency, Size Limit will throw an error
- [bundlesize](https://github.com/siddharthkp/bundlesize) - Keep your bundle size in check
- [nps](https://github.com/kentcdodds/nps) All the benefits of npm scripts without the cost of a bloated package.json and limits of json

## Commit hooks

- [husky: Git hooks made easy](https://github.com/typicode/husky)
- [precise-commits: Painlessly apply Prettier by only formatting lines you have modified anyway!](https://github.com/nrwl/precise-commits)
- [lint-staged: 🚫💩 — Run linters on git staged files](https://github.com/okonet/lint-staged)

## Code formatting and linting

- [Prettier](https://prettier.io/)
  - [pretty-quick: Runs Prettier on your changed files](https://github.com/azz/pretty-quick)
- [Eslint](https://eslint.org)
  - [eslint-plugin-prettier: ESLint plugin for prettier formatting](https://github.com/prettier/eslint-plugin-prettier)
  - [eslint-config-prettier: Turns off all rules that are unnecessary or might conflict with Prettier.](https://github.com/prettier/eslint-config-prettier)
  - [eslint-plugin-react: React specific linting rules for ESLint](https://github.com/yannickcr/eslint-plugin-react)

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

# Programming fonts

- [Input: Fonts for Code](http://input.fontbureau.com/)
- [IBM Plex Mono](https://www.ibm.com/plex/)
- [FiraCode: Monospaced font with programming ligatures](https://github.com/tonsky/FiraCode)
- [fantasque-sans: A font family with a great monospaced variant for programmers.](https://github.com/belluzj/fantasque-sans)

# Code colour schemes

- [Dracula](https://draculatheme.com/visual-studio-code/) A dark theme for Visual Studio Code and 50+ apps
- [Oceanic Next Theme](https://marketplace.visualstudio.com/items?itemName=gerane.Theme-OceanicNext)
- [🌌 Night Owl](https://github.com/sdras/night-owl-vscode-theme) A VS Code dark theme for contrast for nighttime coding
- [Nord](https://marketplace.visualstudio.com/items?itemName=arcticicestudio.nord-visual-studio-code)

# Regular expressions

- [Regex101](https://regex101.com/) Online regex tester and debugger: PHP, PCRE, Python, Golang and JavaScript

--- 

> If you think there are better alternatives, or that there should be something added to the list, please [reate an issue](https://github.com/mrmartineau/awesome-web-dev-resources/issues/new) or [create a pull request](https://github.com/mrmartineau/awesome-web-dev-resources/pulls)
