# CapstoneMain
Kafka using Spring Boot Project

## Development server

Run `tomcat serve` for a dev server. Navigate to `(http://localhost:8080/v1/libraryevent)`. The application will automatically reload if you change any of the source files.
body of json file ex-
{
"libraryEventId":10,
"book":
{
"bookId":457,
"bookName":"Kafka Using Spring Boot",
"bookAuthor":"Malatesh"
}
}

## Build

Run and build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests and integration tests

Run `juint test` to execute the unit tests.

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

