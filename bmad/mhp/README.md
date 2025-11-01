# Modern Hackathon Playbook (mhp)

本模組旨在為黑客松參賽團隊提供一套全面的 Agentic AI 賦能技法，協助團隊在有限時間與資源下，高效拆解問題、快速驗證概念，並產出具影響力的解決方案。

## 概述

本模組提供：

*   **7 個代理程式**：涵蓋協調、程式碼、設計、市場、資料、公部門和溝通等專業領域。
*   **4 個工作流程**：支援黑客松從啟動到回顧的各個階段。

## 安裝

```bash
bmad install mhp
```

## 組件

### 代理程式 (7 個)

*   **代哈 (Dai-Ha)**：高效任務協調者與策略指導者。
*   **程式碼精靈 (Code Genie)**：專注於程式碼實現、除錯、最佳實踐和技術指導。
*   **設計大師 (Design Maestro)**：專注於 UI/UX 設計、原型視覺化、使用者測試和設計原則。
*   **市場洞察者 (Market Insight)**：專注於市場研究、競爭分析、用戶需求驗證和商業模式建議。
*   **資料專家 (Data Expert)**：專長是開放資料的分析、使用、資料整備技巧、資料創造與建構。
*   **公部門導師 (Public Sector Mentor)**：熟悉公部門運作、精通政府架構、熟悉法規。
*   **發言人 (Spokesperson)**：負責報告、測試、系統維護，以及對外的溝通與協調。

### 工作流程 (4 個)

*   **黑客松啟動工作流程 (Hackathon Kickoff Workflow)**：引導團隊進行問題定義、初步腦力激盪、設計思考、團隊角色分配和專案規劃。
*   **解決方案開發工作流程 (Solution Development Workflow)**：指導團隊進行迭代開發，包括設計、實現、測試和優化。
*   **成果展示準備工作流程 (Presentation Prep Workflow)**：協助團隊準備具說服力的簡報、演示稿和技術文件。
*   **黑客松回顧工作流程 (Hackathon Retrospective Workflow)**：引導團隊回顧黑客松過程，總結經驗教訓，規劃未來改進。

### 任務 (0 個)

目前沒有定義獨立的任務。

## 快速入門

1.  **載入主要代理程式**：

    ```
    agent dai-ha
    ```

2.  **查看可用指令**：

    ```
    *help
    ```

3.  **運行主要工作流程**：
    ```
    workflow /bmad/mhp/workflows/hackathon-kickoff/
    ```

## 模組結構

```
mhp/
├── agents/
│   └── dai-ha.agent.yaml
├── workflows/
│   └── hackathon-kickoff/
│       ├── checklist.md
│       ├── data/
│       ├── instructions.md
│       ├── README.md
│       └── workflow.yaml
├── tasks/
├── templates/
├── data/
├── _module-installer/
│   └── install-config.yaml
└── README.md
```

## 配置

本模組的配置檔案位於 `bmad/mhp/config.yaml`。

主要設定：無 (No user-configurable fields)

## 範例

### 範例 1：黑客松啟動

透過 `hackathon-kickoff` 工作流程，團隊可以系統性地啟動黑客松專案，從問題定義到初步規劃。

## 開發路線圖

- [ ] 建立「解決方案開發工作流程」
- [ ] 建立「成果展示準備工作流程」
- [ ] 建立「黑客松回顧工作流程」
- [ ] 建立所有規劃的專家代理程式

## 貢獻

若要擴展此模組：

1.  使用 `create-agent` 工作流程添加新的代理程式。
2.  使用 `create-workflow` 工作流程添加新的工作流程。
3.  透過 Pull Request 提交改進。

## 作者

由 BMad 於 2025年11月1日 星期六 建立。
