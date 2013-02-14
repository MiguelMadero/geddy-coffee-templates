geddy-coffee-templates
==========================

Contains coffee templates for geddy

__Disclaimer:__ This is __work in progress__ and __experimental__. The main purpose of this project at this stage is to test a new `template` switch in geddy's cli. The following is just the expected usage. 

__Disclaimer 2:__ Some template features might not be supported by geddy and there might be some missing files. 

## Trying Coffee Tempaltes

geddy-*-templates are only working in geddy's **[switchable-template-support branch](https://github.com/mde/geddy/tree/switachable-template-support)**. Get the code from there and simply replace `geddy` for `node /path/to/geddy/bin/cli.js` in all the commands or install from this branch by running `make && sudo make install`. Keep in mind this will replace your current geddy version. To uninstall it and go back to NPM's version run `sudo make uninstall && npm install geddy -g && npm update -g`. 

 Once you have geddy installed try any of the following options. 

At the moment only generating a base application is supported (`app` command). Scaffold, model, or other commands supported by the [cli](http://geddyjs.org/documentation#CLI) are still not supported by geddy-coffee-templates.

## Installing globally

npm install it globally

`$ npm install geddy-coffee-templates -g`

Now you can create a new app using the base scripts from this module

`$ geddy app myapp --templates coffee`

You can also use the -t shortcut instead of templates

`$ geddy app myapp -t coffee`

Geddy will take a short-name to form the full module name, so coffee, really means geddy-coffee-templates without all the typing.

Voila.

## Installing as a Local Module

npm install it in your geddy app

`$ npm install geddy-coffee-templates`

Scaffold your app using the new templates

`$ npm scaffold todo title:default status --templates coffee`

**Note:** the only command working now is app. 

Voila. v.s. Scaffold will use the files from this module instead of the default templates. 

## Cloning from GitHub

Clone this repo

`$ git clone https://github.com/MiguelMadero/geddy-coffee-templates.git`

Create a base app or scaffold using the --templates switch

`geddy app myapp --templates /path/to/the/cloned/repo`

Voila. Ditto