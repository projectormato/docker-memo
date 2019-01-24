# Dockerメモ
Dockerでドカドカするメモ  
[Docker Hub](https://hub.docker.com/)はこちら。公式のimageがここで探せる。

## コマンド

### image操作のコマンド
* pull：Dockerイメージをレジストリから取得
* ls：Dockerイメージの一覧を表示
* inspect：Dockerイメージの詳細を表示
* tag：Dockerイメージにタグをつける
* push：Dockerイメージをレジストリへアップロード
* rm：Dockerイメージの削除
* save：Dockerイメージをtarファイルに保存
* load：saveで固めたtarからDockerイメージを作成
* import：exportで固めたtarファイルからDockerイメージを作成

### container操作のコマンド
* ls：コンテナの一覧を表示
* run：Dockerイメージからコンテナを生成
* stats：コンテナのリソース使用状況を表示
* logs：コンテナ内の実行ログ確認
* create：Dockerイメージからコンテナの生成
* start：コンテナの起動
* stop：コンテナの停止
* restart：コンテナの再起動
* pause：コンテナの一時停止
* unpause：一時停止中コンテナの起動
* rm：停止中コンテナの削除
* attach：稼働中コンテナに接続
* exec：稼働中コンテナに接続
* top：稼働中コンテナ内のプロセス一覧表示
* port：コンテナの公開ポート番号表示
* rename：コンテナの名前変更
* cp：コンテナとホストOS間でファイルとディレクトリのコピー
* diff：Dockerイメージが生成されてからの変更情報を表示
* commit：変更があったコンテナからイメージを作成
* export：コンテナをtarファイルに保存

その他
* version：Dockerのバージョンを表示
* info：Dockerの実行環境情報を表示
* search：Docekrイメージの検索
* login：Docker Hubへログイン
* logout：Docker Hubからログアウト
