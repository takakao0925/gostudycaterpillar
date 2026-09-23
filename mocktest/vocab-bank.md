# 循環模式單字庫（Vocab Bank）

> 這份檔案是 [cycle_mode_mvp.html](cycle_mode_mvp.html) 裡 `defaultWordBank()` 函式的**內容鏡像**（source of truth 的人類/AI 可讀版本）。
> 修改流程：先在這份 md 裡加字／改字 → 再把對應的 JS 物件貼進 `cycle_mode_mvp.html` 的 `defaultWordBank()` 陣列裡。這份 md **不會被網頁直接讀取**，單純是給人與其他 AI 編輯、對照用的。
> 加字前請先讀 [vocab-bank-guidelines.md](vocab-bank-guidelines.md)，裡面是格式規則。

目前共 **96 個字**，最後使用的 id 是 `w96`（下一個新字從 `w97` 開始）。

---

## 快速總覽

| 英文 | 詞性／中文意思 |
|---|---|
| address | (vt) 1. 處理；應付　2. 向…致辭；發表演說　(nc) 地址 |
| account | (nc) 帳戶 |
| account for | (phr.) 說明；解釋 |
| run | (vi) 跑步　(vt) 經營；管理 |
| budget | (nc) 預算　(vt) 編列預算 |
| colleague | (nc) 同事 |
| deadline | (nc) 截止日期；期限 |
| efficient | (adj) 有效率的；效率高的 |
| feasible | (adj) 可行的 |
| inventory | (nc) 庫存清單；盤點清單　(nu) 存貨；庫存 |
| logistics | (nu) 物流；後勤 |
| merger | (nc) 合併案；合併 |
| negotiate | (vi) 談判；協商　(vt) 協商達成；談定 |
| outcome | (nc) 結果；成果 |
| proficient | (adj) 熟練的；精通的 |
| quarterly | (adj) 每季的；季度的　(adv) 每季地；以季為單位地 |
| reimburse | (vt) 償還；報銷 |
| supervise | (vt) 監督；督導；管理 |
| thorough | (adj) 徹底的；全面的；仔細的 |
| undergo | (vt) 經歷；接受；經受 |
| vendor | (nc) 供應商；廠商 |
| warranty | (nc) 保固；保固書；保證書 |
| yield | (vi) 讓步；屈服　(vt) 產生；出產；帶來　(nc) 產量；收益；殖利率 |
| zeal | (nu) 熱忱；熱情；熱誠 |
| a game of cat and mouse | (phr.) 貓捉老鼠的把戲；互相追逐周旋的局面 |
| a leap of faith | (phr.) 憑信念放手一搏；不顧風險的嘗試 |
| aboard | (prep) 在（船、飛機、火車等）上 |
| absolutely | (adv) 絕對地；完全地 |
| accident | (nc) 意外；事故 |
| accomplishment | (nc) 成就；成果 |
| accurate | (adj) 準確的；精確的 |
| achieve | (vt) 達成；實現 |
| acre | (nc) 英畝 |
| action | (nc) 行動；措施 |
| activity | (nc) 活動 |
| adapt | (vi) 適應　(vt) 使…適應；改編 |
| additional | (adj) 額外的；附加的 |
| admission | (nc) 1. 承認；招認　2. 入場許可；准入 |
| admit | (vt) 1. 承認　2. 准許進入；允許加入 |
| adopt | (vt) 採用；採納 |
| advance | (vi) 前進；進展　(nc) 預付款 |
| advancement | (nc) 進步；晉升 |
| adventure | (nc) 冒險；奇遇 |
| advertising | (nu) 廣告業；廣告活動 |
| advise | (vt) 建議；勸告 |
| affiliate | (nc) 附屬機構；分支機構　(vt) 使隸屬；使加盟 |
| affordable | (adj) 負擔得起的；價格合理的 |
| agent | (nc) 代理人；經紀人 |
| aggressive | (adj) 積極進取的；有企圖心的 |
| agriculture | (nu) 農業 |
| aid | (nc) 援助；補助　(vt) 幫助；援助 |
| airline | (nc) 航空公司 |
| alarming | (adj) 令人擔憂的；驚人的 |
| alcoholic | (adj) 含酒精的 |
| alien | (nc) 外籍人士　(adj) 陌生的；格格不入的 |
| aluminum | (nu) 鋁 |
| amateur | (nc) 業餘愛好者　(adj) 業餘的 |
| amaze | (vt) 使驚訝；使驚奇 |
| ambitious | (adj) 有野心的；雄心勃勃的 |
| amount | (nc) 數量；金額 |
| amusement | (nu) 娛樂；消遣 |
| analyze | (vt) 分析 |
| ancestor | (nc) 祖先 |
| ancient | (adj) 古老的；古代的 |
| announcement | (nc) 公告；宣布 |
| annoy | (vt) 使惱怒；使煩躁 |
| anxiously | (adv) 焦急地；憂慮地 |
| apparent | (adj) 明顯的；顯而易見的 |
| appeal | (vi) 吸引；有吸引力　(nc) 申訴 |
| appearance | (nc) 1. 外觀；外表　2. 出現；露面 |
| apply | (vi) 申請；適用　(vt) 應用；運用 |
| appropriate | (adj) 適當的；合適的 |
| approval | (nu) 核准；批准；贊同 |
| area | (nc) 區域；領域 |
| arguably | (adv) 可以說；按理來說 |
| armed | (adj) 1. 武裝的　2. 配備的；具備的（資訊、工具等） |
| arouse | (vt) 引起；激起 |
| arrest | (vt) 逮捕 |
| article | (nc) 1. 文章　2. （合約）條款 |
| ash | (nu) 灰燼 |
| aspect | (nc) 方面；層面 |
| assemble | (vt) 組裝；集合 |
| assembly | (nu) 裝配；組裝　(nc) 集會；大會 |
| assist | (vt) 協助；幫助 |
| associate | (vt) 聯想；使有關連　(nc) 同事；夥伴 |
| atmosphere | (nc) 氣氛；氛圍 |
| attempt | (vt) 嘗試　(nc) 嘗試；企圖 |
| attend | (vt) 出席；參加 |
| attitude | (nc) 態度 |
| attract | (vt) 吸引 |
| author | (nc) 作者 |
| authority | (nu) 權威；權力　(nc) 當局；主管機關 |
| automatic | (adj) 自動的 |
| available | (adj) 可得到的；有空的 |
| average | (adj) 平均的　(nc) 平均值 |
| aware | (adj) 察覺到的；知道的 |

---

## 完整資料（可直接貼進 `defaultWordBank()`）

`createdAt` / `wrongCount` / `stats` 是程式執行期自動維護的欄位，新增單字時固定寫 `createdAt: new Date().toISOString(), wrongCount: 0, stats: null` 即可，不用另外算。

```js
[
  {
    id: "w1", english: "address", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["處理","應付"], ["向…致辭","發表演說"] ] },
      { pos: "nc", meaningGroups: [ ["地址"] ] }
    ],
    examples: [
      { en:"We need to address this issue immediately.", zh:"我們需要立刻處理這個問題。" },
      { en:"The CEO will address the shareholders tomorrow.", zh:"執行長明天將向股東致辭。" },
      { en:"Please write your address on the form.", zh:"請在表格上填寫你的地址。" }
    ]
  },
  {
    id: "w2", english: "account", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["帳戶"] ] }
    ],
    examples: [
      { en:"I opened a new bank account.", zh:"我開了一個新的銀行帳戶。" }
    ]
  },
  {
    id: "w3", english: "account for", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["說明","解釋"] ] }
    ],
    examples: [
      { en:"He couldn't account for the missing funds.", zh:"他無法解釋短少的資金。" }
    ]
  },
  {
    id: "w4", english: "run", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["跑步"] ] },
      { pos: "vt", meaningGroups: [ ["經營","管理"] ] }
    ],
    examples: [
      { en:"She runs every morning.", zh:"她每天早上跑步。" },
      { en:"He runs a small bakery.", zh:"他經營一家小麵包店。" }
    ]
  },
  {
    id: "w5", english: "budget", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["預算"] ] },
      { pos: "vt", meaningGroups: [ ["編列預算"] ] }
    ],
    examples: [
      { en:"The marketing team submitted next year's budget for approval.", zh:"行銷團隊提交了明年度的預算以待核准。" },
      { en:"We need to budget carefully for the new office renovation.", zh:"我們需要為新辦公室的整修謹慎編列預算。" }
    ]
  },
  {
    id: "w6", english: "colleague", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["同事"] ] }
    ],
    examples: [
      { en:"She discussed the proposal with her colleagues before the meeting.", zh:"她在會議前與同事討論了這項提案。" }
    ]
  },
  {
    id: "w7", english: "deadline", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["截止日期","期限"] ] }
    ],
    examples: [
      { en:"The deadline for submitting the report was moved up to Friday.", zh:"提交報告的截止日期被提前到星期五。" }
    ]
  },
  {
    id: "w8", english: "efficient", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["有效率的","效率高的"] ] }
    ],
    examples: [
      { en:"The new software made the billing process much more efficient.", zh:"新軟體讓請款流程變得有效率許多。" }
    ]
  },
  {
    id: "w9", english: "feasible", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["可行的"] ] }
    ],
    examples: [
      { en:"The engineers concluded that the project timeline was not feasible.", zh:"工程師們判定這個專案時程並不可行。" }
    ]
  },
  {
    id: "w10", english: "inventory", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["庫存清單","盤點清單"] ] },
      { pos: "nu", meaningGroups: [ ["存貨","庫存"] ] }
    ],
    examples: [
      { en:"The warehouse staff conducted a full inventory at the end of the quarter.", zh:"倉庫人員在季末進行了完整的庫存盤點。" },
      { en:"The store is trying to reduce excess inventory before the holidays.", zh:"這家店正試圖在假期前減少過剩的庫存。" }
    ]
  },
  {
    id: "w11", english: "logistics", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["物流","後勤"] ] }
    ],
    examples: [
      { en:"The company hired a new manager to oversee logistics and shipping.", zh:"公司聘請了一位新經理來監督物流與貨運事宜。" }
    ]
  },
  {
    id: "w12", english: "merger", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["合併案","合併"] ] }
    ],
    examples: [
      { en:"The merger between the two firms was finalized last month.", zh:"這兩家公司的合併案上個月已定案。" }
    ]
  },
  {
    id: "w13", english: "negotiate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["談判","協商"] ] },
      { pos: "vt", meaningGroups: [ ["協商達成","談定"] ] }
    ],
    examples: [
      { en:"Both sides agreed to negotiate a new contract next week.", zh:"雙方同意下週協商一份新合約。" },
      { en:"The union representatives negotiated directly with management.", zh:"工會代表直接與資方談判。" }
    ]
  },
  {
    id: "w14", english: "outcome", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["結果","成果"] ] }
    ],
    examples: [
      { en:"The outcome of the negotiation exceeded everyone's expectations.", zh:"這次談判的結果超出了所有人的預期。" }
    ]
  },
  {
    id: "w15", english: "proficient", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["熟練的","精通的"] ] }
    ],
    examples: [
      { en:"Applicants must be proficient in both English and Mandarin.", zh:"應徵者必須精通英文與中文。" }
    ]
  },
  {
    id: "w16", english: "quarterly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["每季的","季度的"] ] },
      { pos: "adv", meaningGroups: [ ["每季地","以季為單位地"] ] }
    ],
    examples: [
      { en:"The board holds a quarterly review of company performance.", zh:"董事會每季召開一次公司績效檢討會議。" },
      { en:"Dividends are paid out quarterly to shareholders.", zh:"股息每季發放給股東。" }
    ]
  },
  {
    id: "w17", english: "reimburse", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["償還","報銷"] ] }
    ],
    examples: [
      { en:"The company will reimburse employees for approved travel expenses.", zh:"公司將報銷員工核准的差旅費用。" }
    ]
  },
  {
    id: "w18", english: "supervise", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["監督","督導","管理"] ] }
    ],
    examples: [
      { en:"She was promoted to supervise the entire customer service team.", zh:"她被升職去監督整個客服團隊。" }
    ]
  },
  {
    id: "w19", english: "thorough", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["徹底的","全面的","仔細的"] ] }
    ],
    examples: [
      { en:"The auditors conducted a thorough review of the financial records.", zh:"審計人員對財務紀錄進行了徹底的審查。" }
    ]
  },
  {
    id: "w20", english: "undergo", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["經歷","接受","經受"] ] }
    ],
    examples: [
      { en:"The building will undergo renovation starting next month.", zh:"這棟建築將從下個月開始進行整修。" }
    ]
  },
  {
    id: "w21", english: "vendor", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["供應商","廠商"] ] }
    ],
    examples: [
      { en:"The company switched to a new vendor for office supplies.", zh:"公司換了新的辦公用品供應商。" }
    ]
  },
  {
    id: "w22", english: "warranty", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["保固","保固書","保證書"] ] }
    ],
    examples: [
      { en:"The laptop comes with a two-year warranty.", zh:"這台筆電附有兩年保固。" }
    ]
  },
  {
    id: "w23", english: "yield", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["讓步","屈服"] ] },
      { pos: "vt", meaningGroups: [ ["產生","出產","帶來"] ] },
      { pos: "nc", meaningGroups: [ ["產量","收益","殖利率"] ] }
    ],
    examples: [
      { en:"The negotiators refused to yield on the pricing issue.", zh:"談判代表在定價問題上拒絕讓步。" },
      { en:"The new marketing strategy yielded a significant increase in sales.", zh:"新的行銷策略帶來了顯著的銷售成長。" },
      { en:"Investors are attracted by the fund's high yield.", zh:"投資人被這檔基金的高收益率吸引。" }
    ]
  },
  {
    id: "w24", english: "zeal", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["熱忱","熱情","熱誠"] ] }
    ],
    examples: [
      { en:"The new intern approached every task with great zeal.", zh:"這位新實習生對每項任務都充滿熱忱。" }
    ]
  },
  {
    id: "w25", english: "a game of cat and mouse", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "phr.", meaningGroups: [ [ "貓捉老鼠的把戲","互相追逐周旋的局面" ] ] }
    ],
    examples: [
    { en:"The negotiations turned into a game of cat and mouse between the two companies.", zh:"這場談判變成兩家公司之間貓捉老鼠般的角力。" }
    ]
  },
  {
    id: "w26", english: "a leap of faith", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "phr.", meaningGroups: [ [ "憑信念放手一搏","不顧風險的嘗試" ] ] }
    ],
    examples: [
    { en:"Investing in the startup was a leap of faith for the founders.", zh:"投資這家新創公司對創辦人來說是一場憑信念的放手一搏。" }
    ]
  },
  {
    id: "w27", english: "aboard", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "prep", meaningGroups: [ [ "在（船、飛機、火車等）上" ] ] }
    ],
    examples: [
    { en:"All passengers must be aboard before the gate closes.", zh:"所有乘客必須在登機門關閉前登機。" }
    ]
  },
  {
    id: "w28", english: "absolutely", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "adv", meaningGroups: [ [ "絕對地","完全地" ] ] }
    ],
    examples: [
    { en:"The manager was absolutely certain the deal would close by Friday.", zh:"經理絕對確信這筆交易會在星期五前完成。" }
    ]
  },
  {
    id: "w29", english: "accident", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "nc", meaningGroups: [ [ "意外","事故" ] ] }
    ],
    examples: [
    { en:"The factory reported no accidents during the safety audit.", zh:"工廠在安全稽核期間沒有回報任何意外事故。" }
    ]
  },
  {
    id: "w30", english: "accomplishment", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "nc", meaningGroups: [ [ "成就","成果" ] ] }
    ],
    examples: [
    { en:"Winning the industry award was a major accomplishment for the team.", zh:"贏得業界獎項對這個團隊來說是一項重大成就。" }
    ]
  },
  {
    id: "w31", english: "accurate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "adj", meaningGroups: [ [ "準確的","精確的" ] ] }
    ],
    examples: [
    { en:"Please make sure the figures in the report are accurate.", zh:"請確保報告中的數字是準確的。" }
    ]
  },
  {
    id: "w32", english: "achieve", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "vt", meaningGroups: [ [ "達成","實現" ] ] }
    ],
    examples: [
    { en:"The sales team achieved its quarterly target ahead of schedule.", zh:"業務團隊提前達成了季度目標。" }
    ]
  },
  {
    id: "w33", english: "acre", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "nc", meaningGroups: [ [ "英畝" ] ] }
    ],
    examples: [
    { en:"The company purchased twenty acres of land for the new warehouse.", zh:"公司購買了二十英畝的土地來興建新倉庫。" }
    ]
  },
  {
    id: "w34", english: "action", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "nc", meaningGroups: [ [ "行動","措施" ] ] }
    ],
    examples: [
    { en:"Management took immediate action to fix the production delay.", zh:"管理層立即採取行動解決生產延誤問題。" }
    ]
  },
  {
    id: "w35", english: "activity", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "nc", meaningGroups: [ [ "活動" ] ] }
    ],
    examples: [
    { en:"The HR department organizes team-building activities every quarter.", zh:"人資部門每一季都會舉辦團隊建立活動。" }
    ]
  },
  {
    id: "w36", english: "adapt", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "vi", meaningGroups: [ [ "適應" ] ] },
    { pos: "vt", meaningGroups: [ [ "使…適應","改編" ] ] }
    ],
    examples: [
    { en:"New employees usually need a few weeks to adapt to the company culture.", zh:"新進員工通常需要幾週時間才能適應公司文化。" },
    { en:"The manual was adapted for first-time users.", zh:"這本手冊經過調整以適合初次使用者。" }
    ]
  },
  {
    id: "w37", english: "additional", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "adj", meaningGroups: [ [ "額外的","附加的" ] ] }
    ],
    examples: [
    { en:"Additional charges may apply for express shipping.", zh:"快遞可能會產生額外費用。" }
    ]
  },
  {
    id: "w38", english: "admission", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "nc", meaningGroups: [ [ "承認","招認" ], [ "入場許可","准入" ] ] }
    ],
    examples: [
    { en:"His admission of the mistake surprised the whole team.", zh:"他承認錯誤讓整個團隊都感到意外。" },
    { en:"General admission tickets go on sale next Monday.", zh:"普通入場券將於下週一開賣。" }
    ]
  },
  {
    id: "w39", english: "admit", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "vt", meaningGroups: [ [ "承認" ], [ "准許進入","允許加入" ] ] }
    ],
    examples: [
    { en:"She admitted that the report contained an error.", zh:"她承認報告裡有一個錯誤。" }
    ]
  },
  {
    id: "w40", english: "adopt", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "vt", meaningGroups: [ [ "採用","採納" ] ] }
    ],
    examples: [
    { en:"The company decided to adopt a new accounting system next year.", zh:"公司決定明年採用一套新的會計系統。" }
    ]
  },
  {
    id: "w41", english: "advance", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "vi", meaningGroups: [ [ "前進","進展" ] ] },
    { pos: "nc", meaningGroups: [ [ "預付款" ] ] }
    ],
    examples: [
    { en:"Negotiations advanced quickly once both sides agreed on price.", zh:"雙方一旦就價格達成共識，談判便迅速進展。" },
    { en:"Employees can request a cash advance for business travel.", zh:"員工可以申請差旅現金預付款。" }
    ]
  },
  {
    id: "w42", english: "advancement", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "nc", meaningGroups: [ [ "進步","晉升" ] ] }
    ],
    examples: [
    { en:"The new training program supports career advancement.", zh:"這項新的培訓計畫有助於職涯晉升。" }
    ]
  },
  {
    id: "w43", english: "adventure", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "nc", meaningGroups: [ [ "冒險","奇遇" ] ] }
    ],
    examples: [
    { en:"Starting the business was quite an adventure for the two partners.", zh:"創業對這兩位合夥人來說是一場相當大的冒險。" }
    ]
  },
  {
    id: "w44", english: "advertising", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "nu", meaningGroups: [ [ "廣告業","廣告活動" ] ] }
    ],
    examples: [
    { en:"The company increased its advertising budget for the holiday season.", zh:"公司增加了假期季的廣告預算。" }
    ]
  },
  {
    id: "w45", english: "advise", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "vt", meaningGroups: [ [ "建議","勸告" ] ] }
    ],
    examples: [
    { en:"The consultant advised the client to diversify their investments.", zh:"顧問建議客戶要分散投資。" }
    ]
  },
  {
    id: "w46", english: "affiliate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "nc", meaningGroups: [ [ "附屬機構","分支機構" ] ] },
    { pos: "vt", meaningGroups: [ [ "使隸屬","使加盟" ] ] }
    ],
    examples: [
    { en:"The product is distributed through a local affiliate.", zh:"這項產品是透過當地的分支機構經銷的。" },
    { en:"The university affiliated its research center with a leading tech firm.", zh:"這所大學讓其研究中心與一家領先的科技公司建立合作關係。" }
    ]
  },
  {
    id: "w47", english: "affordable", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "adj", meaningGroups: [ [ "負擔得起的","價格合理的" ] ] }
    ],
    examples: [
    { en:"The startup offers an affordable pricing plan for small businesses.", zh:"這家新創公司為小型企業提供價格合理的方案。" }
    ]
  },
  {
    id: "w48", english: "agent", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "nc", meaningGroups: [ [ "代理人","經紀人" ] ] }
    ],
    examples: [
    { en:"Contact your insurance agent before filing a claim.", zh:"申請理賠前請先聯絡你的保險代理人。" }
    ]
  },
  {
    id: "w49", english: "aggressive", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "adj", meaningGroups: [ [ "積極進取的","有企圖心的" ] ] }
    ],
    examples: [
    { en:"The firm set an aggressive growth target for next year.", zh:"這家公司為明年設定了積極的成長目標。" }
    ]
  },
  {
    id: "w50", english: "agriculture", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "nu", meaningGroups: [ [ "農業" ] ] }
    ],
    examples: [
    { en:"The region's economy depends heavily on agriculture.", zh:"這個地區的經濟高度仰賴農業。" }
    ]
  },
  {
    id: "w51", english: "aid", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "nc", meaningGroups: [ [ "援助","補助" ] ] },
    { pos: "vt", meaningGroups: [ [ "幫助","援助" ] ] }
    ],
    examples: [
    { en:"The government provided financial aid to affected businesses.", zh:"政府向受影響的企業提供了財務援助。" },
    { en:"The new software aids employees in tracking their expenses.", zh:"這套新軟體有助於員工追蹤他們的支出。" }
    ]
  },
  {
    id: "w52", english: "airline", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "nc", meaningGroups: [ [ "航空公司" ] ] }
    ],
    examples: [
    { en:"The airline announced a new direct route to Tokyo.", zh:"這家航空公司宣布了一條飛往東京的新直飛航線。" }
    ]
  },
  {
    id: "w53", english: "alarming", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "adj", meaningGroups: [ [ "令人擔憂的","驚人的" ] ] }
    ],
    examples: [
    { en:"The report revealed an alarming drop in customer satisfaction.", zh:"報告顯示顧客滿意度出現令人擔憂的下滑。" }
    ]
  },
  {
    id: "w54", english: "alcoholic", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "adj", meaningGroups: [ [ "含酒精的" ] ] }
    ],
    examples: [
    { en:"The hotel bar serves both alcoholic and non-alcoholic beverages.", zh:"這間飯店酒吧供應含酒精與不含酒精的飲料。" }
    ]
  },
  {
    id: "w55", english: "alien", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "nc", meaningGroups: [ [ "外籍人士" ] ] },
    { pos: "adj", meaningGroups: [ [ "陌生的","格格不入的" ] ] }
    ],
    examples: [
    { en:"The company sponsors work visas for resident aliens.", zh:"公司為外籍居民員工申請工作簽證。" }
    ]
  },
  {
    id: "w56", english: "aluminum", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "nu", meaningGroups: [ [ "鋁" ] ] }
    ],
    examples: [
    { en:"The packaging was redesigned using recyclable aluminum.", zh:"包裝使用可回收的鋁重新設計。" }
    ]
  },
  {
    id: "w57", english: "amateur", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "nc", meaningGroups: [ [ "業餘愛好者" ] ] },
    { pos: "adj", meaningGroups: [ [ "業餘的" ] ] }
    ],
    examples: [
    { en:"The photography contest is open to both amateurs and professionals.", zh:"這項攝影比賽開放給業餘愛好者與專業人士參加。" }
    ]
  },
  {
    id: "w58", english: "amaze", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "vt", meaningGroups: [ [ "使驚訝","使驚奇" ] ] }
    ],
    examples: [
    { en:"The rapid sales growth amazed even the company's founders.", zh:"快速的銷售成長連公司創辦人都感到驚訝。" }
    ]
  },
  {
    id: "w59", english: "ambitious", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "adj", meaningGroups: [ [ "有野心的","雄心勃勃的" ] ] }
    ],
    examples: [
    { en:"The CEO announced an ambitious plan to double revenue in three years.", zh:"執行長宣布了一項要在三年內讓營收翻倍的雄心勃勃計畫。" }
    ]
  },
  {
    id: "w60", english: "amount", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "nc", meaningGroups: [ [ "數量","金額" ] ] }
    ],
    examples: [
    { en:"Please verify the amount before submitting the invoice.", zh:"提交發票前請先確認金額。" }
    ]
  },
  {
    id: "w61", english: "amusement", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "nu", meaningGroups: [ [ "娛樂","消遣" ] ] }
    ],
    examples: [
    { en:"The company organized an amusement park trip for employees.", zh:"公司為員工安排了一趟遊樂園之旅。" }
    ]
  },
  {
    id: "w62", english: "analyze", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "vt", meaningGroups: [ [ "分析" ] ] }
    ],
    examples: [
    { en:"The team analyzed customer feedback to improve the product.", zh:"團隊分析顧客回饋以改善產品。" }
    ]
  },
  {
    id: "w63", english: "ancestor", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "nc", meaningGroups: [ [ "祖先" ] ] }
    ],
    examples: [
    { en:"She researched her ancestors' history for the family reunion.", zh:"她為了家族聚會研究了她祖先的歷史。" }
    ]
  },
  {
    id: "w64", english: "ancient", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "adj", meaningGroups: [ [ "古老的","古代的" ] ] }
    ],
    examples: [
    { en:"The exhibit features artifacts from an ancient civilization.", zh:"這場展覽展出了古代文明的文物。" }
    ]
  },
  {
    id: "w65", english: "announcement", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "nc", meaningGroups: [ [ "公告","宣布" ] ] }
    ],
    examples: [
    { en:"The company made an official announcement about the merger.", zh:"公司針對這次合併發表了正式公告。" }
    ]
  },
  {
    id: "w66", english: "annoy", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "vt", meaningGroups: [ [ "使惱怒","使煩躁" ] ] }
    ],
    examples: [
    { en:"Frequent system errors annoyed the customer service staff.", zh:"頻繁的系統錯誤讓客服人員感到惱怒。" }
    ]
  },
  {
    id: "w67", english: "anxiously", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "adv", meaningGroups: [ [ "焦急地","憂慮地" ] ] }
    ],
    examples: [
    { en:"Investors waited anxiously for the earnings report.", zh:"投資人焦急地等待財報公布。" }
    ]
  },
  {
    id: "w68", english: "apparent", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "adj", meaningGroups: [ [ "明顯的","顯而易見的" ] ] }
    ],
    examples: [
    { en:"It became apparent that the deadline would not be met.", zh:"很明顯這個截止日期無法如期達成。" }
    ]
  },
  {
    id: "w69", english: "appeal", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "vi", meaningGroups: [ [ "吸引","有吸引力" ] ] },
    { pos: "nc", meaningGroups: [ [ "申訴" ] ] }
    ],
    examples: [
    { en:"The new design appeals to younger consumers.", zh:"這項新設計吸引了年輕消費者。" },
    { en:"The company filed an appeal against the tax ruling.", zh:"公司針對這項稅務裁決提出了申訴。" }
    ]
  },
  {
    id: "w70", english: "appearance", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "nc", meaningGroups: [ [ "外觀","外表" ], [ "出現","露面" ] ] }
    ],
    examples: [
    { en:"First impressions often depend on a candidate's appearance.", zh:"第一印象往往取決於應徵者的外表。" }
    ]
  },
  {
    id: "w71", english: "apply", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "vi", meaningGroups: [ [ "申請","適用" ] ] },
    { pos: "vt", meaningGroups: [ [ "應用","運用" ] ] }
    ],
    examples: [
    { en:"Candidates must apply online before the deadline.", zh:"應徵者必須在截止日期前上網申請。" },
    { en:"The team applied the new strategy to all departments.", zh:"團隊將這項新策略應用到所有部門。" }
    ]
  },
  {
    id: "w72", english: "appropriate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "adj", meaningGroups: [ [ "適當的","合適的" ] ] }
    ],
    examples: [
    { en:"Please wear appropriate attire for the client meeting.", zh:"請穿著適當的服裝出席客戶會議。" }
    ]
  },
  {
    id: "w73", english: "approval", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "nu", meaningGroups: [ [ "核准","批准","贊同" ] ] }
    ],
    examples: [
    { en:"The budget is still awaiting approval from senior management.", zh:"這項預算仍在等待高層管理核准。" }
    ]
  },
  {
    id: "w74", english: "area", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "nc", meaningGroups: [ [ "區域","領域" ] ] }
    ],
    examples: [
    { en:"Customer service is an area that needs improvement.", zh:"客戶服務是一個需要改善的領域。" }
    ]
  },
  {
    id: "w75", english: "arguably", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "adv", meaningGroups: [ [ "可以說","按理來說" ] ] }
    ],
    examples: [
    { en:"This is arguably the company's most successful product launch.", zh:"這可以說是公司最成功的一次產品上市。" }
    ]
  },
  {
    id: "w76", english: "armed", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "adj", meaningGroups: [ [ "武裝的" ], [ "配備的","具備的（資訊、工具等）" ] ] }
    ],
    examples: [
    { en:"Armed with the latest sales data, the manager revised the forecast.", zh:"掌握了最新的銷售數據後，經理修正了預測。" }
    ]
  },
  {
    id: "w77", english: "arouse", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "vt", meaningGroups: [ [ "引起","激起" ] ] }
    ],
    examples: [
    { en:"The advertisement aroused strong interest among younger shoppers.", zh:"這則廣告引起了年輕購物者的強烈興趣。" }
    ]
  },
  {
    id: "w78", english: "arrest", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "vt", meaningGroups: [ [ "逮捕" ] ] }
    ],
    examples: [
    { en:"Police arrested the suspect for fraud.", zh:"警方以詐欺罪逮捕了嫌疑人。" }
    ]
  },
  {
    id: "w79", english: "article", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "nc", meaningGroups: [ [ "文章" ], [ "（合約）條款" ] ] }
    ],
    examples: [
    { en:"She wrote an article about workplace productivity.", zh:"她寫了一篇關於職場生產力的文章。" },
    { en:"Article 5 of the contract outlines the payment terms.", zh:"合約第五條說明了付款條件。" }
    ]
  },
  {
    id: "w80", english: "ash", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "nu", meaningGroups: [ [ "灰燼" ] ] }
    ],
    examples: [
    { en:"The factory fire left nothing but ash.", zh:"這場工廠大火只留下一片灰燼。" }
    ]
  },
  {
    id: "w81", english: "aspect", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "nc", meaningGroups: [ [ "方面","層面" ] ] }
    ],
    examples: [
    { en:"Every aspect of the proposal was reviewed by the board.", zh:"董事會審查了這份提案的每一個層面。" }
    ]
  },
  {
    id: "w82", english: "assemble", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "vt", meaningGroups: [ [ "組裝","集合" ] ] }
    ],
    examples: [
    { en:"Workers assemble the final product on the main production line.", zh:"工人在主要生產線上組裝最終產品。" }
    ]
  },
  {
    id: "w83", english: "assembly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "nu", meaningGroups: [ [ "裝配","組裝" ] ] },
    { pos: "nc", meaningGroups: [ [ "集會","大會" ] ] }
    ],
    examples: [
    { en:"The assembly line was upgraded to increase efficiency.", zh:"裝配線經過升級以提高效率。" }
    ]
  },
  {
    id: "w84", english: "assist", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "vt", meaningGroups: [ [ "協助","幫助" ] ] }
    ],
    examples: [
    { en:"The new hire will assist the marketing team with research.", zh:"這位新進員工將協助行銷團隊進行研究。" }
    ]
  },
  {
    id: "w85", english: "associate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "vt", meaningGroups: [ [ "聯想","使有關連" ] ] },
    { pos: "nc", meaningGroups: [ [ "同事","夥伴" ] ] }
    ],
    examples: [
    { en:"Customers associate the brand with high quality.", zh:"顧客將這個品牌與高品質聯想在一起。" },
    { en:"She works as a sales associate at the downtown branch.", zh:"她在市中心分店擔任銷售專員。" }
    ]
  },
  {
    id: "w86", english: "atmosphere", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "nc", meaningGroups: [ [ "氣氛","氛圍" ] ] }
    ],
    examples: [
    { en:"The office renovation created a more relaxed atmosphere.", zh:"辦公室整修營造出更輕鬆的氛圍。" }
    ]
  },
  {
    id: "w87", english: "attempt", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "vt", meaningGroups: [ [ "嘗試" ] ] },
    { pos: "nc", meaningGroups: [ [ "嘗試","企圖" ] ] }
    ],
    examples: [
    { en:"The company made another attempt to enter the Asian market.", zh:"公司再次嘗試進軍亞洲市場。" }
    ]
  },
  {
    id: "w88", english: "attend", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "vt", meaningGroups: [ [ "出席","參加" ] ] }
    ],
    examples: [
    { en:"All department heads are required to attend the meeting.", zh:"所有部門主管都必須出席這場會議。" }
    ]
  },
  {
    id: "w89", english: "attitude", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "nc", meaningGroups: [ [ "態度" ] ] }
    ],
    examples: [
    { en:"Her positive attitude impressed the interview panel.", zh:"她積極的態度令面試官印象深刻。" }
    ]
  },
  {
    id: "w90", english: "attract", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "vt", meaningGroups: [ [ "吸引" ] ] }
    ],
    examples: [
    { en:"The discount campaign attracted many new customers.", zh:"這項折扣活動吸引了許多新顧客。" }
    ]
  },
  {
    id: "w91", english: "author", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "nc", meaningGroups: [ [ "作者" ] ] }
    ],
    examples: [
    { en:"The author of the report will present the findings tomorrow.", zh:"這份報告的作者明天將發表研究結果。" }
    ]
  },
  {
    id: "w92", english: "authority", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "nu", meaningGroups: [ [ "權威","權力" ] ] },
    { pos: "nc", meaningGroups: [ [ "當局","主管機關" ] ] }
    ],
    examples: [
    { en:"She has the authority to approve expenses up to $5,000.", zh:"她有權核准最高五千美元的支出。" },
    { en:"The local authority issued a new business permit requirement.", zh:"當地主管機關發布了新的營業許可規定。" }
    ]
  },
  {
    id: "w93", english: "automatic", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "adj", meaningGroups: [ [ "自動的" ] ] }
    ],
    examples: [
    { en:"The system generates automatic reminders for overdue invoices.", zh:"系統會為逾期發票自動產生提醒通知。" }
    ]
  },
  {
    id: "w94", english: "available", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "adj", meaningGroups: [ [ "可得到的","有空的" ] ] }
    ],
    examples: [
    { en:"The manager is available for a call after 3 p.m.", zh:"經理下午三點後有空可以通話。" }
    ]
  },
  {
    id: "w95", english: "average", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "adj", meaningGroups: [ [ "平均的" ] ] },
    { pos: "nc", meaningGroups: [ [ "平均值" ] ] }
    ],
    examples: [
    { en:"The average delivery time improved by two days.", zh:"平均送貨時間縮短了兩天。" }
    ]
  },
  {
    id: "w96", english: "aware", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
    { pos: "adj", meaningGroups: [ [ "察覺到的","知道的" ] ] }
    ],
    examples: [
    { en:"Employees should be aware of the updated safety policy.", zh:"員工應該要知道最新的安全政策。" }
    ]
  }
]
```
