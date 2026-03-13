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
