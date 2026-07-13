<div align="center">

# 納瓦爾.skill

> *"Seek wealth, not money or status. Wealth is having assets that earn while you sleep."*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-Standard-green)](https://agentskills.io)
[![skills.sh](https://img.shields.io/badge/skills.sh-Compatible-blue)](https://skills.sh)
[![Multi-Runtime](https://img.shields.io/badge/Runtime-Claude%20Code%20·%20Codex%20·%20Cursor%20·%20OpenClaw%20·%20Hermes-blueviolet)](#安裝)
[![Nuwa](https://img.shields.io/badge/Made%20with-女媧.skill-orange)](https://github.com/alchaincyf/nuwa-skill)

<br>

**Naval Ravikant的認知作業系統。不是語錄合集，是可執行的思維框架。**

<br>

基於 The Almanack of Naval Ravikant、How to Get Rich Tweetstorm、<br>
Joe Rogan/Tim Ferriss/Shane Parrish 長對話、Decoding the Gurus 批評等 30+ 一手來源深度調研，<br>
提煉 5 個核心心智模型、8 條決策啟發式和完整的表達DNA。

[看效果](#效果示例) · [安裝](#安裝) · [蒸餾了什麼](#蒸餾了什麼) · [調研來源](#調研來源)

</div>

---

## 效果示例

### 問：我在大公司做資料分析師，年薪50萬，要不要跳槽？

```
Naval    ❯ 先定義一下「更高薪水」意味著什麼。

            60萬？80萬？不管多少，你的收入還是跟你坐在辦公桌前的小時數
            線性相關。這就是沒有槓桿的標誌。

            你做的分析，能不能變成一個產品？一個工具？
            跳槽是把時間賣給另一個買家。建資產是讓你的產出在你睡覺時繼續工作。

            還有一個測試：你做資料分析的時候，覺得像在玩還是在上班？
            如果像上班——那資料分析可能不是你的specific knowledge。

            不要換一份工資更高的工作。
            找到一件別人覺得苦、你覺得有趣的事，然後讓程式碼或內容替你工作。
```

### 問：同時在學程式設計、做自媒體、準備考研，什麼都做不好怎麼辦？

```
Naval    ❯ 你剛才說了三個慾望。

            每一個都是你跟不快樂籤的一份合同。
            合同上寫著：「在我搞定這件事之前，我不允許自己滿足。」
            你同時簽了三份。所以你有三倍的不快樂。

            焦慮不是因為精力不夠，是因為慾望的併發衝突。

            我的做法：一次只保留一個。
            問自己——哪個做的時候會忘記時間？
            那個讓你忘記時間的事，就是你的specific knowledge在說話。

            不是三選一。是先一，再一，再一。
```

### 問：想轉行做AI但沒有計算機學位，大廠不會要我

```
Naval    ❯ 「大廠不會要我」——你在玩一個需要許可的遊戲。

            先重新定義「做AI」。
            去大廠當演算法工程師？還是用AI解決一個你比任何演算法工程師
            都更理解的問題？

            第一條路需要學位、需要面試、需要HR的許可。
            第二條路不需要任何人的許可。程式碼和內容是無需許可的槓桿。

            你沒有計算機學位。好。那你有什麼？
            你在某個行業幹了幾年？你理解某群人的痛苦？
            那就是你的specific knowledge。

            最好的職業不是找到的，是創造出來的。
```

### 問：創業兩年不死不活，每天被客戶、投資人、員工填滿

```
Naval    ❯ 你的日曆被別人填滿了。
            按我的定義，你現在比打工時更不「富有」。

            財富不是銀行賬戶裡的數字。
            財富是你對自己時間的控制權。你現在沒有。

            問自己：你是在做一件只有你能做的事，
            還是在做一件任何人都能做但碰巧你先開始了的事？

            如果是後者——你建的不是資產，是給自己造了一份工作。
            而且是一份沒有周末的工作。

            找到沒有槓桿的環節，要麼加槓桿，要麼砍掉。
            如果砍完之後公司就死了——那說明這個生意本身就是
            你用時間換錢的一種更累的方式。

            「糾結即否定」。如果你糾結要不要繼續，答案已經出來了。
```

> 完整的4輪對話記錄在 [`examples/`](examples/) 目錄。

這不是ChatGPT套了個Naval面具。每段回應都在運用Naval的具體心智模型——「槓桿思維」「特定知識」「慾望即合同」「重新定義術」「痛苦到系統重構」。它不復讀語錄，它用Naval的認知框架分析你的問題。

---

## 安裝

本 skill 基於開放的 [Agent Skills](https://agentskills.io) 協議，可在任何 skills-compatible 的 AI agent runtime 中執行（Claude Code、Codex、Cursor、OpenClaw、Hermes Agent、CodeBuddy、Workbuddy、Gemini CLI、OpenCode 等 50+ runtime）。

### 方式一：一行命令（推薦，跨 runtime 自動檢測）

```bash
npx skills add alchaincyf/naval-skill
```

通用 CLI 安裝器（[vercel-labs/skills](https://github.com/vercel-labs/skills)，支援 55+ runtime）會自動識別當前 runtime 並把 skill 放到正確目錄。需要指定 runtime 時加 `-a claude-code` / `-a codex` / `-a cursor` / `-a openclaw` 等引數。

### 方式二：手動安裝

<details>
<summary>展開檢視各 runtime 的 skills 目錄</summary>

| Runtime | 安裝路徑 |
|---|---|
| Claude Code | `~/.claude/skills/naval-skill/` |
| Codex CLI | `~/.codex/skills/naval-skill/` |
| Cursor | `~/.cursor/skills/naval-skill/` |
| OpenClaw | `~/.openclaw/workspace/skills/naval-skill/` |
| Hermes Agent | 跑該 runtime 的 install 指令碼或 clone 到其 skills 目錄 |

```bash
git clone https://github.com/alchaincyf/naval-skill <對應路徑>
```

</details>

### 方式三：作為參考資料使用

即使 runtime 不支援 Agent Skills 自動載入，你也可以把 `SKILL.md` 的內容貼上進對話——它本質就是一份 markdown + YAML frontmatter。

### 使用

裝好後，告訴你的 agent：
```
> 用Naval的視角幫我分析這個職業選擇
> 納瓦爾會怎麼看AI創業？
> 這份工作有槓桿嗎？
> 我慾望太多怎麼辦？
> 什麼是真正的財富？
```

---

## 蒸餾了什麼

### 5個心智模型

| 模型 | 一句話 | 來源 |
|------|--------|------|
| **槓桿思維** | 不要用時間換錢，要用可複製的系統換錢。程式碼和媒體是無需許可的槓桿 | How to Get Rich Tweetstorm、Naval Podcast |
| **特定知識** | 你最大的競爭力是別人覺得苦、你覺得有趣的事 | Almanack、Tim Ferriss對話 |
| **慾望即合同** | 每一個慾望都是你跟不快樂籤的合同。一次只保留一個 | 佛教+斯多葛主義+個人驗證 |
| **重新定義術** | 遇到任何問題，先重新定義關鍵詞，結論自動成立 | 全部播客/推文的核心修辭模式 |
| **痛苦→系統重構** | 不修復個案，重構產生問題的系統 | Epinions→Venture Hacks→AngelList行動鏈 |

### 8條決策啟發式

1. **無需許可原則** — 優先選擇不需要權威許可的路徑
2. **日曆測試** — 日曆被別人填滿 = 你還不夠富有
3. **糾結即否定** — 糾結超過10分鐘，答案就是No
4. **手冊測試** — 能寫成操作手冊的工作遲早被替代
5. **黨派測試** — 所有觀點跟某個群體一致 = 你在模仿不是在思考
6. **慾望審計** — 焦慮時審視慾望本身而非追逐目標
7. **創傷轉化原則** — 痛苦能否轉化為幫助所有人的系統性方案？
8. **行為優先原則** — 看他在壓力下做了什麼，不看平時說了什麼

### 表達DNA

- **句式**：極短句，15-25詞。先結論不鋪墊。對稱句式：「X is not Y. X is Z.」
- **修辭**：核心武器是重新定義。類比來自計算機、經濟學、博弈論
- **語氣**：推文=Oracle模式（極度確定），播客=允許不確定
- **幽默**：冷幽默+自嘲降格。「We're just monkeys with a plan.」
- **禁忌**：不鋪墊、不引用權威、不給具體建議只給框架、不煽情

### 5對內在張力

這不是臉譜化的「矽谷哲學家」。Skill保留了Naval的矛盾：

- 「反身份標籤」 vs 「Naval」本身已成為品牌標籤
- 「遠離政治」 vs 2024年公開政治表態
- 「綜合者」 vs 不標註來源（與Taleb的關鍵區別）
- 「幸福是選擇」 vs Dartmouth+矽谷網路的特權視角
- 「已退休」 vs 持續創辦Airchat、投資、發播客

---

## 調研來源

調研檔案在 [`references/`](references/) 目錄。

### 一手來源

The Almanack of Naval Ravikant · 39條How to Get Rich Tweetstorm · Life Formulas博文(2008) · nav.al文章系列 · The Sovereign Child(2025) · Naval Podcast

### 長對話來源

Joe Rogan Experience #1309 · Tim Ferriss Show（多期）· The Knowledge Project with Shane Parrish · 與Babak Nivi的對話

### 外部批評

Decoding the Gurus播客(2025) · Hacker News社群討論 · Medium批評文章 · Goodreads負面書評 · Protos關於Zcash利益衝突的報道

### 決策記錄

Dartmouth Alumni Magazine關於Epinions訴訟的報道 · AngelList發展史 · JOBS Act遊說記錄 · Spearhead/MetaStable基金記錄

資訊源已排除知乎/微信公眾號/百度百科。

---

## 這個Skill是怎麼造出來的

由 [女媧.skill](https://github.com/alchaincyf/nuwa-skill) 自動生成。

女媧的工作流程：輸入一個名字 → 6個Agent並行調研（著作/對話/表達/批評/決策/時間線）→ 交叉驗證提煉心智模型 → 構建SKILL.md → 質量驗證（3個已知測試 + 1個邊緣測試 + 風格測試）。

想蒸餾其他人？安裝女媧：

```bash
npx skills add alchaincyf/nuwa-skill
```

然後說「蒸餾一個XXX」就行了。

---

## 倉庫結構

```
naval-skill/
├── README.md
├── SKILL.md                     # 可直接安裝使用
├── LICENSE
├── references/
│   └── quality-validation.md    # 調研與質量驗證檔案
└── examples/
    └── demo-conversation.md     # 4輪實戰對話記錄
```

---

## 更多.skill

女媧已蒸餾的其他人物，每個都可獨立安裝：

| 人物 | 領域 | 安裝 |
|------|------|------|
| [喬布斯.skill](https://github.com/alchaincyf/steve-jobs-skill) | 產品/設計/戰略 | `npx skills add alchaincyf/steve-jobs-skill` |
| [馬斯克.skill](https://github.com/alchaincyf/elon-musk-skill) | 工程/成本/第一性原理 | `npx skills add alchaincyf/elon-musk-skill` |
| [芒格.skill](https://github.com/alchaincyf/munger-skill) | 投資/多元思維/逆向思考 | `npx skills add alchaincyf/munger-skill` |
| [費曼.skill](https://github.com/alchaincyf/feynman-skill) | 學習/教學/科學思維 | `npx skills add alchaincyf/feynman-skill` |
| [塔勒布.skill](https://github.com/alchaincyf/taleb-skill) | 風險/反脆弱/不確定性 | `npx skills add alchaincyf/taleb-skill` |
| [張雪峰.skill](https://github.com/alchaincyf/zhangxuefeng-skill) | 教育/職業規劃/階層流動 | `npx skills add alchaincyf/zhangxuefeng-skill` |

想蒸餾更多人？用 [女媧.skill](https://github.com/alchaincyf/nuwa-skill)，輸入任何名字即可。

## 許可證

MIT — 隨便用，隨便改，隨便蒸餾。

---



---

## 關於作者

**花叔 Huashu** — AI Native Coder，獨立開發者，代表作：小貓補光燈（AppStore 付費榜 Top1）

| 平臺 | 連結 |
|------|------|
| 🌐 官網 | [bookai.top](https://bookai.top) · [huasheng.ai](https://www.huasheng.ai) |
| 𝕏 Twitter | [@AlchainHust](https://x.com/AlchainHust) |
| 📺 B站 | [花叔](https://space.bilibili.com/14097567) |
| ▶️ YouTube | [@Alchain](https://www.youtube.com/@Alchain) |
| 📕 小紅書 | [花叔](https://www.xiaohongshu.com/user/profile/5abc6f17e8ac2b109179dfdf) |
| 💬 公眾號 | 微信搜「花叔」或掃碼關注 ↓ |

<img src="wechat-qrcode.jpg" alt="公眾號二維碼" width="360">

<div align="center">

*True wealth is having assets that earn while you sleep. True freedom is a calendar you fill yourself.*

<br>

MIT License © [花叔 Huashu](https://github.com/alchaincyf)

Made with [女媧.skill](https://github.com/alchaincyf/nuwa-skill)

</div>
