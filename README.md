# 千葉工業大学二輪部 公式HP

GitHub Pages で公開できる静的サイトです。ビルド工程・外部JavaScriptライブラリは不要です。

## 公開方法
1. このフォルダ内の `index.html`、`images/`、`README.md` を GitHub リポジトリのルートへアップロードします。
2. GitHub の **Settings → Pages** を開きます。
3. **Deploy from a branch** を選び、公開したいブランチ（通常は `main`）と `/ (root)` を指定して保存します。
4. 表示された GitHub Pages URL で確認します。

## 写真
画像はすべて `images/` 内のローカルファイルを参照しているため、Unsplash 等の外部画像サービスに依存しません。画像を差し替える場合は同じファイル名で置き換えるか、`index.html` の `images/ファイル名` を変更してください。

- `gallery-01.jpg` — ヒーロー背景、ギャラリー
- `field-mountain.jpg` — FIELD / FOREST
- `field-rock.jpg` — FIELD / ROCK
- `field-mud.jpg` — FIELD / MUD
- `activity-ride.jpg` — 走行アクティビティ
- `machine-01.jpg` — 車両・マシン
- `activity-crew.jpg` — 部員・チーム
- `gallery-02.jpg`〜`gallery-05.jpg` — ギャラリー用

## 公開前に確認すること
- `club@example.com` は仮のメールアドレスです。公式連絡先に変更してください。
- 写真の内容から確定できない排気量・エンジン形式・競技実績・部員数は断定しないでください。
- 写真に写る人の公開許可、大学名・ロゴ等の使用ルールを確認してください。

## 実装
レスポンシブレイアウト、スクロール演出、ハンバーガーメニュー、フィールドフィルターとリセット、横スクロールギャラリー、写真ライトボックス、RIDE STYLE FINDER、キーボード操作、`prefers-reduced-motion` に対応しています。
