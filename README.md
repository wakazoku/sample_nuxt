# ▼当リポジトリについて
学習のため、Nuxt.jsビギナーズガイドの作例を載せてます。  
https://www.amazon.co.jp/dp/B07J5434JB/ref=dp-kindle-redirect?_encoding=UTF8&btkr=1


# ▼環境構築

## ・環境変数の登録
QiitaのAPIが必要なので事前に取得しておく。  
トークンを環境変数に設定する。
```
export QIITA_TOKEN=xxxxxxx
```

## ・起動
```
npm run dev
```

ローカル環境  
http://127.0.0.1:3333/  

QiitaでNuxt.jsタグがつけられた記事を表示する  
http://127.0.0.1:3333/users