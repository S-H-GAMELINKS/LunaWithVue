# Luna With Vue.js
## 概要
C++のWebフレームワーク：[Luna](https://github.com/DEGoodmanWilson/luna) と[Vue.js](https://github.com/vuejs/vue)と[Webpack](https://github.com/webpack/webpack)を組み合わせて制作したSPAサンプル。

## ビルド

[こちら](https://luna.goodman-wilson.com/using.html)を参考にLunaの環境を構築する

それとは別にNodejs環境とyarnの準備も必要。

ソースをclone

```
git clone https://github.com/S-H-GAMELINKS/LunaWithVue.git
```

ディレクトリを移動して、

```
cd LunaWithVue
```

```
conan install .
conan build .
```

を実行。

その後、`assets` ディレクトリに移動して

```
cd assets
yarn install
yarn build
```

を実行し、yarnで管理しているライブラリの導入とwebpackでのビルドを行う。

最後に、ディレクトリを移動して

```
cd .. && ./bin/awesomesauce
```

でアプリする。
`localhost:8080`で実際のページにアクセスできる。

## ライセンス
[MIT](./LISENCE)　ライセンスです。