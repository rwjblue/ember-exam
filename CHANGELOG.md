v0.6.1 / 2017-03-25
===================

  * Ensure iterate exits with proper code
  * Add Ember Exam video link to Readme
  * Add note about using random with a seed
  * Fix seed logging message for random option

v0.6.0 / 2016-11-27
===================

  * Close code coverage gap
  * Update README to include Mocha info
  * Add framework-specific logic
  * Run both Mocha and QUnit tests in CI
  * Add tests for ember-cli-mocha
  * Remove moduleForAcceptance
  * Move QUnit-based tests to sub-directory
  * Remove reliance on QUnit for handling url params

v0.5.3 / 2016-11-19
===================

  * Fixed issue with using a single partition with a double digit

v0.5.2 / 2016-11-15
===================

  * Support specifying multiple partitions (#63)

v0.5.1 / 2016-11-14
===================

  * move rimraf to dependencies from devDependencies
  * Add note about test splitting balancing

v0.5.0 / 2016-08-14
===================

  * Document randomization-iterator
  * Add tests for randomization-iterator
  * Rename main acceptance test to be semantic
  * Introduce exam:iterate command
  * Tighten up npmignore
  * Clarify README typos
  * Increase mass threshold for code climate
  * Improve acceptance test coverage
  * Improve advanced configuration section of readme

v0.4.6 / 2016-08-07
===================

  * Don't run Travis on non-master branches
  * Read in testem config for constructing test page urls

v0.4.5 / 2016-08-03
===================

  * Fix node tests after core-object changes
  * Fix tests of ember-exam in 2.7
  * Upgrade all deps to align with Ember 2.7.0.
  * Temporarily undocument `--weighted`.
  * Setup and document ember-try integration

v0.4.4 / 2016-06-21
===================

  * Remove unused dependencies
  * Make codeclimate and eslint configs local
  * Make requires lazy where possible
  * Remove unused Array utilities
  * Add CodeClimate badges to README
  * Setup Istanbul code coverage for node code
  * Fix issues found via CodeClimate
  * Fix Travis badge to point to master
  * Add additional badges to README

v0.4.3 / 2016-06-05
===================

  * Add Acceptance test for Testem output
  * Add partition number to Testem output only when applicable
  * Handle _split and _partition params as strings
  * Fix typo, partition -> _partition

v0.4.2 / 2016-06-02
===================

  * Introduce tests for TestLoader
  * Add useful errors to TestLoader
  * Don't fail when lint tests are disabled

v0.4.1 / 2016-05-24
===================

  * Fix super callbacks context

v0.4.0 / 2016-05-24
===================

  * Remove AST manipulations and refine API
