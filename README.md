## jQuery Package

The jQuery package provides the popular jQuery library.


### Install

Add `modules` to your dependencies section in `kanso.json`.

```javascript
...
  "dependencies": {
    "jquery": null,
    ...
  }
```

Run `kanso install` to fetch the package.


### Usage

```javascript
(function($) {
  // use $ like a boss
})(require('jquery/core'));
```
