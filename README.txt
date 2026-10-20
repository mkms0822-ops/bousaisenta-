【アップロードするもの】(同じ場所に、上書き・追加)
  index.html          … 本体サイト(メニューに「個人情報が漏れたら」を追加)
  Manual.html         … 緊急対応マニュアル(内容はそのまま。ガイドへのリンクだけ変更)
  leak-guide/         … 個人情報が漏れたら 対処ガイド(フォルダごと)
      index.html, leak-hero.jpg, data/, img/

【メニューの場所】 ☰ → 各種ツール → 🔐 個人情報が漏れたら
【緊急対応マニュアルのリンク】 サイバー攻撃・情報漏洩 → 個人情報漏洩 → 「対応ガイド（個人情報が漏れたら）を開く」
【削除したもの】 ガイド単体のインストール機能(manifest・Service Worker・アイコン)
  ※ 旧ガイドの manifest.webmanifest / sw.js / icon-192.png / icon-512.png は、アップロード不要です
【キャッシュ】 本体の sw.js が古い index.html を返す場合は、sw.js の CACHE_NAME の版を上げてください
