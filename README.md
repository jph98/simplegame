Simple NodeJS Game taken from:

http://learnjs.io/blog/2013/11/16/simple-2d-game/

Install Node, NPM and modules
-----------------------------

  http://nodejs.org/download/

    curl -s https://npmjs.org/install.sh > npm-install-$$.sh
    sh npm-install-*.sh
  
    npm init
    npm install gameloop crtrdg-keyboard
    npm install -g beefy browserify
  
package.json contains:

    {
      "name": "simplegame",
      "version": "0.0.0",
      "description": "Simple Game",
      "main": "index.js",
      "scripts": {
        "start": "beefy game.js:bundle.js --live"
      },
      "author": "Jon",
      "license": "BSD-2-Clause"
    }
