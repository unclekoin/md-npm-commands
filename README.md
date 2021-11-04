# NPM

```bash
NPM

$ npm install 
$ npm i 
$ npm i lodash
$ npm i lodash@4.17.4
$ npm i git://github.com/lodash/lodash#es

# keys:
# --global (-g) - install package globally
# --save-dev (-D) - adds package and save into dev dependencies 
# --no-save - prevents saving package in dependencies

$ npm uninstall (remove, rm, r, un, unlink)
$ npm rm lodash

# keys:
# --global (-g) - uninstall package globally
# --save-dev (-D) - package will be removed from dev dependencies 
# --no-save - package will not be removed from package.json

$ npm update (up, upgrade)
$ npm up lodash

# keys:
# --global (-g) - uninstall package globally

$ npm ls (list, la, ll)
$ npm ls lodash

# keys:
# --global (-g) - shows globally installed packages
# --depth [0] - depth of dependencies tree
# --json - output in json format

$ npm docs (home)
$ npm docs lodash

$ npm publish <your-super-package>
$ npm unpublish <your-super-package>

$ npm run-script <your-script-alias-from-package.json>

$ npm start
$ npm stop
$ npm test
$ npm restart

