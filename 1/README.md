# create-react-appをinstallする

テンプレートから初期状態作成
```
npx create-react-app fake-take-note --template cra-template-typescript
```

起動チェック
```
cd fake-take-note
yarn start
```

# ディレクトリ構造を決める
大きく２つの選択肢がある。

* １つの画面上で、いろいろ切り替わるネイティブアプリケーションっぽいやつ
* 複数のページを行き来するブログっぽいやつ

ネイティブアプリケーション
App.tsxをルートページとして、内部に複数のcontainerコンポーネントをもつ。containerコンポーネントは
* container
* components


複数ページ
routesコンポーネントをApp.tsxにもたせ、表示を切り替える。各ページはpages(views)コンポーネントを作成する。
* pages or views
* components
* routes
