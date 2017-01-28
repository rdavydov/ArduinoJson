---
title: Why some parts are missing?
layout: faq
tags: faq
---

Example: you want to write `{"p1":[0, 1]}`, but instead you get `{"p1":[]}`.

This is because the `StaticJsonBuffer` too small.

Solution: Increase the size of the `StaticJsonBuffer` or switch to a `DynamicJsonBuffer`.

See also:

* [What are the differences between StaticJsonBuffer and DynamicJsonBuffer?](#what-are-the-differences-between-staticjsonbuffer-and-dynamicjsonbuffer)
* [How to determine the buffer size?](#how-to-determine-the-buffer-size)
* [JsonBuffer size calculator](https://bblanchon.github.io/ArduinoJson/)
* Issues [#360](https://github.com/bblanchon/ArduinoJson/issues/360), [#372](https://github.com/bblanchon/ArduinoJson/issues/372), [#374](https://github.com/bblanchon/ArduinoJson/issues/374) and [#380](https://github.com/bblanchon/ArduinoJson/issues/380)