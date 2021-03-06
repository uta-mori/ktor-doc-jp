開発時のルール等についてまとめています。

## PullRequestルール ✅

* 修正対象: 基本的にどんなものでも大丈夫です
  * 英語になっているページの翻訳
  * わかりにくい文章・翻訳を改善（ **元の翻訳は一切気にせずよりわかりやすいと思う訳をご提案ください**）
  * typoの修正
  * [元ドキュメント](https://ktor.io)の修正への追従（後述の`反映済みコミット`の章を参照）
* ルール: 特にありません
  * タイトル・説明・コミットメッセージ等は日本語で作成していただいて大丈夫です。記法に指定はありません。
* 方針
  * 原文を直訳するよりも、多少情報が落ちる・変更されるとしても意訳して読みやすくしたほうがいいと思っています。

## 開発方法 💻

※ `jekyll` がインストールされている必要があります（[公式のインストールガイド](http://jekyllrb-ja.github.io/docs/installation/)）
※ `jekyll-redirect-from`, `jekyll-feed`, `jekyll-sitemap` のgemがインストールされていないとエラーになります（例えば`gem install --user-install bundler jekyll-redirect-from`といったコマンドでインストールしてください）

`./develop.sh` を実行後 `localhost:4000` で修正中のドキュメントが閲覧できます。

## 反映済みコミット

元ドキュメントの以下コミットまでは反映完了しています。
元ドキュメントの修正への追従を行う際には、このコミット以降のコミットを反映します。
https://github.com/ktorio/ktorio.github.io/commit/f5ea8d6c5b6feadbab135b49ca72b9208414327c

※ 差分は以下のURLのようにすれば閲覧することが可能です
https://github.com/ktorio/ktorio.github.io/compare/f5ea8d6c5b6feadbab135b49ca72b9208414327c...master
