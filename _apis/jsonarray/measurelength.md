---
title: JsonArray::measureLength()
layout: api
tags: api
api-group: JsonArray
---

##### Description

Gets the length of string produced by `JsonArray::printTo()`.

This can be very handy to fill the `Content-Length` of an HTTP request or response.

##### Return value

The number of characters in the JSON string that would be generated by `JsonArray::printTo()`.

It doesn't include the zero-terminator.

##### Signature

```c++
size_t measureLength() const
```