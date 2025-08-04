# Chatmodes folder

* 4.1-Beast.chatmode.md
  可能是針對 GPT-4.1 模型的「野獸模式」對話設定，強調高效能或激進推理。
* accesibility.chatmode.md
  用於促進無障礙相關對話，協助開發或設計更易用的產品。
* api-architect.chatmode.md
  聚焦於 API 架構師的角色，協助 API 設計、最佳實踐。
* azure-principal-architect.chatmode.md / azure-saas-architect.chatmode.md
  針對 Azure 雲端服務的主要架構師/ SaaS 架構師對話設定。
* azure-verified-modules-bicep.chatmode.md / azure-verified-modules-terraform.chatmode.md
  協助 Bicep 或 Terraform 模組在 Azure 上的驗證與設計。
* blueprint-mode.chatmode.md
  可能是「藍圖模式」，用於架構規劃或專案設計。
* clojure-interactive-programming.chatmode.md
  針對 Clojure 語言互動式程式設計的對話配置。
* critical-thinking.chatmode.md
  強化批判性思考的對話模式。
* csharp-dotnet-janitor.chatmode.md / janitor.chatmode.md
  針對 C#/.NET 或一般「清道夫」角色，協助程式碼維護、清理。
* debug.chatmode.md
  專注於除錯流程的對話設定。
* demonstrate-understanding.chatmode.md
  協助使用者或AI展現對主題的理解。
* electron-angular-native.chatmode.md
  針對 Electron、Angular 與 Native 結合應用的對話模式。
* expert-dotnet-software-engineer.chatmode.md / expert-react-frontend-engineer.chatmode.md
  專為 .NET 或 React 前端工程師設計的專家模式。
* gilfoyle.chatmode.md
  可能以影集角色「Gilfoyle」為主題的技術對話風格。
* implementation-plan.chatmode.md / plan.chatmode.md / planner.chatmode.md
  協助專案實施計畫、規劃。
* mentor.chatmode.md
  模擬導師角色，提供指導與建議。
* meta-agentic-project-scaffold.chatmode.md
  可能是多智能體（agentic）專案腳手架設定。
* microsoft-study-mode.chatmode.md / microsoft_learn_contributor.chatmode.md
  針對 Microsoft 學習或貢獻者的對話配置。
* ms-sql-dba.chatmode.md / postgresql-dba.chatmode.md
  分別針對 MS SQL 與 PostgreSQL 資料庫管理員（DBA）角色。
* playwright-tester.chatmode.md
  用於 Playwright 測試框架的測試流程。
* prd.chatmode.md
  可能是產品需求文件（PRD）相關的對話模式。
* principal-software-engineer.chatmode.md
  高階軟體工程師的對話設定。
* prompt-engineer.chatmode.md
  專注於提示工程（Prompt Engineering）的模式。
* refine-issue.chatmode.md
  協助細化問題描述。
* rust-gpt-4.1-beast-mode.chatmode.md
  針對 Rust 與 GPT-4.1 組合的「野獸模式」。
* semantic-kernel-dotnet.chatmode.md / semantic-kernel-python.chatmode.md
  用於 .NET 或 Python 的 Semantic Kernel 相關對話。
* simple-app-idea-generator.chatmode.md
  簡易應用程式點子生成器模式。
* software-engineer-agent-v1.chatmode.md
  軟體工程師智能體 V1 對話設定。
* specification.chatmode.md
  協助撰寫或審查規格文件。
* tdd-green.chatmode.md / tdd-red.chatmode.md / tdd-refactor.chatmode.md
  測試驅動開發（TDD）流程的各階段對話設定。
* tech-debt-remediation-plan.chatmode.md
  技術債務減緩計畫模式。
* voidbeast-gpt41enhanced.chatmode.md
  可能是 GPT-4.1 加強版的「Voidbeast」模式。
* wg-code-alchemist.chatmode.md / wg-code-sentinel.chatmode.md
  針對「程式煉金師」或「程式守護者」角色的對話設定。

## blueprint-mode.chatmode.md  還有 implementation-plan.chatmode.md / plan.chatmode.md / planner.chatmode.md 這幾個檔案有什麼不一樣?

| 檔案名稱                        | 主要用途/定位                  | 特色/重點                                                          | 適合使用時機                           |
| ------------------------------- | ------------------------------ | ------------------------------------------------------------------ | -------------------------------------- |
| blueprint-mode.chatmode.md      | 藍圖模式，架構設計、原理圖規劃 | 強調規格先行、嚴謹設計、全流程規劃、資源最佳化、禁止佔位程式碼     | 專案初期架構設計、系統規劃、技術選型   |
| implementation-plan.chatmode.md | 實作計畫，細節執行方案         | 機器可執行、明確步驟、結構化、明確檔案路徑、可自動驗證、無模糊空間 | 需求已明確，需產出可直接執行的行動方案 |
| plan.chatmode.md                | 戰略規劃、全局分析             | 強調資訊蒐集、需求釐清、架構分析、協作討論、風險評估、教育性說明   | 需求還在討論、需釐清目標、架構分析階段 |
| planner.chatmode.md             | 規劃助理，簡易計畫產生         | 產生簡單 Markdown 實作計畫，包含概述、需求、步驟、測試             | 需要快速產生基本實作計畫、任務分派     |

---

### 補充說明

- **blueprint-mode**：偏重於「建構」整體架構、原理圖、設計規範，適合在專案剛開始、需要定義系統邊界與設計原則時使用。
- **implementation-plan**：偏重於「執行」層面，產生可直接由 AI 或人員執行的詳細步驟，適合需求已確定、要開始動手做時。
- **plan**：偏重於「策略」與「分析」，協助釐清需求、了解現有程式碼、討論多種方案，適合在需求還不明確或需要全局思考時。
- **planner**：偏重於「工具性」，快速產生簡易計畫，適合日常任務分派或需要一份基本行動方案時。

如需更細緻的流程或規格，請選擇 blueprint-mode 或 implementation-plan；如需討論、釐清、協作，請選擇 plan；如只需簡單計畫，則用 planner。

## 一個專案從無到有，這四個 chat mode 妳建議要怎麼使用呢?

Copilot: 專案從無到有，這四個 chat mode 建議的使用流程如下：

| 階段              | 建議 chat mode                  | 目的與重點                                                                                         |
| ----------------- | ------------------------------- | -------------------------------------------------------------------------------------------------- |
| 需求釐清/策略分析 | plan.chatmode.md                | 先用 plan 模式協助蒐集資訊、釐清需求、分析現有程式碼、討論架構選型與風險，建立專案全局方向。       |
| 架構設計/原理圖   | blueprint-mode.chatmode.md      | 需求明確後，用 blueprint-mode 進行嚴謹的原理圖規劃、系統邊界定義、設計規範，確保建構品質與延展性。 |
| 實作計畫/細部步驟 | implementation-plan.chatmode.md | 架構確定後，使用 implementation-plan 產生明確、可執行的步驟，指定檔案路徑、函式、驗證標準等細節。  |
| 任務分派/快速規劃 | planner.chatmode.md             | 日常小任務或簡易功能時，用 planner 快速產生 Markdown 實作計畫，方便分派或追蹤。                    |

### 建議流程

1. **先用 plan 模式**：釐清需求、討論策略、分析現有資訊。
2. **進入 blueprint-mode**：設計原理圖、定義系統架構與規範。
3. **用 implementation-plan**：產生可直接執行的詳細步驟與驗證標準。
4. **日常任務用 planner**：快速產生簡易計畫，方便分派或追蹤。

這樣可以確保每個階段都用最適合的工具，提升專案品質與效率。
