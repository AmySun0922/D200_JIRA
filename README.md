1. Epic (大型任務)，約為數個月內可完成之案件  
   a. 標題格式：計劃名、產品名  
2. Task (任務)，約為 1 ~ 2 週內可完成之目標  
   a. 於標題中簡述任務，詳細資訊請填寫在 [描述] 中，包括指派的人、時、緣由，相關附件  
   b. 標上預計開始執行的時間於 [Start date]  
   c. 若有預計完成日期，請標上時間於 [截止日期]  
   d. 於 [受託人] 填上自己的名字  
   e. 設定好所屬的 Epic  
   f. 若發現任務太大，可適當分割成多個  
   g. 若此任務與其他 Task 有連結，可使用 [連結議題] 找到對應的任務  
   h. 若有相關程式開發，請連結 Github 之 Branch 或 PR  
3. Sub-task (子任務)，基於 Task，約為 3 天內可完成之目標  
   a. 規則同 Task  
   b. 同一個 Task 以 5 個 Sub-task 為限  
4. Bug (漏洞)，尚待討論的事項，通常以問題呈現  
   a. 於標題寫上被提出的時間、問題  
   b. 詳細資訊請填寫在 [描述] 中  
   c. 請避免使用 Sub-task，請使用 [連結議題] 連結到相對應的 Task  
   d. 若有預計問題要被解決的時間，請標上時間於 [截止日期]  
   e. 所有跟此問題相關的資訊可在留言中記錄、討論  
6. Story (故事)，於任何場合的重要決議  
   a. 於標題寫上決議的時間、人、決議的事項  
   b. 通常沒有啟始時間也沒有完成時間  
   c. 請避免使用 Sub-task，請使用 [連結議題] 連結到相對應的 Task  
8. Pending/Archive 的任務，請在 [描述] 中留言寫上原因，並請自行修改狀態。  
9. 請於每週五下班前檢查自己的任務狀態，並完成所有更新。  

# card templates (by ChatGPT)

## Epic (大型任務)
- **標題格式**：計劃名、產品名
- **描述**：詳細描述這個大型任務，包括目標、範圍和主要里程碑。

## Task (任務)
- **標題**：簡述任務
- **描述**：
  - 詳細資訊：包括指派的人、時間、緣由，相關附件。
  - 預計開始執行的時間：[Start date]
  - 若有預計完成日期：[截止日期]
  - 受託人：[填上自己的名字]
  - 所屬 Epic：[Epic 名稱]
  - 若發現任務太大，可適當分割成多個
  - 若此任務與其他 Task 有連結，可使用 [連結議題] 找到對應的任務
  - 若有相關程式開發，請連結 Github 之 Branch 或 PR

## Sub-task (子任務)
- **標題**：簡述子任務
- **描述**：
  - 詳細資訊：包括指派的人、時間、緣由，相關附件。
  - 預計開始執行的時間：[Start date]
  - 若有預計完成日期：[截止日期]
  - 受託人：[填上自己的名字]
  - 所屬 Task：[Task 名稱]
  - 若此子任務與其他 Task 有連結，可使用 [連結議題] 找到對應的任務
  - 若有相關程式開發，請連結 Github 之 Branch 或 PR

## Bug (漏洞)
- **標題**：被提出的時間、問題
- **描述**：
  - 詳細資訊：描述漏洞，包括如何重現和相關附件。
  - 若有預計問題要被解決的時間：[截止日期]
  - 所有跟此問題相關的資訊可在留言中記錄、討論
  - 請避免使用 Sub-task，請使用 [連結議題] 連結到相對應的 Task

## Story (故事)
- **標題**：決議的時間、人、決議的事項
- **描述**：詳細描述這個故事，包括背景、決議的內容和相關附件。
- **啟始時間**：無
- **完成時間**：無
- 請避免使用 Sub-task，請使用 [連結議題] 連結到相對應的 Task

## Pending/Archive 任務
- **描述**：在描述中留言寫上原因，並請自行修改狀態。
