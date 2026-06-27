# つくる手帖 くまさん叩き in 秋田市市街地 かくれ場所版

PWA対応のスマホゲームです。
クマが木の後ろ、植え込み、石の陰、下水路、排水溝から出てきます。

## ファイル構成

- index.html
- manifest.webmanifest
- sw.js
- icon-192.png
- icon-512.png
- icon-maskable-512.png
- apple-touch-icon.png

## 設置方法

例：つくる手帖リポジトリ内に `kuma-hide/` フォルダを作り、この中身をアップロードします。

公開URL例：

https://tad551216-rgb.github.io/tsukuru-techo/kuma-hide/

## 注意

更新時は `sw.js` の `CACHE='tt-kuma-hide-v2'` を v2, v3 と上げてください。
古いPWAキャッシュ対策です。

## 戻るリンク

ゲーム内の「つくる手帖へ戻る」は以下へ固定しています。

https://tad551216-rgb.github.io/tsukuru-techo/


## v2 修正

ゲーム終了直後の誤タップ防止として、「もう一度遊ぶ」と「つくる手帖へ戻る」の両方を1.2秒間押せないようにしました。
