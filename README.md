# gitbootcamp
## git commit -a
変更されたファイル(新規を除く)をコミット対象に追加し,コミットする。
## git commit --amend
一つ目のコミットに後からの修正もまとめることができる。
一旦コミットしてからちょっとした修正を入れた場合に、この修正も元のコミットに含めてしまいたいときがある。
また、git commit --amend --no-editとすることで、エディタを開かずに修正することができる。
## git branch fix/42
   ブランチとは、履歴の流れを分岐して記録していく
## git checkout -b fix/42; git commit
新規ブランチfix/42を作成して即時チェックアウトする。その後、コミット対象と指定されたファイルをブランチfix/42にコミットする。
