## Pull Requestの送り方

文章のtypoの修正程度なら、直接GitHub上で編集してPull Requestを送ってください。

- [Editing files in your repository - User Documentation](https://help.github.com/articles/editing-files-in-your-repository/ "Editing files in your repository - User Documentation")

ローカルで編集して送りたい場合は次の手順を試してください。

1. Forkする
2. Branchを作る: `git checkout -b my-new-feature`
3. テストする: `npm test`
3. 変更をコミットする: `git commit -am 'Add some feature'`
4. Pushする: `git push origin my-new-feature`
5. Pull Requestを送る :D
