
{
  "name": "json2json",
  "description": "A simple way to transform a JSON object to another JSON structure",
  "version": "0.2.8",
  "author": "Joel Van Horn <joel@joelvanhorn.com>",
  "repository": {
    "type": "git",
    "url": "git://github.com/joelvh/json2json.git"
  },
  "bugs": {
    "url": "https://github.com/joelvh/json2json/issues"
  },
  "os": [
    "linux",
    "darwin",
    "freebsd",
    "win32",
    "sunos"
  ],
  "directories": {
    "lib": "./lib/"
  },
  "main": "index.js",
  "scripts": {
    "test": "mocha --compilers coffee:coffee-script/register"
  },
  "dependencies": {
    "coffee-script": ">=1.7.0",
    "sysmo": ">=0.0.11"
  },
  "devDependencies": {
    "chai": ">=3.5.0",
    "mocha": "<4.0.0"
  },
  "engines": {
    "node": ">=0.1.97"
  },
  "licenses": []
}