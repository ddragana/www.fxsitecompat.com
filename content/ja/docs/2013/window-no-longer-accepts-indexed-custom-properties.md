---
title: "`window` がインデックス付き独自プロパティを受け入れなくなりました"
date: "2013-02-06T08:44:10-05:00"
categories: ["dom"]
tags: []
versions: "21"
cclicense: "BY-SA 3.0"
references:
    "https://bugzilla.mozilla.org/show_bug.cgi?id=828787": "Bug 828787 – Stop allowing indexed expandos on windows"
---
[`window`](https://developer.mozilla.org/ja/docs/Web/API/window) オブジェクト上でのインデックス付きエクスパンド (数値をプロパティ名として持つ独自プロパティ) の指定が許容されなくなりました。今後 `window[2] = "myString"` のようなコードは無視されます。