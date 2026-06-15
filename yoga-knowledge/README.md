# Yoga Database

原典に根拠を持つヨーガ知識ベース。
パブリックドメインの一次文献を土台に、
サンスクリット用語・スートラ・アーサナ・哲学を
出典付きで管理するベンダー中立のMarkdown知識ベース。

## Format

This knowledge base conforms to
Open Knowledge Format (OKF) v0.1
Published by Google Cloud, 2026-06-12
https://github.com/GoogleCloudPlatform/knowledge-catalog/tree/main/okf

すべてのエントリは OKF v0.1 フロントマター（`type`, `title`, `description`, `tags`, `timestamp`）を持ち、
通常のMarkdownリンクでファイル間を相互参照しています。

## Structure

| フォルダ | OKF type | 内容 |
|---|---|---|
| 05_Sources/ | `source-text` | 原典フルテキスト（3件） |
| 01_Vocabulary/ | `yoga-vocabulary` | サンスクリット用語（9件） |
| 02_Sutras/ | `yoga-sutra` | スートラエントリ（13件） |
| 03_Philosophy/ | `yoga-philosophy` | 哲学体系（1件） |
| 04_Asana/ | `yoga-asana` | アーサナ・実践法（46件） |

全体索引: [index.md](index.md)

## Source Texts

すべてパブリックドメイン。

| テキスト | 訳者 | 年 | 取得元 |
|---|---|---|---|
| Yoga Sutras of Patanjali | Charles Johnston | 1912 | Wikisource |
| Hatha Yoga Pradipika | Pancham Sinh | 1915 | Wikisource |
| Bhagavad Gita | Edwin Arnold | 1885 | Project Gutenberg |

Sanskrit IAST data:
GRETIL (Göttingen Register of Electronic Texts in Indian Languages)
Data entry: Philipp A. Maas, 2020-07-31
License: CC BY-SA

## License

- Source texts: Public Domain
- IAST data: CC BY-SA (GRETIL / Philipp A. Maas 2020)
- Original entries and commentary: MIT License

## Notes

- すべてのエントリは一次文献の章・節番号に紐づいています
- 出典が確認できない情報は本文に混入させていません
- 通常のMarkdownリンクで相互参照（Obsidian非依存）
