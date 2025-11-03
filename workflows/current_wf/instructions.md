# Current Workflow Instructions

<critical>The workflow execution engine is governed by: {project-root}/bmad/core/tasks/workflow.xml</critical>
<critical>You MUST have already loaded and processed: {project-root}/workflows/current_wf/workflow.yaml</critical>
<critical>Communicate in {communication_language} throughout the workflow process</critical>

<workflow>

<step n="1" goal="執行文件索引任務">
  <action>現在，我們將執行文件索引任務，掃描指定目錄並生成 index.md。</action>
  <invoke-task task="bmad/core/tasks/index-docs.xml"/>
</step>

</workflow>