# SharePoint Framework 開発環境用 Dockerfile
SharePoint Framework の開発環境用の Docker イメージを作成するための Dockerfile です。

## 使い方
Dockerfile をダウンロードし Docker でビルドしてイメージを作成してください。

PowerShell
```PowersShell
docker build -t [ラベル] [Dockerfile のパス]
```

例
```PowersShell
docker build -t myspfx:1.9.1 .
```

## タグ
- **latest**: SharePoint Framework Yeoman generator Version 1.9.1