# gitの使い方
- git status
  - ファイルのステータスを確認できる
- git add .
  - すべてのファイルをaddする
- git commit -m "hogehoge"
  - hogehogeという内容でcommitする
- git commit or git commit -av
  - viと同じように書く
- git reset --hard
  - 直前のaddまで戻る
- git stash save
  - stashに現在の変更を保存しておく
- git stash list
  - stashに保存された内容を見れる
- git stash apply stash@{???}
  - stash@{???}の内容を現在のブランチで反映させて、stashの情報をそのままにしておく
- git stash pop
  - stash@{0}の内容を現在のブランチで反映させて、stash@{0}を削除する
- git branch -a
  - すべてのブランチを確認する
- git branch hoge
  - hogeブランチをつくる
- git switch fuga
  - git branch -a で確認できたfugaブランチに移動する
- git push
  - 変更内容をpushする
