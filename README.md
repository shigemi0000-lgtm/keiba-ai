# 競馬AIガイド PWA

iPhoneで毎日使える競馬AIレコメンドアプリです。

## GitHub Pagesで無料公開する手順

### 1. GitHubアカウント作成（無料）
https://github.com にアクセスしてアカウントを作成

### 2. 新しいリポジトリを作成
- 右上の「+」→「New repository」
- Repository name: `keiba-ai` (任意)
- Public を選択
- 「Create repository」をクリック

### 3. ファイルをアップロード
- 「uploading an existing file」をクリック
- 以下の3ファイルをドラッグ&ドロップ:
  - index.html
  - manifest.json
  - sw.js
- 「Commit changes」をクリック

### 4. GitHub Pagesを有効化
- リポジトリの「Settings」タブ
- 左メニューの「Pages」
- Source: 「Deploy from a branch」
- Branch: 「main」/ 「/(root)」を選択
- 「Save」

### 5. URLが発行される（約1〜2分後）
`https://[あなたのGitHubユーザー名].github.io/keiba-ai/`

## iPhoneのホーム画面に追加する方法

1. iPhoneのSafariでURLを開く
2. 下の共有ボタン（四角に矢印）をタップ
3. 「ホーム画面に追加」をタップ
4. 「追加」をタップ

→ ホーム画面にアイコンが追加され、アプリのように使えます！

## 使い方

### 今日タブ
- 今日の開催場をタップして選択
- 自動的に推奨セグメントを表示

### 会場別タブ
- 中央/地方を切り替え
- 会場を選んで全セグメントを確認
- 帯広は曜日切り替え可能

### 照合タブ
- JRAアプリで確認したレースの距離を入力
- 「照合する」でどのレースが推奨か即判定

## 更新方法
AIデータが更新されたら、新しいindex.htmlをGitHubにアップロードし直すだけ

---
Made with Claude AI
