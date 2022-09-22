# Atcoder Python Environment
## Dockerの操作 
コンテナの作成
```
docker-compose build
```

コンテナの起動
```
docker-compose up -d
```

コンテナの中に移動
```
docker-compose exec py-ana /bin/bash
```

コンテナの終了
```
docker-compose down
```

## Pythonの操作
コンテナの中に移動したあとは通常通りPythonコマンドが利用可能