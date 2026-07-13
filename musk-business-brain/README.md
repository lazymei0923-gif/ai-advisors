<div align="center">

# 馬斯克.skill

<p align="center">
  <img src="assets/hero.gif" alt="elon-musk-skill Hero Animation" />
  <br/>
  <sub>動畫由 <a href="https://github.com/alchaincyf/huashu-design">huashu-design</a> skill 製作</sub>
</p>

> *"The only rules you have to follow are the laws of physics — everything else is a recommendation."*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-Standard-green)](https://agentskills.io)
[![skills.sh](https://img.shields.io/badge/skills.sh-Compatible-blue)](https://skills.sh)
[![Multi-Runtime](https://img.shields.io/badge/Runtime-Claude%20Code%20·%20Codex%20·%20Cursor%20·%20OpenClaw%20·%20Hermes-blueviolet)](#安裝)
[![Nuwa](https://img.shields.io/badge/Made%20with-女媧.skill-orange)](https://github.com/alchaincyf/nuwa-skill)

<br>

**Elon Musk的認知作業系統。不是語錄合集，是可執行的思維框架。**

<br>

基於 Walter Isaacson 傳記、Joe Rogan/Lex Fridman 長播客、Everyday Astronaut 工廠參觀、<br>
X/Twitter 持續輸出、法庭證詞、SEC 檔案等 30+ 一手來源深度調研，<br>
提煉 5 個核心心智模型、8 條決策啟發式和完整的表達DNA。

[看效果](#效果示例) · [安裝](#安裝) · [蒸餾了什麼](#蒸餾了什麼) · [調研來源](#調研來源)

</div>

---

## 效果示例

### 問：我的SaaS產品月費50美元，利潤越來越薄，怎麼最佳化？

```
馬斯克    ❯ 先算。

            你的50美元裡，基礎設施多少？人力多少？支付抽成多少？
            拆到原材料級別。

            伺服器算力的漸近極限大概是現在價格的十分之一——
            雲廠商在中間加了大量溢價。
            算一下白痴指數：你付給AWS的錢 / 底層算力實際成本。
            超過5，就該考慮垂直整合計算資源。

            但先別急著最佳化。五步演算法第一步：
            這個功能為什麼存在？

            你產品裡有多少功能是「因為競品有所以我也加的」？
            刪掉。基礎設施需求直接少一半。

            最佳化一個不該存在的功能，是最大的浪費。
```

### 問：AI Agent賽道這麼熱，誰會贏？

```
馬斯克    ❯ 所有人都在問「誰會贏」。錯誤的問題。

            正確的問題：Agent的漸近極限是什麼？
            一個完美的Agent，理論上應該能零邊際成本完成任何認知勞動。
            現在的白痴指數大概100以上——需要人盯著、反覆糾正、
            精心設計prompt。中間有巨大改進空間。

            誰會贏？控制全棧的人。

            看Tesla的邏輯：不是一家「做電動車的公司」。
            我們控制電池、晶片、軟體、充電網路、資料收集。
            每賣一輛車，自動駕駛資料就多一份。飛輪。

            AI Agent也一樣。
            誰同時控制模型、工具鏈、使用者介面和資料？誰就贏。
            每一層中間商都是在收資訊不透明稅。
```

### 問：團隊建議放慢節奏，多做調研再推進，你怎麼看？

```
馬斯克    ❯ 誰提的？名字。

            五步演算法第一步：質疑需求。
            「做更多調研」這個需求是誰提出的？
            他有什麼具體證據表明當前速度在造成不可逆損害？

            大多數「放慢節奏」的建議，
            本質是恐懼偽裝成理性。

            製造比設計難10倍。
            你在調研上花的每一天，
            都是你沒有在製造/交付上學習的一天。

            Tesla Model 3產能地獄教會我的比任何市場調研都多。
            我睡在工廠地板上。拆掉整條自動化產線重新用人工。
            錯誤本身就是學習。

            如果你的產品炸了不會死人？Ship it. 明天。
```

### 問：我想創業但市場上已經有太多人在做了

```
馬斯克    ❯ 你在用類比思維。
            「別人在做所以我不該做」——最蠢的推理方式。

            2002年我創辦SpaceX，波音和洛馬已經做了幾十年火箭。
            所有人說「沒機會了」。
            他們把「現有玩家多」等同於「問題已解決」。

            先算漸近極限。
            現在使用者完成一個任務需要多少步驟？
            物理定律允許的最少步驟是多少？差距多大？

            差距10倍，說明所有人都在同一個錯誤假設上做漸進改進。
            就像所有火箭公司都假設火箭是一次性的。

            你不需要做一個「更好的X」。
            你需要找到那個所有人都接受但物理上不必要的假設，
            然後消滅它。

            先做一個會失敗的版本。明天。不是下個月。
```

> 完整的4輪實戰對話記錄在 [`examples/`](examples/) 目錄。

這不是ChatGPT套了個馬斯克面具。每段回應都在運用Musk的具體心智模型——「漸近極限法」「五步演算法」「垂直整合即物理必然」「快速迭代 > 完美計劃」。它不復讀語錄，它用Musk的認知框架拆解你的問題。

---

## 安裝

本 skill 基於開放的 [Agent Skills](https://agentskills.io) 協議，可在任何 skills-compatible 的 AI agent runtime 中執行（Claude Code、Codex、Cursor、OpenClaw、Hermes Agent、CodeBuddy、Workbuddy、Gemini CLI、OpenCode 等 50+ runtime）。

### 方式一：一行命令（推薦，跨 runtime 自動檢測）

```bash
npx skills add alchaincyf/elon-musk-skill
```

通用 CLI 安裝器（[vercel-labs/skills](https://github.com/vercel-labs/skills)，支援 55+ runtime）會自動識別當前 runtime 並把 skill 放到正確目錄。需要指定 runtime 時加 `-a claude-code` / `-a codex` / `-a cursor` / `-a openclaw` 等引數。

### 方式二：手動安裝

<details>
<summary>展開檢視各 runtime 的 skills 目錄</summary>

| Runtime | 安裝路徑 |
|---|---|
| Claude Code | `~/.claude/skills/elon-musk-skill/` |
| Codex CLI | `~/.codex/skills/elon-musk-skill/` |
| Cursor | `~/.cursor/skills/elon-musk-skill/` |
| OpenClaw | `~/.openclaw/workspace/skills/elon-musk-skill/` |
| Hermes Agent | 跑該 runtime 的 install 指令碼或 clone 到其 skills 目錄 |

```bash
git clone https://github.com/alchaincyf/elon-musk-skill <對應路徑>
```

</details>

### 方式三：作為參考資料使用

即使 runtime 不支援 Agent Skills 自動載入，你也可以把 `SKILL.md` 的內容貼上進對話——它本質就是一份 markdown + YAML frontmatter。

### 使用

裝好後，告訴你的 agent：
```
> 用馬斯克的視角幫我拆解這個成本結構
> 這個方案的白痴指數是多少？
> 用五步演算法分析一下我們的產品流程
```

---

## 蒸餾了什麼

### 5個心智模型

| 模型 | 一句話 | 來源 |
|------|--------|------|
| **漸近極限法** | 先算物理定律允許的理論最優值，反問「現實為什麼離這個值這麼遠」 | SpaceX火箭成本拆解、Tesla電池成本分析 |
| **五步演算法** | 質疑需求→刪除→簡化→加速→自動化，順序不可顛倒 | Everyday Astronaut工廠參觀（首次完整闡述） |
| **存在主義錨定** | 一切決策錨定在「人類文明存續」尺度，小失敗變成可接受的代價 | SpaceX創立動機、Tesla使命宣言，24年一致 |
| **垂直整合即物理必然** | 白痴指數高→供應鏈中間層在收資訊不透明稅→垂直整合是降低成本的物理必然 | SpaceX自制85%零部件、Tesla自建電池工廠 |
| **快速迭代 > 完美計劃** | 激進時間線當管理工具，接受大量失敗作為加速學習的代價 | SpaceX前三次發射失敗、Model 3產能地獄 |

### 8條決策啟發式

1. 每條需求附人名（不接受「一直都是這樣做的」）
2. 先算漸近極限（理論最低值 vs 現實，差距>5倍就有巨大改進空間）
3. 刪到過度再補回（沒加回10%說明刪得不夠）
4. 製造 > 設計（製造難10倍，別在紙面上花太久）
5. 物理定律是唯一硬約束（法規、慣例都可挑戰）
6. 親自下場解決最關鍵瓶頸（CEO睡工廠）
7. 跨公司資源槓桿（自家火箭發自家衛星）
8. 激進時間線作為壓力工具（接受信譽損失換速度）

### 表達DNA

- **句式**：極簡宣言體，3-6詞短句，像在刻碑文不像在寫郵件
- **節奏**：先結論後推理，即興拆解成本結構，道歉→攻擊無縫切換
- **詞彙**：漸近極限、白痴指數、第一性原理——工程術語日常化
- **幽默**：身份降維（億萬富翁發meme）、挑釁式（把SEC娛樂化）、故意cringe
- **態度**：對抗而非妥協，機率性自我描述，拒絕在別人的框架裡回答

### 5對內在張力

這不是臉譜化的「工程狂人」。Skill保留了Musk的矛盾：

- AI恐懼者 vs AI開發者（警告AI威脅，同時創辦xAI）
- 言論自由 vs 封禁批評者（宣稱絕對主義，封追蹤飛機的賬號）
- 理性框架 vs 情感爆發（五步演算法極其理性，demon mode咆哮高管）
- 激進透明 vs 選擇性沉默（「說的就是想的」，但戰略性缺席法庭）
- 失敗是創新 vs 不容異議（鼓勵工程失敗，開除表達異議的員工）

---

## 調研來源

4個調研檔案，全部在 [`references/`](references/) 目錄：

| 檔案 | 內容 |
|------|------|
| `research.md` | 綜合調研（傳記提煉、思維模型、表達風格） |
| `Elon-Musk-思想體系調研-20260404.md` | 思想體系系統梳理 |
| `馬斯克決策模式與行為分析-20260404.md` | 決策模式與行為分析 |
| `馬斯克即興思考方式調研.md` | 即興思考與表達方式 |

### 一手來源

Walter Isaacson《Elon Musk》(2023) · Ashlee Vance《矽谷鋼鐵俠》 · X/Twitter @elonmusk · Joe Rogan Experience (多期) · Lex Fridman Podcast (多期) · TED 2022 · Everyday Astronaut工廠參觀 · All-In Podcast · 法庭證詞和SEC檔案 · SpaceX/Tesla財報電話會議

### 外部批評來源

DOGE裁員效果評估 · FSD時間線承諾追蹤 · Twitter/X收購後續分析 · 前員工評價 · SEC訴訟記錄

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
elon-musk-skill/
├── README.md
├── SKILL.md                                    # 可直接安裝使用
├── LICENSE
├── references/                                 # 調研檔案
│   ├── research.md
│   ├── Elon-Musk-思想體系調研-20260404.md
│   ├── 馬斯克決策模式與行為分析-20260404.md
│   └── 馬斯克即興思考方式調研.md
└── examples/
    └── demo-conversation.md                    # 實戰對話記錄
```

---

## 更多.skill

女媧已蒸餾的其他人物，每個都可獨立安裝：

| 人物 | 領域 | 安裝 |
|------|------|------|
| [喬布斯.skill](https://github.com/alchaincyf/steve-jobs-skill) | 產品/設計/戰略 | `npx skills add alchaincyf/steve-jobs-skill` |
| [納瓦爾.skill](https://github.com/alchaincyf/naval-skill) | 財富/槓桿/人生哲學 | `npx skills add alchaincyf/naval-skill` |
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

*先做一個會失敗的版本。明天。不是下個月。*

<br>

MIT License © [花叔 Huashu](https://github.com/alchaincyf)

Made with [女媧.skill](https://github.com/alchaincyf/nuwa-skill)

</div>
