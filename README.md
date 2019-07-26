# 転生した二人は魔術とITを融合させる(Two people who transmigrated make magic and IT fused)

大体は以下の作品の二次創作です。

- [星月夜の窓](http://wayback.archive.org/web/20140501091437/http://hosidukiyo.at-ninja.jp/novel_c/cm_idx.html)
- [魔法の世界のアリス - ハーメルン](https://novel.syosetu.org/195/)
- [サラダ・デイズ/ありふれた世界が壊れる音 - ハーメルン](https://syosetu.org/novel/91849/)
- [ハリー・ポッターと帝王のホムンクルス - ハーメルン](https://syosetu.org/novel/90960/)
- [魔法科高校の幻想紡義 -旧- - ハーメルン](https://novel.syosetu.org/8796/)
- [恋ぞ積もりて　淵となりぬる - ハーメルン](https://novel.syosetu.org/41759/)
- [「羽吹の巫女」/「yuzhon」のシリーズ [pixiv]](http://www.pixiv.net/series.php?id=606923)

星月夜の窓の六神さんからは二次創作許可もらっていますが、背景設定にちらっと出てくる程度かな・・・。  
他は二次創作と言っても跡形も無いくらい変わると思います。

## Build

[mdbook](https://github.com/rust-lang-nursery/mdBook)を利用しています。

以下の手順でmdbookを使えるようになります。ファイル名は適宜読み替えてください。  
[https://github.com/rust-lang-nursery/mdBook/releases](https://github.com/rust-lang-nursery/mdBook/releases)

```sh
wget https://github.com/rust-lang-nursery/mdBook/releases/download/v0.3.0/mdbook-v0.3.0-x86_64-unknown-linux-gnu.tar.gz
tar -xvf mdbook-v0.3.0-x86_64-unknown-linux-gnu.tar.gz
export PATH=`pwd`:$PATH
```

本をbuildするには以下のようにします。

```sh
mdbook build
```

本をプレビューする場合は以下のようにします。

```sh
mdbook serve
```

デフォルトでは[http://localhost:3000](http://localhost:3000)にブラウザからアクセスするとプレビュー出来ます。

## Lint

[textlint](https://github.com/textlint/textlint)を使用しています。

以下の手順でtextlintを使えるようになります。

```sh
npm ci
```

lintを掛けるには以下のようにします。

```sh
npm run lint
```

## Contributing

小さなtypoでもIssueやPull Requestを歓迎しています。

コントリビュートの方法や確認方法については[CONTRIBUTING.md](./CONTRIBUTING.md)を見てください。

## License

- CC BY-NC。ただし二次創作作品なので本来原作者の許諾が必要だが冒頭の通り。
