# Eventsource

Eventsource implements a [Go](http://golang.org/) implementation of client and server to allow streaming data one-way over a HTTP connection using the Server-Sent Events API http://dev.w3.org/html5/eventsource/

This is a fork of: https://github.com/donovanhide/eventsource

This version of the library supports Go 1.8 and higher. However, its unit tests can only be run in Go 1.13 or higher.

The package is a Go module, but can still be imported by projects that do not use modules.

## Installation

    go get github.com/laynefyc/eventsource

## Documentation

* [Reference](http://godoc.org/github.com/laynefyc/eventsource)

## License

Eventsource is available under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.html).
