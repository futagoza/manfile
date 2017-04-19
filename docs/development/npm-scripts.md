NPM allows us to define a number of tasks ([called NPM scripts](https://docs.npmjs.com/cli/run-script)) that, when used with Node.js based JavaScript files (and/or third party NPM modules), allow us to create cross platform Makefile-like tasks.

All tasks must be defined in the `scripts` field located in [package.json](../../package.json), a meta/configuration file for NPM.

While reading through the documents (or the source code), if you come across a `npm run ...` command, and wish to know what it does, refer to the task defined in [package.json](../../package.json).
