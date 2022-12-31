<div align="center">

![Last commit](https://img.shields.io/github/last-commit/HidemaruOwO/ogp-generate-api?style=flat-square)
![Repository Stars](https://img.shields.io/github/stars/HidemaruOwO/ogp-generate-api?style=flat-square)
![Issues](https://img.shields.io/github/issues/HidemaruOwO/ogp-generate-api?style=flat-square)
![Open Issues](https://img.shields.io/github/issues-raw/HidemaruOwO/ogp-generate-api?style=flat-square)
![Bug Issues](https://img.shields.io/github/issues/HidemaruOwO/ogp-generate-api/bug?style=flat-square)

# OGP Generate API 🔖
v1.0.0-beta1
## なんだこれは

この API に任意のテキストを含めて POST をすると、そのテキストを埋め込んだサイト用の OGP を生成します。

</div>

## 🚀 使い方

[Release](/release)に Linux 及び MacOS 用のビルド済みバイナリがあるので、それをダウンロードして実行してください。

```bash
./ogp
```

これでサーバーが起動します。

```bash
curl -X POST -H "Content-Type: application/json" -d '{"text" : "これはテストです"}' http://127.0.0.1:3090/generate
```

### ✈️ POST データ

```json
{
  "text": "こちらに45文字以内の文字を入力",
  "font": "(任意)base64エンコードしたフォントデータを入力"
}
```

## 💨 ビルド

### リポジトリのクローン

```bash
git clone https://github.com/HidemaruOwO/ogp-generate-api.git
cd ogp-generate-api
```

## ⛏️ 開発

このリポジトリの開発ブランチは`develop`ブランチです。<br/>
PR を送る場合は`develop`ブランチに送っていただくと助かります。

```bash
git checkout develop
```

## 📜 ライセンス

MIT License
