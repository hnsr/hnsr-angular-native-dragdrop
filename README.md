# hnsr-angular-native-dragdrop
Thin wrapper around angular-native-dragdrop so that it can be used with npm+browserify.

## Usage 

Using it is as simple as installing it with npm and `requiring()` it from your code:

```bash
$ npm install --save hnsr-angular-native-dragdrop
```

Then from your code:

```javascript
  var angular = require('angular');
  angular.module('myApp', [  require('hnsr-angular-native-dragdrop') ]);
```

Browserify will then include angular-native-dragdrop in its bundle output. See http://blog.npmjs.org/post/114584444410/using-angulars-new-improved-browserify-support on how (and why) this works.

## Docs

For documentation on using angular-native-dragdrop itself, see https://github.com/angular-dragdrop/angular-dragdrop
