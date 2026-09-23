# AP JOURNAL — ブランドメディア提案デモ

## 開く

`dist/index.html` をブラウザで開くか、`dist` を静的Webサーバーで配信します。ビルド・依存パッケージのインストールは不要です。

日本語書体は Zen Kaku Gothic New、英字は Barlow Condensed。Google Fontsの読み込みにはインターネット接続が必要です。写真はすべて同梱しています。

## 体験

- TOP：大きな文字と写真、スクロール連動の3場面、ブランド切り替え。
- STORY：6記事、5つの編集テーマ。
- BRAND：塚田農場・四十八漁場・焼鳥つかだの探索と詳細。
- FOOD、宮崎・海のORIGINS、架空人物のPEOPLE、OB・OG企画サンプル。
- ブランド診断：3問、3つの結果。やり直し・前の質問に対応。
- 公式の店舗検索・採用・問い合わせへのリンク。

## 商談でたどる順番

1. TOP → 特集記事 → 料理 → 産地 → ブランド → 店舗検索。
2. TOP → ブランド診断 → 結果 → ブランド → 料理・STORY・PEOPLE → 店舗検索。

## 動き

写真の拡大、見出しの出現、流れる英字、スクロール中に固定される写真ステージ、3場面の切り替え、ブランド画像の横方向の切り替え。スクロール操作自体は通常のブラウザ動作です。OSで動きを減らす設定が有効な場合は、演出を止め、場面切り替えはボタンで行えます。

## 検証

36画面の出力、内部リンク、9点の画像参照を確認。診断の全27通りと不正入力の拒否を確認。ブラウザで主要な回遊、診断、場面切り替え、ブランド切り替え、スマホメニューを確認。WebMCPの診断ツールも正常入力・不正入力・画面反映を確認しました。

## 情報と権利

この名称・記事・編集コピーは提案用で、公式メディアではありません。実在ブランド・企業思想・写真の出典はサイト内の「出典・デモについて」にまとめています。公式写真のオープンライセンスは確認できていません。非公開の商談用とし、一般公開・本番利用時には使用許諾の確認または差し替えが必要です。

高橋直人・森由佳は架空です。発言・経歴はデモ用の創作です。高橋直人の顔写真のみAI生成です。予約API、CMS、応募受付、実在社員データベースは含みません。

## 生成画像

保存先：`dist/assets/fictional-chef.png`。built-in image_genで1点生成。

使用プロンプト：

```text
Use case: photorealistic-natural
Asset type: Original editorial portrait for a fictional PEOPLE article in a private restaurant brand media demo.
Primary request: Generate exactly one original photograph of an entirely fictional Japanese male chef, about 32 years old, standing in a warmly lit Japanese restaurant kitchen.
Subject: Relaxed candid half-length portrait, white chef jacket and dark indigo apron, natural expression.
Style/medium: Natural textured analog documentary photography, realistic skin texture.
Composition/framing: Vertical 4:5 composition.
Lighting/mood: Warm restaurant lighting, warm natural skin tones.
Color palette: Olive and charcoal kitchen background.
Constraints: Entirely invented person; do not imitate any actual employee or real person. No logos, no text, no watermark.
```
