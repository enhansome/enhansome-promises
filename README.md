<a href="https://promisesaplus.com/">
    <img src="https://promisesaplus.com/assets/logo-small.png" alt="Promises/A+ logo" align="right" />
</a>

# Awesome Promises with stars

> A curated list of useful resources for JavaScript Promises

Inspired by the [awesome](https://github.com/sindresorhus/awesome) ⭐ 502,390 | 🐛 105 | 📅 2026-09-02 list thing. Not to be confused with other awesome promises like "I promise you a million dollars" or "I promise you'll stay fit and never have to go to the gym again".

**Table of Contents**

* [Resources, Blogs, and Books](#resources-blogs-and-books)
* [Promises/A+ Implementations (ES6/ES2015 compatible)](#promisesa-implementations-es6es2015-compatible)
  * [Strict Implementations](#strict-implementations)
  * [Implementations with extras](#implementations-with-extras)
  * [Fallbacks](#fallbacks)
* [Convenience Utilities](#convenience-utilities)

## Resources, Blogs, and Books

### For beginners

* [You Don't Know JS: Promises](https://github.com/getify/You-Dont-Know-JS/blob/master/async%20&%20performance/ch3.md) ⭐ 184,785 | 🐛 2 | 📅 2026-02-15 - Chapter from [You Don't Know JS: Async & Performance](https://github.com/getify/You-Dont-Know-JS/tree/master/async%20%26%20performance) ⭐ 184,785 | 🐛 2 | 📅 2026-02-15
* [Promise Cookbook](https://github.com/mattdesl/promise-cookbook) ⭐ 1,614 | 🐛 1 | 📅 2017-06-14 - The why, what, and how. "A brief introduction \[...] primarily aimed at frontend developers".
* [Promise it won't hurt](https://github.com/stevekane/promise-it-wont-hurt) ⭐ 738 | 🐛 45 | 🌐 JavaScript | 📅 2021-04-21 - An interactive [nodeschool](https://nodeschool.io/) workshop
* [Promises for Asynchronous Programming](http://exploringjs.com/es6/ch_promises.html) - Chapter from [Exploring ES6](http://exploringjs.com/)
* [JavaScript Promises: an Introduction](https://developers.google.com/web/fundamentals/getting-started/primers/promises) - Basics of JavaScript's native promise implementation.
* [JavaScript with Promises](http://shop.oreilly.com/product/0636920032151.do) - from O'Reilly. Short and to-the-point. Uses native and bluebird.
* [ES6 Kata Promises](http://es6katas.org/) - Promises Katas : [Basics](http://tddbin.com/#?kata=es6/language/promise/basics)
* [ES6 Promises in Depth](https://ponyfoo.com/articles/es6-promises-in-depth)
* [An Incremental Tutorial on Promises](http://www.sohamkamani.com/blog/2016/08/28/incremenal-tutorial-to-promises/) - An FAQ styled tutorial for beginners.

### Deep Dive

* [Promise anti-patterns](https://github.com/petkaantonov/bluebird/wiki/Promise-anti-patterns) ⭐ 20,489 | 🐛 131 | 🌐 JavaScript | 📅 2024-11-07 - Common misuses and how to avoid them.
* [Promise Fun](https://github.com/sindresorhus/promise-fun) ⭐ 5,168 | 🐛 0 | 📅 2024-04-25 - @sindresorhus's notes, patterns, and solutions to common Promise problems
* [You're Missing the Point of Promises](https://blog.domenic.me/youre-missing-the-point-of-promises/) - Promises are much more than callback aggregation, and that jQuery's implementation (prior to 3.0) isn't enough.
* [We have a problem with promises](https://pouchdb.com/2015/05/18/we-have-a-problem-with-promises.html) - "Many of us are using promises without really understanding them."
* [Promise anti-patterns (2)](http://taoofcode.net/promise-anti-patterns/) - Another set of promises anti-patterns
* [Promise Ponderings, (Anti-)Patterns, and Apologies](https://sdgluck.github.io/2015/08/24/promise-ponderings-patterns-apologies/) - Promise behaviour demonstrated and explained by common questions and their answers.
* [Javascript Promises...In Wicked Detail](http://www.mattgreer.org/articles/promises-in-wicked-detail/) - Recreate the promise implementation
* [Writing Promise-Using Specifications](https://www.w3.org/2001/tag/doc/promises-guide) - "This document gives guidance on how to write specifications that create, accept, or manipulate promises"
* [Async functions - making promises friendly](https://developers.google.com/web/fundamentals/getting-started/primers/async-functions)

### References

* [Fates and States](https://github.com/domenic/promises-unwrapping/blob/master/docs/states-and-fates.md) ⚠️ Archived - Quick definitions of possible states.
* [Promises/A+ specification](https://promisesaplus.com/)
* [caniuse promises](http://caniuse.com/#feat=promises)
* [Promisees](https://bevacqua.github.io/promisees/) - Promise visualization playground for the adventurous.

## Promises/A+ Implementations (ES6/ES2015 compatible)

### Strict Implementations

These implement no more or less than the es6 spec. They make great polyfills and are exceptionally compatible with native promises.

* [es6-promise](https://github.com/stefanpenner/es6-promise) ⭐ 7,253 | 🐛 26 | 🌐 JavaScript | 📅 2022-11-14 - Opt-in polyfill. A strict-spec subset of rsvp.js.
* [lie](https://github.com/calvinmetcalf/lie) ⭐ 742 | 🐛 5 | 🌐 JavaScript | 📅 2020-08-21 - Small, browserifyable with an opt-in polyfill.
* [native-promise-only](https://github.com/getify/native-promise-only) ⚠️ Archived - Polyfill. Browser and node-compatible.
* [pinkie](https://github.com/floatdrop/pinkie) ⚠️ Archived - Ponyfill. Node-oriented, but [browserifyable](https://github.com/substack/node-browserify) ⭐ 14,699 | 🐛 380 | 🌐 JavaScript | 📅 2024-12-21. *Extremely* small implementation.

### Implementations with extras

All of these provide more features than the language yet remain compatible. Node + Browsers for all.

* [bluebird](https://github.com/petkaantonov/bluebird) ⭐ 20,489 | 🐛 131 | 🌐 JavaScript | 📅 2024-11-07 - Fully featured, extremely performant. Long stack traces & generator/coroutine support.
* [Q](https://github.com/kriskowal/q) ⚠️ Archived - One of the original implementations. Long stack traces and other goodies.
* [rsvp.js](https://github.com/tildeio/rsvp.js/) ⭐ 3,594 | 🐛 17 | 🌐 JavaScript | 📅 2023-10-27 - Lightweight with a few extras. Compatible down to IE6!
* [when.js](https://github.com/cujojs/when) ⭐ 3,421 | 🐛 67 | 🌐 JavaScript | 📅 2022-04-10 - Packed with control flow, functional, and utility methods.
* [then/promise](https://github.com/then/promise) ⭐ 2,587 | 🐛 24 | 🌐 JavaScript | 📅 2023-10-21 - Small with `nodeify`, `denodify` and `done()` additions.
* [creed](https://github.com/briancavalier/creed) ⭐ 277 | 🐛 16 | 🌐 JavaScript | 📅 2018-05-29 - Hyper performant & full featured like Bluebird, but FP-oriented. Coroutines, generators, promises, ES2015 iterables, & fantasy-land spec.

### Fallbacks

* [any-promise](https://github.com/kevinbeaty/any-promise) ⭐ 180 | 🐛 6 | 🌐 JavaScript | 📅 2018-10-01 - Loads the first available implementation. Safe for browserify.
* [pinkie-promise](https://github.com/floatdrop/pinkie-promise) ⚠️ Archived - Use native, or fall back to `pinkie`. Great for node library authors.
* [native-or-bluebird](https://www.npmjs.com/package/native-or-bluebird) - Helps transition to completely native.

## Convenience Utilities

Native and strictly spec-compliant promises are awesome for compatibility, future-proofness, library authors, and browsers. However, libraries like bluebird patch goodies onto the `Promise` constructor and prototype. Solution? tiny modules of course!

### sindresorhus's many Promise utilities ([see notes](https://github.com/sindresorhus/promise-fun) ⭐ 5,168 | 🐛 0 | 📅 2024-04-25)

* [p-queue](https://github.com/sindresorhus/p-queue) ⭐ 4,265 | 🐛 7 | 🌐 TypeScript | 📅 2026-07-22 - Promise queue with concurrency control
* [p-limit](https://github.com/sindresorhus/p-limit) ⭐ 2,919 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-31 - Run multiple promise-returning & async functions with limited concurrency
* [p-map](https://github.com/sindresorhus/p-map) ⭐ 1,510 | 🐛 12 | 🌐 JavaScript | 📅 2026-08-27 - Map over promises concurrently
* [pify](https://github.com/sindresorhus/pify) ⭐ 1,503 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-23 - Promisify ("denodify") a callback-style function.
* [p-retry](https://github.com/sindresorhus/p-retry) ⭐ 1,030 | 🐛 1 | 🌐 JavaScript | 📅 2026-09-01 - Retry a promise-returning or async function
* [delay](https://github.com/sindresorhus/delay) ⭐ 624 | 🐛 0 | 🌐 JavaScript | 📅 2025-10-31 - Delay a promise a specified amount of time.
* [p-throttle](https://github.com/sindresorhus/p-throttle) ⭐ 519 | 🐛 0 | 🌐 JavaScript | 📅 2025-11-08 - Throttle promise-returning & async functions
* [p-memoize](https://github.com/sindresorhus/p-memoize) ⭐ 449 | 🐛 3 | 🌐 TypeScript | 📅 2026-07-26 - Memoize promise-returning & async functions
* [p-all](https://github.com/sindresorhus/p-all) ⭐ 345 | 🐛 0 | 🌐 TypeScript | 📅 2025-09-18 - Run promise-returning & async functions concurrently with optional limited concurrency
* [p-timeout](https://github.com/sindresorhus/p-timeout) ⭐ 305 | 🐛 0 | 🌐 JavaScript | 📅 2025-10-07 - Timeout a promise after a specified amount of time
* [p-lazy](https://github.com/sindresorhus/p-lazy) ⭐ 286 | 🐛 0 | 🌐 JavaScript | 📅 2024-10-28 - Create a lazy promise that defers execution until `.then()` or `.catch()` is called
* [loud-rejection](https://github.com/sindresorhus/loud-rejection) ⭐ 281 | 🐛 0 | 🌐 JavaScript | 📅 2021-01-24 - Make unhandled promise rejections fail loudly instead of the default silent fail.
* [p-debounce](https://github.com/sindresorhus/p-debounce) ⭐ 238 | 🐛 4 | 🌐 JavaScript | 📅 2025-11-11 - Debounce promise-returning & async functions
* [p-props](https://github.com/sindresorhus/p-props) ⭐ 201 | 🐛 0 | 🌐 JavaScript | 📅 2025-09-21 - Like `Promise.all()` but for `Map` and `Object`
* [p-wait-for](https://github.com/sindresorhus/p-wait-for) ⭐ 169 | 🐛 0 | 🌐 JavaScript | 📅 2025-09-21 - Wait for a condition to be true
* [p-tap](https://github.com/sindresorhus/p-tap) ⭐ 134 | 🐛 0 | 🌐 JavaScript | 📅 2021-04-08 - Tap into a promise chain without affecting its value or state
* [p-pipe](https://github.com/sindresorhus/p-pipe) ⭐ 131 | 🐛 0 | 🌐 TypeScript | 📅 2021-04-08 - Compose promise-returning & async functions into a reusable pipeline
* [hard-rejection](https://github.com/sindresorhus/hard-rejection) ⭐ 107 | 🐛 0 | 🌐 JavaScript | 📅 2022-07-08 - Make unhandled promise rejections fail hard right away instead of the default silent fail
* [p-settle](https://github.com/sindresorhus/p-settle) ⭐ 96 | 🐛 0 | 🌐 JavaScript | 📅 2026-04-11 - Settle promises concurrently and get their fulfillment value or rejection reason
* [p-defer](https://github.com/sindresorhus/p-defer) ⭐ 87 | 🐛 0 | 🌐 JavaScript | 📅 2025-09-08 - Create a deferred promise
* [p-filter](https://github.com/sindresorhus/p-filter) ⭐ 82 | 🐛 0 | 🌐 JavaScript | 📅 2026-03-22 - Filter promises concurrently
* [p-time](https://github.com/sindresorhus/p-time) ⭐ 74 | 🐛 0 | 🌐 JavaScript | 📅 2023-11-05 - Measure the time a promise takes to resolve
* [p-reduce](https://github.com/sindresorhus/p-reduce) ⭐ 73 | 🐛 0 | 🌐 JavaScript | 📅 2023-02-11 - Reduce a list of values using promises into a promise for a value
* [p-if](https://github.com/sindresorhus/p-if) ⭐ 64 | 🐛 0 | 🌐 TypeScript | 📅 2021-04-09 - Conditional promise chains
* [p-try](https://github.com/sindresorhus/p-try) ⭐ 62 | 🐛 0 | 🌐 JavaScript | 📅 2025-09-16 - `Promise#try()` ponyfill - Starts a promise chain
* [p-whilst](https://github.com/sindresorhus/p-whilst) ⭐ 57 | 🐛 0 | 🌐 JavaScript | 📅 2024-10-16 - Calls a function repeatedly while a condition returns true and then resolves the promise
* [p-any](https://github.com/sindresorhus/p-any) ⭐ 56 | 🐛 0 | 🌐 JavaScript | 📅 2022-07-09 - Wait for any promise to be fulfilled
* [p-race](https://github.com/sindresorhus/p-race) ⭐ 52 | 🐛 0 | 🌐 JavaScript | 📅 2022-12-13 - A better `Promise.race()`
* [p-each-series](https://github.com/sindresorhus/p-each-series) ⭐ 52 | 🐛 0 | 🌐 JavaScript | 📅 2022-07-08 - Iterate over promises serially
* [p-map-series](https://github.com/sindresorhus/p-map-series) ⭐ 51 | 🐛 0 | 🌐 JavaScript | 📅 2021-04-09 - Map over promises serially
* [p-finally](https://github.com/sindresorhus/p-finally) ⚠️ Archived - `Promise#finally()` ponyfill - Invoked when the promise is settled regardless of outcome
* [p-times](https://github.com/sindresorhus/p-times) ⭐ 42 | 🐛 1 | 🌐 JavaScript | 📅 2021-10-04 - Run promise-returning & async functions a specific number of times concurrently
* [p-catch-if](https://github.com/sindresorhus/p-catch-if) ⭐ 40 | 🐛 0 | 🌐 JavaScript | 📅 2021-04-09 - Conditional promise catch handler
* [p-some](https://github.com/sindresorhus/p-some) ⭐ 39 | 🐛 0 | 🌐 JavaScript | 📅 2025-09-11 - Wait for a specified number of promises to be fulfilled
* [p-log](https://github.com/sindresorhus/p-log) ⭐ 30 | 🐛 0 | 🌐 JavaScript | 📅 2021-04-09 - Log the value/error of a promise
* [p-break](https://github.com/sindresorhus/p-break) ⭐ 24 | 🐛 0 | 🌐 JavaScript | 📅 2021-04-07 - Break out of a promise chain

### Others

* [co](https://github.com/tj/co) ⭐ 11,839 | 🐛 44 | 🌐 JavaScript | 📅 2020-12-15 - Like `task.js` and `bluebird.coroutine`, but supports thunks too.
* [task.js](https://github.com/mozilla/task.js) ⭐ 1,628 | 🐛 30 | 🌐 JavaScript | 📅 2019-03-28 - Write async functions in a blocking style using promises and generators. Like `bluebird.coroutine`.
* [is-promise](https://github.com/then/is-promise) ⭐ 282 | 🐛 2 | 🌐 JavaScript | 📅 2023-04-29 - Determine if something looks like a Promise.
* [promise-semaphore](https://github.com/samccone/promise-semaphore) ⭐ 28 | 🐛 1 | 🌐 JavaScript | 📅 2016-09-15 - Push a set of work to be done in a configurable serial fashion
* [sprom](https://github.com/then/sprom) ⭐ 14 | 🐛 0 | 🌐 JavaScript | 📅 2017-11-16 - Resolve when a stream ends. Optional buffering (be careful with this!)
* [promise-do-whilst](https://github.com/busterc/promise-do-whilst) ⭐ 3 | 🐛 1 | 🌐 JavaScript | 📅 2018-08-25 - Calls a function repeatedly while a condition returns true and then resolves the promise.
* [promise-method](https://github.com/wbinnssmith/promise-method) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2023-12-15 - Standalone `bluebird.method`. Turn a synchronously-returning method into a promise-returning one.
* [promise-nodeify](https://github.com/kevinoid/promise-nodeify) ⭐ 2 | 🐛 1 | 🌐 JavaScript | 📅 2026-08-10 - Standalone `nodeify` method which calls a Node-style callback on resolution or rejection.
* [promise-do-until](https://github.com/busterc/promise-do-until) ⭐ 1 | 🐛 1 | 🌐 JavaScript | 📅 2018-08-25 - Calls a function repeatedly until a condition returns true and then resolves the promise.
* [lie-fs](https://www.npmjs.com/package/lie-fs) - Promise wrappers for Node's FS API.

## License

Licensed under the [Creative Commons CC0 License](https://creativecommons.org/publicdomain/zero/1.0/).

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-02._
