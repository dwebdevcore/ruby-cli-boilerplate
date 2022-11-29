# ruby-cli-boilerplate

This repository contains a boilerplate Ruby CLI class that can be used to
implement a basic zero-dependency CLI for other Ruby libraries.

## Features

* Zero-dependencies, making it ideal for adding a CLI to small libraries.
* Correctly handles `Ctrl^C` and broken pipe exceptions.
* Catches any other exceptions and prints a bug report.
* Defines the CLI as a class, making it easy to test.
* Comes with boilerplate RSpec tests.
