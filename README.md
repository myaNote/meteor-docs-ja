## Meteor公式ドキュメント日本語化

### 手順

1. リポジトリを更新する。
2. translationsの中にファイルを作成する。ファイル名は"タグ-日付-作者.json"。基本的には`<p>`タグの単位で。
3. 翻訳が完了していない段落をコピペして、jsonファイルに貼り付ける。keyが原文でvalueが訳文のオブジェクトにする。
4. `npm run translate`を実行して、トップディレクトリに生成されたhtmlをブラウザで確認する。
5. 問題なければ、commitしてpushする。

### コミュニケーション

細かい調整などが必要であれば、[Slack](https://meteor-fan.herokuapp.com/)の#docs-jaチャンネルで。

----
以上は暫定案です。今後必要に応じて見直します。
