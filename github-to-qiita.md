# GitHubとQiitaに同時投稿する

## 何をしたいのか
- GitHubをノートのように使いたい
  - 出先から自分のコードを使ったり、
  - 変更があったときに差分を取っておきたい
- せっかくなので、MDで書いて、Qiitaにも投稿しておきたい
- 将来的には拡張して、個人ブログにも連携させたい

## どうやるのか
- それがわからない。
  - 先人の知恵をお借りすると、[PushするタイミングでQiitaへ連携する](https://www.inoue-kobo.com/restapi/qiita_posting/index.html)コードが生産済みとのこと    
  - 機能は完璧、環境もローカルのGitのみと申し分ない
  - PWを埋め込むので、Private Repositoryとして作成する


## 2020/11/03 やってみた
- Windows機を使用しているため、各種パスを若干変更
- PythonはAnaconda3を入れていた、PerlはActivePerlさんを入れた
- フォルダ関連を調整していないため、どう考えても動かないが、どういう流れで動くのかを理解するため、一度実行する
- error: failed to push some refs to 'https://github.com/jun-g-0/notes.git'
- 歯が立たないくらい汎用なエラー…おとなしくpre-pushファイルする。何ヶ月か数年後にまた戻ってこよう。
