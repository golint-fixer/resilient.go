# resilient.go [![Build Status](https://travis-ci.org/resilient-http/resilient.go.png)](https://travis-ci.org/resilient-http/resilient.go) [![GitHub release](http://img.shields.io/github/tag/resilient-http/resilient.go.svg?style=flat-square)](https://github.com/resilient-http/resilient.go/releases) [![GoDoc](https://godoc.org/github.com/resilient-http/resilient.go?status.svg)](https://godoc.org/github.com/resilient-http/resilient.go) [![Coverage Status](https://coveralls.io/repos/resilient-http/resilient.go/badge.svg?branch=master)](https://coveralls.io/r/resilient-http/resilient.go?branch=master)

Middleware-oriented, plugable and fault tolerant HTTP client written in [Go](http://golang.org) designed 
for distributed and [reactive](http://www.reactivemanifesto.org/) systems

This implementation was originally based on [resilient.js](https://github.com/resilient-http/resilient.js), 
but focused on better design, extensibility and simplicity.

Requires Go +1.3

**Work in progress**

## Superpowers

- Full featured HTTP client build on top of `net/http`
- No third-party dependencies (only native packages are used)
- Smart fail over (via multiple strategies)
- Dynamic server discovery (via middleware)
- Retries cycles 
- Client side based balancing and load distribution (via)

**This is a work in progress**

## Installation

```
go get gopkg.in/resilient-http/resilient.go.v0
```

## Addons

### Strategies

- Failover

### Middlewares

- Server discovery

## Rationale

Distributed and reactive system architectures are growing during last years, but they are mostly hard to support since most of the complexibility is delegated in the consumer side.

Resilient aims to simplify this to deal elegantly with distributed systems

## License 

MIT - Tomas Aparicio
