+++
title = "Go is for lovers"
date = "2015-09-17T13:47:08+02:00"
tags = ["go"]
categories = ["programming"]
images = ""
+++

Hugo uses the excellent [go][] [html/template][gohtmltemplate] library for
its template engine. It is an extremely lightweight engine that provides a very
small amount of logic. In our experience that it is just the right amount of
logic to be able to create a good static website. If you have used other
template systems from different languages or frameworks you will find a lot of
similarities in go templates.

This document is a brief primer on using go templates. The [go docs][gohtmltemplate]
provide more details.

## Introduction to Go Templates

Go templates provide an extremely simple template language. It adheres to the
belief that only the most basic of logic belongs in the template or view layer.
One consequence of this simplicity is that go templates parse very quickly.

A unique characteristic of go templates is they are content aware. Variables and
content will be sanitized depending on the context of where they are used. More
details can be found in the [go docs][gohtmltemplate].

**Example:**

    {{ add 1 2 }}

## Logic

Go templates provide the most basic iteration and conditional logic.

* false
* 0
* any array, slice, map, or string of length zero


One of the most powerful components of go templates is the ability to
stack actions one after another. This is done by using pipes. Borrowed
from unix pipes, the concept is simple, each pipeline's output becomes the
input of the following pipe.

Because of the very simple syntax of go templates, the pipe is essential
to being able to chain together function calls. One limitation of the
pipes is that they only can work with a single value and that value
becomes the last parameter of the next pipeline.

A few simple examples should help convey how to use the pipe.

```
---
title: "Permalinks"
date: "2013-11-18"
aliases:
  - "/doc/permalinks/"
groups: ["extras"]
groups_weight: 30
notoc: true
---
```


[go]: <http://golang.org/>
[gohtmltemplate]: <http://golang.org/pkg/html/template/>
