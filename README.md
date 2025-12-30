# Bright Data Web Unlocker Pythonプロジェクト

[![Bright Data Promo](https://github.com/bright-jp/LinkedIn-Scraper/raw/main/Proxies%20and%20scrapers%20GitHub%20bonus%20banner.png)](https://brightdata.jp/)

<a href="https://githubbox.com/bright-jp/bright-data-web-unlocker-python-project?file=index.py" target="_blank">CodeSandboxで開く</a>をクリックし、GitHubでサインインしてから、リポジトリをフォークして変更を開始してください。

## Bright Data Web Unlocker APIの例

このプロジェクトでは、[Bright DataのWeb Unlocker API](https://brightdata.jp/products/web-unlocker) を使用して、[Bright Data Web Unlocker API](https://brightdata.jp/products/web-unlocker) 経由でWebサイトにアクセスする方法を示します。

## 概要

このスクリプトは、Bright DataのWeb Unlockerを使用してアンチボット保護やCAPTCHAを自動的に回避することで、Webサイトへのアクセスを支援します。

### 直接設定

1. `BRIGHT_DATA_API_TOKEN` を実際のAPIトークンに置き換えてください
2. `web_unlocker1` をご自身のzoneに置き換えてください
3. `https://geo.brdtest.com/welcome.txt` をターゲットURLに置き換えてください

## 例の実行

1. `API token` と `zone` が設定されていることを確認してください
2. ターミナルで `python index.py` を実行してください
3. 結果についてコンソール出力を確認してください

## どのように動作しますか？

1. スクリプトがBright DataのUnlocker APIエンドポイントにPOSTリクエストを送信します
2. 認証トークンとターゲットURLが含まれます
3. Bright DataのWeb UnlockerがターゲットURLにアクセスします
4. レスポンスがスクリプトに返され、コンソールに表示されます

## トラブルシューティング

エラーが発生した場合:

- APIトークンが正しいことを確認してください
- zone名が有効であることを確認してください
- ターゲットURLが正しい形式になっていることを確認してください

## 例の変更

別のURLをリクエストするには:
1. CONFIGオブジェクト内の `targetUrl` を更新してください
2. スクリプトを再実行してください

## 追加リソース

- [Bright Data Web Unlocker API](https://docs.brightdata.com/scraping-automation/web-unlocker/introduction)
- [API Tokenを取得する](https://docs.brightdata.com/general/account/api-token)
- [Zonesを管理する](https://brightdata.jp/cp/zones)

**注:** これは学習目的のサンプル実装です。本番環境で使用する場合は、追加のエラーハンドリング、ログ記録、セキュリティ対策の追加をご検討ください。