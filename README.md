# Git Lesson



## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
  - リモートリポジトリ
   - 開発したデータをネット上に配置するために使用されるリポジトリ。複数人でデータを共有し編集できる。
  - ローカルリポジトリ
   - 開発者が個人のPC上にデータを配置する為のリポジトリ。


## プッシュとマージの違いは何でしょうか？
  - プッシュ
    - ローカルで編集したデータをリモートのブランチに反映させる。
  - マージ
    - 分岐させて編集したデータを別のデータに融合させる。


## コミットとプッシュの違い
  - コミットは、編集した内容をローカルリポジトリに上書きする為のコマンド。プッシュは、ローカルリポジトリの内容をリモートリポジトリに反映させる為のコマンド。


## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
  - 編集した内容が一目で分かるように書く


## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
  - 作成した内容をそのままmainにマージしてしまうと、もし不具合やバグがあった際気付かないまま作業が進んでしまうが、プルリクエストでマージすれば別の人の目に触れる為、不具合を発見し問題が起こる事を未然に防ぐことができる。


## コンフリクトを起こしてしまった場合、どう対処すべきですか？
  - 問題が生じている部分を確認し、修正をしたら再度コミットする。
