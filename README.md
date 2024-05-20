# 机上の九龍

## サービス概要

机上の九龍は小説執筆アプリです。

## サービスコンセプト

### 背景

**455,2821**  
これは私が投稿サイトに投稿した小説の総文字数です。

**1,890,985**  
これは私がこれまで書いてきた小説・プロットの総文字数です。

上記の数字から分かる通り、私は小説を書くのが好きです。とくに二次創作を書くのが大好きです。  
上記の数字はどちらも二次創作における文字数です。  
これまで様々な執筆サービスやツールを触ってきました。多機能すぎて使いづらいもの、昨日が少なすぎて足りないもの、ちょうどよいが UI が自分好みじゃないもの、などなど…。  
これまでの経験から「自分が一生使う執筆アプリを作りたい」と考え今回の小説執筆アプリ「机上の九龍」を作成いたします。  
当アプリは完全自己満足ながらに、「数ある執筆アプリの選択肢の１つ」となるようなユニークな内容を目指します。

### 想定されるユーザー層

- 小説を執筆している人
- とくに二次創作を執筆している人
- いろんな執筆アプリを触ってみたい人

## 実装を想定している機能

### MVP

- ユーザー登録
  - メール・パスワード
  - Google ログイン
  - ゲストログイン
- アカウント設定
  - ユーザー名
  - メールアドレス変更
  - パスワード変更
- 小説
  - 一覧
  - 執筆
  - 保存
  - 削除
- プロット
  - 一覧
  - 執筆
  - 保存
  - 削除
- 設定集
  - 一覧
  - 執筆
  - 保存
  - 削除
- 文字数カウンター
- X シェア機能
  - 今日の執筆文字数など
- レスポンシブ

### 本リリース

- プロット
  - 時系列モード
  - リストモード
  - 付箋モード
- 設定集
  - 世界観
  - 人物別
- プレビューモード
  - マークダウン
  - HTML テンプレート
- アウトライン
- ちょこっと共有
  - パスワード認証で閲覧のみ可能

### 追加実装予定

- 配色カスタマイズ
- 投稿サイト向けテキスト出力
- PDF 出力
- HTML/php 出力

## 技術スタック

以下予定している技術スタックです
| カテゴリー | 技術スタック |
| :-- | :-- |
| Frontend | Next.js14, TypeScript |
| Backend | Ruby on Rails7 |
| Infrastructure | AWS |
| Database | |
| Monitoring | Sentry |
| Environment | Docker |
| CSS/UI Component | tailwind CSS, shadcn/ui |
| Frontend package | Recoil, ESLint, Axios |
| Backend gem | DeviseTokenAuth, OmniAuth, rubocop, JSon API Serializer |
