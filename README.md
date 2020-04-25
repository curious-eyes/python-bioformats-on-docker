# python-bioformats 動作確認環境

## Install Docker

Docker, Docker Compose をインストールしてください。

https://docs.docker.com/get-docker/

https://docs.docker.com/compose/install/


## Build and Run Your Docker Container

```
docker-compose build
docker-compose up -d
docker-compose exec bio bash
```

## 動作確認

サンプル画像の縦横サイズを出力します。

```
python3 demo.py ../tests/resources/Channel1-01-A-01.tif
```
