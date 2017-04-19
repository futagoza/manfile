To install and use the latest copy of Manfile in a production environment, using Git _AND NPM_, run the following commands:

```shell
git clone https://github.com/futagoza/manfile.git node_modules/manfile
cd node_modules/manfile && npm install --only=production
```

_**NOTE:**_ This _ONLY_ allows you to use Manfile as a Node.js module, _NOT_ a local (or globally) based cli tool.

If you want to contribute (fix a bug, add a feature, etc) towards the development of Manfile, checkout [development documents](../development/README.md).
