### overflow
- 要素のボックスからはみ出た部分をどう扱うかを指定するプロパティ
- 指定できる値
  - visible: 初期値。はみ出た部分がそのまま表示される
  - hidden: はみ出た部分が隠れる
  - scroll: はみ出た部分が隠れてスクロールできる
  - auto: ブラウザにより表示が変わる (基本的にはスクロールできる)
- 横スクロールにしたい場合

```css
.foo {
  white-space:nowrap;
  overflow:scroll;
}
```

#### overflow-x, overflow-y
- 横方向、縦方向のはみ出た部分の扱いを指定できるプロパティ
- 指定できる値はoverflowと同じ

