---
title: "タッチイベント対応がデスクトップで一時的に無効化されました"
date: "2013-05-19T07:35:00-04:00"
categories: [event-handling]
tags: []
versions: "24"
cclicense: "BY-SA 3.0"
references:
    "https://bugzilla.mozilla.org/show_bug.cgi?id=888304": "Bug 888304 – Content touch-events on Firefox-desktop should be disabled until we can support them properly"
---
[Firefox 18](http://www.fxsitecompat.com/ja/versions/18/) で導入された [タッチイベント](https://developer.mozilla.org/ja/docs/Web/Guide/API/DOM/Events/Touch_events) 対応が**デスクトップ版** Firefox で無効化されました。Google や Twitter といった一部の人気サイトが正常に動作していないことが確認されたためです。バグが修正され次第、この API は再度有効化されます。強制的に有効化するには、`about:config` を開き `dom.w3c_touch_events.enabled` の設定値を `2` に変更してください。[Firefox for Android](https://developer.mozilla.org/ja/docs/Mozilla/Firefox_for_Android) と [Firefox OS](https://developer.mozilla.org/ja/docs/Mozilla/Firefox_OS) を含むモバイル版はこの変更を受けません。また、この API は Windows 8 向けの Metro スタイル Firefox では有効化されています。