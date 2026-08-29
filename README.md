# Evergreen Lesson8

Evergreen English Grammar 47 Lessons / Lesson 8「助動詞（1）」の授業用クリック型HTML教材。

## 公開方法（GitHub Pages）
このリポジトリは、そのまま GitHub Pages で公開できる構成です。

1. Settings → Pages を開く。
2. Source を **Deploy from a branch** にする。
3. Branch を **main / (root)** に設定して Save。

## リポジトリ構成
- `index.html` — 公開起点
- `styles.css` — デザイン
- `app-data.js` — Lesson 8 の例文・問題・助動詞一覧データ
- `app-main.js` — クリック表示・音声・ナビゲーション等の処理
- `manual.html` — 授業での使い方
- `README.md` — この説明

## 主な機能
- 助動詞の全体地図
- 改訂版「助動詞のすべて」一覧（常時呼び出し）
- A 能力・許可 / B 義務・必要 / C 可能性・推量
- EXERCISE 1〜4 全問題
- 正答・詳しい解説・誤答理由・日本語訳
- 英語音声（Web Speech API）
- 意味比較ラボ
- TRY / Exit Ticket
- PC / タブレット / スマホ対応
- 外部ライブラリ・外部画像なし

## 設計上のポイント
- 問題タイトルには正答を示唆する語を入れない。
- 初学者が個々の用法を断片的に覚えないよう、最初に「能力・許可」「義務・必要」「可能性・推量」の3分類を提示。
- 右下の「一覧表」から、授業途中でも改訂版の助動詞表をいつでも呼び出せる。
- must 99% / may 50% のような固定確率表現を避け、根拠・文脈・話し手の態度で推量を説明する。
