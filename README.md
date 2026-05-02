# 補助金情報まとめ

各種補助金・助成金に関する情報を整理するリポジトリです。

## ディレクトリ構成

```
.
├── README.md                # 全体目次（このファイル）
├── templates/
│   └── grant-template.md    # 個別補助金の記載テンプレート
├── grants/                  # 個別補助金の詳細ファイル
├── categories/              # カテゴリ別の補助金一覧
│   ├── business-startup.md  # 創業・起業支援
│   ├── it-digital.md        # IT・DX 関連
│   ├── manufacturing.md     # ものづくり
│   ├── employment.md        # 雇用・人材
│   ├── r-and-d.md           # 研究開発
│   └── energy-environment.md # 省エネ・環境
└── by-issuer/               # 実施機関別（国／都道府県／市区町村 等）
```

## 使い方

1. 新しい補助金を追加するときは `templates/grant-template.md` をコピーして編集する
2. 適切なカテゴリの Markdown に概要と内部リンクを追記する
3. 必要に応じて `by-issuer/` 配下にも実施機関別のリンクを置く

## カテゴリ一覧

| カテゴリ | ファイル | 概要 |
| --- | --- | --- |
| 創業・起業支援 | [business-startup.md](categories/business-startup.md) | 創業時の設備・運転資金等 |
| IT・DX 関連 | [it-digital.md](categories/it-digital.md) | IT 導入・DX 推進 |
| ものづくり | [manufacturing.md](categories/manufacturing.md) | 設備投資・試作開発 |
| 雇用・人材 | [employment.md](categories/employment.md) | 採用・育成・処遇改善 |
| 研究開発 | [r-and-d.md](categories/r-and-d.md) | R&D・実証事業 |
| 省エネ・環境 | [energy-environment.md](categories/energy-environment.md) | 省エネ設備・脱炭素 |

## 補助金一覧（俯瞰用）

| 名称 | カテゴリ | 実施機関 | 対象者 | 補助上限（目安） | 公募期間 | 詳細 |
| --- | --- | --- | --- | --- | --- | --- |
| 小規模事業者持続化補助金 | 創業・起業支援 | 中小企業庁（商工会連合会／日商） | 小規模事業者 | 50 万円〜200 万円 | 年度内に複数回 | [詳細](grants/jizokuka-hojokin.md) |
| デジタル化・AI導入補助金 | IT・DX 関連 | 経済産業省／中小企業庁 | 中小企業・小規模事業者 | 〜450 万円（〜3,000 万円） | 多次締切方式 | [詳細](grants/digital-ai-hojokin.md) |
| ものづくり補助金 | ものづくり | 中小企業庁（中央会） | 中小企業・小規模・特定事業者 | 750 万円〜3,000 万円 | 年度内に複数回 | [詳細](grants/monodzukuri-hojokin.md) |

## タグ運用ルール

各補助金ファイルの frontmatter に付与するタグの命名ルール。

- 対象者: `#中小企業`, `#小規模事業者`, `#個人事業主`, `#スタートアップ`
- 地域: `#全国`, `#東京都`, `#大阪府` など都道府県・市区町村名
- テーマ: `#DX`, `#省エネ`, `#人材育成`, `#販路開拓`, `#研究開発`
- 状態: `#公募中`, `#公募終了`, `#次期予定`

## 凡例

- 金額表記: 円（万円・千円表記の場合は単位を明記）
- 公募期間: `YYYY-MM-DD` 形式
- 最終更新日: 各ファイル冒頭の frontmatter `updated` フィールド
