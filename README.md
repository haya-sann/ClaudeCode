# ClaudeCode

Claude Code を動かすためのルートリポジトリです。

## 概要

このリポジトリは [Claude Code](https://docs.anthropic.com/ja/docs/claude-code/overview) を使用するための基盤となるプロジェクトです。

## セットアップ

### 前提条件

- Node.js 18 以上
- npm または yarn

### インストール

```bash
# Claude Code をグローバルインストール
npm install -g @anthropic-ai/claude-code
```

### 認証

```bash
# Anthropic API キーを設定
export ANTHROPIC_API_KEY="your-api-key-here"
```

または `.env` ファイルを作成してください（`.env` は `.gitignore` に含まれています）：

```
ANTHROPIC_API_KEY=your-api-key-here
```

## 使い方

```bash
# Claude Code を起動
claude
```

プロジェクトルートで `claude` コマンドを実行すると、Claude Code が起動します。  
`CLAUDE.md` に記載されたプロジェクト固有の指示が自動的に読み込まれます。

## ドキュメント

- [Claude Code 公式ドキュメント](https://docs.anthropic.com/ja/docs/claude-code/overview)
- [CLAUDE.md](./CLAUDE.md) - プロジェクト固有の指示
