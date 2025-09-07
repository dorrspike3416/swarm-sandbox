# swarm-sandbox

swarm-sandbox は郡知能（swarm intelligence）の実験を行うためのリポジトリです。

## 目的

- 簡単な群ロボットシミュレーションの実装と検証
- 並列動作アルゴリズムの研究メモ

## セットアップ

以下は開発環境をセットアップする手順の一例です。

```bash
# リポジトリの取得
 git clone <REPOSITORY_URL>
 cd swarm-sandbox

# 仮想環境の作成（任意）
 python -m venv .venv
 source .venv/bin/activate

# 依存関係のインストール
 pip install -e .

# テストの実行
 pytest
```

## ライセンス

本プロジェクトは [MIT License](LICENSE) の下で配布されています。
