# git-hub

現在のリポジトリのPRを一覧し、絞り込みを行ってチェックアウトするgitサブコマンドです。
this command shows your repo prs and checkout you selected.

https://github.com/fruitriin/git-hub/assets/18308639/0207c7ad-9e63-4dc4-9ced-e598d6dbc0b2

## 使い方/How to Use
```
git hub
```


## インストール/Instalation
NPM: https://www.npmjs.com/package/git-sc-hub

```
npm install -g  git-sc-hub
```

# 必要なもの/Requiments
- bat - show coloful preview
   - カラフルなcatでプレビュー見るのに使ってます
- fzf - awesome fuzzy finder
   - 絞り込み機能とかプレビュー機能とかはこいつ
- gh - get prs and pull
   - PRの取得とPullはこいつをつかいます
- sed (may be GNU sed not work currently)
   -  Macで作ったのでGNU Sedだと動かないかも

# 補足とか/More Detail

- 色がおかしいなーとかあったら、BATのテーマ設定がうまくできてないです
  -  [BAT 日本語説明書](https://github.com/sharkdp/bat/blob/master/doc/README-ja.md)
- if your preview broken color, you shuld set bat theme
    - [BAT English README.md](https://github.com/sharkdp/bat/blob/master/doc/README.md)https://github.com/shar

- プレビューでは１行コメントアウトは除外するようにしてます
  - preview strip <!-- --> comment if its in a line.

