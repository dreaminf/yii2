受入テスト
==========

受入テストはユーザの視点からシナリオを検証するものです。
テストされるアプリケーションは PhpBrowser または実際のブラウザによってアクセスされます。
どちらの場合でも、ブラウザは HTTP によって通信しますので、アプリケーションはウェブサーバによってホストされる必要があります。

受入テストは Codeception フレームワークの助けを借りて実装されています。Codeception フレームワークには優れたドキュメントがありますので、参照して下さい。

- [Codeception for Yii framework](http://codeception.com/for/yii)
- [Codeception Acceptance Tests](http://codeception.com/docs/03-AcceptanceTests)

## ベーシックテンプレート、アドバンストテンプレートのテストを実行する

アドバンストテンプレートで開発をしている場合は、テスト実行の詳細について、
["テスト" のガイド](https://github.com/yiisoft/yii2-app-advanced/blob/master/docs/guide-ja/start-testing.md) を参照して下さい。

ベーシックテンプレートで開発をしている場合は、[README の "testing" の節](https://github.com/yiisoft/yii2-app-basic/blob/master/README.md#testing) を参照して下さい。
