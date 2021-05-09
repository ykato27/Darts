# AutoML-Darts
* AutoML-Dartsを活用した時系列解析のプログラム

## リポジトリ構成
```
.
├── README.md                 READMEファイル
├── .dockerignore        
├── Dockerfile                Dockerファイル
├── docker-compose.yml
├── notebook                  jupyter notebook
└── data                      dataファイル
```

## 環境構築

* Dockderfileがあるホスト側のフォルダへ移動（例：Desktop/AutoML-Darts）
```
cd Desktop/AutoML-Darts
```

* Dockerによる環境構築（フォルダをマウント：Desktop/AutoML-Darts）
```
docker-compose up --build
```

* ブラウザーを立ち上げてlocalhost:8888へアクセス
* ローカルフォルダがマウントされている

## jupyter notebook説明
* Time-Series-Forecasting-Darts.ipynb : 時系列解析(Darts)のnotebook

## 動作環境
マシンスペック（Mac)
- MacBook Air (Retina, 13-inch, 2018)
- 1.6 GHz デュアルコアIntel Core i5
- 8 GB 2133 MHz LPDDR3
