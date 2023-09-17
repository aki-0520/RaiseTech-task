# RaiseTech-task

## RaiseTech の課題作成

- github には以前から登録していたがパスワードで管理していた時代だったので個人アクセストークンを作成していなかった。

- 個人アクセストークン（PAT）は github API またはコマンドラインを使用するときに github への認証でパスワードの代わりとなることを学んだ。

- cloud9 のターミナルからの作成ではなく vscode と GitHubDesktop で作成したため、今後ターミナルからの作成にも慣れる必要がある

## ブランチに関する疑問点

- 複数名でブランチを切った場合、1 人目がマージした後に、別の人がマージすると上書きされてしまうのでは、と思ったが、この状態では「競合」状態となり、マージが出来ない。

- 誰かがマージした後に、他の人がマージする場合は、pull してローカルリポジトリに最新情報を取り込むことで競合状態が解消され、マージができるようになる。という仕組みを理解した。
