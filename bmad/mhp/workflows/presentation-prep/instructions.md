# Presentation Prep Workflow Instructions

<critical>The workflow execution engine is governed by: {project-root}/bmad/core/tasks/workflow.xml</critical>
<critical>You MUST have already loaded and processed: {project-root}/bmad/mhp/workflows/presentation-prep/workflow.yaml</critical>
<critical>Communicate in {communication_language} throughout the workflow process</critical>

<workflow>

<step n="1" goal="確認展示目標與受眾">
  <action>英雄，讓我們首先明確這次展示的核心目標，以及您的目標受眾是誰。這將是所有準備工作的基石。

  請引導團隊討論並確認以下問題：
  - 這次展示最想達成的目標是什麼？（例如：獲得評審認可、吸引潛在合作夥伴、展示技術可行性）
  - 您的目標受眾是誰？（例如：技術評審、商業評審、一般大眾）
  - 他們的背景知識、關注點和期望是什麼？

  在每個關鍵點後，請確認團隊是否達成共識，並記錄這些資訊，這將有助於後續內容的設計。
  </action>
  <template-output>presentation_goal_audience</template-output>
</step>

<step n="2" goal="內容結構與大綱設計">
  <action>目標與受眾已明確，現在讓我們為您的展示設計一個具邏輯性和說服力的內容結構。

  請引導團隊討論以下方面：
  - 簡報/演示/文件的主要章節或流程應該是什麼？
  - 如何有效地引導受眾從問題意識到解決方案，再到其價值？
  - 每個部分應包含哪些關鍵資訊點？
  - 建議採用哪些常見的結構模式？（例如：問題-解決方案-價值、STAR 原則）

  請協助團隊填充關鍵內容點，並確保整體結構流暢且能有效傳達核心訊息。
  </action>
  <template-output>content_structure_outline</template-output>
</step>

<step n="3" goal="視覺化與演示稿準備">
  <action>內容大綱已定，現在是時候將其轉化為具吸引力的視覺元素和清晰的演示稿了。

  請引導團隊討論以下問題：
  - 如何將複雜的技術概念視覺化？（例如：流程圖、架構圖、數據圖表）
  - 選擇哪些圖片、圖示或配色方案來增強視覺效果？
  - 演示稿的文字應如何精煉，以達到簡潔有力？
  - 如何設計引人入勝的開場和結尾？

  請提供視覺設計原則，並協助團隊選擇合適的元素，確保視覺與內容的完美結合。
  </action>
  <template-output>visuals_slides</template-output>
</step>

<step n="4" goal="技術文件撰寫與審閱">
  <action>除了演示，一份清晰、準確的技術文件同樣重要。現在讓我們專注於技術文件的撰寫與審閱。

  請引導團隊討論以下方面：
  - 技術文件應包含哪些核心內容？（例如：技術架構、實現細節、API 文件、部署指南）
  - 如何確保技術描述的準確性、完整性和易讀性？
  - 建議採用哪些文件標準或格式？
  - 如何進行內部審閱以發現潛在的錯誤或遺漏？

  請協助團隊組織技術細節，並進行語法和邏輯檢查，確保技術文件的專業水準。
  </action>
  <template-output>technical_documentation</template-output>
</step>

<step n="5" goal="演練與回饋">
  <action>所有準備工作已完成，現在是關鍵的演練時刻！透過演練，我們可以發現問題並進行最終優化。

  請引導團隊進行模擬演示：
  - 模擬真實的展示情境，包括時間控制和問答環節。
  - 鼓勵團隊成員互相提供建設性回饋，包括內容、語氣、肢體語言和時間掌握。
  - 識別演示中的薄弱環節或不清晰之處。

  請協助團隊根據回饋進行調整和優化，確保在正式展示時能達到最佳效果。
  </action>
  <template-output>rehearsal_feedback</template-output>
</step>

</workflow>
