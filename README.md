# 台灣高中教師 AI Skills 資源庫 V2.0

**30 個實用技能｜繁體中文｜台灣高中情境**

這是依教師實務重新撰寫的技能規範套件，不是宣稱為 Anthropic／OpenAI 官方發行的30個技能；不含第三方技能原始碼。每個 `SKILL.md` 具有 `name`、`description` frontmatter 與可執行的工作步驟；**不保證所有平台可直接「安裝」**，需依平台支援的 Skills/Agent 功能載入。

## 包含內容

- `skills/`：6 領域、30 個獨立技能，每個含 `SKILL.md` 與 `EXAMPLE.md`。
- `references/shared-guidelines.md`：108課綱、資料真實性、學生個資、授權、無障礙與人工覆核。
- `templates/`：教師輸入資料表與 Skill 測試紀錄。
- `MANIFEST.json` 與 `SKILLS-INDEX.csv`：技能索引。

## 使用方式

1. 解壓縮，查看 `SKILLS-INDEX.csv` 或下方清單。
2. 依平台支援方式匯入所需技能的**整個資料夾**，或將 `SKILL.md` 內容貼入專案／Agent 指令；共通準則請一併提供。
3. 以 `EXAMPLE.md` 先用去識別化教材測試。
4. 108課綱原文與代碼請提供官方可核對資料；沒有資料就保持「待教師核對」。
5. 若平台沒有檔案、TTS、影片或程式執行工具，技能只能提供素材和操作步驟，不應假稱已產生實體檔案。

### ChatGPT／Claude／Gemini 使用提醒

三者的技能讀取、檔案存取、可執行工具及權限並不完全相同；本套件設計為**內容可攜**，不是三平台一鍵安裝保證。以支援 `SKILL.md` 的執行環境為主；其他環境可貼入為專案指令或自訂助理規則。

## 30個技能

### 01-教學設計與備課

- [完整教案設計](skills/01-教學設計與備課/lesson-plan-creator/SKILL.md)（`lesson-plan-creator`）
- [108課綱對應](skills/01-教學設計與備課/curriculum-alignment/SKILL.md)（`curriculum-alignment`）
- [差異化教學](skills/01-教學設計與備課/differentiated-instruction/SKILL.md)（`differentiated-instruction`）
- [探究與實作課程](skills/01-教學設計與備課/inquiry-based-learning/SKILL.md)（`inquiry-based-learning`）
- [ORID討論教學](skills/01-教學設計與備課/orid-lesson-designer/SKILL.md)（`orid-lesson-designer`）
- [課前準備助手](skills/01-教學設計與備課/teacher-prep-assistant/SKILL.md)（`teacher-prep-assistant`）

### 02-教材轉換與視覺化

- [PDF教材多格式轉換](skills/02-教材轉換與視覺化/pdf-to-teaching-materials/SKILL.md)（`pdf-to-teaching-materials`）
- [長文轉資訊圖卡](skills/02-教材轉換與視覺化/text-to-infographics/SKILL.md)（`text-to-infographics`）
- [教學簡報製作](skills/02-教材轉換與視覺化/slide-deck-generator/SKILL.md)（`slide-deck-generator`）
- [互動學習單頁網站](skills/02-教材轉換與視覺化/interactive-learning-web/SKILL.md)（`interactive-learning-web`）
- [教學影片腳本與製作](skills/02-教材轉換與視覺化/teaching-video-generator/SKILL.md)（`teaching-video-generator`）
- [概念圖與心智圖](skills/02-教材轉換與視覺化/concept-map-generator/SKILL.md)（`concept-map-generator`）

### 03-評量與學習診斷

- [雙向細目表](skills/03-評量與學習診斷/assessment-blueprint/SKILL.md)（`assessment-blueprint`）
- [試題與詳解](skills/03-評量與學習診斷/exam-question-generator/SKILL.md)（`exam-question-generator`）
- [多元評量規準](skills/03-評量與學習診斷/rubric-generator/SKILL.md)（`rubric-generator`）
- [迷思概念診斷](skills/03-評量與學習診斷/misconception-detector/SKILL.md)（`misconception-detector`）
- [學習數據分析](skills/03-評量與學習診斷/learning-analytics/SKILL.md)（`learning-analytics`）

### 04-自主學習與作品

- [18週自主學習規劃](skills/04-自主學習與作品/self-directed-learning-planner/SKILL.md)（`self-directed-learning-planner`）
- [學習歷程檔案整理](skills/04-自主學習與作品/learning-portfolio-builder/SKILL.md)（`learning-portfolio-builder`）
- [專題導向學習](skills/04-自主學習與作品/project-based-learning/SKILL.md)（`project-based-learning`）
- [學生反思引導](skills/04-自主學習與作品/student-reflection-coach/SKILL.md)（`student-reflection-coach`）

### 05-行政與班級經營

- [校園活動行政套件](skills/05-行政與班級經營/school-event-planner/SKILL.md)（`school-event-planner`）
- [校務公文與文書](skills/05-行政與班級經營/school-document-writer/SKILL.md)（`school-document-writer`）
- [會議紀錄與待辦追蹤](skills/05-行政與班級經營/meeting-minutes-generator/SKILL.md)（`meeting-minutes-generator`）
- [校務儀表板](skills/05-行政與班級經營/school-data-dashboard/SKILL.md)（`school-data-dashboard`）
- [親師溝通文稿](skills/05-行政與班級經營/parent-communication/SKILL.md)（`parent-communication`）

### 06-圖書館與閱讀推廣

- [主題書展策展](skills/06-圖書館與閱讀推廣/book-exhibition-curator/SKILL.md)（`book-exhibition-curator`）
- [好書導讀與閱讀提問](skills/06-圖書館與閱讀推廣/book-review-generator/SKILL.md)（`book-review-generator`）
- [閱讀活動與競賽](skills/06-圖書館與閱讀推廣/library-event-designer/SKILL.md)（`library-event-designer`）
- [閱讀與資訊素養](skills/06-圖書館與閱讀推廣/reading-literacy-assistant/SKILL.md)（`reading-literacy-assistant`）

## 授權與用途

本套件為新撰寫的教師工作流程範本。附帶教材、他人書籍、原始圖片和既有課綱的授權由使用者自行確認；請勿將學生或學校機密直接餵入不適合的服務。所有正式教學、校務或評量成品由教師最後覆核。
