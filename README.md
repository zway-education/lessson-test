# 台灣展威文化教育 — 學習測評問卷（前台）

公開給學生 / 家長線上填寫問卷的網站。

## 檔案

- `index.html` — 主程式（驗證 → 角色 → 填題 → 確認 → 送出 → 簡版報告）
- `config.js` — ZW 全域設定（已內嵌於 index.html，這裡備份）

## 部署

直接 push 到 `lessson-test` repo → GitHub Pages 自動發佈到：

https://zway-education.github.io/lessson-test/

## 注意

- 不要把 `測評報告_圖表優化版.html` 放進來（學生不該看到完整報告）
- 不要把 `admin.html` 放進來（後台檔案在另一個 repo）
- 學生只看得到「填寫問卷」介面；右上「🔒 後台」連結會跳到管理後台網址，但沒帳號進不去
