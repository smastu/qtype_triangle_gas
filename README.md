# 三角ロジック（GAS 版）の配信用ファイル

このリポジトリは、三角ロジック（Moodle 問題タイプ `qtype_triangle` の移植）の画面だけを置く配信用です。
GitHub Pages で配信します。

- 学習者用：`index.html`（Google でログインして問題を解く）
- 教員用：`teacher.html`（課題の作成・検査、ログの CSV 書き出し）

ログの受け取りと名簿・課題の保存は、Google Apps Script のウェブアプリ（別に管理）が行います。
この画面が呼ぶ先（endpoint）は `index.html` と `teacher.html` の中の設定に入ります。

判定エンジン・課題データ・画面の正本は、配信元の `gas/` フォルダにあります（ここは生成物だけです）。
