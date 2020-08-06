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
<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->

<!-- code_chunk_output -->

- [General resources](#general-resources)
  - [📦 Finding and vetting npm packages](#finding-and-vetting-npm-packages)
- [🎨 CSS](#css)
  - [CSS-in-JS](#css-in-js)
- [JavaScript](#javascript)
  - [Useful JS links](#useful-js-links)
  - [Framework agnostic packages](#framework-agnostic-packages)
    - [General utilities](#general-utilities)
    - [Async](#async)
    - [Node](#node)
      - [Logging](#logging)
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
  - [⚛️ React](#️-react)
    - [React-specific libs:](#react-specific-libs)
      - [React Hooks](#react-hooks)
    - [State management](#state-management)
    - [Server-rendered React](#server-rendered-react)
    - [Static site generators](#static-site-generators)
    - [Microservices/Serverless](#microservicesserverless)
  - [TypeScript](#typescript)
- [Command Line, Terminal and shells](#command-line-terminal-and-shells)
  - [Creating CLI apps](#creating-cli-apps)
  - [CLI apps](#cli-apps)
- [Tooling](#tooling)
  - [Code bundlers](#code-bundlers)
  - [Package management and publishing](#package-management-and-publishing)
  - [Commit hooks](#commit-hooks)
- [Testing](#testing)
  - [Code formatting and linting](#code-formatting-and-linting)
  - [Miscellaneous](#miscellaneous)
- [Progressive Web Apps](#progressive-web-apps)
- [Code Sandboxes](#code-sandboxes)
- [APIs](#apis)
  - [GraphQL](#graphql)
- [JSON](#json)
- [HTML](#html)
- [SVG](#svg)
  - [Icons](#icons)
  - [SVG/Image Media compression](#svgimage-media-compression)
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
  - [Docker](#docker)
  - [Hosting](#hosting)
  - [Domains](#domains)
- [Design](#design-1)
  - [Typography](#typography-1)
- [IDEs and Text Editors](#ides-and-text-editors)
  - [VS Code](#vs-code)
  - [Programming fonts](#programming-fonts)
  - [Code colour schemes](#code-colour-schemes)
- [Regular expressions](#regular-expressions)
- [Learning resources](#learning-resources)

<!-- /code_chunk_output -->

</details>

# General resources

- [Devdocs.io](http://devdocs.io/): Fast, offline, and free documentation browser for developers. Search 100+ docs in one web app: HTML, CSS, JavaScript, PHP, Ruby, Python, Go, C, C++…
- [DevHints](https://devhints.io/): cheatsheets for many web technologies
- [Carbon](<https://carbon.now.sh/?bg=rgba(171,%20184,%20195,%201)&t=seti&l=auto&ds=true&wc=true&wa=true&pv=32px&ph=32px&ln=false>): use this to share images of your code in presentations etc
- [Badgen](https://badgen.net/): ![](https://badgen.net/badge/add/flare)
- [Shields.io](https://shields.io/): ![](https://img.shields.io/badge/add-flare-green.svg?style=flat-square) to your documentation/readmes
- [Git Flight Rules](https://github.com/k88hudson/git-flight-rules): A guide for astronauts (now, programmers using Git) about what to do when things go wrong.
- [browser-2020](https://github.com/luruke/browser-2020): Things you can do with a browser in 2020 ☕️

## 📦 Finding and vetting npm packages

- [pika](https://www.pikapkg.com/): A searchable catalog of modern "module" packages on npm
- [npms](https://npms.io/): A better and open source search for node packages
- [emma](https://github.com/maticzav/emma-cli): 📦 Terminal assistant to find and install node packages
- [npmvet](https://github.com/harksys/npmvet): A simple CLI tool for vetting npm package versions
- [Bundlephobia](https://bundlephobia.com/): See the "cost" of any npm package
- [Snyk](https://snyk.io): Find any security vulnerabilities for any npm package. Search their database here: `https://snyk.io/vuln/npm:{package}` e.g. https://snyk.io/vuln/npm:react
- [runpkg](https://runpkg.com/): Explore, learn about and perform static analysis on npm packages in the browser

# 🎨 CSS

- [CSS Tricks "Complete Guide to Flexbox"](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [CSS Tricks "Complete Guide to Grid"](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [Cubic bezier curve creator](http://cubic-bezier.com/#.17,.67,.83,.67)
- [Ceaser](http://matthewlein.com/ceaser/): Cubic bezier curve generator
- [CSS Triggers](https://csstriggers.com/): find out what CSS properties trigger Paint/Layout/Composite renders
- [Fluid-responsive font-size calculator](https://websemantics.uk/tools/responsive-font-calculator/): To scale typography smoothly across viewport widths.
- [Browserhacks](http://browserhacks.com/): Browserhacks is an extensive list of browser specific CSS and JavaScript hacks from all over the interwebs
- [Absolute centering](https://codepen.io/shshaw/full/gEiDt): useful techniques for absolute centering in CSS
- [modern-css-reset](https://github.com/hankchizljaw/modern-css-reset): A bare-bones CSS reset for modern web development
- [CSSFX](https://cssfx.netlify.com/): Beautifully simple click-to-copy CSS effects
- [Shape Divider App](https://www.shapedivider.app/)

## CSS-in-JS

- CSS-in-JS libraries
  - [Styled Components](https://styled-components.com): CSS-in-JS for React
  - [Emotion](http://emotion.sh/): CSS-in-JS library
  - [linaria](https://github.com/callstack/linaria): Zero-runtime CSS in JS library
- [Design System Utils](https://github.com/mrmartineau/design-system-utils): Design system framework for modern front-end projects (made by me!)
- [Polished](https://polished.js.org/): A lightweight toolset for writing styles in JavaScript
- [styled-by](https://github.com/brunobertolini/styled-by): Simple and powerful lib to handle styled props in your components
- [xstyled](https://github.com/smooth-code/xstyled): Consistent theme based CSS for styled-components 💅
- [Theme UI](https://theme-ui.com): Build consistent, themeable React apps based on constraint-based design principles

# JavaScript

## Useful JS links

- [JS module import/export syntax](https://stackoverflow.com/a/34842087/91359)
- [JavaScript Event KeyCodes](http://keycode.info/)
- [JavaScript Visualizer](https://tylermcginnis.com/javascript-visualizer/)
- [Does it mutate?](https://doesitmutate.xyz/)
- [jsPerf](https://jsperf.com/): JavaScript performance playground
- [modern-js-cheatsheet](https://github.com/mbeaudru/modern-js-cheatsheet)
- [HTML DOM](https://htmldom.dev/): Common tasks of managing HTML DOM with vanilla JavaScript

## Framework agnostic packages

### General utilities

- [Lodash](https://lodash.com): A modern JavaScript utility library delivering modularity, performance & extras.
- [Just](https://github.com/angus-c/just): A library of dependency-free utilities that do just do one thing (like Lodash but smaller)
  - Install each util independently
  - Read the [tradeoffs document](https://github.com/angus-c/just/blob/master/TRADEOFFS.md) to see if Lodash is better
- [tiny-get](https://github.com/NickGard/tiny-get): A minimal-weight lodash.get equivalent utility
- [evt](https://www.evt.land/): A type safe replacement for node's EventEmitter
- [liteready](https://github.com/nicbell/liteready): A lightweight DOM ready.
- [passport](https://github.com/jaredhanson/passport): Simple, unobtrusive authentication for Node.js
- [get-size](https://github.com/desandro/get-size): Get the size of elements
- [length.js](https://github.com/appalaszynski/length.js): Library for length units conversion
- [action-outside](https://github.com/saschageyer/action-outside): Invoke a callback function when clicked or tabbed outside one or multiple DOM elements
- [select-dom](https://github.com/bfred-it/select-dom): Lightweight `querySelector`/`All` wrapper that outputs an Array
- [memoizee](https://github.com/medikoo/memoizee): Complete memoize/cache solution for JavaScript
- [memoize-one](https://github.com/alexreardon/memoize-one): A memoization library which only remembers the latest invocation
- [kind-of](https://github.com/jonschlinkert/kind-of): Get the native JavaScript type of a value, fast.
- [iterare](https://github.com/felixfbecker/iterare): Array methods + ES6 Iterators =
- [eases-jsnext](https://github.com/Rich-Harris/eases-jsnext): A grab-bag of modular easing equations
- [normalizr](https://github.com/paularmstrong/normalizr): Normalizes nested JSON according to a schema
- [lazy-value](https://github.com/sindresorhus/lazy-value): Create a lazily evaluated value
- [fast-equals](https://github.com/planttheidea/fast-equals): A blazing fast equality comparison, either shallow or deep
- [fast-copy](https://github.com/planttheidea/fast-copy): A blazing fast deep object copier
- [compute-scroll-into-view](https://github.com/stipsan/compute-scroll-into-view): Utility for calculating what should be scrolled, how it's scrolled is up to you
- [arr](https://github.com/lukeed/arr): A collection of tiny, highly performant Array.prototype alternatives
- [timedstorage](https://github.com/fuhton/timedstorage): A library for storing and expiring objects in window.localstorage
- [left-pad](https://github.com/stevemao/left-pad): String left pad
- [dont-go](https://github.com/tiaanduplessis/dont-go): A small client-side library with zero dependencies to change the title and/or favicon of the page when it is inactive
- [always-done](https://github.com/hybridables/always-done): Handle completion and errors with elegance! Support for async/await, promises, callbacks, streams and observables. A drop-in replacement for async-done - pass 100% of its tests plus more
- [words](https://github.com/words): Linguistic javascript modules
- [no-scroll](https://github.com/davidtheclark/no-scroll): Disable scrolling on an element that would otherwise scroll
- [libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js): A simpler (and smaller) rewrite of Google Android's libphonenumber library
- [text-mask](https://github.com/text-mask/text-mask): Input mask for React, Angular, Ember, Vue, & plain JavaScript
- [msk](https://github.com/vtex/msk): Small library to mask strings
- [focus-trap](https://github.com/davidtheclark/focus-trap): Trap focus within a DOM node
- [tinykeys](https://github.com/jamiebuilds/tinykeys): A tiny (~400 B) & modern library for keybindings
- [clack](https://github.com/reasonink/clack): A modern keyboard shortcut library written in Typescript
  - [clack-react](https://github.com/reasonink/clack-react): React support for @reasonink/clack
- [js-humanize](https://github.com/ollieglass/js-humanize): Humanize large numbers
- [sub-in](https://github.com/peterpme/sub-in): 🥙 A tiny (115B) find-and-replace utility for strings in Javascript
- [color-hash](https://github.com/zenozeng/color-hash): Generate color based on the given string (using HSL color space and BKDRHash)
- [title](https://github.com/zeit/title): A service for capitalizing your title properly
- [string-similarity](https://github.com/aceakash/string-similarity): Finds degree of similarity between two strings, based on Dice's Coefficient, which is mostly better than Levenshtein distance
- [cuid](https://github.com/ericelliott/cuid): Collision-resistant ids optimized for horizontal scaling and performance
- [obj-str](https://github.com/lukeed/obj-str): A tiny (96B) library for serializing Object values to Strings. Also serves as a faster & smaller drop-in replacement for the classnames module
- [clsx](https://github.com/lukeed/clsx): A tiny (223B) utility for constructing className strings conditionally. Also serves as a faster & smaller drop-in replacement for the classnames module
- [xstate](https://xstate.js.org/docs): State machines and statecharts for the modern web
- [tasktimer](https://github.com/onury/tasktimer): An accurate timer utility for running periodic tasks on the given interval ticks or dates. (Node and Browser)
- [rough-notation](https://github.com/rough-stuff/rough-notation): Create and animate hand-drawn annotations on a web page

### Async

- [axios](https://github.com/axios/axios): Promise based HTTP client for the browser and node.js
  - [axios-retry](https://github.com/softonic/axios-retry): Axios plugin that intercepts failed requests and retries them whenever possible
- [redaxios](https://github.com/developit/redaxios): The Axios API, as an 800 byte Fetch wrapper
- [cross-fetch](https://github.com/lquixada/cross-fetch): Universal WHATWG Fetch API for Node, Browsers and React Native
- [awaity](https://github.com/asfktz/Awaity.js): A functional, lightweight alternative to bluebird.js, built with `async` / `await` in mind
- [loadjs](https://github.com/muicss/loadjs): A tiny async loader / dependency manager for modern browsers (789 bytes)
- [await-to-js](https://github.com/scopsy/await-to-js): Async await wrapper for easy error handling without try-catch

### Node

- [Fastify](https://www.fastify.io/): Fast and low overhead web framework, for Node.js
- [Express](https://expressjs.com)
  - [helmet](https://github.com/helmetjs/helmet): Help secure Express apps with various HTTP headers
  - [reqresnext](https://github.com/antongolub/reqresnext): Tiny helper for express middleware testing
  - [lusca](https://github.com/krakenjs/lusca): Application security for express apps
  - [cookie-session](https://github.com/expressjs/cookie-session): Simple cookie-based session middleware
- [nodebestpractices](https://github.com/i0natan/nodebestpractices): The largest Node.JS best practices list. Curated from the top ranked articles and always updated
- [dumper.js](https://github.com/zeeshanu/dumper.js): A better and pretty variable inspector for your Node.js applications
- [http-terminator](https://github.com/gajus/http-terminator): Gracefully terminates HTTP(S) server
- [uuid](https://github.com/uuidjs/uuid): Generate RFC-compliant UUIDs in JavaScript
- [http-errors](https://github.com/jshttp/http-errors): Create HTTP Errors
- [boom](https://github.com/hapijs/boom): HTTP-friendly error objects
- [deno](https://github.com/denoland/deno): A secure JavaScript and TypeScript runtime
- [nanomatch](https://github.com/micromatch/nanomatch): Fast, minimal glob matcher for node.js. Similar to micromatch, minimatch and multimatch, but without support for extended globs (extglobs), posix brackets or braces, and with complete Bash 4.3 wildcard support: ("\*", "\*\*", and "?")
- [yn](https://github.com/sindresorhus/yn): Parse yes/no like values
- [ncp](https://github.com/AvianFlu/ncp): Asynchronous recursive file copying with Node.js

#### Logging

- [pino](https://github.com/pinojs/pino): 🌲 super fast, all natural json logger 🌲
- [caterpillar](https://github.com/bevry/caterpillar): Caterpillar is the ultimate logging system for Deno, Node.js, and Web Browsers
- [cabin](https://github.com/cabinjs/cabin): Cabin is the best JavaScript and Node.js logging service and logging npm package

### Responsive

- [responsive-watch](https://github.com/pauldijou/responsive-watch): Watch some media queries and react when they change
- [tornis](https://github.com/robb0wen/tornis): Tornis helps you watch and respond to changes in your browser's viewport 🌲
- [actual](https://github.com/ryanve/actual): Determine actual CSS media query breakpoints via JavaScript

### Media and Images

- [images-loaded](https://github.com/awcross/images-loaded): Wait for images to load using promises. No dependencies.
- [lazysizes](https://github.com/aFarkas/lazysizes): High performance and SEO friendly lazy loader for images (responsive and normal), iframes and more, that detects any visibility changes triggered through user interaction, CSS or JavaScript without configuration.

#### Image services

- [sharp](https://github.com/lovell/sharp): High performance Node.js image processing, the fastest module to resize JPEG, PNG, WebP and TIFF images. Uses the libvips library.
- [IMGIX](https://www.imgix.com/): Real-time image processing and image CDN

### Date

- [date-fns](https://date-fns.org/): Modern JavaScript date utility library
- [tinydate](https://github.com/lukeed/tinydate): A tiny (337B) reusable date formatter. Extremely fast!
- [tinytime](https://github.com/aweary/tinytime): ⏰ A straightforward date and time formatter in <1kb

### Scrolling

- [scroll-watcher](https://github.com/jonataswalker/scroll-watcher)
- [scrolldir](https://github.com/dollarshaveclub/scrolldir): Leverage Vertical Scroll Direction with CSS

### Carousels

- [Flickity](https://flickity.metafizzy.co/)
- [Swiper](http://idangero.us/swiper/)

### Animation

- [ramjet](https://github.com/Rich-Harris/ramjet): Morph DOM elements from one state to another with smooth animations and transitions
- [anime](https://github.com/juliangarnier/anime): JavaScript Animation Engine
- [GSAP](https://greensock.com/):the standard for JavaScript HTML5 animation | GreenSock
- [Vanilla-tilt.js](https://micku7zu.github.io/vanilla-tilt.js/index.html): A smooth 3D tilt javascript library forked from Tilt.js

### Web workers

- [workerize](https://github.com/developit/workerize): Run a module in a Web Worker
- [greenlet](https://github.com/developit/greenlet): Move an async function into its own thread. A simplified single-function version of workerize.

### Immutable

- [immer](https://github.com/mweststrate/immer): Create the next immutable state tree by simply modifying the current tree
  - [use-immer](https://github.com/immerjs/use-immer): Use immer to drive state with a React hooks
- [unchanged](https://github.com/planttheidea/unchanged): A tiny, fast, unopinionated handler for updating JS objects and arrays immutably
- [seamless-immutable](https://github.com/rtfeldman/seamless-immutable): Immutable data structures for JavaScript which are backwards-compatible with normal JS Arrays and Objectsseamless-immutable`
- [mutik](https://github.com/jaredpalmer/mutik): A tiny (495B) immutable state management library based on Immer

### Typography

- [fitty](https://github.com/rikschennink/fitty): Makes text fit perfectly

### Polyfills

- [resize-observer-polyfill](https://github.com/que-etc/resize-observer-polyfill):A polyfill for the Resize Observer API

## ⚛️ React

[reactjs.org](https://reactjs.org)

- [create-react-app](https://github.com/facebook/create-react-app): Create React apps with no build configuration
  - [react-app-rewired](https://github.com/timarney/react-app-rewired): Override create-react-app webpack configs without ejecting
- [react-bits](https://github.com/vasanthk/react-bits): ✨ React patterns, techniques, tips and tricks ✨

### React-specific libs:

- [react-powerplug](https://github.com/renatorib/react-powerplug): Renderless Containers
- [formik](https://github.com/jaredpalmer/formik): Build forms in React, without the tears 😭
- [react-router](https://github.com/ReactTraining/react-router): Declarative routing for React
- [Reach Router](https://reach.tech/router)
- [react-fns](https://react-fns.netlify.com/): React Components for common Web APIs
- [react-portal](https://github.com/tajo/react-portal): React component for transportation of modals, lightboxes, loading bars... to document.body
- [react-ideal-image](https://github.com/stereobooster/react-ideal-image): 🖼️ An Almost Ideal React Image Component
- [react-adopt](https://github.com/pedronauck/react-adopt): Compose render props components like a pro
- [downshift](https://github.com/paypal/downshift)
- [react-loadable](https://github.com/jamiebuilds/react-loadable): A higher order component for loading components with promises
- [react-portal](https://github.com/tajo/react-portal): React component for transportation of modals, lightboxes, loading bars... to document.body
- [js-lingui: 🌍📖](https://github.com/lingui/js-lingui): A readable, automated, and optimized (5 kb) internationalization (Intl / i18n) for JavaScript
- [react-mq](https://github.com/u-wave/react-mq): Barebones CSS media query component for React, ~560 bytes
- [react-media](https://github.com/ReactTraining/react-media): CSS media queries for React. This is SSR compatible as well.
- [merge-props](https://github.com/andrewbranch/merge-props): Merges className, style, and event handler props for React elements
- [react-uid](https://github.com/thearnica/react-uid): Render-less container for generating UID for a11y, consistent react key, and any other good reason 🦄
- [clsx](https://github.com/lukeed/clsx): A tiny (229B) utility for constructing `className` strings conditionally
- [Framer Motion](https://www.framer.com/motion/): An open source React library to power production-ready animations. Design fluid animations for the web, across desktop and mobile
- [react-axe](https://github.com/dequelabs/react-axe): Accessibility auditing for React.js applications
- [use-click-away](https://github.com/geobde/use-click-away): React hook to detect click or touch events outside an element
- [react-tiny-virtual-list](https://github.com/clauderic/react-tiny-virtual-list): A tiny but mighty 3kb list virtualization library, with zero dependencies 💪 Supports variable heights/widths, sticky items, scrolling to index, and more!
- [react-laag](https://github.com/everweij/react-laag): Primitives to build things like tooltips, dropdown menu's and popovers in React
- [react-dnd](https://github.com/react-dnd/react-dnd): Drag and Drop for React

#### React Hooks

- [swr](https://github.com/zeit/swr): React Hooks library for remote data fetching
- [Hooks.Guide](https://www.hooks.guide/): Collection of React hooks curated by the community
- [useHooks](https://usehooks.com/): Easy to understand React Hook recipes
- [beautiful-react-hooks](https://github.com/beautifulinteractions/beautiful-react-hooks): 🔥A collection of beautiful and (hopefully) useful React hooks to speed-up your components and hooks development 🔥
- [react-adaptive-hooks](https://github.com/GoogleChromeLabs/react-adaptive-hooks): Deliver experiences best suited to a user's device and network constraints

### State management

- [zustand](https://github.com/react-spring/zustand): 🐻 Bear necessities for state management in React
- [redux](https://github.com/reduxjs/redux): Predictable state container for JavaScript apps
  - [reselect](https://github.com/reduxjs/reselect): Selector library for Redux
  - [redux-saga](https://github.com/redux-saga/redux-saga): An alternative side effect model for Redux apps
    - [redux-saga-routines](https://github.com/afitiskin/redux-saga-routines): Routines for redux-saga
  - [redux-thunk](https://github.com/reduxjs/redux-thunk): Thunk middleware for Redux
  - [awesome-redux](https://github.com/brillout/awesome-redux): Catalog of Redux Libraries & Learning Material
- [parket](https://github.com/ForsakenHarmony/parket): A library to manage application state, heavily inspired by mobx-state-tree
- [unstated](https://github.com/jamiebuilds/unstated): State so simple, it goes without saying
- [mergeState](https://github.com/zhujinxuan/mergeState): How to Stop Worrying and Use Nested Object/Array in React/Redux States
- [effector](https://github.com/zerobias/effector): The state manager ☄️
- [Recoil](https://github.com/facebookexperimental/Recoil): Recoil is an experimental state management library for React apps. It provides several capabilities that are difficult to achieve with React alone, while being compatible with the newest features of React.

### Server-rendered React

- [Next.js](https://nextjs.org/) ([repo](https://github.com/zeit/next.js)): - Framework for server-rendered or statically-exported React apps
  - [next-plugins](https://github.com/zeit/next-plugins)

### Static site generators

- [Gatsby](https://www.gatsbyjs.org/): Blazing fast static site generator for React

### Microservices/Serverless

- [micro](https://github.com/zeit/micro)
  - [awesome-micro](https://github.com/amio/awesome-micro)

## TypeScript

[typescriptlang.org](https://www.typescriptlang.org/)

- [What's new in TypeScript](https://github.com/Microsoft/TypeScript/wiki/What's-new-in-TypeScript): Microsoft/TypeScript Wiki
- [TypeScript Deep Dive](https://basarat.gitbooks.io/typescript/)
- [TypeScript Evolution](https://blog.mariusschulz.com/series/typescript-evolution)
- [JSON to Typescript Interface](https://transform.now.sh/json-to-ts-interface/)
- [react-typescript-cheatsheet](https://github.com/sw-yx/react-typescript-cheatsheet): a cheatsheet for react users using typescript with react for the first (or nth!) time
- [clean-code-typescript](https://github.com/labs42io/clean-code-typescript): Clean Code concepts adapted for TypeScript

# Command Line, Terminal and shells

[Fish shell](https://fishshell.com/): The user-friendly command line shell

- [My fish_config](https://github.com/mrmartineau/fish)
- [awesome-fish](https://github.com/jorgebucaran/awesome-fish): A curated list of packages, prompts, and resources for the amazing fish shell
- [Starship](https://starship.rs/): Cross-Shell Prompt
- [tide](https://github.com/IlanCosman/tide): 🌊 A modern prompt manager for the Fish shell

## Creating CLI apps

- [gluegun](https://github.com/infinitered/gluegun): A delightful toolkit for building Node-powered CLIs
- [inquirer](https://github.com/SBoudrias/Inquirer.js): A collection of common interactive command line user interfaces
- [commander](https://github.com/tj/commander.js): node.js command-line interfaces made easy
- [sade](https://github.com/lukeed/sade): Sade is a small but powerful tool for building command-line interface (CLI) applications for Node.js that are fast, responsive, and helpful!

## CLI apps

- [hub](https://hub.github.com/): hub is an extension to command-line git that helps you do everyday GitHub tasks without ever leaving the terminal
- [serve](https://github.com/zeit/serve): Static file serving and directory listing
- [awesome-cli-apps](https://github.com/agarrharr/awesome-cli-apps): A curated list of command line apps
- [SpaceVim](https://github.com/SpaceVim/SpaceVim): A community-driven modular vim distribution - The ultimate vim configuration

# Tooling

## Code bundlers

- [preconstruct](https://github.com/preconstruct/preconstruct): 🎁 Dev and build your code painlessly in monorepos
- [Webpack](https://webpack.js.org/): script/asset bundler
  - [Webpack recipes](https://github.com/mrmartineau/webpack-recipes)
  - [ifdef-loader](https://github.com/nippur72/ifdef-loader): Webpack loader for JavaScript/TypeScript conditional compilation
- [Parcel](https://parceljs.org/): Blazing fast, zero configuration web application bundler
- [microbundle](https://github.com/developit/microbundle): Zero-configuration bundler for tiny modules
- [rollup.js](https://rollupjs.org/guide/en): Rollup is a module bundler for JavaScript
- [ncc](https://github.com/zeit/ncc): Node.js Compiler Collection. Simple CLI for compiling a Node.js module into a single file, together with all its dependencies, gcc-style.
- [fastpack](https://github.com/fastpack/fastpack): Pack JS code into a single bundle fast & easy

## Package management and publishing

- [np](https://github.com/sindresorhus/np): A better `npm publish`
- [size-limit](https://github.com/ai/size-limit): Prevent JS libraries bloat. If you accidentally add a massive dependency, Size Limit will throw an error
- [bundlesize](https://github.com/siddharthkp/bundlesize): Keep your bundle size in check
- [nps](https://github.com/kentcdodds/nps): All the benefits of npm scripts without the cost of a bloated package.json and limits of json
- [Dependabot](https://dependabot.com/): Dependabot creates pull requests to keep your dependencies secure and up-to-date
- [npm-config](https://github.com/npm/npm/blob/1fa9169ac9687f0be4156574279a968a48dd2458/doc/misc/npm-config.md) (docs): More than you probably want to know about npm configuration
- [patch-package](https://github.com/ds300/patch-package): Fix broken node modules with no fuss 📦👌
- [madge](https://github.com/pahen/madge): Create graphs from your CommonJS, AMD or ES6 module dependencies

## Commit hooks

- [lefthook](https://github.com/Arkweid/lefthook): Fast and powerful Git hooks manager for any type of projects
- [husky](https://github.com/typicode/husky): Git hooks made easy
- [lint-staged: 🚫💩](https://github.com/okonet/lint-staged): Run linters on git staged files
- [lefthook](https://github.com/Arkweid/lefthook): Fast and powerful Git hooks manager for any type of projects

# Testing

- [Jest](https://facebook.github.io/jest/): Delightful JavaScript Testing
  - [majestic](https://github.com/Raathigesh/majestic): Zero config UI for Jest
  - [jest-chain](https://github.com/mattphillips/jest-chain): Chain Jest matchers together to create one powerful assertion 🃏⛓
  - [jest-extended](https://github.com/jest-community/jest-extended): - Additional Jest matchers 🃏💪
  - [snapshot-diff](https://github.com/jest-community/snapshot-diff): Diffing snapshot utility for Jest
  - [jest-date-mock](https://github.com/hustcc/jest-date-mock): 🌗 Mock `Date` when run unit test cases with jest. Make tests of Date easier
- [Cypress](https://cypress.io): end-to-end testing
  - [cypress-testing-library](https://github.com/kentcdodds/cypress-testing-library): 🐅 Simple and complete custom Cypress commands and utilities that encourage good testing practices
  - [cypress-axe](https://github.com/avanslaars/cypress-axe): Custom commands for Cypress to run a11y checks with axe-core
  - [start-server-and-test](https://github.com/bahmutov/start-server-and-test): - Starts server, waits for URL, then runs test command; when the tests end, shuts down server
- [dom-testing-library](https://github.com/kentcdodds/dom-testing-library): 🐙 Simple and complete DOM testing utilities that encourage good testing practices
- [react-testing-library 🐐](https://github.com/testing-library/react-testing-library): Simple and complete React DOM testing utilities that encourage good testing practices
  - [react-testing-library](https://react-testing-examples.com/): React Testing Examples
  - [react-hooks-testing-library](https://github.com/testing-library/react-hooks-testing-library): 🐏 Simple and complete React hooks testing utilities that encourage good testing practices
- [Chance](https://github.com/chancejs/chancejs): Random generator helper for JavaScript
- [faker.js](https://github.com/Marak/faker.js): generate massive amounts of fake data in Node.js and the browser
- [nock](https://github.com/nock/nock): HTTP server mocking and expectations library for Node.js
- [Stryker Mutator](http://stryker-mutator.io/)
- [given2](https://github.com/tatyshev/given2): Lazy variable evaluation for Jasmine, Mocha, Jest specs, inspired by Ruby and Rspec 💎
- [benny](https://github.com/caderek/benny): A dead simple benchmarking framework for JS/TS libs
- [benchmark.js](https://github.com/bestiejs/benchmark.js): A benchmarking library. As used on jsPerf.com

- [ui-testing-best-practices](https://github.com/NoriSte/ui-testing-best-practices): The largest UI testing best practices list (lat update: April 2020) (work in progress)

## Code formatting and linting

- [Prettier](https://prettier.io/)
  - [precise-commits](https://github.com/nrwl/precise-commits): Painlessly apply Prettier by only formatting lines you have modified anyway!
  - [pretty-quick](https://github.com/azz/pretty-quick): Runs Prettier on your changed files
- [Eslint](https://eslint.org)
  - [eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier): ESLint plugin for prettier formatting
  - [eslint-config-prettier](https://github.com/prettier/eslint-config-prettier): Turns off all rules that are unnecessary or might conflict with Prettier
  - [eslint-plugin-react](https://github.com/yannickcr/eslint-plugin-react): - React specific linting rules for ESLint

## Miscellaneous

- [npm-run-all](https://github.com/mysticatea/npm-run-all): A CLI tool to run multiple npm-scripts in parallel or sequential
- [cross-port-killer](https://github.com/milewski/cross-port-killer): Kill the process running on a given TCP port on Windows, Linux and Mac
- [envinfo](https://github.com/tabrindle/envinfo): Generate a report about your development environment for debugging and issue reporting
- [mkcert](https://github.com/FiloSottile/mkcert): A simple zero-config tool to make locally trusted development certificates with any names you'd like

# Progressive Web Apps

- [Workbox](https://developers.google.com/web/tools/workbox/) & ([repo](https://github.com/GoogleChrome/workbox)): JavaScript libraries for Progressive Web Apps

# Code Sandboxes

- [CodeSandbox](https://codesandbox.io/): CodeSandbox is perfect for React demo apps
- [Codepen](http://codepen.io/): Codepen is perfect for non-React front-end demos and prototypes
- [CodeShare](http://codeshare.io/): Codeshare is useful for collaborating on a single file if devs are not in the same room
- [Glitch](https://glitch.com/)

# APIs

- [Postman](https://www.getpostman.com/): used to develop, test and monitor APIs
- [MockAPI](http://www.mockapi.io/): create a mock API
- [jsonbin](https://jsonbin.org/): A personal JSON store as a RESTful service
- [test-cors.org](http://www.test-cors.org/)
- [Reqres](https://reqres.in/): A hosted REST-API ready to respond to your AJAX requests
- [Mirage JS](https://miragejs.com/): An API mocking library for frontend developers
- [Postwoman](https://postwoman.io/): API request builder

## GraphQL

- [GraphQL Playground](https://www.graphqlbin.com)
- [Apollo GraphQL](https://www.apollographql.com/): Apollo Data Graph Platform— unify APIs, microservices, and databases into a data graph that you can query with GraphQL
  - [Apollo Client (React)](https://www.apollographql.com/docs/react/): Apollo React GraphQL Docs
  - [graphql-directives](https://github.com/Saeris/graphql-directives): 🧭 A collection of custom GraphQL Schema Directives for use with Apollo Server
- [urql](https://github.com/FormidableLabs/urql): The highly customizable and versatile GraphQL client
- [graphql-lodash](https://github.com/APIs-guru/graphql-lodash): 🛠 Data manipulation for GraphQL queries with lodash syntax

# JSON

- [JSON generator](https://next.json-generator.com/): generate a lot of custom JSON for your app/site
- [JSON Editor Online](https://jsoneditoronline.org/): view/edit JSON in a better format
- [fx](https://github.com/antonmedv/fx): Command-line tool and terminal JSON viewer 🔥

# HTML

- [github.com/joshbuchea/HEAD](https://github.com/joshbuchea/HEAD): the definitive resource for everything that _could_ go in the head of your document
- [MetaTags.io](https://metatags.io/): Preview, Edit and Generate
- [HEY META](https://www.heymeta.com/): Website Meta Tag Check
- [Rich Link Preview](https://richpreview.com/)

# SVG

- [A Practical Guide to SVGs on the web](https://svgontheweb.com/)
- [Get Waves](https://getwaves.io/): Create SVG waves for your next design
- [Blobmaker](https://www.blobmaker.app/): Make organic SVG shapes for your next design
- [flubber](https://github.com/veltman/flubber): Tools for smoother shape animations
- [Hero Patterns](http://www.heropatterns.com/): Free repeatable SVG background patterns for your web projects

## Icons

- [ICONSVG](https://iconsvg.xyz/): Quick customizable SVG icons for your project
- [Simple Icons](https://simpleicons.org/)
- [React Icons](https://react-icons.github.io/react-icons/#/)
- [Evil Icons](https://evil-icons.io/)
- [Icon Font & SVG Icon Sets ❍ IcoMoon](https://icomoon.io/)
- [SVG PORN](https://svgporn.com/)
- [Feather](https://feathericons.com/): Simply beautiful open source icons
  - [react-feather](https://github.com/feathericons/react-feather): React component for Feather icons
- [System UIcons](https://systemuicons.com/)

## SVG/Image Media compression

- [Squoosh](https://squoosh.app/)
- [SVGOMG](https://jakearchibald.github.io/svgomg/): SVGO's Missing GUI

# Conversions and unicode

- [Transform](https://transform.now.sh/): All important transforms at one place ⭐️⭐️⭐️ this is so useful
- [SVGR](https://svgr.now.sh/): The SVG to JSX transformer
- [svg2jsx](https://svg2jsx.herokuapp.com/)
- [JSON to JavaScript object literal](https://json-to-js.com/)
- [Unminify JS, CSS and HTML Code](https://unminify.com/)
- [Multi-Encoder](https://encoder.internetwache.org/#tab_uni)
- [Unicode code converter](https://r12a.github.io/app-conversion/)

# Features and feature detection

- [Can I Use...](https://caniuse.com/): Browser support tables for modern web technologies (HTML5, CSS3, JavaScript etc)
- [Kangax JavaScript compatibility table](http://kangax.github.io/compat-table/es6/)

# Performance

- [Bundlephobia](https://bundlephobia.com/): find the cost of adding a npm package to your bundle

## Performance testing and monitoring

- [WebPageTest](https://www.webpagetest.org/)
- [Lighthouse](https://developers.google.com/web/tools/lighthouse/)
- [Calibre](https://calibreapp.com/)
- [Website Speed Test Image Analysis Tool](https://webspeedtest.cloudinary.com/) by Cloudinary

# Design

- [Subtract Guides](https://subtract.design/entry/forms): Simple Rules for Designing Web & Mobile Forms

# Design Systems and documentation

- [Storybook](https://storybook.js.org/): UI dev environment you'll love to use
- [react-styleguidist](https://github.com/styleguidist/react-styleguidist): - Isolated React component development environment with a living style guide
- [Docusaurus](https://docusaurus.io/): Easy to Maintain Open Source Documentation Websites
- [Docz](https://www.docz.site/)
- [design-system-utils](https://github.com/mrmartineau/design-system-utils): - Design system framework for modern front-end projects
- [Docute](https://docute.org/): The fastest way to create a documentation site for your project
- [playroom](https://github.com/seek-oss/playroom): Design with JSX, powered by your own component library

# Accessibility (A11y)

Accessibility is an extremely important part of any web project. While the SOW, functional spec or user-stories might not directly mention a11y, it is up to each developer to ensure that best efforts are made to make our websites as accessible as possible.

## A11y tools and resources:

- [Interactive WCAG](http://code.viget.com/interactive-wcag/): guidelines - cheatsheet for A, AA & AAA
- [awesome-a11y](https://github.com/brunopulis/awesome-a11y): massive list of a11y-related resources & information
- [tenon.io](https://tenon.io/): a11y tester
- [a11yproject.com/checklist.html](http://a11yproject.com/checklist.html): - a11y checklist
- [a11yproject.com](http://a11yproject.com/): a11y resources
- [w3.org/WAI/ER/tools/](https://www.w3.org/WAI/ER/tools/): list of a11y tools from the W3C
- [allyjs.io](https://allyjs.io/index.html): JavaScript library to help modern web applications with accessibility concerns by making accessibility simpler
- [Four principles of Accessibility](https://www.w3.org/TR/UNDERSTANDING-WCAG20/intro.html#introduction-fourprincs-head)
- [Aria landmarks example](https://w3c.github.io/aria-practices/examples/landmarks/index.html)
- [A11y Style-guide](http://a11y-style-guide.com/style-guide/): markup examples and best practices
- [Inclusive Components](https://inclusive-components.design/): A blog trying to be a pattern library. All about designing inclusive web interfaces, piece by piece.
- [Color contrast checker](http://leaverou.github.io/contrast-ratio/)
- [Accessible color palette builder](https://toolness.github.io/accessible-color-matrix/): An prototype to help designers build accessible color palettes
- [Practical ARIA Examples](http://heydonworks.com/practical_aria_examples/)
- [Nutrition Cards for Accessible Components A11Y Expectations](https://davatron5000.github.io/a11y-nutrition-cards/)
- [Web Accessibility Tutorials](https://www.w3.org/WAI/tutorials/): Guidance on how to create websites that meet WCAG

### A11y Chrome extensions

- [Accessibility Insights for Web](https://chrome.google.com/webstore/detail/accessibility-insights-fo/pbjjkligggfmakdaogkfomddhfmpjeni)
- [Color Contrast Analyzer](https://chrome.google.com/webstore/detail/color-contrast-analyzer/dagdlcijhfbmgkjokkjicnnfimlebcll)
- [NoCoffee](https://chrome.google.com/webstore/detail/nocoffee/jjeeggmbnhckmgdhmgdckeigabjfbddl): has options for testing color blindness and other sight-related issues

# DevOps

[HTTP Status Codes](https://httpstatuses.com/)

## Continuous integration

- [CircleCI](https://circleci.com): Paid.
- [Bitrise](https://bitrise.com): Paid. For iOS/Android apps
- [Travis CI](https://travisci.com): Free for open-source

## Docker

- [dockle](https://github.com/goodwithtech/dockle): Container Image Linter for Security, Helping build the Best-Practice Docker Image, Easy to start

## Hosting

- [Vercel](https://vercel.com)
- [Netlify](https://netlify.com)

## Domains

- [iwantmyname](https://iwantmyname.com/)

# Design

## Typography

- [Modular Scale](http://modularscale.com/)
- [Adaptive Modular Scale](https://codepen.io/getflourish/full/vXqewy/)
- [Type Scale - A Visual Calculator](http://type-scale.com/)

# IDEs and Text Editors

## VS Code

- [My VS Code extensions](https://gist.github.com/mrmartineau/28ef03c53275ea468e470532d6d20449)
- [My preferences](https://gist.github.com/mrmartineau/ea3b428124bc1e31cd46dfa55469d781)
- [awesome-vscode](https://github.com/viatsko/awesome-vscode): 🎨 A curated list of delightful VS Code packages and resources

## Programming fonts

- [IBM Plex Mono](https://www.ibm.com/plex/)
- [iA-Fonts](https://github.com/iaolo/iA-Fonts)
- [Input: Fonts for Code](http://input.fontbureau.com/)
- [FiraCode](https://github.com/tonsky/FiraCode)
- [fantasque-sans](https://github.com/belluzj/fantasque-sans)
- [Jet Brains Mono](https://github.com/JetBrains/JetBrainsMono)

## Code colour schemes

- [Monokai Pro](https://monokai.pro/)
- [Ayu (Mirage)](https://marketplace.visualstudio.com/items?itemName=teabyii.ayu)
- [Dracula](https://draculatheme.com/visual-studio-code/): A dark theme for Visual Studio Code and 50+ apps
- [Oceanic Next Theme](https://marketplace.visualstudio.com/items?itemName=gerane.Theme-OceanicNext)
- [🌌 Night Owl](https://github.com/sdras/night-owl-vscode-theme): A VS Code dark theme for contrast for nighttime coding
- [Nord](https://marketplace.visualstudio.com/items?itemName=arcticicestudio.nord-visual-studio-code)
- [VSCodeThemes](https://vscodethemes.com/)
- [themer](https://github.com/mjswensen/themer): 🎨 themer takes a set of colors and generates themes for your apps (editors, terminals, wallpapers, and more)

# Regular expressions

- [Regex101](https://regex101.com/): Online regex tester and debugger: PHP, PCRE, Python, Golang and JavaScript

# Learning resources

- [Web Skills](https://andreasbm.github.io/web-skills/?compact): A visual overview of useful skills to learn as a web developer

---

> If you think there are better alternatives, or that there should be something added to the list, please [create an issue](https://github.com/mrmartineau/awesome-web-dev-resources/issues/new) or [create a pull request](https://github.com/mrmartineau/awesome-web-dev-resources/pulls)
