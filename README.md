geddy-coffee-templates
==========================

Contains coffee templates for geddy

__Disclaimer:__ This is __work in progress__ and __experimental__. The main purpose of this project at this stage is to test a new `template` switch in geddy's cli. The following is just the expected usage. geddy-*-templates aren't working in geddy, available on NPM, might not even contain real templates and coffee or other template features might not be supported by geddy.


## Using from NPM

npm install it in your geddy app

`$ npm install geddy-coffee-templates`

Scaffold your app using the new templates

`$ npm scaffold todo title:default status --templates coffee`

Voila. Scaffold will use the files from this module instead of the default templates. 

## Installing globally

npm install it globally

`$ npm install geddy-coffee-templates -g`

Now you can create a new app using the base scripts on this module

`$ geddy app myapp --templates coffee`

Voila. v.s.

## Cloning from GitHub

Clone this repo

`$ git clone https://github.com/MiguelMadero/geddy-coffee-templates.git`

Create a base app or scaffold using the --templates switch

`geddy app myapp --templates /path/to/the/cloned/repo`

Voila. Ditto