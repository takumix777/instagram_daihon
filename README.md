# WOODY HOUSE Reel Script Builder v8

住宅会社のInstagramリール台本制作を「半自動化」することだけに絞った静的Webアプリです。

## 使っているデータ
- WOODY HOUSE公式HP由来のKnowledge DB
- 添付された社内Q&A資料
- `LIFEアカウント.xlsx` の既存台本12本
- 同Excelの「修正案」にある編集フィードバック

## 考え方
- 過去台本 = HOW（伝え方・CUT・テンポ・撮影素材）
- Q&A / 公式HP = WHAT（会社固有の事実）
- 古い台本の金額・制度を現在の事実として流用しない
- 数値、保証、補助金、価格、施工エリア等は要確認表示

## 使い方
1. テーマと必須内容を入力
2. 「参考情報を自動選択」
3. 必要なら会社情報・過去台本のチェックを変更
4. 「台本を作成」
5. 人間が確認・修正して完成
6. さらに品質を上げる場合は「AIで仕上げる」のプロンプトをChatGPT / Claudeへ貼る

## GitHub Pages
リポジトリ直下に `index.html` を置き、
Settings → Pages → Deploy from a branch → `main` / `(root)` → Save。

## 注意
この版は学習・投稿分析・自動企画提案を目的にしていません。
「既存情報を使って台本のたたき台を速く作る」ことに特化しています。
公開GitHub Pagesに置く場合、社外秘情報がKnowledge DBに含まれていないか確認してください。
