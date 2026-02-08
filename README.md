## 課題名
ベンターマネジメントシステム。

## どんなシステム
エンジニアのパフォーマンス、育成などをマネジメントするシステム。

##　ログインID.PW
tokio
Loop123456

## ディレクトリ構成（主要）

```
LOOP/
├── index.html                     # ログイン画面（api/login.php を呼ぶ）
├── neorisloop.html                # メイン画面（AMS/VMS/LMS）
├── js/
│   └── api.js                     # API呼び出しユーティリティ（fetch + session）
├── api/
│   ├── login.php                  # ログイン
│   ├── logout.php                 # ログアウト
│   ├── check_session.php          # セッション確認
│   ├── ams.php                    # AMS API（案件/マッチング）
│   ├── vms.php                    # VMS API（フィードバック/チャット）
│   ├── lms.php                    # LMS API（学習/通知）
│   └── engineers.php              # エンジニアAPI
├── config.php                     # DB接続/JSONレスポンス/セッション設定
├── config.secrets.php             # 本番用の機密設定（本番だけに配置推奨）
├── config.secrets.example.php     # 機密設定の雛形
├── database.sql                   # DB初期化（テーブル+サンプルデータ）
├── deploy_sakura.php              # 本番デプロイ確認（DB/テーブル/ユーザー）
├── test_db_connection.php         # DB接続テスト
