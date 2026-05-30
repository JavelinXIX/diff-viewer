# Goal

ブラウザで動作するWinMerge風差分表示ツールを作成する。

# Requirements

- サーバー不要
- index.htmlのみで動作
- 差分表示専用
- マージ機能不要
- 左右2ペイン
- ファイル読込対応
- 行単位diff
- 単語単位ハイライト
- スクロール同期
- オフライン動作

# UI

- WinMerge風
- 行番号表示
- 追加=緑
- 削除=赤
- 変更=黄色

# Security

- 外部送信禁止
- XSS対策
- ユーザー入力をHTMLエスケープ

# Deliverables

- index.html
- README.md
