# ampfire
A modified, CommonJS version of Firebase's [BackboneFire](https://github.com/firebase/backbonefire) Library that replaces Backbone with [AmpersandJS](http://ampersandjs.com/) Collections and Models

It's broken into two modules, [ampfire-model](#ampfire-model) and ampfire-collection. Since one of the great things about AmpersandJS is it's modularity, I fealt this library should be modular as well.

## ampfire-model
Support for the [ampersand-model](https://github.com/AmpersandJS/ampersand-model) module.

#### Dependencies
This is dependent on the [ampersand-model](https://github.com/AmpersandJS/ampersand-model) module

## ampfire-collection
Support for the [ampersand-rest-collection](https://github.com/ampersandjs/ampersand-rest-collection) module.
- The [ampersand-collection](https://github.com/ampersandjs/ampersand-collection) with the [ampersand-collection-rest-mixin](https://github.com/ampersandjs/ampersand-collection-rest-mixin) if the lodash functions aren't needed.

#### Dependencies
This is dependent on the [ampersand-rest-collection](https://github.com/AmpersandJS/ampersand-rest-collection) module

## Tests
I want to write tests for the modules and plan on doing that soon.
