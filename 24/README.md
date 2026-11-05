# 24. 入力フォームの作成
名前やメールアドレスを入力できるフォーム（`<form>`タグ＋`<input>`タグ等）を作成すること．
各入力欄に`<label>`を対応付け，type="email"やrequired属性によるブラウザの入力チェックも利用すること．
ボタン（`<button>`または`<input type="submit">`）も追加すること．

```

<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>入力フォーム</title>
</head>
<body>

  <h2>入力してください</h2>

  <form>
    <div>
      <label for="name">名前：</label>
      <input type="text" id="name" name="user_name" required placeholder="例：九大花子">
    </div>

    <div>
      <label for="email">メールアドレス：</label>
      <input type="email" id="email" name="user_email" required placeholder="example@email.com">
    </div>

    <div>
      <button type="submit">送信する</button>
    </div>
  </form>

</body>
</html>

```


