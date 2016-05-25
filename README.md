# Primer CSS States

[![NPM version](http://img.shields.io/npm/v/primer-states.svg)](https://www.npmjs.org/package/primer-states)
[![Build Status](https://travis-ci.org/primer/states.svg?branch=master)](https://travis-ci.org/primer/states)

> States, or state indicators, inform users of the current status of a particular item. Included common states are Open, Closed, or Merged, each requiring it’s own modifier class.

This repository is a module of the full [primer-css][primer] repository.

## Documentation

You can read more about states in the [docs][docs].

## Install

This repository is distributed with [npm][npm]. After [installing npm][install-npm], you can install `primer-states` with this command.

```
$ npm install --save primer-states
```

## Usage

The source files included are written in [Sass][sass] (`scss`) You can simply point your sass `include-path` at your `node_modules` directory and import it like this.

```scss
@import "primer-states/index.scss";
```

You can also import specific portions of the module by importing those partials from the `/lib/` folder. _Make sure you import any requirements along with the modules._

## Build

For a compiled **css** version of this module, a npm script is included that will output a css version to `build/build.css`

```
$ npm run build
```

## Related

* [Primer Documentation][docs]
* [primer-css][primer]
* [primer-support][primer-support]

## License

MIT &copy; [GitHub](https://github.com/)

[primer]: https://github.com/primer/primer
[primer-support]: https://github.com/primer/primer-support
[docs]: http://primercss.io/
[npm]: https://www.npmjs.com/
[install-npm]: https://docs.npmjs.com/getting-started/installing-node
[sass]: http://sass-lang.com/
