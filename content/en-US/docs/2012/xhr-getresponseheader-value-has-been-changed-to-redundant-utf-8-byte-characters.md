---
title: "`XHR.getResponseHeader()` value has been changed to redundant UTF-8 byte characters"
date: "2012-12-03T03:53:26-05:00"
categories: ["dom"]
tags: []
versions: "18"
cclicense: "BY-SA 3.0"
references:
    "https://bugzilla.mozilla.org/show_bug.cgi?id=795867": "Bug 795867 – XHR getResponseHeader() should inflate the value"
---
Following the latest [`XMLHttpRequest`](https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest) spec, the [`XMLHttpRequest.getResponseHeader`](https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest#getResponseHeader) method now returns value expressed in redundant encoding. For example, "`…`" will be "`\xE2\x80\xA6`".
