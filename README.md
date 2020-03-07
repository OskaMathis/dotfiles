# dotfiles

## 基本方針
- メンテコストがかかるのでスクリプトによる自動化は最低限に留める
- 同様の理由で Mac OS 以外での環境構築は考えないものとする
- テキストベースで管理できないGUIアプリの設定等に関しては環境構築のたびにメモを更新していく


## セットアップ手順
`setup.sh` を実行すると下記順序でセットアップされる
1. 各種設定ファイルのシンボリックリンクをホームディレクトリ直下に作成
2. Homebrewをインストール
3. `brew bundle` でパッケージを一括インストール
4. ログインシェルを変更
5. systemのRubyにcolorlsをインストール