# Hackathon Retrospective Workflow Instructions

<critical>The workflow execution engine is governed by: {project-root}/bmad/core/tasks/workflow.xml</critical>
<critical>You MUST have already loaded and processed: {project-root}/bmad/mhp/workflows/hackathon-retrospective/workflow.yaml</critical>
<critical>Communicate in {communication_language} throughout the workflow process</critical>

<workflow>

<step n="1" goal="設定回顧目標與安全空間">
  <action>英雄，歡迎來到黑客松回顧環節！讓我們首先明確本次回顧的目標，並建立一個開放、誠實、無指責的討論環境。

  請引導團隊討論以下問題：
  - 我們希望透過這次回顧達成什麼？（例如：改進未來合作、解決遺留問題、慶祝成功）
  - 如何確保每位成員都能自在地分享想法和感受？
  - 我們將秉持哪些原則來進行這次回顧？

  請強調「安全空間」的重要性，鼓勵團隊成員專注於學習和成長，而非指責。
  </action>
  <template-output>retrospective_goal_safespace</template-output>
</step>

<step n="2" goal="收集數據與事件">
  <action>目標已定，現在讓我們回顧黑客松期間發生的關鍵事件、挑戰和成功。請收集客觀數據和團隊成員的個人感受。

  請引導團隊成員分享：
  - 「做得好的地方」：哪些方面超出了預期，帶來了積極的結果？
  - 「可以改進的地方」：哪些方面沒有達到預期，或可以做得更好？
  - 「遇到的阻礙」：哪些外部或內部因素阻礙了團隊的進展？
  - 「學到的新事物」：個人或團隊在技術、協作或領域知識方面有何收穫？

  請確保每位成員都有機會發言，並記錄所有分享的內容。
  </action>
  <template-output>data_event_collection</template_output>
</step>

<step n="3" goal="分析原因與洞察">
  <action>我們已經收集了豐富的資訊。現在，讓我們深入分析這些事件背後的原因，挖掘根本問題和成功因素，形成具體洞察。

  請引導團隊使用「五個為什麼」或其他分析工具，對每個「可以改進的地方」和「遇到的阻礙」進行追問，直到找出根本原因。
  同時，也請分析「做得好的地方」背後的成功因素。

  請協助團隊將這些分析轉化為清晰的洞察，避免表面歸因，並鼓勵批判性思考。
  </action>
  <template-output>cause_analysis_insights</template_output>
</step>

<step n="4" goal="制定行動計畫">
  <action>洞察已形成，現在是時候將這些寶貴的學習轉化為具體、可執行的改進行動計畫了！

  請引導團隊討論：
  - 針對每個洞察，我們可以採取哪些具體的行動？
  - 這些行動的優先順序是什麼？
  - 誰將負責執行這些行動？
  - 預計何時完成？
  - 如何衡量這些行動的成效？

  請協助團隊將行動計畫具體化為 SMART 目標（Specific, Measurable, Achievable, Relevant, Time-bound），並確保責任到人。
  </action>
  <template-output>action_plan</template_output>
</step>

<step n="5" goal="回顧總結與慶祝">
  <action>英雄們，我們已經完成了這次富有成效的回顧！現在，讓我們總結成果，並慶祝團隊的努力與成長。

  請引導團隊：
  - 確認所有行動計畫都已清晰記錄並達成共識。
  - 每位成員分享一個從這次回顧中獲得的最大收穫。
  - 互相表達感謝，肯定彼此的貢獻。
  - 簡短慶祝團隊在黑客松中的努力和成就。

  請確保回顧在積極和充滿希望的氛圍中結束，為團隊的未來合作注入正能量。
  </action>
  <template-output>retrospective_summary_celebration</template_output>
</step>

</workflow>
