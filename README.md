# Hands-on Diffusion Language Models

拡散言語モデルの基盤技術である離散拡散モデル（吸収拡散）の最小実装です。

## 概要

本リポジトリは技術記事「[手を動かして拡散言語モデルの仕組みを理解する](https://zenn.dev/v_ajw63600/articles/504c3dc3155178)」の補助資料として作成されました。ニューラルネットワークを使わずに、離散拡散モデルの本質的な動作を体験できます。

## ファイル構成

- `01-simulation-forward.jl` - 順方向過程のシミュレーション
- `02-simulation-reverse.jl` - 逆方向過程のシミュレーション
- `03-diffusion-on-images.jl` - 画像への順方向拡散過程適用デモ

## 実行方法

1. Julia環境をセットアップ
2. Pluto.jlを起動
   ```bash
   julia -e "using Pluto; Pluto.run()"
   ```
3. ブラウザで各ノートブックを開いて実行

## ライセンス

MIT License
