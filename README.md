# goog-integer

A (temporary?) fork of the `goog.math.Integer` class in the
google-closure JavaScript library that includes bugfixes. Packaged as
a jar for ClojureScript.

## Obtention

Via Leiningen:

``` clojure
[com.gfredericks/goog-integer "1.0.1"]
```

## Usage

Simply replace references to `goog.math.Integer` with
`com.gfredericks.goog.math.Integer`.

## Development

The bugs fixed in this fork were discovered and the fixes tested using
the test suite in
[this library](https://github.com/gfredericks/exact).

## License

Copyright © 2015 Gary Fredericks

Distributed under the Eclipse Public License either version 1.0 or (at
your option) any later version.
