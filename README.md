## DRAFT CoverageJSON 1.0 Executable Test Suite

### Scope

This Executable Test Suite is still in development.

The test suite checks whether implementations comply with the CoverageJSON 1.0 Community Standard.

### How to run the test suite using Docker

Run the following maven command from the root folder of the repository:

`mvn clean install -Dsource=8  docker:run -Pdocker`

From here, you can now access http://localhost:8081/teamengine to access the Executable Test Suite.

You can log in as `ogctest`, with a password of ogctest.

### How to build the test suite

The test suite is built using https://maven.apache.org/[Apache Maven v3].

### How to run the test suite
The options for running the suite are summarized in

include::src/site/asciidoc/how-to-run-the-tests.adoc[]

### How to contribute

If you would like to get involved, you can:

* [Report an issue](https://github.com/opengeospatial/ets-coveragejson10/issues) such as a defect or
an enhancement request
* Help to resolve an [open issue](https://github.com/opengeospatial/ets-coveragejson10/issues?q=is%3Aopen)
* Fix a bug: Fork the repository, apply the fix, and create a pull request
* Add new tests: Fork the repository, implement (and verify) the tests on a new topic branch,
and create a pull request
