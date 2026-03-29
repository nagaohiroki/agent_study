# AGENTS.md

## Language

- ユーザーとの会話はすべて日本語で行う
- コード生成は英語でも良い
- コードの説明・コメントは日本語で書く

---

## Development Environment

このプロジェクトは以下の環境を使用する。

- Python
- uv (Python package manager)
- ./srcフォルダにコードを書く

依存関係管理は **uv** を使用すること。


## Package install

- pyproject.tomlから追加してuv sync

## Coding style

- ruffで整形
- basedpyrightでの警告は全て直す

## コミットメッセージのガイドライン

- コミットメッセージは日本語で書く
- コミットメッセージの最初の行は50文字以内で、概要を書く
- コミットメッセージの2行目は空行
- コミットメッセージの3行目以降は、詳細を書く

## ArchitectDesign

- ./ARCHITECTURE.mdに記載しています
