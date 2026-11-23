# 臺灣穿山甲 LLM Wiki

這個專案以臺灣穿山甲的生理、行為、生態與保育為研究主題。課程作業以 Wiki 為知識基礎，製作了互動 HTML 教學簡報《如果你是一隻穿山甲，你能在臺灣活得好嗎？》。每題先邀請觀眾猜測，再用研究證據解釋答案。Wiki 也將作為 2D 生態探索遊戲《當一隻穿山甲》的知識基礎。

| 路徑 | 用途 |
| --- | --- |
| [AGENTS.md](AGENTS.md) | Schema、證據規則及維護流程 |
| [raw/](raw/) | 原始來源與存取資訊 |
| [wiki/index.md](wiki/index.md) | 研究領域、來源與開放問題入口 |
| [wiki/overview.md](wiki/overview.md) | 研究與轉譯範圍 |
| [templates/](templates/) | 資料、頁面與報告範本 |
| [docs/workflow.md](docs/workflow.md) | 完整流程圖及各關卡定義 |
| [reports/](reports/) | 實際檢查與修訂紀錄 |
| [slides/](slides/) | HTML 教學簡報與離線包 |
| [log.md](log.md) | 變更與執行歷程 |

第二階段已匯入 8 份來源，包含 5 篇核心研究、2 篇限定取用的論文與 1 則案例報導。可查閱 [來源審查](reports/source-review.md) 與 [執行摘要](reports/phase-2-summary.md)。後續增量補充 13 筆來源，目前索引共 21 筆，各筆的取用範圍見[來源頁](wiki/index.md)。

## 作業成果

- [公開 HTML 簡報](https://taiwan-pangolin-field-notes.brawnymyrrh128.chatgpt.site/#cover)共 19 張，依序是物種介紹、六道解謎、總結與 Wiki 查閱。另有[本機 HTML](slides/dist/index.html)和[離線 ZIP](slides/pangolin-presentation.zip)。
- [LLM Wiki 索引](wiki/index.md)可進入概念與來源頁。[六道解謎題綱](docs/quiz-outline.md)可逐題回查依據。
- [Graph 與節點規則](docs/workflow.md)記載 Wiki 與 HTML 的檢查及修正路徑。
- [全庫初檢](reports/lint-corpus-initial.md)、[複檢](reports/lint-corpus-recheck.md)與[簡報驗證](reports/slides-validation.md)保存實際結果、讀者回饋與反思。

後續新增來源時，確認來源版本、全文取得方式、保存權利、作者與發布單位。來源組合應檢查對六個領域的涵蓋度，以及是否有臺灣野外研究能支持核心敘述。馬頭山案例須先核對所指開發案、文件日期及程序階段，再分別收錄公文、審查紀錄與當事方說法。
