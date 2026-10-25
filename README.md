# 朝5分FCCL-News

パソコン業界と家電量販店の最新ニュースを、毎朝5分で読める日本語ダイジェストにまとめる個人用のスマホ向けアプリです。

**富士通クライアントコンピューティング株式会社の公式サイトではありません。** 公開されている報道や発表だけをもとに作成しています。

- 公開URL: https://pecpec37-gift.github.io/FCCL-News/
- 毎朝 6:00ごろ（日本時間）、Claude の定期タスクが新しい号を追加します。

## データの置き場所

- `data/index.json` … 号の一覧（新しい順、最大30号）
- `data/editions/YYYY-MM-DD.json` … 各号の本文

`items[].cat` は `fccl` `market` `maker` `parts` `retail` `biz` のいずれかです。`items[].rel` はFCCLへの関係を一言で書いたものです。
