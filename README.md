# Immutable JSON

[![CircleCI](https://circleci.com/gh/mfelsche/pony-immutable-json.svg?style=svg)](https://circleci.com/gh/mfelsche/pony-immutable-json)

Just like the [Ponylang stdlib JSON package](https://stdlib.ponylang.io/json--index), just with everything immutable.

That means most of all `JsonArray` and `JsonObject` have a `val` capability now instead of `ref`. It was horrible to parse and serialize JSON if you have `val` data or you only see it as `box`.

## Installation

* Install [corral](https://github.com/ponylang/corral)
* `corral add github.com/mfelsche/pony-immutable-json.git --version master`
* `corral fetch` to fetch your dependencies
* `use "immutable-json"` to include this package
* `corral run -- ponyc` to compile your application
