# 21. 複数のHTML要素を用いて自己紹介ページの作成
`<h1>`（見出し），`<p>`（段落），`<ul>・<li>`（リスト），`<a>`（リンク），`<img>`（画像）などを用いて，自己紹介ページを作成すること．外部サイト（例：九州大学のWebサイトなど）へのリンクを1つ以上含めること．画像はフリー素材やアイコン等でもよい．`<img>`には内容を説明するalt属性を付けること．

```

<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>自己紹介</title>
</head>
<body>
  

<h1>自己紹介ページ</h1>


<h2>基本情報</h2>
  <ul>
    <li>松本真美</li>
    <li>芸術工学部メディアデザインコース4年</li>
    <li>B型</li>
  </ul>

<h2>好きなモノ・コト</h2>
  <ul>
    <li>紅茶・コーヒー</li>
    <li>モスバーガー</li>
    <li>クラゲ</li>
    <li>野球観戦</li>
    <li>M!LK</li>
  </ul>

<h2>所属（元）</h2>
<p>未定研に所属していました</p>
 <img src="aruba.jpeg" alt="サムネ" width="120" height="120">
よければ過去作品もご覧ください！
<p><a href="https://youtu.be/C2iAzqANcyw?si=IPfuCwp0LRa4CBip">2025年上映作品「空色のアルバ」</a></p>


</body>
</html>

```


