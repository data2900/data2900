# 👋 Hi, I'm FUKUO TANNAKA

## 💼 About Me

- 💻 Python・データ分析を学習・実践中の障がい者雇用ワーカー
- 🏡 完全在宅での業務経験あり（例：ニュースデータ分析、トレンド可視化、Webスクレイピング）
- 🎯 目標：自宅からでも価値を提供できる実務スキルを継続的に習得・発信していくこと

---

## 🔧 Skills & Tools

| 分野        | 使用技術・ツール                     |
|-------------|--------------------------------------|
| データ分析   | `Python`（pandas, matplotlib, sklearn, pytrends） |
| 情報収集     | `feedparser`, `Google News RSS`, `Selenium`, `Scrapy` |
| 自動処理     | `GAS`, `gspread`, `pickle`, `csv`, `SQLite`, `Excel` |
| 可視化       | `matplotlib`, `Google Sheets`, `条件付き書式（GAS）` |
| その他       | `VS Code`, `GitHub`, `Jupyter Notebook`, `Janome`（形態素解析） |

---

## 📈 最近のプロジェクト

### 🔹 [日本株定点観測ツール]
Nikkei・MoneyWorld・SBI証券などの公開データを統合・可視化。

- `nikkei.py`：日経の企業コンセンサス一覧をScrapyでクロール
- `sbi_scraper.py`：SBI証券の財務・業績情報を自動取得し保存（HTML→辞書→CSV/SQLite）
- `merge_and_store.py`：複数ソースからの企業情報を統合して保存
- `set_conditional_formatting.gs`：GASによるGoogleスプレッドシートへの条件付き書式設定

➡️ 実務を想定した在宅データ収集・可視化ワークフローを構築

### 🔹 [ニュース×トレンド分析パイプライン]
RSSニュースの収集からトレンド可視化・バズ指数算出までを自動化。

- `fetch_news.py`：Googleニュース（RSS）からビジネス系記事を収集
- `extract_keywords.py`：TF-IDFによる頻出語・重要語の抽出
- `google_trends.py`：キーワードとGoogleトレンドの照合・ピーク検出
- `process_data.py`：話題度スコアの算出、トレンド要約出力

---

## 🧩 その他の特徴

- 障がい者雇用（身体1級）× 完全在宅 × 転職活動中
- 実務ベースの学習と、自主プロジェクトによる成果物を継続公開中
- GitHubを通じて職務能力・スキルの見える化を推進
