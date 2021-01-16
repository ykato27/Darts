# Darts
* Dartsを活用した時系列解析のプログラム

## リポジトリ構成
```
.
├── README.md                 READMEファイル
├── Dockerfile                Dockerファイル
├── notebook                  jupyter notebook
└── data                      dataファイル
```

## 環境構築
Dockderfileがあるホスト側のフォルダへ移動（例：Desktop/Darts）
```
cd Desktop/Darts
```
Dockerによる環境構築
```
docker build .
```
docker run実行（対象フォルダをマウントする／例：Desktop/Darts）
```
docker run -p 8888:8888 -v ~/Desktop/Darts/:/work --name Darts <docker image>
```
ブラウザーを立ち上げてlocalhost:8888へアクセス
workフォルダ内が対象フォルダにマウントされている

## jupyter notebook説明
* Darts.ipynb : 時系列解析(Darts)のnotebook

## 動作環境
マシンスペック（Mac)
- MacBook Air (Retina, 13-inch, 2018)
- 1.6 GHz デュアルコアIntel Core i5
- 8 GB 2133 MHz LPDDR3