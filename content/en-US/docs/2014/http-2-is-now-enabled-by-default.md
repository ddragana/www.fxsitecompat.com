---
title: "HTTP/2 is now enabled by default"
date: "2014-09-01T22:12:15-04:00"
categories: ["networking"]
tags: []
versions: "34"
cclicense: "BY-SA 3.0"
references:
    "https://bugzilla.mozilla.org/show_bug.cgi?id=1047594": "Bug 1047594 – Enable http/2 (and alpn) by default"
    "https://bugzilla.mozilla.org/show_bug.cgi?id=1027720": "Bug 1027720 – Restrict HTTP/2 connections to AEAD ciphers only"
    "https://bugzilla.mozilla.org/show_bug.cgi?id=1077806": "Bug 1077806 – tweetdeck.twitter.com and twitter.com history doesn\'t load in Nightly 35.0a1 and Aurora 34.0a2 when http2 enabled"
---
The [HTTP/2](http://http2.github.io/) spec draft 14 has been implemented and enabled by default for connections using the AEAD cipher suites. If you encountered any regressions, please [report the issue](https://bugzilla.mozilla.org/enter_bug.cgi?product=Core&component=Networking%3A%20HTTP) to Bugzilla.
