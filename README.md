# CSSの:has()で親セレクターを使いこなす — デモ

CodeGrid「CSSの`:has()`で親セレクターを使いこなす」シリーズのデモファイル集です。

- [第1回](https://www.codegrid.net/articles/2026-css-selector-has-1/)
- [第2回](https://www.codegrid.net/articles/2026-css-selector-has-2/)

## デモ一覧

### @supportsによるサポート確認

今お使いのブラウザが`:has()`に対応しているかどうかを、`@supports selector(:has(*))`で確認します。

- [デモを見る](https://codegrid.github.io/2026-css-selector-has/supports-check.html)
- [ソースコード](./supports-check.html)
- 掲載記事：第1回

---

### フォームのバリデーション状態

`.form-group:has(input:invalid)`を使って、無効な入力を含むフォームグループ全体の色を変えます。

- [デモを見る](https://codegrid.github.io/2026-css-selector-has/form-validation.html)
- [ソースコード](./form-validation.html)
- 掲載記事：第1回

---

### モーダルダイアログのスクロールロック

`body:has(:modal)`を使って、モーダルダイアログが開いているあいだ背景のスクロールをCSSだけで止めます。

- [デモを見る](https://codegrid.github.io/2026-css-selector-has/scroll-lock.html)
- [ソースコード](./scroll-lock.html)
- 掲載記事：第1回

---

### ホバー中のカード以外を暗くする

`.card-list:has(.card:hover) .card:not(:hover)`を使って、ホバーされていないカードの透明度を下げます。

- [デモを見る](https://codegrid.github.io/2026-css-selector-has/card-hover.html)
- [ソースコード](./card-hover.html)
- 掲載記事：第1回

---

### 画像の有無でカードのレイアウトを切り替える

`.card:has(img)`と`.card:not(:has(img))`を使って、画像があるカードとないカードのグリッドレイアウトを自動で切り替えます。

- [デモを見る](https://codegrid.github.io/2026-css-selector-has/card-layout.html)
- [ソースコード](./card-layout.html)
- 掲載記事：第2回

---

### 連続する見出しのマージンを調整する

`h2:has(+ h3)`を使って、直後に別の見出しが続く見出しの下マージンだけを縮めます。

- [デモを見る](https://codegrid.github.io/2026-css-selector-has/heading-margin.html)
- [ソースコード](./heading-margin.html)
- 掲載記事：第2回

---

### サブメニューを持つナビゲーションにアイコンを追加する

`nav li:has(ul)`を使って、サブメニューを持つナビゲーション項目にだけ▼アイコンを追加します。

- [デモを見る](https://codegrid.github.io/2026-css-selector-has/nav-icon.html)
- [ソースコード](./nav-icon.html)
- 掲載記事：第2回
