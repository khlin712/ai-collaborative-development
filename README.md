# AI Collaborative Development

一套把 AI 程式開發納入獨立審查、實際驗證與 RCA 回饋的 Codex skill。

## 內容

- `skills/ai-collaborative-development/SKILL.md`：skill 入口與使用規則
- `skills/ai-collaborative-development/references/reviewers.md`：Code reviewer、Report reviewer、RCA 官方 prompt
- `skills/ai-collaborative-development/references/workflow.md`：完整開發流程與品質關卡
- `skills/ai-collaborative-development/references/rca-watchdog.md`：RCA 病例庫與 Watchdog 設計
- `ai-collaborative-development-infographic.png`：快速說明圖

## 使用

在 Codex 對話中使用：

```text
使用 $ai-collaborative-development。

目標：我要完成＿＿＿＿。
使用者：＿＿＿＿。
驗收條件：
1. ＿＿＿＿
2. ＿＿＿＿

請先分析需求與可行性，不要先宣稱完成。
```

完整 reviewer prompt 請直接參考 `references/reviewers.md`，不要自行改寫官方檢查條件。

