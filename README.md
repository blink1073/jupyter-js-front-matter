steal-front-matter
==================

[![Build Status](https://travis-ci.org/blink1073/steal-front-matter.svg)](https://travis-ci.org/blink1073/steal-front-matter?branch=master)
[![Coverage Status](https://coveralls.io/repos/blink1073/steal-front-matter/badge.svg?branch=master&service=github)](https://coveralls.io/github/blink1073/steal-front-matter?branch=master)

Front matter for a Jupyter steal-based application.

[API Docs](http://blink1073.github.io/steal-front-matter/api/)


Package Install
---------------

**Prerequisites**
- [node](http://nodejs.org/)

```bash
npm install --save steal-front-matter
```


Source Build
------------

**Prerequisites**
- [git](http://git-scm.com/)
- [node](http://nodejs.org/)

```bash
git clone https://github.com/blink1073/steal-front-matter.git
cd steal-front-matter
npm install
```

**Rebuild**
```bash
npm run clean
npm run build
```


Run Tests
---------

Follow the source build instructions first.

```bash
# run tests in Firefox
npm test

# run tests in Chrome
npm run test:chrome

# run tests in IE
npm run test:ie
```


Build Docs
----------

Follow the source build instructions first.

```bash
npm run docs
```

Navigate to `docs/index.html`.


Build Example
-------------

Follow the source build instructions first.

```bash
npm run build:example
```

Navigate to `example/index.html`.


Supported Runtimes
------------------

The runtime versions which are currently *known to work* are listed below.
Earlier versions may also work, but come with no guarantees.

- IE 11+
- Firefox 32+
- Chrome 38+


Usage Examples
--------------

**Note:** This module is fully compatible with Node/Babel/ES6/ES5. Simply
omit the type declarations when using a language other than TypeScript.
