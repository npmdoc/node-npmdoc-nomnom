# api documentation for  [nomnom (v1.8.1)](https://github.com/harthur/nomnom)  [![npm package](https://img.shields.io/npm/v/npmdoc-nomnom.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-nomnom) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-nomnom.svg)](https://travis-ci.org/npmdoc/node-npmdoc-nomnom)
#### Option parser with generated usage and commands

[![NPM](https://nodei.co/npm/nomnom.png?downloads=true)](https://www.npmjs.com/package/nomnom)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nomnom/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-nomnom_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nomnom/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-nomnom/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-nomnom/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Heather Arthur",
        "email": "fayearthur@gmail.com"
    },
    "bugs": {
        "url": "https://github.com/harthur/nomnom/issues"
    },
    "dependencies": {
        "chalk": "~0.4.0",
        "underscore": "~1.6.0"
    },
    "description": "Option parser with generated usage and commands",
    "devDependencies": {
        "nodeunit": "~0.7.4"
    },
    "directories": {},
    "dist": {
        "shasum": "2151f722472ba79e50a76fc125bb8c8f2e4dc2a7",
        "tarball": "https://registry.npmjs.org/nomnom/-/nomnom-1.8.1.tgz"
    },
    "homepage": "https://github.com/harthur/nomnom",
    "keywords": [
        "arguments",
        "option parser",
        "command line",
        "options",
        "parser"
    ],
    "main": "./nomnom",
    "maintainers": [
        {
            "name": "harth",
            "email": "fayearthur@gmail.com"
        }
    ],
    "name": "nomnom",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/harthur/nomnom.git"
    },
    "scripts": {
        "test": "nodeunit test/*.js"
    },
    "version": "1.8.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module nomnom](#apidoc.module.nomnom)
1.  [function <span class="apidocSignatureSpan">nomnom.</span>colors ()](#apidoc.element.nomnom.colors)
1.  [function <span class="apidocSignatureSpan">nomnom.</span>command ()](#apidoc.element.nomnom.command)
1.  [function <span class="apidocSignatureSpan">nomnom.</span>getUsage ()](#apidoc.element.nomnom.getUsage)
1.  [function <span class="apidocSignatureSpan">nomnom.</span>globalOpts ()](#apidoc.element.nomnom.globalOpts)
1.  [function <span class="apidocSignatureSpan">nomnom.</span>help ()](#apidoc.element.nomnom.help)
1.  [function <span class="apidocSignatureSpan">nomnom.</span>nocolors ()](#apidoc.element.nomnom.nocolors)
1.  [function <span class="apidocSignatureSpan">nomnom.</span>nocommand ()](#apidoc.element.nomnom.nocommand)
1.  [function <span class="apidocSignatureSpan">nomnom.</span>nom ()](#apidoc.element.nomnom.nom)
1.  [function <span class="apidocSignatureSpan">nomnom.</span>opt ()](#apidoc.element.nomnom.opt)
1.  [function <span class="apidocSignatureSpan">nomnom.</span>option ()](#apidoc.element.nomnom.option)
1.  [function <span class="apidocSignatureSpan">nomnom.</span>options ()](#apidoc.element.nomnom.options)
1.  [function <span class="apidocSignatureSpan">nomnom.</span>opts ()](#apidoc.element.nomnom.opts)
1.  [function <span class="apidocSignatureSpan">nomnom.</span>parse ()](#apidoc.element.nomnom.parse)
1.  [function <span class="apidocSignatureSpan">nomnom.</span>parseArgs ()](#apidoc.element.nomnom.parseArgs)
1.  [function <span class="apidocSignatureSpan">nomnom.</span>printer ()](#apidoc.element.nomnom.printer)
1.  [function <span class="apidocSignatureSpan">nomnom.</span>script ()](#apidoc.element.nomnom.script)
1.  [function <span class="apidocSignatureSpan">nomnom.</span>scriptName ()](#apidoc.element.nomnom.scriptName)
1.  [function <span class="apidocSignatureSpan">nomnom.</span>setOption ()](#apidoc.element.nomnom.setOption)
1.  [function <span class="apidocSignatureSpan">nomnom.</span>usage ()](#apidoc.element.nomnom.usage)



# <a name="apidoc.module.nomnom"></a>[module nomnom](#apidoc.module.nomnom)

#### <a name="apidoc.element.nomnom.colors"></a>[function <span class="apidocSignatureSpan">nomnom.</span>colors ()](#apidoc.element.nomnom.colors)
- description and source-code
```javascript
colors = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nomnom.command"></a>[function <span class="apidocSignatureSpan">nomnom.</span>command ()](#apidoc.element.nomnom.command)
- description and source-code
```javascript
command = function () { [native code] }
```
- example usage
```shell
...

# Commands
Nomnom supports command-based interfaces (e.g. with git: 'git add -p' and 'git rebase -i' where 'add' and 'rebase' are the commands
):

'''javascript
var parser = require("nomnom");

parser.command('browser')
.callback(function(opts) {
   runBrowser(opts.url);
})
.help("run browser tests");

parser.command('sanity')
.option('outfile', {
...
```

#### <a name="apidoc.element.nomnom.getUsage"></a>[function <span class="apidocSignatureSpan">nomnom.</span>getUsage ()](#apidoc.element.nomnom.getUsage)
- description and source-code
```javascript
getUsage = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nomnom.globalOpts"></a>[function <span class="apidocSignatureSpan">nomnom.</span>globalOpts ()](#apidoc.element.nomnom.globalOpts)
- description and source-code
```javascript
globalOpts = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nomnom.help"></a>[function <span class="apidocSignatureSpan">nomnom.</span>help ()](#apidoc.element.nomnom.help)
- description and source-code
```javascript
help = function () { [native code] }
```
- example usage
```shell
...
'''javascript
var parser = require("nomnom");

parser.command('browser')
.callback(function(opts) {
   runBrowser(opts.url);
})
.help("run browser tests");

parser.command('sanity')
.option('outfile', {
   abbr: 'o',
   help: "file to write results to"
})
.option('config', {
...
```

#### <a name="apidoc.element.nomnom.nocolors"></a>[function <span class="apidocSignatureSpan">nomnom.</span>nocolors ()](#apidoc.element.nomnom.nocolors)
- description and source-code
```javascript
nocolors = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nomnom.nocommand"></a>[function <span class="apidocSignatureSpan">nomnom.</span>nocommand ()](#apidoc.element.nomnom.nocommand)
- description and source-code
```javascript
nocommand = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nomnom.nom"></a>[function <span class="apidocSignatureSpan">nomnom.</span>nom ()](#apidoc.element.nomnom.nom)
- description and source-code
```javascript
nom = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nomnom.opt"></a>[function <span class="apidocSignatureSpan">nomnom.</span>opt ()](#apidoc.element.nomnom.opt)
- description and source-code
```javascript
opt = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nomnom.option"></a>[function <span class="apidocSignatureSpan">nomnom.</span>option ()](#apidoc.element.nomnom.option)
- description and source-code
```javascript
option = function () { [native code] }
```
- example usage
```shell
...


# nomnom
nomnom is an option parser for node. It noms your args and gives them back to you in a hash.

'''javascript
var opts = require("nomnom")
.option('debug', {
   abbr: 'd',
   flag: true,
   help: 'Print debugging info'
})
.option('config', {
   abbr: 'c',
   default: 'config.json',
...
```

#### <a name="apidoc.element.nomnom.options"></a>[function <span class="apidocSignatureSpan">nomnom.</span>options ()](#apidoc.element.nomnom.options)
- description and source-code
```javascript
options = function () { [native code] }
```
- example usage
```shell
...

# Usage
Nomnom prints out a usage message if '--help' or '-h' is an argument. Usage for these options in 'test.js':

'''javascript
var opts = require("nomnom")
.script("runtests")
.options({
   path: {
      position: 0,
      help: "Test file to run",
      list: true
   },
   config: {
      abbr: 'c',
...
```

#### <a name="apidoc.element.nomnom.opts"></a>[function <span class="apidocSignatureSpan">nomnom.</span>opts ()](#apidoc.element.nomnom.opts)
- description and source-code
```javascript
opts = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nomnom.parse"></a>[function <span class="apidocSignatureSpan">nomnom.</span>parse ()](#apidoc.element.nomnom.parse)
- description and source-code
```javascript
parse = function () { [native code] }
```
- example usage
```shell
...
   .option('version', {
      flag: true,
      help: 'print version and exit',
      callback: function() {
         return "version 1.2.4";
      }
   })
   .parse();

if (opts.debug)
   // do stuff
'''

You don't have to specify anything if you don't want to:
...
```

#### <a name="apidoc.element.nomnom.parseArgs"></a>[function <span class="apidocSignatureSpan">nomnom.</span>parseArgs ()](#apidoc.element.nomnom.parseArgs)
- description and source-code
```javascript
parseArgs = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nomnom.printer"></a>[function <span class="apidocSignatureSpan">nomnom.</span>printer ()](#apidoc.element.nomnom.printer)
- description and source-code
```javascript
printer = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nomnom.script"></a>[function <span class="apidocSignatureSpan">nomnom.</span>script ()](#apidoc.element.nomnom.script)
- description and source-code
```javascript
script = function () { [native code] }
```
- example usage
```shell
...
Each command generates its own usage message when '-h' or '--help' is specified with the command.

# Usage
Nomnom prints out a usage message if '--help' or '-h' is an argument. Usage for these options in 'test.js':

'''javascript
var opts = require("nomnom")
.script("runtests")
.options({
   path: {
      position: 0,
      help: "Test file to run",
      list: true
   },
   config: {
...
```

#### <a name="apidoc.element.nomnom.scriptName"></a>[function <span class="apidocSignatureSpan">nomnom.</span>scriptName ()](#apidoc.element.nomnom.scriptName)
- description and source-code
```javascript
scriptName = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nomnom.setOption"></a>[function <span class="apidocSignatureSpan">nomnom.</span>setOption ()](#apidoc.element.nomnom.setOption)
- description and source-code
```javascript
setOption = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nomnom.usage"></a>[function <span class="apidocSignatureSpan">nomnom.</span>usage ()](#apidoc.element.nomnom.usage)
- description and source-code
```javascript
usage = function () { [native code] }
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
