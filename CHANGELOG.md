# master

# 1.2.3

* improve debug logging, less verbose by default, but more verbose with opt-in DEBUG_VERBOSE=true

# 1.2.2

* revert FSTreeDiff update

# 1.2.1

* upgrade FSTreeDiff

# 1.2.0

* [#50](https://github.com/stefanpenner/broccoli-persistent-filter/pull/50) Add ability to return an object (must be `JSON.stringify`able) from `processString`.
* [#50](https://github.com/stefanpenner/broccoli-persistent-filter/pull/50) Add `postProcess` hook that is called after `processString` (both when cached and not cached).

# 1.0.0

* Forked from broccoli-filter
