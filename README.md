# swarm-sandbox

swarm-sandbox は郡知能（swarm intelligence）の実験を行うためのリポジトリです。

## 目的

- 簡単な群ロボットシミュレーションの実装と検証
- 並列動作アルゴリズムの研究メモ

## セットアップ

以下は `uv` を利用して開発環境をセットアップする手順です。

```bash
# リポジトリの取得
git clone <REPOSITORY_URL>
cd swarm-sandbox

# 依存関係の同期と動作確認（3コマンド）
uv sync
uv run python -V
uv run pytest -q   # テストが整備され次第
```

## ライセンス

本プロジェクトは [MIT License](LICENSE) の下で配布されています。
