# 別再當 Claude 的輸送帶：Felix Rieseberg 談 2024 年之後的用法

Silicon Valley Girl 頻道在 2026 年 10 月 20 日上架訪談〈Claude Engineering Lead: "Stop Using Claude Like It's 2024"〉，講者是 Felix Rieseberg（Anthropic，自述曾領導 Claude.ai、Cowork 與 Claude Code 桌面版的工程）。本導讀整理他談的做法：怎麼把整個目標而不是單一任務交給 Claude、怎麼另開工作階段挑錯、「你是專家」為什麼不夠、怎麼不當團隊的瓶頸；並把他提到的產品（Claude Tag、新版 Projects、Cowork 內建瀏覽器等）和 Anthropic 官方文件對照，標明哪些已確認、哪些只是他的說法、一般使用者現在能不能用。

## 200字介紹

Felix Rieseberg 說，只拿 Claude 摘要信件、改語氣，等於沒用到新一代模型。他的做法是讓 Claude 看完整資料（例如全部當機紀錄）再自己判斷，另開工作階段讓多個「攻擊者」挑錯、再由裁判篩選，並把自己給過的回饋濃縮成審查原則。本導讀逐段對照他的說法與 Anthropic 官方文件：Claude Tag、新版 Projects、內建瀏覽器都有方案與平台限制；「一週半做出 Cowork」其實建立在約一年半的原型上；Opus 5.5 在 3D 與影片的「大躍進」查不到官方對應。文末整理六件可以馬上試的事，並標明哪些是 AI 製作時的取捨與限制。

> **製作聲明**：本導讀的分析與撰稿由 AI 模型完成，不是人類分析，也未經人工逐句校稿（統籌：Claude Code／Claude Sonnet 5.5；翻譯：Sonnet 初譯、Opus 審校；研究、撰稿、審稿：Claude Opus；查證：Codex、Claude Code、agy〔Gemini 3.8 Flash；原用的 Gemini 4 Argon 額度用完〕；插圖：Codex imagegen 與腳本繪製 SVG）。分工見導讀文末〈製作說明〉。

## 檔案

| 檔案 | 說明 |
|---|---|
| `index.html` | 導讀網頁（單檔，直接用瀏覽器開啟；圖片用相對路徑） |
| `translation-zh.html` | 訪談逐字繁中譯文（非官方，依 YouTube 機器字幕由 AI 模型翻譯與審校，未經人工校稿、未對照原音） |
| `claude-engineering-lead-stop-using-claude-like-2024.md` | 導讀 Markdown 原稿 |
| `images/` | 封面（橫式、直式各一版）、8 張輔助圖（SVG，桌面與手機各一版） |
| `share_post.md` | 社群分享文 |

## 原始素材

- 影片：https://www.youtube.com/watch?v=D-SVFneJ_Nk （Silicon Valley Girl，2026-10-20，49:23）
- 逐字稿：YouTube 英文機器字幕（en-orig），不含說話者標記；譯文與導讀中無法判斷說話者之處已標「（說話者不明）」。
- Felix 本人的文章（2026-09-27、2026-10-13）與 Anthropic 官方公告、文件作為對照來源。

## 狀態

已發布（2026-10-24）：https://lushinshang.github.io/claude-engineering-lead-stop-using-claude-like-2024/ 。資料截至 2026-10-24。本導讀為非官方整理，訪談內容版權屬原作者。
