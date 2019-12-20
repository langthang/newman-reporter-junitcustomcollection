# newman-reporter-junitcustomcollection
JUnit reporter for [Newman](https://github.com/postmanlabs/newman) that provides the information about the collection run in JUnit format.
This needs to be used in [conjunction with Newman](https://github.com/postmanlabs/newman#external-reporters) so that it can recognize JUnit reporting options.

> Different from [newman-reporter-junit](https://github.com/postmanlabs/newman/blob/develop/lib/reporters/junit/index.js) is using executions to have different test suites name than the one from collection.