# DAY2 - Part2

## PART2 CSS

> Cascading Style Sheets - HTML、XMLの表示レイアウトなどの修飾を指定するのための仕様。 - Wikipedia

CSSファイルはHTMLファイルと同様にテキストエディタで作成します。HTMLファイルからCSSファイルを参照することで、文字色や背景色を変更したり、文字の大きさやベージの余白を調整したり、Webページ全体の見栄えを変更することができます。

CSSでスタイルを指定するには以下の3つの方法があります。

+ タグ名による指定
+ id属性による指定
+ class属性による指定

---

### sample.html

まずは動作確認用にHTMLを作成します。

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>CSS Sample</title>
    <link rel="stylesheet" href="style01.css">
  </head>
  <body>
    <div>
      <h1 id="title">Programming</h1>
      <ul>
        <li class="server">PHP</li>
        <li class="server">Java</li>
        <li class="client">JavaScript</li>
      </ul>
    </div>
  </body>
</html>
```

HTMLファイルは&lt;link&gt;タグでCSSファイルを参照することができます。

```html
<link rel="stylesheet" href="style01.css">
```

上記の場合、style01.cssファイルを参照するように指定しています。


> 以降は上記のsample.htmlファイルをベースに作業していきます。ブラウザで動作確認をする際はsample.htmlにアクセスするようにします。

---

### style01.css

タグ名を指定してスタイルを指定します。

```css
body {
  background-color: #eeeeee;
  color: white;
}

div {
  background-color: #6FC041;
}
```

+ スタイルは {} の中に ```プロパティ: 値;``` で定義します。
+ background-colorは背景色を指定しています。
+ colorはテキストの色を指定しています。
+ 色の指定にはカラーネーム、カラーコードの2種類があります。

---

### style02.css

id属性を指定してスタイルを指定します。id属性には一つのHTMLの中で重複のない値を指定します。

```css
#title {
  font-size: 64px;
}
```

+ id属性を指定する場合は先頭に```#```をつけます。
+ font-sizeプロパティはフォントサイズを指定します。


---

### style03.css

class属性を指定してスタイルを指定します。class属性は関係のある要素をグループ化します。

```css
.server {
  color: blue;
}

.client {
  color: red;
}
```

+ class属性を指定する場合は先頭に.をつけます。

---

### 課題

以下のスタイルを試してみましょう。それぞれのスタイルの役割を考察してください。

#### margin

```css
h1 {
  margin : 20px;  
}
```

#### padding

```css
#title {
  padding : 20px;
}
```

#### border

```css
.server {
  border: 1px solid gray;
}
```
