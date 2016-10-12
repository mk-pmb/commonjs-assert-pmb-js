
<!--#echo json="package.json" key="name" underline="=" -->
commonjs-assert-pmb
===================
<!--/#echo -->

<!--#echo json="package.json" key="description" -->
Aims to provide the orthodox assert module experience as described in the
CommonJS Unit Testing 1.0 spec.
<!--/#echo -->


Do you really want this?
------------------------

Please make sure you know about the spec bugs, including, but in no way
limited to, those from [the tests](test/all.js).

If you don't care about orthodoxy, please try the module
[`reasonable-assert-pmb`][re-assert] instead.



Usage
-----

Since the module name `assert` is taken on NPM, some customization is
required to comply with rule #1.

### Module alias method

  1. Tell your module loader that by `assert`, you mean this module.
     (How? Below.)
  2. Use as per the spec: http://wiki.commonjs.org/wiki/Unit_Testing/1.0


### Alternate require method

  1. `require = require('commonjs-assert-pmb/require`)(require);`
  2. Use as per the spec: http://wiki.commonjs.org/wiki/Unit_Testing/1.0


### Module alias method (cont.)

How to tell your module loader?

  * :TODO:



<!--#toc stop="scan" -->


License
-------
<!--#echo json="package.json" key=".license" -->
ISC
<!--/#echo -->




  [re-assert]: https://github.com/mk-pmb/reasonable-assert-pmb-js/
