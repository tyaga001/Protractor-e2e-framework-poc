Initial Framework setup- Protractor
===================================

A sample POC which contains all the necessary setup for the protractor E2E testing using grunt.

here we are trying to do every steps in grunt only.


Installation
do the following commands after downloading the repo

```bash
// open a cmd first window & hit the belwo two commands.
$ npm install
$ npm install -g grunt-cli

Now open a new cmd window & update & start webdriver-manger update/start 

use the below commnads in the current dir-
// this will update the webdriver manager
node ./node_modules/protractor/bin/webdriver-manager update

// now start the selenium server with below command

node ./node_modules/protractor/bin/webdriver-manager start

//go back to the first cmd window & just hit the belwo command it will open the new chrome window & do rest of the magic.

$ grunt

```
