---
title: "`event.timeStamp` now returns `DOMHighResTimeStamp` on Nightly/Aurora for Linux"
date: "2015-09-09T15:11:00-04:00"
categories: ["dom"]
tags: []
versions: "43"
references:
    "https://bugzilla.mozilla.org/show_bug.cgi?id=1026803": "Bug 1026803 - Convert native event times to TimeStamps for Linux"
---
Starting with version 43, the [`event.timeStamp`](https://developer.mozilla.org/en-US/docs/Web/API/event.timeStamp) property returns a [`DOMHighResTimeStamp`](https://developer.mozilla.org/en-US/docs/Web/API/DOMHighResTimeStamp) in microseconds, instead of a traditional time stamp in milliseconds, on the Nightly and Aurora ([Developer Edition](https://www.mozilla.org/firefox/channel/#developer)) channels for Linux. This feature has been implemented on Windows since [Firefox 33](https://www.fxsitecompat.com/en-US/docs/2014/event-timestamp-now-returns-domhighrestimestamp-on-nightly-aurora-for-windows/), but still disabled on the Beta and Release channels, and not yet implemented on OS X.
