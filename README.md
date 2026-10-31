# 学習計画アプリ

## GitHub Pages で公開する手順
1. GitHub で新しいリポジトリを作成（例：gakushu-keikaku、Public）
2. このフォルダ内のファイルをすべてアップロード（index.html / manifest.json / sw.js / icon-*.png）
3. Settings → Pages → Branch を main / (root) にして Save
4. 数分後、https://ユーザー名.github.io/gakushu-keikaku/ で開けます
5. iPhone の Safari で開き、共有ボタン →「ホーム画面に追加」

## 更新するとき
sw.js の先頭 `const C='gakushu-v3'` の数字を上げてからアップロードすると、新しい内容に切り替わります。
