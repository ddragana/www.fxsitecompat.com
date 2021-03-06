---
title: "Delay between touch and mouse events has been removed on responsive pages"
date: "2014-03-21T04:50:04-04:00"
categories: [event-handling]
tags: []
versions: "30"
cclicense: "BY-SA 3.0"
references:
    "https://bugzilla.mozilla.org/show_bug.cgi?id=941995": "Bug 941995 – Remove 300ms touch > mouse events delay for double-tap zoom on \"responsive\" pages"
---
Both [Firefox for Android](https://developer.mozilla.org/en-US/Firefox_for_Android) and [Firefox OS](https://developer.mozilla.org/en-US/Firefox_OS) support double-tap-to-zoom, and there is a 300-millisecond delay between the touch event ([`touchend`](https://developer.mozilla.org/en-US/docs/Web/Reference/Events/touchend)) and the mouse event ([`click`](https://developer.mozilla.org/en-US/docs/Web/Reference/Events/click)) to detect and enable this gesture. In order to improve the responsiveness of applications, this delay has been removed on non-zoomable, [responsive designed](https://developer.mozilla.org/en-US/docs/Web_Development/Mobile/Responsive_design) pages that specify `width=device-width` (or some value less than `device-width`) and/or `user-scalable=no` in the [viewport `<meta>` tag](https://developer.mozilla.org/en-US/docs/Mozilla/Mobile/Viewport_meta_tag). Google Chrome 32 also removed the delay. Read an [article on HTML5 Rocks](http://updates.html5rocks.com/2013/12/300ms-tap-delay-gone-away) for details.
