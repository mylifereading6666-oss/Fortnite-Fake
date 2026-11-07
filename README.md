# Fortnite Fake — 3D建築練習

Fortniteのモバイル版の操作感を参考にした、オリジナルの3D建築練習サイトです。Fortnite本体とは独立した練習用シミュレーターです。

## 起動

GitHub Pagesで公開する場合：
1. GitHubのリポジトリ設定（Settings）を開く。
2. Pages → Build and deployment で `Deploy from a branch` を選択。
3. Branchを `main`、フォルダーを `/ (root)` にして保存。
4. 公開されたPages URLからアクセスする。

`index.html` をブラウザーで開いても利用できますが、Three.jsをCDNから読み込むためインターネット接続が必要です。

## 操作

### PC
- WASD / 矢印キー：移動
- マウス：視点変更
- 左クリック：建築を配置
- Space：建築を配置
- R：建築パーツを回転

### スマートフォン・タブレット
- 左下のスティック：移動
- 画面ドラッグ：視点変更
- 建築ボタン：選択中の建築を配置

## 建築パーツ

- 壁
- 床
- 階段
- 屋根

「削除」で最後に置いた建築を削除し、「リセット」で建築物をすべて消去できます。

## 技術

- HTML / CSS / JavaScript
- Three.js（CDN）
- サーバー・データベース不要

## 注意

本サイトは非公式のファン制作練習プロジェクトです。Epic Games / Fortniteとは関係ありません。Fortniteの公式ロゴやゲーム内素材は使用していません。