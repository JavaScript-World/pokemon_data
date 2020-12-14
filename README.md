※このページはフォークです。元はkotofurumiya様のページにあります。
フォーク後の変更点は次の通りです。
- ミニリュウ、ハクリュー、クラブ、キングラーのとくせいの誤字を修正
- ガラルのすがたを追加
- メルタン、メルメタル、ガラルのポケモンを追加
- レギジガスからレジギガスに修正
- index.htmlを追加 (テスト用ページ)  アクセス: http://javascript-world.github.io/pokemon_data
# pokemon_data

ポケットモンスターの全ポケモンの日本語データです。ご自由にお使いください。

data/pokemon_data.jsonファイルにデータが入っています。

## 収載しているデータ

- 図鑑番号
- 名前
- フォーム名
- 進化先
- タイプ
- 特性
- 種族値

## 収載していないデータ

- 覚える技
- 倒して手に入る努力値
- 野生出現時の持ち物
- など

## 編集方法

必要なnpmパッケージをインストールします：

```bash
$ npm install
```

インストールできたら、手動でjsonファイルを編集してください。

編集したら、formatコマンドでフォーマットを整えます。

```bash
$ npm run format
```

最後に、validateコマンドでデータが正しいか検証してください：

```bash
$ npm run validate
```

## ミスを発見したら

pokemon_dataは手動で入力しています。そのためデータの記載ミスが存在する場合があります。

ミスを発見した際は、[issueを作成する](https://github.com/kotofurumiya/pokemon_data/issues)か、
Twitterで[@kfurumiya](https://twitter.com/kfurumiya)宛にリプライを飛ばしてください。
