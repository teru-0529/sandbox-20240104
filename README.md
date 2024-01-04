# sandbox-20240104

Gitコマンドの確認用

## 0. 準備

* ファイルDummy1.txt、Dummy2.txtを作成

## 1. git stash

現在の作業ディレクトリの変更が一時的に退避できる。Gitは、変更をスタック（stack）に保存。
https://zenn.dev/ganmo3/articles/5bf0b9d42894c4

```powershell
# 変更を一時的に退避する
git stash
# stashした変更の一覧を表示する
git stash list
# stashした変更を復元して削除する
git stash pop
```

* 新規ブランチを作成し変更、コミット前にコマンドの確認
