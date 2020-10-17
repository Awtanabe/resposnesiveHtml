
## Todo

- レスポンシブ
  - カラム落ち or カラム数変更
  - 要素消す



## 学び

- リセットcss
- 基本的なHTMLタグの使い方
  - sectionタグ
- ナビゲーション
  - nav-container
    - width %で指定 && margin 0 auto
  - フロートを使わない

- 画像の扱い

親の要素を%で指定
imgはwidth100%で指定をすると親の要素の中で治る
.item{
  width: 30%;
}
.item img{
  width: 100%;
}

- text-align

ブロックコンテナ内の行を揃える
http://www.htmq.com/style/text-align.shtml

- flex box
   floatを使わずにflexを使う

  display: flex;
  justify-content: center;

- 凡庸なクラス名はcssの競合を起こすのでだめ絶対
  ex） .itemはだめ！！ 具体性あげる！！

- 複数のcss指定
リセットcssでやるかも
body,
h1 {


- ブロックの中のaタグの一の調整
ligh-height

- hover