Although Node.js v4 can execute JavaScript, the ECMAScript 2015 compliance is at [54%](http://node.green/#ES2015), meaning JavaScript based on [ES2017+](http://node.green/#ES2017) must be transpiled. This is achieved using a transpiler (source to source compiler) to generate ES2015 JavaScript that works on Node.js v4

## ECMAScript Compliance

This data was gathered from [http://node.green/](http://node.green/), who used data from the [source repository](https://github.com/kangax/compat-table) for [kangax's compat-table](https://kangax.github.io/compat-table/), and applied it to different Node.js versions.

* Node.js v4 supports:
    * [54%](http://node.green/#ES2015) of ECMAScript 2015
    * [7%](http://node.green/#ES2016) of ECMAScript 2016
    * [17%](http://node.green/#ES2017) of ECMAScript 2017
    * [5%](http://node.green/#ESNEXT) of ECMAScript Next

* Node.js v5 slightly increased support to:
    * [58%](http://node.green/#ES2015) of ECMAScript 2015

* Node.js v6 bumped up support to:
    * [91%](http://node.green/#ES2015) of ECMAScript 2015
    * [76%](http://node.green/#ES2016) of ECMAScript 2016
    * [18%](http://node.green/#ES2017) of ECMAScript 2017

* Node.js v6 LTS, since Node.js v6.5, has support for:
    * [99%](http://node.green/#ES2015) of ECMAScript 2015

* Node.js v7 supports:
    * [100%](http://node.green/#ES2016) of ECMAScript 2016
    * [28%](http://node.green/#ES2017) of ECMAScript 2017

* Node.js v7.6 slightly increased support to:
    * [51%](http://node.green/#ES2017) of ECMAScript 2017

* This leaves the current Node.js ECMAScript compliance at:
    * [99%](http://node.green/#ES2015) of ECMAScript 2015
    * [100%](http://node.green/#ES2016) of ECMAScript 2016
    * [51%](http://node.green/#ES2017) of ECMAScript 2017
    * [5%](http://node.green/#ESNEXT) of ECMAScript Next

## Development

To develope my projects (including Manfile) in ECMAScript 2017+, I use the following:

* [http://node.green/](http://node.green/) to confirm what can be used
* [Babel](https://babeljs.io/) to transpile JavaScript based on ESMAScript 2017+
* Use plugins and presets ([Official](https://babeljs.io/docs/plugins/) or [third party](https://www.npmjs.com/browse/keyword/babel-plugin)) to increase and extend features for JavaScript
* [rollup.js](https://rollupjs.org/) to generate the module and command files

## More Information

This above data was last updated on the 19th of April, 2017.

For more information about ECMAScript, check out the [Wikipedia article](https://en.wikipedia.org/wiki/ECMAScript).

To check out the latest ECMAScript compliance, go to [http://node.green/](http://node.green/) for Node.js and [kangax's compat-table](https://kangax.github.io/compat-table/) for the rest (including Babel).
