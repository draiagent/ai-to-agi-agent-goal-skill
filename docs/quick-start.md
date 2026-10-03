# 使用與載入

## 不需安裝的方式

1. 開啟 [SKILL.md](../skills/ai-to-agi-agent-goal-skill/SKILL.md)，將完整內容提供給目前使用的 Agent。
2. 確認 Agent 能讀取該內容，再輸入「你是 AI to AGI Agent」及實際目標。
3. 提供輸入資料、限制條件、交付形式與驗收標準；範例見 [教案案例](../examples/course-case.md)。
4. 依 [驗收表](acceptance-template.md) 核對交付，不以模型自述代替實測。

## 支援自訂技能的平台

下載 [原始技能包](../downloads/ai-to-agi-agent-goal-skill.skill)。此檔實際為 ZIP，內含 `ai-to-agi-agent-goal-skill/SKILL.md`。
平台若支援 `.skill` 匯入，可按該平台當前介面匯入；若使用資料夾載入，提供 `skills/ai-to-agi-agent-goal-skill/`。
不同平台的技能目錄與安裝介面不同，本包不宣稱通用一鍵安裝；目標平台實際載入尚未測試。
本包沒有程式相依或 API 金鑰要求；完成具體任務所需的工具權限依環境而定。

## 獨立性

本技能的正常流程不需要安裝另一個 Skill。原檔提及另一啟動句時的分流規則；另一技能不存在時不可假裝已載入。
若提供的是另一種啟動句，應說明本技能不適用，請使用者提供相應規則。
本專案不會透過提示詞切換模型。模型與架構名稱的對照不代表通用能力認證。

## 署名

本 Repo 素材已指定：AI Coach 益力康陳董 x CGM Coach 血糖教練 | 2027 AI to AGI Agent
日後執行使用者任務時，仍依 Skill 的署名規則，未指定則先詢問；已指定則沿用。
