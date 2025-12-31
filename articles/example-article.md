---
title: "Zennの記事サンプル"
emoji: "📝"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: ["zenn", "markdown"]
published: false
---

# はじめに

これはZennの記事サンプルです。Zennでは、GitHubリポジトリと連携して記事を管理・公開できます。

## Zennの記事フォーマット

### フロントマター（記事の設定）

記事の冒頭には、YAML形式で記事の設定を記述します：

- **title**: 記事のタイトル（必須）
- **emoji**: 記事のアイキャッチ絵文字（必須）
- **type**: 記事のタイプ（必須）
  - `tech`: 技術記事
  - `idea`: アイデア・読み物系
- **topics**: 記事に関連するトピック（タグ）
- **published**: 公開設定（必須）
  - `true`: 公開
  - `false`: 下書き

### Markdown記法

Zennでは標準的なMarkdownが使えます：

```javascript
// コードブロックの例
function hello() {
  console.log("Hello, Zenn!");
}
```

#### リスト

- 箇条書き1
- 箇条書き2
- 箇条書き3

1. 番号付きリスト1
2. 番号付きリスト2
3. 番号付きリスト3

#### 引用

> これは引用文です。
> 複数行にわたって書くこともできます。

#### リンク

[Zenn公式サイト](https://zenn.dev)

#### 画像

画像は`/images/`ディレクトリに配置し、以下のように参照します：

```markdown
![画像の説明](/images/sample-image.png)
```

## まとめ

Zennを使って技術記事を書いてみましょう！
