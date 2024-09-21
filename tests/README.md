## `/tests` Directory

This folder contains test files for the Go project. Unit tests, integration tests, and any other test-related files should be placed here.

### Purpose

The `/tests` directory is meant to store the test files that verify the functionality and correctness of the codebase. Go test files are typically named with the `_test.go` suffix and are used to ensure that the application logic works as expected.

### How to Run Tests

To run all the tests in the project, including those in the `/tests` folder, use the following command:

```bash
go test ./...
## `/tests` Directory

This folder contains test files for the Go project. Unit tests, in## `/tests` Directory

This folder contains test files for the Go project. Unit tests, integration tests, and any other test-related files should be placed here.


### Writing Tests

## Test File Naming Conventions
Test files should have the _test.go suffix.
Example: mytestfile_test.go.
Test Function Naming Conventions
Test functions must start with Test followed by the function or behavior being tested.
Each test function should take a single parameter of type *testing.T.

### Purpose

The `/tests` directory is meant to store the test files that verify the functionality and correctness of the codebase. Go test files are typically named with the `_test.go` suffix and are used to ensure that the application logic works as expected.

### How to Run Tests

To run all the tests in the project, including those in the `/tests` folder, use the following command:

```bash
go test ./...

