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

## 使用上の注意点
作成した Docker イメージを利用する際には、以下のサイトにある Known issues を読んで必要な対応を行ってください。

[waldekmastykarz/docker-spfx](https://github.com/waldekmastykarz/docker-spfx)

## タグ
- **latest**: SharePoint Framework Yeoman generator Version 1.10.0
- **1.10.0**: SharePoint Framework Yeoman generator Version 1.10.0
- **1.9.1**: SharePoint Framework Yeoman generator Version 1.9.1
