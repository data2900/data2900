# 👋 Hi, I'm F.T.

# 📊 学習・実践プロジェクト

このリポジトリの内容は、**生成AI（ChatGPT）を活用しながら自主的に学習・構築した成果**です。  
AIの提案を参考にしつつ、自身で検証・修正を重ね、実務を意識した形で仕上げています。  

---

💼 About Me

Pythonを活用したデータ処理や業務効率化スクリプトを日々作成しながら、実務に近い形でのスキル習得を進めています。  
リモート環境でのデータ収集・整理や小規模DBの運用に慣れ、ツール改善や自動化を通じて効率的に作業を行う工夫を積み重ねています。  

近年は体調も安定してきたため、学び直しと就職活動に取り組んでおり、在宅勤務を中心にデータ活用の実務経験を広げたいと考えています。  
将来的には、収集したデータを基盤に **シンプルな機械学習やBIツールを用いた可視化・予測モデル構築** に挑戦し、データから価値を生み出せる働き方を目指しています。  

---

🔧 Skills & Tools  
（ChatGPTを活用しつつ実務を想定して習得）

| 分野       | 使用技術・ツール |
|------------|-----------------|
| データ分析 | Python（pandas, matplotlib, sklearn, pytrends） |
| 情報収集   | feedparser, Google News RSS, Selenium, Scrapy, requests, BeautifulSoup, Playwright |
| 自動処理   | GAS, gspread, pickle, csv, openpyxl, SQLite, Excel |
| 可視化     | matplotlib, Google Sheets, 条件付き書式（GAS）, BIツール学習中 |
| 日本語処理 | Janome, re, collections, TF-IDF, 共起語分析など |
| 環境構築   | VS Code, GitHub, Jupyter Notebook, virtualenv |

---

📈 プロジェクト例  
（生成AIを活用しつつ、自身で設計・改良）

🔹 日本株 定点観測ツール（Python × GAS × Google Sheets）  
- Webスクレイピング（Nikkei, MoneyWorld, SBI証券）  
- SQLiteを用いたデータ保存と加工  
- GASによる条件付き書式の自動化  
- 定期運用を意識した構成に調整中  

➡️ 情報収集から整理・可視化までの一連の流れを意識  

---

🔹 SBI証券・Nikkei関連スクレイパー群  
- `sbi_scraper.py` : SBI証券ページ（四季報タブ含む）のデータ収集  
- `moneyworld_scraper.py` : QUICK Money Worldのアナリストレポート収集  
- `nikkeireport.py` : 日経新聞コンセンサス情報のスクレイピング・DB格納  
- `nikkei.py` : 日経オンライン記事から銘柄関連情報の取得  

➡️ 複数ソースを横断的に収集し、共通DBに統合  

---

🔹 ニュース × トレンド分析（自動バズ指数の試行）  
- Google News RSSを活用した話題ニュースの自動収集  
- TF-IDFと形態素解析によるキーワード抽出  
- Google Trendsとの照合で「話題度」を数値化  
- Pythonでログ自動保存  

➡️ ニュースの定量評価・分析の実践  

---

🚀 今後挑戦したいこと  
- 蓄積データを活用した **シンプルな機械学習モデルの導入**  
- **BIツールや可視化基盤** を活かした意思決定支援  
- ニュース・株式情報など複数データソースを統合し、**予測モデルやレコメンド機能** の試作  
