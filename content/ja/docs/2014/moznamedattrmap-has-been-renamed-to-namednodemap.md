---
title: "`MozNamedAttrMap` が `NamedNodeMap` へ改名されました"
date: "2014-09-01T22:12:15-04:00"
categories: ["dom"]
tags: []
versions: "34"
cclicense: "BY-SA 3.0"
references:
    "https://bugzilla.mozilla.org/show_bug.cgi?id=1055467": "Bug 1055467 – Rename MozNamedAttrMap to NamedNodeMap"
---
[`NamedNodeMap`](https://developer.mozilla.org/ja/docs/Web/API/NamedNodeMap) インタフェースは、仕様から削除されたため [Firefox 22](https://www.fxsitecompat.com/ja/docs/2013/namednodemap-has-been-renamed-to-moznamedattrmap/) で `MozNamedAttrMap` へ改名されましたが、後方互換性のため Firefox 34 で `NamedNodeMap` へ戻されました。
