---
layout: single
category: command
author_profile: false
excerpt: ""
title: crossentropy
tags: [Exponential and logarithmic functions]
comments: true
date: '2016-09-17'
sidebar:
  nav: "commands"
---

### Description
[crossentropy](/command/crossentropy) is defined as \\(-\sum x_i\log(y_i)\\). Read more on [Wikipedias article on cross entropty](http://en.wikipedia.org/wiki/Cross_entropy).

### Syntax

````matlab
z = crossentropy(x,y)
````

### Implementation

The operator is implemented as a [callback operator](/tutorial/nonlinearoperatorscallback).
