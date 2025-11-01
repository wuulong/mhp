# Solution Development Workflow Instructions

<critical>The workflow execution engine is governed by: {project-root}/bmad/core/tasks/workflow.xml</critical>
<critical>You MUST have already loaded and processed: {project-root}/bmad/mhp/workflows/solution-development/workflow.yaml</critical>
<critical>Communicate in {communication_language} throughout the workflow process</critical>

<workflow>

<step n="1" goal="理解解決方案願景與範圍">
  <action>英雄，讓我們共同確認解決方案的願景與範圍。這將確保團隊對開發目標有共同的理解。

  請引導團隊討論並確認以下關鍵點：
  - 解決方案的核心功能是什麼？
  - 預期解決什麼問題？
  - 誰是主要使用者？
  - 成功的衡量標準是什麼？

  在每個關鍵點後，請確認團隊是否達成共識。如果存在分歧，請引導討論以達成一致。
  </action>
  <template-output>solution_vision_scope</template-output>
</step>

<step n="2" goal="設計與規劃迭代">
  <action>願景已定，現在讓我們將解決方案拆解為可管理的迭代，並進行初步設計。

  請引導團隊討論以下問題：
  - 第一個迭代（例如 MVP）應包含哪些核心功能？
  - 每個迭代的目標是什麼？
  - 建議採用哪些設計模式或架構原則？
  - 如何規劃每個迭代的時間表和資源分配？

  在每個討論點後，請確認團隊的決策，並記錄關鍵的設計選擇和迭代規劃。
  </action>
  <template-output>iteration_design_planning</template-output>
</step>

<step n="3" goal="實作與開發指導">
  <action>設計與規劃完成，現在進入實作階段。我將提供必要的指導與支援。

  請引導團隊討論以下方面：
  - 選擇的技術棧是否合適？
  - 開發過程中可能遇到的主要技術挑戰是什麼？
  - 如何進行程式碼審查以確保品質？
  - 需要哪些工具來輔助開發和除錯？

  在開發過程中，請根據團隊遇到的具體問題，提供即時的技術建議，並協助他們解決困難。
  </action>
  <template-output>implementation_guidance</template-output>
</step>

<step n="4" goal="測試與品質保證">
  <action>程式碼已初步完成，現在是時候確保其品質與穩定性了。

  請引導團隊討論並確認以下測試策略：
  - 應進行哪些類型的測試（單元測試、整合測試、使用者驗收測試等）？
  - 如何設計有效的測試案例？
  - 如何追蹤和管理缺陷？
  - 成功的測試標準是什麼？

  請協助團隊分析測試結果，並確保所有關鍵缺陷都已解決。
  </action>
  <template-output>testing_qa</template_output>
</step>

<step n="5" goal="優化與迭代回顧">
  <action>一個迭代的開發與測試已完成。現在，讓我們進行優化並規劃下一個階段。

  請引導團隊進行回顧討論：
  - 這個迭代中，哪些方面做得好？
  - 哪些方面可以改進？
  - 根據測試結果和潛在的使用者回饋，需要進行哪些優化？
  - 下一個迭代的重點和目標是什麼？

  請協助團隊制定具體的優化方案和下一個迭代的計畫。
  </action>
  <template-output>optimization_retrospective</template_output>
</step>

</workflow>
