# mizukara-event-lp

ミズカラのイベントLPを GitHub Pages で公開するためのリポジトリです。

## 公開URL

`https://mizukara-corp.github.io/mizukara-event-lp/<フォルダ名>/`

`main` ブランチに入れると、数分で上のURLに反映されます。

## LPの追加のしかた

1. イベントごとにフォルダを作る（例: `2026-11-coaching-seminar/`）
2. フォルダの中に `index.html` を置く。画像などはそのフォルダの中にまとめる
3. `main` に入れる → `https://mizukara-corp.github.io/mizukara-event-lp/2026-11-coaching-seminar/` で公開される

Claude Code に頼むときは「mizukara-event-lp に `<フォルダ名>` で LP を追加して公開して」と伝えればOKです。

## 注意（このリポジトリは誰でも見られます）

- リポジトリもページも **全世界に公開** されています。URLを知らない人でも見つけられます
- 受講生・お客様の個人情報、パスワード、APIキー、社内の資料は **絶対に置かない**
- 限定公開したいもの（パスワード付き・社内限定）は html-publisher を使ってください
