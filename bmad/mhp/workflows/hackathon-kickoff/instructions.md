# Hackathon Kickoff Workflow Instructions

<critical>The workflow execution engine is governed by: {project-root}/bmad/core/tasks/workflow.xml</critical>
<critical>You MUST have already loaded and processed: {project-root}/bmad/mhp/workflows/hackathon-kickoff/workflow.yaml</critical>
<critical>Communicate in {communication_language} throughout the workflow process</critical>

<workflow>

<step n="1" goal="理解黑客松挑戰">
  <action>英雄，讓我們深入探索這次黑客松的挑戰！

  請引導團隊成員，透過開放性討論，共同挖掘問題的根源、其對目標受眾的影響，以及其中蘊藏的潛在機會。

  鼓勵團隊思考：
  - 我們要解決的核心問題是什麼？
  - 這個問題對誰造成影響？
  - 為什麼這個問題值得被解決？
  - 解決這個問題可能帶來哪些積極的變化？

  作為引導者，請適應團隊的討論方向，並在必要時提出引導性問題，確保對挑戰有全面而深入的理解。
  </action>
  <template-output>challenge_understanding</template-output>
</step>

<step n="2" goal="初步概念發想與腦力激盪">
  <action>太棒了！現在我們對挑戰有了清晰的認識。接下來，讓我們進入創意發想階段！

  請引導團隊進行一場高效的腦力激盪，鼓勵所有成員自由提出任何解決方案的概念，無論多麼大膽或初步。

  作為腦力激盪的引導者，請確保：
  - 鼓勵數量而非品質：越多想法越好。
  - 暫緩判斷：不對任何想法進行批評或評估。
  - 建立連結：協助團隊成員在不同想法之間建立聯繫，激發更多靈感。
  - 整理分類：初步協助團隊將發想出的概念進行整理和分類。

  目標是生成多樣化的解決方案概念，為後續的設計思考奠定基礎。
  </action>
  <template-output>brainstormed_concepts</template-output>
</step>

<step n="3" goal="設計思考與解決方案聚焦">
  <action>我們已經擁有了豐富的創意概念！現在是時候透過設計思考，將這些想法轉化為具體的解決方案方向。

  請引導團隊：
  - 進行使用者情境分析：想像目標使用者如何與解決方案互動。
  - 識別痛點：從使用者的角度，找出當前方案或情境中的主要困難。
  - 評估方案優劣：協助團隊評估不同概念的優勢、劣勢、可行性和潛在影響。
  - 聚焦核心：引導團隊選擇 1-2 個最具潛力且符合黑客松目標的解決方案方向。

  作為引導者，請確保團隊的討論聚焦於實際問題和使用者需求，並協助他們做出有根據的選擇。
  </action>
  <template-output>focused_solutions</template_output>
</step>

<step n="4" goal="團隊角色與職責分配">
  <action>解決方案方向已定，現在讓我們組建一支無堅不摧的團隊！

  請引導團隊成員：
  - 識別各自的技能與專長：包括技術、設計、溝通、專案管理等。
  - 討論黑客松期間所需的關鍵角色：例如開發者、設計師、數據分析師、發言人等。
  - 進行角色分配：根據成員的興趣和專長，將他們分配到最適合的角色。
  - 明確職責：確保每個角色都有清晰的職責範圍和預期貢獻。

  作為引導者，請促進團隊成員之間的溝通，確保每個人都對自己的角色和團隊的協作方式有清晰的理解。
  </action>
  <template-output>team_roles</template-output>
</step>

<step n="5" goal="專案初步規劃與里程碑設定">
  <action>團隊已就位，目標清晰！最後一步，讓我們為黑客松期間的衝刺做好準備。

  請引導團隊：
  - 制定初步的專案計畫：包括主要任務、預計時間分配。
  - 設定關鍵里程碑：定義黑客松期間的短期目標和交付物。
  - 識別潛在風險：討論可能遇到的挑戰及應對策略。
  - 建立溝通機制：確定團隊內部如何進行日常溝通和進度更新。

  作為引導者，請協助團隊建立一個實際可行且具有彈性的計畫，為他們在黑客松中的高效執行提供堅實的基礎。
  </action>
  <template-output>project_plan</template-output>
</step>

</workflow>
