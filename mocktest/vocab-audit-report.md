# 單字庫稽核報告(比對劍橋詞典)

稽核日期:2026-09-26 ~ 2026-09-28
稽核來源:劍橋詞典英漢(繁體) https://dictionary.cambridge.org/dictionary/english-chinese-traditional/

稽核範圍:
- 第一批:w1 ~ w100(原始 2115 字，依 id 順序;後續 w101 起待續)
- 第二批:w2331 ~ w2398(2026-09-27 新增的 68 個字，全部稽核完成)

## 摘要(隨批次更新)

**第一批 w1~w100**
- 已稽核:100 個字
- ✅ 一致:44 個
- ⚠️ 需要修正:8 個
- ❓ 劍橋查不到:1 個
- ➕ 有缺漏義項:47 個

**第二批 w2331~w2398(新增字，已全部完成)**
- 已稽核:68 個字
- ✅ 一致:35 個
- ⚠️ 需要修正:4 個(balance、benefit、quote 已於 2026-09-28 修正完成，見下方對應條目;keep up 分組較籠統，次要，未修正)
- ❓ 劍橋查不到:11 個
- ➕ 有缺漏義項:18 個

---

## ⚠️ 需要修正

### w10 inventory
- 現有:`(nc) 庫存清單；盤點清單` `(nu) 存貨；庫存`
- 劍橋顯示:
  - `noun [C]` 某處的物品清單 → 對應「庫存清單」
  - `noun [U] US` 商店的存貨；存貨價值 → 對應「存貨；庫存」
  - `noun [U] US (UK: stocktaking)` 盤點，清點存貨 → **這是第三個獨立義項(不可數，指「盤點」這個清點動作),不是「清單」的同義詞**
- 說明:現有 `nc` 群組把「庫存清單」(可數,指清單本身)和「盤點清單」(我們自創的講法,實際劍橋沒有這個詞,劍橋的「盤點」是 `nu` 且是指清點動作本身,不是一份清單)當同義詞放在一起,分類不準確。建議：`nc` 只留「庫存清單」；「盤點」應另立一個 `nu` 群組(意思是清點存貨的動作,不是清單)。
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/inventory

### w19 thorough
- 現有:`(adj) 徹底的；全面的；仔細的`(單一群組,當同義詞處理)
- 劍橋顯示這其實是兩個不同義項:
  - `adjective (CAREFUL)` 仔細的(詳細而謹慎地做某事,如 "a thorough search")
  - `adjective (COMPLETE)` 徹頭徹尾的；完全的；十足的(當強調詞用,如 "a thorough waste of time" 完全是浪費時間)
- 建議:拆成兩個 `meaningGroups` 子陣列 → `[ ["仔細的"], ["徹底的","完全的","十足的"] ]`,而不是全部當同義詞放在一起
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/thorough

### w34 action
- 現有:`(nc) 行動；措施`
- 問題 1(詞性):劍橋在「採取行動」這個核心意思(action noun (DOING SOMETHING))標示為 **`noun [U]` 不可數**(例如 "take action" 不會說 "take an action"),但我們標成 `nc` 可數。建議改成 `nu`。
- 問題 2(缺漏義項):"action" 是高度多義字,劍橋底下還有大量常見義項完全沒收錄,包括:
  - `noun (SOMETHING DONE) [C]` （身體的）動作
  - `noun (ACTIVITY) [U]` 發生的事情，尤指令人激動的事(如 "a movie with a lot of action")
  - `noun (LEGAL PROCESS) [C or U]` **訴訟；起訴**(bring a legal action against someone)——商務/法律情境常見
  - `noun (WAY THING WORKS) [U or C]` 運作；功能
  - `verb [T]`（英式辦公室用語）對…採取行動；就…採取措施("please action this")
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/action

### w38 admission
- 現有:`(nc) 1. 承認；招認　2. 入場許可；准入`
- 問題 1(詞性):劍橋把「准許進入」(admission noun (ALLOWING IN), permission to enter) 標為 **`noun [U]` 不可數**,我們標成 `nc`,可能需要改成 `nu`(「承認」義項劍橋是 `[C or U]`,我們標 nc 不算錯)
- 問題 2(缺漏義項):劍橋在「入場許可」之外,另外還有一個**更常見的義項**完全沒收錄——`noun (ALLOWING IN) [U or C]` B1 **入場費；門票費**(the money you pay to enter,例如 "The admission charge is €5"),這個「門票費」的意思比「准許進入」更常在日常/考試中出現,建議優先新增
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/admission

### w42 advancement
- 現有:`(nc) 進步；晉升`
- 劍橋顯示:`noun [U]` 不可數,意思是「發展，提高，改善」(如 career advancement)
- 說明:劍橋這個字明確標為不可數 `[U]`,我們標成 `nc` 可數,建議改成 `nu`。另外劍橋的翻譯是「發展/提高/改善」,沒有直接給「晉升」這個譯法,但語意上算合理延伸(career advancement 常引申為升遷),不算錯譯,只是詞性需要修正
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/advancement

### w51 aid
- 現有:`(nc) 援助；補助` `(vt) 幫助；援助`
- 問題 1(詞性):劍橋「援助」這個義項(對貧弱國家的食品/金錢/醫療援助)標為 **`noun [U]` 不可數**,我們標成 `nc`,建議改成 `nu`
- 問題 2(缺漏義項):劍橋還有 `noun [C]` **輔助物，輔助工具**(a piece of equipment that helps you do something,例如 "teaching aids"教材、"a walking aid"助行器),這是可數名詞,完全沒收錄
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/aid

### w61 amusement
- 現有:`(nu) 娛樂；消遣`
- 問題:劍橋把這個字分成兩個義項——`noun [U]` **開心，愉悅，快樂**(感到有趣/好笑的「感受」,例如 "she looked at him with amusement" 她愉悅地看著他)與 `noun [C]` **娛樂（活動）；消遣（方式）**(可參與的娛樂活動,如遊樂場設施)。現有翻譯「娛樂,消遣」實際對應的是劍橋的 **`[C]` 可數**義項,但我們卻標成 `nu`；而且劍橋的 `[U]`「開心,愉悅的感受」這個義項完全沒收錄
- 建議:改成 `nc`(對應「娛樂活動」),並考慮另外新增一個 `nu`「開心,愉悅,快樂」的義項
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/amusement

### w26 a leap of faith
- 現有:`(phr.) 憑信念放手一搏；不顧風險的嘗試`
- 劍橋顯示:`idiom` an act of believing something that is not easily believed → **不易的舉動；讓人難以置信的做法**
- 說明:劍橋官方翻譯跟現有翻譯落差較大。劍橋原意比較偏「哲學/宗教脈絡下,相信一件難以證實之事」,而現有翻譯偏向「不顧風險放手一搏做某件事」(比較接近這個成語在日常/商業情境的引申用法,例句 "Investing in the startup was a leap of faith" 也是這種引申用法)。兩者意思相關但劍橋字典給的中文翻譯明顯不同,建議人工確認要採用哪個翻譯,或兩者並列
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/leap-of-faith?q=a+leap+of+faith

---

## ➕ 有缺漏義項

### w1 address
- 現有:`(vt) 1. 處理；應付　2. 向…致辭；發表演說` `(nc) 地址`
- 劍橋顯示還有:
  - `noun [C] (COMPUTERS)` 網址；電子郵件地址(電腦專業用法還有「（記憶體）位址」)——完全沒收錄
  - `noun [C] (SPEECH)` 演講，演說(名詞用法,例如 "give an address to the Royal Academy")——現有只收了動詞的「發表演說」,沒收名詞用法
  - `verb [T] (WRITE DETAILS)` 在信封或包裹上寫姓名/地址——沒收錄
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/address

### w2 account
- 現有:`(nc) 帳戶`
- 劍橋顯示還有:
  - `noun (REPORT) [C]` 報導；報告；記述；描述——沒收錄
  - `noun (BUSINESS) [C]` 賒銷帳；賒購——沒收錄
  - `noun (BUSINESS) [C]` **客戶；主顧**(例如廣告公司的 "account" 指往來客戶)——這個在商業情境很常見,TOEIC 也會考,建議優先考慮新增
  - `verb [T] (JUDGE, 正式)` 認為是；視為——較少見,優先度低
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/account

### w3 account for
- 現有:`(phr.) 說明；解釋`
- 劍橋顯示:劍橋把 "account for" 拆成兩個獨立詞條——
  - `account (to someone) for something`:對某人就…作出解釋/說明 → 對應現有的「說明；解釋」✓
  - `account for something`:**「（在數量上）佔」**(例如 "Students account for the vast majority of our customers." 學生佔了我們顧客的絕大多數)——**這個意思完全沒收錄,而且是 TOEIC 閱讀/聽力很常考的用法(例如 "Sales in Asia account for 40% of revenue")**,建議優先新增
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/account-to-for?q=account+for 、 https://dictionary.cambridge.org/dictionary/english-chinese-traditional/account-for

### w4 run
- 現有:`(vi) 跑步` `(vt) 經營；管理`
- 劍橋顯示 "run" 是極多義的字,除了現有兩個義項外還有大量常見用法沒收錄,包括(僅列較常見/職場相關的):
  - `verb (OPERATE) [I or T]` （機器/系統）運轉；運作——與現有「經營」不同,這個是指機器運轉
  - `verb (POLITICS) [I]` 參加競選(run for office)
  - `verb (SHOW) [T]` （媒體）刊登；播出
  - `noun` 大量名詞義項完全沒收錄,例如 `a run of something`(一連串,如 "a run of bad luck")、`run on the dollar`(拋售)等
- 說明:這個字本來就以極度多義聞名,現有收錄的兩個義項没有錯,但劍橋詞典下面的完整詞條非常長,建議之後可以評估要不要擴充,但不是格式錯誤,列在此處供參考
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/run

### w5 budget
- 現有:`(nc) 預算` `(vt) 編列預算`
- 劍橋顯示還有:
  - `adjective [before noun]` **低廉的**(例如 "a budget hotel/price" 廉價旅館/低廉的價格)——這個形容詞用法很常見(budget airline、budget hotel),完全沒收錄,建議新增
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/budget

### w13 negotiate
- 現有:`(vi) 談判；協商` `(vt) 協商達成；談定`
- 劍橋顯示還有:
  - `verb (MANAGE TO DO) [T]` 設法穿過，越過（難走的路段）——沒收錄
  - `verb (MANAGE TO DO) [T]` **解決（難題）**(negotiate a problem/difficulty)——沒收錄,商務情境也算常見
  - `verb (EXCHANGE) [T]`(金融專業)議付，洽兌——冷僻,優先度低
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/negotiate

### w16 quarterly
- 現有:`(adj) 每季的；季度的` `(adv) 每季地；以季為單位地`
- 劍橋顯示還有:
  - `noun [C]` **季刊雜誌**(a magazine published four times a year)——完全沒收錄
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/quarterly

### w23 yield
- 現有:`(vi) 讓步；屈服` `(vt) 產生；出產；帶來` `(nc) 產量；收益；殖利率`
- 劍橋顯示還有:
  - `verb (BEND/BREAK) [I] formal` （受壓）彎曲，折斷，垮掉——沒收錄
  - `verb (STOP) [I] US`(英式稱 give way)停車讓道(以讓其他車輛通過,常見於交通標誌 "YIELD")——沒收錄
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/yield

### w27 aboard
- 現有:`(prep) 在（船、飛機、火車等）上`
- 劍橋顯示 "aboard" 同時是 `adverb, preposition`,我們只收錄了介系詞用法,漏了副詞用法(不接受詞,單獨使用,如 "Welcome aboard!" 歡迎登機/上船、"climbing aboard" 爬上船)
- 建議:新增一個 `pos: "adv"` 的 posGroup,意思同樣是「上船（或飛機、火車等）；在船（或飛機、火車等）上」
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/aboard

### w28 absolutely
- 現有:`(adv) 絕對地；完全地`
- 劍橋顯示還有:
  - `adverb` B2 **用於強烈表示同意,單獨當回答用**(如 "It was an excellent film." "Absolutely!") → 一點不錯，完全對——這個口語用法很常見(TOEIC 聽力常考的簡短回應),完全沒收錄
  - 附帶片語 `absolutely not`(強烈的「不」)——次要,可一併考慮
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/absolutely

### w30 accomplishment
- 現有:`(nc) 成就；成果`
- 劍橋顯示還有:
  - `noun [U]` 完成；實現(the finishing of something,不可數,指「完成」這件事本身)——沒收錄
  - `noun [C]` **造詣；技能；才華**(a skill,例如 "Cordon bleu cookery is one of her many accomplishments")——沒收錄,且與現有「成就」意思不同
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/accomplishment

### w35 activity
- 現有:`(nc) 活動`
- 劍橋顯示還有:
  - `noun (MOVEMENT) [U]` **活躍；繁忙；熱鬧**(指「活動熱絡的狀態」,例如 "economic activity"、"business activity"、"a flurry of activity")——這是與「一項活動」不同的獨立義項,且是 TOEIC 商業文章常見用法(經濟活動、商業活動),完全沒收錄
- 說明:現有「活動」比較對應劍橋 `noun (ENJOYMENT)` 與 `noun (WORK)` 這兩個義項,但「活躍程度」這個不可數義項是缺漏的
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/activity

### w39 admit
- 現有:`(vt) 1. 承認　2. 准許進入；允許加入`
- 劍橋顯示還有:
  - `verb (ALLOW IN) [T]` 接收…入院；收治(admitted to hospital)——與現有「准許進入」概念相近但劍橋另外獨立列出,優先度低,僅供參考
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/admit

### w40 adopt
- 現有:`(vt) 採用；採納`
- 劍橋顯示還有:
  - `verb (TAKE INTO HOME) [T or I]` **收養；領養**(adopt a child)——這其實是 "adopt" 最基本常見的意思之一,完全沒收錄,只收了「採用政策/策略」的商務義項
  - `verb (CHOOSE) [T]` 養成（某種習慣）(adopt a habit/mannerism)——次要,沒收錄
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/adopt

### w41 advance
- 現有:`(vi) 前進；進展` `(nc) 預付款`
- 劍橋顯示還有大量常見義項沒收錄,較重要的包括:
  - `adjective [before noun]` **預先的，事先的**(advance notice/booking/payment,例如 "advance booking" 預訂、"advance notice" 事先通知)——完全沒有 `adj` 這個詞性,商務情境很常見
  - `verb (SUGGEST) [T] formal` 提出（想法或理論）(advance a theory)
  - `verb (INCREASE) [I]`（股價）上漲
  - `noun (SEX) [C usually plural]` 勾引；追求(較次要)
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/advance

### w45 advise
- 現有:`(vt) 建議；勸告`
- 劍橋顯示還有:
  - `verb [T] formal` **通知；（正式）告知**(to give official information,例如 "Please be advised that..."、"be advised of their rights")——商務書信中非常常見的正式用法,完全沒收錄
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/advise

### w48 agent
- 現有:`(nc) 代理人；經紀人`
- 劍橋顯示還有:
  - `noun (SPY) [C]` 特務；間諜——沒收錄
  - `noun (CAUSE) [C]` **原動力，動因；作用劑**(a substance that produces an effect,例如 "a cleaning agent" 清潔劑、"a raising agent" 發酵劑)——這個「作用劑」的意思跟「代理人」完全不同,常見於產品說明情境,沒收錄
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/agent

### w49 aggressive
- 現有:`(adj) 積極進取的；有企圖心的`
- 劍橋顯示還有:
  - `adjective (ANGRY) [B2]` **好鬥的；富於攻擊性的；挑釁的**——這其實是 "aggressive" 最基本、最常見的意思(帶有負面攻擊性),但現有詞庫完全沒收錄,只收了「積極進取」這個較正面的商務引申義,建議優先新增
  - `adjective (MEDICAL) specialized` （疾病）惡性的；（治療）積極手段的——較次要
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/aggressive

### w54 alcoholic
- 現有:`(adj) 含酒精的`
- 劍橋顯示還有:
  - `noun [C]` **酗酒者，嗜酒者**(a person addicted to alcohol)——完全沒收錄這個名詞詞性
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/alcoholic

### w55 alien
- 現有:`(nc) 外籍人士` `(adj) 陌生的；格格不入的`
- 劍橋顯示還有:
  - `noun [C]` **外星人（或生物）**——這其實是 "alien" 日常最常見的意思,完全沒收錄(現有只收了法律上的「外籍人士」義項)
  - `adjective [before noun]` 外星人（或生物）的(an alien spacecraft)——沒收錄
  - `adjective` 外國的；異域的；異族的(an alien culture)——與現有「陌生的」略有不同,沒明確收錄
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/alien

### w57 amateur
- 現有:`(nc) 業餘愛好者` `(adj) 業餘的`
- 劍橋顯示還有:
  - `noun [C] disapproving` **外行；不熟練的人**(someone who does not have much skill,例如 "they're a bunch of amateurs")——與「業餘愛好者」是不同的義項(帶貶義,指技術不佳的人),沒收錄
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/amateur

### w59 ambitious(次要)
- 現有:`(adj) 有野心的；雄心勃勃的`
- 劍橋把這個字拆成兩個義項:形容「人」的有抱負/雄心勃勃(✓現有已收錄),以及形容「計畫、想法」時的**要求過高的；需要極大努力及才能的；費勁的**(an ambitious plan/timeline)。現有翻譯大致可以延伸涵蓋計畫的用法,但劍橋明確獨立列出,供參考是否要新增子義項
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/ambitious

### w63 ancestor(次要)
- 現有:`(nc) 祖先`
- 劍橋顯示還有:`noun [C]` （動植物）原種；（物體）原型(a plant/animal/object that is the precursor of a later one,例如 "ancestor of the modern flute")——比喻用法,沒收錄,優先度低
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/ancestor

### w67 anxiously
- 現有:`(adv) 焦急地；憂慮地`
- 劍橋顯示還有:`adverb (EAGER)` **迫切地**(表示「渴望、殷切期待」,例如 "their anxiously awaited presents" 他們殷切期待的禮物)——這是跟「焦急/憂慮」不同的正面期待語氣,完全沒收錄
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/anxiously

### w68 apparent
- 現有:`(adj) 明顯的；顯而易見的`
- 劍橋顯示還有:`adjective [before noun] C1` **表面上的；貌似（真實）的；顯得…的**(seeming to exist or be true,但不一定是真的,例如 "her apparent innocence" 她貌似天真——暗示可能不是真的天真)——這個「表面上/貌似」的意思跟「顯而易見」明顯不同,甚至帶有相反的暗示(一個是確定為真,一個是看似為真但存疑),對閱讀理解影響較大,完全沒收錄
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/apparent

### w69 appeal
- 現有:`(vi) 吸引；有吸引力` `(nc) 申訴`
- 劍橋顯示還有:
  - `noun (REQUEST) [C]` 呼籲，籲請，求助，懇求——完全沒收錄(名詞)
  - `verb (REQUEST) [I]` 呼籲，籲請，求助，懇求——完全沒收錄(動詞)
  - `verb (LEGAL) [I]` **上訴**——現有 `nc` 只收了「申訴」這個名詞,但對應的動詞「上訴」完全沒收錄
  - `noun (QUALITY) [U]` **吸引力；魅力**(the quality that makes something attractive,例如 "sex appeal"、"Spielberg's movies have a wide appeal")——現有只有動詞「吸引」,沒有對應的名詞「吸引力」
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/appeal

### w70 appearance(次要)
- 現有:`(nc) 1. 外觀；外表　2. 出現；露面`
- 劍橋顯示還有:`noun (BEING PRESENT) [C]` **出庭**(a court appearance)——法律情境的次要用法,沒收錄,優先度低
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/appearance

### w71 apply
- 現有:`(vi) 申請；適用` `(vt) 應用；運用`
- 劍橋顯示還有:
  - `verb (PUT ON) [T]` **塗，敷**(apply cream/paint to a surface,例如防曬乳、油漆)——完全沒收錄
  - `apply yourself` `[C2]` 勤奮，努力(致力於某事)——沒收錄
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/apply

### w72 appropriate
- 現有:`(adj) 適當的；合適的`
- 劍橋顯示 "appropriate" 也是 `verb [T] formal`,完全沒收錄這個動詞詞性,包含兩個義項:
  - `verb (TAKE)` **挪用；佔用；盜用；侵吞**(未經許可佔為己用,例如侵吞公款)
  - `verb (KEEP MONEY)` **撥出（款項）**(政府撥款做特定用途,例如 "Congress appropriated millions for the project")
- 建議新增 `pos: "vt"`
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/appropriate

### w74 area
- 現有:`(nc) 區域；領域`
- 劍橋顯示還有:`noun (MEASURE) [C or U]` **面積**(the size of a flat surface,例如 "the area of a rectangle")——這是「area」很基本、常見的數學/度量意思,完全沒收錄
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/area

### w77 arouse(次要)
- 現有:`(vt) 引起；激起`
- 劍橋顯示還有:「激起…的性慾」(to cause someone to feel sexual excitement)——較敏感的次要義項,是否新增由使用者決定
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/arouse

### w78 arrest
- 現有:`(vt) 逮捕`
- 劍橋顯示還有:
  - `verb [T] (STOP) formal` 阻止；抑制(to stop the development of something,例如 "arrest the spread of cancer")——沒收錄
  - `verb [T] (MAKE NOTICE) formal` 引起（某人的）注意——沒收錄
  - `noun [C or U]` **逮捕；拘捕**(the act of arresting,如 "under arrest")——完全沒有名詞詞性
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/arrest

### w79 article
- 現有:`(nc) 1. 文章　2.（合約）條款`
- 劍橋顯示還有:
  - `noun [C] (GRAMMAR)` **冠詞**(a/an/the 這類詞)——文法詞彙,完全沒收錄
  - `noun [C] (OBJECT)` **物品，物件**(article of clothing 一件衣物)——常見用法,沒收錄
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/article

### w80 ash(次要)
- 現有:`(nu) 灰燼`
- 劍橋顯示還有:`noun [C]` 白蠟樹、`noun [U]` 白蠟木(一種樹木及其木材)——冷僻,優先度低
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/ash

### w81 aspect
- 現有:`(nc) 方面；層面`
- 劍橋顯示還有:
  - `noun (DIRECTION) [C]` 朝向；方位(建築物的朝向)——沒收錄
  - `noun (APPEARANCE) [S] formal` 外表，外觀；樣子，神態——沒收錄
  - `noun (TV) [C] MEDIA specialized` **寬高比，縱橫比**(aspect ratio,如 16:9)——沒收錄,媒體/科技情境常見
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/aspect

### w83 assembly(次要)
- 現有:`(nu) 裝配；組裝` `(nc) 集會；大會`
- 劍橋顯示還有:`noun [C] ENGINEERING specialized` **組合體；組成部件**(例如 "engine assembly" 引擎組)——製造業情境常見的可數名詞義項,沒收錄
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/assembly

### w84 assist(次要)
- 現有:`(vt) 協助；幫助`
- 劍橋顯示還有:`noun [C] SPORTS specialized` 助攻；助殺——體育專用詞,優先度低
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/assist

### w85 associate
- 現有:`(vt) 聯想；使有關連` `(nc) 同事；夥伴`
- 劍橋顯示還有:
  - `adjective [before noun]` **副的；準的；非正式的**(用於職稱,例如 "associate director"副總監、"associate professor"副教授)——這在職場/學術頭銜很常見,完全沒有 `adj` 詞性
  - `noun [C] US` 副學士(someone with an associate's degree)——較次要
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/associate

### w86 atmosphere
- 現有:`(nc) 氣氛；氛圍`
- 劍橋顯示還有:`the atmosphere [S]` **大氣，大氣層**(地球外圍的氣體層,如溫室氣體排放到大氣中)、`[S]` （特定場所的）空氣(room's air)——這是「atmosphere」最基本/字面的意思(地球大氣層),完全沒收錄,現有只收了「氣氛」這個引申義
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/atmosphere

### w87 attempt(次要)
- 現有:`(vt) 嘗試` `(nc) 嘗試；企圖`
- 劍橋顯示還有:`noun [C] (IN SPORT)` 射門(足球比賽中的 attempt on goal)——體育用語,優先度低
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/attempt

### w88 attend
- 現有:`(vt) 出席；參加`
- 劍橋顯示還有:
  - `verb (NOTICE) [I] formal` **注意；傾聽**(attend to what's being said)——沒收錄
  - `verb (PROVIDE HELP) [T]` （尤指工作上）服侍；陪同；看護，照顧(attend to a patient)——沒收錄
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/attend

### w89 attitude(次要)
- 現有:`(nc) 態度`
- 劍橋顯示還有:`noun (CONFIDENCE) [U]` 自信(informal,指「很有個性、想引人注目」的自信,如 "she's got attitude")——較口語的次要義項,沒收錄
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/attitude

### w91 author
- 現有:`(nc) 作者`
- 劍橋顯示還有:
  - `noun [C] formal` 發起者，始創人(the author of our troubles - 造成某事的人)——沒收錄
  - `verb [T] formal` **撰寫，寫作；編寫**(he has authored 30 books)——完全沒有動詞詞性
  - `verb [T] mainly US` 發起，創造——沒收錄
- 建議新增 `pos: "vt"`
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/author

### w92 authority
- 現有:`(nu) 權威；權力` `(nc) 當局；主管機關`
- 劍橋顯示還有:`noun (EXPERT) [C]` **權威人士；專家；泰斗**(an expert on a subject,如 "a world authority on Irish history")——與現有兩個義項都不同,沒收錄
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/authority

### w93 automatic
- 現有:`(adj) 自動的`
- 劍橋顯示還有:
  - `adjective (NOT CONSCIOUS)` 無意識的，不自覺的；機械的(automatic response,不假思索的反應)——沒收錄
  - `adjective (CERTAIN)` **必然隨之發生的；自然而然的**(automatic promotion 自動晉升、automatic renewal 自動續約)——商務情境常見,沒收錄
  - `noun [C]` 自動變速汽車——完全沒有名詞詞性
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/automatic

### w95 average
- 現有:`(adj) 平均的` `(nc) 平均值`
- 劍橋顯示還有:
  - `verb [T]` **平均數是，平均為**(例如 "employees average 70 hours a week")——完全沒有動詞詞性
  - `adjective (USUAL)` **普通的；平常的；中等的；一般的**(跟「平均的」數學義不同,是「普通/一般」的意思,如 "an average student" 中等程度的學生)——與現有「平均的」意思不同,沒收錄
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/average

### w96 aware(次要)
- 現有:`(adj) 察覺到的；知道的`
- 劍橋顯示還有:「有…意識的；有…覺悟的」(例如 "ecologically aware" 有環保意識的、"politically aware" 有政治意識的)——與「知道某事實」略有不同的子義項(指對某領域有涉獵/敏銳度),現有翻譯大致可涵蓋,優先度低
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/aware

---

## ✅ 一致

- w6 colleague — `(nc) 同事` 與劍橋 `noun [C]` 同事；同僚 一致
- w7 deadline — `(nc) 截止日期；期限` 與劍橋 `noun [C]` 最後期限；截止日期 一致
- w8 efficient — `(adj) 有效率的；效率高的` 與劍橋 `adjective` 效率高的 一致
- w9 feasible — `(adj) 可行的` 與劍橋 `adjective` 可行的；行得通的 一致
- w11 logistics — `(nu) 物流；後勤` 與劍橋 `noun [plural]` 後勤；後勤學 一致(劍橋文法上是恆用複數形,但語意對應沒問題)
- w12 merger — `(nc) 合併案；合併` 與劍橋 `noun [C]` （公司、企業等的）合併 一致
- w14 outcome — `(nc) 結果；成果` 與劍橋 `noun [C]` 結果，後果；效果 一致
- w15 proficient — `(adj) 熟練的；精通的` 與劍橋 `adjective` 熟練的；精通的 一致
- w17 reimburse — `(vt) 償還；報銷` 與劍橋 `verb [T]` 償還；付還；補償 一致
- w18 supervise — `(vt) 監督；督導；管理` 與劍橋 `verb [I or T]` 監督，管理，指導 一致(劍橋顯示不及物也可用,我們只收 vt,不算錯)
- w20 undergo — `(vt) 經歷；接受；經受` 與劍橋 `verb [T]` 經歷，經受（令人不快的事或變化）一致
- w21 vendor — `(nc) 供應商；廠商` 與劍橋 `noun [C]` 賣主；賣方 核心意思一致(劍橋例句偏「小販/房屋賣方」,「供應商」是常見的商業延伸用法,不算錯)
- w22 warranty — `(nc) 保固；保固書；保證書` 與劍橋 `noun [C]` （商品的）保用單，保用卡 一致(僅為兩岸用語差異:保固 vs 保用)
- w24 zeal — `(nu) 熱忱；熱情；熱誠` 與劍橋 `noun [S or U]` 熱忱，熱情；激情 一致
- w29 accident — `(nc) 意外；事故` 與劍橋 `noun [C]` 意外；不測；事故 一致
- w31 accurate — `(adj) 準確的；精確的` 與劍橋 `adjective` 準確的；精確的；正確的 一致
- w32 achieve — `(vt) 達成；實現` 與劍橋 `verb [T]` 完成；達到；實現 一致
- w33 acre — `(nc) 英畝` 與劍橋 `noun [C]` 英畝 一致
- w36 adapt — `(vi) 適應` `(vt) 使…適應；改編` 與劍橋 `verb [I]` 適應 / `verb [T]` 使適應…；改編 一致
- w37 additional — `(adj) 額外的；附加的` 與劍橋 `adjective` 外加的，附加的；額外的 一致
- w43 adventure — `(nc) 冒險；奇遇` 與劍橋 `noun [C or U]` 冒險，歷險；奇遇；刺激 一致
- w44 advertising — `(nu) 廣告業；廣告活動` 與劍橋 `noun [U]` 廣告（業） 一致
- w46 affiliate — `(nc) 附屬機構；分支機構` `(vt) 使隸屬；使加盟` 與劍橋 `noun [C]` 隸屬機構 / `verb [T]` 使隸屬 一致
- w47 affordable — `(adj) 負擔得起的；價格合理的` 與劍橋 `adjective` 付得起的；買得起的 一致
- w50 agriculture — `(nu) 農業` 與劍橋 `noun [U]` 農業 一致
- w52 airline — `(nc) 航空公司` 與劍橋 `noun [C]` 航空公司 一致
- w53 alarming — `(adj) 令人擔憂的；驚人的` 與劍橋 `adjective` 使人驚恐的；令人擔憂的 一致
- w56 aluminum — `(nu) 鋁` 與劍橋 `noun [U]`(aluminium) 鋁 一致
- w58 amaze — `(vt) 使驚訝；使驚奇` 與劍橋 `verb [T]` 使大為驚奇，使驚愕 一致
- w60 amount — `(nc) 數量；金額` 與劍橋 `noun [C]` 數量；數額；量；總數 一致
- w62 analyze/analyse — `(vt) 分析` 與劍橋 `verb [T]` 分析 一致(analyze 為美式拼法,劍橋標為 analyse 的美式拼寫)
- w64 ancient — `(adj) 古老的；古代的` 與劍橋 `adjective` 古代的；古老的 一致
- w65 announcement — `(nc) 公告；宣布` 與劍橋 `noun [C or U]` 公告，佈告；通告 一致
- w66 annoy — `(vt) 使惱怒；使煩躁` 與劍橋 `verb [T]` 煩擾；打攪；使煩惱 一致
- w73 approval — `(nu) 核准；批准；贊同` 與劍橋 `noun [U]` 贊成/批准 一致
- w75 arguably — `(adv) 可以說；按理來說` 與劍橋 `adverb` 大概，可能 意思相近,一致
- w76 armed — `(adj) 1. 武裝的　2. 配備的；具備的` 第一義項與劍橋 `adjective` 武裝的 一致；第二義項(配備資訊/工具的)劍橋這一頁沒有明確獨立列出,但屬於「攜帶」的合理比喻延伸,不算查無此意
- w82 assemble — `(vt) 組裝；集合` 與劍橋 `verb (GATHER)` 集合，聚集 / `verb (JOIN)` 組裝；裝配 一致
- w90 attract — `(vt) 吸引` 與劍橋 `verb [T]` 吸引；招引；引起 一致
- w94 available — `(adj) 可得到的；有空的` 與劍橋 `adjective` 可獲得的；可用的／可取得聯繫的 一致
- w97 retaliate — `(vi) 報復；反擊` 與劍橋 `verb [I]` 報復；反擊 一致
- w98 enlist — `(vt) 徵募；爭取（支持、協助）` `(vi) 從軍；入伍` 與劍橋 `verb (ASK FOR HELP)` 爭取，謀取（幫助或支援）／`verb (JOIN)` 從軍，入伍 一致
- w99 tetanus — `(nu) 破傷風` 與劍橋 `noun [U]` 破傷風 一致
- w100 monotony — `(nu) 單調；乏味` 與劍橋 `noun [U]` 單調乏味；毫無變化 一致

---

## ❓ 劍橋查不到

### w25 a game of cat and mouse
- 現有:`(phr.) 貓捉老鼠的把戲；互相追逐周旋的局面`
- 說明:劍橋詞典**沒有**「a game of cat and mouse」這個詞條,查詢會被導到拼字建議頁。劍橋收錄的是動詞片語 **`play cat and mouse`**(玩貓捉老鼠的遊戲；耍弄——意指「用計謀讓對方出錯藉此佔上風」),意思跟現有收錄的「互相追逐周旋的局面」相近但不完全相同,詞性也不同(劍橋是動詞片語,不是名詞片語)。「a cat-and-mouse game」作為名詞用法在一般英文中也算常見,但劍橋詞典沒有單獨收錄這個名詞形式的詞條。建議人工確認:要不要把 `english` 改成劍橋實際收錄的 `play cat and mouse`,或保留現有名詞用法但註明劍橋查無此確切詞條
- 查詢網址:https://dictionary.cambridge.org/search/english-chinese-traditional/direct/?q=a%20game%20of%20cat%20and%20mouse (查無,自動導向拼字建議) 、 https://dictionary.cambridge.org/dictionary/english-chinese-traditional/play-cat-and-mouse (劍橋實際收錄的相近詞條)

---

# 第二批次:w2331 ~ w2398(2026-09-27 新增的 68 個新字，全部稽核完成)

稽核日期:2026-09-28
說明:這 68 個字(w2331~w2398)是在第一批稽核完成後才新增進 `vocab-bank.md` 的，id 編號接續在原本 2115 字之後。分兩次稽核完成:先做 w2331~w2380(前 50 個)，再做 w2381~w2398(後 18 個)，以下結果已合併。

## ⚠️ 需要修正

### w2342 balance
- 現有:`(nc) 帳戶餘額；結餘` `(vt) 使平衡；權衡`
- 劍橋顯示:劍橋把 balance 的名詞義項分成三組，排序第一、最基本的義項是 `noun (EQUAL STATE) [S or U]` **「平衡」**(物理或抽象意義上的平衡狀態，如 "lost his balance" 失去平衡、"strike a balance" 取得平衡)——這個最核心、最常用的意思**完全沒有收錄**，現有條目只收了 `noun (MONEY) [C usually singular]` 「結存，結餘」這個較窄的商務義項。
- 另外動詞部分，劍橋把「（使）平衡」`[I or T]`(物理站立不倒)、「權衡，斟酌」`[T]`(給予同等重要性)、「使收支平衡」`[T]`(帳目)拆成三個略有差異的義項，我們的 `vt` 群組「使平衡；權衡」把前兩者合併在一起，分組較籠統，但不算錯。
- 建議:優先補上最基本的「平衡」這個名詞義項(EQUAL STATE)，這是 TOEIC / 日常英文中 balance 最常出現的用法。
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/balance
- **✅ 已於 2026-09-28 修正**:在 `vocab-bank.md` 與 `cycle_mode_mvp.html` 補上 `{ pos: "nu", meaningGroups: [ ["平衡"] ] }` 並新增對應例句。

### w2344 benefit
- 現有:`(nc) 福利；津貼` `(vi) 獲益`
- 劍橋顯示:劍橋名詞排序第一、最基本的義項是 `noun (ADVANTAGE) [C or U]` **「利益，好處；優勢」**(如 "the benefits of foreign travel")——這個最核心的意思**完全沒有收錄**，現有條目只收了 `[C, usually plural]`「（僱主為員工提供的）福利政策」這個較窄的商務義項(對應「福利，津貼」)。
- 動詞 `verb [I or T]` B2「得益，受惠」對應「獲益」一致(劍橋顯示及物不及物皆可，我們只收 vi 不算錯)。
- 另有 `noun (MONEY FROM GOVERNMENT)` UK「（政府）補助金，救濟金」、`noun (EVENT)`「義演、義賣」未收錄，較次要。
- 建議:優先補上最基本的「利益，好處」這個名詞義項，這比「福利」更常見、更基礎。
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/benefit
- **✅ 已於 2026-09-28 修正**:在 `vocab-bank.md` 與 `cycle_mode_mvp.html` 的 `nc` 群組補上 `["利益","好處"]` 作為第一義項，並新增對應例句。

### w2379 quote
- 現有:`(nc) 報價` `(vt) 報價`
- 劍橋顯示:劍橋動詞排序第一、最基本的義項是 `verb (SAY) [I or T]` C1 **「引用，引述，援引」**(如 "He's always quoting from the Bible.")——這個最核心、最常用的意思**完全沒有收錄**，現有條目只收了 `verb (GIVE PRICE) [T]` C2「報價」這個較窄的商務義項。
- 名詞 `noun (PRICE) [C]` C2「報價」對應現有「報價」一致。
- 另有 `noun (SYMBOLS)` "quotes"「引號」未收錄，較次要。
- 建議:優先補上「引用，引述」這個動詞義項，這是 quote 最基本、最常見的用法。
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/quote
- **✅ 已於 2026-09-28 修正**:在 `vocab-bank.md` 與 `cycle_mode_mvp.html` 的 `vt` 群組補上 `["引用","引述","援引"]` 作為第一義項，並新增對應例句。

### w2395 keep up(次要)
- 現有:`(phr.) 跟上,維持`
- 劍橋顯示:劍橋把 keep up 相關的片語動詞拆成好幾個不同詞條，包括不及物的 `keep up` B2「跟上（變化、形勢等）」，以及及物的 `keep something up` B1「使不下降；使保持在高水準」和 `keep (something) up` B1「（使）繼續下去，不停止」。我們把「跟上」和「維持」當同義詞放在同一個 meaningGroup 裡，但這其實對應劍橋不同及物性的片語動詞，語意上有微妙差異(不算錯，但分組可以更精確)，跟第一批 w19 thorough 的情況類似。
- 查詢網址:https://dictionary.cambridge.org/search/english-chinese-traditional/direct/?q=keep%20up

---

## ➕ 有缺漏義項

### w2336 application
- 現有:`(nc) 申請書；申請表`
- 現有義項與劍橋 `application noun (REQUEST) [C or U]` B1「（通常指書面的）申請，請求」一致。但 application 是高度多義字，劍橋還有大量常見義項完全沒收錄:
  - `noun (COMPUTER) [C]` B2 **「應用軟體」**(如 "spreadsheet applications")——這在辦公室/科技情境中非常常見，優先度高
  - `noun (USE) [C or U]` C2「用途，用法;應用」
  - `noun (HARD WORK) [U]`「勤奮；努力；專心致志」
  - `noun (PUTTING ON) [C or U]`「塗抹;敷用」(乳液、油漆等)
  - `noun (RELATION TO) [C or U]`「（法律，規定等的）適用」
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/application

### w2337 appointment
- 現有:`(nc) 預約；約定`
- 現有義項與劍橋 `appointment noun (ARRANGEMENT)` A2「約會;預約;約定」一致。但劍橋還有 `appointment noun (JOB) [C or U]` C2「任命，委派」完全沒收錄(如 "the appointment of Julia Lewis as head of sales")，這在商務英文中也很常見。
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/appointment

### w2338 arrangement(次要)
- 現有:`(nc) 安排；準備事宜`
- 現有義項與劍橋 `arrangement noun (PLAN)`「安排；籌劃；準備（工作）」一致。劍橋另有 `noun (POSITION) [C]`「排列，安排」(物品擺放方式，如插花)及 `noun (MUSIC) [C]`「改編曲」完全沒收錄，較次要。
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/arrangement

### w2339 assistant(次要)
- 現有:`(nc) 助理`
- 現有義項與劍橋 `noun [C]` B1「助手；幫手；助理」一致。劍橋另有 A2 UK「店員；營業員；售貨員」("a sales/shop assistant")完全沒收錄，較次要。
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/assistant

### w2345 board
- 現有:`(nc) 董事會` `(vt) 登上（交通工具）`
- 現有義項對應劍橋 `board noun (PEOPLE)`「董事會;理事會;委員會」與 `board verb (GET ON)`「（使）上（船、火車或飛機）」，皆一致。但 board 是高度多義字，劍橋還有很多基本義項完全沒收錄，包括 `noun (WOOD) [C]`「（有特定用途的）薄木板;板;牌子」(黑板、棋盤、佈告欄、跳板等都屬於這個義項下的細分)及 `noun (MEALS) [U]`「（住宿處提供的）伙食，膳食」(常見於 "room and board")。因為單字庫是商務情境導向，可能是刻意只收商務相關意思，建議使用者確認是否要保持現狀。
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/board

### w2347 bonus(次要)
- 現有:`(nc) 獎金；紅利`
- 現有義項與劍橋 `noun [C]` B2「奬金；花紅；紅利；津貼」一致。劍橋另有第二義項 B2「另外的優點;額外的好處」(pleasant extra thing)完全沒收錄，較次要。
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/bonus

### w2350 capacity
- 現有:`(nu) 產能；容量`
- 現有義項與劍橋 `capacity noun (AMOUNT) [U or C]` B2「容積，容量;生產能力;（尤指某人或某組織的）辦事能力」一致。但劍橋另有 `capacity noun (POSITION) [S]` formal C1「職位;工作;角色」(如 "in her capacity as...")完全沒收錄，這在正式商務文書中相當常見。
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/capacity

### w2351 catalog(次要)
- 現有:`(nc) 商品目錄`
- 劍橋以英式拼法 catalogue 為主詞條(catalog 為美式拼法)。現有義項與 `catalogue noun (LIST) [C]` B2「（商品）目錄冊」一致。劍橋另有「（某處書籍、繪畫作品等的）目錄」、`noun (BAD EVENTS) [S]`「一連串（壞事情）」、動詞「紀錄；編入目錄」完全沒收錄，較次要。
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/catalog

### w2353 certificate(次要)
- 現有:`(nc) 證書；證明書`
- 現有義項與劍橋兩個名詞義項「證書;證明」、「成績合格證書;畢業證書」皆一致。劍橋另有 `certificate verb [T]` UK「證書;證明」(提供官方文件證明某事)完全沒收錄動詞用法，較次要。
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/certificate

### w2354 client(次要)
- 現有:`(nc) 客戶`
- 現有義項與劍橋 `client noun [C] (CUSTOMER)` B2「客戶;顧客，主顧;委託人」一致。劍橋另有 `client noun [C] (COMPUTER)`「（連接在伺服器上的）客戶機」完全沒收錄，屬電腦術語，較次要。
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/client

### w2362 discount
- 現有:`(nc) 折扣` `(vt) 給予折扣`
- 現有義項對應劍橋 `noun [C]`「減價，打折」與 `discount verb (REDUCE) [T often passive]`「減價，打折」皆一致。但劍橋動詞還有另一個完全獨立、且相當常見的義項 `discount verb (NOT CONSIDER) [T]`「忽視，忽略，不理會」(如 "You shouldn't discount the possibility of him coming back.")完全沒收錄，這個意思跟「打折」完全不同，屬於重要缺漏。
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/discount

### w2364 departure(次要)
- 現有:`(nc) 啟程；出發`
- 現有義項與劍橋 `departure noun (LEAVING) [C]` B1「（人、交通工具等）離開;啟程，出發」一致。劍橋同一義項下還包含「離職，辭職」的用法(如 "Graham's sudden departure")，以及獨立的 `departure noun (CHANGE)`「偏離，背離，脫離」未特別收錄，較次要，但「離職」這個延伸用法在商務新聞中不少見。
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/departure

### w2366 facility(次要)
- 現有:`(nc) 設施`
- 現有義項與劍橋 `facility noun (BUILDING) [C]` B1「（尤指包含多個建築物，有特定用途的）場所」及複數 facilities「設施」一致。劍橋另有 `facility noun (ABILITY) [C or U]` B2「天資，才能」及「（產品的）功能」(如 "overdraft facility" 透支額度)完全沒收錄，較次要但「功能」義項在產品說明情境中也算常見。
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/facility

### w2372 interview(次要)
- 現有:`(nc) 面試` `(vt) 面試（某人）`
- 現有義項與劍橋「面試;面談」及對應動詞用法一致。劍橋名詞另有「採訪」(新聞媒體)及「訊問」(警方偵訊)兩個義項完全沒收錄，較次要。
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/interview

### w2377 partner(次要)
- 現有:`(nc) 合夥人；合作夥伴`
- 現有義項與劍橋「一般夥伴，同伴」及 B2「（公司的）合夥人」一致。劍橋另有 B1「配偶；情人；性伴侶」、A2「舞伴」及動詞用法「（在運動/舞蹈中）與…搭檔」、「與…合夥」完全沒收錄，較次要(與商務情境關聯度較低)。
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/partner

### w2378 qualification(次要)
- 現有:`(nc) 資格；合格證明`
- 現有義項與劍橋 `qualification noun (TRAINING)`「合格證書，資格證明」及「資歷，資格;條件」一致。劍橋另有 `noun (COMPETITION) [U]` C1「（取得）比賽資格」及 `noun (LIMIT) [C]`「（附加的）限制條件」(如 "with the qualification that...")完全沒收錄，較次要，但後者在正式文書中偶爾出現。
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/qualification

### w2380 rental(次要)
- 現有:`(nc) 租金；租賃`
- 現有義項與劍橋 `[C or U]`「出租，租賃，租借；租金，租費」一致。劍橋另有 `[C]` mainly US「租用的物品（如房屋、汽車、單車等）」(如 "Is that your car or is it a rental?")完全沒收錄，較次要。
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/rental

### w2387 tax(次要)
- 現有:`(nc) 稅金,稅款`
- 現有義項與劍橋 `noun [C or U]` B1「稅;稅款」一致。但完全沒收錄動詞用法:`tax verb (MONEY) [T]` C1「對…徵稅，對…課稅」(如 "Husbands and wives may be taxed jointly.")，這在商務/報稅情境也算常見；另有 `tax verb (NEED EFFORT)`「使負重擔；使大傷腦筋」較次要冷僻。
- 查詢網址:https://dictionary.cambridge.org/dictionary/english-chinese-traditional/tax

---

## ✅ 一致

- w2331 mess up — `(phr.) 搞砸,弄糟` 與劍橋 `phrasal verb with mess` informal B2「搞砸，弄糟」一致
- w2332 batch — `(nc) 一批,批次` 與劍橋 `noun [C]`「一批，一組」一致
- w2334 accountant — `(nc) 會計師` 與劍橋 `noun [C]` B1「會計;會計師」一致
- w2335 advertisement — `(nc) 廣告` 與劍橋 `noun [C]` A2「廣告;啟事」一致
- w2340 assistance — `(nu) 協助,援助` 與劍橋 `noun [U]` B2「幫助；協助；援助」一致
- w2341 attendance — `(nu) 出席,出席人數` 與劍橋 `attendance noun (BEING PRESENT)`「出席，參加」與「出席人數」皆一致
- w2343 banquet — `(nc) 宴會,晚宴` 與劍橋 `noun [C]`「（正式的）宴會」一致
- w2346 boarding pass — `(nc) 登機證` 與劍橋 `noun [C]`「登機證;登船證」一致
- w2348 briefing — `(nc) 簡報,說明會` 與劍橋 `noun [C or U]`「簡報，簡要介紹；簡明指示；簡報會」一致
- w2352 CEO — `(nc) 執行長` 與劍橋 `noun [C]`「執行長（chief executive officer的縮寫）」完全吻合
- w2355 committee — `(nc) 委員會` 與劍橋 `noun [C, + sing/pl verb]` B2「（代表較大的組織決策或搜集資訊的）委員會」一致
- w2358 credit card — `(nc) 信用卡` 與劍橋 `noun [C]` A1「信用卡」一致
- w2359 customer — `(nc) 顧客,客戶` 與劍橋 `noun [C]` A2「顧客，主顧，客戶」一致
- w2360 deposit — `(nc) 訂金,押金` `(vt) 存放,支付訂金` 與劍橋 `deposit noun (MONEY)`「預繳費用，定金」/「押金」及 `deposit verb (MONEY)`「存放，儲存」/「支付押金、訂金」一致(劍橋另把一般性「留下」的意思獨立列為 `deposit verb (LEAVE)`，我們的 vt 群組只涵蓋金錢相關用法，不算錯，只是分組較籠統)
- w2361 description — `(nc) 說明,描述` 與劍橋 `noun [C or U]` B1「描述，描寫，描繪」一致
- w2363 duty — `(nc) 職責,責任` `(nu) 關稅` 與劍橋 `duty noun (RESPONSIBILITY) [C or U]`「責任；義務」及 `duty noun (TAX) [C or U]`「稅;（尤指進口）關稅」一致(劍橋兩個義項都是 [C or U]，我們各自只選一種不算錯)
- w2365 employee — `(nc) 員工` 與劍橋 `noun [C]` B1「受僱者，僱員，員工」一致
- w2367 fee — `(nc) 費用` 與劍橋 `noun [C]` B1「報酬;服務費;費用」一致
- w2368 file — `(nc) 檔案` `(vt) 歸檔,提交` 與劍橋 `file noun (COMPUTER)`「（電腦的）檔案，文檔」/`file noun (CONTAINER)`「文件箱，文件夾」及 `file verb (STORE/RECORD INFORMATION)`「把…歸檔」/`file verb (LAW)`「（法庭）提出（訴訟）」一致
- w2369 floor plan — `(nc) 樓層平面圖` 與劍橋 `noun [C]`「（建築物的）平面圖」一致
- w2371 headset — `(nc) 耳機（含麥克風）` 與劍橋 `noun [C]`「（尤指帶有話筒的）一副耳機」一致
- w2373 logo — `(nc) 商標,標誌` 與劍橋 `noun [C]` B1「（公司的）標誌，標識」一致
- w2381 salesperson — `(nc) 業務員,銷售員` 與劍橋 `noun [C]` A2「售貨員；推銷員」一致
- w2383 software — `(nu) 軟體` 與劍橋 `noun [U]` A2「（電腦）軟體」一致
- w2384 staff — `(nu) 員工（總稱）` 與劍橋 `staff noun (PEOPLE) [S, +sing/pl verb]` A2「全體員工，全體僱員」語意一致(劍橋標記為特殊的單數集合用法，不是典型的不可數名詞，但我們歸類為 nu 不算錯)
- w2385 stationery — `(nu) 文具` 與劍橋 `noun [U]`「文具」一致
- w2386 survey — `(nc) 調查` `(vt) 調查` 與劍橋 `survey noun (QUESTIONS) [C]` B2「調查」及 `survey verb (QUESTIONS) [T]` C1「調查」一致
- w2388 whiteboard — `(nc) 白板` 與劍橋 `noun [C]`「白色書寫板」/「手寫板（電子設備）」一致
- w2389 zone — `(nc) 區域` 與劍橋 `noun [C]` B1「（尤指有不同特徵或用途的）地帶，地區」一致
- w2391 fill out — `(phr.) 填寫` 與劍橋 `fill something in/out` A2「填寫（正式文件）」一致(注意:劍橋把「fill out」單獨列為不及物用法時意思是「發福，長胖」，我們對應的其實是及物的「fill something in/out」詞條，查詢時要用完整詞條名稱才查得到正確翻譯，但我們收錄的中文意思本身是對的)
- w2393 look forward to — `(phr.) 期待` 與劍橋 `look forward to something` B1「盼望，期盼」一致
- w2394 narrow down — `(phr.) 縮小範圍` 與劍橋 `narrow something down` C2「把…縮減，壓縮」一致
- w2396 sign up — `(phr.) 報名,註冊` 與劍橋 `sign up` B1「報名參加（某項有組織的活動）」一致
- w2397 take place — `(phr.) 舉行,發生` 與劍橋 `place` 詞條下的 idiom `take place` B1「舉行」一致
- w2398 on time — `(phr.) 準時` 與劍橋 `time` 詞條下的文法說明及相關片語 `(right/dead/bang) on time`「極為準時」一致(劍橋沒有把「on time」單獨列為一個詞條，但文法說明明確定義「on time = at the scheduled time」，語意吻合)

---

## ❓ 劍橋查不到

### w2333 intended recipient
- 現有:`(nc) 預定收件人,指定收件人`
- 說明:劍橋英漢繁體詞典查無「intended recipient」這個詞條，搜尋會導向拼字建議頁（只顯示 "intended recipient collocation" 建議連結，點進去也無詞條內容）。這是 intended(形容詞) + recipient(名詞) 組成的自由片語，語意合理常見(常見於商用信件的免責聲明)，但並非劍橋收錄的獨立詞條。
- 查詢網址:https://dictionary.cambridge.org/search/english-chinese-traditional/direct/?q=intended%20recipient

### w2349 business trip
- 現有:`(nc) 商務出差`
- 說明:劍橋英漢繁體詞典查無「business trip」的中文對照詞條，查詢會自動導向純英文版(English Dictionary / Business English Dictionary)，只給英文釋義「a journey taken for business purposes」，沒有中文翻譯頁面。語意上與「商務出差」完全吻合，只是劍橋的英漢雙語版沒有收錄這個複合詞的翻譯詞條。
- 查詢網址:https://dictionary.cambridge.org/search/english-chinese-traditional/direct/?q=business%20trip (導向純英文版 https://dictionary.cambridge.org/dictionary/english/business-trip)

### w2356 conference room
- 現有:`(nc) 會議室`
- 說明:劍橋英漢繁體詞典完全查無此詞條，連英文版也沒有，搜尋只導向拼字建議頁(建議 conference call 等不相關詞)。這是自由片語(conference + room)，語意合理常見，但非劍橋收錄詞條。
- 查詢網址:https://dictionary.cambridge.org/search/english-chinese-traditional/direct/?q=conference%20room

### w2357 copy machine
- 現有:`(nc) 影印機`
- 說明:劍橋詞典完全查無此詞條，搜尋建議頁甚至沒有相關的 collocation 建議連結(比 conference room 更徹底查無)。劍橋詞典收錄的對應詞是 `photocopier`，沒有「copy machine」這個美式口語複合詞的獨立詞條。
- 查詢網址:https://dictionary.cambridge.org/search/english-chinese-traditional/direct/?q=copy%20machine

### w2370 front desk
- 現有:`(nc) 櫃檯`
- 說明:劍橋英漢繁體詞典查無中文對照詞條，查詢導向純英文版 Business English Dictionary，釋義「a desk near the entrance to a hotel, office building, etc.」，語意與「櫃檯」完全吻合，只是英漢雙語版沒有收錄這個詞條的翻譯。
- 查詢網址:https://dictionary.cambridge.org/search/english-chinese-traditional/direct/?q=front%20desk (導向純英文版 https://dictionary.cambridge.org/dictionary/english/front-desk)

### w2374 lunch meeting
- 現有:`(nc) 午餐會議`
- 說明:劍橋詞典完全查無此詞條(連英文版也沒有)，搜尋建議頁沒有相關 collocation 連結。這是自由片語(lunch + meeting)，語意合理，但非劍橋收錄詞條。
- 查詢網址:https://dictionary.cambridge.org/search/english-chinese-traditional/direct/?q=lunch%20meeting

### w2375 main branch
- 現有:`(nc) 總行,總公司`
- 說明:劍橋詞典查無此詞條，搜尋只建議 "main branch collocation"(點進去無內容)及一些不相關詞(olive branch 等)。這是自由片語(main + branch)，語意合理常見於銀行業情境，但非劍橋收錄詞條。
- 查詢網址:https://dictionary.cambridge.org/search/english-chinese-traditional/direct/?q=main%20branch

### w2376 meeting room
- 現有:`(nc) 會議室`
- 說明:劍橋英漢繁體詞典查無中文對照詞條，查詢導向純英文版 Business English Dictionary，釋義「a room that is used for meetings」，語意與「會議室」完全吻合，只是英漢雙語版沒有收錄這個詞條的翻譯。
- 查詢網址:https://dictionary.cambridge.org/search/english-chinese-traditional/direct/?q=meeting%20room (導向純英文版 https://dictionary.cambridge.org/dictionary/english/meeting-room)

### w2382 shuttle bus
- 現有:`(nc) 接駁車`
- 說明:劍橋詞典查無此詞條，搜尋只建議 "shuttle bus collocation"(點進去無內容)。這是自由片語(shuttle + bus)，語意合理常見，但非劍橋收錄詞條。
- 查詢網址:https://dictionary.cambridge.org/search/english-chinese-traditional/direct/?q=shuttle%20bus

### w2390 apply for
- 現有:`(phr.) 申請`
- 說明:劍橋英漢繁體詞典查無中文對照詞條，查詢導向純英文版 Cambridge Advanced Learner's Dictionary，釋義「If you apply for something, you request it, usually officially, especially in writing or by sending in a form」，語意與「申請」完全吻合，只是英漢雙語版沒有收錄這個詞條的翻譯。
- 查詢網址:https://dictionary.cambridge.org/search/english-chinese-traditional/direct/?q=apply%20for (導向純英文版 https://dictionary.cambridge.org/dictionary/english/apply-for)

### w2392 get in touch with
- 現有:`(phr.) 與…取得聯繫`
- 說明:劍橋詞典查無此詞條(連英文版也沒有)，搜尋建議頁沒有相關 collocation 連結，只建議一些拼字相近但不相關的詞(get it over with 等)。這是自由片語(get + in touch + with)，語意合理常見，但非劍橋收錄詞條。
- 查詢網址:https://dictionary.cambridge.org/search/english-chinese-traditional/direct/?q=get%20in%20touch%20with
