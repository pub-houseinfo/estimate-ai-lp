# estimate-ai-lp — 見積AIエージェント講座 LP

株式会社ハウスインフォ／IT032-AI研修事業。30分無料相談の申込獲得LP（静的HTML・1ページ）。

- 正本（版管理・設計書）：GDrive `IT032-AI研修事業/見積AIエージェント/LP/`（`index_v2_GSAP.html` → ここでは `index.html`）
- 設計書：同フォルダ `README_LP設計書.md`
- フォーム受け口：Apps Script（`claude-code/gas/見積AIエージェントLP_フォーム送信/`）。`index.html` の `data-endpoint`
- 公開先：Netlify（予定）。`netlify.toml` はヘッダー指定のみ

## 更新のしかた
1. GDrive 側で `index_vN_○○.html` として新版を作る（過去版は残す）
2. `index.html` にコピーし、`thanks_v1_初版.html` → `thanks.html` の参照を直す
3. コミット → push（Netlify が自動で公開）
