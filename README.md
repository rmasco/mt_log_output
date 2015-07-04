# mt_logをファイル出力するためのプラグイン

プラグイン開発などを行っているとログに出力してデバッグするという場面も多く出てきます。
ソース書いてツール＞ログの画面を更新して、、、
ログが大量に出た場合なんかは画面も非常に見づらくなってしまいます。

そこで、mtのログに出力された内容をファイル出力することで、
そのファイルをtailやlessで簡単におうことができます。

## インストール

MTLoggerフォルダをMTのpluginsフォルダにアップロードしてください。
初期ではmt-static/logs/以下にログファイルを出力します。
ファイルを書き出すディレクトリを変更したい場合には、下記環境変数をmt-config.cgiに追記してください。

`LoggerFilePath /var/log/`

