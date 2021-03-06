# 0.2.1

* Fixed support for Ember 2.11+ which is freezing `attributeBindings` now (#59)

# 0.2.0

* Added support for `data-test-*` attributes without values on components (#55)

# 0.1.1

* Replaced initializer with IIFE in the vendor tree which fixes
  usage in integration tests (#52)
* Added warning when tagName is empty and data-test-* attributes are used (#53)

# 0.1.0

* Removed unnecessary `lodash` dependency (#37)
* Added `data-test-*` attribute stripping to component and helper
  invocations in Handlebars files (#40)
* Added `strip` and deprecated `environments` options (#42)
* Added automatic binding for `data-test-*` properties in components (#27)
* Simplified `testSelector()` import to `ember-test-helpers` (#43)
* Added Babel plugin that automatically removed `data-test-*` keys from
  all objects including components and controllers (#45) 

# 0.0.5

* the `testSelector` helper now treats empty but non-none values (like `0`)
  correctly, see #24.

# 0.0.4 

* Fixed a caching warning, see #22.
* Fixed and improved tests, see #22.

# 0.0.3

* The environments that ember-test-selectors strips `data-test-*` attributes
  for can now be configured, see #14.
* Fix the `package.json` to include the correct repository URL, see #16.

# 0.0.2

* Add the `testSelector` test helper that makes generating `data` attribute
  based selectors easier, see #12.

# 0.0.1

initial release
