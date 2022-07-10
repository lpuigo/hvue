# Intro

hvue is a [GopherJS](https://github.com/gopherjs/gopherjs) wrapper for the
[Vue](https://vuejs.org/) Javascript framework.


It is forked from [github.com/huckridgesw/hvue](https://github.com/huckridgesw/hvue)

# Install

`go get github.com/lpuigo/hvue`

# Examples & Demos

## Overview

Generally speaking, the [examples](https://github.com/huckridgesw/hvue/tree/master/examples)
follow the examples in the Vue [guide](https://vuejs.org/v2/guide/).

[01-introduction](https://github.com/lpuigo/hvue/tree/master/examples/01-introduction)
has examples from the Vue [Introduction](https://vuejs.org/v2/guide/index.html) page.

[02-lifecycle](https://github.com/lpuigo/hvue/tree/master/examples/02-lifecycle)
demos Vue [lifecycle hooks](https://vuejs.org/v2/guide/instance.html#Instance-Lifecycle-Hooks)
but does not correspond to any specific example on that page.

[03-computed-basic](https://github.com/lpuigo/hvue/tree/master/examples/03-computed-basic)
and [04-computed-with-setter](https://github.com/lpuigo/hvue/tree/master/examples/04-computed-with-setter)
have examples from [Computed Properties and Watchers](https://vuejs.org/v2/guide/computed.html).

And so on.  Links are in the code.

## Running the examples

```
cd /path/to/github.com/lpuigo/hvue
gopherjs serve github.com/lpuigo/hvue
```
and then
- http://localhost:8080/examples/01-introduction/
- http://localhost:8080/examples/02-lifecycle/
- http://localhost:8080/examples/ for more

# GoDoc

http://godoc.org/github.com/lpuigo/hvue
