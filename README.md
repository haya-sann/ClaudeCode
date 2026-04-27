# ClaudeCode

Claude Code 用のルートリポジトリです。

## 概要

このリポジトリは [Claude Code](https://docs.anthropic.com/ja/docs/claude-code/overview) を使った開発のためのルートリポジトリです。

## セットアップ

### 前提条件

- [Claude Code](https://docs.anthropic.com/ja/docs/claude-code/quickstart) がインストールされていること

### インストール

```bash
# リポジトリをクローン
git clone https://github.com/haya-sann/ClaudeCode.git
cd ClaudeCode

# Claude Code を起動
claude
```

## 使い方

Claude Code を起動すると、このリポジトリの `CLAUDE.md` に記載されたガイドラインに従って動作します。

```bash
# Claude Code をインタラクティブモードで起動する
claude

# 特定のタスクを実行する
claude "このコードを説明して"
```

## ディレクトリ構成

```
ClaudeCode/
├── CLAUDE.md        # Claude Code 向けの指示・ガイドライン
├── README.md        # このファイル
└── .gitignore       # Git の除外設定
```

## 参考リンク

- [Claude Code 公式ドキュメント](https://docs.anthropic.com/ja/docs/claude-code/overview)
- [Claude Code クイックスタート](https://docs.anthropic.com/ja/docs/claude-code/quickstart)
- [CLAUDE.md の書き方](https://docs.anthropic.com/ja/docs/claude-code/memory)
