# 転生した二人は魔術とITを融合させる(Two people who transmigrated make magic and IT fused)

[![Greenkeeper badge](https://badges.greenkeeper.io/yumetodo/novel_two_people_who_transmigrated_make_magic_and_IT_fused.svg)](https://greenkeeper.io/)

大体は

- [星月夜の窓](http://wayback.archive.org/web/20140501091437/http://hosidukiyo.at-ninja.jp/novel_c/cm_idx.html)
- [魔法の世界のアリス - ハーメルン](https://novel.syosetu.org/195/)
- [魔法科高校の幻想紡義 -旧- - ハーメルン](https://novel.syosetu.org/8796/)
- [恋ぞ積もりて　淵となりぬる - ハーメルン](https://novel.syosetu.org/41759/)
- [「羽吹の巫女」/「yuzhon」のシリーズ [pixiv]](http://www.pixiv.net/series.php?id=606923)

の二次創作です。星月夜の窓の六神さんからは二次創作許可もらっていますが、背景設定にちらっと出てくる程度かな・・・。
他は二次創作と言っても跡形も無いくらい変わると思います。

## Installation

    npm install -g gitbook-cli
    npm install

Node.js 6.0.0以上が必要です。

## Usage

**Build**

GitBookのbuildをします
    
    npm run build
    
**Watch**

GitBookのbuildかつWatchをします。
プレビューをする場合は、ローカルサーバを利用してください。

次のコマンドを実行後、[http://localhost:4000/](http://localhost:4000/)へアクセスすることでプレビューを見られます。

    npm run serve
    # open http://localhost:4000/

### Trouble Shooting

#### buildに失敗する

GitBook3.2.1を使っている場合、buildに失敗することがわかっています。

    gitbook update
    
して最新のGitBookを使うようにしてください

#### serveに失敗する(Linux)

ファイルを監視するディスクリプタの許容数を超えてしまい、失敗することがあります。

```sh
$ echo fs.inotify.max_user_watches=524288 | sudo tee -a /etc/sysctl.conf && sudo sysctl -p
```

してください。

#### 改行がおかしい

Gitbook3.2.1以前を利用している場合に発生します。

    gitbook update

してGitBook3.2.2以降を使うようにしてくだい

## Contributing

小さなtypoでもIssueやPull Requestを歓迎しています。

コントリビュートの方法や確認方法については[CONTRIBUTING.md](./CONTRIBUTING.md)を見てください。

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

- 謎。二次創作する承諾は得てるけど、勝手に原文を再公開する承諾は得てない。
