<!-- 標題請用 Conventional Commits 格式：<type>(<scope>): <subject>
     （團隊慣例：subject 全小寫、結尾不加句號） -->

## 變更摘要

<!-- 這個 PR 做了什麼、為什麼。 -->

Closes # <!-- 填 linked issue 編號（輸入 # 後可用自動補全）；pr-issue-check 會擋未連結 issue 的 PR -->


## 測試 Runbook

<!--
merge 進 dev 後，issue 會自動走 In Deploy → 佈署 → In QA，QA 工程師依本區塊在 dev env 驗收。
runbook 跟著 code 一起被 review：reviewer 看不懂怎麼驗，就是 runbook 要改。
純文件、CI、重構等無需上機驗收的變更，請填「N/A」並簡述原因。
-->

### 驗收標準

<!-- 怎樣算通過。每條都要可判定（可觀察、可量測），例如：
- [ ] Grafana 可依 project_id / run_id 撈出單次執行的完整 log 軌跡
-->

- [ ]

### 操作流程

<!-- QA 逐步照做的操作，包含入口（URL / 指令）、前置條件、測試資料。例如：
1. 開 `https://grafana.{dev-domain}/dashboards`，進入「run 執行追蹤」
2. 以測試 project_id=... 查詢，確認 ...
-->

1.

## 佈署注意事項

<!-- DevOps 佈署時需要知道的事：DB migration、新環境變數、需重建/重啟的服務、相依 repo 順序。無則填「無」。 -->

無
