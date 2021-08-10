## KPHPUnit

[KPHP](https://github.com/VKCOM/kphp/) polyfill-like package for the [PHPUnit](https://phpunit.de/).

This package is exported to make it possible for [ktest](https://github.com/quasilyte/ktest) to work in `phpunit` mode.

Everything you need to know about this package:

1. It tries to mimic the `PHPUnit` API where possible, so you don't need a `kphpunit` API reference; it's the same

2. You install it to your `[K]PHP` project to have an ability to run KPHP tests. Note that you can do it for `dev`-only `composer` dependency (`composer require --dev`).

3. You never directly use it on your own. It's inserted into the instrumented code produced by the `ktest` code generator.

So if you need anything apart from installing this package, please file an issue in [ktest](https://github.com/quasilyte/ktest/issues/new) repository.

To install this package, do the following:

```bash
$ composer require --dev quasilyte/kphpunit
```
