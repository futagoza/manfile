To have everything setup for you to dive into your task simply run the following:

```shell
npm run setup
```

This run's a number of other NPM (and Node.js based) scripts that:

* install any missing NPM packages (production and development)
* remove any pre-generated module and command files
* generate all module and command files for Manfile

The commands that are run (through NPM):

```shell
npm install
npm run rebuild
```

The `rebuild` task runs:

```shell
npm run clean:manfile
npm run build:all
```
