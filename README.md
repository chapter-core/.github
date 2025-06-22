# Organization Settings

組織共通の設定・テンプレートを管理するリポジトリです。

## 概要

本リポジトリでは、以下の組織共通設定を管理します：

- Issue/PRテンプレート
- GitHub Actionsワークフロー
- セキュリティポリシー
- コントリビューションガイド

## リポジトリ構成

```bash
.github-template/
├── .github/
│   ├── ISSUE_TEMPLATE/      # Issueテンプレート
│   │   ├── config.yml      # テンプレート設定
│   │   ├── 1-feature.yml   # 機能実装
│   │   ├── 2-bug.yml      # バグ報告
│   │   └── 3-document.yml # ドキュメント
│   └── workflows/          # GitHub Actions
├── docs/
│   ├── CONTRIBUTING.md     # コントリビューションガイド
│   ├── SECURITY.md        # セキュリティポリシー
│   └── CODE_OF_CONDUCT.md # 行動規範
└── README.md
```

## Issue管理

### ステータスの種類

| ステータス | 説明 |
|-----------|------|
| 📥 Backlog | 未着手のタスク |
| 🏃 In Progress | 作業中のタスク |
| 👀 In Review | レビュー中のタスク |
| ✅ Done | 完了したタスク |

### ラベルの種類

| ラベル | 説明 |
|--------|------|
| 🚀 Feature | 新機能開発・機能改善 |
| 🐛 Bug | バグ修正・不具合対応 |
| 📚 Doc | ドキュメント整備 |
| 🛠️ Infra | インフラ構築・設定変更 |
| 🧪 Test | テストコード・品質管理 |
| 🔄 Duplicate | 重複Issue |
| 🚫 Blocked | 他タスク依存・待ち |
| 🔒 Security | セキュリティ関連 |
