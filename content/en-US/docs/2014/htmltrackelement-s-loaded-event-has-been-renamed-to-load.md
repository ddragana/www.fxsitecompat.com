---
title: "`HTMLTrackElement`\'s `loaded` event has been renamed to `load`"
date: "2014-07-22T05:06:26-04:00"
categories: ["audio-video"]
tags: []
versions: "33"
cclicense: "BY-SA 3.0"
references:
    "https://bugzilla.mozilla.org/show_bug.cgi?id=1035505": "Bug 1035505 – [webvtt] HTMLTrackElement should fire a \'load\' event not a \'loaded\'"
---
The implementation of the [`HTMLTrackElement`](https://developer.mozilla.org/en-US/docs/Web/API/HTMLTrackElement) interface has been updated to fire a `load` event instead of `loaded`, to comply with the latest spec.
