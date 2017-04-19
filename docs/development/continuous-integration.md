Currently, CI is only remotely tested on [Travis](https://travis-ci.org/futagoza/manfile), and done automatically on the latest commit to the [Manfile source repository](https://github.com/futagoza/manfile).

You can also perform a local CI check by simply running:

```shell
npm run ci
```

This run's a number of other NPM (and Node.js based) scripts that:

* install any missing NPM dependencies (production and development)
* remove any pre-generated module and command files
* remove any module based cache files used by script tasks or third party tools
* lint the current source code using [ESLint](http://eslint.org/), reporting errors only
* generate all module and command files for Manfile
* run the mocha based `**/*.test.js` files located in [Manfile's test directory](https://github.com/futagoza/manfile/tree/master/test)

The commands that are run (through NPM):

```shell
npm install
npm run clean:all
npm run lint -- --quiet
npm run build:all
npm test
```
