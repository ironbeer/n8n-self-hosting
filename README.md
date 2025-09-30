# n8n-self-hosting

## 使い方

.env.sampleをコピー。
```shell
cp .env.sample .env
```

以下の環境変数をランダム文字列に書き換える。おすすめコマンド：`curl -L pw.vdx.sh/s/16`
- DB_POSTGRESDB_PASSWORD
- N8N_ENCRYPTION_KEY
- N8N_RUNNERS_AUTH_TOKEN

起動。
```shell
docker-compose up -d
```

[http://localhost:5678/](http://localhost:5678/)を開いてオーナーアカウントの設定を済ませたら完了。
