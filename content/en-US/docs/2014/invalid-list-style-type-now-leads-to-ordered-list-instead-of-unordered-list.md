---
title: "Invalid `list-style-type` now leads to ordered list instead of unordered list"
date: "2014-07-22T05:06:26-04:00"
categories: ["css"]
tags: []
versions: "33"
cclicense: "BY-SA 3.0"
references:
    "https://bugzilla.mozilla.org/show_bug.cgi?id=1027647": "Bug 1027647 – invalid list-style-type makes ordered list from unordered list"
---
Starting with Firefox 33, invalid [`list-style-type`](https://developer.mozilla.org/en-US/docs/Web/CSS/list-style-type) property values, like `non`, `bulleted` or `disk`, are fallbacked to `decimal` instead of `disc`, to follow the CSS3 Counter Styles spec.
