# aws-handson-template

AWS ハンズオン用のテンプレートリポジトリです。

## 🚀 使い方

1. このリポジトリの **Use this template** → **Create a new repository** をクリック
2. リポジトリ名を入力して **Create repository** をクリック
3. 作成したリポジトリの **Code** → **Codespaces** タブ → **Create codespace on main** をクリック

Codespace が起動すると、以下のツールが自動的にインストールされます:

- **AWS CLI v2** - AWS リソースの操作
- **Python 3.12** - Lambda 関数の開発（`python` / `pip` コマンドでも利用可）
- **Node.js (LTS)** - JavaScript/TypeScript 開発
- **npm** - パッケージ管理

## 📁 含まれるファイル

```
.devcontainer/
  devcontainer.json  ... Codespace の開発環境設定
test.txt             ... テスト用テキストファイル
```

## ⚙️ Codespace 起動後の設定

AWS CLI の認証情報を設定します:

```bash
aws configure
```

| 項目 | 値 |
|------|-----|
| AWS Access Key ID | 自分の IAM ユーザーのアクセスキー |
| AWS Secret Access Key | 自分の IAM ユーザーのシークレットキー |
| Default region name | `ap-northeast-1` |
| Default output format | `json` |
