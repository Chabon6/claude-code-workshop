# Claude Code Workshop

90 分鐘 Claude Code 工作實戰教材。

## Course flow

教材目前按照這條主線安排：

**Skill 基礎 → Case A（簡單）→ 專業判斷 → Case B（判斷密集）→ Hands-on → Test & Improve → Automation → Case C（自動化）→ Wrap-up**

三個案例分別示範：

- **Case A · Simple**：把重複格式與邊界規則做成 Skill。
- **Case B · Judgment-heavy**：把專業判斷、取捨與停止條件存進 Skill。
- **Case C · Automated**：把穩定的 Skill 接上 trigger，並討論無人值守執行的風險。

## Website

GitHub Pages：

`https://chabon6.github.io/claude-code-workshop/`

網站入口為 `index.html`。桌機與手機分別使用：

- `styles.css`
- `mobile.css`

頁面已加入：

```html
<meta name="robots" content="noindex,nofollow,noarchive">
```

這只是在要求搜尋引擎不要索引，**不是存取權限控制**。網站是否公開、能否限制存取，仍以目前 GitHub Pages 的 repository / organization / plan 設定為準。

## Demo Skill

Case A 的可執行示範 Skill 位於：

`.claude/skills/meeting-follow-up/SKILL.md`

教材中的示範輸入與示範輸出，應和這個 Skill 的實際行為保持一致。修改其中一邊時，請同步檢查另一邊。

## Content principles

教材內文以忙碌、具基本數位工具經驗的職場工作者為主要讀者，並參考 ISO 24495 plain-language 原則整理：

- 重點先行
- 一段一個主題
- 必要術語第一次出現時解釋
- 能用中文說清楚時，避免不必要的中英夾雜
- 步驟與可執行事項寫清楚

文字優化參考：`https://github.com/danyuchn/iso-24495-skill/`（非 ISO 官方專案）。

## Maintenance checklist

正式授課前請重新確認 Anthropic / Claude Code 官方文件，尤其是：

- Skills 與 Skill Creator
- Routines
- Desktop scheduled tasks
- `/loop` / session-scoped scheduled tasks
- 任何課堂會現場操作的安裝或排程指令

產品功能、限制與方案可用性可能更新。
