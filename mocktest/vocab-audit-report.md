# 單字庫稽核報告(比對劍橋詞典)

稽核日期:2026-09-26
稽核範圍:w1 ~ w100(第一批,依 id 順序;後續批次待續)
稽核來源:劍橋詞典英漢(繁體) https://dictionary.cambridge.org/dictionary/english-chinese-traditional/

## 摘要(隨批次更新)
- 目前已稽核:100 個字(w1~w96、w97~w100)
- ✅ 一致:44 個
- ⚠️ 需要修正:8 個
- ❓ 劍橋查不到:1 個
- ➕ 有缺漏義項:47 個

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
