# DAY2 - Part1

## Webページ開発の準備

デスクトップ上にitcaretというフォルダを作ってください。

> 以降、作成するファイルはitcaretフォルダ上に保存します。

---

## PART1 HTML編

### Wikipedia

> HyperText Markup Language（ハイパーテキスト マークアップ ランゲージ）、略記・略称HTML（エイチティーエムエル）とは、ウェブ上の文書を記述するためのマークアップ言語である。 文章の中に記述することでさまざまな機能を記述設定することができる。- Wikipedia

HTMLファイルはテキストエディタで作成します。作成したHTMLファイルはブラウザで結果を確認できます。

テキストエディタには次のようなソフトウェアがあります。

+ Atom
  + https://atom.io/
+ Brackets
  + http://brackets.io/
+ Visual Studio Code
  + https://code.visualstudio.com/

ブラウザには次のようなソフトウェアがあります。

+ Chrome
  + https://www.google.com/intl/ja_ALL/chrome/
+ Firefox
  + https://www.mozilla.org/ja/firefox/new/
+ Safari
  + https://www.apple.com/jp/safari/

---

### hello.html

テキストエディタでHTMLファイルを作成してみましょう。

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Hello</title>
  </head>
  <body>
    <h1>Hello World</h1>
  </body>
</html>
```

> 作成したファイルは ctrl + s で保存するようにします。

コードを保存したらブラウザで表示してみましょう。

> &lt;h1&gt;の部分を&lt;h2&gt;、&lt;h3&gt;に変更してみましょう。

---

### image.html

imgタグを使って画像を表示します。

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Image</title>
  </head>
  <body>
    <img src="http://kronos.jp/img/logo.png">
  </body>
</html>
```

コードを保存したらブラウザで表示してみましょう。

---

### link.html

リンクを表示します。

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>link</title>
  </head>
  <body>
    <a href="http://itcaret.com/">IT CARET</a>
  </body>
</html>
```

コードを保存したらブラウザで表示してみましょう。

---

### list.html

リスト（箇条書き）を表示してみましょう。

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>List</title>
  </head>
  <body>
    <ul>
      <li>PHP</li>
      <li>Java</li>
      <li>JavaScript</li>
    </ul>
  </body>
</html>
```

コードを保存したらブラウザで表示してみましょう。

---

### 課題

以下のタグを試してみましょう。それぞれのタグの役割を考察してください。

#### hNタグ

```html
<h1>Head1</h1>
<h2>Head2</h2>
<h3>Head3</h3>
```

#### pタグ

```html
<p>paragraph</p>
```


#### tableタグ

```html
<table>
  <tr>
    <td>A1</td>
    <td>A2</td>
    <td>A3</td>
  </tr>
  <tr>
    <td>B1</td>
    <td>B2</td>
    <td>B3</td>
  </tr>
</table>
```

#### divタグ

```html
<div>division</div>
```
