## 課題名
ベンターマネジメントシステム。

## どんなシステム
エンジニアのパフォーマンス、育成などをマネジメントするシステム。

##　ログインID.PW
tokio
Loop123456

## ディレクトリ構成（主要）

## 今後の課題
データベースの再設計、構築
CSRF対策
管理画面の拡張
学習コンテンツのデータ投入
指摘事項のデータ投入

```
LOOP/
├── index.html                     # ログイン画面
├── neorisloop.html                # Loopメイン画面
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
├── test_db_connection.php         # DB接続テスト

