# yukinissie-zenn-contents

yukinissie's Zenn contents

## 📚 このリポジトリについて

このリポジトリは[Zenn](https://zenn.dev)で記事を管理・公開するためのものです。

## 🚀 セットアップ

### 1. 依存パッケージのインストール

```bash
npm install
```

### 2. ローカルプレビュー

```bash
npm run preview
```

ブラウザで `http://localhost:8000` にアクセスすると、記事のプレビューが確認できます。

## 📝 記事の作成

### 新しい記事を作成する

```bash
npm run new:article
```

または、手動で `articles/` ディレクトリ内に `.md` ファイルを作成します。

### テンプレートを使用する

`articles/.template.md` をコピーして新しい記事を作成できます：

```bash
cp articles/.template.md articles/your-article-name.md
```

## 📁 ディレクトリ構造

```
.
├── articles/          # 記事ファイル（.md）
├── books/             # 本（複数チャプター）
├── images/            # 画像ファイル
├── .gitignore         # Gitの除外設定
├── package.json       # npm設定
└── README.md          # このファイル
```

## ✍️ 記事フォーマット

各記事は以下のフロントマターを含む必要があります：

```markdown
---
title: "記事のタイトル"
emoji: "📝"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: ["tag1", "tag2"]
published: false # true: 公開 / false: 下書き
---

# 記事の内容

ここに本文を書きます。
```

### フロントマターの説明

- **title**: 記事のタイトル（必須）
- **emoji**: アイキャッチ絵文字（必須）
- **type**: `tech`（技術記事）または `idea`（アイデア）（必須）
- **topics**: トピック（タグ）の配列
- **published**: `true`で公開、`false`で下書き（必須）

## 🖼️ 画像の使用

1. 画像を `images/` ディレクトリに配置
2. 記事内で以下のように参照：

```markdown
![画像の説明](/images/your-image.png)
```

## 📖 本（Books）の作成

```bash
npm run new:book
```

本は `books/` ディレクトリ内に作成され、複数のチャプターで構成されます。

## 🔗 参考リンク

- [Zenn公式](https://zenn.dev)
- [Zenn CLI](https://github.com/zenn-dev/zenn-editor)
- [ZennのMarkdown記法](https://zenn.dev/zenn/articles/markdown-guide)

## 📄 ライセンス

MIT
