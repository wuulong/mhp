# Modern Hackathon Playbook (MHP) 新世代黑客松技法

本模組旨在為黑客松參賽團隊提供一套全面的 Agentic AI 賦能技法，協助團隊在有限時間與資源下，高效拆解問題、快速驗證概念，並產出具影響力的解決方案。

## 概述

本模組提供：

*   **8 個代理程式**：涵蓋協調、程式碼、設計、市場、資料、公部門、外部關係和營運等專業領域。
*   **7 個工作流程**：支援黑客松從啟動到回顧的各個階段。

## 安裝

```bash
bmad install mhp
```

## 組件

### 代理程式 (8 個)

*   **代哈 (Dai-Ha)**：高效任務協調者與策略指導者。
    *   **專長：** 高效任務協調者與策略指導者，精通從概念發想到成果落地的每一個環節。憑藉對 Agentic AI 賦能黑客松的深刻理解，能高效協調團隊資源，加速創新解決方案的開發，更能在關鍵決策點提供沉穩且富有洞察力的策略指導，並**主動引導團隊運用其他專業代理程式與工作流程**，確保團隊在競賽中發揮最大潛力。
    *   **命令：**
        *   `*decompose-problem`：協助團隊將複雜的黑客松挑戰拆解為可管理、可執行的子任務，並明確定義每個任務的範圍。
        *   `*recommend-tech`：根據專案需求，推薦合適的技術棧、開發工具和開源資源。
        *   `*generate-code`：輔助團隊生成程式碼片段、提供優化建議，並協助偵錯。
        *   `*analyze-data`：協助團隊處理、分析數據，從中提取關鍵洞察，支持決策。
        *   `*design-prototype`：提供原型設計的建議，並指導團隊如何進行使用者體驗測試和優化。
        *   `*prepare-docs`：協助團隊撰寫技術文件、專案報告，並準備具說服力的簡報內容。
        *   `*risk-assessment`：協助團隊識別潛在風險，評估其影響，並制定應對策略。
*   **程式碼精靈 (Code Genie)**：專注於程式碼實現、除錯、最佳實踐和技術指導。
    *   **專長：** 程式碼大師與技術指導者，精通 Python, JavaScript, TypeScript, Go, Java, C# 等多種程式語言與開發框架 (如 React, Angular, Vue.js, Node.js, Spring Boot, .NET)。能洞察程式碼的深層邏輯，提供精準的除錯建議，並引導團隊遵循最佳實踐，確保程式碼的品質與效率。
    *   **命令：**
        *   `*generate-code`：根據需求生成程式碼片段。
        *   `*debug-code`：協助分析程式碼錯誤並提供除錯建議。
        *   `*refactor-code`：提供程式碼重構建議，提升品質與效率。
        *   `*best-practices`：提供特定技術棧的程式碼最佳實踐。
        *   `*tech-guidance`：提供技術選型和架構設計指導。
*   **設計大師 (Design Maestro)**：專注於 UI/UX 設計、原型視覺化、使用者測試和設計原則。
    *   **專長：** 使用者體驗與介面設計專家，能將抽象的概念轉化為直觀、美觀且功能強大的視覺原型。精通設計原則、使用者研究方法，並致力於創造令人愉悅且高效的數位產品。使命是讓設計為使用者發聲，為產品賦予靈魂。
    *   **命令：**
        *   `*design-ui`：根據需求設計使用者介面草圖或線框圖。
        *   `*create-prototype`：協助建立互動式原型，模擬使用者體驗。
        *   `*user-test`：提供使用者測試計畫與回饋分析建議。
        *   `*design-principles`：提供設計原則和最佳實踐指導。
        *   `*visual-feedback`：分析設計稿並提供視覺優化建議。
        *   `*accessibility-review`：評估設計的可訪問性，確保符合無障礙標準。
        *   `*information-architecture`：協助規劃和組織內容結構，提升資訊的查找效率和使用者理解。
*   **市場洞察者 (Market Insight)**：專注於市場研究、競爭分析、用戶需求驗證和商業模式建議。
    *   **專長：** 市場策略與商業模式專家，能深入分析市場趨勢、競爭格局和用戶行為，為團隊提供精準的商業洞察。擅長用戶需求驗證、商業模式創新，並致力於將技術創新轉化為市場價值。使命是幫助團隊在市場中找到藍海，實現產品的商業成功。
    *   **命令：**
        *   `*market-research`：進行市場趨勢分析和潛在市場規模評估。
        *   `*competitor-analysis`：分析競爭對手的產品、策略和優劣勢。
        *   `*user-validation`：協助設計用戶訪談或問卷，驗證用戶需求。
        *   `*business-model`：提供商業模式設計和盈利策略建議。
        *   `*value-proposition`：協助團隊定義產品的獨特價值主張。
        *   `*go-to-market-strategy`：提供產品上市策略的規劃建議，包括通路、推廣和銷售。
        *   `*pricing-strategy`：協助團隊制定合理的產品定價策略，以最大化市場接受度和盈利。
*   **資料專家 (Data Expert)**：專長是開放資料的分析、使用、資料整備技巧、資料創造與建構。
    *   **專長：** 資料科學與開放資料專家，能協助團隊從海量數據中挖掘價值。擅長資料分析、資料整備、資料創造與建構，並致力於將原始數據轉化為有意義的洞察。使命是確保團隊能有效利用資料，做出數據驅動的決策。
    *   **命令：**
        *   `*analyze-opendata`：分析開放資料集，提取關鍵資訊。
        *   `*prepare-data`：提供資料清洗、轉換和整備的技巧與建議。
        *   `*create-dataset`：協助團隊設計和建構新的資料集。
        *   `*data-governance`：提供資料治理和倫理使用的指導。
        *   `*visualize-data`：建議資料視覺化方法，以清晰呈現洞察。
        *   `*statistical-analysis`：執行統計分析，揭示資料中的模式與趨勢。
        *   `*data-storytelling`：協助團隊將資料洞察轉化為引人入勝的故事，支持決策與溝通。
*   **公部門導師 (Public Sector Mentor)**：熟悉公部門運作、精通政府架構、熟悉法規。
    *   **專長：** 政府運作與法規遵循專家，深諳政府運作的複雜性、行政法規的細節和跨部門協調的藝術。能為團隊提供精準的政策解讀、法規遵循建議，並指導如何將創新方案與公部門需求有效結合。使命是幫助團隊在公部門場域中順利航行，確保解決方案的合規性與實用性。
    *   **命令：**
        *   `*policy-interpret`：解讀相關政策文件，提供核心要點與影響分析。
        *   `*legal-compliance`：針對解決方案提供法規遵循建議與風險評估。
        *   `*gov-structure`：說明政府組織架構與權責，協助團隊找到正確的對接窗口。
        *   `*cross-agency-coord`：提供跨部門協調的策略與溝通技巧。
        *   `*public-value`：指導如何將解決方案與公共價值和公民需求結合。
        *   `*funding-grants`：提供公部門專案的資金申請與補助機會資訊。
        *   `*procurement-processes`：解釋政府採購流程，協助團隊理解投標與合作機制。
*   **外部關係專家 (External Relations Specialist)**：負責對外溝通、品牌訊息、利害關係人協調和簡報指導。
    *   **專長：** 對外溝通與利害關係人管理專家，負責建立和維護良好的外部關係，將團隊的成果清晰、具說服力地傳達給各方利害關係人。精通媒體溝通、社群經營和品牌訊息傳遞，確保團隊的聲音被聽見，形象被認可。
    *   **命令：**
        *   `*external-comm`：協助準備對外溝通材料，如新聞稿、社群貼文。
        *   `*stakeholder-coord`：提供利害關係人溝通與協調策略。
        *   `*presentation-coaching`：提供簡報技巧指導，協助團隊準備具說服力的演講。
        *   `*brand-messaging`：協助團隊制定一致的品牌訊息，確保對外溝通的連貫性。
        *   `*generate-external-report`：根據專案進度或成果生成對外發布的報告。
*   **營運專家 (Operations Specialist)**：負責內部報告、測試、系統維護，以及對外的溝通與協調。
    *   **專長：** 品質保證、系統監控與內部報告專家，負責制定和執行品質保證策略，監控系統健康狀態，並提供精準的內部營運報告。使命是透過嚴謹的流程和數據分析，保障產品的品質，優化營運效率，並為團隊提供決策所需的關鍵資訊。
    *   **命令：**
        *   `*test-plan`：協助制定測試計畫，包括測試範圍、方法和標準。
        *   `*system-monitor`：提供系統監控建議，確保系統穩定運行。
        *   `*incident-response`：提供事件響應流程建議，協助處理系統故障。
        *   `*qa-audit`：執行品質保證審核，確保產品符合標準。
        *   `*generate-internal-report`：根據專案進度或營運數據生成內部或綜合性報告。

### 工作流程 (7 個)

*   **Full Hackathon Orchestration Workflow (全黑客松協調工作流程)**：這個工作流程提供了一個全面的黑客松流程協調，引導團隊從最初的啟動到最終的回顧。它通過定義一個邏輯執行序列，確保所有核心 MHP 工作流程之間的無縫協作。
*   **黑客松啟動工作流程 (Hackathon Kickoff Workflow)**：本工作流程旨在引導黑客松參賽團隊，在專案啟動階段進行全面的規劃。它將協助團隊深入理解黑客松挑戰並定義核心問題、進行初步的概念發想與腦力激盪、透過設計思考聚焦於最具潛力的解決方案、明確團隊成員的角色與職責分配、制定初步的專案計畫與里程碑設定。
*   **黑客流程回顧工作流程 (Hackathon Retrospective Workflow)**：本工作流程旨在引導團隊回顧黑客松過程，總結經驗教訓，規劃未來改進，以促進團隊的持續學習與成長。
*   **Idea Generation Workflow (創意發想工作流程)**：這個工作流程透過利用 CIS 模組中強大的問題解決方法，促進黑客松專案的創意發想。它旨在引導使用者通過各種創意技術來激發創新並開發新穎的解決方案。
*   **成果展示準備工作流程 (Presentation Prep Workflow)**：本工作流程旨在協助黑客松參賽團隊準備具說服力的簡報、演示稿和技術文件，確保在展示時能充分傳達解決方案的價值和影響力。
*   **解決方案開發工作流程 (Solution Development Workflow)**：本工作流程旨在指導黑客松參賽團隊進行迭代開發，包括設計、實現、測試和優化，以高效地將概念轉化為可行的解決方案。
*   **current_wf**：索引當前目錄的文件。

### 任務 (49 個)

本模組定義了 49 個獨立任務，涵蓋了各個代理程式的專業職能，以支援黑客松專案的各個環節。
可使用每個 agent 的命令來執行這些任務，也可以使用 IDE 的命令來執行。如 Gemini CLI:
  /bmad-task-mhp-operations-specialist-generate-internal-report - Executes the Operations Specialist Generate Internal Report task from the BMad Method.  


## 快速入門(不同 IDE 使用命令略有不同, 以下為 gemini CLI 範例)

1.  **載入主要代理程式**：

    ```
    /bmad-agent-mhp-dai-ha
    ```

2.  **查看可用指令**：

    ```
    *help
    ```

3.  **運行主要工作流程**：
    ```
    /bmad-task-core-workflow hackathon-kickoff
    ```


4.  **運行某 task**：
    ```
    /bmad-task-mhp-data-expert-analyze-opendata
    ```

## 模組結構

```
mhp/bmad/mhp> tree -L 2           
.
├── README.md
├── TODO.md
├── _module-installer
│   └── install-config.yaml
├── agents
│   ├── code-genie.agent.yaml
│   ├── code-genie.md
│   ├── dai-ha.agent.yaml
│   ├── dai-ha.md
│   ├── data-expert.agent.yaml
│   ├── data-expert.md
│   ├── design-maestro.agent.yaml
│   ├── design-maestro.md
│   ├── external-relations-specialist.md
│   ├── market-insight.agent.yaml
│   ├── market-insight.md
│   ├── operations-specialist.md
│   ├── public-sector-mentor.agent.yaml
│   └── public-sector-mentor.md
├── config.yaml
├── data
│   └── AIQA-MHP_ModernHackathonPlaybook.md
├── tasks
│   ├── code-genie-best-practices.xml
│   ├── code-genie-debug-code.xml
│   ├── code-genie-generate-code.xml
│   ├── code-genie-refactor-code.xml
│   ├── code-genie-tech-guidance.xml
│   ├── dai-ha-analyze-data.xml
│   ├── dai-ha-decompose-problem.xml
│   ├── dai-ha-design-prototype.xml
│   ├── dai-ha-generate-code.xml
│   ├── dai-ha-prepare-docs.xml
│   ├── dai-ha-recommend-tech.xml
│   ├── dai-ha-risk-assessment.xml
│   ├── data-expert-analyze-opendata.xml
│   ├── data-expert-create-dataset.xml
│   ├── data-expert-data-governance.xml
│   ├── data-expert-data-storytelling.xml
│   ├── data-expert-prepare-data.xml
│   ├── data-expert-statistical-analysis.xml
│   ├── data-expert-visualize-data.xml
│   ├── design-maestro-accessibility-review.xml
│   ├── design-maestro-create-prototype.xml
│   ├── design-maestro-design-principles.xml
│   ├── design-maestro-design-ui.xml
│   ├── design-maestro-information-architecture.xml
│   ├── design-maestro-user-test.xml
│   ├── design-maestro-visual-feedback.xml
│   ├── external-relations-specialist-brand-messaging.xml
│   ├── external-relations-specialist-external-comm.xml
│   ├── external-relations-specialist-generate-external-report.xml
│   ├── external-relations-specialist-presentation-coaching.xml
│   ├── external-relations-specialist-stakeholder-coord.xml
│   ├── market-insight-business-model.xml
│   ├── market-insight-competitor-analysis.xml
│   ├── market-insight-go-to-market-strategy.xml
│   ├── market-insight-market-research.xml
│   ├── market-insight-pricing-strategy.xml
│   ├── market-insight-user-validation.xml
│   ├── market-insight-value-proposition.xml
│   ├── operations-specialist-generate-internal-report.xml
│   ├── operations-specialist-incident-response.xml
│   ├── operations-specialist-qa-audit.xml
│   ├── operations-specialist-system-monitor.xml
│   ├── operations-specialist-test-plan.xml
│   ├── public-sector-mentor-cross-agency-coord.xml
│   ├── public-sector-mentor-funding-grants.xml
│   ├── public-sector-mentor-gov-structure.xml
│   ├── public-sector-mentor-legal-compliance.xml
│   ├── public-sector-mentor-policy-interpret.xml
│   ├── public-sector-mentor-procurement-processes.xml
│   └── public-sector-mentor-public-value.xml
├── templates
└── workflows
    ├── current_wf
    ├── full-hackathon-workflow
    ├── hackathon-kickoff
    ├── hackathon-retrospective
    ├── idea-generation
    ├── presentation-prep
    └── solution-development

```

## 配置

本模組的配置檔案位於 `bmad/mhp/config.yaml`。

主要設定：無 (No user-configurable fields)



## gov_openapi_agent 啟用與使用範例

### 啟用 gov_openapi_agent

1.  **複製專案**：
    ```bash
    git clone https://github.com/wuulong/gov_openapi_agent
    ```
2.  **啟用 gov_opendata_platform**：
    ```bash
    cd gov_opendata_platform && uvicorn gov_opendata_platform:app --reload --port 8801
    ```
    *   可能需要編輯 `config/agent_config.yaml`，確保 `enable_platform` 中包含 `gov_opendata_platform_api`：
        ```yaml
        enable_platform:
          - gov_opendata_platform_api
        ```
3.  **啟用 gov_openapi_agent mcp server**：
    *   編輯 `.gemini/settings.json`，新增 `mcpServers` 設定：
        ```json
         "mcpServers": {
            "gov-openapi-agent-mcp":{
              "url":"http://127.0.0.1:8800/sse"
            }
          },
        ```
    *   啟動伺服器：
        ```bash
        python agent_mcp_server.py --transport sse --port 8800
        ```

### 使用 gov_openapi_agent - 方法1

```
use gov-openapi-agent-mcp: 請問有什麼跟水庫相關的資料集
 @docs/file_based_open_data_method.md
請問寶二水庫目前的水位是多少
```

### 使用 gov_openapi_agent - 方法2

```
/bmad-task-mhp-data-expert-analyze-opendata 請問有什麼跟水庫相關的資料集
/bmad-task-mhp-data-expert-analyze-opendata 請問寶二水庫目前的水位是多少
- 先找水庫相關資料集
- 水庫水情資料
```

