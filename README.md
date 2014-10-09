     ____    __       _____  ____
    /\  _`\ /\ \     /\___ \/\  _`\
    \ \ \L\_\ \ \    \/__/\ \ \,\L\_\
     \ \  _\L\ \ \  __  _\ \ \/_\__ \
      \ \ \L\ \ \ \L\ \/\ \_\ \/\ \L\ \
       \ \____/\ \____/\ \____/\ `\____\
        \/___/  \/___/  \/___/  \/_____/

[ELJS][0] is an expression language dedicated to JavaScript.

[![Build Status](https://travis-ci.org/neocotic/ELJS.svg?branch=develop)][1]
[![Dependency Status](https://gemnasium.com/neocotic/ELJS.svg)][3]
[![Built with Grunt](https://cdn.gruntjs.com/builtwith.png)][4]

## Install

Install using the package manager for your desired environment(s):

``` bash
# for node.js:
$ npm install eljs
# OR; for the browser:
$ bower install eljs
```

This library has no dependencies on any other library.

## Usage

TODO

### Miscellaneous

#### `noConflict()`
Returns `el` in a no-conflict state, reallocating the `el` global variable name to its previous owner, where possible.

This is really just intended for use within a browser.

``` html
<script src="/path/to/conflict-lib.js"></script>
<script src="/path/to/el.min.js"></script>
<script>
  var elNC = el.noConflict();
  // Conflicting lib works again and use elNC for this library onwards...
</script>
```

#### `VERSION`
The current version of `el`.

``` javascript
console.log(el.VERSION); // "0.1.0"
```

## Bugs

If you have any problems with this library or would like to see changes currently in development you can do so
[here][5].

## Contributors

If you want to contribute, you're a legend! Information on how you can do so can be found in [CONTRIBUTING.md][7]. We
want your suggestions and pull requests!

A list of [ELJS][0] contributors can be found in [AUTHORS.md][6].

## License

Copyright (c) 2014 Alasdair Mercer

See [LICENSE.md][8] for more information on our MIT license.

[0]: http://neocotic.com/ELJS
[1]: https://travis-ci.org/neocotic/ELJS
[2]: https://twitter.com/neocotic
[3]: https://gemnasium.com/neocotic/ELJS
[4]: http://gruntjs.com
[5]: https://github.com/neocotic/ELJS/issues
[6]: https://github.com/neocotic/ELJS/blob/master/AUTHORS.md
[7]: https://github.com/neocotic/ELJS/blob/master/CONTRIBUTING.md
[8]: https://github.com/neocotic/ELJS/blob/master/LICENSE.md