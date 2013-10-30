# API PEGjs tests

A collection of language-agnostic tests in JSON format for parsing into and generating from [api-pegjs](https://github.com/for-GET/api-pegjs)' AST.

**This is part of a bigger effort: [for-GET HTTP](https://github.com/for-GET/README).**


## Structure

Each specification has its own folder with test suites.

Each ABNF rule in the specification has its own test suite as a JSON file.

Each JSON file is an array of test cases.

Each test case is structured as `[description, input, result]` for positive tests, and just `[description, input]` for negative tests.

`input` can be a string or a JSON reference pointing to a local file.

`result` is an AST.


## License

[Apache 2.0](LICENSE)
