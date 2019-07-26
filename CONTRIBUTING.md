# CONTRIBUTING

新しく話を書いて送ってこられても無視します。

気になった矛盾点などはIssueにどうぞ。

## Pull Requestの送り方

文章のtypoの修正程度なら、直接GitHub上で編集してPull Requestを送ってください。

- [Editing files in your repository - User Documentation](https://help.github.com/articles/editing-files-in-your-repository/ "Editing files in your repository - User Documentation")

ローカルで編集して送りたい場合は次の手順を試してください。

1. Forkする
2. Branchを作る: `git checkout -b my-new-feature`
3. lintを掛ける: `npm run lint`
4. 変更をコミットする: `git commit -am 'Add some feature'`
5. Pushする: `git push origin my-new-feature`
6. Pull Requestを送る :D
