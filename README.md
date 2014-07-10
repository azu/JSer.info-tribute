# JSer.info-tribute

[azu/jser.info](https://github.com/azu/jser.info "azu/jser.info") に対して載せたいサイト等のpull requestを補助するサイトです。

以下から利用できます。

* [JSer.info Contributing form](http://azu.github.io/JSer.info-tribute/ "JSer.info Contributing form")


## Usage

1. [JSer.info Contributing form](http://azu.github.io/JSer.info-tribute/ "JSer.info Contributing form")にアクセス
2. 紹介したいサイトの情報を入力する
4. [azu/jser.info](https://github.com/azu/jser.info "azu/jser.info") のデータに追記する
5. pull requestする

### Parameter

URLの含まれる特定のクエリと入力項目は対応しているため、

`http://azu.github.io/JSer.info-tribute/?title=TEST&url=http://example.com&content=content&tags=javascript,library`

のようなURLにアクセスする事で、項目を入力した状態で開くことが出来ます。

対応しているパラーメータは以下のとおりです

* `title`
    * サイトタイトル
* `url`
    * サイトURL
* `content`
    * 説明文
* `tags`
    * タグ(カンマ区切りで複数並べられます)

簡単なブックマークレットも用意してあります。

* [JSer.info Contributing - Hatena::Let](http://let.hatelabo.jp/efcl/let/hJmdgKOVlstQ "JSer.info Contributing - Hatena::Let")

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Build

``` sh
npm install
npm install -g gulp
gulp watch
```

## License

MIT