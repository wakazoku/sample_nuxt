# ▼当リポジトリについて
学習のため、Nuxt.jsビギナーズガイドの作例を載せてます。  
https://www.amazon.co.jp/dp/B07J5434JB/ref=dp-kindle-redirect?_encoding=UTF8&btkr=1


# ▼環境構築
## ・envファイルを作る
`.env.example`を`.env`に書き換える。

## ・APIトークンの登録
QiitaのAPIが必要なので事前に取得しておく。  
.envファイルに以下の行を追加する。
```
QIITA_TOKEN=xxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
```

## ・起動
```
npm run dev
```

ローカル環境  
http://127.0.0.1:3333/  

QiitaでNuxt.jsタグがつけられた記事を表示する  
http://127.0.0.1:3333/users