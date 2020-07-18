# SharePoint Framework 開発環境用 Dockerfile 及び Docker イメージ
SharePoint Framework の開発環境用の Docker イメージを作成するための Dockerfile と、この Dockerfile により作成された Docker イメージです。  
Dockerfile は [GitHub](https://github.com/HiroakiOikawa/docker-spfx/) に、Docker イメージは [Docker Hub](https://hub.docker.com/r/orivers/spfx/) にそれぞれ格納しています。

## Dockerfile
### 使い方
[GitHub](https://github.com/HiroakiOikawa/docker-spfx/) から Dockerfile をダウンロードし Docker でビルドしてイメージを作成してください。

PowerShell
```PowersShell
docker build -t [ラベル] [Dockerfile のパス]
```

例
```PowersShell
docker build -t myspfx:1.9.1 .
```

## Docker イメージ
### 使い方
docker コマンドで [Docker Hub](https://hub.docker.com/r/orivers/spfx/) から Docker イメージを Pull してください。

PowerShell
```PowersShell
docker pull orivers/spfx:[SPFx バージョン番号]
```

例：最新版を取得する
```PowersShell
docker pull orivers/spfx
```

例：v1.9.1を取得する
```PowersShell
docker pull orivers/spfx:1.9.1
```

## 使用上の注意点
作成した Docker イメージを利用する際には、以下のサイトにある Known issues を読んで必要な対応を行ってください。

[waldekmastykarz/docker-spfx](https://github.com/waldekmastykarz/docker-spfx)

## タグ
- **latest**: SharePoint Framework Yeoman generator Version 1.10.0
- **1.10.0**: SharePoint Framework Yeoman generator Version 1.10.0
- **1.9.1**: SharePoint Framework Yeoman generator Version 1.9.1
