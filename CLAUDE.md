# ArchiPrep 2級 — 二級建築士学科試験対策アプリ

## プロジェクト構成
- `structure.html` — 学科III 建築構造（テンプレート見本・変更禁止）
- `planning.html` — 学科I 建築計画
- `regulations.html` — 学科II 建築法規
- `construction.html` — 学科IV 建築施工
- `index.html` — 科目選択メニュー
- `data/*.json` — 各科目の問題データ

## 重要ルール
- structure.html は見本として保持。編集禁止
- 問題の正確性が最優先。不確実な問題は作らない
- 法規問題の tip には条文番号を含める
- 1ファイル完結（CDN以外の外部依存なし）
- JSON形式: {id, cat, sub, diff, isNew, q, ch[], ans, ex, tip}
- 仕様書の choices オブジェクト形式ではなく、見本のシンプル配列形式を採用

## カラースキーム
- 計画: #2563EB（青）
- 法規: #059669（緑）
- 構造: #D97706（橙）
- 施工: #7C3AED（紫）
