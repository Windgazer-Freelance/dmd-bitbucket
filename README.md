[![view on npm](http://img.shields.io/npm/v/dmd-plugin-example.svg)](https://www.npmjs.org/package/dmd-plugin-example)
[![npm module downloads per month](http://img.shields.io/npm/dm/dmd-plugin-example.svg)](https://www.npmjs.org/package/dmd-plugin-example)
[![Dependency Status](https://david-dm.org/jsdoc2md/dmd-plugin-example.svg)](https://david-dm.org/jsdoc2md/dmd-plugin-example)

# dmd-bitbucket
You might have noticed the default jsdoc2md output looks shit on Bitbucket. Hence this plugin.. 


## Install and use
In the project requiring this plug-in, install it as a devDependency: 
```
$ npm install dmd-plugin-example --save-dev
```

Then pass the plug-in name to `jsdoc2md` or `dmd` when generating your docs:
```
$ jsdoc2md --plugin dmd-plugin-example lib/*.js 
```
