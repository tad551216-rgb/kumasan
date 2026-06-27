# つくる手帖 くまさん叩き in 秋田市

スマホで遊べる PWA 形式のミニゲームです。
秋田市市街地をイメージした背景で、穴から出てくるくまさんをタッチして得点します。

## 内容

- `index.html` ゲーム本体
- `manifest.webmanifest` PWA設定
- `sw.js` オフライン用サービスワーカー
- `icon-192.png`
- `icon-512.png`
- `icon-maskable-512.png`
- `apple-touch-icon.png`

## 公開方法

GitHub Pages で公開する場合は、任意のフォルダ、例：

```text
kuma-tap/
```

にこの一式を入れてください。

公開URL例：

```text
https://ユーザー名.github.io/tsukuru-techo/kuma-tap/
```

## トップページからのリンク例

```html
<a href="./kuma-tap/">くまさん叩きで遊ぶ</a>
```

## 更新時の注意

`sw.js` のキャッシュ名を変更してください。

```js
const CACHE='tt-kuma-tap-v2';
```

これをしないと、古いゲーム画面が表示され続けることがあります。
