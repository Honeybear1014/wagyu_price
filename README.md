# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？

リモートリポジトリ:ネット上に配置して複数人で共有するためのリポジトリ

ローカルリポジトリ:開発者一人ひとりが使用するために自分のPC上に配置するためのリポジトリ

リポジトリ:ファイルやディレクトリの状態を保存する場所

## プッシュとマージの違いは何でしょうか？

変更箇所を反映させる場所が違う

プッシュ:ローカルリポジトリの変更内容をリモートリポジトリに反映する

マージ:別のブランチの作業内容をブランチに取り込むこと

## コミットとプッシュの違い

変更を反映させるリポジトリが違う

コミット:ローカルリポジトリに変更を反映

プッシュ:リモートリポジトリに変更を反映

## コミットのメッセージはどのように書いてあげるのが最適でしょうか？

編集した内容をより正確に表すようなメッセージを記載する。
変更を加えたファイル名や変更を加えたコードを詳細に記載。
例:〇〇ファイルにある△△機能の✕✕を変更。

## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？

マージとプッシュをどこで行うかが異なる

プルリクエスト:リモート上の作業ブランチにプッシュしてからマージ依頼をして別の担当者がmasterブランチにマージを行う

ローカル:ローカルリポジトリでmasterブランチにマージをしてリモートリポジトリにプッシュする

## コンフリクトを起こしてしまった場合、どう対処すべきですか？

状況に応じて3通りの方法で変更を取り込む。

1．先にマージされた変更内容を取り込む
2．後にマージしようとしている変更内容を取り込む
3．どちらの変更内容も取り込む

3．の方法をとる場合はエディタ上で両方の変更内容を取り込んだ処理で上書きして取り込む必要がある。