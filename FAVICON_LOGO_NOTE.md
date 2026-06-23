# SVGロゴ・favicon反映内容

変更内容:
- 添付SVGを `images/logo-sasaki.svg` として追加
- メニュー内の `images/logo-sasaki.webp` 参照を `images/logo-sasaki.svg` に変更
- ルート直下に `favicon.svg` を追加
- 検索結果・ブラウザ互換性を考慮して、以下も生成
  - favicon.ico
  - favicon-48x48.png
  - favicon-96x96.png
  - favicon-192x192.png
  - favicon-512x512.png
  - apple-touch-icon.png
- head内のfavicon指定をルート直下ファイル参照に変更
- og:site_name と WebSite 構造化データを追加

注意:
Google検索結果のfaviconやサイト名表示は、アップロード後すぐには反映されません。
Search ConsoleでURL検査から再インデックス登録をリクエストしてください。
