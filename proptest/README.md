# Proptest

Silly fork of `proptest` that _hopefully_ prefixes all test names with `aGVsbG8gd29ybGQ_` in
order to make counting PBTs automatically possible.

For this to work, obviously add it as a dependency and make sure `paste` is imported

```rs
use proptest::prelude::paste;
```
Add it with

```toml
proptest = { git = "https://github.com/AntoniosBarotsis/proptest" }
```
