---
title: Window.console
slug: Web/API/Window/console
---

{{ APIRef }}

読み取り専用プロパティの **`Window.console`** は、ブラウザーのコンソールへ情報を出力するメソッドを提供する{{domxref("Console")}}オブジェクトへの参照を返します。これらのメソッドで出力される情報はデバッグ目的のものであり、ユーザーへ情報を提示するために使われるべきではありません。

## 構文

```js
var consoleObj = window.console;
```

## 例

### コンソールへの出力

一つ目の例はテキストをコンソールに出力します。

```js
console.log("An error occurred while loading the content");
```

次の例では開閉ウィジェットによって要素が展開可能な状態でオブジェクトをコンソールに出力します。

```js
console.dir(someObject);
```

より詳細な例については{{SectionOnPage("/ja/docs/Web/API/Console", "Usage")}}をご参照下さい。

## 仕様書

{{Specifications}}

> **メモ:** 現在はブラウザー間で多くの実装の違いがありますが、それらを統合して互いの一貫性を高める作業が進められています。
