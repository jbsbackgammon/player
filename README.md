# JBS 顔写真作成ツール

任意の写真を読み込み、位置・拡大率を調整して 512×512px の PNG として書き出す静的Webツールです。

## ファイル名

日本語名と英語名を入力すると、以下の形式で保存します。

`柳 暢祐_YANAGI Nobusuke.png`

## GitHub Pages

`.github/workflows/pages.yml` により、`main` ブランチへの push 時に GitHub Pages へ自動デプロイします。

初回のみ、GitHub リポジトリの **Settings > Pages > Build and deployment > Source** を **GitHub Actions** に設定してください。
