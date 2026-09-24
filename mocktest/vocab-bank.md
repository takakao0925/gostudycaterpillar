# 循環模式單字庫（Vocab Bank）

> 這份檔案是 [cycle_mode_mvp.html](cycle_mode_mvp.html) 裡 `defaultWordBank()` 函式的**內容鏡像**（source of truth 的人類/AI 可讀版本）。
> 修改流程：先在這份 md 裡加字／改字 → 再把對應的 JS 物件貼進 `cycle_mode_mvp.html` 的 `defaultWordBank()` 陣列裡。這份 md **不會被網頁直接讀取**，單純是給人與其他 AI 編輯、對照用的。
> 加字前請先讀 [vocab-bank-guidelines.md](vocab-bank-guidelines.md)，裡面是格式規則。

目前共 **2115 個字**，最後使用的 id 是 `w2329`（下一個新字從序號更大的 id 開始，請先確認目前最大值）。

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
| retaliate | (vi) 報復；反擊 |
| enlist | (vt) 徵募；爭取（支持、協助）　(vi) 從軍；入伍 |
| tetanus | (nu) 破傷風 |
| monotony | (nu) 單調；乏味 |
| labyrinth | (nc) 迷宮；錯綜複雜的事物 |
| calico | (nu) 印花棉布 |
| delegation | (nc) 代表團　(nu) 授權；委派 |
| cumbersome | (adj) 笨重的；累贅的；繁瑣的 |
| visceral | (adj) 發自本能的；直覺的 |
| adjourn | (vt) 休會；延期；暫停（會議） |
| drivel | (vi) 胡言亂語；說廢話 |
| scandalously | (adv) 可恥地；駭人聽聞地 |
| conformance | (nu) 符合；遵從（規範、標準） |
| bacon | (nu) 培根；醃肉 |
| ballet | (nc) 芭蕾舞 |
| banana split | (nc) 香蕉船 |
| barely | (adv) 幾乎不；勉強地 |
| barrel | (nc) 桶；一桶 |
| barrier | (nc) 障礙；屏障 |
| basis | (nc) 基礎；依據 |
| battery | (nc) 電池 |
| bay | (nc) 灣；海灣 |
| beast | (nc) 野獸 |
| belly | (nc) 腹部；肚子 |
| berry | (nc) 漿果 |
| bidding | (nu) 投標；出價 |
| billion | (nc) 十億 |
| biography | (nc) 傳記 |
| biscuit | (nc) 餅乾 |
| black and white | (adj) 1. 黑白的　2. 白紙黑字的；書面明確的 |
| bloom | (vi) 開花；綻放 |
| blossom | (vi) 1. 開花；綻放　2. 蓬勃發展；茁壯成長 |
| border | (nc) 邊界；國界　(vt) 與…為界；毗鄰 |
| branch | (nc) 1. 分公司；分店　2. 樹枝；枝幹 |
| break out | (phr.) 爆發；突然發生 |
| brilliant | (adj) 燦爛的；出色的；極好的 |
| bring something to life | (phr.) 使…栩栩如生；賦予生命力 |
| broadcast | (vt) 廣播；播送　(nc) 廣播節目；轉播 |
| brutal | (adj) 殘暴的；殘酷的 |
| buffet | (nc) 自助餐 |
| bulb | (nc) 1. 燈泡　2. 球根 |
| cancellation | (nc) 取消；作廢 |
| candidate | (nc) 候選人；應徵者 |
| capable | (adj) 有能力的；能勝任的 |
| capture | (vt) 1. 捕獲；捉住　2. 捕捉；擷取 |
| care for someone | (phr.) 照顧；關心 |
| career | (nc) 職業生涯；事業 |
| carve out | (phr.) 開拓；努力創造出 |
| case | (nc) 案例；情況 |
| catch | (vt) 抓住；趕上　(nc) 隱藏的問題；陷阱 |
| cause | (nc) 原因；起因　(vt) 導致；造成 |
| celebration | (nc) 慶祝活動；慶典 |
| century | (nc) 世紀 |
| chain | (nc) 1. 連鎖店；連鎖企業　2. 鏈子 |
| challenge | (nc) 挑戰；難題　(vt) 質疑；向…挑戰 |
| chamber | (nc) 會議廳；議院 |
| channel | (nc) 頻道；管道　(vt) 引導；輸送 |
| chapter | (nc) 1. 章節　2. 分會 |
| character | (nc) 人物；角色　(nu) 性格；特質 |
| characteristic | (nc) 特徵；特色　(adj) 典型的；特有的 |
| charm | (nu) 魅力　(vt) 使陷入魅力；迷住 |
| cheerful | (adj) 愉快的；開朗的 |
| chemical | (nc) 化學物質　(adj) 化學的 |
| cherry | (nc) 櫻桃 |
| chicken breast | (nc) 雞胸肉 |
| chip | (nc) 1. 碎片；缺口　2. 洋芋片　3. 晶片　(vt) 削出缺口；打出缺角 |
| chirp | (vi) 發出唧唧聲；啁啾 |
| chopped | (adj) 切碎的 |
| claim | (vt) 1. 聲稱；宣稱　2. 索取；申請理賠　(nc) 索賠；理賠申請 |
| clear | (adj) 清楚的；明確的　(vt) 清除；結清 |
| click | (vt) 點擊　(vi) 合得來；意氣相投 |
| clothing | (nu) 衣物；服裝 |
| clue | (nc) 線索；提示 |
| cocktail dress | (nc) 雞尾酒禮服；小禮服 |
| coconut | (nc) 椰子 |
| code | (nc) 1. 法規；準則　2. 代碼；密碼 |
| combine | (vt) 結合；合併 |
| come in handy | (phr.) 派上用場；很有用 |
| come into play | (phr.) 開始起作用；發揮作用 |
| comedy | (nc) 喜劇 |
| comfort | (nu) 舒適；安慰　(vt) 安慰 |
| comic | (adj) 喜劇的；滑稽的　(nc) 漫畫 |
| comment | (nc) 評論；意見　(vi) 發表評論；表示意見 |
| commerce | (nu) 商業；貿易 |
| commercial | (nc) 廣告　(adj) 商業的；商用的 |
| committed | (adj) 全心投入的；有承諾的 |
| communicate | (vi) 溝通；交流　(vt) 傳達 |
| community | (nc) 社區；社群 |
| compete | (vi) 競爭 |
| competition | (nc) 1. 競爭　2. 比賽 |
| competitor | (nc) 競爭者；對手 |
| complaint | (nc) 抱怨；投訴 |
| complex | (adj) 複雜的　(nc) 綜合建築群 |
| complicated | (adj) 複雜的；難懂的 |
| compose | (vt) 1. 組成；構成　2. 創作；譜寫 |
| compound | (nc) 1. 化合物　2. 建築群；場地　(adj) 複合的；混合的 |
| concept | (nc) 概念；觀念 |
| concern | (nc) 擔憂；顧慮　(vt) 使擔憂；與…有關 |
| condition | (nc) 條件；狀況 |
| conference | (nc) 會議；研討會 |
| confirmation | (nc) 確認 |
| connecting | (adj) 連接的；轉接的 |
| consequence | (nc) 後果；結果 |
| consequently | (adv) 因此；所以 |
| considerably | (adv) 相當地；頗多地 |
| construct | (vt) 建造；建構 |
| construction | (nu) 建造；施工 |
| constructive | (adj) 建設性的 |
| consult | (vt) 查詢；請教　(vi) 諮詢；商議 |
| consultant | (nc) 顧問 |
| consumer | (nc) 消費者 |
| container | (nc) 1. 容器　2. 貨櫃 |
| content | (nu) 內容　(adj) 滿足的；滿意的 |
| contest | (nc) 比賽；競賽　(vt) 對…提出異議；質疑 |
| contract | (nc) 合約　(vt) 收縮；縮減 |
| contribution | (nc) 貢獻；捐款 |
| convenient | (adj) 方便的 |
| converse | (vi) 交談；談話 |
| convince | (vt) 說服；使確信 |
| corded | (adj) 有線的 |
| correspond | (vi) 1. 符合；相符　2. 通信；聯繫 |
| costume | (nc) 服裝；戲服 |
| cottage | (nc) 小屋；農舍 |
| count on | (phr.) 指望；依賴 |
| courageous | (adj) 勇敢的 |
| cozy | (adj) 舒適的；溫馨的 |
| creation | (nc) 創造；創作品 |
| creative | (adj) 有創意的；創造性的 |
| creativity | (nu) 創造力；創意 |
| creature | (nc) 生物；動物 |
| credit | (nu) 1. 信用；信貸　2. 功勞；讚揚　(nc) 學分 |
| crew | (nc) 全體工作人員；機組人員 |
| crisp | (adj) 1. 脆的；酥脆的　2. 清爽的；乾脆利落的 |
| critic | (nc) 評論家；批評者 |
| criticism | (nu) 批評；評論 |
| crowd | (nc) 群眾；人群 |
| cucumber | (nc) 黃瓜 |
| cuisine | (nc) 菜系；料理 |
| cultivate | (vt) 1. 培養；建立　2. 耕種；種植 |
| cup of tea | (phr.) 合意的事物；感興趣的東西 |
| curve | (vi) 彎曲；轉彎　(nc) 曲線；彎道 |
| custom-made | (adj) 訂製的；定制的 |
| daily | (adj) 每日的；每天的　(adv) 每日地；每天 |
| dare | (vi) 敢；膽敢 |
| darling | (nc) 最受喜愛的人或事物；寵兒 |
| dash | (vi) 衝；奔跑　(nc) 少量；一點點 |
| data | (nu) 資料；數據 |
| deal | (nc) 交易；協議　(vi) 交易；經銷 |
| decade | (nc) 十年 |
| decide | (vt) 決定 |
| define | (vt) 定義；界定；明確說明 |
| definition | (nc) 定義 |
| delay | (vt) 使延遲；耽誤　(nc) 延遲；延誤 |
| delivery | (nc) 遞送；交貨；送貨 |
| demand | (nu) 需求　(vt) 要求 |
| demonstration | (nc) 1. 示範；展示　2. 示威活動；抗議活動 |
| dependable | (adj) 可靠的；可信賴的 |
| dependent | (adj) 依賴的；依附的　(nc) 受撫養人；家屬 |
| depressing | (adj) 令人沮喪的；令人壓抑的 |
| deserve | (vt) 應得；值得 |
| designer | (nc) 設計師 |
| despite | (prep) 儘管；不管 |
| determine | (vt) 決定；確定；判定 |
| developed | (adj) 已開發的；發達的 |
| development | (nu) 發展；開發 |
| device | (nc) 裝置；設備 |
| devote | (vt) 投入；奉獻 |
| digital | (adj) 數位的 |
| diligence | (nu) 勤奮；勤勉 |
| direction | (nu) 方向；指引 |
| director | (nc) 1. 主管；董事；總監　2. 導演 |
| disadvantaged | (adj) 處於不利地位的；貧困的 |
| disappointing | (adj) 令人失望的 |
| disappointment | (nc) 失望 |
| disaster | (nc) 災難 |
| disconnected | (adj) 斷開的；不連貫的 |
| discourage | (vt) 使沮喪；勸阻 |
| disguise | (vt) 偽裝；掩飾　(nc) 偽裝物；偽裝 |
| disk | (nc) 磁碟；光碟 |
| dispute | (nc) 爭議；糾紛　(vt) 對…提出異議；質疑 |
| dissatisfaction | (nu) 不滿 |
| distance | (nc) 距離 |
| distant | (adj) 遙遠的；疏遠的 |
| distinctive | (adj) 獨特的；有特色的 |
| distinguished | (adj) 傑出的；卓越的 |
| distraction | (nc) 分心的事物；干擾 |
| distribute | (vt) 分配；分發；經銷 |
| document | (nc) 文件　(vt) 記錄；記載 |
| domestic | (adj) 國內的；家庭的 |
| download | (vt) 下載 |
| doze | (vi) 打瞌睡 |
| drain | (vt) 耗盡；使疲憊　(nc) 排水管；下水道 |
| dramatically | (adv) 顯著地；劇烈地 |
| dreadful | (adj) 可怕的；糟糕的 |
| drift | (vi) 漂流；漂移；偏離 |
| drive | (vt) 1. 駕駛　2. 推動；促使　(nc) 衝勁；幹勁；積極性 |
| dynamic | (adj) 動態的；有活力的　(nc) 互動關係；運作模式 |
| eager | (adj) 渴望的；急切的 |
| earnest | (adj) 認真的；誠摯的 |
| ease | (vt) 減輕；緩和　(nu) 輕鬆；容易 |
| edge | (nc) 1. 邊緣　2. 優勢 |
| edible | (adj) 可食用的 |
| edition | (nc) 版本；版次 |
| education | (nu) 教育 |
| effect | (nc) 效果；影響 |
| effective | (adj) 1. 有效的；有效果的　2. 生效的 |
| effort | (nu) 努力；費力 |
| electrician | (nc) 電工；電匠 |
| element | (nc) 元素；要素 |
| elementary | (adj) 基本的；初級的 |
| emerge | (vi) 出現；浮現 |
| emergency | (nc) 緊急情況 |
| emerging | (adj) 新興的 |
| emotional | (adj) 情緒上的；情感的 |
| employ | (vt) 1. 雇用；聘用　2. 運用；使用 |
| empty | (adj) 空的　(vt) 倒空；清空 |
| enable | (vt) 使能夠；促成 |
| encounter | (vt) 遭遇；遇到 |
| encourage | (vt) 鼓勵 |
| energetic | (adj) 有活力的；精力充沛的 |
| enforcement | (nu) 執行；強制執行 |
| engaged | (adj) 1. 訂婚的　2. 忙於…的；從事於…的 |
| engineer | (nc) 工程師　(vt) 設計；策劃 |
| enjoyable | (adj) 令人愉快的；有趣的 |
| enormous | (adj) 巨大的 |
| entertain | (vt) 1. 招待；款待　2. 考慮 |
| entertainment | (nu) 娛樂 |
| entrance | (nc) 入口 |
| environmental | (adj) 環境的 |
| equip | (vt) 裝備；配備 |
| essential | (adj) 必要的；不可或缺的　(nc) 必需品；基本要素 |
| evaluate | (vt) 評估；評價 |
| event | (nc) 事件；活動 |
| eventually | (adv) 最終；終於 |
| everything in between | (phr.) 介於兩者之間的一切；其他種種 |
| evident | (adj) 明顯的；顯而易見的 |
| exception | (nc) 例外 |
| exchange | (vt) 交換　(nc) 交易所 |
| exclusive | (adj) 獨家的；專屬的 |
| exhibit | (vt) 展示；展出　(nc) 展品；陳列品 |
| exhibition | (nc) 展覽；展覽會 |
| existence | (nu) 存在 |
| exit | (nc) 出口　(vt) 退出；離開 |
| expansion | (nu) 擴張；擴展 |
| expectation | (nc) 期望 |
| experiment | (nc) 實驗　(vi) 做實驗；嘗試 |
| explore | (vt) 探索；探討 |
| exposure | (nu) 1. 暴露；曝露　2. 曝光度；知名度 |
| expression | (nc) 表達；表情；用語 |
| extend | (vt) 1. 延伸；延長　2. 給予；致以 |
| extraordinary | (adj) 非凡的；特別的 |
| extremely | (adv) 非常地；極其 |
| facial | (adj) 臉部的 |
| fail | (vi) 失敗；未能 |
| fair | (adj) 公平的；公正的　(nc) 展覽會；博覽會 |
| fame | (nu) 名聲；名譽 |
| fancy | (adj) 高級的；精美的　(vt) 想要；喜歡 |
| fantastic | (adj) 極好的；了不起的 |
| faraway | (adj) 遙遠的 |
| fare | (nc) 票價　(vi) 進展；表現 |
| fear | (nu) 恐懼；害怕　(vt) 害怕；畏懼 |
| feast | (nc) 盛宴；宴會　(vi) 大吃大喝；飽餐一頓 |
| feel at home | (phr.) 感到自在；賓至如歸 |
| female | (adj) 女性的；雌性的　(nc) 女性 |
| festival | (nc) 節日；慶典 |
| fierce | (adj) 激烈的；猛烈的 |
| financial | (adj) 財務的；金融的 |
| fine | (adj) 1. 良好的；不錯的　2. 精細的；細微的　(nc) 罰款　(vt) 處以罰款 |
| firework | (nc) 煙火 |
| flame | (nc) 火焰 |
| flat | (adj) 平坦的；扁平的　(nc) 公寓（英式用法） |
| flavor | (nc) 風味；口味　(vt) 為…調味 |
| float | (vi) 漂浮　(vt) 使（股票）上市；發行 |
| fluent | (adj) 流利的；精通的 |
| flush | (vi) 臉紅　(vt) 沖洗（馬桶等） |
| flying saucer | (nc) 飛碟 |
| follower | (nc) 追隨者；跟隨者；粉絲 |
| following | (adj) 接下來的；下列的　(prep) 在…之後 |
| forbidden | (adj) 被禁止的 |
| force | (nu) 力量；武力　(vt) 迫使；強迫 |
| formula | (nc) 1. 公式　2. 配方 |
| forth | (adv) 向前；往前 |
| fortunate | (adj) 幸運的 |
| forward | (adv) 向前　(vt) 轉寄；轉交 |
| found | (vt) 創立；建立 |
| foundation | (nu) 基礎　(nc) 基金會 |
| fountain | (nc) 噴水池 |
| freedom | (nu) 自由 |
| freeway | (nc) 高速公路 |
| frequently | (adv) 頻繁地；經常 |
| friendship | (nu) 友誼 |
| frown | (vi) 皺眉　(nc) 皺眉的表情 |
| frustrated | (adj) 沮喪的；感到挫折的 |
| frustration | (nu) 挫折；沮喪 |
| fulfilling | (adj) 令人滿足的；有成就感的 |
| function | (nu) 功能；作用　(vi) 運作；發揮作用 |
| fund | (nc) 基金　(vt) 資助；提供資金 |
| fundamental | (adj) 基本的；根本的 |
| further | (adj) 更多的；進一步的　(vt) 促進；推動 |
| future | (nu) 未來　(adj) 未來的 |
| gap | (nc) 差距；缺口 |
| garlic | (nu) 大蒜 |
| gas | (nu) 1. 瓦斯；氣體　2. 汽油 |
| gaze | (vi) 注視；凝視　(nc) 注視；凝視 |
| generation | (nc) 世代；一代 |
| genuine | (adj) 真正的；真誠的 |
| gigantic | (adj) 巨大的 |
| ginger | (nu) 薑 |
| give away | (vt) 1. 贈送；免費給予　2. 洩露；暴露 |
| give credit to someone | (phr.) 歸功於（某人）；讚許（某人的貢獻） |
| global | (adj) 全球的；全球性的 |
| glow | (vi) 發光；發亮　(nc) 光輝；光亮 |
| goods | (nc) 貨物；商品 |
| gossip | (nu) 閒言閒語；八卦　(vi) 說閒話；聊八卦 |
| govern | (vt) 治理；統治 |
| gradually | (adv) 漸漸地；逐漸地 |
| graduate | (nc) 畢業生　(vi) 畢業 |
| grain | (nu) 穀物；穀粒 |
| grapefruit | (nc) 葡萄柚 |
| grasp | (vt) 理解；掌握　(nc) 理解；掌握 |
| gratitude | (nu) 感激；感謝 |
| ground | (nu) 地面　(nc) 理由；根據 |
| growth | (nu) 成長；增長 |
| grub | (vi) 翻找；挖尋 |
| guard | (nc) 警衛；守衛　(vt) 守衛；保護 |
| guardian | (nc) 監護人 |
| guidance | (nu) 指導；引導 |
| guide | (vt) 指導；引導　(nc) 1. 指南　2. 導遊 |
| handcrafted | (adj) 手工製作的 |
| handful | (nc) 一把；少數 |
| handle | (vt) 處理；應付　(nc) 把手 |
| handwriting | (nu) 筆跡；手寫字 |
| handy | (adj) 便利的；方便的 |
| hardship | (nu) 困苦；艱難 |
| harmful | (adj) 有害的 |
| harmony | (nu) 和諧 |
| harvest | (nc) 收成；收穫　(vt) 收割；收穫 |
| headline | (nc) 標題；頭條新聞 |
| headquarters | (nc) 總部 |
| healthful | (adj) 有益健康的 |
| hell | (nu) 地獄 |
| hero | (nc) 英雄 |
| hesitate | (vi) 遲疑；猶豫 |
| highly | (adv) 高度地；非常 |
| hike | (nc) 1. 健行；遠足　2. （物價）上漲　(vt) 提高（物價） |
| honest | (adj) 誠實的 |
| honor | (nu) 榮譽　(vt) 1. 尊敬　2. 履行（承諾）；遵守 |
| hook sb. in | (phr.) 吸引；拉攏 |
| horrible | (adj) 可怕的；糟糕的 |
| hostel | (nc) 旅舍；青年旅館 |
| humorous | (adj) 幽默的；滑稽的 |
| hunt | (vt) 1. 狩獵；打獵　2. 搜尋；尋找 |
| ideal | (adj) 理想的　(nc) 理想 |
| identity | (nu) 1. 身份　2. 特性 |
| idol | (nc) 偶像 |
| illustrate | (vt) 說明；闡明 |
| image | (nc) 1. 圖像；影像　2. 形象 |
| imagination | (nu) 想像力 |
| imaginative | (adj) 有想像力的；創意豐富的 |
| imagine | (vt) 想像 |
| immediately | (adv) 立即；馬上 |
| immigration | (nu) 移民（入境） |
| impact | (nu) 衝擊；影響　(vt) 對…產生影響 |
| impartial | (adj) 公正的；不偏不倚的 |
| importance | (nu) 重要性 |
| improve | (vt) 改善；改進 |
| in addition to | (phr.) 除了…之外（還）；加上 |
| incense | (nc) 香；香品 |
| include | (vt) 包括；包含 |
| income | (nc) 收入 |
| inconsistency | (nc) 不一致；矛盾 |
| inconvenient | (adj) 不方便的 |
| industry | (nc) 產業；工業 |
| influential | (adj) 有影響力的 |
| initial | (adj) 最初的；初始的　(nc) 姓名的首字母 |
| inn | (nc) 小旅館；客棧 |
| inner | (adj) 內部的；內心的 |
| inspection | (nc) 檢查；檢驗 |
| inspiring | (adj) 鼓舞人心的 |
| install | (vt) 安裝 |
| instead of | (phr.) 而不是 |
| instruction | (nc) 指令；說明 |
| insurance | (nu) 保險 |
| intend | (vt) 打算；意圖 |
| interpret | (vt) 1. 解釋；詮釋　2. 口譯；傳譯 |
| interrupt | (vt) 打斷；打擾 |
| intimate | (adj) 親密的；私人的　(vt) 暗示；示意 |
| introduce | (vt) 1. 介紹　2. 引進；推出 |
| invitation | (nc) 邀請；邀請函 |
| isolated | (adj) 1. 孤立的；隔離的　2. 偶發的；單一的 |
| issue | (nc) 問題；議題　(vt) 發布；發行 |
| ivory | (nu) 象牙 |
| jealous | (adj) 嫉妒的；吃醋的 |
| jet lag | (nu) 時差；時差疲勞 |
| jewel | (nc) 珠寶；寶石 |
| jewelry | (nu) 珠寶；首飾 |
| journal | (nc) 1. 日誌；日記　2. 期刊；雜誌 |
| journey | (nc) 旅程；旅途 |
| junk | (nu) 垃圾；廢物 |
| kick off | (phr.) 開始；啟動 |
| knob | (nc) 把手；旋鈕 |
| let sb. in on sth | (phr.) 讓某人知道秘密；透露某事給某人 |
| labor | (nu) 勞動；勞力；人力 |
| lack | (nu) 缺乏；不足　(vt) 缺乏；沒有 |
| landscape | (nc) 1. 景觀；風景　2. 局勢；格局 |
| large-scale | (adj) 大規模的 |
| latter | (adj) 後者的；後面的 |
| lawn | (nc) 草坪 |
| lawyer | (nc) 律師 |
| learning curve | (phr.) 學習曲線 |
| legal | (adj) 法律的；合法的 |
| legend | (nc) 1. 傳說；傳奇人物　2. 圖例；說明 |
| length | (nc) 長度 |
| limitation | (nc) 限制；限度 |
| limited | (adj) 有限的 |
| liquor | (nu) 酒；烈酒 |
| literary | (adj) 文學的；文藝的 |
| lively | (adj) 活潑的；熱鬧的；生動的 |
| location | (nc) 位置；地點 |
| loss | (nc) 損失；虧損 |
| lotion | (nu) 乳液；護膚液 |
| loyal | (adj) 忠誠的；忠實的 |
| luck | (nu) 運氣；幸運 |
| luggage | (nu) 行李 |
| madam | (nc) 夫人；女士 |
| magical | (adj) 神奇的；魔法的 |
| magnificent | (adj) 壯麗的；宏偉的 |
| maintain | (vt) 1. 維持；保養　2. 主張；堅稱 |
| make sense | (phr.) 有道理；合理 |
| manage | (vt) 1. 管理；經營　2. 設法；成功做到 |
| manager | (nc) 經理；主管 |
| marvelous | (adj) 奇妙的；了不起的 |
| masses | (nc) 群眾；大眾 |
| master | (nc) 大師；專家　(vt) 精通；掌握 |
| material | (nu) 材料；原料　(adj) 重要的；實質性的 |
| maturity | (nu) 1. 到期；期滿　2. 成熟；成熟度 |
| meaningful | (adj) 有意義的 |
| means | (nc) 方法；手段 |
| media | (nu) 媒體 |
| membership | (nu) 會員資格；會籍 |
| memorable | (adj) 難忘的；值得紀念的 |
| merchant | (nc) 商人；貿易商 |
| merit | (nc) 優點；價值　(vt) 值得；應得 |
| messy | (adj) 1. 凌亂的；雜亂的　2. 棘手的；麻煩的 |
| microphone | (nc) 麥克風 |
| miserable | (adj) 悲慘的；痛苦的 |
| misery | (nu) 痛苦；苦難 |
| misfortune | (nu) 不幸；厄運 |
| miss out | (phr.) 錯過機會 |
| mixture | (nc) 混合物；混合 |
| mobile | (adj) 移動的；可移動的 |
| moist | (adj) 潮濕的；濕潤的 |
| monthly | (adj) 每月的　(adv) 每月一次地 |
| moral | (adj) 道德的；道義上的 |
| moreover | (adv) 而且；此外 |
| motivate | (vt) 激勵；促使 |
| musical | (adj) 音樂的　(nc) 音樂劇 |
| native | (adj) 本地的；原生的　(nc) 本地人 |
| nature | (nu) 1. 自然；自然界　2. 本質；性質 |
| necessarily | (adv) 必然地；一定 |
| neighborhood | (nc) 鄰里；社區 |
| nevertheless | (adv) 然而；儘管如此 |
| nightmare | (nc) 惡夢；夢魘 |
| noble | (adj) 高貴的；崇高的 |
| normal | (adj) 正常的；一般的 |
| nourishing | (adj) 滋補的；有營養的 |
| novel | (nc) 小說　(adj) 新穎的；新奇的 |
| numerous | (adj) 眾多的；許多的 |
| object | (nc) 物體　(vi) 反對 |
| objective | (nc) 目標　(adj) 客觀的 |
| observe | (vt) 1. 觀察；注意到　2. 遵守 |
| obstacle | (nc) 障礙；阻礙 |
| obtain | (vt) 獲得；取得 |
| obvious | (adj) 明顯的；顯而易見的 |
| occasion | (nc) 場合；時機 |
| odd | (adj) 1. 奇怪的；古怪的　2. 奇數的 |
| offering | (nc) 提供之物；產品或服務項目 |
| on top of that | (phr.) 此外；再加上 |
| open market | (nc) 公開市場；自由市場 |
| opera | (nc) 歌劇 |
| operation | (nc) 1. 營運；作業　2. 手術 |
| opinion | (nc) 意見；看法 |
| organically | (adv) 1. 有機地　2. 自然地；逐漸地 |
| original | (adj) 最初的；原創的　(nc) 原件；原作 |
| out of date | (phr.) 過時的；已到期的 |
| overlook | (vt) 1. 忽略；忽視　2. 俯瞰；眺望 |
| overnight | (adv) 一夜之間；突然　(adj) 過夜的；隔夜的 |
| overtake | (vt) 1. 超越；超過　2. 超車 |
| part | (nc) 部分；零件 |
| participate | (vi) 參與；參加 |
| participation | (nu) 參與 |
| particular | (adj) 1. 特別的；特定的　2. 挑剔的；講究的 |
| partnership | (nc) 合作關係；合夥 |
| pass away | (phr.) 去世；逝世 |
| passenger | (nc) 乘客 |
| passion | (nu) 熱情；熱愛 |
| patience | (nu) 耐心；忍耐 |
| percent | (nc) 百分之… |
| percentage | (nc) 百分比；比例 |
| performance | (nc) 1. 表現；績效　2. 表演　3. 性能 |
| performer | (nc) 1. 表演者　2. 表現優異者；佼佼者 |
| period | (nc) 期間；時期 |
| personality | (nc) 個性；人格 |
| pest | (nc) 害蟲 |
| petal | (nc) 花瓣 |
| physically | (adv) 1. 身體上地；體力上地　2. 實際上；實體上 |
| pioneer | (nc) 先驅；開拓者　(vt) 開創；首創 |
| pit | (nc) 坑洞；礦坑　(vt) 使…對抗；使…競爭 |
| pleasure | (nu) 樂趣；愉快 |
| plentiful | (adj) 豐富的；充足的 |
| plenty | (nu) 大量；充足的量 |
| plug | (nc) 插頭　(vt) 堵塞；塞住 |
| plum | (nc) 李子；梅子　(adj) 極佳的；令人稱羨的 |
| plumber | (nc) 水管工人 |
| political | (adj) 政治的 |
| popularity | (nu) 人氣；受歡迎程度 |
| possess | (vt) 擁有；具有 |
| post | (nc) 職位；崗位　(vt) 公布；張貼 |
| powdered | (adj) 粉狀的 |
| powerful | (adj) 強大的；有影響力的 |
| practical | (adj) 實用的；務實的 |
| prayer | (nc) 禱告；祈禱 |
| precious | (adj) 珍貴的；寶貴的 |
| preferable | (adj) 更合適的；較好的 |
| pregnant | (adj) 懷孕的 |
| preparation | (nu) 準備 |
| preserves | (nc) 果醬；蜜餞 |
| president | (nc) 總裁；董事長 |
| press | (vt) 按；壓　(nc) 新聞界；媒體 |
| pressure | (nu) 壓力 |
| previous | (adj) 先前的；之前的 |
| print | (vt) 印刷；列印　(nu) 印刷品 |
| privacy | (nu) 隱私 |
| privilege | (nc) 特權；權利 |
| proceed | (vi) 繼續進行；前進 |
| production | (nu) 生產；製造 |
| productive | (adj) 有生產力的；有成效的 |
| professional | (adj) 專業的　(nc) 專業人士 |
| profit | (nc) 利潤　(vi) 獲利；得益 |
| profitable | (adj) 有利可圖的；獲利的 |
| progress | (nu) 進展　(vi) 進展；前進 |
| project | (nc) 專案；計畫　(vt) 預測；估計 |
| prominent | (adj) 顯著的；著名的 |
| promise | (vt) 承諾；保證　(nc) 承諾 |
| promotional | (adj) 促銷的；宣傳的 |
| prompt | (adj) 迅速的；準時的　(vt) 促使；引起 |
| proof | (nu) 證明；證據 |
| property | (nc) 房地產；財產　(nu) 特性；屬性 |
| prosperous | (adj) 繁榮的；興旺的 |
| proudly | (adv) 自豪地；驕傲地 |
| prove | (vt) 證明 |
| psychological | (adj) 心理的 |
| psychology | (nu) 心理學 |
| public | (adj) 公開的；公共的　(nu) 公眾 |
| publication | (nu) 出版　(nc) 出版物；刊物 |
| publicity | (nu) 宣傳；公眾關注 |
| publish | (vt) 出版；發表 |
| punch | (vt) 1. 打孔；沖壓　2. 出拳打　(nc) 一拳 |
| pursue | (vt) 追求；從事 |
| pursuit | (nu) 追求 |
| put sth. into motion | (phr.) 使…開始進行；啟動 |
| quality | (nu) 品質　(nc) 特質 |
| raise | (vt) 提高；提出　(nc) 加薪 |
| raisin | (nc) 葡萄乾 |
| range | (nc) 範圍；系列　(vi) 範圍涵蓋 |
| razor | (nc) 剃刀 |
| reach | (vt) 1. 達到；抵達　2. 聯繫上 |
| reason | (nc) 原因；理由 |
| reasonable | (adj) 合理的 |
| recent | (adj) 最近的 |
| recognition | (nu) 認可；表揚 |
| recover | (vi) 恢復；復原 |
| reference | (nc) 1. 參考　2. 推薦人；介紹信　(vt) 提及；引用 |
| referral | (nc) 推薦；轉介 |
| regarding | (prep) 關於 |
| region | (nc) 地區；區域 |
| regulation | (nc) 法規；規定 |
| relate to | (phr.) 與…有關；涉及 |
| relation | (nc) 關係 |
| release | (vt) 發布；發行　(nc) 新聞稿 |
| relieved | (adj) 安心的；放心的 |
| rely | (vi) 依靠；依賴 |
| remain | (vi) 保持；仍然是 |
| remarkable | (adj) 卓越的；顯著的 |
| remote | (adj) 遠端的；偏遠的 |
| rented | (adj) 租用的；出租的 |
| replace | (vt) 更換；取代 |
| report | (nc) 報告　(vt) 報告；報導 |
| reporter | (nc) 記者 |
| represent | (vt) 代表 |
| representation | (nu) 代表；代表權 |
| reputation | (nc) 名聲；聲譽 |
| research | (nu) 研究　(vt) 研究；調查 |
| researcher | (nc) 研究員 |
| reservation | (nc) 預訂 |
| resident | (nc) 居民　(adj) 常駐的 |
| resign | (vi) 辭職 |
| resolve | (vt) 解決 |
| resource | (nc) 資源 |
| respectable | (adj) 體面的；可觀的 |
| response | (nc) 回應 |
| result | (nc) 結果　(vi) 導致；造成 |
| retail | (nu) 零售　(vi) 以零售價出售 |
| rising | (adj) 上升的；上漲的 |
| risky | (adj) 冒險的；有風險的 |
| roasted | (adj) 烘烤的；烘焙的 |
| role | (nc) 角色；職務 |
| roll | (vi) 滾動　(nc) 名冊 |
| romantic | (adj) 浪漫的 |
| roughly | (adv) 大約；粗略地 |
| routine | (nc) 常規；慣例　(adj) 例行的 |
| ruin | (vt) 破壞；毀壞　(nc) 廢墟 |
| rumor | (nc) 謠言；傳聞 |
| rural | (adj) 鄉村的；農村的 |
| safely | (adv) 安全地 |
| satisfy | (vt) 滿足；使滿意 |
| sausage | (nc) 香腸 |
| scarce | (adj) 稀少的；缺乏的 |
| scary | (adj) 可怕的；令人害怕的 |
| scatter | (vi) 分散；散開 |
| scoop | (vt) 挖取；舀取　(nc) 獨家新聞 |
| sculpture | (nc) 雕塑 |
| seal | (vt) 1. 密封；封住　2. 敲定；確定　(nc) 印章；封條 |
| security | (nu) 安全；保安　(nc) 證券 |
| seek | (vt) 尋求；謀求 |
| seize | (vt) 抓住；把握 |
| sense | (nc) 感覺；意識　(vt) 感覺到；察覺 |
| series | (nc) 系列；連續 |
| shampoo | (nc) 洗髮精 |
| shape | (nc) 形狀　(vt) 塑造；形成 |
| shave | (vi) 剃鬍子；刮毛 |
| shelter | (nc) 避難所；收容所　(vt) 庇護；掩護 |
| shiny | (adj) 閃亮的；光亮的 |
| shocked | (adj) 震驚的；驚訝的 |
| shortage | (nc) 短缺；不足 |
| sign | (vt) 簽署　(nc) 1. 標誌；招牌　2. 跡象；徵兆 |
| signature style | (phr.) 招牌風格；獨特特色 |
| similar | (adj) 類似的；相似的 |
| simply | (adv) 1. 僅僅；只是　2. 簡單地 |
| sincerely | (adv) 誠摯地 |
| single | (adj) 1. 單一的；唯一的　2. 單身的；未婚的 |
| sir | (nc) 先生 |
| site | (nc) 1. 現場；工地　2. 網站 |
| situation | (nc) 情況；情勢 |
| skeleton | (nc) 骨骼；骷髏 |
| sketch | (nc) 草圖；素描　(vt) 繪製草圖 |
| slice | (nc) 片；一片　(vt) 切片 |
| slightly | (adv) 略微；稍微 |
| snap | (vi) 猛然折斷；啪地斷裂　(nc) 快照 |
| social | (adj) 社交的；社會的 |
| solid | (adj) 堅固的；可靠的　(nc) 固體 |
| somewhat | (adv) 有點；稍微 |
| soul | (nc) 靈魂 |
| spark | (nc) 火花　(vt) 引發；激起 |
| sparkle | (vi) 閃爍；發光　(nc) 光彩；光芒 |
| specialize | (vi) 專攻；專精於 |
| specific | (adj) 具體的；特定的 |
| spell | (vt) 拼寫　(nc) 1. 咒語；魔法　2. 一段時間 |
| spice up | (phr.) 使...更有趣；增添趣味 |
| spiritual | (adj) 精神上的；心靈的 |
| spiritually | (adv) 精神上地；心靈上地 |
| splash | (vi) 潑濺；濺出　(nc) 轟動；引人注目的效果 |
| splendid | (adj) 極好的；壯麗的 |
| spot | (nc) 1. 地點　2. 斑點　(vt) 發現；認出 |
| spread | (vi) 傳播；散布；蔓延　(vt) 散布；傳播 |
| sprinkle | (vt) 撒；灑 |
| stage | (nc) 1. 舞台　2. 階段　(vt) 舉辦；策劃 |
| stale | (adj) 不新鮮的；陳舊的 |
| starvation | (nu) 飢餓；餓死 |
| state | (nc) 1. 州　2. 狀態；情況　(vt) 陳述；聲明 |
| status | (nu) 地位；狀態 |
| stock | (nu) 1. 股票　2. 庫存；存貨　(vt) 進貨；備有 |
| strategy | (nc) 策略；戰略 |
| strength | (nu) 力量；實力　(nc) 優點；長處 |
| strive | (vi) 努力；力求 |
| struggle | (vi) 掙扎；努力奮鬥　(nc) 掙扎；困境 |
| suitable | (adj) 合適的；適當的 |
| superior | (adj) 優越的；較好的　(nc) 上級；上司 |
| support | (vt) 支持；支援；支撐　(nu) 支持；支援 |
| suppose | (vt) 猜想；假設 |
| surf | (vi) 衝浪　(vt) 瀏覽 |
| surface | (nc) 表面　(vi) 浮現；顯現 |
| surrounding | (adj) 周圍的 |
| survival | (nu) 生存；倖存 |
| survive | (vt) 存活；倖存 |
| suspicion | (nu) 懷疑；猜疑 |
| suspicious | (adj) 可疑的；懷疑的 |
| symbolize | (vt) 象徵 |
| syrup | (nu) 糖漿 |
| tag | (nc) 標籤　(vt) 貼標籤；標記 |
| take for granted | (phr.) 認為...理所當然；視...為理所當然 |
| talent | (nc) 才能；天賦　(nu) 人才 |
| technically | (adv) 技術上；嚴格來說 |
| technique | (nc) 技術；技巧 |
| technological | (adj) 技術的；科技的 |
| teenager | (nc) 青少年 |
| temporarily | (adv) 暫時地 |
| the departed | (phr.) 已故者；亡者 |
| thirst | (nu) 渴；口渴　(nc) 渴望 |
| tide | (nc) 潮汐；潮流 |
| tissue paper | (phr.) 棉紙；薄紙 |
| to top it all off | (phr.) 更甚者；最後還有一件更誇張的事 |
| toast | (nc) 1. 吐司；烤麵包　2. 祝酒辭；敬酒辭　(vt) 向...敬酒；舉杯祝賀 |
| toss | (vt) 投擲；輕拋　(vi) 輾轉；翻騰 |
| tough | (adj) 艱難的；強硬的 |
| tourist | (nc) 遊客；觀光客 |
| trade | (nu) 貿易；交易　(vt) 交易；以...交換 |
| traditional | (adj) 傳統的 |
| traffic | (nu) 交通；車流量　(vi) 販運；非法交易 |
| tragedy | (nc) 悲劇 |
| transform | (vt) 轉變；改造 |
| translate | (vt) 翻譯　(vi) 轉化為；反映為 |
| transport | (vt) 運輸　(nu) 運輸；交通工具 |
| trash | (nu) 垃圾　(vt) 丟棄；毀掉 |
| traveler | (nc) 旅客；旅行者 |
| tremendous | (adj) 巨大的；驚人的 |
| trend | (nc) 趨勢；潮流 |
| tribute | (nc) 1. 致敬；讚辭　2. 貢品 |
| triumph | (nc) 勝利；凱旋　(vi) 獲勝；克服困難 |
| tropical | (adj) 熱帶的 |
| tune in | (phr.) 收聽；收看 |
| turn the tide | (phr.) 扭轉局勢；力挽狂瀾 |
| type | (nc) 類型　(vt) 打字 |
| undesirable | (adj) 不良的；不受歡迎的 |
| unexpectedly | (adv) 出乎意料地 |
| unfavorable | (adj) 不利的；不贊成的 |
| unplug | (vt) 拔掉插頭；拔除 |
| unpredictable | (adj) 不可預測的 |
| upset | (adj) 難過的；不安的　(vt) 使不安；打亂 |
| urban | (adj) 城市的；都市的 |
| utilize | (vt) 利用 |
| value | (nu) 價值　(vt) 重視；評估 |
| variety | (nu) 多樣性　(nc) 種類；品種 |
| various | (adj) 各種的；多樣的 |
| vast | (adj) 廣闊的；大量的 |
| vegetarian | (nc) 素食者　(adj) 素食的 |
| victim | (nc) 受害者 |
| violet | (adj) 紫色的　(nc) 紫羅蘭 |
| viral marketing | (phr.) 病毒式行銷 |
| virus | (nc) 病毒 |
| vision | (nu) 視力；視覺　(nc) 願景；遠見 |
| visual | (adj) 視覺的　(nc) 視覺輔助資料；圖表 |
| vital | (adj) 極重要的；必不可少的 |
| volcano | (nc) 火山 |
| volunteer | (nc) 志工；自願者　(vi) 自願 |
| weekly | (adj) 每週的　(adv) 每週地；每星期一次　(nc) 週刊 |
| whip up | (phr.) 1. 迅速準備；快速做出　2. 激起；煽動 |
| whole wheat | (phr.) 全麥的 |
| wireless | (adj) 無線的 |
| wonder | (vt) 想知道；感到好奇　(nc) 奇跡；令人驚奇的事物 |
| word of mouth | (phr.) 口碑；口耳相傳 |
| worth | (adj) 值...的；值得...的　(nu) 價值 |
| worthy | (adj) 值得的；配得上的 |
| wrapped | (adj) 包裹好的；包紮好的 |
| imminent | (adj) 即將發生的；迫近的 |
| wary | (adj) 謹慎的；提防的；小心翼翼的 |
| overhaul | (vt) 徹底檢修；全面改革　(nc) 徹底檢修；大修 |
| against all the odds | (phr.) 儘管困難重重；不顧種種不利因素 |
| apprentice | (nc) 學徒；見習生 |
| computer literate | (adj) 精通電腦操作的 |
| credential | (nc) 資歷；證明文件 |
| excel | (vi) 擅長；表現出色 |
| increment | (nc) 增額；增量 |
| lag | (vi) 落後；滯後 |
| lay out | (phr.) 展開放置；規劃佈局 |
| make a commitment to | (phr.) 承諾要做 |
| make a point of | (phr.) 特別注意去做；刻意做到 |
| mindful | (adj) 留意的；謹記的 |
| overqualified | (adj) 資格過高的 |
| pertaining to | (phr.) 與某事有關的；關於 |
| preliminary | (adj) 初步的；預備性的 |
| replenish | (vt) 補充；重新裝滿 |
| screening | (nu) 篩選；審查 |
| simplicity | (nu) 簡單；簡易 |
| stellar | (adj) 極優秀的；出色的 |
| sternly | (adv) 嚴厲地；嚴格地 |
| workstation | (nc) 工作站 |
| zealous | (adj) 熱心的；熱切的 |
| alert | (adj) 警覺的；機警的　(vt) 警告；提醒 |
| at the discretion of | (phr.) 由某人決定；取決於某人的裁量 |
| bound | (adj) 有義務的；受約束的 |
| by all means | (phr.) 當然可以；務必 |
| circumscribe | (vt) 限制；約束 |
| depiction | (nc) 描繪；描述 |
| disobedient | (adj) 不服從的；違抗命令的 |
| distrust | (nu) 不信任；懷疑　(vt) 不信任；懷疑 |
| enactment | (nu) 制定；頒布 |
| exemplary | (adj) 1. 值得效法的；堪為典範的　2. 以儆效尤的；嚴厲警示性的 |
| from this day onward | (phr.) 從今天起；自此以後 |
| hold up | (phr.) 1. 維持良好狀態；撐住　2. 延誤；阻礙 |
| if I'm not mistaken | (phr.) 如果我沒記錯的話 |
| impeccable | (adj) 完美無瑕的；無可挑剔的 |
| in accordance with | (phr.) 依照；根據 |
| inadvertently | (adv) 不經意地；非故意地 |
| indecisive | (adj) 猶豫不決的；不果斷的 |
| infringement | (nc) 侵犯；違反 |
| in observance of | (phr.) 為紀念；依循慣例 |
| judicial | (adj) 司法的 |
| keenly | (adv) 熱切地；敏銳地 |
| legitimate | (adj) 合法的；正當合理的 |
| observance | (nu) 遵守；奉行 |
| ordinance | (nc) 法令；條例 |
| reprimand | (vt) 斥責；正式責備 |
| stand over | (phr.) 站在旁邊監視；緊盯著 |
| stiff | (adj) 堅硬的；僵硬的 |
| substantiate | (vt) 證實；提供證據支持 |
| suppress | (vt) 壓制；抑制 |
| tensely | (adv) 緊張地；焦慮地 |
| testimony | (nu) 證詞；證言 |
| trespass | (vi) 擅自進入；非法侵入 |
| under the supervision of | (phr.) 在某人的監督下 |
| without respect to | (phr.) 不論；不考慮 |
| administer | (vt) 管理；執行 |
| clerical | (adj) 文書的；辦公室事務的 |
| condense | (vt) 濃縮；精簡 |
| default | (nc) 違約；未履行義務 |
| errand | (nc) 差事；跑腿的任務 |
| extend an invitation | (phr.) 發出邀請；邀請 |
| follow up on | (phr.) 追蹤；進一步處理 |
| head up | (phr.) 領導；主持 |
| impending | (adj) 即將發生的 |
| in alphabetical order | (phr.) 按字母順序排列 |
| in luck | (phr.) 運氣好；幸運 |
| officiate | (vi) 主持典禮；主持儀式 |
| past due | (adj) 逾期未付的；過期的 |
| popularize | (vt) 使普及；推廣 |
| proponent | (nc) 支持者；提倡者 |
| put forward | (phr.) 提出 |
| scrub | (vt) 用力刷洗；擦洗乾淨 |
| site inspection | (phr.) 現場勘查；場地檢查 |
| strew | (vt) 散置；散落 |
| take initiative | (phr.) 主動採取行動 |
| telecommute | (vi) 遠端工作；居家辦公 |
| throw one's effort into | (phr.) 全力投入 |
| acquaintance | (nc) 認識的人；相識 |
| ambiance | (nu) 氛圍；環境氣氛 |
| aspiration | (nc) 渴望達成的目標；志向 |
| business contact | (phr.) 商業人脈；業務聯絡人 |
| copy editor | (nc) 文字編輯；校稿編輯 |
| discerning | (adj) 有鑑別力的；判斷敏銳的 |
| draw on | (phr.) 運用；借助 |
| entrust A with B | (phr.) 將某物託付給某人；委託某人照管某物 |
| have one's hands full | (phr.) 忙得不可開交 |
| in anticipation of | (phr.) 為某事而預做準備；預期 |
| in the light of | (phr.) 鑑於；考慮到 |
| make an outside call | (phr.) 撥打對外電話 |
| obsess about | (phr.) 對某事念念不忘；過度掛心 |
| on edge | (phr.) 緊張不安的 |
| personal effects | (nc) 個人隨身物品 |
| propel | (vt) 推動；促使前進 |
| recline | (vi) 向後靠；斜躺 |
| repository | (nc) 儲藏處；存放地 |
| seamless | (adj) 無縫的；順暢無阻的 |
| sort | (nc) 種類；類型 |
| supplementary | (adj) 補充的；額外增加的 |
| trivial | (adj) 微不足道的；不重要的 |
| typewriter | (nc) 打字機 |
| writing pad | (nc) 便條紙本 |
| written consent | (phr.) 書面同意；書面許可 |
| aggravate | (vt) 使惡化；加重 |
| astute | (adj) 精明的；敏銳的 |
| be up late | (phr.) 很晚才睡；熬夜 |
| compartment | (nc) 隔間；分隔的小空間 |
| contingency | (nc) 應變措施；意外事件 |
| customary | (adj) 慣例的；習慣上的 |
| drag | (vt) 拖；拉 |
| draw a distinction between | (phr.) 區分；劃分 |
| draw the line at | (phr.) 堅決不做；設下底線 |
| evacuate | (vt) 疏散；撤離 |
| formality | (nc) 例行程序；形式上的手續 |
| give way to | (phr.) 讓步於；被取代 |
| in commemoration of | (phr.) 為紀念 |
| look up to | (phr.) 敬重；仰慕 |
| on probation | (phr.) 處於試用期 |
| proofread | (vt) 校對；校讀 |
| recondition | (vt) 翻修；整修 |
| segregate A from B | (phr.) 將某物與某物分開；隔離 |
| smock | (nc) 罩衫；工作服 |
| stool | (nc) 凳子 |
| timecard | (nc) 打卡卡；工時記錄卡 |
| wary of | (phr.) 對某事提防；不完全信任 |
| artifact | (nc) 文物；人工製品 |
| artistic | (adj) 藝術的 |
| auditorium | (nc) 禮堂；觀眾席 |
| be booked up | (phr.) 被預訂滿；訂位已滿 |
| botanical garden | (nc) 植物園 |
| censorship | (nu) 審查制度 |
| choir | (nc) 合唱團 |
| contestant | (nc) 參賽者 |
| enlightening | (adj) 有啟發性的 |
| excursion | (nc) 短程旅遊；遠足 |
| flower bed | (nc) 花圃；花壇 |
| grip | (vt) 緊握；牢牢抓住 |
| head for | (vi) 朝某方向前進；前往 |
| intermission | (nc) 中場休息 |
| intriguingly | (adv) 引人好奇地；有趣地 |
| legroom | (nu) 腿部空間 |
| make yourself at home | (phr.) 別客氣；當自己家一樣自在 |
| memoirs | (nc) 回憶錄 |
| mural | (nc) 壁畫 |
| oar | (nc) 船槳 |
| out of order | (phr.) 故障；無法使用 |
| paddle | (vt) 用槳划　(nc) 短槳 |
| pass the time | (phr.) 消磨時間 |
| rake | (nc) 耙子　(vt) 耙；用耙子整理 |
| rally | (nc) 拉力賽 |
| roam around | (vi) 漫遊；四處走動 |
| running time | (nc) 片長；播放時長 |
| sail | (vi) 航行；行駛 |
| slide down | (vi) 滑下；向下滑動 |
| sport tournament | (nc) 體育錦標賽；運動賽事 |
| stadium | (nc) 體育場；運動場 |
| stay tuned | (phr.) 請繼續關注；敬請期待 |
| stay up | (phr.) 很晚才睡；熬夜不睡 |
| stroll | (vi) 散步；閒逛 |
| touch up | (phr.) 修飾；稍加潤色 |
| transferable | (adj) 可轉移的；可轉調適用的 |
| unsanitary | (adj) 不衛生的；不潔的 |
| usher | (vt) 引導；引領　(nc) 引座員；接待員 |
| vacate | (vt) 騰出；搬離 |
| all-out | (adj) 全力的；徹底的 |
| all the way | (phr.) 從頭到尾；完全地 |
| all walks of life | (phr.) 各行各業；各界人士 |
| as opposed to | (phr.) 而不是；相對於 |
| astonishingly | (adv) 驚人地；令人驚訝地 |
| at a stretch | (phr.) 連續不斷地；一口氣 |
| back up | (vt) 證實；佐證　(vi) 回堵；堵塞 |
| boldly | (adv) 大膽地；勇敢地 |
| call on | (phr.) 呼籲；號召 |
| compilation | (nu) 彙編；編纂 |
| comprehensible | (adj) 可理解的；易懂的 |
| confiscation | (nu) 沒收；查扣 |
| constitute | (vt) 構成；組成 |
| contend | (vi) 競爭；爭奪 |
| definite | (adj) 明確的；確定的 |
| drive up | (phr.) 推高；使上漲 |
| expectancy | (nu) 期待；期盼的心情 |
| feasibility study | (nc) 可行性研究；可行性評估 |
| fixed price | (nc) 固定價格；固定售價 |
| forgetfully | (adv) 健忘地；粗心遺忘地 |
| gauge | (vt) 測量；估量 |
| have control over | (phr.) 掌控；控制 |
| in bloom | (phr.) 開花；盛開 |
| in reference to | (phr.) 關於；就…而言 |
| intervention | (nc) 介入；干預 |
| irretrievable | (adj) 無法挽回的；不可恢復的 |
| lose ground | (phr.) 失去優勢；落後 |
| make an assessment | (phr.) 進行評估；做評估 |
| market stall | (nc) 市場攤位 |
| mediate | (vi) 調解；斡旋 |
| modestly | (adv) 謙虛地；適度地 |
| over the Internet | (phr.) 透過網路；經由網際網路 |
| perception | (nc) 觀感；看法 |
| public profile | (nc) 公眾形象；公開檔案 |
| setback | (nc) 挫折；阻礙 |
| set forth | (vt) 陳述；列出　(vi) 出發；啟程 |
| striking | (adj) 顯著的；引人注目的 |
| telling | (adj) 顯露真相的；意味深長的 |
| underlying | (adj) 潛在的；根本的 |
| with the exception of | (phr.) 除…之外；除了…以外 |
| abruptly | (adv) 突然地；意外地 |
| absorbing | (adj) 引人入勝的；吸引人的 |
| assimilate | (vi) 融入；被同化 |
| as well as | (conj) 以及；不僅…而且 |
| at all costs | (phr.) 不惜一切代價 |
| attend to | (phr.) 接待；照料 |
| anxious to | (phr.) 急切想要的；渴望的 |
| boast | (vi) 誇耀；自誇 |
| bother | (vi) 費心；特意去做 |
| captivate | (vt) 使著迷；吸引住 |
| come across | (phr.) 偶然遇到；偶然發現 |
| come along | (phr.) 出現；一起來 |
| come loose | (phr.) 鬆脫；鬆動 |
| confront | (vt) 面對；正視 |
| contrive | (vi) 設法；策劃達成 |
| culminate | (vi) 達到高潮；最終導致 |
| defiance | (nu) 反抗；不服從 |
| deliberate | (adj) 故意的；蓄意的 |
| depict | (vt) 描繪；描述 |
| dissipate | (vi) 逐漸消散；消失 |
| driven | (adj) 有幹勁的；一心追求成功的 |
| eagerly awaited | (adj) 令人期待已久的；備受期待的 |
| elicit | (vt) 引出；獲得(反應或資訊) |
| fortify | (vt) 加強；強化 |
| get back to | (phr.) 稍後回覆；再次聯繫 |
| gradual | (adj) 逐漸的；漸進的 |
| a great deal | (phr.) 大量；許多 |
| inadequate | (adj) 不足的；不夠格的 |
| in a timely fashion | (phr.) 及時地；適時地 |
| make up one's mind | (phr.) 下定決心；做出決定 |
| mingle | (vi) 交際；混合 |
| mobility | (nu) 流動性；移動能力 |
| put a strain on | (phr.) 對…造成壓力；對…造成負擔 |
| put up with | (phr.) 容忍；忍受 |
| rave review | (nc) 好評如潮的評論；讚譽有加的評論 |
| reach for | (phr.) 伸手去拿 |
| stark | (adj) 光禿禿的；空蕩蕩的；顯而易見的　(adv) 完全地；徹底地 |
| steadiness | (nu) 穩定性；持續不變 |
| televise | (vt) 電視轉播；播送 |
| abate | (vi) 減弱；平息 |
| brokerage | (nu) 仲介業務；經紀業務 |
| business practice | (nc) 商業慣例；經營方式 |
| conspicuously | (adv) 顯眼地；明顯地 |
| deteriorate | (vi) 惡化；變差 |
| entail | (vt) 需要；牽涉 |
| flourish | (vi) 蓬勃發展；興旺 |
| foremost | (adj) 最重要的；首要的 |
| forerunner | (nc) 先驅；前身 |
| have a monopoly on | (phr.) 獨占；壟斷 |
| implicitly | (adv) 含蓄地；不明說地 |
| indifferent | (adj) 漠不關心的；不感興趣的 |
| marketable | (adj) 適合銷售的；有市場的 |
| menace | (vt) 威脅；危及 |
| multilateral | (adj) 多邊的 |
| perceptible | (adj) 可察覺的；可感覺到的 |
| privatization | (nc) 民營化；私有化 |
| put forth | (phr.) 提出；提議 |
| ratio | (nc) 比率；比例 |
| retrieval | (nu) 檢索；取回 |
| runner-up | (nc) 第二名；亞軍 |
| sluggish | (adj) 遲緩的；不景氣的 |
| solitary | (adj) 單獨的；孤獨的 |
| stationary | (adj) 靜止不動的；不變的 |
| synergy | (nu) 協同效應；合作效益 |
| synthesis | (nc) 綜合；融合 |
| vicious cycle | (nc) 惡性循環 |
| volatile | (adj) 不穩定的；易變動的 |
| apparel | (nu) 服飾；衣著 |
| at a discounted price | (phr.) 以折扣價；以優惠價 |
| at a substantial discount | (phr.) 以相當大的折扣；以大幅折扣 |
| at the moment | (phr.) 目前；此刻 |
| by no means | (phr.) 絕非；決不 |
| cash register | (nc) 收銀機 |
| conversely | (adv) 相反地；反之 |
| cooking utensils | (nc) 烹飪用具；廚具 |
| dilute | (vt) 稀釋；沖淡 |
| embellish | (vt) 裝飾；美化 |
| embroider | (vt) 刺繡；繡花 |
| exhilarating | (adj) 令人興奮的；振奮人心的 |
| exorbitant | (adj) 過高的；過分的 |
| exposition | (nc) 展覽會；博覽會 |
| extravagance | (nu) 奢侈；浪費 |
| generic | (adj) 通用的；無品牌的 |
| glassware | (nu) 玻璃器皿 |
| lavish | (adj) 豪華的；奢華的 |
| make no difference | (phr.) 沒有影響；沒有差別 |
| observably | (adv) 明顯可見地；顯而易見地 |
| overcoat | (nc) 大衣；外套 |
| readership | (nu) 讀者群 |
| readily | (adv) 容易地；欣然地 |
| redeem | (vt) 兌換；贖回 |
| shoelace | (nc) 鞋帶 |
| showcase | (nc) 1. 展示櫃；陳列櫃　2. 展現特色的場合；展示的舞台 |
| sleeve | (nc) 衣袖；袖子 |
| stack | (nc) 一疊；一堆 |
| storefront | (nc) 店面；店頭 |
| tailor | (nc) 裁縫師；裁縫 |
| take an order | (phr.) 受理訂單；幫忙點餐 |
| undercharge | (vt) 少收費；收費過低 |
| underline | (vt) 強調；凸顯 |
| valid | (adj) 有效的；有效力的 |
| watchband | (nc) 錶帶 |
| wind | (vt) 上鏈；轉緊發條 |
| wrap | (vt) 包裝；包裹 |
| electronics | (nu) 電子學；電子產業 |
| evolve | (vi) 演化；逐漸發展　(vt) 使演化；使逐漸發展 |
| exploration | (nu) 探勘；探索 |
| implant | (vt) 1. 植入　2. 灌輸；注入 |
| intently | (adv) 專注地；全神貫注地 |
| limited edition | (nc) 限量版 |
| ornamental | (adj) 裝飾性的；裝飾用的　(nc) 裝飾品 |
| remnant | (nc) 剩餘部分；殘餘 |
| specimen | (nc) 1. 樣品；範例　2. 檢驗樣本 |
| staple | (nc) 主要產品；必需品　(adj) 主要的；基本的 |
| apparatus | (nc) 器械；裝置 |
| carry out | (phr.) 執行；實施 |
| be geared to | (phr.) 針對…而設計；符合…需求 |
| bewildering | (adj) 令人困惑的 |
| bring out | (phr.) 推出(產品) |
| complementary | (adj) 互補的 |
| composition | (nu) 組成；構成　(nc) 作品；創作 |
| concurrently | (adv) 同時地 |
| configuration | (nc) 配置；佈局 |
| distill | (vt) 1. 蒸餾　2. 提煉精華；濃縮精要 |
| dysfunction | (nc) 功能失調；故障 |
| steer | (vt) 1. 駕駛；操控方向　2. 引導；導向 |
| sturdily | (adv) 1. 堅固地；結實地　2. 堅定地；堅決地 |
| transparent | (adj) 透明的 |
| trial period | (nc) 試用期 |
| vulnerable | (adj) 易受傷害的；脆弱的 |
| arable | (adj) 耕種的；適於耕作的 |
| broadly | (adv) 大體上；概括地說 |
| combustible | (adj) 易燃的；可燃的 |
| come apart | (phr.) 破裂；散開；裂成碎片 |
| continuity | (nu) 連續性；持續性 |
| disassemble | (vt) 拆卸；拆解 |
| fabricate | (vt) 1. 捏造；虛構　2. 製造；生產(產品) |
| fitted | (adj) 1. 合身的；量身訂做的　2. 固定式的；嵌入式的 |
| flow chart | (nc) 流程圖 |
| gem | (nc) 1. 寶石；珠寶　2. 極好的人或事物；珍寶 |
| generator | (nc) 發電機 |
| go out of production | (phr.) 停產 |
| grease | (nu) 油脂；潤滑油 |
| identically | (adv) 完全相同地；一模一樣地 |
| integration | (nu) 整合；融合 |
| liquidity | (nu) 流動性；資金週轉能力 |
| made-to-order | (adj) 訂製的；按客戶要求製作的 |
| make an exception | (phr.) 破例；例外處理 |
| make public | (phr.) 公開；公布 |
| makeup | (nc) 組成；構成方式 |
| miniature | (adj) 微型的；縮小的 |
| much to one's surprise | (phr.) 令人非常驚訝的是 |
| neatly | (adv) 1. 整齊地　2. 巧妙地；精巧地 |
| nimble | (adj) 敏捷的；反應靈敏的 |
| obfuscate | (vt) 使模糊不清；混淆 |
| on the spot | (phr.) 當場；在事發現場 |
| outlast | (vt) 比…更持久；比…存在得更久 |
| output | (nu) 產量；產出 |
| pack away | (phr.) 把…收起來；裝箱收好 |
| perturbed | (adj) 不安的；煩擾的 |
| pragmatic | (adj) 務實的；實事求是的 |
| precede | (vt) 在…之前；先於 |
| prevail | (vi) 1. 獲勝；佔優勢　2. 盛行；普遍存在 |
| ready-made | (adj) 現成的；成品的 |
| recede | (vi) 1. 後退；變得模糊　2. 下降；減少 |
| reproduction | (nc) 複製品；仿製品　(nu) 繁殖；生殖 |
| scale model | (nc) 比例模型；縮小模型 |
| settle on | (phr.) 決定；選定 |
| sort out | (phr.) 整理；清理 |
| squeak | (vi) 1. 發出吱吱聲　2. 勉強成功 |
| synthetic | (adj) 1. 人工合成的；人造的　2. 虛假的；不真誠的 |
| tie up | (vt) 把…綁緊；捆紮　(nc) 業務合作；合作協議 |
| unfailingly | (adv) 始終不變地；一直 |
| unmet | (adj) 未滿足的；未達成的 |
| upon | (prep) 一…就…；於…之上 |
| wear and tear | (phr.) (正常使用造成的)損耗；磨損 |
| welding | (nu) 焊接 |
| workbench | (nc) 工作台 |
| deputy | (nc) 副手；代理人 |
| distress | (nu) 痛苦；憂傷　(vt) 使痛苦；使苦惱 |
| factually | (adv) 在事實方面；就事實而言 |
| faulty | (adj) 有缺陷的；故障的 |
| fleetingly | (adv) 短暫地；一閃而過地 |
| graciously | (adv) 親切地；有禮地 |
| handheld | (adj) 手持式的 |
| intercept | (vt) 攔截；截住 |
| loaf | (nc) 一條(麵包) |
| nourish | (vt) 1. 滋養；供給營養　2. 懷有(希望、想法等) |
| pharmacist | (nc) 藥劑師 |
| affair | (nc) 事務；事情 |
| aggression | (nu) 侵略性；攻擊性 |
| bare | (adj) 1. 赤裸的；未遮蓋的　2. 最基本的；僅有的 |
| blemish | (nc) 1. (外表上的)瑕疵　2. (名聲、性格上的)污點 |
| button up | (phr.) 扣上鈕釦；扣好 |
| censure | (nc) 嚴厲批評；譴責　(vt) 正式譴責 |
| ceremonial | (adj) 儀式的；典禮的 |
| claims department | (nc) 理賠部門 |
| compelling | (adj) 1. 令人信服的　2. 引人入勝的 |
| cut back | (phr.) 削減；縮減 |
| depot | (nc) 倉庫；貨運站；車輛停放場 |
| prepaid | (adj) 預付的 |
| retrospective | (nc) 回顧展　(adj) 回顧性的；追溯的 |
| slip one's mind | (phr.) 被遺忘；忘記 |
| soak up | (phr.) 吸收(液體) |
| sparsely | (adv) 稀疏地；稀少地 |
| swiftly | (adv) 迅速地 |
| testimonial | (nc) 推薦信；推薦函 |
| unwavering | (adj) 堅定不移的；不動搖的 |
| wardrobe | (nc) 衣櫥；衣櫃 |
| airsickness | (nu) 飛行嘔吐感；暈機 |
| barge | (nc) 駁船；平底貨船 |
| be left unattended | (phr.) 無人看管；未受照看 |
| board a flight | (phr.) 登機 |
| buckle up | (phr.) 扣上安全帶 |
| carousel | (nc) 行李轉盤 |
| charter | (vt) 租用；包租(飛機、船等) |
| concourse | (nc) (車站、機場的)大廳；中央通道 |
| confer | (vi) 商討；交換意見 |
| deck | (nc) 甲板 |
| disembark | (vi) 下(船、飛機等) |
| dispense | (vt) 分發；提供(物品) |
| fluid | (nc) 液體 |
| harbor | (nc) 港口；海港 |
| impound | (vt) (依法)扣押；沒收 |
| layover | (nc) (旅途中的)短暫停留 |
| life preserver | (nc) 救生圈；救生衣 |
| lodging | (nu) 住宿 |
| motion sickness | (nu) 動暈症；乘車不適 |
| presumable | (adj) 可推測的；可能的 |
| quarantine | (nu) 隔離檢疫 |
| reclaim | (vt) 取回；索回 |
| remains | (nc) 1. 殘餘物；剩下的部分　2. 遺跡；遺址 |
| remittance | (nc) 匯款 |
| row the boat | (phr.) 划船 |
| seasickness | (nu) 船暈；海上暈船 |
| stall | (vi) (引擎)突然熄火 |
| stop over | (phr.) 中途停留 |
| swap | (vt) 交換；互換　(nc) 交換；交換物 |
| touch down | (phr.) (飛機)著陸 |
| turn up | (phr.) 出現；被找到 |
| unload | (vt) 卸貨；卸下 |
| annotated | (adj) 附加註解的；有註釋的 |
| arbitration | (nu) 仲裁 |
| be in agreement | (phr.) 意見一致；達成共識 |
| beside the point | (phr.) 不相關的；離題的 |
| close a deal | (phr.) 達成交易 |
| dial a number | (phr.) 撥打電話號碼 |
| down payment | (nc) 頭期款；訂金 |
| embark on | (phr.) 著手進行；開始從事 |
| enclosure | (nc) 1. 圍欄區域；圍場　2. (信件中的)附件 |
| foil | (vt) 阻止；挫敗(計畫) |
| for ages | (phr.) 很久；許久 |
| in appreciation of | (phr.) 為感謝；以表謝意 |
| inconclusively | (adv) 沒有明確結果地；不了了之地 |
| in contrast | (phr.) 相比之下；對比之下 |
| in print | (phr.) (書等)仍在印行；可購得 |
| instrumental in | (phr.) 對…有重大作用；是…的關鍵因素 |
| in summary | (phr.) 總而言之；總之 |
| make a deposit | (phr.) 存入(款項、押金) |
| make a move | (phr.) 採取行動；動身離開 |
| mediation | (nu) 調解；斡旋 |
| moderator | (nc) 調解人；主持人 |
| offend | (vi) 犯罪；違法　(vt) 冒犯；使不悅 |
| omission | (nc) 遺漏；疏漏之處 |
| originate in | (phr.) 起源於；發源於 |
| pave | (vt) 鋪(路面) |
| portray | (vt) 描繪；描寫 |
| preferential treatment | (phr.) 優惠待遇；特殊優待 |
| provision | (nc) (法律或合約中的)條款 |
| rational | (adj) 理性的；合理的 |
| recollection | (nc) 回憶；記憶中的事　(nu) 記憶力；回想能力 |
| relinquish | (vt) 放棄；交出(權利、責任等) |
| remembrance | (nu) 追悼；紀念 |
| replica | (nc) 複製品；仿製品 |
| rocky | (adj) 艱難的；不穩定的 |
| rough | (adj) 粗糙的；不平坦的 |
| sarcastic | (adj) 諷刺的；挖苦的 |
| security deposit | (nc) 保證金；押金 |
| solicit | (vt) 請求；徵求(金錢、資訊或協助) |
| under the contract | (phr.) 根據合約；依合約規定 |
| virtual | (adj) 1. 幾乎的；實質上的　2. 虛擬的 |
| within reason | (phr.) 在合理範圍內 |
| attain | (vt) 達成；獲得 |
| at the latest | (phr.) 最晚；最遲 |
| barring | (prep) 除非；若非(發生某事) |
| barter | (vt) 以物易物；用…交換 |
| capitalize on | (phr.) 利用；憑藉…獲利 |
| cast a ballot | (phr.) 投票 |
| come to power | (phr.) 掌權；上臺執政 |
| constituency | (nc) 1. (某地區的)選民　2. 選區 |
| contend with | (phr.) 應付；處理(困難的情況) |
| engrave | (vt) 雕刻；刻(字或圖案)於 |
| exercise one's right | (phr.) 行使權利 |
| honorable | (adj) 光榮的；正直可敬的 |
| inclination | (nc) 傾向；意願 |
| itemized | (adj) 逐項列出的 |
| lead up to | (phr.) 逐漸引導至；為…作鋪陳 |
| parliament | (nc) 1. 國會；議會　2. 國會會期；議會任期 |
| peddler | (nc) 小販；沿街叫賣者 |
| perceptive | (adj) 敏銳的；有洞察力的 |
| predominantly | (adv) 主要地；大多 |
| profoundly | (adv) 深切地；極其 |
| protocol | (nc) (國際間的)協議；公約 |
| reasonably priced | (phr.) 價格合理的 |
| scarcity | (nc) 缺乏；不足 |
| step down | (phr.) 辭職；卸下職位 |
| surrender | (vi) 1. 投降；屈服　2. 屈服於(誘惑、情感) |
| take inventory | (phr.) 盤點存貨 |
| write up | (phr.) 撰寫(完整報告) |
| accelerate | (vi) 加速；加快　(vt) 使加速；促進 |
| as of | (phr.) 從…起；自…開始 |
| bilateral | (adj) 雙邊的 |
| consulate | (nc) 領事館 |
| courier service | (nc) 快遞服務；快遞公司 |
| diplomat | (nc) 外交官 |
| discard | (vt) 丟棄；拋棄 |
| drive off | (phr.) 開車離開 |
| drop off | (phr.) 把…送到（某處） |
| expatriate | (nc) 僑民；外派人員　(vt) 驅逐出境；使流亡 |
| expedite | (vt) 加快處理；加速進行 |
| handrail | (nc) 扶手 |
| inaugurate | (vt) 為…舉行就職典禮 |
| janitor | (nc) 管理員；清潔工 |
| lace | (nc) 鞋帶；繩帶　(vt) 繫上鞋帶 |
| marginally | (adv) 些微地；略微地 |
| oversight | (nc) 疏忽；失察　(nu) 監督；督導 |
| packing tape | (nu) 包裝膠帶 |
| pavement | (nc) 人行道 |
| pier | (nc) 支柱；橋墩 |
| provided that | (phr.) 只要；如果 |
| reciprocal | (adj) 互惠的；相互的 |
| registered mail | (nu) 掛號信；掛號郵件 |
| stow | (vt) 收放；存放 |
| strap | (nc) 帶子；背帶　(vt) 用帶子固定 |
| wheelbarrow | (nc) 獨輪推車 |
| agreeably | (adv) 愉快地；令人滿意地 |
| as a courtesy | (phr.) 作為禮貌；出於好意 |
| atrium | (nc) 中庭；大廳 |
| chop | (vt) 切碎；剁碎 |
| cloakroom | (nc) 衣物間；寄物處 |
| corridor | (nc) 走廊；通道 |
| countertop | (nc) 檯面；流理台 |
| decaffeinated | (adj) 去咖啡因的 |
| double occupancy | (nu) 雙人住房 |
| eat up | (phr.) 吃完；吃光 |
| forfeit | (vt) 喪失；被沒收 |
| frosting | (nu) 糖霜 |
| garner | (vt) 獲得；贏得 |
| garnish | (vt) 裝飾（食物）；點綴 |
| gather up | (phr.) 收集起來；收拾 |
| grab a bite | (phr.) 隨便吃點東西；簡單吃一下 |
| gusty | (adj) 風大的；陣風的 |
| have a light dinner | (phr.) 吃一份清淡的晚餐 |
| indigenous | (adj) 本土的；原生的 |
| kettle | (nc) 水壺；茶壺 |
| palate | (nc) 味覺；品味 |
| parlor | (nc) 1. 客廳；接待室　2. …店；…館（提供特定服務或商品的店家） |
| peel off | (phr.) 剝掉；撕下 |
| pick up the check | (phr.) 買單；付帳 |
| potholder | (nc) 隔熱手套；鍋墊 |
| preheat | (vt) 預熱 |
| progressively | (adv) 逐漸地；漸進地 |
| room attendant | (nc) 房務員 |
| sanitary | (adj) 1. 衛生的；清潔的　2. （婦女）生理用的 |
| seemingly | (adv) 看似；表面上 |
| slurp | (vt) 發出聲音地喝；啜飲 |
| spoil | (vi) 變質；腐壞 |
| stove | (nc) 爐子；炊具 |
| tablecloth | (nc) 桌布 |
| teapot | (nc) 茶壺 |
| thickly | (adv) 厚厚地 |
| unpack | (vt) 打開（行李、包裹）；拆封 |
| vinegar | (nu) 醋 |
| agile | (adj) 敏捷的；靈活的 |
| allotment | (nc) 分配額；配額 |
| at a rapid rate | (phr.) 快速地；迅速地 |
| coil | (nc) 一圈；一捲　(vt) 把…捲成一圈 |
| dean | (nc) 1. （大學）院長　2. （同行中的）資深領袖，元老 |
| deviate | (vi) 偏離；背離 |
| do damage | (phr.) 造成損害；造成傷害 |
| downfall | (nc) 垮台；衰敗（的原因） |
| even out | (phr.) 使…平均；使…趨於平衡 |
| file for bankruptcy | (phr.) 申請破產 |
| gratify | (vt) 使滿足；使高興 |
| gross income | (nu) 總收入；毛收入 |
| harsh | (adj) 嚴厲的；嚴苛的 |
| hollow | (adj) 1. 空心的；中空的　2. 空洞的；不真誠的 |
| infusion | (nc) 1. 注入（資金等）　2. （藥草、茶等的）沖泡飲品 |
| insolvency | (nu) 破產；無力償債 |
| literally | (adv) 1. 確實地；真的　2. 逐字地；照字面地 |
| loosely | (adv) 鬆散地；不緊密地 |
| offset | (vt) 抵銷；彌補 |
| optimal | (adj) 最理想的；最佳的 |
| outpace | (vt) 超越；勝過（發展速度） |
| outsell | (vt) 銷售量超過 |
| piece by piece | (phr.) 一件一件地；逐步地 |
| profit margin | (nc) 利潤率 |
| proportion | (nc) 比例；部分 |
| proportionate | (adj) 成比例的；相稱的 |
| signify | (vt) 表示；意味著 |
| split | (vt) 分割；分開　(nc) 裂縫；分裂 |
| steeply | (adv) 急劇地；陡峭地 |
| subside | (vi) 減弱；平息 |
| swell | (vi) 膨脹；增加 |
| timeline | (nc) 時間表；時程 |
| uncover | (vt) 揭露；發現 |
| vitally | (adv) 極為重要地；不可或缺地 |
| adjournment | (nc) 休會；暫停（會議、審訊） |
| amply | (adv) 充分地；足夠地 |
| back order | (nc) 缺貨訂單；延期交貨訂單 |
| bound for | (phr.) 前往…的；以…為目的地的 |
| break-even point | (nc) 損益平衡點 |
| by contrast | (phr.) 相比之下；相對地 |
| collectively | (adv) 共同地；集體地 |
| digit | (nc) 數字；位數 |
| displace | (vt) 取代；使離開原位 |
| implicate | (vt) 牽連；涉及（於不當行為） |
| incrementally | (adv) 逐步地；漸增地 |
| ledger | (nc) 帳簿；分類帳 |
| levy | (nc) 徵稅；稅捐 |
| liability | (nu) 責任；法律責任　(nc) 負債 |
| outlay | (nc) 支出；開支 |
| overly | (adv) 過於；過度地 |
| precedent | (nc) 先例；前例 |
| pretax | (adj) 稅前的 |
| rigorously | (adv) 嚴格地；嚴謹地 |
| sequel | (nc) 續集；後續篇 |
| side by side | (phr.) 並排地；並肩地 |
| stringently | (adv) 嚴格地；嚴密地 |
| a string of | (phr.) 一連串的；一系列的 |
| substantively | (adv) 實質上地；在重要方面 |
| take after | (phr.) 與…相似；像（家人） |
| well in advance | (phr.) 提前很多；事先充分準備 |
| whereabouts | (nu) 行蹤；下落 |
| advisory | (adj) 顧問性質的；諮詢性質的　(nc) 官方通告（含建議、資訊或警告） |
| allegedly | (adv) 據稱；傳聞中 |
| bump into | (phr.) 偶然遇到；碰見 |
| celebratory | (adj) 慶祝的 |
| clout | (nu) 權勢；影響力　(nc) 打擊；敲打 |
| contingent upon | (phr.) 取決於；以…為條件 |
| correlation | (nc) 關聯性；相關性 |
| exemplify | (vt) 是…的典型例子；體現 |
| exert pressure on | (phr.) 對…施加壓力 |
| hinder | (vt) 妨礙；阻礙 |
| incline | (vi) 傾斜　(nc) 斜坡 |
| indefinitely | (adv) 無限期地；不定期地 |
| inhabitant | (nc) 居民 |
| instinctive | (adj) 本能的；直覺的 |
| interfere with | (phr.) 妨礙；干擾 |
| intermittently | (adv) 斷斷續續地；間歇性地 |
| landfill | (nc) 垃圾掩埋場 |
| latent | (adj) 潛在的；隱伏的 |
| look out | (phr.) 注意；留意 |
| lucid | (adj) 清晰易懂的；條理清楚的 |
| makeshift | (adj) 臨時的；權宜的 |
| momentarily | (adv) 1. 短暫地；片刻　2. 馬上；很快 |
| narrative | (nc) 1. 敘述；故事　2. 說法；論述角度 |
| outreach | (nu) 外展服務；推廣服務 |
| overstaffed | (adj) 人員過多的；人力過剩的 |
| rashly | (adv) 草率地；輕率地 |
| renown | (nu) 聲望；名望 |
| retreat | (vi) 撤退；退避 |
| rule out | (phr.) 排除；排除…的可能性 |
| scholar | (nc) 學者 |
| sensible | (adj) 1. 明智的；合理的　2. 實用的（衣物等） |
| squeaky | (adj) 發出尖銳聲音的；吱吱作響的 |
| succession | (nc) 一連串；接連發生　(nu) 繼任；接班 |
| succumb to | (phr.) 屈服於；抵擋不住 |
| take a turn for the better | (phr.) 好轉；出現轉機 |
| abbreviate | (vt) 縮寫 |
| abridgment | (nc) 節略本；縮寫版 |
| biweekly | (adv) 每兩週一次地 |
| clash | (nc) 衝突；爭執 |
| coherent | (adj) 有條理的；前後一致的；易懂的 |
| counteroffer | (nc) 還價；反提議 |
| disperse | (vi) 散開；疏散　(vt) 使散開；驅散 |
| eloquent | (adj) 能言善道的；口才流利的 |
| enthuse | (vi) 熱切表達；讚不絕口　(vt) 使…產生熱情 |
| excerpt | (nc) 節錄；摘錄 |
| faction | (nc) 派系；小團體 |
| hold back | (phr.) 阻礙；抑制 |
| inviting | (adj) 吸引人的；誘人的 |
| on the off chance | (phr.) 萬一；以防萬一（雖然機會不大） |
| pass around | (phr.) 傳遞；輪流傳閱 |
| presiding | (adj) 主持的；主管的 |
| presumably | (adv) 據推測；大概 |
| prop something against something | (phr.) 把…靠著…撐住 |
| put in an offer | (phr.) 出價（購買）；提出報價 |
| reassure | (vt) 使安心；使放心 |
| run late | (phr.) 延誤；晚到 |
| stare into | (phr.) 凝視；盯著看 |
| succinct | (adj) 簡潔的；言簡意賅的 |
| symposium | (nc) 研討會；座談會 |
| take part in | (phr.) 參與；加入 |
| to start with | (phr.) 首先；一開始 |
| uphold | (vt) 維護；堅持（原則、決定等） |
| biannual | (adj) 一年兩次的 |
| chronological | (adj) 按時間順序的 |
| citation | (nc) 1. 引文；引述　2. 傳票；出庭通知 |
| credit someone with something | (phr.) 將…歸功於某人；認為某人具有（某特質） |
| discriminate | (vi) 1. 歧視　2. 分辨；辨別 |
| distort | (vt) 扭曲；曲解 |
| fringe benefit | (nc) 附加福利；額外津貼 |
| give in to | (phr.) 向…讓步；屈服於 |
| goodwill | (nu) 善意；友好態度 |
| have the nerve to do something | (phr.) 有勇氣（或膽子）做某事 |
| hearty | (adj) 1. 熱情的；衷心的　2. 豐盛的；大量的 |
| keep up to date | (phr.) 隨時更新；保持最新資訊 |
| knock off | (phr.) 下班；停止工作 |
| know something like the back of your hand | (phr.) 對某事物非常熟悉；瞭若指掌 |
| laugh away | (phr.) 用笑聲化解（尷尬或不悅） |
| nursery | (nc) 1. 托兒所　2. 苗圃；花圃　(adj) 幼兒教育的 |
| off-peak | (adj) 非高峰時段的；離峰的 |
| overtime rate | (nc) 加班費率 |
| pending | (adj) 懸而未決的；即將發生的　(prep) 在…之前（暫緩）；等待…期間 |
| pique | (nu) 不悅；慍怒 |
| preservation area | (nc) 保育區；自然保護區 |
| sabotage | (vt) 蓄意破壞；暗中阻撓 |
| safety drill | (nc) 安全演習；應變演練 |
| second | (vt) 附議；正式表示支持 |
| severance pay | (nu) 遣散費 |
| sheltered housing | (nu) （為老年人或弱勢者提供的）安養住宅 |
| spry | (adj) 矯健的；老當益壯的 |
| straightforward | (adj) 1. 簡單的；易懂的　2. 誠實直率的 |
| strong-willed | (adj) 意志堅定的；固執己見的 |
| take some time off | (phr.) 請假；休息一段時間 |
| terribly | (adv) 非常；極其 |
| yearn | (vi) 渴望；嚮往 |
| arm in arm | (phr.) 手臂勾著手臂地；手牽手地 |
| aspire to | (phr.) 渴望；有志於 |
| cordially | (adv) 1. 誠摯地；友善地　2. 謹啟（信函結尾用語） |
| degrade | (vt) 1. 貶低；侮辱　2. 使…品質下降；破壞 |
| delicate | (adj) 易碎的；脆弱的；需謹慎處理的 |
| deploy | (vt) 部署；調度運用 |
| dignitary | (nc) 政要；顯要人物 |
| disorient | (vt) 使…迷失方向；使…困惑 |
| empower | (vt) 授權；賦予權力 |
| extraordinary feat | (nc) 非凡的成就；了不起的成果 |
| fill in for someone | (phr.) 代替某人（暫代職務） |
| forage | (vi) 尋找食物；覓食　(nu) （家畜的）飼料 |
| gratis | (adv) 免費地　(adj) 免費的 |
| heighten | (vt) 加劇；增強 |
| hurdle | (nc) 1. 障礙；難題　2. 跨欄（賽跑用具）　(vt) 跨越（障礙） |
| immensity | (nu) 巨大；龐大規模 |
| incumbent | (nc) 現任者　(adj) 現任的 |
| in defiance of | (phr.) 不顧；公然違抗 |
| irreversible | (adj) 不可逆的；無法挽回的 |
| lingering | (adj) 持續不去的；揮之不去的 |
| lose yourself in something | (phr.) 全神貫注於某事；沉浸其中 |
| miscellaneous | (adj) 各式各樣的；雜項的 |
| namely | (adv) 也就是說；即 |
| pass up | (phr.) 錯過（機會）；放棄 |
| pavilion | (nc) 展覽館；涼亭 |
| plunge | (vi) 驟然跌落；突然下降　(nc) 暴跌；大幅下滑 |
| preach | (vi) 說教；訓誡 |
| push back | (phr.) 推延；延後 |
| put in for something | (phr.) 正式申請；提出要求 |
| rear | (nc) 後方；後部　(adj) 後方的；後面的 |
| reinstate | (vt) 恢復（職位）；使復職 |
| ritual | (nc) 固定儀式；慣例 |
| scheme | (nc) 計畫；方案　(vi) 密謀；策劃陰謀 |
| scuff | (vt) 刮傷；磨損（表面）　(nc) 磨損痕跡；刮痕 |
| shred | (vt) 撕碎；粉碎（文件）　(nc) 1. 一點點；極少量　2. 碎片；細條 |
| speck | (nc) 微小的痕跡；小顆粒；少量 |
| take early retirement | (phr.) 提早退休 |
| underpass | (nc) 地下道；地下通道 |
| unwind | (vi) 放鬆；舒緩壓力　(vt) 解開；鬆開 |
| upbeat | (adj) 樂觀的；充滿希望的 |
| at full speed | (phr.) 以最快速度；全速地 |
| bear | (vt) 帶有；載有；懷有 |
| be held up in traffic | (phr.) 被塞車耽誤；被交通堵塞困住 |
| be towed away | (phr.) （車輛）被拖走 |
| bypass | (nc) 1. 環道；替代道路　2. 繞道手術 |
| carpool | (vi) 共乘（汽車）　(nc) 共乘車隊；汽車共乘小組 |
| carriage | (nc) 1. （火車）車廂　2. 馬車 |
| collide | (vi) 碰撞；相撞 |
| come to a standstill | (phr.) 停頓；停滯不前 |
| direct traffic | (phr.) 指揮交通 |
| drawbridge | (nc) 活動橋；可升降的橋 |
| driveway | (nc) 私人車道 |
| emphatic | (adj) 強調的；明確有力的 |
| footrest | (nc) 腳踏板；足部支撐架 |
| gratuity | (nc) 小費；服務費 |
| hastily | (adv) 匆忙地；倉促地 |
| have a flat tire | (phr.) 輪胎沒氣了；爆胎 |
| lane | (nc) 車道；跑道 |
| lean over the railing | (phr.) 倚靠或俯身在欄杆上 |
| license plate | (nc) 車牌 |
| march | (vi) 行進；邁步前進 |
| mileage | (nu) 行駛里程；油耗里程 |
| necessitate | (vt) 使…成為必要；需要 |
| overnight express | (nc) 夜間快車；隔夜快遞班次 |
| passerby | (nc) 路人；過路人 |
| principal | (adj) 主要的；首要的　(nc) 負責人；校長 |
| pull into | (phr.) （車輛）駛入並停靠 |
| ramp | (nc) 斜坡；坡道 |
| refurbish | (vt) 翻新；重新裝修 |
| ridership | (nu) （大眾運輸的）乘客人數 |
| spoke | (nc) （輪子的）輪輻 |
| steering wheel | (nc) 方向盤 |
| still | (adj) 靜止不動的 |
| storage compartment | (nc) 儲物櫃；置物空間 |
| streetcar | (nc) 有軌電車 |
| toll | (nc) 通行費；過路費 |
| wagon | (nc) 1. 貨運馬車　2. （火車）貨運車廂 |
| windshield | (nc) 擋風玻璃 |
| accounts payable | (nu) 應付帳款 |
| accrue | (vi) 累積；逐漸增加 |
| alternate | (vt) 交替進行；輪流做 |
| awfully | (adv) 非常；極其 |
| bank teller | (nc) 銀行櫃員；出納員 |
| be amazed at | (phr.) 對…感到驚訝；對…感到驚奇 |
| be caught in | (phr.) 被困在…裡；卡在…裡 |
| belatedly | (adv) 延遲地；為時已晚地 |
| cluster | (nc) 一群；一簇 |
| contender | (nc) 競爭者；角逐者 |
| debit card | (nc) 借記卡；轉帳卡 |
| deposit slip | (nc) 存款單 |
| deterrent | (nc) 嚇阻因素；威嚇手段 |
| direct deposit | (nu) 直接轉帳存入；薪資轉帳 |
| forge | (vt) 偽造；仿造 |
| forgery | (nu) 偽造；偽造罪　(nc) 偽造品；仿製品 |
| for the sake of | (phr.) 為了…的利益；為了…著想 |
| fortnight | (nc) 兩週；十四天 |
| make a withdrawal | (phr.) 提款；提取存款 |
| midtown | (nu) 市中心區域 |
| on standby | (phr.) 待命；隨時準備 |
| overdrawn | (adj) 透支的；超額提取的 |
| public holiday | (nc) 公共假日；國定假日 |
| redemption | (nc) （債券、股份等的）贖回，變現 |
| remit | (vt) 匯款；寄錢 |
| scrutinize | (vt) 仔細檢查；詳細審查 |
| secured | (adj) 有擔保的；有抵押保障的 |
| spurious | (adj) 虛假的；不實的 |
| sustain | (vt) 1. 維持；使持續　2. 支撐；維持（生存） |
| take out a loan | (phr.) 申請貸款；借貸 |
| take out insurance | (phr.) 投保；購買保險 |
| trust company | (nc) 信託公司 |
| twofold | (adj) 兩倍的　(adv) 兩倍地 |
| wire transfer | (nc) 電匯 |
| accredit | (vt) 認可；正式承認資格 |
| approximation | (nc) 大略的估計；近似值 |
| at one's disposal | (phr.) 供某人隨意使用；任憑某人調度 |
| attainable | (adj) 可達成的；可實現的 |
| confusion | (nu) 混亂；困惑不清的狀態 |
| considerate | (adj) 體貼的；體諒他人的 |
| consultation | (nc) 諮詢；商討會議 |
| cutback | (nc) 削減；縮減 |
| deflate | (vt) 使貨幣貶值；使經濟緊縮　(vi) 物價下跌；經濟緊縮萎縮 |
| deliberately | (adv) 故意地；蓄意地 |
| devalue | (vt) 使貨幣貶值 |
| devastate | (vt) 使遭受重創；徹底破壞 |
| emergency evacuation | (nc) 緊急疏散；緊急逃生 |
| evoke | (vt) 喚起；引起回憶或情感 |
| faithfully | (adv) 忠實地；忠誠地 |
| fictitious | (adj) 虛構的；假的 |
| impair | (vt) 損害；削弱功能或能力 |
| intake | (nu) 攝取量；吸入量 |
| in the vicinity of | (phr.) 在…附近；大約 |
| leaky | (adj) 會漏水的；會漏氣的 |
| legacy | (nc) 1. 從先人取得的遺產　2. 歷史遺風；前人留下的傳承 |
| outlying | (adj) 偏遠的；外圍的 |
| outweigh | (vt) 比…更重要；超過 |
| projected | (adj) 預計的；預測的 |
| property line | (nc) 地界線；產權界線 |
| reexamine | (vt) 重新審視；再次檢查 |
| set aside | (phr.) 撥出金錢或時間；保留 |
| take pride in | (phr.) 以…為榮；對…感到自豪 |
| tear | (vt) 撕；扯破 |
| wipe off | (phr.) 1. 擦掉；抹去　2. 使股票市值瞬間蒸發消失 |
| annex | (nc) 附屬建築；別館 |
| archway | (nc) 拱門；拱形通道 |
| be mounted on | (phr.) 被固定裝設於牆上或框架上 |
| canopy | (nc) 頂蓋；罩篷 |
| carpentry | (nu) 木工技術；木工手藝 |
| cast a shadow | (phr.) 為情況蒙上陰影；帶來不愉快的影響 |
| column | (nc) 1. 報刊專欄　2. 石柱；柱子 |
| courtyard | (nc) 中庭；院子 |
| cupboard | (nc) 碗櫃；儲物櫥 |
| dedication ceremony | (nc) 落成典禮；獻堂儀式 |
| desirable | (adj) 令人想要的；理想的 |
| doorway | (nc) 門口；門道 |
| dresser | (nc) 1. 梳妝台；衣櫃　2. 穿著特定風格的人 |
| erect | (vt) 建造；豎立　(adj) 直立的；挺直的 |
| faucet | (nc) 水龍頭 |
| fitting room | (nc) 試衣間 |
| fixture | (nc) 1. 固定裝置；固定設備　2. 固定不變的人或事物 |
| flooring | (nu) 地板材料 |
| hedge | (nc) 籬笆；綠籬　(vt) 嚴格限制　(vi) 迴避；不直接表態 |
| insulation | (nu) 1. 隔熱；隔音；絕緣措施　2. 隔熱材料；絕緣材料 |
| lamppost | (nc) 路燈柱 |
| ledge | (nc) 窄架；岩架；突出的窄台 |
| light bulb | (nc) 燈泡 |
| locale | (nc) 地點；場景 |
| make the bed | (phr.) 整理床鋪 |
| multistory | (adj) 多層樓的 |
| pole | (nc) 1. 桿；柱　2. 極；意見等的兩極端 |
| porch | (nc) 有頂門廊 |
| premises | (nc) 房屋及土地；場所 |
| reconfiguration | (nc) 重新配置；調整 |
| restoration | (nc) 修復；復原 |
| saw | (vt) 用鋸子切割　(nc) 鋸子 |
| shockproof | (adj) 防震的；耐衝擊的 |
| staircase | (nc) 樓梯 |
| startle | (vt) 使驚嚇；使嚇一跳 |
| symmetrically | (adv) 對稱地 |
| tap | (nc) 水龍頭 |
| tear down | (phr.) 拆除建築物 |
| uninhabited | (adj) 無人居住的 |
| windowsill | (nc) 窗台 |
| woodwork | (nu) 1. 建築物的木造部分　2. 木工手藝 |
| affirmative | (adj) 肯定的；表示同意的　(nc) 肯定的答覆；表示同意的話 |
| along the shore | (phr.) 沿著海岸；沿著湖岸或河岸 |
| atmospheric | (adj) 1. 大氣的；與空氣有關的　2. 有特殊氣氛的；神秘或浪漫的 |
| body of water | (nc) 水域 |
| botanical | (adj) 植物學的；與植物有關的 |
| cliff | (nc) 懸崖；峭壁 |
| depletion | (nu) 耗盡；減少 |
| fade | (vi) 褪色；逐漸消失 |
| fertile | (adj) 1. 肥沃的；豐產的　2. 能生育的；多產的 |
| fumes | (nc) 刺鼻或有害的煙霧；廢氣 |
| grazing | (nu) 放牧；牧草地 |
| hail | (nu) 冰雹　(vi) 下冰雹 |
| inclement | (adj) 天氣惡劣的 |
| irrigation system | (nc) 灌溉系統 |
| lakefront | (nc) 湖濱地區 |
| logging | (nu) 伐木業 |
| mining | (nu) 採礦業 |
| mow the lawn | (phr.) 割草；修剪草坪 |
| natural habitat | (nc) 自然棲息地 |
| nightfall | (nu) 黃昏；入夜時分 |
| nourishment | (nu) 營養；滋養 |
| nurture | (vt) 1. 養育；照顧尤指兒童或植物　2. 培育；扶植計畫或人才 |
| off the shore | (phr.) 離岸不遠處的海面上 |
| outskirts | (nc) 城鎮的郊區；外圍 |
| outwardly | (adv) 表面上；外表上看來 |
| overflow | (vi) 溢出；滿出來 |
| potted plant | (nc) 盆栽植物 |
| precipitation | (nu) 降水；雨或雪等 |
| promptness | (nu) 迅速；準時 |
| react to | (phr.) 對…做出反應 |
| residue | (nc) 1. 殘留物；剩餘物　2. 付清債務稅款後的遺產餘額 |
| revert | (vi) 恢復；回到原狀或原話題 |
| revolve | (vi) 繞著轉；圍繞旋轉 |
| rugged | (adj) 1. 崎嶇不平的　2. 粗獷強壯的；結實耐用的 |
| scenery | (nu) 自然風景；景色 |
| scenic | (adj) 風景優美的 |
| sewage | (nu) 汙水；下水道廢水 |
| sheer | (adj) 1. 完全的；十足的　2. 極陡峭的；近乎垂直的　3. 布料輕薄透明的 |
| shrub | (nc) 灌木；矮樹叢 |
| slope | (nc) 斜面；斜坡 |
| splendor | (nu) 壯麗；光輝 |
| stream | (nc) 小溪；水流　(vi) 源源不斷地流出；湧入 |
| sustainable | (adj) 可持續的；能維持下去的；永續的 |
| sweep | (vt) 打掃；清掃　(vi) 快速蔓延；席捲　(nc) 迅速有力的動作；橫掃 |
| tangible | (adj) 實際的；有形的；可具體感受到的 |
| terrestrial | (adj) 1. 陸地的；陸生的　2. 地面廣播的；非衛星的 |
| toxication | (nu) 中毒；毒化作用 |
| trimming | (nc) 邊緣的裝飾物；鑲邊 |
| trunk | (nc) 樹的主幹；血管或神經的主幹 |
| twilight | (nu) 黃昏；傍晚時分　(adj) 邊緣的；半明半暗的；近乎非法的 |
| acute | (adj) 1. 嚴重的；劇烈的　2. 敏銳的 |
| ailment | (nc) 疾病；小毛病 |
| ankle sprain | (nc) 腳踝扭傷 |
| asthma | (nu) 氣喘；哮喘 |
| be on medication | (phr.) 服藥中；正在服用藥物治療 |
| blurry | (adj) 模糊不清的 |
| deter | (vt) 阻止；使不敢做 |
| epidemic | (nc) 流行病；氾濫蔓延的現象　(adj) 流行的；猖獗的 |
| eradicate | (vt) 徹底消滅；根除 |
| exhale | (vi) 呼氣；吐氣 |
| first aid | (nu) 急救 |
| heart attack | (nc) 心臟病發作 |
| hiccup | (nc) 打嗝　(vi) 打嗝 |
| inhale | (vi) 吸入；吸氣　(vt) 狼吞虎嚥地吃 |
| insomnia | (nu) 失眠症 |
| intuitively | (adv) 憑直覺地 |
| lean back | (phr.) 向後靠；向後傾斜 |
| life expectancy | (nu) 預期壽命 |
| lifespan | (nc) 壽命；使用年限 |
| maternity ward | (nc) 產科病房 |
| medicinal | (adj) 藥用的；有療效的 |
| outpatient clinic | (nc) 門診部；門診診所 |
| over the counter | (phr.) 無需處方即可購買的；非處方的 |
| palpitation | (nc) 心悸 |
| paralysis | (nu) 麻痺；癱瘓 |
| perspire | (vi) 流汗；出汗 |
| plausible | (adj) 似乎可信的；言之有理的 |
| practitioner | (nc) 執業人員；尤指醫療專業人士 |
| prolonged | (adj) 持續很久的；長期的 |
| pulse | (nc) 脈搏 |
| recuperate | (vi) 康復；恢復健康 |
| recurring | (adj) 反覆發生的；週期性的 |
| resemble | (vt) 與…相似；像 |
| respiratory system | (nc) 呼吸系統 |
| respire | (vi) 呼吸 |
| sterilize | (vt) 1. 消毒；殺菌　2. 使絕育；結紮 |
| terminal | (adj) 末期的；無法治癒的　(nc) 航廈；終點站 |
| vaccination | (nc) 疫苗接種 |
| vocation | (nc) 天職；志業 |
| abolish | (vt) 廢除；廢止 |
| abstract | (adj) 抽象的 |
| accomplished | (adj) 熟練的；有才藝的 |
| accountable for | (phr.) 對…負有責任的 |
| acquaint someone with something | (phr.) 使…熟悉；使…認識 |
| adhere to | (phr.) 遵守；堅持 |
| advisable | (adj) 明智的；可取的 |
| after all | (phr.) 畢竟；終究 |
| aim | (vt) 打算；意圖　(nc) 目標；目的 |
| apprehensive | (adj) 擔憂的；不安的 |
| aptitude | (nc) 天賦；資質 |
| array | (nc) 一系列；一批(令人讚嘆的事物) |
| as it is | (phr.) 已經如此；照現況來看 |
| bend over | (phr.) 彎腰；俯身 |
| briefcase | (nc) 公事包；手提箱 |
| brisk | (adj) 熱絡的；快速且有活力的 |
| by means of | (phr.) 藉由；透過…的方式 |
| care for | (phr.) 愛慕；對…有好感(帶戀愛意味) |
| cast | (vt) 投擲；拋出(釣魚線等) |
| conceal | (vt) 隱藏；掩飾 |
| concrete | (adj) 具體的；確實的　(nu) 混凝土 |
| defy | (vt) 違抗；不顧；挑戰 |
| defy description | (phr.) 難以形容；無法形容 |
| disregard | (vt) 忽視；不理會　(nu) 漠視；不顧 |
| do one's utmost | (phr.) 竭盡全力 |
| drastic | (adj) 激烈的；極端的 |
| fairly | (adv) 相當地；還算 |
| favorably | (adv) 正面地；順利地 |
| implication | (nc) 1. 暗示；含意　2. (對未來的)影響；衝擊 |
| improvise | (vt) 臨時編造；即興創作 |
| in compliance with | (phr.) 遵照；符合(規定) |
| in total | (phr.) 總共 |
| in use | (phr.) 正在使用中 |
| keypad | (nc) 鍵盤；按鍵盤 |
| lightly | (adv) 1. 輕輕地　2. (烹調)簡單地；稍微地 |
| log on | (phr.) 登入 |
| mandate | (vt) 正式規定；授權　(nc) 授權；委任 |
| mastermind | (nc) 策劃者；幕後主謀　(vt) 策劃；主導 |
| mounting | (adj) 逐漸增加的 |
| on the wane | (phr.) 逐漸衰退；式微 |
| paper jam | (nc) (印表機)夾紙；卡紙 |
| shelf | (nc) 架子；擱板 |
| shovel | (nc) 鏟子　(vt) 用鏟子鏟 |
| showing | (nc) (作品的)展示；(表現的)呈現 |
| spare | (adj) 備用的；多餘的 |
| spare no expense | (phr.) 不惜花費；不吝成本 |
| subsequent | (adj) 隨後的；接下來的 |
| affix | (vt) 貼上；黏貼；蓋上(印章) |
| critical of | (adj) 對…持批評態度的 |
| liable for | (adj) 應負(法律)責任的 |
| liable to | (adj) 很可能(發生)的 |
| belt | (nc) 皮帶；腰帶 |
| subject to | (adj) 視…而定的；須經…核准的　(vt) 使遭受；使經歷 |
| bid for | (phr.) 出價競標；投標 |
| comforting | (adj) 令人安心的；帶來慰藉的 |
| commission | (vt) 委託；委任　(nc) 1. 委員會　2. 佣金 |
| commitment to | (phr.) 對…的承諾；致力於 |
| commodity | (nc) 商品；日用品 |
| counselor | (nc) 1. 顧問；輔導員　2. 律師 |
| courier | (nc) 快遞員；快遞公司　(vt) 用快遞寄送 |
| crate | (nc) 木箱；板條箱　(vt) 把…裝箱 |
| critique | (nc) 評論；評析 |
| curtail | (vt) 削減；限制 |
| customarily | (adv) 慣例上；通常 |
| cyclist | (nc) 騎自行車的人 |
| deadlock | (nc) 僵局 |
| deficient | (adj) 不足的；缺乏的 |
| detach | (vt) 使分離；拆下 |
| dispute over | (phr.) 關於…的爭議；糾紛 |
| encompass | (vt) 包含；涵蓋 |
| envision | (vt) 預見；設想 |
| exempt from | (phr.) 被豁免的；免除的 |
| firewood | (nu) 柴火；木柴 |
| hold | (vt) 1. 容納　2. 舉行 |
| hospitality industry | (nc) 服務業；餐旅業 |
| imperative | (adj) 極為重要的；必須的 |
| incidental | (adj) 附帶的；次要的 |
| indication | (nc) 跡象；顯示 |
| indulge in | (vi) 沉溺於；耽於 |
| infuriate | (vt) 使…極為憤怒 |
| lay the foundation | (phr.) 打下基礎；奠定基礎 |
| lid | (nc) 蓋子 |
| make progress | (phr.) 取得進展 |
| maneuver | (vt) 操縱；巧妙地移動 |
| markedly | (adv) 顯著地；明顯地 |
| midday | (nu) 正午；中午 |
| modification | (nc) 修改；調整 |
| narrow down to | (phr.) 縮減至；篩選至 |
| oblige | (vt) 強制；使有義務 |
| occupancy | (nu) (空間的)使用率；入住率 |
| offload | (vt) 卸貨；卸下 |
| omit | (vt) 遺漏；省略 |
| on consignment | (phr.) 以寄售方式 |
| outgoing | (adj) 即將離職的；外發的 |
| perishable | (adj) 易腐壞的 |
| pottery | (nu) 陶器 |
| proceed with | (phr.) 繼續進行 |
| projection | (nc) 預測；推估 |
| renewal | (nc) 1. 續約；續簽　2. 更新；重建 |
| rinse | (vt) 沖洗；漂洗 |
| senior | (nc) 1. 階級較高的人；上級　2. 年長者　(adj) 較高階的；資深的 |
| shift | (vt) 使轉移；調動　(vi) 轉移；改變 |
| shortfall | (nc) 短缺；差額 |
| span | (vt) 跨越；持續(一段時間)　(nc) 期間；跨度 |
| spice | (nc) 香料 |
| spray | (vt) 噴灑　(nc) 噴霧；噴劑 |
| stipulation | (nc) 規定；條款 |
| stir | (vt) 攪拌 |
| trim | (vt) 1. 修剪；剪整齊　2. 削減；縮減 |
| volume | (nc) 1. 音量　2. 容量；體積　3. (書的)冊；卷 |
| adjacent to | (phr.) 鄰近的；緊鄰的 |
| alternatively | (adv) 或者；換一種方式 |
| arise | (vi) 發生；出現 |
| assent | (vi) 同意；准許　(nu) 同意；批准 |
| attentive | (adj) 專注聆聽的；細心的 |
| authorship | (nu) 作者身分；著作權歸屬 |
| banking | (nu) 銀行業；銀行業務 |
| cautiously optimistic | (phr.) 謹慎樂觀的 |
| cavity | (nc) 1. 蛀牙；齲齒　2. (物體內的)空洞；孔洞 |
| Celsius | (nu) 攝氏(溫度) |
| chilly | (adj) 1. 寒冷的　2. (態度)冷淡的；不友善的 |
| collision | (nc) 碰撞；相撞事故 |
| compulsory | (adj) 必須的；強制性的 |
| consent | (nu) 同意；許可 |
| considerable | (adj) 相當大的；可觀的 |
| convert into | (phr.) 轉換成；改建成 |
| deliberation | (nu) 商議；審議 |
| delinquent | (adj) 逾期未繳的；拖欠的 |
| deplete | (vt) 耗盡；使減少 |
| deprivation | (nc) 匱乏；(生活必需品的)缺乏 |
| determine the cause of | (phr.) 查明…的原因 |
| dirt | (nu) 灰塵；污垃；泥土 |
| discharge | (vt) 1. 排放(廢棄物)　2. 准許(病人)出院；解除職務 |
| drape with | (phr.) 用(布)覆蓋；披掛 |
| duration | (nu) 期間；持續時間 |
| dwell | (vi) 居住 |
| excessive | (adj) 過度的；過多的 |
| expressly | (adv) 1. 明確地　2. 特意；專門為了 |
| fireplace | (nc) 壁爐 |
| hood | (nc) (汽車的)引擎蓋 |
| humid | (adj) 潮濕的 |
| improbable | (adj) 不太可能的；難以置信的 |
| induce | (vt) 1. 導致；引起　2. 說服；誘使 |
| inducement | (nc) 誘因；獎勵 |
| inflict | (vt) 使遭受；施加(損害) |
| informative | (adj) 資訊豐富的；有幫助的 |
| informed | (adj) 見聞廣博的；充分了解情況的 |
| inherently | (adv) 本質上；固有地 |
| inhibition | (nc) 拘束；顧慮 |
| innate | (adj) 天生的；固有的 |
| intensively | (adv) 密集地 |
| in the interest of | (phr.) 為了…的利益 |
| inward | (adv) 向內地 |
| ironing | (nu) 燙衣服 |
| lastingly | (adv) 持久地；長久地 |
| payable to | (phr.) (支票)應付給…的 |
| place an emphasis on | (phr.) 把重點放在；強調 |
| plaza | (nc) 廣場 |
| pleasing | (adj) 令人滿意的；討人喜歡的 |
| pollutant | (nc) 污染物 |
| premium | (nc) 保險費 |
| preside over | (phr.) 主持(會議、儀式等) |
| prevalent | (adj) 普遍存在的；盛行的 |
| prominently | (adv) 顯著地；顯眼地 |
| radically | (adv) 徹底地；根本地 |
| refutation | (nc) 反駁；駁斥 |
| refute | (vt) 反駁；駁斥 |
| remedy | (nc) 解決方法；補救措施 |
| rope | (nc) 繩子　(vt) 用繩子綑綁；拉攏 |
| safeguard | (nc) 保障措施　(vt) 保護；維護 |
| seating chart | (nc) 座位表 |
| smoking section | (nc) 吸菸區 |
| solely | (adv) 僅僅；單獨地 |
| susceptible | (adj) 易受影響的；容易受到…傷害的 |
| take into account | (phr.) 將…納入考量 |
| unprecedented | (adj) 前所未有的；空前的 |
| veranda | (nc) 陽台；走廊 |
| vested interest | (phr.) (既得的)個人利益；私利 |
| accommodation | (nu) 住宿　(nc) 妥協；通融 |
| alternative | (adj) 替代的；另一種的　(nc) 替代方案；另一種選擇 |
| appliance | (nc) 家用電器；器具 |
| approximately | (adv) 大約；大概 |
| campaign | (nc) 宣傳活動；活動　(vi) 發起運動；進行遊說 |
| ceremony | (nc) 典禮；儀式 |
| competence | (nu) 能力；勝任能力 |
| complete | (adj) 完整的；十足的　(vt) 完成 |
| comprehensive | (adj) 詳盡的；全面的 |
| convey | (vt) 傳達；表達 |
| convincingly | (adv) 令人信服地；有說服力地 |
| cooperation | (nu) 合作；配合 |
| delegate | (nc) 代表　(vt) 委派；授權 |
| duplicate | (nc) 副本；複本　(vt) 複製；重複 |
| enthusiasm | (nu) 熱忱；熱情 |
| entitle | (vt) 使有權利；給予資格 |
| estimate | (nc) 估價；估計數　(vt) 估計；估算 |
| extracurricular | (adj) 課外的 |
| etiquette | (nu) 禮儀；禮節 |
| fuel | (nu) 燃料　(vt) 刺激；助長 |
| impose | (vt) 施加；強制實行　(vi) 打擾；造成不便 |
| innovative | (adj) 創新的；新穎的 |
| intelligent | (adj) 聰明的；有智慧的 |
| invoice | (nc) 發票；帳單　(vt) 開發票給 |
| launch | (vt) 推出；發起　(nc) 推出；發行 |
| manufacturer | (nc) 製造商；廠商 |
| layout | (nc) 佈局；編排 |
| maintenance | (nu) 維修；保養 |
| occupation | (nc) 職業 |
| organization | (nc) 機構；團體　(nu) 組織；安排 |
| philosophy | (nu) 哲學　(nc) 理念；原則 |
| permit | (nc) 許可證　(vt) 允許；准許 |
| photography | (nu) 攝影；攝影術 |
| postage | (nu) 郵資 |
| potential | (adj) 潛在的　(nu) 潛力 |
| precise | (adj) 精確的；準確的 |
| presentation | (nc) 簡報；報告　(nu) 呈現方式；外觀 |
| priority | (nc) 優先事項　(nu) 優先權 |
| procedure | (nc) 程序；步驟 |
| purchase | (vt) 購買　(nc) 購買的物品 |
| prior to | (prep) 在…之前；先於 |
| profile | (nc) 1. 個人資料；簡介　2. 形象；知名度 |
| private | (adj) 1. 私人的；私密的　2. 私營的 |
| projector | (nc) 投影機 |
| red carpet | (nc) 隆重的禮遇；貴賓待遇 |
| proposal | (nc) 提案；建議 |
| recognize | (vt) 1. 認出；辨識出　2. 承認；表彰 |
| punctual | (adj) 準時的 |
| receipt | (nc) 收據　(nu) 收到 |
| semester | (nc) 學期 |
| reception | (nc) 1. 接待處　2. 招待會；歡迎會 |
| significant | (adj) 重大的；顯著的 |
| regret | (vt) 後悔；對…感到遺憾　(nu) 懊悔；遺憾 |
| slide | (vi) 下滑；下跌　(nc) 投影片 |
| reliable | (adj) 可靠的 |
| socialize | (vi) 交際；社交往來 |
| reminder | (nc) 提醒；提醒事項 |
| squeeze | (vt) 擠壓；壓縮　(nc) 緊縮；擠壓 |
| representative | (adj) 典型的；代表性的　(nc) 代表；業務員 |
| storage | (nu) 儲存；倉儲 |
| requirement | (nc) 要求；必要條件 |
| strengthen | (vt) 增強；加強 |
| straw | (nc) 吸管　(nu) 稻草 |
| strict | (adj) 嚴格的；嚴厲的 |
| stress | (nu) 壓力；緊張　(vt) 強調 |
| submit | (vt) 提交　(vi) 屈服；服從 |
| strike | (nc) 罷工　(vt) 1. 打；擊中　2. 使突然想到 |
| summary | (nc) 摘要；概要 |
| supply | (nu) 供應；供應量　(vt) 供應；提供 |
| submission | (nc) 提交物；投稿　(nu) 屈服；聽從 |
| urgent | (adj) 緊急的；迫切的 |
| take up | (phr.) 1. 佔用　2. 開始從事；著手進行 |
| vet | (nc) 獸醫　(vt) 審查；核實 |
| vice president | (nc) 副總裁；副總統 |
| video conference | (nc) 視訊會議 |
| voucher | (nc) 禮券；憑證 |
| gravitate | (vi) 受吸引；自然趨向 |
| dictate | (vt) 1. 口述；聽寫　2. 規定；決定 |
| diminish | (vt) 減少；縮小　(vi) 減少；變小 |
| adherence | (nu) 堅持；遵守 |
| resonate | (vi) 引起共鳴；產生迴響 |

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
  },
  {
    id: "w97", english: "retaliate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vi", meaningGroups: [ ["報復","反擊"] ] } ],
    examples: [ { en:"The competitor retaliated by cutting its prices by 20 percent.", zh:"這家對手公司以降價百分之二十作為報復。" } ]
  },
  {
    id: "w98", english: "enlist", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["徵募","爭取（支持、協助）"] ] },
      { pos: "vi", meaningGroups: [ ["從軍","入伍"] ] }
    ],
    examples: [
      { en:"The manager enlisted the help of an outside consultant.", zh:"經理尋求了一位外部顧問的協助。" },
      { en:"He enlisted in the navy right after graduation.", zh:"他一畢業就從軍加入海軍。" }
    ]
  },
  {
    id: "w99", english: "tetanus", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["破傷風"] ] } ],
    examples: [ { en:"The construction worker received a tetanus shot after the injury.", zh:"這名建築工人受傷後施打了破傷風疫苗。" } ]
  },
  {
    id: "w100", english: "monotony", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["單調","乏味"] ] } ],
    examples: [ { en:"Employees suggested new activities to break the monotony of daily routines.", zh:"員工建議增加新活動來打破日常例行工作的單調。" } ]
  },
  {
    id: "w101", english: "labyrinth", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["迷宮","錯綜複雜的事物"] ] } ],
    examples: [ { en:"Navigating the company's approval process felt like a labyrinth.", zh:"在公司的核准流程中穿梭，感覺就像走迷宮一樣。" } ]
  },
  {
    id: "w102", english: "calico", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["印花棉布"] ] } ],
    examples: [ { en:"The tablecloths were made from bright red calico.", zh:"這些桌巾是用鮮紅色印花棉布做的。" } ]
  },
  {
    id: "w103", english: "delegation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["代表團"] ] },
      { pos: "nu", meaningGroups: [ ["授權","委派"] ] }
    ],
    examples: [
      { en:"A delegation from the head office will visit the factory next week.", zh:"總部的一個代表團下週將參訪工廠。" },
      { en:"Effective delegation of tasks improves team efficiency.", zh:"有效的任務委派能提升團隊效率。" }
    ]
  },
  {
    id: "w104", english: "cumbersome", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["笨重的","累贅的","繁瑣的"] ] } ],
    examples: [ { en:"The old filing system was cumbersome and slowed down the office.", zh:"舊的歸檔系統既繁瑣又拖慢了辦公室的效率。" } ]
  },
  {
    id: "w105", english: "visceral", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["發自本能的","直覺的"] ] } ],
    examples: [ { en:"Customers had a visceral reaction to the price increase.", zh:"顧客對這次漲價有著本能且強烈的反應。" } ]
  },
  {
    id: "w106", english: "adjourn", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["休會","延期","暫停（會議）"] ] } ],
    examples: [ { en:"The meeting was adjourned until next Monday.", zh:"會議延期到下週一。" } ]
  },
  {
    id: "w107", english: "drivel", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vi", meaningGroups: [ ["胡言亂語","說廢話"] ] } ],
    examples: [ { en:"Stop drivelling and get to the point.", zh:"別再胡言亂語了，講重點。" } ]
  },
  {
    id: "w108", english: "scandalously", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["可恥地","駭人聽聞地"] ] } ],
    examples: [ { en:"The former manager was accused of scandalously misusing company funds.", zh:"這位前任經理被控駭人聽聞地挪用公司資金。" } ]
  },
  {
    id: "w109", english: "conformance", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["符合","遵從（規範、標準）"] ] } ],
    examples: [ { en:"The product passed conformance testing before shipment.", zh:"這項產品在出貨前通過了符合性測試。" } ]
  },
{
    id: "w110", english: "bacon", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["培根","醃肉"] ] }
    ],
    examples: [
      { en:"She fried some bacon and eggs for breakfast.", zh:"她煎了培根和蛋當早餐。" }
    ]
  },
  {
    id: "w111", english: "ballet", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["芭蕾舞"] ] }
    ],
    examples: [
      { en:"The children take ballet lessons every Saturday.", zh:"孩子們每週六上芭蕾舞課。" }
    ]
  },
  {
    id: "w112", english: "banana split", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["香蕉船"] ] }
    ],
    examples: [
      { en:"We ordered a banana split to share after dinner.", zh:"我們晚餐後點了一份香蕉船一起分享。" }
    ]
  },
  {
    id: "w113", english: "barely", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adv", meaningGroups: [ ["幾乎不","勉強地"] ] }
    ],
    examples: [
      { en:"She barely finished the report before the deadline.", zh:"她在截止期限前勉強完成了報告。" }
    ]
  },
  {
    id: "w114", english: "barrel", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["桶","一桶"] ] }
    ],
    examples: [
      { en:"Oil prices rose after production fell by two million barrels.", zh:"石油產量減少兩百萬桶後，油價上漲。" }
    ]
  },
  {
    id: "w115", english: "barrier", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["障礙","屏障"] ] }
    ],
    examples: [
      { en:"Language can be a major barrier in international business negotiations.", zh:"語言在國際商業談判中可能是一大障礙。" }
    ]
  },
  {
    id: "w116", english: "basis", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["基礎","依據"] ] }
    ],
    examples: [
      { en:"Employees are paid on a monthly basis.", zh:"員工按月支薪。" }
    ]
  },
  {
    id: "w117", english: "battery", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["電池"] ] }
    ],
    examples: [
      { en:"Please replace the battery in the smoke detector.", zh:"請更換煙霧偵測器裡的電池。" }
    ]
  },
  {
    id: "w118", english: "bay", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["灣","海灣"] ] }
    ],
    examples: [
      { en:"The hotel offers a beautiful view of the bay.", zh:"這家飯店可以欣賞到美麗的海灣景色。" }
    ]
  },
  {
    id: "w119", english: "beast", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["野獸"] ] }
    ],
    examples: [
      { en:"The documentary shows how the beast hunts for food in the wild.", zh:"這部紀錄片展示了這隻野獸在野外如何獵食。" }
    ]
  },
  {
    id: "w120", english: "belly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["腹部","肚子"] ] }
    ],
    examples: [
      { en:"He lay on his belly to look under the machine.", zh:"他趴在地上看機器底下。" }
    ]
  },
  {
    id: "w121", english: "berry", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["漿果"] ] }
    ],
    examples: [
      { en:"The bushes were full of ripe berries in early summer.", zh:"初夏時灌木叢裡結滿了成熟的漿果。" }
    ]
  },
  {
    id: "w122", english: "bidding", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["投標","出價"] ] }
    ],
    examples: [
      { en:"The construction contract will be awarded through competitive bidding.", zh:"這項建築合約將透過競標方式發放。" }
    ]
  },
  {
    id: "w123", english: "billion", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["十億"] ] }
    ],
    examples: [
      { en:"The company's annual revenue exceeded three billion dollars.", zh:"該公司年營收超過三十億美元。" }
    ]
  },
  {
    id: "w124", english: "biography", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["傳記"] ] }
    ],
    examples: [
      { en:"He is writing a biography of the company's founder.", zh:"他正在寫這家公司創辦人的傳記。" }
    ]
  },
  {
    id: "w125", english: "biscuit", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["餅乾"] ] }
    ],
    examples: [
      { en:"She served tea and biscuits to the guests.", zh:"她端出茶和餅乾招待客人。" }
    ]
  },
  {
    id: "w126", english: "black and white", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["黑白的"], ["白紙黑字的","書面明確的"] ] }
    ],
    examples: [
      { en:"The old photo was printed in black and white.", zh:"這張老照片是用黑白印製的。" },
      { en:"Please put the agreement in black and white before we proceed.", zh:"在我們繼續之前，請把這項協議白紙黑字寫清楚。" }
    ]
  },
  {
    id: "w127", english: "bloom", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["開花","綻放"] ] }
    ],
    examples: [
      { en:"The cherry trees bloom in early April.", zh:"櫻花樹在四月初開花。" }
    ]
  },
  {
    id: "w128", english: "blossom", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["開花","綻放"], ["蓬勃發展","茁壯成長"] ] }
    ],
    examples: [
      { en:"The apple trees blossom every spring.", zh:"蘋果樹每年春天開花。" },
      { en:"Her career blossomed after she joined the marketing team.", zh:"她加入行銷團隊後，事業蓬勃發展。" }
    ]
  },
  {
    id: "w129", english: "border", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["邊界","國界"] ] },
      { pos: "vt", meaningGroups: [ ["與…為界","毗鄰"] ] }
    ],
    examples: [
      { en:"The two countries share a long border.", zh:"這兩個國家有一段很長的邊界。" },
      { en:"Germany borders France to the west.", zh:"德國西邊與法國為界。" }
    ]
  },
  {
    id: "w130", english: "branch", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["分公司","分店"], ["樹枝","枝幹"] ] }
    ],
    examples: [
      { en:"The bank opened a new branch downtown.", zh:"這家銀行在市中心開了一家新分行。" },
      { en:"A bird landed on a branch outside the window.", zh:"一隻鳥停在窗外的樹枝上。" }
    ]
  },
  {
    id: "w131", english: "break out", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["爆發","突然發生"] ] }
    ],
    examples: [
      { en:"A fire broke out in the warehouse last night.", zh:"昨晚倉庫發生了一場火災。" }
    ]
  },
  {
    id: "w132", english: "brilliant", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["燦爛的","出色的","極好的"] ] }
    ],
    examples: [
      { en:"She came up with a brilliant solution to the budget problem.", zh:"她想出了一個解決預算問題的絕妙辦法。" }
    ]
  },
  {
    id: "w133", english: "bring something to life", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["使…栩栩如生","賦予生命力"] ] }
    ],
    examples: [
      { en:"The new special effects really bring the film to life.", zh:"這些新的特效真的讓這部電影栩栩如生。" }
    ]
  },
  {
    id: "w134", english: "broadcast", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["廣播","播送"] ] },
      { pos: "nc", meaningGroups: [ ["廣播節目","轉播"] ] }
    ],
    examples: [
      { en:"The network will broadcast the conference live.", zh:"這家電視台將現場直播這場會議。" },
      { en:"We watched the evening broadcast together.", zh:"我們一起看了晚間的新聞節目。" }
    ]
  },
  {
    id: "w135", english: "brutal", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["殘暴的","殘酷的"] ] }
    ],
    examples: [
      { en:"The competition in this market has become brutal.", zh:"這個市場的競爭變得非常殘酷。" }
    ]
  },
  {
    id: "w136", english: "buffet", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["自助餐"] ] }
    ],
    examples: [
      { en:"The hotel offers a breakfast buffet every morning.", zh:"這家飯店每天早上提供自助式早餐。" }
    ]
  },
  {
    id: "w137", english: "bulb", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["燈泡"], ["球根"] ] }
    ],
    examples: [
      { en:"Please change the bulb in the hallway light.", zh:"請更換走廊燈的燈泡。" },
      { en:"She planted tulip bulbs in the garden last fall.", zh:"她去年秋天在花園裡種下了鬱金香球根。" }
    ]
  },
  {
    id: "w138", english: "cancellation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["取消","作廢"] ] }
    ],
    examples: [
      { en:"The airline notified passengers of the flight cancellation by email.", zh:"航空公司透過電子郵件通知乘客航班取消的消息。" }
    ]
  },
  {
    id: "w139", english: "candidate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["候選人","應徵者"] ] }
    ],
    examples: [
      { en:"The HR department is interviewing three candidates for the position.", zh:"人資部門正在面談三位應徵這個職位的候選人。" }
    ]
  },
  {
    id: "w140", english: "capable", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["有能力的","能勝任的"] ] }
    ],
    examples: [
      { en:"She is fully capable of managing the entire project on her own.", zh:"她完全有能力獨自管理整個專案。" }
    ]
  },
  {
    id: "w141", english: "capture", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["捕獲","捉住"], ["捕捉","擷取"] ] }
    ],
    examples: [
      { en:"The zoo successfully captured the escaped tiger.", zh:"動物園成功捕獲了逃脫的老虎。" },
      { en:"The advertisement quickly captured the attention of consumers.", zh:"這則廣告很快就抓住了消費者的注意力。" }
    ]
  },
  {
    id: "w142", english: "care for someone", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["照顧","關心"] ] }
    ],
    examples: [
      { en:"She has cared for her elderly parents for years.", zh:"她多年來一直照顧著年邁的父母。" }
    ]
  },
  {
    id: "w143", english: "career", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["職業生涯","事業"] ] }
    ],
    examples: [
      { en:"He decided to pursue a career in finance.", zh:"他決定投身金融業發展事業。" }
    ]
  },
  {
    id: "w144", english: "carve out", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["開拓","努力創造出"] ] }
    ],
    examples: [
      { en:"The startup managed to carve out a niche in the crowded market.", zh:"這家新創公司成功在競爭激烈的市場中開拓出一塊利基市場。" }
    ]
  },
  {
    id: "w145", english: "case", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["案例","情況"] ] }
    ],
    examples: [
      { en:"In this case, we need approval from senior management.", zh:"在這種情況下，我們需要獲得高層管理的核准。" }
    ]
  },
  {
    id: "w146", english: "catch", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["抓住","趕上"] ] },
      { pos: "nc", meaningGroups: [ ["隱藏的問題","陷阱"] ] }
    ],
    examples: [
      { en:"He ran to catch the last train home.", zh:"他跑去趕搭最後一班回家的火車。" },
      { en:"The offer sounds great, but there must be a catch.", zh:"這個提案聽起來很棒，但一定有什麼隱藏的問題。" }
    ]
  },
  {
    id: "w147", english: "cause", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["原因","起因"] ] },
      { pos: "vt", meaningGroups: [ ["導致","造成"] ] }
    ],
    examples: [
      { en:"Investigators are still trying to determine the cause of the delay.", zh:"調查人員仍在試圖確定延誤的原因。" },
      { en:"The software update caused several errors in the system.", zh:"這次軟體更新導致系統出現多個錯誤。" }
    ]
  },
  {
    id: "w148", english: "celebration", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["慶祝活動","慶典"] ] }
    ],
    examples: [
      { en:"The company held a celebration for its tenth anniversary.", zh:"公司為十週年舉辦了一場慶祝活動。" }
    ]
  },
  {
    id: "w149", english: "century", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["世紀"] ] }
    ],
    examples: [
      { en:"The firm has been in business for over a century.", zh:"這家公司已經經營超過一個世紀。" }
    ]
  },
  {
    id: "w150", english: "chain", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["連鎖店","連鎖企業"], ["鏈子"] ] }
    ],
    examples: [
      { en:"The restaurant chain plans to open ten new branches this year.", zh:"這家連鎖餐廳計畫今年再開十家新分店。" },
      { en:"He locked his bicycle with a heavy chain.", zh:"他用一條粗重的鏈子鎖住他的自行車。" }
    ]
  },
  {
    id: "w151", english: "challenge", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["挑戰","難題"] ] },
      { pos: "vt", meaningGroups: [ ["質疑","向…挑戰"] ] }
    ],
    examples: [
      { en:"Finding qualified staff remains a major challenge for the company.", zh:"招募合格的員工仍是這家公司的一大挑戰。" },
      { en:"She challenged the manager's decision during the meeting.", zh:"她在會議中質疑了經理的決定。" }
    ]
  },
  {
    id: "w152", english: "chamber", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["會議廳","議院"] ] }
    ],
    examples: [
      { en:"The bill was debated in the upper chamber of parliament.", zh:"這項法案在國會的上議院進行了辯論。" }
    ]
  },
  {
    id: "w153", english: "channel", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["頻道","管道"] ] },
      { pos: "vt", meaningGroups: [ ["引導","輸送"] ] }
    ],
    examples: [
      { en:"Customers can submit complaints through several channels.", zh:"顧客可以透過多種管道提出投訴。" },
      { en:"The manager channeled the extra budget into staff training.", zh:"經理把額外的預算用於員工培訓。" }
    ]
  },
  {
    id: "w154", english: "chapter", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["章節"], ["分會"] ] }
    ],
    examples: [
      { en:"Please read the first chapter before the next meeting.", zh:"請在下次會議前讀完第一章。" },
      { en:"The organization has local chapters in over twenty cities.", zh:"這個組織在二十多個城市設有地方分會。" }
    ]
  },
  {
    id: "w155", english: "character", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["人物","角色"] ] },
      { pos: "nu", meaningGroups: [ ["性格","特質"] ] }
    ],
    examples: [
      { en:"The main character in the novel is a young entrepreneur.", zh:"這部小說的主角是一位年輕的企業家。" },
      { en:"Honesty is an important part of her character.", zh:"誠實是她性格中重要的一部分。" }
    ]
  },
  {
    id: "w156", english: "characteristic", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["特徵","特色"] ] },
      { pos: "adj", meaningGroups: [ ["典型的","特有的"] ] }
    ],
    examples: [
      { en:"Flexibility is a key characteristic of a good manager.", zh:"靈活性是優秀主管的一項重要特徵。" },
      { en:"She handled the crisis with her characteristic calm.", zh:"她用她一貫的冷靜處理了這場危機。" }
    ]
  },
  {
    id: "w157", english: "charm", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["魅力"] ] },
      { pos: "vt", meaningGroups: [ ["使陷入魅力","迷住"] ] }
    ],
    examples: [
      { en:"The old town is full of charm.", zh:"這座老城充滿魅力。" },
      { en:"The sales rep charmed the client with his friendly manner.", zh:"這位業務代表用他親切的態度迷住了客戶。" }
    ]
  },
  {
    id: "w158", english: "cheerful", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["愉快的","開朗的"] ] }
    ],
    examples: [
      { en:"The receptionist always greets visitors with a cheerful smile.", zh:"這位接待員總是帶著愉快的笑容迎接訪客。" }
    ]
  },
  {
    id: "w159", english: "chemical", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["化學物質"] ] },
      { pos: "adj", meaningGroups: [ ["化學的"] ] }
    ],
    examples: [
      { en:"Workers must wear gloves when handling chemicals.", zh:"工作人員在處理化學物質時必須戴手套。" },
      { en:"The factory uses a chemical process to purify the water.", zh:"這家工廠使用化學程序來淨化水質。" }
    ]
  },
  {
    id: "w160", english: "cherry", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["櫻桃"] ] }
    ],
    examples: [
      { en:"She bought a basket of fresh cherries at the market.", zh:"她在市場買了一籃新鮮的櫻桃。" }
    ]
  },
  {
    id: "w161", english: "chicken breast", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["雞胸肉"] ] }
    ],
    examples: [
      { en:"The recipe calls for two boneless chicken breasts.", zh:"這份食譜需要兩片去骨雞胸肉。" }
    ]
  },
  {
    id: "w162", english: "chip", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["碎片","缺口"], ["洋芋片"], ["晶片"] ] },
      { pos: "vt", meaningGroups: [ ["削出缺口","打出缺角"] ] }
    ],
    examples: [
      { en:"There's a chip in the edge of this plate.", zh:"這個盤子邊緣有個缺口。" },
      { en:"He grabbed a bag of chips from the vending machine.", zh:"他從自動販賣機拿了一包洋芋片。" },
      { en:"The new chip inside the phone makes it much faster.", zh:"這款手機裡的新晶片讓它速度快了許多。" },
      { en:"She chipped the mug while washing dishes.", zh:"她洗碗時把馬克杯打出了一個缺角。" }
    ]
  },
  {
    id: "w163", english: "chirp", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["發出唧唧聲","啁啾"] ] }
    ],
    examples: [
      { en:"Birds were chirping outside the office window all morning.", zh:"整個早上，辦公室窗外都有鳥兒啁啾。" }
    ]
  },
  {
    id: "w164", english: "chopped", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["切碎的"] ] }
    ],
    examples: [
      { en:"The salad is topped with chopped nuts and dried fruit.", zh:"這份沙拉上面撒了切碎的堅果和果乾。" }
    ]
  },
  {
    id: "w165", english: "claim", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["聲稱","宣稱"], ["索取","申請理賠"] ] },
      { pos: "nc", meaningGroups: [ ["索賠","理賠申請"] ] }
    ],
    examples: [
      { en:"The supplier claims that the delay was caused by a shipping error.", zh:"供應商聲稱這次延誤是運輸錯誤造成的。" },
      { en:"He filed a claim with the insurance company after the accident.", zh:"事故發生後，他向保險公司提出理賠申請。" }
    ]
  },
  {
    id: "w166", english: "clear", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["清楚的","明確的"] ] },
      { pos: "vt", meaningGroups: [ ["清除","結清"] ] }
    ],
    examples: [
      { en:"The instructions were clear and easy to follow.", zh:"這些指示清楚易懂。" },
      { en:"Please clear your desk before the office move.", zh:"辦公室搬遷前請清空你的桌面。" }
    ]
  },
  {
    id: "w167", english: "click", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["點擊"] ] },
      { pos: "vi", meaningGroups: [ ["合得來","意氣相投"] ] }
    ],
    examples: [
      { en:"Click the link to download the file.", zh:"點擊這個連結以下載檔案。" },
      { en:"The two new colleagues just clicked right away.", zh:"這兩位新同事一見面就很合得來。" }
    ]
  },
  {
    id: "w168", english: "clothing", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["衣物","服裝"] ] }
    ],
    examples: [
      { en:"The store sells clothing for the whole family.", zh:"這家店販售全家人的服裝。" }
    ]
  },
  {
    id: "w169", english: "clue", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["線索","提示"] ] }
    ],
    examples: [
      { en:"The detective found an important clue at the scene.", zh:"這位探長在現場找到了一個重要線索。" }
    ]
  },
  {
    id: "w170", english: "cocktail dress", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["雞尾酒禮服","小禮服"] ] }
    ],
    examples: [
      { en:"She wore a black cocktail dress to the company party.", zh:"她穿了一件黑色雞尾酒禮服參加公司派對。" }
    ]
  },
  {
    id: "w171", english: "coconut", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["椰子"] ] }
    ],
    examples: [
      { en:"He opened a fresh coconut and drank the water inside.", zh:"他打開一顆新鮮椰子，喝了裡面的椰子水。" }
    ]
  },
  {
    id: "w172", english: "code", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["法規","準則"], ["代碼","密碼"] ] }
    ],
    examples: [
      { en:"All staff must follow the company's dress code.", zh:"所有員工都必須遵守公司的服裝規定。" },
      { en:"You will receive a confirmation code by text message.", zh:"你將會收到一則簡訊確認碼。" }
    ]
  },
  {
    id: "w173", english: "combine", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["結合","合併"] ] }
    ],
    examples: [
      { en:"The two departments will combine their resources on this project.", zh:"這兩個部門將在這個專案上整合資源。" }
    ]
  },
  {
    id: "w174", english: "come in handy", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["派上用場","很有用"] ] }
    ],
    examples: [
      { en:"This extra cable will come in handy during the presentation.", zh:"這條備用的電線在報告時會派上用場。" }
    ]
  },
  {
    id: "w175", english: "come into play", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["開始起作用","發揮作用"] ] }
    ],
    examples: [
      { en:"Several factors come into play when setting the final price.", zh:"在制定最終價格時，有好幾個因素會發揮作用。" }
    ]
  },
  {
    id: "w176", english: "comedy", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["喜劇"] ] }
    ],
    examples: [
      { en:"The theater is showing a popular comedy this weekend.", zh:"這家劇院這個週末上演一部很受歡迎的喜劇。" }
    ]
  },
  {
    id: "w177", english: "comfort", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["舒適","安慰"] ] },
      { pos: "vt", meaningGroups: [ ["安慰"] ] }
    ],
    examples: [
      { en:"The new chairs were designed for maximum comfort.", zh:"這些新椅子的設計以舒適度為優先。" },
      { en:"Her colleague comforted her after the difficult client call.", zh:"她跟客戶通了一次很難應付的電話之後，同事安慰了她。" }
    ]
  },
  {
    id: "w178", english: "comic", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["喜劇的","滑稽的"] ] },
      { pos: "nc", meaningGroups: [ ["漫畫"] ] }
    ],
    examples: [
      { en:"He has a comic way of explaining serious topics.", zh:"他用一種滑稽的方式來解釋嚴肅的主題。" },
      { en:"My son collects comics from that publisher.", zh:"我兒子收集那家出版社的漫畫。" }
    ]
  },
  {
    id: "w179", english: "comment", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["評論","意見"] ] },
      { pos: "vi", meaningGroups: [ ["發表評論","表示意見"] ] }
    ],
    examples: [
      { en:"Please leave your comments in the box below.", zh:"請在下方欄位留下你的意見。" },
      { en:"The spokesperson declined to comment on the merger.", zh:"發言人拒絕針對這次併購發表評論。" }
    ]
  },
  {
    id: "w180", english: "commerce", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["商業","貿易"] ] }
    ],
    examples: [
      { en:"The city has long been a center of commerce.", zh:"這座城市長期以來都是商業中心。" }
    ]
  },
  {
    id: "w181", english: "commercial", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["廣告"] ] },
      { pos: "adj", meaningGroups: [ ["商業的","商用的"] ] }
    ],
    examples: [
      { en:"The company aired a new commercial during the game.", zh:"這家公司在比賽期間播出了一則新廣告。" },
      { en:"The building is zoned for commercial use only.", zh:"這棟大樓的用途劃分僅限於商業用途。" }
    ]
  },
  {
    id: "w182", english: "committed", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["全心投入的","有承諾的"] ] }
    ],
    examples: [
      { en:"She is fully committed to meeting the project deadline.", zh:"她全心投入以確保如期完成專案。" }
    ]
  },
  {
    id: "w183", english: "communicate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["溝通","交流"] ] },
      { pos: "vt", meaningGroups: [ ["傳達"] ] }
    ],
    examples: [
      { en:"Good managers communicate clearly with their teams.", zh:"優秀的主管會與團隊清楚地溝通。" },
      { en:"The memo communicated the new policy to all employees.", zh:"這份備忘錄向所有員工傳達了新的政策。" }
    ]
  },
  {
    id: "w184", english: "community", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["社區","社群"] ] }
    ],
    examples: [
      { en:"The company supports several local community programs.", zh:"這家公司支持好幾項當地的社區計畫。" }
    ]
  },
  {
    id: "w185", english: "compete", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["競爭"] ] }
    ],
    examples: [
      { en:"Small businesses often struggle to compete with large chains.", zh:"小型企業經常很難與大型連鎖企業競爭。" }
    ]
  },
  {
    id: "w186", english: "competition", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["競爭"], ["比賽"] ] }
    ],
    examples: [
      { en:"The market has seen fierce competition in recent years.", zh:"近年來這個市場出現了激烈的競爭。" },
      { en:"She won first place in the essay competition.", zh:"她在徵文比賽中獲得第一名。" }
    ]
  },
  {
    id: "w187", english: "competitor", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["競爭者","對手"] ] }
    ],
    examples: [
      { en:"Our main competitor just lowered its prices.", zh:"我們主要的競爭對手剛剛降價了。" }
    ]
  },
  {
    id: "w188", english: "complaint", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["抱怨","投訴"] ] }
    ],
    examples: [
      { en:"The customer service team handles complaints within 24 hours.", zh:"客服團隊會在24小時內處理投訴。" }
    ]
  },
  {
    id: "w189", english: "complex", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["複雜的"] ] },
      { pos: "nc", meaningGroups: [ ["綜合建築群"] ] }
    ],
    examples: [
      { en:"The tax regulations are extremely complex.", zh:"稅務法規極其複雜。" },
      { en:"The new office complex includes a gym and a cafeteria.", zh:"這個新的辦公大樓群包含一間健身房和一間員工餐廳。" }
    ]
  },
  {
    id: "w190", english: "complicated", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["複雜的","難懂的"] ] }
    ],
    examples: [
      { en:"The application process turned out to be more complicated than expected.", zh:"申請流程比預期的更加複雜。" }
    ]
  },
  {
    id: "w191", english: "compose", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["組成","構成"], ["創作","譜寫"] ] }
    ],
    examples: [
      { en:"The committee is composed of five senior managers.", zh:"這個委員會由五位高階經理組成。" },
      { en:"She composed the music for the company's promotional video.", zh:"她為公司的宣傳影片譜寫了音樂。" }
    ]
  },
  {
    id: "w192", english: "compound", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["化合物"], ["建築群","場地"] ] },
      { pos: "adj", meaningGroups: [ ["複合的","混合的"] ] }
    ],
    examples: [
      { en:"The lab tested a new chemical compound.", zh:"實驗室測試了一種新的化合物。" },
      { en:"The factory compound is surrounded by a tall fence.", zh:"這座工廠的場地周圍有一圈高聳的圍籬。" },
      { en:"The bank offers a savings account with compound interest.", zh:"這家銀行提供有複利的儲蓄帳戶。" }
    ]
  },
  {
    id: "w193", english: "concept", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["概念","觀念"] ] }
    ],
    examples: [
      { en:"The marketing team pitched a new concept for the campaign.", zh:"行銷團隊為這次活動提出了一個新的概念。" }
    ]
  },
  {
    id: "w194", english: "concern", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["擔憂","顧慮"] ] },
      { pos: "vt", meaningGroups: [ ["使擔憂","與…有關"] ] }
    ],
    examples: [
      { en:"Employees raised several concerns about the new schedule.", zh:"員工對新的班表提出了幾項擔憂。" },
      { en:"This policy concerns all full-time staff.", zh:"這項政策與所有正職員工有關。" }
    ]
  },
  {
    id: "w195", english: "condition", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["條件","狀況"] ] }
    ],
    examples: [
      { en:"The contract includes several terms and conditions.", zh:"這份合約包含幾項條款與條件。" }
    ]
  },
  {
    id: "w196", english: "conference", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["會議","研討會"] ] }
    ],
    examples: [
      { en:"The annual sales conference will be held in Taipei this year.", zh:"今年的年度銷售會議將在台北舉行。" }
    ]
  },
  {
    id: "w197", english: "confirmation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["確認"] ] }
    ],
    examples: [
      { en:"You will receive a confirmation email once your order ships.", zh:"訂單出貨後，你將會收到一封確認郵件。" }
    ]
  },
  {
    id: "w198", english: "connecting", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["連接的","轉接的"] ] }
    ],
    examples: [
      { en:"We have only forty minutes to catch our connecting flight.", zh:"我們只有四十分鐘的時間趕搭轉機班機。" }
    ]
  },
  {
    id: "w199", english: "consequence", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["後果","結果"] ] }
    ],
    examples: [
      { en:"Missing the deadline could have serious consequences for the team.", zh:"錯過截止期限可能會對團隊造成嚴重的後果。" }
    ]
  },
  {
    id: "w200", english: "consequently", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adv", meaningGroups: [ ["因此","所以"] ] }
    ],
    examples: [
      { en:"The flight was delayed; consequently, the meeting had to be rescheduled.", zh:"班機延誤了，因此會議必須重新安排時間。" }
    ]
  },
  {
    id: "w201", english: "considerably", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adv", meaningGroups: [ ["相當地","頗多地"] ] }
    ],
    examples: [
      { en:"Sales have increased considerably since the new campaign launched.", zh:"自新活動推出以來，銷售額大幅增加。" }
    ]
  },
  {
    id: "w202", english: "construct", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["建造","建構"] ] }
    ],
    examples: [
      { en:"The company plans to construct a new warehouse next year.", zh:"這家公司計畫明年建造一座新倉庫。" }
    ]
  },
  {
    id: "w203", english: "construction", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["建造","施工"] ] }
    ],
    examples: [
      { en:"Construction on the new office building will begin next month.", zh:"新辦公大樓的施工將於下個月開始。" }
    ]
  },
  {
    id: "w204", english: "constructive", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["建設性的"] ] }
    ],
    examples: [
      { en:"Please give constructive feedback during the performance review.", zh:"請在績效考核期間提供建設性的意見。" }
    ]
  },
  {
    id: "w205", english: "consult", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["查詢","請教"] ] },
      { pos: "vi", meaningGroups: [ ["諮詢","商議"] ] }
    ],
    examples: [
      { en:"Please consult the manual before contacting technical support.", zh:"在聯繫技術支援之前，請先查閱手冊。" },
      { en:"She consulted with her supervisor before making the decision.", zh:"她在做決定之前先和主管商量過。" }
    ]
  },
  {
    id: "w206", english: "consultant", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["顧問"] ] }
    ],
    examples: [
      { en:"The firm hired a consultant to improve its supply chain.", zh:"這家公司聘請了一位顧問來改善其供應鏈。" }
    ]
  },
  {
    id: "w207", english: "consumer", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["消費者"] ] }
    ],
    examples: [
      { en:"Consumer demand for eco-friendly products is rising.", zh:"消費者對環保產品的需求正在上升。" }
    ]
  },
  {
    id: "w208", english: "container", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["容器"], ["貨櫃"] ] }
    ],
    examples: [
      { en:"Store the leftovers in an airtight container.", zh:"把剩菜放進密封容器裡保存。" },
      { en:"The goods will be shipped in a single container.", zh:"這些貨物將用一個貨櫃運送。" }
    ]
  },
  {
    id: "w209", english: "content", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["內容"] ] },
      { pos: "adj", meaningGroups: [ ["滿足的","滿意的"] ] }
    ],
    examples: [
      { en:"The editor reviewed the content of the report before publishing it.", zh:"編輯在發布之前審閱了這份報告的內容。" },
      { en:"She seems content with her new role in the department.", zh:"她似乎對自己在部門裡的新職務感到滿意。" }
    ]
  },
  {
    id: "w210", english: "contest", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["比賽","競賽"] ] },
      { pos: "vt", meaningGroups: [ ["對…提出異議","質疑"] ] }
    ],
    examples: [
      { en:"Employees can enter the photo contest until Friday.", zh:"員工可以在星期五之前參加攝影比賽。" },
      { en:"The employee decided to contest the disciplinary decision.", zh:"這位員工決定對這項處分決定提出異議。" }
    ]
  },
  {
    id: "w211", english: "contract", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["合約"] ] },
      { pos: "vt", meaningGroups: [ ["收縮","縮減"] ] }
    ],
    examples: [
      { en:"Both parties signed the contract yesterday.", zh:"雙方昨天簽署了合約。" },
      { en:"The economy contracted for the second straight quarter.", zh:"經濟連續第二個季度出現萎縮。" }
    ]
  },
  {
    id: "w212", english: "contribution", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["貢獻","捐款"] ] }
    ],
    examples: [
      { en:"Her contribution to the project was greatly appreciated.", zh:"她對這個專案的貢獻備受讚賞。" }
    ]
  },
  {
    id: "w213", english: "convenient", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["方便的"] ] }
    ],
    examples: [
      { en:"Is it convenient for you to meet on Thursday afternoon?", zh:"你星期四下午方便開會嗎？" }
    ]
  },
  {
    id: "w214", english: "converse", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["交談","談話"] ] }
    ],
    examples: [
      { en:"The two managers conversed briefly before the meeting began.", zh:"這兩位經理在會議開始前簡短交談了一下。" }
    ]
  },
  {
    id: "w215", english: "convince", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["說服","使確信"] ] }
    ],
    examples: [
      { en:"The salesperson convinced the client to upgrade the package.", zh:"這位銷售人員說服了客戶升級方案。" }
    ]
  },
  {
    id: "w216", english: "corded", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["有線的"] ] }
    ],
    examples: [
      { en:"He prefers a corded mouse because the battery never runs out.", zh:"他偏好使用有線滑鼠，因為不會有電池耗盡的問題。" }
    ]
  },
  {
    id: "w217", english: "correspond", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["符合","相符"], ["通信","聯繫"] ] }
    ],
    examples: [
      { en:"The figures in the report should correspond with the data in the spreadsheet.", zh:"報告中的數字應該要與試算表中的資料相符。" },
      { en:"They have corresponded by email for years.", zh:"他們多年來一直透過電子郵件聯繫。" }
    ]
  },
  {
    id: "w218", english: "costume", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["服裝","戲服"] ] }
    ],
    examples: [
      { en:"Every actor needed a different costume for the play.", zh:"每位演員在這部戲裡都需要不同的戲服。" }
    ]
  },
  {
    id: "w219", english: "cottage", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["小屋","農舍"] ] }
    ],
    examples: [
      { en:"They rented a cottage by the lake for the weekend.", zh:"他們週末租了一間湖邊的小屋。" }
    ]
  },
  {
    id: "w220", english: "count on", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["指望","依賴"] ] }
    ],
    examples: [
      { en:"You can always count on her to meet deadlines.", zh:"你總是可以指望她如期完成工作。" }
    ]
  },
  {
    id: "w221", english: "courageous", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["勇敢的"] ] }
    ],
    examples: [
      { en:"It was a courageous decision to enter a new market during the recession.", zh:"在經濟衰退期間進入新市場是個勇敢的決定。" }
    ]
  },
  {
    id: "w222", english: "cozy", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["舒適的","溫馨的"] ] }
    ],
    examples: [
      { en:"The small café has a cozy atmosphere.", zh:"這家小咖啡館有種溫馨舒適的氛圍。" }
    ]
  },
  {
    id: "w223", english: "creation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["創造","創作品"] ] }
    ],
    examples: [
      { en:"The new logo was the creation of a young designer.", zh:"這個新標誌是一位年輕設計師的創作。" }
    ]
  },
  {
    id: "w224", english: "creative", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["有創意的","創造性的"] ] }
    ],
    examples: [
      { en:"The team came up with a creative solution to cut costs.", zh:"團隊想出了一個有創意的方法來削減成本。" }
    ]
  },
  {
    id: "w225", english: "creativity", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["創造力","創意"] ] }
    ],
    examples: [
      { en:"The workshop is designed to boost employees' creativity.", zh:"這個工作坊旨在提升員工的創造力。" }
    ]
  },
  {
    id: "w226", english: "creature", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["生物","動物"] ] }
    ],
    examples: [
      { en:"Scientists discovered a new species of deep-sea creature.", zh:"科學家發現了一種新的深海生物。" }
    ]
  },
  {
    id: "w227", english: "credit", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["信用","信貸"], ["功勞","讚揚"] ] },
      { pos: "nc", meaningGroups: [ ["學分"] ] }
    ],
    examples: [
      { en:"Customers can pay by credit card or bank transfer.", zh:"顧客可以用信用卡或銀行轉帳付款。" },
      { en:"She deserves credit for turning the project around.", zh:"她讓這個專案扭轉局面，理應獲得讚揚。" },
      { en:"She needs six more credits to graduate.", zh:"她還需要六個學分才能畢業。" }
    ]
  },
  {
    id: "w228", english: "crew", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["全體工作人員","機組人員"] ] }
    ],
    examples: [
      { en:"The flight crew welcomed passengers as they boarded.", zh:"機組人員在乘客登機時歡迎他們。" }
    ]
  },
  {
    id: "w229", english: "crisp", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["脆的","酥脆的"], ["清爽的","乾脆利落的"] ] }
    ],
    examples: [
      { en:"The bread crust was crisp and golden.", zh:"麵包皮又脆又金黃。" },
      { en:"She gave a crisp, confident answer during the interview.", zh:"她在面試中給出了一個乾脆又有自信的回答。" }
    ]
  },
  {
    id: "w230", english: "critic", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["評論家","批評者"] ] }
    ],
    examples: [
      { en:"The restaurant received a glowing review from a well-known food critic.", zh:"這家餐廳獲得一位知名美食評論家的高度好評。" }
    ]
  },
  {
    id: "w231", english: "criticism", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["批評","評論"] ] }
    ],
    examples: [
      { en:"He accepted the criticism and revised his proposal.", zh:"他接受了批評，並修改了他的提案。" }
    ]
  },
  {
    id: "w232", english: "crowd", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["群眾","人群"] ] }
    ],
    examples: [
      { en:"A large crowd gathered outside the store for the sale.", zh:"一大群人聚集在店外等著搶購。" }
    ]
  },
  {
    id: "w233", english: "cucumber", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["黃瓜"] ] }
    ],
    examples: [
      { en:"She sliced a cucumber for the salad.", zh:"她切了一根黃瓜放進沙拉裡。" }
    ]
  },
{
  id: "w234", english: "cuisine", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["菜系","料理"] ] } ],
  examples: [
    { en:"This restaurant is famous for its authentic Italian cuisine.", zh:"這家餐廳以道地的義式料理聞名。" }
  ]
},
{
  id: "w235", english: "cultivate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vt", meaningGroups: [ ["培養","建立"], ["耕種","種植"] ] } ],
  examples: [
    { en:"The company works hard to cultivate strong relationships with its clients.", zh:"公司努力與客戶培養穩固的關係。" },
    { en:"Farmers cultivate rice in this region.", zh:"這個地區的農民種植稻米。" }
  ]
},
{
  id: "w236", english: "cup of tea", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "phr.", meaningGroups: [ ["合意的事物","感興趣的東西"] ] } ],
  examples: [
    { en:"Extreme sports are just not my cup of tea.", zh:"極限運動真的不是我喜歡的類型。" }
  ]
},
{
  id: "w237", english: "curve", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "vi", meaningGroups: [ ["彎曲","轉彎"] ] },
    { pos: "nc", meaningGroups: [ ["曲線","彎道"] ] }
  ],
  examples: [
    { en:"The road curves sharply near the mountain pass.", zh:"這條路在山口附近急劇轉彎。" },
    { en:"The sales chart shows an upward curve this quarter.", zh:"銷售圖表顯示這一季呈上升曲線。" }
  ]
},
{
  id: "w238", english: "custom-made", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["訂製的","定制的"] ] } ],
  examples: [
    { en:"The tailor offers custom-made suits for executives.", zh:"這位裁縫師為主管們提供訂製西裝。" }
  ]
},
{
  id: "w239", english: "daily", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adj", meaningGroups: [ ["每日的","每天的"] ] },
    { pos: "adv", meaningGroups: [ ["每日地","每天"] ] }
  ],
  examples: [
    { en:"Employees must submit a daily report before leaving the office.", zh:"員工必須在下班前提交每日報告。" },
    { en:"The machine is inspected daily to ensure safety.", zh:"這台機器每天都會被檢查以確保安全。" }
  ]
},
{
  id: "w240", english: "dare", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vi", meaningGroups: [ ["敢","膽敢"] ] } ],
  examples: [
    { en:"Few employees dared to question the manager's decision.", zh:"很少員工敢質疑經理的決定。" }
  ]
},
{
  id: "w241", english: "darling", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["最受喜愛的人或事物","寵兒"] ] } ],
  examples: [
    { en:"The startup quickly became the darling of investors.", zh:"這家新創公司很快成為投資人的最愛。" }
  ]
},
{
  id: "w242", english: "dash", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "vi", meaningGroups: [ ["衝","奔跑"] ] },
    { pos: "nc", meaningGroups: [ ["少量","一點點"] ] }
  ],
  examples: [
    { en:"He dashed to the airport to catch his flight.", zh:"他衝去機場趕搭班機。" },
    { en:"Add a dash of humor to your presentation.", zh:"在你的簡報中加一點幽默感。" }
  ]
},
{
  id: "w243", english: "data", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nu", meaningGroups: [ ["資料","數據"] ] } ],
  examples: [
    { en:"The report is based on data collected from customer surveys.", zh:"這份報告是根據客戶調查收集的數據撰寫的。" }
  ]
},
{
  id: "w244", english: "deal", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["交易","協議"] ] },
    { pos: "vi", meaningGroups: [ ["交易","經銷"] ] }
  ],
  examples: [
    { en:"The two companies finally closed the deal after months of negotiation.", zh:"經過數月談判，兩家公司終於完成了這筆交易。" },
    { en:"This supplier deals in industrial equipment.", zh:"這家供應商經銷工業設備。" }
  ]
},
{
  id: "w245", english: "decade", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["十年"] ] } ],
  examples: [
    { en:"The firm has grown steadily over the past decade.", zh:"這家公司在過去十年間穩定成長。" }
  ]
},
{
  id: "w246", english: "decide", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vt", meaningGroups: [ ["決定"] ] } ],
  examples: [
    { en:"The committee decided the winner of the award.", zh:"委員會決定了這個獎項的得主。" }
  ]
},
{
  id: "w247", english: "define", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vt", meaningGroups: [ ["定義","界定","明確說明"] ] } ],
  examples: [
    { en:"The contract clearly defines each party's responsibilities.", zh:"合約明確界定了雙方的責任。" }
  ]
},
{
  id: "w248", english: "definition", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["定義"] ] } ],
  examples: [
    { en:"The manual provides a clear definition of each technical term.", zh:"手冊對每個技術術語都提供了清楚的定義。" }
  ]
},
{
  id: "w249", english: "delay", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "vt", meaningGroups: [ ["使延遲","耽誤"] ] },
    { pos: "nc", meaningGroups: [ ["延遲","延誤"] ] }
  ],
  examples: [
    { en:"Bad weather delayed the shipment by two days.", zh:"惡劣天氣使貨物延誤了兩天。" },
    { en:"Passengers were frustrated by the long delay.", zh:"乘客們對長時間的延誤感到很沮喪。" }
  ]
},
{
  id: "w250", english: "delivery", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["遞送","交貨","送貨"] ] } ],
  examples: [
    { en:"The delivery arrived two days late.", zh:"這批貨物的到貨晚了兩天。" }
  ]
},
{
  id: "w251", english: "demand", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nu", meaningGroups: [ ["需求"] ] },
    { pos: "vt", meaningGroups: [ ["要求"] ] }
  ],
  examples: [
    { en:"Demand for the new product has exceeded expectations.", zh:"這項新產品的需求已超出預期。" },
    { en:"The client demanded a full refund.", zh:"客戶要求全額退款。" }
  ]
},
{
  id: "w252", english: "demonstration", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["示範","展示"], ["示威活動","抗議活動"] ] } ],
  examples: [
    { en:"The sales rep gave a product demonstration to the client.", zh:"業務代表向客戶進行了產品示範。" },
    { en:"Workers organized a demonstration outside the factory.", zh:"工人們在工廠外組織了一場示威活動。" }
  ]
},
{
  id: "w253", english: "dependable", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["可靠的","可信賴的"] ] } ],
  examples: [
    { en:"We need a dependable supplier who can meet tight deadlines.", zh:"我們需要一個能配合緊迫期限的可靠供應商。" }
  ]
},
{
  id: "w254", english: "dependent", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adj", meaningGroups: [ ["依賴的","依附的"] ] },
    { pos: "nc", meaningGroups: [ ["受撫養人","家屬"] ] }
  ],
  examples: [
    { en:"The company's profits are heavily dependent on overseas sales.", zh:"公司的利潤高度依賴海外銷售。" },
    { en:"Employees can add dependents to their health insurance plan.", zh:"員工可以將家屬加入健康保險計劃。" }
  ]
},
{
  id: "w255", english: "depressing", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["令人沮喪的","令人壓抑的"] ] } ],
  examples: [
    { en:"The quarterly sales figures were depressing for the whole team.", zh:"這季的銷售數字讓整個團隊感到沮喪。" }
  ]
},
{
  id: "w256", english: "deserve", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vt", meaningGroups: [ ["應得","值得"] ] } ],
  examples: [
    { en:"She deserves a promotion after her outstanding performance.", zh:"她出色的表現讓她應得升遷。" }
  ]
},
{
  id: "w257", english: "designer", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["設計師"] ] } ],
  examples: [
    { en:"The designer presented three new logo concepts.", zh:"設計師提出了三個新的標誌概念。" }
  ]
},
{
  id: "w258", english: "despite", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "prep", meaningGroups: [ ["儘管","不管"] ] } ],
  examples: [
    { en:"Despite the budget cuts, the project was completed on time.", zh:"儘管預算被削減，這個專案仍如期完成。" }
  ]
},
{
  id: "w259", english: "determine", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vt", meaningGroups: [ ["決定","確定","判定"] ] } ],
  examples: [
    { en:"The committee will determine the winner of the contract bid.", zh:"委員會將決定合約標案的贏家。" }
  ]
},
{
  id: "w260", english: "developed", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["已開發的","發達的"] ] } ],
  examples: [
    { en:"The firm plans to expand into more developed markets.", zh:"這家公司計劃拓展到更多已開發市場。" }
  ]
},
{
  id: "w261", english: "development", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nu", meaningGroups: [ ["發展","開發"] ] } ],
  examples: [
    { en:"The company invests heavily in product development.", zh:"這家公司在產品開發上投入大量資金。" }
  ]
},
{
  id: "w262", english: "device", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["裝置","設備"] ] } ],
  examples: [
    { en:"This device measures the temperature of the machinery.", zh:"這個裝置用來測量機械的溫度。" }
  ]
},
{
  id: "w263", english: "devote", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vt", meaningGroups: [ ["投入","奉獻"] ] } ],
  examples: [
    { en:"The team devoted extra hours to finishing the report on time.", zh:"團隊投入額外的時間以如期完成報告。" }
  ]
},
{
  id: "w264", english: "digital", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["數位的"] ] } ],
  examples: [
    { en:"The company is shifting all its records to a digital format.", zh:"這家公司正將所有記錄轉為數位格式。" }
  ]
},
{
  id: "w265", english: "diligence", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nu", meaningGroups: [ ["勤奮","勤勉"] ] } ],
  examples: [
    { en:"Her diligence and attention to detail impressed the manager.", zh:"她的勤奮與注重細節讓經理印象深刻。" }
  ]
},
{
  id: "w266", english: "direction", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nu", meaningGroups: [ ["方向","指引"] ] } ],
  examples: [
    { en:"The new manager gave clear direction to the sales team.", zh:"新任經理給銷售團隊明確的指引。" }
  ]
},
{
  id: "w267", english: "director", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["主管","董事","總監"], ["導演"] ] } ],
  examples: [
    { en:"She was recently promoted to marketing director.", zh:"她最近被升為行銷總監。" },
    { en:"The award-winning director attended the film's premiere.", zh:"這位獲獎導演出席了電影首映會。" }
  ]
},
{
  id: "w268", english: "disadvantaged", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["處於不利地位的","貧困的"] ] } ],
  examples: [
    { en:"The program provides training for disadvantaged job seekers.", zh:"這個計畫為處於不利地位的求職者提供培訓。" }
  ]
},
{
  id: "w269", english: "disappointing", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["令人失望的"] ] } ],
  examples: [
    { en:"The quarterly earnings were disappointing to shareholders.", zh:"這一季的獲利讓股東感到失望。" }
  ]
},
{
  id: "w270", english: "disappointment", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["失望"] ] } ],
  examples: [
    { en:"The delayed launch was a major disappointment for the team.", zh:"延遲上市對團隊來說是一大失望。" }
  ]
},
{
  id: "w271", english: "disaster", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["災難"] ] } ],
  examples: [
    { en:"The company set up a fund to help victims of the natural disaster.", zh:"這家公司設立了基金以幫助天災的受害者。" }
  ]
},
{
  id: "w272", english: "disconnected", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["斷開的","不連貫的"] ] } ],
  examples: [
    { en:"The video call was disconnected due to a network problem.", zh:"視訊通話因網路問題而斷線。" }
  ]
},
{
  id: "w273", english: "discourage", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vt", meaningGroups: [ ["使沮喪","勸阻"] ] } ],
  examples: [
    { en:"High shipping costs discourage customers from ordering online.", zh:"高昂的運費使顧客不願線上訂購。" }
  ]
},
{
  id: "w274", english: "disguise", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "vt", meaningGroups: [ ["偽裝","掩飾"] ] },
    { pos: "nc", meaningGroups: [ ["偽裝物","偽裝"] ] }
  ],
  examples: [
    { en:"He tried to disguise his lack of experience during the interview.", zh:"他在面試中試圖掩飾自己經驗不足。" },
    { en:"The thief wore a disguise to avoid being recognized.", zh:"這名竊賊戴著偽裝以避免被認出。" }
  ]
},
{
  id: "w275", english: "disk", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["磁碟","光碟"] ] } ],
  examples: [
    { en:"Please back up the files onto an external disk.", zh:"請將檔案備份到外接磁碟上。" }
  ]
},
{
  id: "w276", english: "dispute", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["爭議","糾紛"] ] },
    { pos: "vt", meaningGroups: [ ["對…提出異議","質疑"] ] }
  ],
  examples: [
    { en:"The two companies are in a legal dispute over the contract.", zh:"這兩家公司因合約發生法律糾紛。" },
    { en:"The customer disputed the charge on his invoice.", zh:"這名客戶對他發票上的收費提出異議。" }
  ]
},
{
  id: "w277", english: "dissatisfaction", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nu", meaningGroups: [ ["不滿"] ] } ],
  examples: [
    { en:"Customer dissatisfaction rose after the price increase.", zh:"漲價後顧客的不滿情緒上升。" }
  ]
},
{
  id: "w278", english: "distance", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["距離"] ] } ],
  examples: [
    { en:"The warehouse is within walking distance of the office.", zh:"這個倉庫距離辦公室步行可達。" }
  ]
},
{
  id: "w279", english: "distant", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["遙遠的","疏遠的"] ] } ],
  examples: [
    { en:"The firm is expanding into distant overseas markets.", zh:"這家公司正在拓展到遙遠的海外市場。" }
  ]
},
{
  id: "w280", english: "distinctive", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["獨特的","有特色的"] ] } ],
  examples: [
    { en:"The brand is known for its distinctive packaging.", zh:"這個品牌以其獨特的包裝聞名。" }
  ]
},
{
  id: "w281", english: "distinguished", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["傑出的","卓越的"] ] } ],
  examples: [
    { en:"The company hired a distinguished economist as a consultant.", zh:"這家公司聘請了一位傑出的經濟學家擔任顧問。" }
  ]
},
{
  id: "w282", english: "distraction", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["分心的事物","干擾"] ] } ],
  examples: [
    { en:"Constant emails are a major distraction at work.", zh:"不斷收到的電子郵件是工作上很大的干擾。" }
  ]
},
{
  id: "w283", english: "distribute", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vt", meaningGroups: [ ["分配","分發","經銷"] ] } ],
  examples: [
    { en:"The company distributes its products to over thirty countries.", zh:"這家公司將其產品經銷到三十多個國家。" }
  ]
},
{
  id: "w284", english: "document", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["文件"] ] },
    { pos: "vt", meaningGroups: [ ["記錄","記載"] ] }
  ],
  examples: [
    { en:"Please attach the required document to your application.", zh:"請在申請書中附上所需的文件。" },
    { en:"The inspector documented every safety violation.", zh:"檢查員記錄了每一項安全違規事項。" }
  ]
},
{
  id: "w285", english: "domestic", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["國內的","家庭的"] ] } ],
  examples: [
    { en:"Domestic sales grew faster than international sales this year.", zh:"今年國內銷售的成長比國際銷售更快。" }
  ]
},
{
  id: "w286", english: "download", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vt", meaningGroups: [ ["下載"] ] } ],
  examples: [
    { en:"You can download the invoice from our website.", zh:"你可以從我們的網站下載發票。" }
  ]
},
{
  id: "w287", english: "doze", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vi", meaningGroups: [ ["打瞌睡"] ] } ],
  examples: [
    { en:"He dozed off during the long meeting.", zh:"他在冗長的會議中打起了瞌睡。" }
  ]
},
{
  id: "w288", english: "drain", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "vt", meaningGroups: [ ["耗盡","使疲憊"] ] },
    { pos: "nc", meaningGroups: [ ["排水管","下水道"] ] }
  ],
  examples: [
    { en:"The lengthy project drained the team's energy.", zh:"這個冗長的專案耗盡了團隊的精力。" },
    { en:"A blocked drain caused flooding in the basement.", zh:"堵塞的排水管導致地下室積水。" }
  ]
},
{
  id: "w289", english: "dramatically", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adv", meaningGroups: [ ["顯著地","劇烈地"] ] } ],
  examples: [
    { en:"Sales increased dramatically after the marketing campaign.", zh:"行銷活動後，銷售額顯著增加。" }
  ]
},
{
  id: "w290", english: "dreadful", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["可怕的","糟糕的"] ] } ],
  examples: [
    { en:"The customer service she received was dreadful.", zh:"她所受到的客戶服務糟糕透頂。" }
  ]
},
{
  id: "w291", english: "drift", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vi", meaningGroups: [ ["漂流","漂移","偏離"] ] } ],
  examples: [
    { en:"The conversation drifted away from the main agenda.", zh:"對話漸漸偏離了主要議題。" }
  ]
},
{
  id: "w292", english: "drive", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "vt", meaningGroups: [ ["駕駛"], ["推動","促使"] ] },
    { pos: "nc", meaningGroups: [ ["衝勁","幹勁","積極性"] ] }
  ],
  examples: [
    { en:"He drives to the office every day.", zh:"他每天開車去上班。" },
    { en:"New pricing strategies helped drive sales growth.", zh:"新的定價策略有助於推動銷售成長。" },
    { en:"She has the drive to succeed in this competitive industry.", zh:"她有在這個競爭激烈的產業中成功的幹勁。" }
  ]
},
{
  id: "w293", english: "dynamic", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adj", meaningGroups: [ ["動態的","有活力的"] ] },
    { pos: "nc", meaningGroups: [ ["互動關係","運作模式"] ] }
  ],
  examples: [
    { en:"The company operates in a dynamic and competitive market.", zh:"這家公司在一個充滿活力且競爭激烈的市場中運作。" },
    { en:"The new hire changed the dynamic of the whole team.", zh:"這位新員工改變了整個團隊的互動關係。" }
  ]
},
{
  id: "w294", english: "eager", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["渴望的","急切的"] ] } ],
  examples: [
    { en:"The intern is eager to learn new skills.", zh:"這位實習生渴望學習新技能。" }
  ]
},
{
  id: "w295", english: "earnest", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["認真的","誠摯的"] ] } ],
  examples: [
    { en:"He made an earnest effort to resolve the dispute.", zh:"他做出了誠摯的努力來解決這場糾紛。" }
  ]
},
{
  id: "w296", english: "ease", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "vt", meaningGroups: [ ["減輕","緩和"] ] },
    { pos: "nu", meaningGroups: [ ["輕鬆","容易"] ] }
  ],
  examples: [
    { en:"The new software eases the burden of manual data entry.", zh:"這套新軟體減輕了手動輸入資料的負擔。" },
    { en:"She handled the client's complaint with ease.", zh:"她輕鬆地處理了客戶的抱怨。" }
  ]
},
{
  id: "w297", english: "edge", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["邊緣"], ["優勢"] ] } ],
  examples: [
    { en:"He stood at the edge of the platform.", zh:"他站在平台的邊緣。" },
    { en:"Innovation gives the company a competitive edge.", zh:"創新給了這家公司競爭優勢。" }
  ]
},
{
  id: "w298", english: "edible", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["可食用的"] ] } ],
  examples: [
    { en:"All the ingredients used in the product are edible.", zh:"這項產品所使用的所有原料都是可食用的。" }
  ]
},
{
  id: "w299", english: "edition", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["版本","版次"] ] } ],
  examples: [
    { en:"The magazine released a special edition for its anniversary.", zh:"這份雜誌為週年紀念發行了特刊。" }
  ]
},
{
  id: "w300", english: "education", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nu", meaningGroups: [ ["教育"] ] } ],
  examples: [
    { en:"The company offers continuing education programs for employees.", zh:"這家公司為員工提供持續教育課程。" }
  ]
},
{
  id: "w301", english: "effect", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["效果","影響"] ] } ],
  examples: [
    { en:"The new policy had a positive effect on employee morale.", zh:"這項新政策對員工士氣產生了正面的影響。" }
  ]
},
{
  id: "w302", english: "effective", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["有效的","有效果的"], ["生效的"] ] } ],
  examples: [
    { en:"This is an effective way to reduce production costs.", zh:"這是降低生產成本的有效方法。" },
    { en:"The new policy is effective from next Monday.", zh:"這項新政策從下週一開始生效。" }
  ]
},
{
  id: "w303", english: "effort", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nu", meaningGroups: [ ["努力","費力"] ] } ],
  examples: [
    { en:"The team put a lot of effort into the presentation.", zh:"這個團隊在簡報上投入了很多努力。" }
  ]
},
{
  id: "w304", english: "electrician", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["電工","電匠"] ] } ],
  examples: [
    { en:"The company hired an electrician to fix the wiring.", zh:"這家公司雇用了一名電工來修理電路。" }
  ]
},
{
  id: "w305", english: "element", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["元素","要素"] ] } ],
  examples: [
    { en:"Teamwork is an essential element of this project's success.", zh:"團隊合作是這個專案成功的必要要素。" }
  ]
},
{
  id: "w306", english: "elementary", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["基本的","初級的"] ] } ],
  examples: [
    { en:"The training covers only elementary accounting skills.", zh:"這項培訓只涵蓋基本的會計技能。" }
  ]
},
{
  id: "w307", english: "emerge", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vi", meaningGroups: [ ["出現","浮現"] ] } ],
  examples: [
    { en:"New competitors have emerged in the smartphone market.", zh:"智慧型手機市場出現了新的競爭者。" }
  ]
},
{
  id: "w308", english: "emergency", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["緊急情況"] ] } ],
  examples: [
    { en:"The office has a plan in place for handling emergencies.", zh:"辦公室已備有處理緊急情況的計畫。" }
  ]
},
{
  id: "w309", english: "emerging", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["新興的"] ] } ],
  examples: [
    { en:"The company is expanding into emerging markets in Southeast Asia.", zh:"這家公司正拓展至東南亞的新興市場。" }
  ]
},
{
  id: "w310", english: "emotional", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["情緒上的","情感的"] ] } ],
  examples: [
    { en:"Managers should provide emotional support during stressful periods.", zh:"主管應在壓力大的時期提供情感上的支持。" }
  ]
},
{
  id: "w311", english: "employ", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vt", meaningGroups: [ ["雇用","聘用"], ["運用","使用"] ] } ],
  examples: [
    { en:"The factory employs over five hundred workers.", zh:"這家工廠雇用了超過五百名員工。" },
    { en:"The team employed a new strategy to boost sales.", zh:"這個團隊運用了一套新策略來提升銷售額。" }
  ]
},
{
  id: "w312", english: "empty", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adj", meaningGroups: [ ["空的"] ] },
    { pos: "vt", meaningGroups: [ ["倒空","清空"] ] }
  ],
  examples: [
    { en:"The conference room was empty when I arrived.", zh:"我到達時，會議室是空的。" },
    { en:"Please empty the recycling bin before you leave.", zh:"離開前請把回收桶清空。" }
  ]
},
{
  id: "w313", english: "enable", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vt", meaningGroups: [ ["使能夠","促成"] ] } ],
  examples: [
    { en:"This software enables employees to work remotely.", zh:"這套軟體讓員工能夠遠端工作。" }
  ]
},
{
  id: "w314", english: "encounter", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vt", meaningGroups: [ ["遭遇","遇到"] ] } ],
  examples: [
    { en:"The team encountered several problems during the product launch.", zh:"這個團隊在產品上市期間遇到了幾個問題。" }
  ]
},
{
  id: "w315", english: "encourage", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vt", meaningGroups: [ ["鼓勵"] ] } ],
  examples: [
    { en:"The manager encourages employees to share their ideas.", zh:"經理鼓勵員工分享自己的想法。" }
  ]
},
{
  id: "w316", english: "energetic", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["有活力的","精力充沛的"] ] } ],
  examples: [
    { en:"The new intern is energetic and eager to contribute.", zh:"這位新實習生充滿活力且渴望貢獻。" }
  ]
},
{
  id: "w317", english: "enforcement", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nu", meaningGroups: [ ["執行","強制執行"] ] } ],
  examples: [
    { en:"Strict enforcement of safety rules reduced workplace accidents.", zh:"嚴格執行安全規範減少了職場意外。" }
  ]
},
{
  id: "w318", english: "engaged", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["訂婚的"], ["忙於…的","從事於…的"] ] } ],
  examples: [
    { en:"She got engaged to her longtime boyfriend last month.", zh:"她上個月和交往多年的男友訂婚了。" },
    { en:"The staff were fully engaged in preparing for the audit.", zh:"員工們全力投入準備這場稽核。" }
  ]
},
{
  id: "w319", english: "engineer", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["工程師"] ] },
    { pos: "vt", meaningGroups: [ ["設計","策劃"] ] }
  ],
  examples: [
    { en:"The engineer inspected the machine before installation.", zh:"工程師在安裝前檢查了這台機器。" },
    { en:"The executives engineered a merger to expand market share.", zh:"高階主管策劃了一場合併以擴大市場佔有率。" }
  ]
},
{
  id: "w320", english: "enjoyable", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["令人愉快的","有趣的"] ] } ],
  examples: [
    { en:"The workshop was both informative and enjoyable.", zh:"這場工作坊既有內容又令人愉快。" }
  ]
},
{
  id: "w321", english: "enormous", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["巨大的"] ] } ],
  examples: [
    { en:"The merger created an enormous multinational corporation.", zh:"這次合併創造了一個龐大的跨國企業。" }
  ]
},
{
  id: "w322", english: "entertain", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vt", meaningGroups: [ ["招待","款待"], ["考慮"] ] } ],
  examples: [
    { en:"The company entertained several important clients last night.", zh:"這家公司昨晚招待了幾位重要客戶。" },
    { en:"The board is willing to entertain a lower offer.", zh:"董事會願意考慮一個較低的出價。" }
  ]
},
{
  id: "w323", english: "entertainment", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nu", meaningGroups: [ ["娛樂"] ] } ],
  examples: [
    { en:"The budget includes a small amount for client entertainment.", zh:"預算中包含一小筆用於招待客戶的娛樂費用。" }
  ]
},
{
  id: "w324", english: "entrance", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["入口"] ] } ],
  examples: [
    { en:"Visitors must sign in at the main entrance.", zh:"訪客必須在主要入口處登記。" }
  ]
},
{
  id: "w325", english: "environmental", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["環境的"] ] } ],
  examples: [
    { en:"The factory must comply with strict environmental regulations.", zh:"這家工廠必須遵守嚴格的環境法規。" }
  ]
},
{
  id: "w326", english: "equip", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vt", meaningGroups: [ ["裝備","配備"] ] } ],
  examples: [
    { en:"The training program equips employees with practical skills.", zh:"這項培訓計畫讓員工具備實用技能。" }
  ]
},
{
  id: "w327", english: "essential", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adj", meaningGroups: [ ["必要的","不可或缺的"] ] },
    { pos: "nc", meaningGroups: [ ["必需品","基本要素"] ] }
  ],
  examples: [
    { en:"Clear communication is essential for successful teamwork.", zh:"清楚的溝通對於成功的團隊合作是不可或缺的。" },
    { en:"The kit contains all the essentials for a new employee.", zh:"這個工具包包含新員工所需的所有必需品。" }
  ]
},
{
  id: "w328", english: "evaluate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vt", meaningGroups: [ ["評估","評價"] ] } ],
  examples: [
    { en:"Managers evaluate employee performance every six months.", zh:"經理每六個月評估員工的表現。" }
  ]
},
{
  id: "w329", english: "event", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["事件","活動"] ] } ],
  examples: [
    { en:"The company sponsored a charity event last weekend.", zh:"這家公司上週末贊助了一場慈善活動。" }
  ]
},
{
  id: "w330", english: "eventually", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adv", meaningGroups: [ ["最終","終於"] ] } ],
  examples: [
    { en:"The negotiations were difficult, but the two sides eventually reached an agreement.", zh:"談判過程艱難，但雙方最終達成了協議。" }
  ]
},
{
  id: "w331", english: "everything in between", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "phr.", meaningGroups: [ ["介於兩者之間的一切","其他種種"] ] } ],
  examples: [
    { en:"The store sells electronics, furniture, and everything in between.", zh:"這家店販售電子產品、家具，以及介於兩者之間的各種商品。" }
  ]
},
{
  id: "w332", english: "evident", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["明顯的","顯而易見的"] ] } ],
  examples: [
    { en:"It was evident that the strategy was not working.", zh:"很明顯這項策略並未奏效。" }
  ]
},
{
  id: "w333", english: "exception", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["例外"] ] } ],
  examples: [
    { en:"The company makes no exceptions to its return policy.", zh:"這家公司的退貨政策沒有任何例外。" }
  ]
},
{
  id: "w334", english: "exchange", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "vt", meaningGroups: [ ["交換"] ] },
    { pos: "nc", meaningGroups: [ ["交易所"] ] }
  ],
  examples: [
    { en:"The two managers exchanged business cards after the meeting.", zh:"兩位經理在會後交換了名片。" },
    { en:"The company's shares are listed on the stock exchange.", zh:"這家公司的股票在證券交易所上市。" }
  ]
},
{
  id: "w335", english: "exclusive", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["獨家的","專屬的"] ] } ],
  examples: [
    { en:"The magazine obtained an exclusive interview with the CEO.", zh:"這家雜誌獲得了與執行長的獨家專訪。" }
  ]
},
{
  id: "w336", english: "exhibit", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "vt", meaningGroups: [ ["展示","展出"] ] },
    { pos: "nc", meaningGroups: [ ["展品","陳列品"] ] }
  ],
  examples: [
    { en:"The company will exhibit its latest products at the trade show.", zh:"這家公司將在貿易展中展示其最新產品。" },
    { en:"The museum added a fascinating new exhibit on ancient Egypt.", zh:"博物館新增了一項關於古埃及的精彩展品。" }
  ]
},
{
  id: "w337", english: "exhibition", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["展覽","展覽會"] ] } ],
  examples: [
    { en:"The trade exhibition attracted buyers from around the world.", zh:"這場貿易展覽吸引了來自世界各地的買家。" }
  ]
},
{
  id: "w338", english: "existence", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nu", meaningGroups: [ ["存在"] ] } ],
  examples: [
    { en:"The startup has been in existence for only two years.", zh:"這家新創公司成立至今才兩年。" }
  ]
},
{
  id: "w339", english: "exit", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["出口"] ] },
    { pos: "vt", meaningGroups: [ ["退出","離開"] ] }
  ],
  examples: [
    { en:"The emergency exit is located at the back of the building.", zh:"緊急出口位於大樓後方。" },
    { en:"The investor decided to exit the market before the downturn.", zh:"這位投資人決定在市場下跌前退出。" }
  ]
},
{
  id: "w340", english: "expansion", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nu", meaningGroups: [ ["擴張","擴展"] ] } ],
  examples: [
    { en:"The company announced plans for overseas expansion.", zh:"這家公司宣布了海外擴張的計畫。" }
  ]
},
{
  id: "w341", english: "expectation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["期望"] ] } ],
  examples: [
    { en:"The product exceeded customers' expectations.", zh:"這項產品超出了顧客的期望。" }
  ]
},
{
  id: "w342", english: "experiment", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["實驗"] ] },
    { pos: "vi", meaningGroups: [ ["做實驗","嘗試"] ] }
  ],
  examples: [
    { en:"The lab conducted an experiment to test the new formula.", zh:"這間實驗室進行了一項實驗來測試新配方。" },
    { en:"Scientists experimented with different formulas to improve durability.", zh:"科學家嘗試了不同的配方以提升耐用度。" }
  ]
},
{
  id: "w343", english: "explore", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vt", meaningGroups: [ ["探索","探討"] ] } ],
  examples: [
    { en:"The team will explore new options for reducing costs.", zh:"這個團隊將探討降低成本的新方案。" }
  ]
},
{
  id: "w344", english: "exposure", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nu", meaningGroups: [ ["暴露","曝露"], ["曝光度","知名度"] ] } ],
  examples: [
    { en:"Workers must limit their exposure to hazardous chemicals.", zh:"工人必須限制自己接觸有害化學物質的時間。" },
    { en:"The sponsorship gave the brand valuable media exposure.", zh:"這次贊助為品牌帶來了寶貴的媒體曝光度。" }
  ]
},
{
  id: "w345", english: "expression", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["表達","表情","用語"] ] } ],
  examples: [
    { en:"She used a common business expression in her email.", zh:"她在電子郵件中使用了一個常見的商業用語。" }
  ]
},
{
  id: "w346", english: "extend", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vt", meaningGroups: [ ["延伸","延長"], ["給予","致以"] ] } ],
  examples: [
    { en:"The landlord agreed to extend the lease for another year.", zh:"房東同意將租約再延長一年。" },
    { en:"The company extended an invitation to all major clients.", zh:"這家公司向所有主要客戶發出了邀請。" }
  ]
},
{
  id: "w347", english: "extraordinary", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["非凡的","特別的"] ] } ],
  examples: [
    { en:"She showed extraordinary leadership during the crisis.", zh:"她在這場危機中展現了非凡的領導能力。" }
  ]
},
{
  id: "w348", english: "extremely", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adv", meaningGroups: [ ["非常地","極其"] ] } ],
  examples: [
    { en:"The negotiations were extremely difficult.", zh:"這場談判極其困難。" }
  ]
},
{
  id: "w349", english: "facial", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["臉部的"] ] } ],
  examples: [
    { en:"The security system uses facial recognition to grant access.", zh:"這個安全系統使用臉部辨識來授予進入權限。" }
  ]
},
{
  id: "w350", english: "fail", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vi", meaningGroups: [ ["失敗","未能"] ] } ],
  examples: [
    { en:"The product failed to meet the safety standards.", zh:"這項產品未能符合安全標準。" }
  ]
},
{
  id: "w351", english: "fair", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adj", meaningGroups: [ ["公平的","公正的"] ] },
    { pos: "nc", meaningGroups: [ ["展覽會","博覽會"] ] }
  ],
  examples: [
    { en:"The manager made sure the promotion process was fair.", zh:"經理確保了升遷流程的公平性。" },
    { en:"The company set up a booth at the trade fair.", zh:"這家公司在貿易博覽會上設立了攤位。" }
  ]
},
{
  id: "w352", english: "fame", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nu", meaningGroups: [ ["名聲","名譽"] ] } ],
  examples: [
    { en:"The brand gained fame after the celebrity endorsement.", zh:"這個品牌因名人代言而聲名大噪。" }
  ]
},
{
  id: "w353", english: "fancy", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adj", meaningGroups: [ ["高級的","精美的"] ] },
    { pos: "vt", meaningGroups: [ ["想要","喜歡"] ] }
  ],
  examples: [
    { en:"The client took us to a fancy restaurant for dinner.", zh:"客戶帶我們去一家高級餐廳吃晚餐。" },
    { en:"Do you fancy joining us for the conference next week?", zh:"你想不想跟我們一起參加下週的研討會？" }
  ]
},
{
  id: "w354", english: "fantastic", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["極好的","了不起的"] ] } ],
  examples: [
    { en:"The team did a fantastic job on the annual report.", zh:"這個團隊在年度報告上做得非常出色。" }
  ]
},
{
  id: "w355", english: "faraway", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["遙遠的"] ] } ],
  examples: [
    { en:"The company shipped the equipment to a faraway branch office.", zh:"這家公司把設備運送到一個遙遠的分公司。" }
  ]
},
{
  id: "w356", english: "fare", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["票價"] ] },
    { pos: "vi", meaningGroups: [ ["進展","表現"] ] }
  ],
  examples: [
    { en:"The train fare has increased by ten percent this year.", zh:"今年火車票價上漲了百分之十。" },
    { en:"How did the company fare during the economic downturn?", zh:"這家公司在經濟低迷期間表現如何？" }
  ]
},
{
  id: "w357", english: "fear", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nu", meaningGroups: [ ["恐懼","害怕"] ] },
    { pos: "vt", meaningGroups: [ ["害怕","畏懼"] ] }
  ],
  examples: [
    { en:"Fear of failure should not stop you from taking risks.", zh:"對失敗的恐懼不應該阻止你去冒險。" },
    { en:"Employees fear losing their jobs during the restructuring.", zh:"員工們害怕在重組過程中失去工作。" }
  ]
},
{
    id: "w358", english: "feast", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["盛宴","宴會"] ] },
      { pos: "vi", meaningGroups: [ ["大吃大喝","飽餐一頓"] ] }
    ],
    examples: [
      { en:"The company held a feast to celebrate the successful merger.", zh:"公司舉辦了一場盛宴來慶祝合併案的成功。" },
      { en:"They feasted on seafood after closing the deal.", zh:"他們在完成交易後大吃了一頓海鮮以示慶祝。" }
    ]
  },
  {
    id: "w359", english: "feel at home", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["感到自在","賓至如歸"] ] }
    ],
    examples: [
      { en:"The staff did their best to make every guest feel at home.", zh:"員工盡力讓每位客人都感到賓至如歸。" }
    ]
  },
  {
    id: "w360", english: "female", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["女性的","雌性的"] ] },
      { pos: "nc", meaningGroups: [ ["女性"] ] }
    ],
    examples: [
      { en:"The company is hiring more female engineers this year.", zh:"公司今年招募了更多女性工程師。" },
      { en:"Females make up over half of the management team.", zh:"女性佔管理團隊的一半以上。" }
    ]
  },
  {
    id: "w361", english: "festival", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["節日","慶典"] ] }
    ],
    examples: [
      { en:"The town holds an annual food festival every autumn.", zh:"這個小鎮每年秋天都會舉辦美食節。" }
    ]
  },
  {
    id: "w362", english: "fierce", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["激烈的","猛烈的"] ] }
    ],
    examples: [
      { en:"Competition in the smartphone market has become fierce.", zh:"智慧型手機市場的競爭已變得非常激烈。" }
    ]
  },
  {
    id: "w363", english: "financial", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["財務的","金融的"] ] }
    ],
    examples: [
      { en:"The firm hired a consultant to review its financial statements.", zh:"該公司聘請顧問來審查其財務報表。" }
    ]
  },
  {
    id: "w364", english: "fine", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["良好的","不錯的"], ["精細的","細微的"] ] },
      { pos: "nc", meaningGroups: [ ["罰款"] ] },
      { pos: "vt", meaningGroups: [ ["處以罰款"] ] }
    ],
    examples: [
      { en:"The new equipment has been working fine since the repair.", zh:"新設備維修後運作良好。" },
      { en:"The company received a hefty fine for violating safety regulations.", zh:"該公司因違反安全規定而收到高額罰款。" },
      { en:"The city will fine drivers who park illegally.", zh:"該市將對違規停車的駕駛人開罰。" }
    ]
  },
  {
    id: "w365", english: "firework", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["煙火"] ] }
    ],
    examples: [
      { en:"Fireworks lit up the sky during the New Year celebration.", zh:"跨年慶祝活動時，煙火點亮了天空。" }
    ]
  },
  {
    id: "w366", english: "flame", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["火焰"] ] }
    ],
    examples: [
      { en:"The candle's flame flickered in the breeze.", zh:"蠟燭的火焰在微風中搖曳。" }
    ]
  },
  {
    id: "w367", english: "flat", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["平坦的","扁平的"] ] },
      { pos: "nc", meaningGroups: [ ["公寓（英式用法）"] ] }
    ],
    examples: [
      { en:"Make sure the surface is flat before installing the equipment.", zh:"安裝設備前請確保表面平坦。" },
      { en:"She rented a flat near the city center.", zh:"她在市中心附近租了一間公寓。" }
    ]
  },
  {
    id: "w368", english: "flavor", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["風味","口味"] ] },
      { pos: "vt", meaningGroups: [ ["為…調味"] ] }
    ],
    examples: [
      { en:"This restaurant is known for its unique flavors.", zh:"這家餐廳以其獨特的風味聞名。" },
      { en:"The chef flavored the soup with fresh herbs.", zh:"主廚用新鮮香草為湯調味。" }
    ]
  },
  {
    id: "w369", english: "float", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["漂浮"] ] },
      { pos: "vt", meaningGroups: [ ["使（股票）上市","發行"] ] }
    ],
    examples: [
      { en:"The boxes floated on the water after the flood.", zh:"洪水過後，這些箱子漂浮在水面上。" },
      { en:"The company plans to float its shares on the stock exchange next year.", zh:"該公司計劃明年將股票在證券交易所上市。" }
    ]
  },
  {
    id: "w371", english: "fluent", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["流利的","精通的"] ] }
    ],
    examples: [
      { en:"Applicants must be fluent in both English and Mandarin.", zh:"應徵者必須精通英語和中文。" }
    ]
  },
  {
    id: "w372", english: "flush", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["臉紅"] ] },
      { pos: "vt", meaningGroups: [ ["沖洗（馬桶等）"] ] }
    ],
    examples: [
      { en:"She flushed with embarrassment after making the mistake.", zh:"她犯錯之後因尷尬而臉紅。" },
      { en:"Please remember to flush the toilet after use.", zh:"使用後請記得沖馬桶。" }
    ]
  },
  {
    id: "w373", english: "flying saucer", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["飛碟"] ] }
    ],
    examples: [
      { en:"Witnesses claimed they saw a flying saucer above the factory.", zh:"目擊者聲稱他們在工廠上方看到一個飛碟。" }
    ]
  },
  {
    id: "w374", english: "follower", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["追隨者","跟隨者","粉絲"] ] }
    ],
    examples: [
      { en:"The leader inspired many loyal followers within the company.", zh:"這位領導者在公司內激勵了許多忠實的追隨者。" },
      { en:"The brand gained thousands of followers on social media.", zh:"該品牌在社群媒體上獲得了數千名粉絲。" }
    ]
  },
  {
    id: "w375", english: "following", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["接下來的","下列的"] ] },
      { pos: "prep", meaningGroups: [ ["在…之後"] ] }
    ],
    examples: [
      { en:"Please complete the following form before your interview.", zh:"請在面試前填寫下列表格。" },
      { en:"Following the merger, the two companies combined their sales teams.", zh:"合併之後，這兩家公司整合了各自的銷售團隊。" }
    ]
  },
  {
    id: "w376", english: "forbidden", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["被禁止的"] ] }
    ],
    examples: [
      { en:"Smoking is forbidden inside the warehouse.", zh:"倉庫內禁止吸菸。" }
    ]
  },
  {
    id: "w377", english: "force", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["力量","武力"] ] },
      { pos: "vt", meaningGroups: [ ["迫使","強迫"] ] }
    ],
    examples: [
      { en:"The storm hit the coast with tremendous force.", zh:"這場風暴以驚人的力量襲擊了海岸。" },
      { en:"The budget cuts forced the department to lay off several employees.", zh:"預算削減迫使該部門裁掉了幾名員工。" }
    ]
  },
  {
    id: "w378", english: "formula", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["公式"], ["配方"] ] }
    ],
    examples: [
      { en:"Analysts use a specific formula to calculate the company's growth rate.", zh:"分析師使用特定公式來計算公司的成長率。" },
      { en:"The recipe's formula has remained unchanged for decades.", zh:"這個配方數十年來都沒有改變過。" }
    ]
  },
  {
    id: "w379", english: "forth", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adv", meaningGroups: [ ["向前","往前"] ] }
    ],
    examples: [
      { en:"The two sides went back and forth for several weeks during the negotiation.", zh:"雙方在談判過程中來回討論了好幾週。" }
    ]
  },
  {
    id: "w380", english: "fortunate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["幸運的"] ] }
    ],
    examples: [
      { en:"We are fortunate to have such a talented team.", zh:"我們很幸運能擁有這麼優秀的團隊。" }
    ]
  },
  {
    id: "w381", english: "forward", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adv", meaningGroups: [ ["向前"] ] },
      { pos: "vt", meaningGroups: [ ["轉寄","轉交"] ] }
    ],
    examples: [
      { en:"The project will move forward as originally scheduled.", zh:"這項專案將依照原訂排程繼續進行。" },
      { en:"Could you forward this email to the finance department?", zh:"你可以把這封電子郵件轉寄給財務部門嗎？" }
    ]
  },
  {
    id: "w382", english: "found", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["創立","建立"] ] }
    ],
    examples: [
      { en:"She founded her own consulting firm five years ago.", zh:"她五年前創立了自己的顧問公司。" }
    ]
  },
  {
    id: "w383", english: "foundation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["基礎"] ] },
      { pos: "nc", meaningGroups: [ ["基金會"] ] }
    ],
    examples: [
      { en:"A solid foundation of trust is essential for any partnership.", zh:"任何合作關係都需要堅實的信任基礎。" },
      { en:"The foundation provides scholarships to students in need.", zh:"該基金會為需要幫助的學生提供獎學金。" }
    ]
  },
  {
    id: "w384", english: "fountain", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["噴水池"] ] }
    ],
    examples: [
      { en:"Employees often eat lunch near the fountain in the courtyard.", zh:"員工經常在中庭的噴水池旁吃午餐。" }
    ]
  },
  {
    id: "w385", english: "freedom", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["自由"] ] }
    ],
    examples: [
      { en:"The new policy gives employees more freedom to work remotely.", zh:"新政策讓員工有更多遠端工作的自由。" }
    ]
  },
  {
    id: "w386", english: "freeway", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["高速公路"] ] }
    ],
    examples: [
      { en:"Traffic on the freeway was heavy during rush hour.", zh:"尖峰時段高速公路上的車流量很大。" }
    ]
  },
  {
    id: "w387", english: "frequently", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adv", meaningGroups: [ ["頻繁地","經常"] ] }
    ],
    examples: [
      { en:"Customers frequently ask about our return policy.", zh:"顧客經常詢問我們的退貨政策。" }
    ]
  },
  {
    id: "w388", english: "friendship", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["友誼"] ] }
    ],
    examples: [
      { en:"The two companies have built a strong friendship over the years.", zh:"這兩家公司多年來建立了深厚的情誼。" }
    ]
  },
  {
    id: "w389", english: "frown", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["皺眉"] ] },
      { pos: "nc", meaningGroups: [ ["皺眉的表情"] ] }
    ],
    examples: [
      { en:"The manager frowned when he saw the sales figures.", zh:"經理看到銷售數字時皺起了眉頭。" },
      { en:"She greeted the complaint with a frown.", zh:"她皺著眉頭回應了這項客訴。" }
    ]
  },
  {
    id: "w390", english: "frustrated", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["沮喪的","感到挫折的"] ] }
    ],
    examples: [
      { en:"Staff felt frustrated by the constant delays in the project.", zh:"員工對專案不斷延誤感到十分沮喪。" }
    ]
  },
  {
    id: "w391", english: "frustration", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["挫折","沮喪"] ] }
    ],
    examples: [
      { en:"Frustration among employees grew after the second postponement.", zh:"第二次延期之後，員工之間的挫折感加劇了。" }
    ]
  },
  {
    id: "w392", english: "fulfilling", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["令人滿足的","有成就感的"] ] }
    ],
    examples: [
      { en:"Many employees find volunteer work fulfilling.", zh:"許多員工認為做志工的工作很有成就感。" }
    ]
  },
  {
    id: "w393", english: "function", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["功能","作用"] ] },
      { pos: "vi", meaningGroups: [ ["運作","發揮作用"] ] }
    ],
    examples: [
      { en:"The main function of this software is to track inventory.", zh:"這個軟體的主要功能是追蹤庫存。" },
      { en:"The office cannot function properly without a reliable internet connection.", zh:"沒有穩定的網路連線，辦公室就無法正常運作。" }
    ]
  },
  {
    id: "w394", english: "fund", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["基金"] ] },
      { pos: "vt", meaningGroups: [ ["資助","提供資金"] ] }
    ],
    examples: [
      { en:"The government set up a fund to support small businesses.", zh:"政府設立了一項基金以支持小型企業。" },
      { en:"The project was funded by several private investors.", zh:"這項專案由幾位私人投資者提供資金。" }
    ]
  },
  {
    id: "w395", english: "fundamental", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["基本的","根本的"] ] }
    ],
    examples: [
      { en:"Honesty is a fundamental principle of our company culture.", zh:"誠實是我們公司文化的基本原則。" }
    ]
  },
  {
    id: "w396", english: "further", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["更多的","進一步的"] ] },
      { pos: "vt", meaningGroups: [ ["促進","推動"] ] }
    ],
    examples: [
      { en:"Further discussion will be needed before we sign the contract.", zh:"在簽約之前還需要進一步的討論。" },
      { en:"The new policy is designed to further employee development.", zh:"這項新政策旨在促進員工發展。" }
    ]
  },
  {
    id: "w397", english: "future", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["未來"] ] },
      { pos: "adj", meaningGroups: [ ["未來的"] ] }
    ],
    examples: [
      { en:"The company is investing heavily in the future of renewable energy.", zh:"該公司正大力投資於再生能源的未來。" },
      { en:"Future employees will receive training on the new system.", zh:"未來的員工將接受新系統的培訓。" }
    ]
  },
  {
    id: "w398", english: "gap", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["差距","缺口"] ] }
    ],
    examples: [
      { en:"There is a significant gap between the two departments' budgets.", zh:"這兩個部門的預算存在顯著差距。" }
    ]
  },
  {
    id: "w399", english: "garlic", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["大蒜"] ] }
    ],
    examples: [
      { en:"The chef added extra garlic to the sauce.", zh:"主廚在醬料中加了額外的大蒜。" }
    ]
  },
  {
    id: "w400", english: "gas", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["瓦斯","氣體"], ["汽油"] ] }
    ],
    examples: [
      { en:"The building uses natural gas for heating.", zh:"這棟建築使用天然瓦斯供暖。" },
      { en:"Rising gas prices have increased delivery costs.", zh:"汽油價格上漲增加了運送成本。" }
    ]
  },
  {
    id: "w401", english: "gaze", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["注視","凝視"] ] },
      { pos: "nc", meaningGroups: [ ["注視","凝視"] ] }
    ],
    examples: [
      { en:"She gazed out the window while thinking about the proposal.", zh:"她凝視著窗外，思考著這項提案。" },
      { en:"He kept his gaze fixed on the presentation screen.", zh:"他的目光一直盯著簡報畫面。" }
    ]
  },
  {
    id: "w402", english: "generation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["世代","一代"] ] }
    ],
    examples: [
      { en:"The company's founder passed the business on to the next generation.", zh:"公司創辦人把生意傳給了下一代。" }
    ]
  },
  {
    id: "w403", english: "genuine", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["真正的","真誠的"] ] }
    ],
    examples: [
      { en:"The manager showed genuine concern for the team's workload.", zh:"經理對團隊的工作量表現出真誠的關心。" }
    ]
  },
  {
    id: "w404", english: "gigantic", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["巨大的"] ] }
    ],
    examples: [
      { en:"The merger created a gigantic corporation with global reach.", zh:"這次合併打造出一家具有全球影響力的巨型企業。" }
    ]
  },
  {
    id: "w405", english: "ginger", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["薑"] ] }
    ],
    examples: [
      { en:"The recipe calls for fresh ginger and garlic.", zh:"這份食譜需要新鮮的薑和大蒜。" }
    ]
  },
  {
    id: "w406", english: "give away", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["贈送","免費給予"], ["洩露","暴露"] ] }
    ],
    examples: [
      { en:"The store gave away free samples to attract new customers.", zh:"這家店贈送了免費樣品以吸引新顧客。" },
      { en:"His nervous smile gave away his true feelings.", zh:"他緊張的笑容洩露了他真實的感受。" }
    ]
  },
  {
    id: "w407", english: "give credit to someone", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["歸功於（某人）","讚許（某人的貢獻）"] ] }
    ],
    examples: [
      { en:"The manager gave credit to her team for the successful product launch.", zh:"經理將這次成功的產品上市歸功於她的團隊。" }
    ]
  },
  {
    id: "w408", english: "global", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["全球的","全球性的"] ] }
    ],
    examples: [
      { en:"The company is expanding its global supply chain.", zh:"該公司正在擴展其全球供應鏈。" }
    ]
  },
  {
    id: "w409", english: "glow", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["發光","發亮"] ] },
      { pos: "nc", meaningGroups: [ ["光輝","光亮"] ] }
    ],
    examples: [
      { en:"The screen glowed in the dark conference room.", zh:"螢幕在黑暗的會議室中發出光亮。" },
      { en:"The lamp gave off a soft glow.", zh:"這盞燈發出柔和的光輝。" }
    ]
  },
  {
    id: "w410", english: "goods", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["貨物","商品"] ] }
    ],
    examples: [
      { en:"The warehouse stores goods before they are shipped to retailers.", zh:"倉庫在貨物運送給零售商之前會先儲存它們。" }
    ]
  },
  {
    id: "w411", english: "gossip", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["閒言閒語","八卦"] ] },
      { pos: "vi", meaningGroups: [ ["說閒話","聊八卦"] ] }
    ],
    examples: [
      { en:"Office gossip can damage trust among colleagues.", zh:"辦公室的八卦會破壞同事間的信任。" },
      { en:"Employees were gossiping about the upcoming layoffs.", zh:"員工們正在議論即將到來的裁員。" }
    ]
  },
  {
    id: "w412", english: "govern", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["治理","統治"] ] }
    ],
    examples: [
      { en:"New regulations now govern how the industry handles customer data.", zh:"新法規現在規範了該產業如何處理客戶資料。" }
    ]
  },
  {
    id: "w413", english: "gradually", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adv", meaningGroups: [ ["漸漸地","逐漸地"] ] }
    ],
    examples: [
      { en:"Sales gradually improved after the marketing campaign began.", zh:"行銷活動開始後，銷售逐漸好轉。" }
    ]
  },
  {
    id: "w414", english: "graduate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["畢業生"] ] },
      { pos: "vi", meaningGroups: [ ["畢業"] ] }
    ],
    examples: [
      { en:"The company prefers to hire recent graduates for entry-level positions.", zh:"該公司偏好聘用剛畢業的學生擔任入門職位。" },
      { en:"She graduated from business school two years ago.", zh:"她兩年前從商學院畢業。" }
    ]
  },
  {
    id: "w415", english: "grain", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["穀物","穀粒"] ] }
    ],
    examples: [
      { en:"The country exports large quantities of grain every year.", zh:"該國每年出口大量的穀物。" }
    ]
  },
  {
    id: "w416", english: "grapefruit", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["葡萄柚"] ] }
    ],
    examples: [
      { en:"The hotel serves fresh grapefruit juice at breakfast.", zh:"這家飯店在早餐時提供新鮮的葡萄柚汁。" }
    ]
  },
  {
    id: "w417", english: "grasp", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["理解","掌握"] ] },
      { pos: "nc", meaningGroups: [ ["理解","掌握"] ] }
    ],
    examples: [
      { en:"New employees may take time to grasp the company's procedures.", zh:"新員工可能需要一些時間才能掌握公司的作業流程。" },
      { en:"He has a good grasp of the local market.", zh:"他對當地市場有很好的掌握。" }
    ]
  },
  {
    id: "w418", english: "gratitude", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["感激","感謝"] ] }
    ],
    examples: [
      { en:"The manager expressed her gratitude to the entire team.", zh:"經理向整個團隊表達了她的感激之情。" }
    ]
  },
  {
    id: "w419", english: "ground", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["地面"] ] },
      { pos: "nc", meaningGroups: [ ["理由","根據"] ] }
    ],
    examples: [
      { en:"Workers laid new cables under the ground.", zh:"工人在地下鋪設了新的電纜。" },
      { en:"The client had no grounds for canceling the contract.", zh:"客戶沒有取消合約的理由。" }
    ]
  },
  {
    id: "w420", english: "growth", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["成長","增長"] ] }
    ],
    examples: [
      { en:"The company reported steady growth in overseas markets.", zh:"該公司回報海外市場有穩定的成長。" }
    ]
  },
  {
    id: "w421", english: "grub", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["翻找","挖尋"] ] }
    ],
    examples: [
      { en:"He grubbed around in his bag looking for his employee badge.", zh:"他在包裡翻找他的員工識別證。" }
    ]
  },
  {
    id: "w422", english: "guard", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["警衛","守衛"] ] },
      { pos: "vt", meaningGroups: [ ["守衛","保護"] ] }
    ],
    examples: [
      { en:"A security guard checks IDs at the main entrance.", zh:"警衛在正門檢查身分證件。" },
      { en:"The company guards its trade secrets carefully.", zh:"該公司謹慎地保護其商業機密。" }
    ]
  },
  {
    id: "w423", english: "guardian", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["監護人"] ] }
    ],
    examples: [
      { en:"The child's legal guardian signed the consent form.", zh:"這名兒童的法定監護人簽署了同意書。" }
    ]
  },
  {
    id: "w424", english: "guidance", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["指導","引導"] ] }
    ],
    examples: [
      { en:"New hires receive guidance from a senior mentor during their first month.", zh:"新員工在第一個月會獲得資深導師的指導。" }
    ]
  },
  {
    id: "w425", english: "guide", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["指導","引導"] ] },
      { pos: "nc", meaningGroups: [ ["指南"], ["導遊"] ] }
    ],
    examples: [
      { en:"The manager guided the new intern through the onboarding process.", zh:"經理引導新來的實習生完成入職流程。" },
      { en:"The employee handbook serves as a guide to company policies.", zh:"員工手冊作為公司政策的指南。" }
    ]
  },
  {
    id: "w426", english: "handcrafted", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["手工製作的"] ] }
    ],
    examples: [
      { en:"The store sells handcrafted furniture made by local artisans.", zh:"這家店販售由當地工匠手工製作的家具。" }
    ]
  },
  {
    id: "w427", english: "handful", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["一把","少數"] ] }
    ],
    examples: [
      { en:"Only a handful of employees attended the optional training session.", zh:"只有少數員工參加了這場自願性的培訓課程。" }
    ]
  },
  {
    id: "w428", english: "handle", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["處理","應付"] ] },
      { pos: "nc", meaningGroups: [ ["把手"] ] }
    ],
    examples: [
      { en:"The customer service team handles complaints professionally.", zh:"客服團隊以專業的方式處理客訴。" },
      { en:"The door handle needs to be repaired.", zh:"門把手需要修理。" }
    ]
  },
  {
    id: "w429", english: "handwriting", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["筆跡","手寫字"] ] }
    ],
    examples: [
      { en:"The pharmacist had trouble reading the doctor's handwriting.", zh:"藥師很難辨認醫生的筆跡。" }
    ]
  },
  {
    id: "w430", english: "handy", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["便利的","方便的"] ] }
    ],
    examples: [
      { en:"This app is handy for tracking business expenses.", zh:"這個應用程式對追蹤商務支出很方便。" }
    ]
  },
  {
    id: "w432", english: "hardship", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["困苦","艱難"] ] }
    ],
    examples: [
      { en:"The company offered financial support to employees facing hardship.", zh:"公司為面臨困境的員工提供財務支援。" }
    ]
  },
  {
    id: "w433", english: "harmful", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["有害的"] ] }
    ],
    examples: [
      { en:"The factory reduced emissions of harmful chemicals.", zh:"這家工廠減少了有害化學物質的排放。" }
    ]
  },
  {
    id: "w434", english: "harmony", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["和諧"] ] }
    ],
    examples: [
      { en:"The manager tries to maintain harmony among team members.", zh:"經理努力維持團隊成員之間的和諧。" }
    ]
  },
  {
    id: "w435", english: "harvest", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["收成","收穫"] ] },
      { pos: "vt", meaningGroups: [ ["收割","收穫"] ] }
    ],
    examples: [
      { en:"This year's harvest was smaller due to the drought.", zh:"由於乾旱，今年的收成較少。" },
      { en:"Farmers harvest the crops in early autumn.", zh:"農民在初秋收割農作物。" }
    ]
  },
  {
    id: "w436", english: "headline", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["標題","頭條新聞"] ] }
    ],
    examples: [
      { en:"The merger made headlines in every major newspaper.", zh:"這次合併成為每家主要報紙的頭條新聞。" }
    ]
  },
  {
    id: "w437", english: "headquarters", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["總部"] ] }
    ],
    examples: [
      { en:"The company relocated its headquarters to a bigger city.", zh:"該公司將總部遷移到了一個更大的城市。" }
    ]
  },
  {
    id: "w438", english: "healthful", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["有益健康的"] ] }
    ],
    examples: [
      { en:"The cafeteria now offers more healthful meal options.", zh:"員工餐廳現在提供更多有益健康的餐點選擇。" }
    ]
  },
  {
    id: "w439", english: "hell", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["地獄"] ] }
    ],
    examples: [
      { en:"The delayed flight turned their business trip into hell.", zh:"航班延誤讓他們的出差之旅變得如地獄般痛苦。" }
    ]
  },
  {
    id: "w440", english: "hero", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["英雄"] ] }
    ],
    examples: [
      { en:"The employee who reported the safety flaw was treated as a hero.", zh:"那位回報安全缺陷的員工被視為英雄。" }
    ]
  },
  {
    id: "w441", english: "hesitate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["遲疑","猶豫"] ] }
    ],
    examples: [
      { en:"Please don't hesitate to contact us if you have any questions.", zh:"如果您有任何問題，請不要遲疑，儘管與我們聯繫。" }
    ]
  },
  {
    id: "w442", english: "highly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adv", meaningGroups: [ ["高度地","非常"] ] }
    ],
    examples: [
      { en:"She is a highly qualified candidate for the position.", zh:"她是這個職位條件極佳的候選人。" }
    ]
  },
  {
    id: "w443", english: "hike", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["健行","遠足"], ["（物價）上漲"] ] },
      { pos: "vt", meaningGroups: [ ["提高（物價）"] ] }
    ],
    examples: [
      { en:"Employees went on a hike to celebrate the end of the project.", zh:"員工們去健行以慶祝專案結束。" },
      { en:"The airline announced a price hike for international flights.", zh:"這家航空公司宣布國際航班將提高票價。" }
    ]
  },
  {
    id: "w444", english: "honest", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["誠實的"] ] }
    ],
    examples: [
      { en:"Honest feedback from customers helps us improve our service.", zh:"顧客誠實的意見回饋有助於我們改善服務。" }
    ]
  },
  {
    id: "w445", english: "honor", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["榮譽"] ] },
      { pos: "vt", meaningGroups: [ ["尊敬"], ["履行（承諾）","遵守"] ] }
    ],
    examples: [
      { en:"It is an honor to receive this award on behalf of the team.", zh:"能代表團隊接受這個獎項是一種榮譽。" },
      { en:"The supplier failed to honor the terms of the contract.", zh:"供應商未能履行合約條款。" }
    ]
  },
  {
    id: "w446", english: "hook sb. in", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["吸引","拉攏"] ] }
    ],
    examples: [
      { en:"The eye-catching advertisement hooked customers in immediately.", zh:"這則吸睛的廣告立刻吸引了顧客。" }
    ]
  },
  {
    id: "w447", english: "horrible", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["可怕的","糟糕的"] ] }
    ],
    examples: [
      { en:"The team had a horrible experience with the previous vendor.", zh:"這個團隊之前和那家供應商合作的經驗非常糟糕。" }
    ]
  },
  {
    id: "w448", english: "hostel", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["旅舍","青年旅館"] ] }
    ],
    examples: [
      { en:"Budget travelers often stay at hostels near the train station.", zh:"精打細算的旅客常住在火車站附近的青年旅館。" }
    ]
  },
  {
    id: "w449", english: "humorous", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["幽默的","滑稽的"] ] }
    ],
    examples: [
      { en:"The presenter opened the seminar with a humorous story.", zh:"主持人以一個幽默的故事開場這場研討會。" }
    ]
  },
  {
    id: "w450", english: "hunt", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["狩獵","打獵"], ["搜尋","尋找"] ] }
    ],
    examples: [
      { en:"The documentary shows how wolves hunt in packs.", zh:"這部紀錄片展示狼群如何集體狩獵。" },
      { en:"She has been hunting for a new job for months.", zh:"她已經找工作好幾個月了。" }
    ]
  },
  {
    id: "w451", english: "ideal", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["理想的"] ] },
      { pos: "nc", meaningGroups: [ ["理想"] ] }
    ],
    examples: [
      { en:"This location is ideal for a new retail store.", zh:"這個地點很適合開設新的零售店。" },
      { en:"Customer satisfaction is the company's ideal, not just a slogan.", zh:"顧客滿意度是公司的理想目標，而不只是口號。" }
    ]
  },
  {
    id: "w452", english: "identity", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["身份"], ["特性"] ] }
    ],
    examples: [
      { en:"Visitors must show identification to confirm their identity at the front desk.", zh:"訪客必須出示證件以在櫃檯確認身份。" },
      { en:"The brand redesigned its logo to strengthen its corporate identity.", zh:"該品牌重新設計標誌以強化其企業特色。" }
    ]
  },
  {
    id: "w453", english: "idol", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["偶像"] ] }
    ],
    examples: [
      { en:"The young designer became an idol among fashion students.", zh:"這位年輕設計師成為時尚系學生心中的偶像。" }
    ]
  },
  {
    id: "w454", english: "illustrate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["說明","闡明"] ] }
    ],
    examples: [
      { en:"The chart illustrates the company's revenue growth over five years.", zh:"這張圖表說明了公司五年來的營收成長。" }
    ]
  },
  {
    id: "w455", english: "image", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["圖像","影像"], ["形象"] ] }
    ],
    examples: [
      { en:"Please attach an image of the damaged product.", zh:"請附上損壞產品的圖片。" },
      { en:"The scandal damaged the company's public image.", zh:"這場醜聞損害了公司的公眾形象。" }
    ]
  },
  {
    id: "w456", english: "imagination", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["想像力"] ] }
    ],
    examples: [
      { en:"Great advertising requires both data and imagination.", zh:"出色的廣告既需要數據也需要想像力。" }
    ]
  },
  {
    id: "w457", english: "imaginative", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["有想像力的","創意豐富的"] ] }
    ],
    examples: [
      { en:"The design team came up with an imaginative solution to the packaging problem.", zh:"設計團隊針對包裝問題提出了一個富有創意的解決方案。" }
    ]
  },
  {
    id: "w458", english: "imagine", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["想像"] ] }
    ],
    examples: [
      { en:"It's hard to imagine the office without the old coffee machine.", zh:"很難想像辦公室裡沒有那台舊咖啡機的樣子。" }
    ]
  },
  {
    id: "w459", english: "immediately", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adv", meaningGroups: [ ["立即","馬上"] ] }
    ],
    examples: [
      { en:"Please respond to the client immediately.", zh:"請立即回覆客戶。" }
    ]
  },
  {
    id: "w460", english: "immigration", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["移民（入境）"] ] }
    ],
    examples: [
      { en:"The company's HR team helps foreign employees with immigration paperwork.", zh:"公司的人資團隊協助外籍員工處理移民相關文件。" }
    ]
  },
  {
    id: "w461", english: "impact", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["衝擊","影響"] ] },
      { pos: "vt", meaningGroups: [ ["對…產生影響"] ] }
    ],
    examples: [
      { en:"The new policy will have a significant impact on employee benefits.", zh:"這項新政策將對員工福利產生重大影響。" },
      { en:"Rising fuel costs have impacted the company's shipping budget.", zh:"燃料成本上升已經影響了公司的運送預算。" }
    ]
  },
  {
    id: "w462", english: "impartial", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["公正的","不偏不倚的"] ] }
    ],
    examples: [
      { en:"An impartial committee will review all the complaints.", zh:"一個公正的委員會將審查所有的投訴。" }
    ]
  },
  {
    id: "w463", english: "importance", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["重要性"] ] }
    ],
    examples: [
      { en:"Management stressed the importance of meeting the deadline.", zh:"管理層強調了如期完成的重要性。" }
    ]
  },
  {
    id: "w464", english: "improve", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["改善","改進"] ] }
    ],
    examples: [
      { en:"The new software helped improve productivity across departments.", zh:"這套新軟體有助於提升各部門的生產力。" }
    ]
  },
  {
    id: "w466", english: "in addition to", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["除了…之外（還）","加上"] ] }
    ],
    examples: [
      { en:"In addition to a salary increase, employees will receive extra vacation days.", zh:"除了加薪之外，員工還會獲得額外的休假天數。" }
    ]
  },
  {
    id: "w467", english: "incense", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["香","香品"] ] }
    ],
    examples: [
      { en:"The shop specializes in scented candles and incense.", zh:"這家店專門販售香氛蠟燭和香品。" }
    ]
  },
  {
    id: "w468", english: "include", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["包括","包含"] ] }
    ],
    examples: [
      { en:"The package includes shipping and installation.", zh:"這個套裝方案包含運送和安裝服務。" }
    ]
  },
  {
    id: "w469", english: "income", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["收入"] ] }
    ],
    examples: [
      { en:"The company's annual income increased by ten percent.", zh:"該公司的年度收入增加了百分之十。" }
    ]
  },
  {
    id: "w470", english: "inconsistency", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["不一致","矛盾"] ] }
    ],
    examples: [
      { en:"The auditor found several inconsistencies in the financial report.", zh:"稽核人員在財務報告中發現了幾處矛盾之處。" }
    ]
  },
  {
    id: "w471", english: "inconvenient", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["不方便的"] ] }
    ],
    examples: [
      { en:"The new parking policy is inconvenient for employees who drive.", zh:"新的停車政策對開車通勤的員工來說很不方便。" }
    ]
  },
  {
    id: "w472", english: "industry", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["產業","工業"] ] }
    ],
    examples: [
      { en:"The tourism industry suffered a major setback during the pandemic.", zh:"觀光產業在疫情期間遭受了重大打擊。" }
    ]
  },
  {
    id: "w473", english: "influential", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["有影響力的"] ] }
    ],
    examples: [
      { en:"She is one of the most influential leaders in the tech industry.", zh:"她是科技產業中最具影響力的領導者之一。" }
    ]
  },
  {
    id: "w474", english: "initial", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["最初的","初始的"] ] },
      { pos: "nc", meaningGroups: [ ["姓名的首字母"] ] }
    ],
    examples: [
      { en:"The initial proposal was rejected by the board.", zh:"最初的提案遭到董事會否決。" },
      { en:"Please sign your initials at the bottom of each page.", zh:"請在每一頁的底部簽署您姓名的首字母。" }
    ]
  },
  {
    id: "w475", english: "inn", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["小旅館","客棧"] ] }
    ],
    examples: [
      { en:"The travelers stayed at a cozy inn near the harbor.", zh:"旅客們住在港口附近一間舒適的小旅館。" }
    ]
  },
  {
    id: "w476", english: "inner", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["內部的","內心的"] ] }
    ],
    examples: [
      { en:"Employees can access the inner office only with a keycard.", zh:"員工只有使用門卡才能進入內部辦公室。" }
    ]
  },
  {
    id: "w477", english: "inspection", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["檢查","檢驗"] ] }
    ],
    examples: [
      { en:"The factory passed its annual safety inspection.", zh:"這家工廠通過了年度安全檢查。" }
    ]
  },
  {
    id: "w478", english: "inspiring", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["鼓舞人心的"] ] }
    ],
    examples: [
      { en:"The CEO gave an inspiring speech at the annual meeting.", zh:"執行長在年度會議上發表了一場鼓舞人心的演講。" }
    ]
  },
  {
    id: "w479", english: "install", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["安裝"] ] }
    ],
    examples: [
      { en:"The IT team will install the new software this weekend.", zh:"IT團隊將在這個週末安裝新軟體。" }
    ]
  },
  {
    id: "w480", english: "instead of", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["而不是"] ] }
    ],
    examples: [
      { en:"The manager chose to email the update instead of calling.", zh:"經理選擇用電子郵件發送更新，而不是打電話。" }
    ]
  },
  {
    id: "w481", english: "instruction", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["指令","說明"] ] }
    ],
    examples: [
      { en:"Please follow the instructions carefully before operating the machine.", zh:"操作機器前請仔細遵循說明。" }
    ]
  },
{
    id: "w482", english: "insurance", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["保險"] ] }
    ],
    examples: [
      { en:"The company offers health insurance to all full-time employees.", zh:"公司為所有正職員工提供健康保險。" }
    ]
  },
  {
    id: "w483", english: "intend", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["打算","意圖"] ] }
    ],
    examples: [
      { en:"She intends to apply for the management position next month.", zh:"她打算下個月申請那個管理職位。" }
    ]
  },
  {
    id: "w484", english: "interpret", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["解釋","詮釋"], ["口譯","傳譯"] ] }
    ],
    examples: [
      { en:"Analysts interpreted the sales data differently.", zh:"分析師對這份銷售數據有不同的解讀。" },
      { en:"She was hired to interpret for the foreign delegation.", zh:"她被聘請為那個外國代表團做口譯。" }
    ]
  },
  {
    id: "w485", english: "interrupt", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["打斷","打擾"] ] }
    ],
    examples: [
      { en:"Please don't interrupt me while I'm on a call with a client.", zh:"我跟客戶通話時請不要打斷我。" }
    ]
  },
  {
    id: "w486", english: "intimate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["親密的","私人的"] ] },
      { pos: "vt", meaningGroups: [ ["暗示","示意"] ] }
    ],
    examples: [
      { en:"The two founders have an intimate working relationship.", zh:"這兩位創辦人有著親密的合作關係。" },
      { en:"He intimated that the merger might fall through.", zh:"他暗示這次併購可能會失敗。" }
    ]
  },
  {
    id: "w487", english: "introduce", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["介紹"], ["引進","推出"] ] }
    ],
    examples: [
      { en:"Let me introduce you to our new marketing director.", zh:"讓我向你介紹我們的新行銷總監。" },
      { en:"The company plans to introduce a new product line next quarter.", zh:"公司計劃在下一季推出新的產品線。" }
    ]
  },
  {
    id: "w488", english: "invitation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["邀請","邀請函"] ] }
    ],
    examples: [
      { en:"We received an invitation to the annual shareholders' meeting.", zh:"我們收到了年度股東大會的邀請函。" }
    ]
  },
  {
    id: "w489", english: "isolated", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["孤立的","隔離的"], ["偶發的","單一的"] ] }
    ],
    examples: [
      { en:"The factory is isolated from the rest of the industrial park.", zh:"這家工廠與工業園區的其他部分是隔離的。" },
      { en:"Management insisted the complaint was an isolated incident.", zh:"管理層堅稱這只是一個偶發事件。" }
    ]
  },
  {
    id: "w490", english: "issue", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["問題","議題"] ] },
      { pos: "vt", meaningGroups: [ ["發布","發行"] ] }
    ],
    examples: [
      { en:"The company is facing a serious issue with its supply chain.", zh:"這家公司的供應鏈正面臨一個嚴重的問題。" },
      { en:"The bank issued a refund after confirming the billing error.", zh:"銀行確認帳單錯誤後發放了退款。" }
    ]
  },
  {
    id: "w491", english: "ivory", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["象牙"] ] }
    ],
    examples: [
      { en:"The museum displayed a rare carving made of ivory.", zh:"博物館展出了一件用象牙雕刻的稀有藏品。" }
    ]
  },
  {
    id: "w492", english: "jealous", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["嫉妒的","吃醋的"] ] }
    ],
    examples: [
      { en:"He felt jealous when his colleague received the promotion instead of him.", zh:"當同事得到那個升遷機會而不是他時，他感到很嫉妒。" }
    ]
  },
  {
    id: "w493", english: "jet lag", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["時差","時差疲勞"] ] }
    ],
    examples: [
      { en:"After the long flight to Tokyo, she was suffering from severe jet lag.", zh:"經過長途飛行到東京後，她受到嚴重時差的影響。" }
    ]
  },
  {
    id: "w494", english: "jewel", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["珠寶","寶石"] ] }
    ],
    examples: [
      { en:"The museum's collection includes a jewel once owned by royalty.", zh:"博物館的收藏品中包括一件曾屬於皇室的寶石。" }
    ]
  },
  {
    id: "w495", english: "jewelry", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["珠寶","首飾"] ] }
    ],
    examples: [
      { en:"The store specializes in handmade jewelry.", zh:"這家店專門販售手工首飾。" }
    ]
  },
  {
    id: "w496", english: "journal", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["日誌","日記"], ["期刊","雜誌"] ] }
    ],
    examples: [
      { en:"He keeps a journal of his daily business meetings.", zh:"他把每天的商務會議都記錄在日誌裡。" },
      { en:"Her research was published in a leading scientific journal.", zh:"她的研究發表在一份頂尖的科學期刊上。" }
    ]
  },
  {
    id: "w497", english: "journey", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["旅程","旅途"] ] }
    ],
    examples: [
      { en:"The company's journey from a small startup to a global brand took over a decade.", zh:"這家公司從小型新創企業成長為全球品牌的過程花了十多年。" }
    ]
  },
  {
    id: "w498", english: "junk", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["垃圾","廢物"] ] }
    ],
    examples: [
      { en:"Please clear out the junk from the storage room before the inspection.", zh:"請在檢查前把儲藏室裡的廢物清理掉。" }
    ]
  },
  {
    id: "w499", english: "kick off", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["開始","啟動"] ] }
    ],
    examples: [
      { en:"The conference will kick off with a keynote speech from the CEO.", zh:"這場研討會將以執行長的主題演講開始。" }
    ]
  },
  {
    id: "w500", english: "knob", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["把手","旋鈕"] ] }
    ],
    examples: [
      { en:"Turn the knob clockwise to increase the volume.", zh:"把旋鈕順時針轉動可以調高音量。" }
    ]
  },
  {
    id: "w501", english: "let sb. in on sth", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["讓某人知道秘密","透露某事給某人"] ] }
    ],
    examples: [
      { en:"The manager let the team in on the upcoming restructuring plan.", zh:"經理讓團隊知道了即將進行的重組計畫。" }
    ]
  },
  {
    id: "w502", english: "labor", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["勞動","勞力","人力"] ] }
    ],
    examples: [
      { en:"The factory relies heavily on manual labor during peak season.", zh:"這家工廠在旺季非常依賴人力勞動。" }
    ]
  },
  {
    id: "w503", english: "lack", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["缺乏","不足"] ] },
      { pos: "vt", meaningGroups: [ ["缺乏","沒有"] ] }
    ],
    examples: [
      { en:"The lack of funding delayed the entire project.", zh:"資金的缺乏使整個專案延遲。" },
      { en:"The startup lacks the resources to expand overseas.", zh:"這家新創公司缺乏拓展海外市場的資源。" }
    ]
  },
  {
    id: "w504", english: "landscape", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["景觀","風景"], ["局勢","格局"] ] }
    ],
    examples: [
      { en:"The hotel offers a stunning landscape view of the mountains.", zh:"這間飯店可以欣賞到令人驚嘆的山景。" },
      { en:"The competitive landscape has changed dramatically over the past year.", zh:"競爭局勢在過去一年中發生了劇烈的變化。" }
    ]
  },
  {
    id: "w505", english: "large-scale", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["大規模的"] ] }
    ],
    examples: [
      { en:"The company launched a large-scale marketing campaign across Asia.", zh:"這家公司在亞洲展開了一場大規模的行銷活動。" }
    ]
  },
  {
    id: "w506", english: "latter", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["後者的","後面的"] ] }
    ],
    examples: [
      { en:"Of the two proposals, the latter is more cost-effective.", zh:"在這兩個提案中，後者更具成本效益。" }
    ]
  },
  {
    id: "w507", english: "lawn", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["草坪"] ] }
    ],
    examples: [
      { en:"The gardener mows the lawn every Saturday morning.", zh:"園丁每個星期六早上都會修剪草坪。" }
    ]
  },
  {
    id: "w508", english: "lawyer", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["律師"] ] }
    ],
    examples: [
      { en:"The company hired a lawyer to review the merger contract.", zh:"這家公司聘請了一位律師審查併購合約。" }
    ]
  },
  {
    id: "w509", english: "learning curve", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["學習曲線"] ] }
    ],
    examples: [
      { en:"There is a steep learning curve when using this new accounting software.", zh:"使用這套新的會計軟體有很陡的學習曲線。" }
    ]
  },
  {
    id: "w510", english: "legal", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["法律的","合法的"] ] }
    ],
    examples: [
      { en:"The department consulted a legal advisor before signing the contract.", zh:"該部門在簽約前徵詢了法律顧問的意見。" }
    ]
  },
  {
    id: "w511", english: "legend", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["傳說","傳奇人物"], ["圖例","說明"] ] }
    ],
    examples: [
      { en:"The founder of the company has become a legend in the industry.", zh:"這家公司的創辦人已成為業界的傳奇人物。" },
      { en:"Check the legend at the bottom of the chart to understand the color codes.", zh:"請參考圖表下方的圖例以了解顏色代碼的意思。" }
    ]
  },
  {
    id: "w512", english: "length", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["長度"] ] }
    ],
    examples: [
      { en:"Please specify the length and width of the package for shipping.", zh:"請標明包裹的長度和寬度以便運送。" }
    ]
  },
  {
    id: "w513", english: "limitation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["限制","限度"] ] }
    ],
    examples: [
      { en:"Every insurance policy has certain limitations on coverage.", zh:"每份保單的承保範圍都有一定的限制。" }
    ]
  },
  {
    id: "w514", english: "limited", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["有限的"] ] }
    ],
    examples: [
      { en:"The promotional offer is available for a limited time only.", zh:"這項優惠僅在限定的時間內提供。" }
    ]
  },
  {
    id: "w515", english: "liquor", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["酒","烈酒"] ] }
    ],
    examples: [
      { en:"The store's liquor license allows it to sell alcoholic beverages.", zh:"這家店的酒類執照允許它銷售含酒精飲品。" }
    ]
  },
  {
    id: "w516", english: "literary", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["文學的","文藝的"] ] }
    ],
    examples: [
      { en:"She won a prestigious literary award for her first novel.", zh:"她的第一部小說獲得了一項聲望崇高的文學獎。" }
    ]
  },
  {
    id: "w517", english: "lively", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["活潑的","熱鬧的","生動的"] ] }
    ],
    examples: [
      { en:"The trade show had a lively atmosphere with visitors from around the world.", zh:"這場貿易展覽會氣氛熱鬧，吸引了來自世界各地的訪客。" }
    ]
  },
  {
    id: "w518", english: "location", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["位置","地點"] ] }
    ],
    examples: [
      { en:"The company is looking for a new location for its headquarters.", zh:"這家公司正在尋找新的總部地點。" }
    ]
  },
  {
    id: "w519", english: "loss", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["損失","虧損"] ] }
    ],
    examples: [
      { en:"The firm reported a net loss for the third quarter.", zh:"該公司第三季報告出現淨虧損。" }
    ]
  },
  {
    id: "w520", english: "lotion", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["乳液","護膚液"] ] }
    ],
    examples: [
      { en:"The hotel provides complimentary lotion in every guest room.", zh:"這間飯店在每個客房都提供免費的乳液。" }
    ]
  },
  {
    id: "w521", english: "loyal", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["忠誠的","忠實的"] ] }
    ],
    examples: [
      { en:"The company rewards its loyal customers with exclusive discounts.", zh:"這家公司會給忠實的顧客提供專屬折扣作為回饋。" }
    ]
  },
  {
    id: "w522", english: "luck", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["運氣","幸運"] ] }
    ],
    examples: [
      { en:"With a bit of luck, the negotiation should be finalized by Friday.", zh:"運氣好的話，這場談判應該可以在星期五前完成。" }
    ]
  },
  {
    id: "w523", english: "luggage", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["行李"] ] }
    ],
    examples: [
      { en:"Passengers are advised to check their luggage in advance.", zh:"建議乘客提早辦理行李托運。" }
    ]
  },
  {
    id: "w524", english: "madam", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["夫人","女士"] ] }
    ],
    examples: [
      { en:"Good morning, madam. How may I assist you today?", zh:"早安，女士。今天有什麼需要我協助的嗎？" }
    ]
  },
  {
    id: "w525", english: "magical", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["神奇的","魔法的"] ] }
    ],
    examples: [
      { en:"The marketing team created a magical shopping experience for customers.", zh:"行銷團隊為顧客創造了神奇的購物體驗。" }
    ]
  },
  {
    id: "w526", english: "magnificent", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["壯麗的","宏偉的"] ] }
    ],
    examples: [
      { en:"The new corporate headquarters offers a magnificent view of the city skyline.", zh:"這座新的企業總部可以看到宏偉的城市天際線景觀。" }
    ]
  },
  {
    id: "w527", english: "maintain", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["維持","保養"], ["主張","堅稱"] ] }
    ],
    examples: [
      { en:"The technician is responsible for maintaining the equipment.", zh:"這位技術人員負責保養設備。" },
      { en:"The spokesperson maintained that the company had done nothing wrong.", zh:"發言人堅稱公司並沒有做錯任何事。" }
    ]
  },
  {
    id: "w528", english: "make sense", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["有道理","合理"] ] }
    ],
    examples: [
      { en:"It doesn't make sense to invest more money in a failing project.", zh:"再把更多錢投入一個失敗的專案並不合理。" }
    ]
  },
  {
    id: "w529", english: "manage", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["管理","經營"], ["設法","成功做到"] ] }
    ],
    examples: [
      { en:"She manages a team of fifteen employees.", zh:"她管理著一個十五人的團隊。" },
      { en:"Despite the tight deadline, they managed to finish the report on time.", zh:"儘管期限很緊迫，他們還是設法及時完成了報告。" }
    ]
  },
  {
    id: "w530", english: "manager", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["經理","主管"] ] }
    ],
    examples: [
      { en:"The new manager introduced several changes to improve efficiency.", zh:"新任經理引進了幾項改變以提升效率。" }
    ]
  },
  {
    id: "w531", english: "marvelous", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["奇妙的","了不起的"] ] }
    ],
    examples: [
      { en:"The presentation received marvelous feedback from the audience.", zh:"這場報告得到了聽眾了不起的好評。" }
    ]
  },
  {
    id: "w532", english: "masses", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["群眾","大眾"] ] }
    ],
    examples: [
      { en:"The new pricing strategy was designed to appeal to the masses.", zh:"這項新的定價策略是為了吸引大眾而設計的。" }
    ]
  },
  {
    id: "w533", english: "master", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["大師","專家"] ] },
      { pos: "vt", meaningGroups: [ ["精通","掌握"] ] }
    ],
    examples: [
      { en:"He is regarded as a master of negotiation.", zh:"他被認為是談判方面的大師。" },
      { en:"It took years for her to master the software's advanced features.", zh:"她花了好幾年才精通這套軟體的進階功能。" }
    ]
  },
  {
    id: "w534", english: "material", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["材料","原料"] ] },
      { pos: "adj", meaningGroups: [ ["重要的","實質性的"] ] }
    ],
    examples: [
      { en:"The factory ran out of raw material for production.", zh:"這家工廠的生產原料已經用完了。" },
      { en:"The contract was terminated due to a material breach of terms.", zh:"由於重大違約，這份合約遭到終止。" }
    ]
  },
  {
    id: "w535", english: "maturity", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["到期","期滿"], ["成熟","成熟度"] ] }
    ],
    examples: [
      { en:"The bond will reach maturity in five years.", zh:"這張債券將在五年後到期。" },
      { en:"The company has shown remarkable maturity in handling the crisis.", zh:"這家公司在處理這場危機時展現出驚人的成熟度。" }
    ]
  },
  {
    id: "w536", english: "meaningful", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["有意義的"] ] }
    ],
    examples: [
      { en:"The manager gave meaningful feedback during the performance review.", zh:"經理在績效考核中給予了有意義的回饋。" }
    ]
  },
  {
    id: "w537", english: "means", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["方法","手段"] ] }
    ],
    examples: [
      { en:"Email is the most common means of communication in the office.", zh:"電子郵件是辦公室裡最常見的溝通方式。" }
    ]
  },
  {
    id: "w538", english: "media", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["媒體"] ] }
    ],
    examples: [
      { en:"The product launch attracted significant media attention.", zh:"這次產品發表會吸引了媒體大量的關注。" }
    ]
  },
  {
    id: "w539", english: "membership", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["會員資格","會籍"] ] }
    ],
    examples: [
      { en:"Employees receive a free gym membership as part of their benefits package.", zh:"員工可以獲得免費的健身房會籍作為福利之一。" }
    ]
  },
  {
    id: "w540", english: "memorable", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["難忘的","值得紀念的"] ] }
    ],
    examples: [
      { en:"The company's anniversary event was truly memorable for all the staff.", zh:"公司的週年慶活動對全體員工來說真的很難忘。" }
    ]
  },
  {
    id: "w541", english: "merchant", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["商人","貿易商"] ] }
    ],
    examples: [
      { en:"The merchant imported textiles from overseas suppliers.", zh:"這位商人從海外供應商那裡進口紡織品。" }
    ]
  },
  {
    id: "w542", english: "merit", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["優點","價值"] ] },
      { pos: "vt", meaningGroups: [ ["值得","應得"] ] }
    ],
    examples: [
      { en:"The proposal has considerable merit and should be considered.", zh:"這項提案有相當大的價值，應該被納入考量。" },
      { en:"The issue merits further investigation.", zh:"這個問題值得進一步調查。" }
    ]
  },
  {
    id: "w543", english: "messy", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["凌亂的","雜亂的"], ["棘手的","麻煩的"] ] }
    ],
    examples: [
      { en:"His desk is always messy with piles of paperwork.", zh:"他的桌子總是堆滿文件，很凌亂。" },
      { en:"The merger turned into a messy legal dispute.", zh:"這次併購演變成一場棘手的法律糾紛。" }
    ]
  },
  {
    id: "w544", english: "microphone", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["麥克風"] ] }
    ],
    examples: [
      { en:"Please speak clearly into the microphone during the presentation.", zh:"報告時請對著麥克風清楚地說話。" }
    ]
  },
  {
    id: "w545", english: "miserable", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["悲慘的","痛苦的"] ] }
    ],
    examples: [
      { en:"Working conditions at the old factory were miserable.", zh:"那間老工廠的工作環境非常悲慘。" }
    ]
  },
  {
    id: "w546", english: "misery", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["痛苦","苦難"] ] }
    ],
    examples: [
      { en:"The delayed shipment caused nothing but misery for the logistics team.", zh:"貨物延遲送達只給物流團隊帶來了痛苦。" }
    ]
  },
  {
    id: "w547", english: "misfortune", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["不幸","厄運"] ] }
    ],
    examples: [
      { en:"It was sheer misfortune that the shipment arrived just after the deadline.", zh:"貨物剛好在期限之後才送達，純粹是不幸。" }
    ]
  },
  {
    id: "w548", english: "miss out", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["錯過機會"] ] }
    ],
    examples: [
      { en:"If you don't register today, you might miss out on the early-bird discount.", zh:"如果你今天不報名，可能會錯過早鳥優惠。" }
    ]
  },
  {
    id: "w549", english: "mixture", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["混合物","混合"] ] }
    ],
    examples: [
      { en:"The product is a mixture of natural and synthetic ingredients.", zh:"這項產品是天然與合成成分的混合物。" }
    ]
  },
  {
    id: "w550", english: "mobile", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["移動的","可移動的"] ] }
    ],
    examples: [
      { en:"The company introduced a mobile sales unit to reach rural customers.", zh:"這家公司推出了一個移動銷售單位以接觸鄉村地區的顧客。" }
    ]
  },
  {
    id: "w551", english: "moist", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["潮濕的","濕潤的"] ] }
    ],
    examples: [
      { en:"Keep the packaging in a cool place to prevent the contents from becoming moist.", zh:"請把包裝放在陰涼處，以避免內容物變潮濕。" }
    ]
  },
  {
    id: "w552", english: "monthly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["每月的"] ] },
      { pos: "adv", meaningGroups: [ ["每月一次地"] ] }
    ],
    examples: [
      { en:"Employees receive a monthly report summarizing their performance.", zh:"員工會收到一份總結其績效的月報。" },
      { en:"The rent is paid monthly by bank transfer.", zh:"房租是每月透過銀行轉帳支付一次。" }
    ]
  },
  {
    id: "w553", english: "moral", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["道德的","道義上的"] ] }
    ],
    examples: [
      { en:"The company faced a moral dilemma when deciding whether to lay off staff.", zh:"這家公司在決定是否裁員時面臨了道德上的難題。" }
    ]
  },
  {
    id: "w554", english: "moreover", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adv", meaningGroups: [ ["而且","此外"] ] }
    ],
    examples: [
      { en:"The proposal is cost-effective; moreover, it can be implemented within a month.", zh:"這項提案很具成本效益，而且可以在一個月內實施。" }
    ]
  },
  {
    id: "w555", english: "motivate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["激勵","促使"] ] }
    ],
    examples: [
      { en:"The manager used bonuses to motivate the sales team.", zh:"經理用獎金來激勵銷售團隊。" }
    ]
  },
  {
    id: "w556", english: "musical", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["音樂的"] ] },
      { pos: "nc", meaningGroups: [ ["音樂劇"] ] }
    ],
    examples: [
      { en:"She has a strong musical background.", zh:"她有很深厚的音樂背景。" },
      { en:"The company sponsored a Broadway musical as part of its marketing campaign.", zh:"這家公司贊助了一部百老匯音樂劇作為行銷活動的一部分。" }
    ]
  },
  {
    id: "w557", english: "native", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["本地的","原生的"] ] },
      { pos: "nc", meaningGroups: [ ["本地人"] ] }
    ],
    examples: [
      { en:"The firm prefers candidates with native fluency in Japanese.", zh:"這家公司偏好日語達到母語流利程度的應徵者。" },
      { en:"The tour guide is a native of the region.", zh:"這位導遊是這個地區的本地人。" }
    ]
  },
  {
    id: "w558", english: "nature", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["自然","自然界"], ["本質","性質"] ] }
    ],
    examples: [
      { en:"The resort is surrounded by nature.", zh:"這間度假村四周環繞著自然景觀。" },
      { en:"The nature of the problem requires immediate attention.", zh:"這個問題的本質需要立即處理。" }
    ]
  },
  {
    id: "w559", english: "necessarily", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adv", meaningGroups: [ ["必然地","一定"] ] }
    ],
    examples: [
      { en:"A higher price does not necessarily mean better quality.", zh:"較高的價格不一定代表較好的品質。" }
    ]
  },
  {
    id: "w560", english: "neighborhood", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["鄰里","社區"] ] }
    ],
    examples: [
      { en:"The new store is located in a busy commercial neighborhood.", zh:"這家新店位於一個熱鬧的商業社區裡。" }
    ]
  },
  {
    id: "w561", english: "nevertheless", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adv", meaningGroups: [ ["然而","儘管如此"] ] }
    ],
    examples: [
      { en:"The budget was tight; nevertheless, the team completed the project successfully.", zh:"預算很緊，儘管如此，團隊還是成功完成了這個專案。" }
    ]
  },
  {
    id: "w562", english: "nightmare", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["惡夢","夢魘"] ] }
    ],
    examples: [
      { en:"Coordinating the schedules of fifty employees turned into a logistical nightmare.", zh:"協調五十名員工的行程變成了一場後勤上的惡夢。" }
    ]
  },
  {
    id: "w563", english: "noble", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["高貴的","崇高的"] ] }
    ],
    examples: [
      { en:"The charity's noble mission attracted many corporate sponsors.", zh:"這個慈善機構崇高的使命吸引了許多企業贊助商。" }
    ]
  },
  {
    id: "w564", english: "normal", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["正常的","一般的"] ] }
    ],
    examples: [
      { en:"It is normal for shipments to take a few extra days during the holiday season.", zh:"假期期間貨物運送多花幾天是正常的。" }
    ]
  },
  {
    id: "w565", english: "nourishing", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["滋補的","有營養的"] ] }
    ],
    examples: [
      { en:"The cafeteria now offers more nourishing meal options for employees.", zh:"員工餐廳現在提供更多有營養的餐點選擇。" }
    ]
  },
  {
    id: "w566", english: "novel", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["小說"] ] },
      { pos: "adj", meaningGroups: [ ["新穎的","新奇的"] ] }
    ],
    examples: [
      { en:"She spent five years writing her first novel.", zh:"她花了五年時間寫她的第一部小說。" },
      { en:"The startup came up with a novel approach to recycling packaging.", zh:"這家新創公司想出了一個新穎的包裝回收方法。" }
    ]
  },
  {
    id: "w567", english: "numerous", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["眾多的","許多的"] ] }
    ],
    examples: [
      { en:"The company has received numerous complaints about the delayed delivery.", zh:"這家公司收到了許多關於延遲送貨的抱怨。" }
    ]
  },
  {
    id: "w568", english: "object", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["物體"] ] },
      { pos: "vi", meaningGroups: [ ["反對"] ] }
    ],
    examples: [
      { en:"Please remove any sharp objects before packing the box.", zh:"包裝箱子前請先移除任何尖銳物體。" },
      { en:"Several board members objected to the proposed merger.", zh:"好幾位董事會成員反對這項擬議中的併購案。" }
    ]
  },
  {
    id: "w569", english: "objective", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["目標"] ] },
      { pos: "adj", meaningGroups: [ ["客觀的"] ] }
    ],
    examples: [
      { en:"The team's main objective is to increase customer retention.", zh:"這個團隊的主要目標是提高顧客留存率。" },
      { en:"The manager tried to give an objective assessment of the situation.", zh:"這位經理試圖對這個情況給出客觀的評估。" }
    ]
  },
  {
    id: "w570", english: "observe", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["觀察","注意到"], ["遵守"] ] }
    ],
    examples: [
      { en:"The supervisor observed a decline in productivity.", zh:"主管注意到生產力下降了。" },
      { en:"All employees must observe the company's safety regulations.", zh:"所有員工都必須遵守公司的安全規定。" }
    ]
  },
  {
    id: "w571", english: "obstacle", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["障礙","阻礙"] ] }
    ],
    examples: [
      { en:"Limited funding remains the biggest obstacle to expanding the business.", zh:"資金有限仍是拓展業務最大的障礙。" }
    ]
  },
  {
    id: "w572", english: "obtain", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["獲得","取得"] ] }
    ],
    examples: [
      { en:"The firm must obtain government approval before launching the product.", zh:"這家公司在推出產品前必須先取得政府核准。" }
    ]
  },
  {
    id: "w573", english: "obvious", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["明顯的","顯而易見的"] ] }
    ],
    examples: [
      { en:"It was obvious that the marketing strategy needed to change.", zh:"很明顯，這項行銷策略需要改變。" }
    ]
  },
  {
    id: "w574", english: "occasion", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["場合","時機"] ] }
    ],
    examples: [
      { en:"The annual gala is a special occasion for the company to honor top performers.", zh:"年度晚宴是公司表揚頂尖員工的特別場合。" }
    ]
  },
  {
    id: "w575", english: "odd", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["奇怪的","古怪的"], ["奇數的"] ] }
    ],
    examples: [
      { en:"It seemed odd that no one responded to the email.", zh:"沒有人回覆這封電子郵件似乎很奇怪。" },
      { en:"Invoices with odd numbers are processed on Mondays.", zh:"編號為奇數的發票會在星期一處理。" }
    ]
  },
  {
    id: "w576", english: "offering", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["提供之物","產品或服務項目"] ] }
    ],
    examples: [
      { en:"The company expanded its product offerings to include eco-friendly packaging.", zh:"這家公司擴充了產品項目，加入了環保包裝。" }
    ]
  },
  {
    id: "w577", english: "on top of that", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["此外","再加上"] ] }
    ],
    examples: [
      { en:"The flight was delayed for three hours; on top of that, our luggage was lost.", zh:"班機延誤了三個小時，此外，我們的行李還遺失了。" }
    ]
  },
  {
    id: "w578", english: "open market", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["公開市場","自由市場"] ] }
    ],
    examples: [
      { en:"The shares will soon be available for trading on the open market.", zh:"這些股票不久後就能在公開市場上交易。" }
    ]
  },
  {
    id: "w579", english: "opera", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["歌劇"] ] }
    ],
    examples: [
      { en:"The corporate sponsor donated funds to support the local opera house.", zh:"這家企業贊助商捐款支持當地的歌劇院。" }
    ]
  },
  {
    id: "w580", english: "operation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["營運","作業"], ["手術"] ] }
    ],
    examples: [
      { en:"The factory's operations were suspended due to the power outage.", zh:"由於停電，工廠的作業被迫暫停。" },
      { en:"He was absent from work because he underwent an operation.", zh:"他因為接受了一場手術而缺勤。" }
    ]
  },
  {
    id: "w581", english: "opinion", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["意見","看法"] ] }
    ],
    examples: [
      { en:"The survey was conducted to gather customers' opinions on the new product.", zh:"這項調查是為了收集顧客對新產品的意見。" }
    ]
  },
  {
    id: "w582", english: "organically", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adv", meaningGroups: [ ["有機地"], ["自然地","逐漸地"] ] }
    ],
    examples: [
      { en:"The vegetables are grown organically without any pesticides.", zh:"這些蔬菜是以有機方式種植，不使用任何農藥。" },
      { en:"The company's revenue grew organically over the past five years.", zh:"這家公司的營收在過去五年間自然地成長。" }
    ]
  },
  {
    id: "w583", english: "original", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["最初的","原創的"] ] },
      { pos: "nc", meaningGroups: [ ["原件","原作"] ] }
    ],
    examples: [
      { en:"The original design had to be revised after customer feedback.", zh:"在收到顧客的意見後，最初的設計必須修改。" },
      { en:"Please submit the original along with two copies.", zh:"請連同兩份影本一起提交原件。" }
    ]
  },
  {
    id: "w584", english: "out of date", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["過時的","已到期的"] ] }
    ],
    examples: [
      { en:"The software is out of date and needs to be updated immediately.", zh:"這套軟體已經過時了，需要立即更新。" }
    ]
  },
  {
    id: "w585", english: "overlook", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["忽略","忽視"], ["俯瞰","眺望"] ] }
    ],
    examples: [
      { en:"The manager overlooked a minor error in the report.", zh:"經理忽略了報告中的一個小錯誤。" },
      { en:"The conference room overlooks the harbor.", zh:"這間會議室可以俯瞰港口。" }
    ]
  },
  {
    id: "w586", english: "overnight", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adv", meaningGroups: [ ["一夜之間","突然"] ] },
      { pos: "adj", meaningGroups: [ ["過夜的","隔夜的"] ] }
    ],
    examples: [
      { en:"The company's stock price soared overnight after the announcement.", zh:"公司股價在公告發布後一夜之間飆升。" },
      { en:"We offer overnight delivery for urgent orders.", zh:"我們為緊急訂單提供隔夜到貨服務。" }
    ]
  },
  {
    id: "w587", english: "overtake", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["超越","超過"], ["超車"] ] }
    ],
    examples: [
      { en:"The company's sales overtook those of its main competitor.", zh:"這家公司的銷售額超越了主要競爭對手。" },
      { en:"It is illegal to overtake on this narrow road.", zh:"在這條狹窄的道路上超車是違法的。" }
    ]
  },
  {
    id: "w588", english: "part", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["部分","零件"] ] }
    ],
    examples: [
      { en:"The technician ordered a replacement part for the broken machine.", zh:"技術人員為故障的機器訂了一個替換零件。" }
    ]
  },
  {
    id: "w589", english: "participate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["參與","參加"] ] }
    ],
    examples: [
      { en:"All department heads are expected to participate in the strategic planning meeting.", zh:"所有部門主管都應該參加這次的策略規劃會議。" }
    ]
  },
  {
    id: "w590", english: "participation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["參與"] ] }
    ],
    examples: [
      { en:"Employee participation in the survey was higher than expected.", zh:"員工參與這項調查的比例高於預期。" }
    ]
  },
  {
    id: "w591", english: "particular", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["特別的","特定的"], ["挑剔的","講究的"] ] }
    ],
    examples: [
      { en:"The client requested a particular color for the packaging.", zh:"客戶要求包裝要用特定的顏色。" },
      { en:"He is very particular about how the reports are formatted.", zh:"他對報告的格式非常講究。" }
    ]
  },
  {
    id: "w592", english: "partnership", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["合作關係","合夥"] ] }
    ],
    examples: [
      { en:"The two firms entered into a strategic partnership to expand into new markets.", zh:"這兩家公司建立了戰略合作關係以拓展新市場。" }
    ]
  },
  {
    id: "w593", english: "pass away", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["去世","逝世"] ] }
    ],
    examples: [
      { en:"The company's founder passed away peacefully last week.", zh:"這家公司的創辦人上週安詳地過世了。" }
    ]
  },
  {
    id: "w594", english: "passenger", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["乘客"] ] }
    ],
    examples: [
      { en:"All passengers must present a valid ID before boarding.", zh:"所有乘客登機前都必須出示有效證件。" }
    ]
  },
  {
    id: "w595", english: "passion", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["熱情","熱愛"] ] }
    ],
    examples: [
      { en:"She has a genuine passion for customer service.", zh:"她對客戶服務有著真正的熱情。" }
    ]
  },
  {
    id: "w596", english: "patience", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["耐心","忍耐"] ] }
    ],
    examples: [
      { en:"Handling difficult clients requires a great deal of patience.", zh:"應付難相處的客戶需要極大的耐心。" }
    ]
  },
  {
    id: "w597", english: "percent", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["百分之…"] ] }
    ],
    examples: [
      { en:"Sales increased by ten percent compared to last year.", zh:"銷售額比去年增加了百分之十。" }
    ]
  },
  {
    id: "w598", english: "percentage", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["百分比","比例"] ] }
    ],
    examples: [
      { en:"Only a small percentage of applicants passed the final interview.", zh:"只有一小部分的應徵者通過了最終面試。" }
    ]
  },
  {
    id: "w599", english: "performance", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["表現","績效"], ["表演"], ["性能"] ] }
    ],
    examples: [
      { en:"Her performance during the last quarter earned her a promotion.", zh:"她上一季的績效表現讓她獲得了升遷。" },
      { en:"The theater held a special performance for corporate sponsors.", zh:"這家劇院為企業贊助商舉辦了一場特別表演。" },
      { en:"Engineers tested the engine's performance under extreme temperatures.", zh:"工程師測試了引擎在極端溫度下的性能。" }
    ]
  },
  {
    id: "w600", english: "performer", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["表演者"], ["表現優異者","佼佼者"] ] }
    ],
    examples: [
      { en:"The theater hired several talented performers for the annual show.", zh:"這家劇院為年度演出聘請了幾位有才華的表演者。" },
      { en:"She has consistently been the top performer on the sales team.", zh:"她一直是銷售團隊中表現最優異的人。" }
    ]
  },
  {
    id: "w601", english: "period", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["期間","時期"] ] }
    ],
    examples: [
      { en:"Sales are expected to rise during the holiday period.", zh:"假期期間銷售額預期會上升。" }
    ]
  },
  {
    id: "w602", english: "personality", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["個性","人格"] ] }
    ],
    examples: [
      { en:"The recruiter looks for candidates with a strong, outgoing personality.", zh:"招募人員會找個性強烈且外向的應徵者。" }
    ]
  },
  {
    id: "w603", english: "pest", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["害蟲"] ] }
    ],
    examples: [
      { en:"The restaurant hired a company to control pests in the kitchen.", zh:"這家餐廳聘請了一家公司來控制廚房裡的害蟲。" }
    ]
  },
  {
    id: "w604", english: "petal", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["花瓣"] ] }
    ],
    examples: [
      { en:"The florist carefully arranged each petal to create the bouquet.", zh:"花藝師細心地排列每一片花瓣來製作花束。" }
    ]
  },
  {
    id: "w605", english: "physically", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adv", meaningGroups: [ ["身體上地","體力上地"], ["實際上","實體上"] ] }
    ],
    examples: [
      { en:"The job requires employees to be physically fit.", zh:"這份工作要求員工必須有良好的體能。" },
      { en:"Although the team works remotely, they meet physically once a month.", zh:"雖然團隊採遠端工作，他們每個月還是會實際見面一次。" }
    ]
  },
{
    id: "w606", english: "pioneer", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["先驅","開拓者"] ] },
      { pos: "vt", meaningGroups: [ ["開創","首創"] ] }
    ],
    examples: [
      { en:"She was a pioneer in the field of renewable energy.", zh:"她是可再生能源領域的先驅。" },
      { en:"The firm pioneered a new approach to customer service.", zh:"這家公司首創了一種新的客服方式。" }
    ]
  },
  {
    id: "w607", english: "pit", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["坑洞","礦坑"] ] },
      { pos: "vt", meaningGroups: [ ["使…對抗","使…競爭"] ] }
    ],
    examples: [
      { en:"The mining company dug a new pit to extract coal.", zh:"這家採礦公司開挖了一個新礦坑來開採煤炭。" },
      { en:"The auction pitted several bidders against one another.", zh:"這場拍賣讓幾位競標者互相競爭。" }
    ]
  },
  {
    id: "w608", english: "pleasure", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["樂趣","愉快"] ] }
    ],
    examples: [
      { en:"It's a pleasure to work with such a dedicated team.", zh:"與如此敬業的團隊合作是一種樂趣。" }
    ]
  },
  {
    id: "w609", english: "plentiful", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["豐富的","充足的"] ] }
    ],
    examples: [
      { en:"Job opportunities in the tech sector remain plentiful this year.", zh:"今年科技產業的工作機會依然十分充足。" }
    ]
  },
  {
    id: "w610", english: "plenty", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["大量","充足的量"] ] }
    ],
    examples: [
      { en:"The company has plenty of resources to expand overseas.", zh:"這家公司有充足的資源可以拓展海外業務。" }
    ]
  },
  {
    id: "w611", english: "plug", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["插頭"] ] },
      { pos: "vt", meaningGroups: [ ["堵塞","塞住"] ] }
    ],
    examples: [
      { en:"Make sure the plug is inserted correctly into the socket.", zh:"請確保插頭正確插入插座。" },
      { en:"Workers plugged the leak in the pipeline immediately.", zh:"工人立刻堵住了管線的漏洞。" }
    ]
  },
  {
    id: "w612", english: "plum", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["李子","梅子"] ] },
      { pos: "adj", meaningGroups: [ ["極佳的","令人稱羨的"] ] }
    ],
    examples: [
      { en:"The orchard produces plums, peaches, and apricots every summer.", zh:"這座果園每年夏天生產李子、桃子和杏子。" },
      { en:"She landed a plum assignment managing the Tokyo office.", zh:"她獲得了一個令人稱羨的職位，負責管理東京辦事處。" }
    ]
  },
  {
    id: "w613", english: "plumber", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["水管工人"] ] }
    ],
    examples: [
      { en:"We called a plumber to fix the leaking pipe in the office kitchen.", zh:"我們請了一位水管工人來修理辦公室廚房裡漏水的管子。" }
    ]
  },
  {
    id: "w614", english: "political", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["政治的"] ] }
    ],
    examples: [
      { en:"The merger faces several political obstacles before approval.", zh:"這次合併在獲得批准前面臨幾項政治上的障礙。" }
    ]
  },
  {
    id: "w615", english: "popularity", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["人氣","受歡迎程度"] ] }
    ],
    examples: [
      { en:"The new smartphone model gained popularity quickly among young consumers.", zh:"這款新手機在年輕消費者間迅速獲得高人氣。" }
    ]
  },
  {
    id: "w616", english: "possess", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["擁有","具有"] ] }
    ],
    examples: [
      { en:"Candidates must possess at least three years of relevant experience.", zh:"應徵者必須具備至少三年的相關經驗。" }
    ]
  },
  {
    id: "w617", english: "post", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["職位","崗位"] ] },
      { pos: "vt", meaningGroups: [ ["公布","張貼"] ] }
    ],
    examples: [
      { en:"She was appointed to the post of regional sales director.", zh:"她被任命為區域銷售總監一職。" },
      { en:"The HR department posted the job opening on the company website.", zh:"人資部門在公司網站上公布了這個職缺。" }
    ]
  },
  {
    id: "w618", english: "powdered", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["粉狀的"] ] }
    ],
    examples: [
      { en:"The recipe calls for powdered sugar instead of granulated sugar.", zh:"這份食譜需要用糖粉而不是砂糖。" }
    ]
  },
  {
    id: "w619", english: "powerful", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["強大的","有影響力的"] ] }
    ],
    examples: [
      { en:"The CEO is one of the most powerful figures in the industry.", zh:"這位執行長是業界最具影響力的人物之一。" }
    ]
  },
  {
    id: "w620", english: "practical", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["實用的","務實的"] ] }
    ],
    examples: [
      { en:"We need a practical solution that fits within our budget.", zh:"我們需要一個符合預算的實用解決方案。" }
    ]
  },
  {
    id: "w621", english: "prayer", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["禱告","祈禱"] ] }
    ],
    examples: [
      { en:"The community held a prayer service after the disaster.", zh:"社區在災難發生後舉行了一場祈禱儀式。" }
    ]
  },
  {
    id: "w622", english: "precious", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["珍貴的","寶貴的"] ] }
    ],
    examples: [
      { en:"Time is precious during the final stage of contract negotiations.", zh:"在合約談判的最後階段，時間非常寶貴。" }
    ]
  },
  {
    id: "w623", english: "preferable", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["更合適的","較好的"] ] }
    ],
    examples: [
      { en:"A direct flight is preferable to one with multiple layovers.", zh:"直飛班機比需要多次轉機的班機更為理想。" }
    ]
  },
  {
    id: "w624", english: "pregnant", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["懷孕的"] ] }
    ],
    examples: [
      { en:"The company offers extended leave for pregnant employees.", zh:"公司為懷孕的員工提供延長的休假。" }
    ]
  },
  {
    id: "w625", english: "preparation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["準備"] ] }
    ],
    examples: [
      { en:"Careful preparation is essential before any client presentation.", zh:"在任何客戶簡報之前，仔細的準備都是必要的。" }
    ]
  },
  {
    id: "w626", english: "preserves", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["果醬","蜜餞"] ] }
    ],
    examples: [
      { en:"She brought homemade strawberry preserves as a gift.", zh:"她帶了自製的草莓果醬當禮物。" }
    ]
  },
  {
    id: "w627", english: "president", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["總裁","董事長"] ] }
    ],
    examples: [
      { en:"The president of the company announced a new expansion plan.", zh:"公司總裁宣布了一項新的擴張計畫。" }
    ]
  },
  {
    id: "w628", english: "press", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["按","壓"] ] },
      { pos: "nc", meaningGroups: [ ["新聞界","媒體"] ] }
    ],
    examples: [
      { en:"Please press the red button to stop the machine.", zh:"請按下紅色按鈕以停止機器運轉。" },
      { en:"The press was invited to cover the product launch.", zh:"媒體受邀報導這次的產品發表會。" }
    ]
  },
  {
    id: "w629", english: "pressure", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["壓力"] ] }
    ],
    examples: [
      { en:"Employees are under a lot of pressure to meet the deadline.", zh:"員工承受著很大的壓力要在期限內完成任務。" }
    ]
  },
  {
    id: "w630", english: "previous", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["先前的","之前的"] ] }
    ],
    examples: [
      { en:"Please refer to the previous report for background information.", zh:"請參閱先前的報告以了解背景資訊。" }
    ]
  },
  {
    id: "w631", english: "print", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["印刷","列印"] ] },
      { pos: "nu", meaningGroups: [ ["印刷品"] ] }
    ],
    examples: [
      { en:"Please print three copies of the contract for signing.", zh:"請將合約列印三份供簽署。" },
      { en:"The article was finally available in print last week.", zh:"這篇文章上週終於以印刷品形式發行。" }
    ]
  },
  {
    id: "w632", english: "privacy", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["隱私"] ] }
    ],
    examples: [
      { en:"The company updated its policy to better protect customer privacy.", zh:"公司更新了政策以更好地保護客戶隱私。" }
    ]
  },
  {
    id: "w633", english: "privilege", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["特權","權利"] ] }
    ],
    examples: [
      { en:"Senior employees enjoy the privilege of flexible working hours.", zh:"資深員工享有彈性工時的特權。" }
    ]
  },
  {
    id: "w634", english: "proceed", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["繼續進行","前進"] ] }
    ],
    examples: [
      { en:"Once the contract is signed, we can proceed with the project.", zh:"合約一經簽署，我們就可以繼續進行這個專案。" }
    ]
  },
  {
    id: "w635", english: "production", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["生產","製造"] ] }
    ],
    examples: [
      { en:"The factory increased production to meet holiday demand.", zh:"工廠提高了產量以滿足假期需求。" }
    ]
  },
  {
    id: "w636", english: "productive", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["有生產力的","有成效的"] ] }
    ],
    examples: [
      { en:"The meeting was highly productive and resolved several issues.", zh:"這場會議非常有成效，解決了幾個問題。" }
    ]
  },
  {
    id: "w637", english: "professional", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["專業的"] ] },
      { pos: "nc", meaningGroups: [ ["專業人士"] ] }
    ],
    examples: [
      { en:"She always maintains a professional attitude with clients.", zh:"她對客戶總是保持專業的態度。" },
      { en:"The firm hired several IT professionals last quarter.", zh:"這家公司上個季度雇用了幾位IT專業人士。" }
    ]
  },
  {
    id: "w638", english: "profit", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["利潤"] ] },
      { pos: "vi", meaningGroups: [ ["獲利","得益"] ] }
    ],
    examples: [
      { en:"The company reported a record profit this quarter.", zh:"公司本季度公布了創紀錄的利潤。" },
      { en:"Small investors also profited from the market rally.", zh:"小型投資者也從這波市場上漲中獲利。" }
    ]
  },
  {
    id: "w639", english: "profitable", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["有利可圖的","獲利的"] ] }
    ],
    examples: [
      { en:"The new product line proved to be highly profitable.", zh:"這條新產品線證明非常有利可圖。" }
    ]
  },
  {
    id: "w640", english: "progress", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["進展"] ] },
      { pos: "vi", meaningGroups: [ ["進展","前進"] ] }
    ],
    examples: [
      { en:"The team has made significant progress on the merger.", zh:"團隊在合併案上取得了顯著的進展。" },
      { en:"Negotiations progressed smoothly throughout the week.", zh:"談判在這一週進展順利。" }
    ]
  },
  {
    id: "w641", english: "project", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["專案","計畫"] ] },
      { pos: "vt", meaningGroups: [ ["預測","估計"] ] }
    ],
    examples: [
      { en:"The construction project is scheduled to finish next spring.", zh:"這項建案預計明年春天完工。" },
      { en:"Analysts project a 5% increase in sales next year.", zh:"分析師預測明年銷售額將增加百分之五。" }
    ]
  },
  {
    id: "w642", english: "prominent", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["顯著的","著名的"] ] }
    ],
    examples: [
      { en:"He is a prominent figure in the financial industry.", zh:"他是金融業中一位著名的人物。" }
    ]
  },
  {
    id: "w643", english: "promise", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["承諾","保證"] ] },
      { pos: "nc", meaningGroups: [ ["承諾"] ] }
    ],
    examples: [
      { en:"The supplier promised to deliver the goods by Friday.", zh:"供應商承諾週五前交貨。" },
      { en:"She kept her promise to finish the report on time.", zh:"她如期完成了報告，信守了自己的承諾。" }
    ]
  },
  {
    id: "w644", english: "promotional", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["促銷的","宣傳的"] ] }
    ],
    examples: [
      { en:"The store is running a promotional campaign for the new product.", zh:"這家商店正在為新產品進行促銷活動。" }
    ]
  },
  {
    id: "w645", english: "prompt", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["迅速的","準時的"] ] },
      { pos: "vt", meaningGroups: [ ["促使","引起"] ] }
    ],
    examples: [
      { en:"We appreciate your prompt response to our inquiry.", zh:"我們很感謝您對我們詢問的迅速回覆。" },
      { en:"The customer complaints prompted the company to revise its policy.", zh:"顧客的抱怨促使公司修訂了政策。" }
    ]
  },
  {
    id: "w646", english: "proof", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["證明","證據"] ] }
    ],
    examples: [
      { en:"Please provide proof of purchase to request a refund.", zh:"請提供購買證明以申請退款。" }
    ]
  },
  {
    id: "w647", english: "property", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["房地產","財產"] ] },
      { pos: "nu", meaningGroups: [ ["特性","屬性"] ] }
    ],
    examples: [
      { en:"The company purchased a new property downtown for its headquarters.", zh:"這家公司在市中心購買了一處新的房地產作為總部。" },
      { en:"This material has unique properties that resist heat.", zh:"這種材料具有耐熱的特性。" }
    ]
  },
  {
    id: "w648", english: "prosperous", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["繁榮的","興旺的"] ] }
    ],
    examples: [
      { en:"The region has become increasingly prosperous since the trade agreement.", zh:"自貿易協定簽署以來，這個地區變得越來越繁榮。" }
    ]
  },
  {
    id: "w649", english: "proudly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adv", meaningGroups: [ ["自豪地","驕傲地"] ] }
    ],
    examples: [
      { en:"The team proudly presented their annual achievements to the board.", zh:"團隊自豪地向董事會展示了他們的年度成就。" }
    ]
  },
  {
    id: "w650", english: "prove", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["證明"] ] }
    ],
    examples: [
      { en:"The audit proved that the accounts were accurate.", zh:"審計證明了帳目是準確的。" }
    ]
  },
  {
    id: "w651", english: "psychological", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["心理的"] ] }
    ],
    examples: [
      { en:"Job security has a strong psychological impact on employee morale.", zh:"工作保障對員工士氣有很大的心理影響。" }
    ]
  },
  {
    id: "w652", english: "psychology", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["心理學"] ] }
    ],
    examples: [
      { en:"Understanding consumer psychology helps marketers design better campaigns.", zh:"了解消費者心理有助於行銷人員設計更好的行銷活動。" }
    ]
  },
  {
    id: "w653", english: "public", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["公開的","公共的"] ] },
      { pos: "nu", meaningGroups: [ ["公眾"] ] }
    ],
    examples: [
      { en:"The company issued a public statement about the recall.", zh:"公司針對這次召回發布了一份公開聲明。" },
      { en:"The product will not be available to the public until next month.", zh:"這項產品要到下個月才會開放給大眾購買。" }
    ]
  },
  {
    id: "w654", english: "publication", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["出版"] ] },
      { pos: "nc", meaningGroups: [ ["出版物","刊物"] ] }
    ],
    examples: [
      { en:"The report is scheduled for publication early next year.", zh:"這份報告預計於明年初出版。" },
      { en:"The magazine is a well-known publication in the finance industry.", zh:"這本雜誌是金融業中知名的刊物。" }
    ]
  },
  {
    id: "w655", english: "publicity", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["宣傳","公眾關注"] ] }
    ],
    examples: [
      { en:"The scandal generated a lot of negative publicity for the brand.", zh:"這起醜聞為該品牌帶來了大量負面的公眾關注。" }
    ]
  },
  {
    id: "w656", english: "publish", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["出版","發表"] ] }
    ],
    examples: [
      { en:"The company will publish its annual report next week.", zh:"公司將於下週發表年度報告。" }
    ]
  },
  {
    id: "w657", english: "punch", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["打孔","沖壓"], ["出拳打"] ] },
      { pos: "nc", meaningGroups: [ ["一拳"] ] }
    ],
    examples: [
      { en:"Use this machine to punch holes in the metal sheets.", zh:"使用這台機器在金屬板上打孔。" },
      { en:"The boxer landed a strong punch in the final round.", zh:"這位拳擊手在最後一輪打出了有力的一拳。" }
    ]
  },
  {
    id: "w658", english: "pursue", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["追求","從事"] ] }
    ],
    examples: [
      { en:"She decided to pursue a career in international marketing.", zh:"她決定從事國際行銷相關的職業。" }
    ]
  },
  {
    id: "w659", english: "pursuit", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["追求"] ] }
    ],
    examples: [
      { en:"The company's pursuit of innovation led to several new patents.", zh:"公司對創新的追求帶來了好幾項新專利。" }
    ]
  },
  {
    id: "w660", english: "put sth. into motion", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["使…開始進行","啟動"] ] }
    ],
    examples: [
      { en:"The manager put the new marketing plan into motion immediately.", zh:"經理立即啟動了這項新的行銷計畫。" }
    ]
  },
  {
    id: "w661", english: "quality", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["品質"] ] },
      { pos: "nc", meaningGroups: [ ["特質"] ] }
    ],
    examples: [
      { en:"The factory implemented strict quality control measures.", zh:"工廠實施了嚴格的品質管控措施。" },
      { en:"Honesty is an important quality in a good leader.", zh:"誠實是優秀領導者的重要特質。" }
    ]
  },
  {
    id: "w662", english: "raise", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["提高","提出"] ] },
      { pos: "nc", meaningGroups: [ ["加薪"] ] }
    ],
    examples: [
      { en:"The manager raised concerns about the shrinking budget.", zh:"經理對日益縮減的預算提出了擔憂。" },
      { en:"She received a raise after her excellent performance review.", zh:"她在績效考核表現優異後獲得了加薪。" }
    ]
  },
  {
    id: "w663", english: "raisin", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["葡萄乾"] ] }
    ],
    examples: [
      { en:"The bakery uses raisins in its signature bread recipe.", zh:"這家麵包店在招牌麵包食譜中使用了葡萄乾。" }
    ]
  },
  {
    id: "w664", english: "range", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["範圍","系列"] ] },
      { pos: "vi", meaningGroups: [ ["範圍涵蓋"] ] }
    ],
    examples: [
      { en:"The store offers a wide range of office supplies.", zh:"這家商店提供各式各樣的辦公用品。" },
      { en:"Prices range from $10 to $50 depending on the size.", zh:"價格依尺寸從十美元到五十美元不等。" }
    ]
  },
  {
    id: "w665", english: "razor", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["剃刀"] ] }
    ],
    examples: [
      { en:"The company launched a new line of razors for sensitive skin.", zh:"這家公司推出了一系列適合敏感肌膚的剃刀新品。" }
    ]
  },
  {
    id: "w666", english: "reach", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["達到","抵達"], ["聯繫上"] ] }
    ],
    examples: [
      { en:"The two companies finally reached an agreement after months of negotiation.", zh:"經過數月談判，兩家公司終於達成協議。" },
      { en:"You can reach me by phone during business hours.", zh:"上班時間你可以透過電話聯繫我。" }
    ]
  },
  {
    id: "w667", english: "reason", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["原因","理由"] ] }
    ],
    examples: [
      { en:"The main reason for the delay was a shortage of raw materials.", zh:"延誤的主要原因是原材料短缺。" }
    ]
  },
  {
    id: "w668", english: "reasonable", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["合理的"] ] }
    ],
    examples: [
      { en:"The client requested a more reasonable price for the service.", zh:"客戶要求提供更合理的服務價格。" }
    ]
  },
  {
    id: "w669", english: "recent", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["最近的"] ] }
    ],
    examples: [
      { en:"According to a recent survey, remote work has increased productivity.", zh:"根據最近的一項調查，遠距工作提高了生產力。" }
    ]
  },
  {
    id: "w670", english: "recognition", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["認可","表揚"] ] }
    ],
    examples: [
      { en:"The employee received recognition for her outstanding sales performance.", zh:"這位員工因銷售表現優異而獲得表揚。" }
    ]
  },
  {
    id: "w671", english: "recover", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["恢復","復原"] ] }
    ],
    examples: [
      { en:"The stock market began to recover after the announcement.", zh:"股市在宣布消息後開始回升。" }
    ]
  },
  {
    id: "w672", english: "reference", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["參考"], ["推薦人","介紹信"] ] },
      { pos: "vt", meaningGroups: [ ["提及","引用"] ] }
    ],
    examples: [
      { en:"Please list two professional references on your application.", zh:"請在申請表上列出兩位職業推薦人。" },
      { en:"The report referenced several studies on consumer behavior.", zh:"這份報告引用了幾項有關消費者行為的研究。" }
    ]
  },
  {
    id: "w673", english: "referral", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["推薦","轉介"] ] }
    ],
    examples: [
      { en:"We received several new clients through referral this month.", zh:"這個月我們透過推薦介紹獲得了幾位新客戶。" }
    ]
  },
  {
    id: "w674", english: "regarding", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "prep", meaningGroups: [ ["關於"] ] }
    ],
    examples: [
      { en:"Please contact HR regarding your benefits enrollment.", zh:"關於您的福利加入事宜，請聯絡人資部門。" }
    ]
  },
  {
    id: "w675", english: "region", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["地區","區域"] ] }
    ],
    examples: [
      { en:"Sales in the Asia-Pacific region grew by 15 percent last year.", zh:"去年亞太地區的銷售額成長了百分之十五。" }
    ]
  },
  {
    id: "w676", english: "regulation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["法規","規定"] ] }
    ],
    examples: [
      { en:"All employees must comply with the new safety regulations.", zh:"所有員工都必須遵守新的安全法規。" }
    ]
  },
  {
    id: "w677", english: "relate to", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["與…有關","涉及"] ] }
    ],
    examples: [
      { en:"This clause relates to the confidentiality of client data.", zh:"這項條款與客戶資料的保密性有關。" }
    ]
  },
  {
    id: "w678", english: "relation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["關係"] ] }
    ],
    examples: [
      { en:"The two departments maintain a good working relation.", zh:"這兩個部門維持著良好的合作關係。" }
    ]
  },
  {
    id: "w679", english: "release", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["發布","發行"] ] },
      { pos: "nc", meaningGroups: [ ["新聞稿"] ] }
    ],
    examples: [
      { en:"The company will release its new product next month.", zh:"公司將於下個月發布新產品。" },
      { en:"The press release announced the merger details.", zh:"這份新聞稿宣布了合併的細節。" }
    ]
  },
  {
    id: "w680", english: "relieved", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["安心的","放心的"] ] }
    ],
    examples: [
      { en:"She felt relieved after passing the final inspection.", zh:"通過最終檢驗後，她感到很安心。" }
    ]
  },
  {
    id: "w681", english: "rely", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["依靠","依賴"] ] }
    ],
    examples: [
      { en:"The company relies heavily on overseas suppliers.", zh:"這家公司高度依賴海外供應商。" }
    ]
  },
  {
    id: "w682", english: "remain", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["保持","仍然是"] ] }
    ],
    examples: [
      { en:"Despite the setback, sales figures remained strong.", zh:"儘管遇到挫折，銷售數字依然強勁。" }
    ]
  },
  {
    id: "w683", english: "remarkable", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["卓越的","顯著的"] ] }
    ],
    examples: [
      { en:"The team achieved remarkable results in a short period.", zh:"團隊在短時間內取得了卓越的成果。" }
    ]
  },
  {
    id: "w684", english: "remote", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["遠端的","偏遠的"] ] }
    ],
    examples: [
      { en:"The company adopted a remote work policy for all staff.", zh:"這家公司為全體員工採用了遠端工作政策。" }
    ]
  },
  {
    id: "w685", english: "rented", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["租用的","出租的"] ] }
    ],
    examples: [
      { en:"The team used a rented van to transport the equipment.", zh:"團隊使用一輛租來的貨車運送設備。" }
    ]
  },
  {
    id: "w686", english: "replace", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["更換","取代"] ] }
    ],
    examples: [
      { en:"The old printer was replaced with a more efficient model.", zh:"舊印表機被一台更有效率的機型取代了。" }
    ]
  },
  {
    id: "w687", english: "report", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["報告"] ] },
      { pos: "vt", meaningGroups: [ ["報告","報導"] ] }
    ],
    examples: [
      { en:"Please submit your monthly report by Friday.", zh:"請於週五前提交你的月報。" },
      { en:"The accountant reported an error in the budget.", zh:"會計師報告了預算中的一個錯誤。" }
    ]
  },
  {
    id: "w688", english: "reporter", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["記者"] ] }
    ],
    examples: [
      { en:"A reporter interviewed the CEO after the press conference.", zh:"一位記者在記者會後採訪了執行長。" }
    ]
  },
  {
    id: "w689", english: "represent", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["代表"] ] }
    ],
    examples: [
      { en:"She was chosen to represent the company at the trade fair.", zh:"她被選為在貿易展上代表公司。" }
    ]
  },
  {
    id: "w690", english: "representation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["代表","代表權"] ] }
    ],
    examples: [
      { en:"The union ensures fair representation for all workers.", zh:"工會確保所有工人都能獲得公平的代表權。" }
    ]
  },
  {
    id: "w691", english: "reputation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["名聲","聲譽"] ] }
    ],
    examples: [
      { en:"The firm has built a solid reputation for quality service.", zh:"這家公司因優質服務而建立了良好的聲譽。" }
    ]
  },
  {
    id: "w692", english: "research", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["研究"] ] },
      { pos: "vt", meaningGroups: [ ["研究","調查"] ] }
    ],
    examples: [
      { en:"The team conducted extensive research before launching the product.", zh:"團隊在產品上市前進行了廣泛的研究。" },
      { en:"Analysts researched consumer trends before making recommendations.", zh:"分析師在提出建議之前研究了消費者趨勢。" }
    ]
  },
  {
    id: "w693", english: "researcher", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["研究員"] ] }
    ],
    examples: [
      { en:"The lab hired two new researchers this semester.", zh:"這間實驗室這學期聘請了兩位新的研究員。" }
    ]
  },
  {
    id: "w694", english: "reservation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["預訂"] ] }
    ],
    examples: [
      { en:"I'd like to make a reservation for a table of four.", zh:"我想預訂一張四人桌。" }
    ]
  },
  {
    id: "w695", english: "resident", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["居民"] ] },
      { pos: "adj", meaningGroups: [ ["常駐的"] ] }
    ],
    examples: [
      { en:"Local residents complained about the noise from construction.", zh:"當地居民抱怨施工噪音。" },
      { en:"The hotel has a resident chef who creates seasonal menus.", zh:"這家飯店有一位常駐主廚，負責製作季節菜單。" }
    ]
  },
  {
    id: "w696", english: "resign", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["辭職"] ] }
    ],
    examples: [
      { en:"She resigned from her position as marketing director.", zh:"她辭去了行銷總監的職位。" }
    ]
  },
  {
    id: "w697", english: "resolve", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["解決"] ] }
    ],
    examples: [
      { en:"The two parties resolved their dispute out of court.", zh:"雙方在法庭外解決了他們的爭議。" }
    ]
  },
  {
    id: "w698", english: "resource", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["資源"] ] }
    ],
    examples: [
      { en:"The department lacks the resources to complete the project on time.", zh:"該部門缺乏資源以準時完成這項專案。" }
    ]
  },
  {
    id: "w699", english: "respectable", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["體面的","可觀的"] ] }
    ],
    examples: [
      { en:"The company reported a respectable profit despite the economic downturn.", zh:"儘管經濟不景氣，這家公司仍公布了一筆可觀的利潤。" }
    ]
  },
  {
    id: "w700", english: "response", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["回應"] ] }
    ],
    examples: [
      { en:"We received a positive response from most customers.", zh:"我們從大多數顧客那裡得到了積極的回應。" }
    ]
  },
  {
    id: "w701", english: "result", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["結果"] ] },
      { pos: "vi", meaningGroups: [ ["導致","造成"] ] }
    ],
    examples: [
      { en:"The survey results showed a rise in customer satisfaction.", zh:"調查結果顯示顧客滿意度上升。" },
      { en:"The delay resulted from a shortage of parts.", zh:"這次延誤是由零件短缺造成的。" }
    ]
  },
  {
    id: "w702", english: "retail", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["零售"] ] },
      { pos: "vi", meaningGroups: [ ["以零售價出售"] ] }
    ],
    examples: [
      { en:"The company plans to expand into the retail sector.", zh:"這家公司計劃拓展到零售業。" },
      { en:"The device retails for around $200.", zh:"這款裝置的零售價約為兩百美元。" }
    ]
  },
  {
    id: "w703", english: "rising", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["上升的","上漲的"] ] }
    ],
    examples: [
      { en:"Rising fuel prices are affecting shipping costs.", zh:"上漲的燃油價格正在影響運輸成本。" }
    ]
  },
  {
    id: "w704", english: "risky", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["冒險的","有風險的"] ] }
    ],
    examples: [
      { en:"Investing in a new market can be risky without proper research.", zh:"沒有適當的研究，投資新市場可能是有風險的。" }
    ]
  },
  {
    id: "w705", english: "roasted", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["烘烤的","烘焙的"] ] }
    ],
    examples: [
      { en:"The cafe is famous for its freshly roasted coffee beans.", zh:"這家咖啡店以新鮮烘焙的咖啡豆聞名。" }
    ]
  },
  {
    id: "w706", english: "role", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["角色","職務"] ] }
    ],
    examples: [
      { en:"He took on a leadership role in the new division.", zh:"他在新部門中擔任了領導角色。" }
    ]
  },
  {
    id: "w707", english: "roll", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["滾動"] ] },
      { pos: "nc", meaningGroups: [ ["名冊"] ] }
    ],
    examples: [
      { en:"The cart rolled down the ramp toward the loading dock.", zh:"推車沿著斜坡滾向裝卸區。" },
      { en:"New employees are added to the payroll after orientation.", zh:"新員工在完成新人訓練後會被加入薪資名冊。" }
    ]
  },
  {
    id: "w708", english: "romantic", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["浪漫的"] ] }
    ],
    examples: [
      { en:"The resort is a popular spot for romantic getaways.", zh:"這座度假村是浪漫小旅行的熱門地點。" }
    ]
  },
  {
    id: "w709", english: "roughly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adv", meaningGroups: [ ["大約","粗略地"] ] }
    ],
    examples: [
      { en:"The project will cost roughly two million dollars.", zh:"這項專案大約要花費兩百萬美元。" }
    ]
  },
  {
    id: "w710", english: "routine", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["常規","慣例"] ] },
      { pos: "adj", meaningGroups: [ ["例行的"] ] }
    ],
    examples: [
      { en:"Filing reports has become part of her daily routine.", zh:"填寫報告已成為她每天例行工作的一部分。" },
      { en:"The company conducts routine inspections of its facilities.", zh:"這家公司對其設施進行例行檢查。" }
    ]
  },
  {
    id: "w711", english: "ruin", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["破壞","毀壞"] ] },
      { pos: "nc", meaningGroups: [ ["廢墟"] ] }
    ],
    examples: [
      { en:"A single mistake ruined the entire shipment.", zh:"一個小錯誤就毀了整批貨物。" },
      { en:"The old factory was left in ruins after the fire.", zh:"那座舊工廠在火災後成了廢墟。" }
    ]
  },
  {
    id: "w712", english: "rumor", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["謠言","傳聞"] ] }
    ],
    examples: [
      { en:"There have been rumors of a merger between the two firms.", zh:"有傳聞說這兩家公司即將合併。" }
    ]
  },
  {
    id: "w713", english: "rural", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["鄉村的","農村的"] ] }
    ],
    examples: [
      { en:"The company opened a new branch in a rural area to cut costs.", zh:"這家公司在鄉村地區開設了一家新分店以降低成本。" }
    ]
  },
  {
    id: "w714", english: "safely", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adv", meaningGroups: [ ["安全地"] ] }
    ],
    examples: [
      { en:"Please make sure all equipment is stored safely before leaving.", zh:"離開前請確保所有設備都安全存放好。" }
    ]
  },
  {
    id: "w715", english: "satisfy", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["滿足","使滿意"] ] }
    ],
    examples: [
      { en:"The new policy was designed to satisfy customer demands.", zh:"這項新政策旨在滿足客戶的需求。" }
    ]
  },
  {
    id: "w716", english: "sausage", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["香腸"] ] }
    ],
    examples: [
      { en:"The catering company served sausages at the company picnic.", zh:"外燴公司在公司野餐時提供了香腸。" }
    ]
  },
  {
    id: "w717", english: "scarce", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["稀少的","缺乏的"] ] }
    ],
    examples: [
      { en:"Skilled workers are becoming scarce in this industry.", zh:"熟練工人在這個行業中變得越來越稀少。" }
    ]
  },
  {
    id: "w718", english: "scary", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["可怕的","令人害怕的"] ] }
    ],
    examples: [
      { en:"Losing such a major client was a scary prospect for the firm.", zh:"失去這麼重要的客戶對這家公司來說是件可怕的事。" }
    ]
  },
  {
    id: "w719", english: "scatter", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["分散","散開"] ] }
    ],
    examples: [
      { en:"The documents scattered across the floor when the box fell.", zh:"箱子掉落時，文件散落在地板上。" }
    ]
  },
  {
    id: "w720", english: "scoop", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["挖取","舀取"] ] },
      { pos: "nc", meaningGroups: [ ["獨家新聞"] ] }
    ],
    examples: [
      { en:"She scooped the ice cream into a cup for the customer.", zh:"她把冰淇淋舀進杯子裡給顧客。" },
      { en:"The reporter got the scoop on the company's upcoming merger.", zh:"這位記者搶先獲得了該公司即將合併的獨家新聞。" }
    ]
  },
  {
    id: "w721", english: "sculpture", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["雕塑"] ] }
    ],
    examples: [
      { en:"A large sculpture was installed in the lobby of the new building.", zh:"新大樓的大廳裡安裝了一座大型雕塑。" }
    ]
  },
  {
    id: "w722", english: "seal", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["密封","封住"], ["敲定","確定"] ] },
      { pos: "nc", meaningGroups: [ ["印章","封條"] ] }
    ],
    examples: [
      { en:"Both parties sealed the deal with a handshake.", zh:"雙方以握手敲定了這筆交易。" },
      { en:"The document bears the official seal of the ministry.", zh:"這份文件蓋有該部門的官方印章。" }
    ]
  },
  {
    id: "w723", english: "security", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["安全","保安"] ] },
      { pos: "nc", meaningGroups: [ ["證券"] ] }
    ],
    examples: [
      { en:"The building has tight security to protect sensitive data.", zh:"這棟大樓有嚴密的保安措施以保護敏感資料。" },
      { en:"The firm specializes in trading government securities.", zh:"這家公司專門從事政府證券交易。" }
    ]
  },
  {
    id: "w724", english: "seek", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["尋求","謀求"] ] }
    ],
    examples: [
      { en:"The company is seeking new investors to fund its expansion.", zh:"這家公司正在尋求新投資者以資助其擴張。" }
    ]
  },
  {
    id: "w725", english: "seize", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["抓住","把握"] ] }
    ],
    examples: [
      { en:"The firm seized the opportunity to enter the emerging market.", zh:"這家公司抓住機會進入了這個新興市場。" }
    ]
  },
  {
    id: "w726", english: "sense", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["感覺","意識"] ] },
      { pos: "vt", meaningGroups: [ ["感覺到","察覺"] ] }
    ],
    examples: [
      { en:"She has a strong sense of responsibility toward her team.", zh:"她對團隊有強烈的責任感。" },
      { en:"The manager sensed that morale was low after the layoffs.", zh:"經理察覺到裁員後士氣低落。" }
    ]
  },
  {
    id: "w727", english: "series", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["系列","連續"] ] }
    ],
    examples: [
      { en:"The company launched a series of workshops for new employees.", zh:"這家公司為新員工推出了一系列的工作坊。" }
    ]
  },
  {
    id: "w728", english: "shampoo", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["洗髮精"] ] }
    ],
    examples: [
      { en:"The store is offering a discount on all shampoo brands this week.", zh:"這家商店本週對所有洗髮精品牌提供折扣。" }
    ]
  },
  {
    id: "w729", english: "shape", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["形狀"] ] },
      { pos: "vt", meaningGroups: [ ["塑造","形成"] ] }
    ],
    examples: [
      { en:"The packaging was redesigned into a more compact shape.", zh:"包裝被重新設計成更緊湊的形狀。" },
      { en:"Customer feedback helped shape the company's new strategy.", zh:"顧客的意見幫助塑造了公司的新策略。" }
    ]
  },
{
    id: "w730", english: "shave", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["剃鬍子","刮毛"] ] }
    ],
    examples: [
      { en:"He shaves every morning before going to the office.", zh:"他每天早上上班前都會刮鬍子。" }
    ]
  },
  {
    id: "w731", english: "shelter", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["避難所","收容所"] ] },
      { pos: "vt", meaningGroups: [ ["庇護","掩護"] ] }
    ],
    examples: [
      { en:"The company set up a temporary shelter for employees during the storm.", zh:"公司在風暴期間為員工設立了臨時避難所。" },
      { en:"The manager sheltered the new intern from criticism during the meeting.", zh:"經理在會議中護著那位新來的實習生，讓她免受批評。" }
    ]
  },
  {
    id: "w732", english: "shiny", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["閃亮的","光亮的"] ] }
    ],
    examples: [
      { en:"The showroom floor was polished until it was shiny.", zh:"展示廳的地板被打磨得閃閃發亮。" }
    ]
  },
  {
    id: "w733", english: "shocked", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["震驚的","驚訝的"] ] }
    ],
    examples: [
      { en:"The staff were shocked by the sudden announcement of layoffs.", zh:"員工們對突然宣布的裁員消息感到震驚。" }
    ]
  },
  {
    id: "w734", english: "shortage", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["短缺","不足"] ] }
    ],
    examples: [
      { en:"The factory is facing a shortage of raw materials this quarter.", zh:"該工廠本季正面臨原料短缺的問題。" }
    ]
  },
  {
    id: "w735", english: "sign", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["簽署"] ] },
      { pos: "nc", meaningGroups: [ ["標誌","招牌"], ["跡象","徵兆"] ] }
    ],
    examples: [
      { en:"Please sign the contract before the end of the week.", zh:"請在本週結束前簽署合約。" },
      { en:"There is a sign outside the store announcing the sale.", zh:"店外有一個招牌宣布促銷活動。" },
      { en:"Rising costs are a sign of inflation.", zh:"成本上升是通貨膨脹的一個徵兆。" }
    ]
  },
  {
    id: "w736", english: "signature style", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["招牌風格","獨特特色"] ] }
    ],
    examples: [
      { en:"The chef's signature style combines local ingredients with French techniques.", zh:"這位主廚的招牌風格是將當地食材與法式技巧結合。" }
    ]
  },
  {
    id: "w737", english: "similar", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["類似的","相似的"] ] }
    ],
    examples: [
      { en:"Our new product has a similar design to last year's model.", zh:"我們的新產品設計與去年的機型相似。" }
    ]
  },
  {
    id: "w738", english: "simply", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adv", meaningGroups: [ ["僅僅","只是"], ["簡單地"] ] }
    ],
    examples: [
      { en:"The project failed simply because of poor planning.", zh:"這個專案失敗只是因為規劃不當。" },
      { en:"She explained the process simply so everyone could understand.", zh:"她把流程解釋得很簡單，讓大家都能理解。" }
    ]
  },
  {
    id: "w739", english: "sincerely", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adv", meaningGroups: [ ["誠摯地"] ] }
    ],
    examples: [
      { en:"The manager sincerely apologized for the delay in shipment.", zh:"經理誠摯地為出貨延遲致歉。" }
    ]
  },
  {
    id: "w740", english: "single", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["單一的","唯一的"], ["單身的","未婚的"] ] }
    ],
    examples: [
      { en:"Please fill out a single form for all your expenses.", zh:"請填寫一張表格來申報所有的費用。" },
      { en:"He remained single throughout his career at the company.", zh:"他在公司工作期間一直保持單身。" }
    ]
  },
  {
    id: "w741", english: "sir", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["先生"] ] }
    ],
    examples: [
      { en:"Excuse me, sir, may I see your boarding pass?", zh:"先生，不好意思，我可以看一下您的登機證嗎？" }
    ]
  },
  {
    id: "w742", english: "site", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["現場","工地"], ["網站"] ] }
    ],
    examples: [
      { en:"All visitors must wear a helmet on the construction site.", zh:"所有訪客在工地上都必須戴安全帽。" },
      { en:"You can find more details on the company's site.", zh:"你可以在公司的網站上找到更多細節。" }
    ]
  },
  {
    id: "w743", english: "situation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["情況","情勢"] ] }
    ],
    examples: [
      { en:"The manager needs to assess the situation before making a decision.", zh:"經理需要先評估情況才能做出決定。" }
    ]
  },
  {
    id: "w744", english: "skeleton", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["骨骼","骷髏"] ] }
    ],
    examples: [
      { en:"The museum displayed a dinosaur skeleton in the main hall.", zh:"博物館在大廳展示了一副恐龍骨骼。" }
    ]
  },
  {
    id: "w745", english: "sketch", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["草圖","素描"] ] },
      { pos: "vt", meaningGroups: [ ["繪製草圖"] ] }
    ],
    examples: [
      { en:"The designer showed us a rough sketch of the new logo.", zh:"設計師給我們看了新標誌的草圖。" },
      { en:"She sketched the layout of the office before the renovation.", zh:"她在裝修前先繪製了辦公室的佈局草圖。" }
    ]
  },
  {
    id: "w746", english: "slice", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["片","一片"] ] },
      { pos: "vt", meaningGroups: [ ["切片"] ] }
    ],
    examples: [
      { en:"He ordered a slice of pizza for lunch.", zh:"他午餐點了一片披薩。" },
      { en:"Please slice the cake into twelve equal pieces.", zh:"請把蛋糕切成十二等份。" }
    ]
  },
  {
    id: "w747", english: "slightly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adv", meaningGroups: [ ["略微","稍微"] ] }
    ],
    examples: [
      { en:"Sales increased slightly compared to last month.", zh:"銷售額比上個月略微增加。" }
    ]
  },
  {
    id: "w748", english: "snap", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["猛然折斷","啪地斷裂"] ] },
      { pos: "nc", meaningGroups: [ ["快照"] ] }
    ],
    examples: [
      { en:"The branch snapped under the weight of the snow.", zh:"樹枝在雪的重量下啪地折斷了。" },
      { en:"She took a quick snap of the whiteboard before the meeting ended.", zh:"她在會議結束前迅速拍了一張白板的快照。" }
    ]
  },
  {
    id: "w749", english: "social", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["社交的","社會的"] ] }
    ],
    examples: [
      { en:"The company organizes social events to boost employee morale.", zh:"公司舉辦社交活動來提升員工士氣。" }
    ]
  },
  {
    id: "w750", english: "solid", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["堅固的","可靠的"] ] },
      { pos: "nc", meaningGroups: [ ["固體"] ] }
    ],
    examples: [
      { en:"The team delivered a solid performance this quarter.", zh:"團隊本季度的表現相當可靠。" },
      { en:"Water turns into a solid when it freezes.", zh:"水結冰後會變成固體。" }
    ]
  },
  {
    id: "w751", english: "somewhat", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adv", meaningGroups: [ ["有點","稍微"] ] }
    ],
    examples: [
      { en:"The client seemed somewhat hesitant about signing the contract.", zh:"客戶對於簽署合約似乎有點猶豫。" }
    ]
  },
  {
    id: "w752", english: "soul", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["靈魂"] ] }
    ],
    examples: [
      { en:"He put his heart and soul into building the business.", zh:"他全心全意投入這項事業。" }
    ]
  },
  {
    id: "w753", english: "spark", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["火花"] ] },
      { pos: "vt", meaningGroups: [ ["引發","激起"] ] }
    ],
    examples: [
      { en:"A single spark from the machine started the fire.", zh:"機器產生的一個火花引起了這場火災。" },
      { en:"The new marketing campaign sparked a lot of interest online.", zh:"這次新的行銷活動在網路上引發了很多關注。" }
    ]
  },
  {
    id: "w754", english: "sparkle", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["閃爍","發光"] ] },
      { pos: "nc", meaningGroups: [ ["光彩","光芒"] ] }
    ],
    examples: [
      { en:"The diamonds sparkled under the showroom lights.", zh:"鑽石在展示廳的燈光下閃閃發光。" },
      { en:"Her presentation had a sparkle that captured the audience's attention.", zh:"她的簡報散發出一種吸引觀眾注意的光彩。" }
    ]
  },
  {
    id: "w755", english: "specialize", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["專攻","專精於"] ] }
    ],
    examples: [
      { en:"Our firm specializes in international trade law.", zh:"我們公司專門處理國際貿易法。" }
    ]
  },
  {
    id: "w756", english: "specific", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["具體的","特定的"] ] }
    ],
    examples: [
      { en:"Please provide specific details about the delay.", zh:"請提供有關延誤的具體細節。" }
    ]
  },
  {
    id: "w757", english: "spell", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["拼寫"] ] },
      { pos: "nc", meaningGroups: [ ["咒語","魔法"], ["一段時間"] ] }
    ],
    examples: [
      { en:"Could you spell your last name for me?", zh:"你能為我拼一下你的姓嗎？" },
      { en:"The witch in the story casts a powerful spell.", zh:"故事裡的女巫施展了一個強大的咒語。" },
      { en:"The region experienced a long spell of dry weather.", zh:"這個地區經歷了一段長時間的乾旱天氣。" }
    ]
  },
  {
    id: "w758", english: "spice up", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["使...更有趣","增添趣味"] ] }
    ],
    examples: [
      { en:"The host added some jokes to spice up the presentation.", zh:"主持人加了一些笑話來讓簡報更有趣。" }
    ]
  },
  {
    id: "w759", english: "spiritual", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["精神上的","心靈的"] ] }
    ],
    examples: [
      { en:"Many employees find spiritual fulfillment outside of work.", zh:"許多員工在工作之外尋求心靈上的滿足。" }
    ]
  },
  {
    id: "w760", english: "spiritually", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adv", meaningGroups: [ ["精神上地","心靈上地"] ] }
    ],
    examples: [
      { en:"The retreat helped the team feel spiritually refreshed.", zh:"這次靜修讓團隊在心靈上感到煥然一新。" }
    ]
  },
  {
    id: "w761", english: "splash", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["潑濺","濺出"] ] },
      { pos: "nc", meaningGroups: [ ["轟動","引人注目的效果"] ] }
    ],
    examples: [
      { en:"Water splashed onto the documents during the flood.", zh:"洪水期間水濺到了文件上。" },
      { en:"The new product made a big splash at the trade show.", zh:"這款新產品在商展上引起了極大關注。" }
    ]
  },
  {
    id: "w762", english: "splendid", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["極好的","壯麗的"] ] }
    ],
    examples: [
      { en:"The clients had a splendid time at the company banquet.", zh:"客戶們在公司的宴會上度過了非常愉快的時光。" }
    ]
  },
  {
    id: "w763", english: "spot", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["地點"], ["斑點"] ] },
      { pos: "vt", meaningGroups: [ ["發現","認出"] ] }
    ],
    examples: [
      { en:"This is a popular spot for business lunches.", zh:"這是一個受歡迎的商務午餐地點。" },
      { en:"The auditor spotted an error in the financial report.", zh:"稽核員在財務報告中發現了一個錯誤。" }
    ]
  },
  {
    id: "w764", english: "spread", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["傳播","散布","蔓延"] ] },
      { pos: "vt", meaningGroups: [ ["散布","傳播"] ] }
    ],
    examples: [
      { en:"The news of the merger spread quickly through the office.", zh:"合併的消息很快就在辦公室裡傳開了。" },
      { en:"Someone spread a rumor about the merger before it was announced.", zh:"有人在合併消息公布前散布了謠言。" }
    ]
  },
  {
    id: "w765", english: "sprinkle", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["撒","灑"] ] }
    ],
    examples: [
      { en:"She sprinkled some sugar on top of the pastries before serving.", zh:"她在端上點心前灑了一些糖。" }
    ]
  },
  {
    id: "w766", english: "stage", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["舞台"], ["階段"] ] },
      { pos: "vt", meaningGroups: [ ["舉辦","策劃"] ] }
    ],
    examples: [
      { en:"The project is still in the early stage of development.", zh:"這個專案還在開發的早期階段。" },
      { en:"The company staged a press conference to announce the merger.", zh:"公司舉辦了一場記者會來宣布合併消息。" }
    ]
  },
  {
    id: "w767", english: "stale", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["不新鮮的","陳舊的"] ] }
    ],
    examples: [
      { en:"The bread in the break room had gone stale.", zh:"休息室裡的麵包已經不新鮮了。" }
    ]
  },
  {
    id: "w768", english: "starvation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["飢餓","餓死"] ] }
    ],
    examples: [
      { en:"The charity works to prevent starvation in developing countries.", zh:"這個慈善機構致力於防止發展中國家的飢荒。" }
    ]
  },
  {
    id: "w769", english: "state", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["州"], ["狀態","情況"] ] },
      { pos: "vt", meaningGroups: [ ["陳述","聲明"] ] }
    ],
    examples: [
      { en:"The company's headquarters is located in the state of Texas.", zh:"公司總部位於德州。" },
      { en:"The equipment is in a poor state and needs repair.", zh:"這台設備狀況不佳，需要維修。" },
      { en:"Please state your reasons for requesting a refund.", zh:"請陳述您要求退款的理由。" }
    ]
  },
  {
    id: "w770", english: "status", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["地位","狀態"] ] }
    ],
    examples: [
      { en:"Could you update me on the status of the shipment?", zh:"你能跟我更新一下貨運的狀態嗎？" }
    ]
  },
  {
    id: "w771", english: "stock", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["股票"], ["庫存","存貨"] ] },
      { pos: "vt", meaningGroups: [ ["進貨","備有"] ] }
    ],
    examples: [
      { en:"The company's stock price rose after the earnings report.", zh:"公司股價在財報公布後上漲。" },
      { en:"The store ran out of stock for the popular item.", zh:"這家商店這款熱銷商品的庫存已經用完了。" },
      { en:"The warehouse manager stocks extra parts every month.", zh:"倉庫經理每個月都會進貨額外的零件。" }
    ]
  },
  {
    id: "w772", english: "strategy", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["策略","戰略"] ] }
    ],
    examples: [
      { en:"The team developed a new marketing strategy for the launch.", zh:"團隊為這次上市制定了新的行銷策略。" }
    ]
  },
  {
    id: "w773", english: "strength", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["力量","實力"] ] },
      { pos: "nc", meaningGroups: [ ["優點","長處"] ] }
    ],
    examples: [
      { en:"The company's financial strength allowed it to survive the downturn.", zh:"公司的財務實力讓它得以度過經濟低迷期。" },
      { en:"Attention to detail is one of her greatest strengths.", zh:"注重細節是她最大的優點之一。" }
    ]
  },
  {
    id: "w774", english: "strive", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["努力","力求"] ] }
    ],
    examples: [
      { en:"The staff strive to meet every customer's expectations.", zh:"員工們努力滿足每位顧客的期望。" }
    ]
  },
  {
    id: "w775", english: "struggle", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["掙扎","努力奮鬥"] ] },
      { pos: "nc", meaningGroups: [ ["掙扎","困境"] ] }
    ],
    examples: [
      { en:"Small businesses struggled to stay afloat during the recession.", zh:"小型企業在經濟衰退期間努力維持生存。" },
      { en:"The company faced a long struggle to regain market share.", zh:"公司經歷了一場長期的掙扎才重新奪回市佔率。" }
    ]
  },
  {
    id: "w776", english: "suitable", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["合適的","適當的"] ] }
    ],
    examples: [
      { en:"This venue is suitable for large conferences.", zh:"這個場地適合舉辦大型會議。" }
    ]
  },
  {
    id: "w777", english: "superior", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["優越的","較好的"] ] },
      { pos: "nc", meaningGroups: [ ["上級","上司"] ] }
    ],
    examples: [
      { en:"This model offers superior performance at a lower price.", zh:"這款機型以較低的價格提供更優越的性能。" },
      { en:"She reported the incident directly to her superior.", zh:"她直接向上司報告了這件事。" }
    ]
  },
  {
    id: "w778", english: "support", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["支持","支援","支撐"] ] },
      { pos: "nu", meaningGroups: [ ["支持","支援"] ] }
    ],
    examples: [
      { en:"The IT department supports all employees with technical issues.", zh:"IT部門為所有員工提供技術問題的支援。" },
      { en:"The proposal received strong support from the board.", zh:"這項提案獲得了董事會的大力支持。" }
    ]
  },
  {
    id: "w779", english: "suppose", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["猜想","假設"] ] }
    ],
    examples: [
      { en:"I suppose the meeting will be rescheduled due to the storm.", zh:"我猜這場會議會因為暴風雨而改期。" }
    ]
  },
  {
    id: "w780", english: "surf", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["衝浪"] ] },
      { pos: "vt", meaningGroups: [ ["瀏覽"] ] }
    ],
    examples: [
      { en:"They went to surf on the beach during their vacation.", zh:"他們在假期時去海邊衝浪。" },
      { en:"He was surfing the internet for competitor pricing.", zh:"他在網路上瀏覽競爭對手的價格資訊。" }
    ]
  },
  {
    id: "w781", english: "surface", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["表面"] ] },
      { pos: "vi", meaningGroups: [ ["浮現","顯現"] ] }
    ],
    examples: [
      { en:"Wipe the surface of the table before the meeting starts.", zh:"會議開始前先擦拭桌面。" },
      { en:"New concerns about the budget surfaced during the discussion.", zh:"討論過程中浮現了對預算的新疑慮。" }
    ]
  },
  {
    id: "w782", english: "surrounding", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["周圍的"] ] }
    ],
    examples: [
      { en:"The factory and its surrounding area were inspected for safety.", zh:"工廠及其周邊地區都接受了安全檢查。" }
    ]
  },
  {
    id: "w783", english: "survival", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["生存","倖存"] ] }
    ],
    examples: [
      { en:"Cutting costs was essential for the company's survival.", zh:"削減成本對公司的生存至關重要。" }
    ]
  },
  {
    id: "w784", english: "survive", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["存活","倖存"] ] }
    ],
    examples: [
      { en:"Few small shops survived the economic crisis.", zh:"很少有小商店在這場經濟危機中存活下來。" }
    ]
  },
  {
    id: "w785", english: "suspicion", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["懷疑","猜疑"] ] }
    ],
    examples: [
      { en:"The auditor's report raised suspicion about the company's accounts.", zh:"稽核員的報告讓人對公司的帳目產生懷疑。" }
    ]
  },
  {
    id: "w786", english: "suspicious", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["可疑的","懷疑的"] ] }
    ],
    examples: [
      { en:"Security flagged a suspicious package at the entrance.", zh:"保全人員在入口處發現了一件可疑的包裹。" }
    ]
  },
  {
    id: "w787", english: "symbolize", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["象徵"] ] }
    ],
    examples: [
      { en:"The new logo symbolizes the company's commitment to innovation.", zh:"這個新標誌象徵著公司對創新的承諾。" }
    ]
  },
  {
    id: "w788", english: "syrup", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["糖漿"] ] }
    ],
    examples: [
      { en:"The hotel restaurant serves pancakes with maple syrup.", zh:"這家飯店餐廳供應搭配楓糖漿的鬆餅。" }
    ]
  },
  {
    id: "w789", english: "tag", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["標籤"] ] },
      { pos: "vt", meaningGroups: [ ["貼標籤","標記"] ] }
    ],
    examples: [
      { en:"Check the price tag before you make the purchase.", zh:"購買前先看一下價格標籤。" },
      { en:"Employees are tagged in the system by department.", zh:"員工在系統中依部門被標記分類。" }
    ]
  },
  {
    id: "w790", english: "take for granted", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["認為...理所當然","視...為理所當然"] ] }
    ],
    examples: [
      { en:"Don't take your job security for granted during a merger.", zh:"在合併期間別把工作保障視為理所當然。" }
    ]
  },
  {
    id: "w791", english: "talent", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["才能","天賦"] ] },
      { pos: "nu", meaningGroups: [ ["人才"] ] }
    ],
    examples: [
      { en:"She has a real talent for negotiation.", zh:"她在談判方面真的很有天賦。" },
      { en:"The company invests heavily in attracting new talent.", zh:"公司在吸引新人才方面投入了大量資金。" }
    ]
  },
  {
    id: "w792", english: "technically", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adv", meaningGroups: [ ["技術上","嚴格來說"] ] }
    ],
    examples: [
      { en:"Technically, the contract expires at midnight tonight.", zh:"嚴格來說，這份合約今晚午夜就到期。" }
    ]
  },
  {
    id: "w793", english: "technique", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["技術","技巧"] ] }
    ],
    examples: [
      { en:"The sales team learned a new negotiation technique.", zh:"銷售團隊學習了一種新的談判技巧。" }
    ]
  },
  {
    id: "w794", english: "technological", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["技術的","科技的"] ] }
    ],
    examples: [
      { en:"The factory underwent a major technological upgrade.", zh:"這家工廠進行了一次重大的技術升級。" }
    ]
  },
  {
    id: "w795", english: "teenager", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["青少年"] ] }
    ],
    examples: [
      { en:"The survey targeted teenagers between the ages of 13 and 19.", zh:"這項調查的對象是十三到十九歲的青少年。" }
    ]
  },
  {
    id: "w796", english: "temporarily", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adv", meaningGroups: [ ["暫時地"] ] }
    ],
    examples: [
      { en:"The office was temporarily closed for renovation.", zh:"辦公室因裝修暫時關閉。" }
    ]
  },
  {
    id: "w797", english: "the departed", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["已故者","亡者"] ] }
    ],
    examples: [
      { en:"The company held a moment of silence for the departed.", zh:"公司為已故的同事默哀。" }
    ]
  },
  {
    id: "w798", english: "thirst", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["渴","口渴"] ] },
      { pos: "nc", meaningGroups: [ ["渴望"] ] }
    ],
    examples: [
      { en:"Working outdoors all day left the crew with a strong thirst.", zh:"整天在戶外工作讓工作人員感到非常口渴。" },
      { en:"Her thirst for knowledge led her to pursue an MBA.", zh:"她對知識的渴望讓她去讀了工商管理碩士。" }
    ]
  },
  {
    id: "w799", english: "tide", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["潮汐","潮流"] ] }
    ],
    examples: [
      { en:"The tide was too high for the ferry to dock.", zh:"潮水太高，渡輪無法靠岸。" }
    ]
  },
  {
    id: "w800", english: "tissue paper", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["棉紙","薄紙"] ] }
    ],
    examples: [
      { en:"The gift shop wraps every item in colorful tissue paper.", zh:"這家禮品店會用彩色棉紙包裝每件商品。" }
    ]
  },
  {
    id: "w801", english: "to top it all off", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["更甚者","最後還有一件更誇張的事"] ] }
    ],
    examples: [
      { en:"The flight was delayed, and to top it all off, our luggage was lost.", zh:"班機延誤了，更誇張的是，我們的行李還丟了。" }
    ]
  },
  {
    id: "w802", english: "toast", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["吐司","烤麵包"], ["祝酒辭","敬酒辭"] ] },
      { pos: "vt", meaningGroups: [ ["向...敬酒","舉杯祝賀"] ] }
    ],
    examples: [
      { en:"He had toast and coffee for breakfast.", zh:"他早餐吃吐司配咖啡。" },
      { en:"The board proposed a toast to celebrate the merger.", zh:"董事會提議敬酒以慶祝合併案。" },
      { en:"The manager toasted the sales team for exceeding their targets.", zh:"經理向銷售團隊敬酒，祝賀他們超越目標。" }
    ]
  },
  {
    id: "w803", english: "toss", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["投擲","輕拋"] ] },
      { pos: "vi", meaningGroups: [ ["輾轉","翻騰"] ] }
    ],
    examples: [
      { en:"She tossed the report onto the desk in frustration.", zh:"她沮喪地把報告丟到桌上。" },
      { en:"He tossed and turned all night worrying about the presentation.", zh:"他整晚為了簡報擔心得輾轉難眠。" }
    ]
  },
  {
    id: "w804", english: "tough", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["艱難的","強硬的"] ] }
    ],
    examples: [
      { en:"Negotiating the new contract was a tough process.", zh:"談判新合約的過程相當艱難。" }
    ]
  },
  {
    id: "w805", english: "tourist", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["遊客","觀光客"] ] }
    ],
    examples: [
      { en:"The hotel offers special packages for tourists.", zh:"這家飯店為遊客提供特別套裝行程。" }
    ]
  },
  {
    id: "w806", english: "trade", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["貿易","交易"] ] },
      { pos: "vt", meaningGroups: [ ["交易","以...交換"] ] }
    ],
    examples: [
      { en:"International trade between the two countries increased last year.", zh:"兩國之間的國際貿易去年有所增長。" },
      { en:"The two companies agreed to trade technology for market access.", zh:"這兩家公司同意用技術交換市場准入。" }
    ]
  },
  {
    id: "w807", english: "traditional", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["傳統的"] ] }
    ],
    examples: [
      { en:"The firm still relies on traditional advertising methods.", zh:"這家公司仍然依賴傳統的廣告方式。" }
    ]
  },
  {
    id: "w808", english: "traffic", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["交通","車流量"] ] },
      { pos: "vi", meaningGroups: [ ["販運","非法交易"] ] }
    ],
    examples: [
      { en:"Heavy traffic delayed the delivery truck by two hours.", zh:"嚴重的交通堵塞讓貨運卡車延誤了兩個小時。" },
      { en:"The company was investigated for trafficking counterfeit goods.", zh:"這家公司因販運仿冒品而遭到調查。" }
    ]
  },
  {
    id: "w809", english: "tragedy", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["悲劇"] ] }
    ],
    examples: [
      { en:"The factory fire was a tragedy for the entire community.", zh:"這場工廠火災對整個社區來說是一場悲劇。" }
    ]
  },
  {
    id: "w810", english: "transform", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["轉變","改造"] ] }
    ],
    examples: [
      { en:"The new CEO transformed the struggling company into a market leader.", zh:"新任執行長將這家陷入困境的公司轉變成市場領導者。" }
    ]
  },
  {
    id: "w811", english: "translate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["翻譯"] ] },
      { pos: "vi", meaningGroups: [ ["轉化為","反映為"] ] }
    ],
    examples: [
      { en:"The contract needs to be translated into Japanese before signing.", zh:"這份合約需要在簽署前翻譯成日文。" },
      { en:"Increased traffic to the website did not translate into higher sales.", zh:"網站流量的增加並沒有轉化為更高的銷售額。" }
    ]
  },
  {
    id: "w812", english: "transport", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["運輸"] ] },
      { pos: "nu", meaningGroups: [ ["運輸","交通工具"] ] }
    ],
    examples: [
      { en:"The goods are transported by truck to distribution centers.", zh:"這些貨物由卡車運輸到配銷中心。" },
      { en:"Public transport is convenient for commuting to the office.", zh:"大眾運輸對通勤到辦公室來說很方便。" }
    ]
  },
  {
    id: "w813", english: "trash", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["垃圾"] ] },
      { pos: "vt", meaningGroups: [ ["丟棄","毀掉"] ] }
    ],
    examples: [
      { en:"Please separate the recycling from the trash.", zh:"請把可回收物與垃圾分開。" },
      { en:"The manager trashed the old proposal and started over.", zh:"經理放棄了舊的提案，重新開始。" }
    ]
  },
  {
    id: "w814", english: "traveler", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["旅客","旅行者"] ] }
    ],
    examples: [
      { en:"The airline offers discounts for frequent travelers.", zh:"這家航空公司為經常旅行的旅客提供折扣。" }
    ]
  },
  {
    id: "w815", english: "tremendous", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["巨大的","驚人的"] ] }
    ],
    examples: [
      { en:"The new product achieved tremendous success in its first month.", zh:"這款新產品在上市第一個月就取得了巨大的成功。" }
    ]
  },
  {
    id: "w816", english: "trend", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["趨勢","潮流"] ] }
    ],
    examples: [
      { en:"The report highlights the latest trends in consumer spending.", zh:"這份報告強調了消費者支出的最新趨勢。" }
    ]
  },
  {
    id: "w817", english: "tribute", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["致敬","讚辭"], ["貢品"] ] }
    ],
    examples: [
      { en:"The company held a dinner as a tribute to its retiring founder.", zh:"公司舉辦了一場晚宴向即將退休的創辦人致敬。" },
      { en:"In ancient times, smaller kingdoms paid tribute to the empire.", zh:"在古代，較小的王國會向帝國進貢。" }
    ]
  },
  {
    id: "w818", english: "triumph", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["勝利","凱旋"] ] },
      { pos: "vi", meaningGroups: [ ["獲勝","克服困難"] ] }
    ],
    examples: [
      { en:"The product launch was a triumph for the marketing team.", zh:"這次產品上市對行銷團隊來說是一場勝利。" },
      { en:"The company triumphed over its competitors despite a tough market.", zh:"儘管市場艱難，這家公司仍然戰勝了競爭對手。" }
    ]
  },
  {
    id: "w819", english: "tropical", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["熱帶的"] ] }
    ],
    examples: [
      { en:"The resort is located in a tropical climate.", zh:"這間度假村位於熱帶氣候區。" }
    ]
  },
  {
    id: "w820", english: "tune in", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["收聽","收看"] ] }
    ],
    examples: [
      { en:"Millions of viewers tuned in to watch the product launch live.", zh:"數百萬觀眾收看了這次產品發布會的直播。" }
    ]
  },
  {
    id: "w821", english: "turn the tide", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["扭轉局勢","力挽狂瀾"] ] }
    ],
    examples: [
      { en:"The new strategy helped turn the tide for the failing division.", zh:"這項新策略幫助這個陷入困境的部門力挽狂瀾。" }
    ]
  },
  {
    id: "w822", english: "type", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["類型"] ] },
      { pos: "vt", meaningGroups: [ ["打字"] ] }
    ],
    examples: [
      { en:"What type of contract do you need?", zh:"你需要哪種類型的合約？" },
      { en:"She typed up the minutes right after the meeting.", zh:"她在會議結束後馬上把會議記錄打好。" }
    ]
  },
  {
    id: "w823", english: "undesirable", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["不良的","不受歡迎的"] ] }
    ],
    examples: [
      { en:"The merger had several undesirable side effects for employees.", zh:"這次合併對員工產生了一些不良的附帶影響。" }
    ]
  },
  {
    id: "w824", english: "unexpectedly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adv", meaningGroups: [ ["出乎意料地"] ] }
    ],
    examples: [
      { en:"The CEO resigned unexpectedly last week.", zh:"執行長上週出乎意料地辭職了。" }
    ]
  },
  {
    id: "w825", english: "unfavorable", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["不利的","不贊成的"] ] }
    ],
    examples: [
      { en:"The unfavorable exchange rate reduced the company's profits.", zh:"不利的匯率降低了公司的利潤。" }
    ]
  },
  {
    id: "w826", english: "unplug", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["拔掉插頭","拔除"] ] }
    ],
    examples: [
      { en:"Please unplug the printer before servicing it.", zh:"維修前請先拔掉印表機的插頭。" }
    ]
  },
  {
    id: "w827", english: "unpredictable", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["不可預測的"] ] }
    ],
    examples: [
      { en:"The stock market has been unpredictable this year.", zh:"今年股市一直難以預測。" }
    ]
  },
  {
    id: "w828", english: "upset", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["難過的","不安的"] ] },
      { pos: "vt", meaningGroups: [ ["使不安","打亂"] ] }
    ],
    examples: [
      { en:"The client was upset about the delayed shipment.", zh:"客戶對延誤的貨運感到不滿。" },
      { en:"The sudden change in schedule upset the whole project plan.", zh:"時程突然的變更打亂了整個專案計畫。" }
    ]
  },
  {
    id: "w829", english: "urban", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["城市的","都市的"] ] }
    ],
    examples: [
      { en:"The company specializes in urban development projects.", zh:"這家公司專門從事城市開發專案。" }
    ]
  },
  {
    id: "w830", english: "utilize", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["利用"] ] }
    ],
    examples: [
      { en:"The team utilized new software to speed up the process.", zh:"團隊利用新軟體加快了流程。" }
    ]
  },
  {
    id: "w831", english: "value", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["價值"] ] },
      { pos: "vt", meaningGroups: [ ["重視","評估"] ] }
    ],
    examples: [
      { en:"The property's value increased significantly over the past decade.", zh:"這處房產的價值在過去十年大幅增加。" },
      { en:"The manager values employees who take initiative.", zh:"經理很重視主動積極的員工。" }
    ]
  },
  {
    id: "w832", english: "variety", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["多樣性"] ] },
      { pos: "nc", meaningGroups: [ ["種類","品種"] ] }
    ],
    examples: [
      { en:"The team values variety in its hiring process.", zh:"團隊在招聘過程中重視多樣性。" },
      { en:"The restaurant offers a variety of dishes to suit every taste.", zh:"這家餐廳提供多種菜色以滿足各種口味。" }
    ]
  },
  {
    id: "w833", english: "various", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["各種的","多樣的"] ] }
    ],
    examples: [
      { en:"The company operates in various countries across Asia.", zh:"這家公司在亞洲多個國家經營業務。" }
    ]
  },
  {
    id: "w834", english: "vast", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["廣闊的","大量的"] ] }
    ],
    examples: [
      { en:"The merger gave the firm access to a vast customer base.", zh:"這次合併讓公司得以接觸到龐大的客戶群。" }
    ]
  },
  {
    id: "w835", english: "vegetarian", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["素食者"] ] },
      { pos: "adj", meaningGroups: [ ["素食的"] ] }
    ],
    examples: [
      { en:"The cafeteria added more vegetarian options to the menu.", zh:"員工餐廳在菜單上增加了更多素食選項。" },
      { en:"She has been a vegetarian for over ten years.", zh:"她已經吃素超過十年了。" }
    ]
  },
  {
    id: "w836", english: "victim", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["受害者"] ] }
    ],
    examples: [
      { en:"The company compensated the victims of the product defect.", zh:"公司對這次產品缺陷的受害者進行了補償。" }
    ]
  },
  {
    id: "w837", english: "violet", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["紫色的"] ] },
      { pos: "nc", meaningGroups: [ ["紫羅蘭"] ] }
    ],
    examples: [
      { en:"The new packaging uses a soft violet color.", zh:"新的包裝採用柔和的紫色。" },
      { en:"She received a bouquet of violets for her promotion.", zh:"她因升職收到了一束紫羅蘭花束。" }
    ]
  },
  {
    id: "w838", english: "viral marketing", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["病毒式行銷"] ] }
    ],
    examples: [
      { en:"The startup relied on viral marketing instead of paid ads.", zh:"這家新創公司依靠病毒式行銷，而不是付費廣告。" }
    ]
  },
  {
    id: "w839", english: "virus", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["病毒"] ] }
    ],
    examples: [
      { en:"The IT department detected a virus on several company laptops.", zh:"IT部門在多台公司筆電上發現了病毒。" }
    ]
  },
  {
    id: "w840", english: "vision", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["視力","視覺"] ] },
      { pos: "nc", meaningGroups: [ ["願景","遠見"] ] }
    ],
    examples: [
      { en:"Regular eye exams help protect your vision.", zh:"定期做眼科檢查有助於保護你的視力。" },
      { en:"The CEO shared her vision for the company's future.", zh:"執行長分享了她對公司未來的願景。" }
    ]
  },
  {
    id: "w841", english: "visual", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["視覺的"] ] },
      { pos: "nc", meaningGroups: [ ["視覺輔助資料","圖表"] ] }
    ],
    examples: [
      { en:"The report includes several visual charts for clarity.", zh:"這份報告包含幾張圖表以提高清晰度。" },
      { en:"She added a visual to the slide to illustrate the trend.", zh:"她在投影片中加了一張圖，以說明這個趨勢。" }
    ]
  },
  {
    id: "w842", english: "vital", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["極重要的","必不可少的"] ] }
    ],
    examples: [
      { en:"Clear communication is vital to the success of the project.", zh:"清晰的溝通對這個專案的成功至關重要。" }
    ]
  },
  {
    id: "w843", english: "volcano", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["火山"] ] }
    ],
    examples: [
      { en:"The tour includes a visit to an active volcano.", zh:"這趟行程包含參觀一座活火山。" }
    ]
  },
  {
    id: "w844", english: "volunteer", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["志工","自願者"] ] },
      { pos: "vi", meaningGroups: [ ["自願"] ] }
    ],
    examples: [
      { en:"The company encourages employees to become volunteers for local charities.", zh:"公司鼓勵員工擔任當地慈善機構的志工。" },
      { en:"She volunteered to lead the new project.", zh:"她自願負責這個新專案。" }
    ]
  },
  {
    id: "w845", english: "weekly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["每週的"] ] },
      { pos: "adv", meaningGroups: [ ["每週地","每星期一次"] ] },
      { pos: "nc", meaningGroups: [ ["週刊"] ] }
    ],
    examples: [
      { en:"The team holds a weekly meeting every Monday morning.", zh:"團隊每週一早上都會開會。" },
      { en:"The report is issued weekly to all department heads.", zh:"這份報告每週都會發送給所有部門主管。" },
      { en:"He reads the business weekly during his commute.", zh:"他在通勤時閱讀商業週刊。" }
    ]
  },
  {
    id: "w846", english: "whip up", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["迅速準備","快速做出"], ["激起","煽動"] ] }
    ],
    examples: [
      { en:"The chef whipped up a quick meal for the late guests.", zh:"主廚為晚到的客人迅速準備了一餐。" },
      { en:"The politician's speech whipped up strong emotions in the crowd.", zh:"這位政治人物的演講激起了群眾強烈的情緒。" }
    ]
  },
  {
    id: "w847", english: "whole wheat", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["全麥的"] ] }
    ],
    examples: [
      { en:"The cafeteria switched to whole wheat bread for a healthier menu.", zh:"員工餐廳改用全麥麵包，讓菜單更健康。" }
    ]
  },
  {
    id: "w848", english: "wireless", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["無線的"] ] }
    ],
    examples: [
      { en:"The office was upgraded with a faster wireless network.", zh:"辦公室升級了更快速的無線網路。" }
    ]
  },
  {
    id: "w849", english: "wonder", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["想知道","感到好奇"] ] },
      { pos: "nc", meaningGroups: [ ["奇跡","令人驚奇的事物"] ] }
    ],
    examples: [
      { en:"I wonder if the shipment will arrive on time.", zh:"我很好奇這批貨會不會準時到達。" },
      { en:"The new headquarters is truly a wonder of modern architecture.", zh:"這棟新總部大樓真的是現代建築的奇跡。" }
    ]
  },
  {
    id: "w850", english: "word of mouth", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["口碑","口耳相傳"] ] }
    ],
    examples: [
      { en:"Most of our new customers come from word of mouth.", zh:"我們大部分的新客戶都是透過口碑而來的。" }
    ]
  },
  {
    id: "w851", english: "worth", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["值...的","值得...的"] ] },
      { pos: "nu", meaningGroups: [ ["價值"] ] }
    ],
    examples: [
      { en:"This investment is definitely worth the risk.", zh:"這項投資絕對值得冒這個風險。" },
      { en:"The consultant explained the true worth of the property.", zh:"顧問說明了這處房產的真正價值。" }
    ]
  },
  {
    id: "w852", english: "worthy", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["值得的","配得上的"] ] }
    ],
    examples: [
      { en:"The proposal is worthy of further consideration.", zh:"這項提案值得進一步考慮。" }
    ]
  },
  {
    id: "w853", english: "wrapped", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["包裹好的","包紮好的"] ] }
    ],
    examples: [
      { en:"All the products were carefully wrapped before shipping.", zh:"所有產品在出貨前都被小心地包裝好。" }
    ]
  },
  {
    id: "w854", english: "imminent", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["即將發生的","迫近的"] ] }
    ],
    examples: [
      { en:"The company announced layoffs amid an imminent budget crisis.", zh:"公司在迫近的預算危機中宣布裁員。" }
    ]
  },
  {
    id: "w2321", english: "wary", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["謹慎的","提防的","小心翼翼的"] ] }
    ],
    examples: [
      { en:"Investors remained wary of the volatile market conditions.", zh:"投資人對這波動的市場情勢保持謹慎。" }
    ]
  },
  {
    id: "w2322", english: "overhaul", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["徹底檢修","全面改革"] ] },
      { pos: "nc", meaningGroups: [ ["徹底檢修","大修"] ] }
    ],
    examples: [
      { en:"The company plans to overhaul its outdated inventory system.", zh:"公司計畫全面改革其過時的庫存系統。" },
      { en:"The factory is undergoing a complete overhaul of its safety procedures.", zh:"這家工廠正在對其安全程序進行全面檢修。" }
    ]
  },
  { id: "w855", english: "against all the odds", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["儘管困難重重","不顧種種不利因素"] ] } ],
    examples: [ { en:"Against all the odds, the small startup won the contract over its much larger competitors.", zh:"儘管困難重重，這家小型新創公司仍從規模大得多的競爭對手手中贏得了這份合約。" } ] },
  { id: "w856", english: "apprentice", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["學徒","見習生"] ] } ],
    examples: [ { en:"The apprentice spent two years learning welding techniques from a master craftsman.", zh:"這名學徒花了兩年時間向一位資深工匠學習焊接技術。" } ] },
  { id: "w857", english: "computer literate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["精通電腦操作的"] ] } ],
    examples: [ { en:"Applicants for this position must be computer literate and familiar with spreadsheet software.", zh:"應徵這個職位的人必須精通電腦操作，並熟悉試算表軟體。" } ] },
  { id: "w858", english: "credential", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["資歷","證明文件"] ] } ],
    examples: [ { en:"She submitted her academic credentials along with the job application.", zh:"她在求職申請中附上了她的學歷證明文件。" } ] },
  { id: "w859", english: "excel", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vi", meaningGroups: [ ["擅長","表現出色"] ] } ],
    examples: [ { en:"He has always excelled at negotiating favorable contract terms for the company.", zh:"他向來擅長為公司談出有利的合約條件。" } ] },
  { id: "w860", english: "increment", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["增額","增量"] ] } ],
    examples: [ { en:"Employees receive an annual salary increment based on their performance review.", zh:"員工會根據績效考核獲得年度加薪。" } ] },
  { id: "w861", english: "lag", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vi", meaningGroups: [ ["落後","滯後"] ] } ],
    examples: [ { en:"Sales in the overseas market have started to lag behind the domestic figures.", zh:"海外市場的銷售已開始落後於國內數字。" } ] },
  { id: "w862", english: "lay out", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["展開放置","規劃佈局"] ] } ],
    examples: [ { en:"The manager laid out the new floor plan for the office renovation.", zh:"經理把辦公室裝修的新平面圖攤開來給大家看。" } ] },
  { id: "w863", english: "make a commitment to", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["承諾要做"] ] } ],
    examples: [ { en:"The company made a commitment to reduce its carbon emissions by 2030.", zh:"該公司承諾在二零三零年前減少碳排放。" } ] },
  { id: "w864", english: "make a point of", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["特別注意去做","刻意做到"] ] } ],
    examples: [ { en:"She always makes a point of thanking clients personally after every meeting.", zh:"她總是特別在每次會議後親自向客戶致謝。" } ] },
  { id: "w865", english: "mindful", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["留意的","謹記的"] ] } ],
    examples: [ { en:"Employees should be mindful of the company's dress code when meeting clients.", zh:"員工與客戶會面時應留意公司的服裝規定。" } ] },
  { id: "w866", english: "overqualified", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["資格過高的"] ] } ],
    examples: [ { en:"The recruiter worried that the candidate was overqualified for the entry-level position.", zh:"招募人員擔心這名應徵者的資格對這個初階職位來說過高。" } ] },
  { id: "w867", english: "pertaining to", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["與某事有關的","關於"] ] } ],
    examples: [ { en:"Please forward any questions pertaining to the merger to the legal department.", zh:"有關合併案的任何問題請轉交法務部門。" } ] },
  { id: "w868", english: "preliminary", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["初步的","預備性的"] ] } ],
    examples: [ { en:"The preliminary results of the survey suggest strong customer interest in the new product.", zh:"這項調查的初步結果顯示顧客對新產品有濃厚興趣。" } ] },
  { id: "w869", english: "replenish", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["補充","重新裝滿"] ] } ],
    examples: [ { en:"The warehouse staff replenish the shelves with new stock every morning.", zh:"倉庫人員每天早上補充貨架上的新庫存。" } ] },
  { id: "w870", english: "screening", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["篩選","審查"] ] } ],
    examples: [ { en:"All new hires must pass a background screening before starting work.", zh:"所有新進員工必須先通過背景審查才能開始工作。" } ] },
  { id: "w871", english: "simplicity", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["簡單","簡易"] ] } ],
    examples: [ { en:"The main appeal of this software is its simplicity of use.", zh:"這套軟體最大的吸引力在於它使用上的簡便。" } ] },
  { id: "w872", english: "stellar", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["極優秀的","出色的"] ] } ],
    examples: [ { en:"The sales team delivered a stellar performance this quarter.", zh:"銷售團隊本季的表現非常出色。" } ] },
  { id: "w873", english: "sternly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["嚴厲地","嚴格地"] ] } ],
    examples: [ { en:"The supervisor spoke sternly to the staff about repeated tardiness.", zh:"主管針對員工屢次遲到的問題嚴厲地訓話。" } ] },
  { id: "w874", english: "workstation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["工作站"] ] } ],
    examples: [ { en:"Each employee is assigned a personal workstation equipped with two monitors.", zh:"每位員工都配有一個裝設兩台螢幕的個人工作站。" } ] },
  { id: "w875", english: "zealous", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["熱心的","熱切的"] ] } ],
    examples: [ { en:"The new intern is a zealous supporter of the company's sustainability initiatives.", zh:"這名新來的實習生是公司永續發展計畫的熱心支持者。" } ] },
  { id: "w876", english: "alert", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["警覺的","機警的"] ] },
      { pos: "vt", meaningGroups: [ ["警告","提醒"] ] }
    ],
    examples: [
      { en:"Security guards must remain alert throughout their shift.", zh:"保全人員在整個班次期間必須保持警覺。" },
      { en:"The manager alerted staff to the upcoming system outage.", zh:"經理提醒員工即將發生的系統中斷。" }
    ] },
  { id: "w877", english: "at the discretion of", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["由某人決定","取決於某人的裁量"] ] } ],
    examples: [ { en:"Bonuses are awarded at the discretion of the department head.", zh:"獎金的發放取決於部門主管的裁量。" } ] },
  { id: "w878", english: "bound", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["有義務的","受約束的"] ] } ],
    examples: [ { en:"Under the contract, the supplier is bound to deliver the goods within thirty days.", zh:"根據合約，供應商有義務在三十天內交貨。" } ] },
  { id: "w879", english: "by all means", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["當然可以","務必"] ] } ],
    examples: [ { en:"\"Could I reschedule our meeting?\" \"By all means, just let me know a time that works.\"", zh:"「我可以重新安排會議時間嗎？」「當然可以，告訴我方便的時間就好。」" } ] },
  { id: "w880", english: "circumscribe", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["限制","約束"] ] } ],
    examples: [ { en:"The new regulations circumscribe the powers of local authorities to raise taxes.", zh:"新法規限制了地方政府提高稅收的權力。" } ] },
  { id: "w881", english: "depiction", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["描繪","描述"] ] } ],
    examples: [ { en:"The report gave an accurate depiction of the company's financial troubles.", zh:"這份報告準確地描繪了公司的財務困境。" } ] },
  { id: "w882", english: "disobedient", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["不服從的","違抗命令的"] ] } ],
    examples: [ { en:"The employee was reprimanded for being disobedient toward his supervisor's instructions.", zh:"這名員工因不服從主管的指示而受到訓誡。" } ] },
  { id: "w883", english: "distrust", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["不信任","懷疑"] ] },
      { pos: "vt", meaningGroups: [ ["不信任","懷疑"] ] }
    ],
    examples: [
      { en:"There has been a growing sense of distrust between the two departments.", zh:"這兩個部門之間逐漸產生了不信任感。" },
      { en:"Investors began to distrust the accuracy of the company's earnings reports.", zh:"投資人開始不信任該公司財報數字的準確性。" }
    ] },
  { id: "w884", english: "enactment", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["制定","頒布"] ] } ],
    examples: [ { en:"The enactment of the new labor law will take effect next January.", zh:"這項新勞動法的頒布將於明年一月生效。" } ] },
  { id: "w885", english: "exemplary", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["值得效法的","堪為典範的"], ["以儆效尤的","嚴厲警示性的"] ] } ],
    examples: [
      { en:"She received an award for her exemplary customer service.", zh:"她因堪為典範的客戶服務而獲獎。" },
      { en:"The court imposed an exemplary fine to deter similar violations.", zh:"法院處以警示性的高額罰款以遏止類似違規行為。" }
    ] },
  { id: "w886", english: "from this day onward", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["從今天起","自此以後"] ] } ],
    examples: [ { en:"From this day onward, all expense reports must be submitted electronically.", zh:"從今天起，所有的費用報告都必須以電子方式提交。" } ] },
  { id: "w887", english: "hold up", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["維持良好狀態","撐住"], ["延誤","阻礙"] ] } ],
    examples: [
      { en:"Despite the economic downturn, the company's sales have held up well.", zh:"儘管經濟不景氣，公司的銷售仍然維持得相當不錯。" },
      { en:"A traffic accident caused a two-hour hold-up on the highway.", zh:"一場車禍導致高速公路延誤了兩個小時。" }
    ] },
  { id: "w888", english: "if I'm not mistaken", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["如果我沒記錯的話"] ] } ],
    examples: [ { en:"If I'm not mistaken, the shipment was supposed to arrive yesterday.", zh:"如果我沒記錯的話，這批貨昨天應該就到了。" } ] },
  { id: "w889", english: "impeccable", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["完美無瑕的","無可挑剔的"] ] } ],
    examples: [ { en:"The hotel is known for its impeccable service.", zh:"這家飯店以無可挑剔的服務聞名。" } ] },
  { id: "w890", english: "in accordance with", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["依照","根據"] ] } ],
    examples: [ { en:"The refund was processed in accordance with company policy.", zh:"這筆退款是依照公司政策處理的。" } ] },
  { id: "w891", english: "inadvertently", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["不經意地","非故意地"] ] } ],
    examples: [ { en:"The clerk inadvertently sent the confidential file to the wrong department.", zh:"職員不小心把機密檔案寄給了錯誤的部門。" } ] },
  { id: "w892", english: "indecisive", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["猶豫不決的","不果斷的"] ] } ],
    examples: [ { en:"An indecisive manager can slow down the entire project timeline.", zh:"一位猶豫不決的經理可能會拖慢整個專案的時程。" } ] },
  { id: "w893", english: "infringement", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["侵犯","違反"] ] } ],
    examples: [ { en:"The company was sued for patent infringement.", zh:"該公司因侵犯專利權而遭到起訴。" } ] },
  { id: "w894", english: "in observance of", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["為紀念","依循慣例"] ] } ],
    examples: [ { en:"The office will be closed in observance of the national holiday.", zh:"為配合國定假日，公司將休息一天。" } ] },
  { id: "w895", english: "judicial", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["司法的"] ] } ],
    examples: [ { en:"The dispute will be settled through judicial proceedings.", zh:"這項爭議將透過司法程序解決。" } ] },
  { id: "w896", english: "keenly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["熱切地","敏銳地"] ] } ],
    examples: [ { en:"Investors are keenly watching the central bank's next interest rate decision.", zh:"投資人正密切關注央行下一次的利率決定。" } ] },
  { id: "w897", english: "legitimate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["合法的","正當合理的"] ] } ],
    examples: [ { en:"The auditor confirmed that all the expenses were legitimate business costs.", zh:"稽核員確認所有支出都是正當的營業成本。" } ] },
  { id: "w898", english: "observance", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["遵守","奉行"] ] } ],
    examples: [ { en:"Strict observance of safety regulations is required on the factory floor.", zh:"工廠現場要求嚴格遵守安全規範。" } ] },
  { id: "w899", english: "ordinance", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["法令","條例"] ] } ],
    examples: [ { en:"The city council passed an ordinance banning smoking in public parks.", zh:"市議會通過了一項禁止在公共公園吸菸的法令。" } ] },
  { id: "w900", english: "reprimand", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["斥責","正式責備"] ] } ],
    examples: [ { en:"The supervisor reprimanded the clerk for mishandling customer data.", zh:"主管斥責這名職員不當處理客戶資料。" } ] },
  { id: "w901", english: "stand over", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["站在旁邊監視","緊盯著"] ] } ],
    examples: [ { en:"I find it hard to concentrate when my boss stands over me while I work.", zh:"當老闆站在旁邊盯著我工作時，我很難專心。" } ] },
  { id: "w902", english: "stiff", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["堅硬的","僵硬的"] ] } ],
    examples: [ { en:"After sitting at the desk all day, her neck felt stiff.", zh:"整天坐在辦公桌前後，她的脖子感到僵硬。" } ] },
  { id: "w903", english: "substantiate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["證實","提供證據支持"] ] } ],
    examples: [ { en:"The auditor asked for receipts to substantiate the reported expenses.", zh:"稽核員要求提供收據以證實申報的費用。" } ] },
  { id: "w904", english: "suppress", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["壓制","抑制"] ] } ],
    examples: [ { en:"The company was accused of suppressing negative reviews about its product.", zh:"該公司被指控壓制對其產品的負面評論。" } ] },
  { id: "w905", english: "tensely", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["緊張地","焦慮地"] ] } ],
    examples: [ { en:"The staff waited tensely for the CEO's announcement about layoffs.", zh:"員工們緊張地等待執行長宣布裁員消息。" } ] },
  { id: "w906", english: "testimony", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["證詞","證言"] ] } ],
    examples: [ { en:"The witness gave testimony that contradicted the company's official statement.", zh:"這名證人提出的證詞與公司的官方聲明相互矛盾。" } ] },
  { id: "w907", english: "trespass", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vi", meaningGroups: [ ["擅自進入","非法侵入"] ] } ],
    examples: [ { en:"Visitors who trespass on the construction site will be prosecuted.", zh:"擅自進入工地的訪客將被起訴。" } ] },
  { id: "w908", english: "under the supervision of", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["在某人的監督下"] ] } ],
    examples: [ { en:"New employees complete their training under the supervision of a senior staff member.", zh:"新員工在資深員工的監督下完成培訓。" } ] },
  { id: "w909", english: "without respect to", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["不論","不考慮"] ] } ],
    examples: [ { en:"The company promotes staff based on merit, without respect to seniority.", zh:"公司根據能力晉升員工，而不考慮資歷深淺。" } ] },
  { id: "w910", english: "administer", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["管理","執行"] ] } ],
    examples: [ { en:"The HR department administers the company's benefits program.", zh:"人資部門負責管理公司的福利計畫。" } ] },
  { id: "w911", english: "clerical", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["文書的","辦公室事務的"] ] } ],
    examples: [ { en:"She was hired to handle clerical duties such as filing and data entry.", zh:"她被雇來處理文書工作，如歸檔與資料輸入。" } ] },
  { id: "w912", english: "condense", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["濃縮","精簡"] ] } ],
    examples: [ { en:"He condensed the forty-page report into a two-page summary.", zh:"他把這份四十頁的報告濃縮成兩頁的摘要。" } ] },
  { id: "w913", english: "default", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["違約","未履行義務"] ] } ],
    examples: [ { en:"The bank warned that any default on the loan would damage the company's credit rating.", zh:"銀行警告，任何貸款違約都會損害該公司的信用評等。" } ] },
  { id: "w914", english: "errand", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["差事","跑腿的任務"] ] } ],
    examples: [ { en:"The assistant was sent on an errand to pick up supplies from the printer.", zh:"助理被派去跑腿到印刷廠取貨。" } ] },
  { id: "w915", english: "extend an invitation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["發出邀請","邀請"] ] } ],
    examples: [ { en:"The board extended an invitation to the guest speaker for next month's conference.", zh:"董事會向下個月會議的演講嘉賓發出了邀請。" } ] },
  { id: "w916", english: "follow up on", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["追蹤","進一步處理"] ] } ],
    examples: [ { en:"I'll follow up on your complaint and get back to you by Friday.", zh:"我會追蹤處理你的申訴，並在星期五前回覆你。" } ] },
  { id: "w917", english: "head up", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["領導","主持"] ] } ],
    examples: [ { en:"She was promoted to head up the marketing division.", zh:"她被升職去領導行銷部門。" } ] },
  { id: "w918", english: "impending", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["即將發生的"] ] } ],
    examples: [ { en:"Employees were nervous about the impending merger.", zh:"員工們對即將發生的合併案感到緊張。" } ] },
  { id: "w919", english: "in alphabetical order", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["按字母順序排列"] ] } ],
    examples: [ { en:"The client list is filed in alphabetical order for easy reference.", zh:"客戶名單按字母順序歸檔，以便查閱。" } ] },
  { id: "w920", english: "in luck", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["運氣好","幸運"] ] } ],
    examples: [ { en:"You're in luck—we still have one seat left on tonight's flight.", zh:"你運氣真好，今晚的班機還剩一個座位。" } ] },
  { id: "w921", english: "officiate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vi", meaningGroups: [ ["主持典禮","主持儀式"] ] } ],
    examples: [ { en:"The company's founder officiated at the ribbon-cutting ceremony.", zh:"公司創辦人主持了剪綵典禮。" } ] },
  { id: "w922", english: "past due", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["逾期未付的","過期的"] ] } ],
    examples: [ { en:"The accounting department sent a reminder about the past due invoice.", zh:"會計部門就這張逾期未付的發票發出提醒。" } ] },
  { id: "w923", english: "popularize", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["使普及","推廣"] ] } ],
    examples: [ { en:"The company's marketing campaign helped popularize the new payment app.", zh:"該公司的行銷活動幫助推廣了這款新的支付應用程式。" } ] },
  { id: "w924", english: "proponent", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["支持者","提倡者"] ] } ],
    examples: [ { en:"He is a leading proponent of remote work policies within the industry.", zh:"他是業界推動遠距工作政策的主要提倡者之一。" } ] },
  { id: "w925", english: "put forward", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["提出"] ] } ],
    examples: [ { en:"The consultant put forward a proposal to cut operating costs.", zh:"這位顧問提出了一項削減營運成本的方案。" } ] },
  { id: "w926", english: "scrub", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["用力刷洗","擦洗乾淨"] ] } ],
    examples: [ { en:"The cleaning crew scrubbed the lobby floor before the client's visit.", zh:"清潔人員在客戶來訪前刷洗了大廳地板。" } ] },
  { id: "w927", english: "site inspection", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["現場勘查","場地檢查"] ] } ],
    examples: [ { en:"The engineer conducted a site inspection before approving the construction plan.", zh:"工程師在核准施工計畫前先進行了現場勘查。" } ] },
  { id: "w928", english: "strew", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["散置","散落"] ] } ],
    examples: [ { en:"Papers were strewn across the desk after the meeting.", zh:"會議結束後，文件散落在桌上。" } ] },
  { id: "w929", english: "take initiative", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["主動採取行動"] ] } ],
    examples: [ { en:"New employees are encouraged to take initiative rather than wait for instructions.", zh:"公司鼓勵新員工主動採取行動，而不是等待指示。" } ] },
  { id: "w930", english: "telecommute", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vi", meaningGroups: [ ["遠端工作","居家辦公"] ] } ],
    examples: [ { en:"Many employees now telecommute two or three days a week.", zh:"現在許多員工每週有兩三天居家遠端工作。" } ] },
  { id: "w931", english: "throw one's effort into", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["全力投入"] ] } ],
    examples: [ { en:"She threw all her effort into completing the project ahead of schedule.", zh:"她全力投入，提前完成了這個專案。" } ] },
  { id: "w932", english: "acquaintance", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["認識的人","相識"] ] } ],
    examples: [ { en:"He is more of a business acquaintance than a close friend.", zh:"他比較算是生意上認識的人，而不是親密的朋友。" } ] },
  { id: "w933", english: "ambiance", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["氛圍","環境氣氛"] ] } ],
    examples: [ { en:"The restaurant's cozy ambiance makes it popular for client dinners.", zh:"這家餐廳溫馨的氛圍使它很受歡迎，適合用來招待客戶晚餐。" } ] },
  { id: "w934", english: "aspiration", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["渴望達成的目標","志向"] ] } ],
    examples: [ { en:"Her career aspiration is to become the company's next chief financial officer.", zh:"她的職業志向是成為公司下一任財務長。" } ] },
  { id: "w935", english: "business contact", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["商業人脈","業務聯絡人"] ] } ],
    examples: [ { en:"He made several valuable business contacts at the trade fair.", zh:"他在這場貿易展上結識了幾位寶貴的商業人脈。" } ] },
  { id: "w936", english: "copy editor", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["文字編輯","校稿編輯"] ] } ],
    examples: [ { en:"The copy editor checked the brochure for spelling and grammar errors before printing.", zh:"文字編輯在印刷前檢查了手冊中的拼字與文法錯誤。" } ] },
  { id: "w937", english: "discerning", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["有鑑別力的","判斷敏銳的"] ] } ],
    examples: [ { en:"The brand caters to discerning customers who value quality over price.", zh:"這個品牌迎合的是重視品質勝過價格、有鑑別力的顧客。" } ] },
  { id: "w938", english: "draw on", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["運用","借助"] ] } ],
    examples: [ { en:"The consultant drew on years of experience to solve the client's problem.", zh:"這位顧問運用了多年的經驗來解決客戶的問題。" } ] },
  { id: "w939", english: "entrust A with B", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["將某物託付給某人","委託某人照管某物"] ] } ],
    examples: [ { en:"The board entrusted the new CEO with turning the company around.", zh:"董事會將扭轉公司局勢的重任託付給了新任執行長。" } ] },
  { id: "w940", english: "have one's hands full", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["忙得不可開交"] ] } ],
    examples: [ { en:"With three major projects due this month, she has her hands full.", zh:"這個月有三個大型專案要交，她忙得不可開交。" } ] },
  { id: "w941", english: "in anticipation of", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["為某事而預做準備","預期"] ] } ],
    examples: [ { en:"The store hired extra staff in anticipation of the holiday rush.", zh:"這家店預期假期購物人潮，提前多雇用了員工。" } ] },
  { id: "w942", english: "in the light of", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["鑑於","考慮到"] ] } ],
    examples: [ { en:"In the light of recent complaints, the company revised its return policy.", zh:"鑑於最近的申訴，公司修訂了退貨政策。" } ] },
  { id: "w943", english: "make an outside call", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["撥打對外電話"] ] } ],
    examples: [ { en:"Dial nine first if you need to make an outside call from the office.", zh:"如果你需要從辦公室撥打對外電話，請先撥九。" } ] },
  { id: "w944", english: "obsess about", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["對某事念念不忘","過度掛心"] ] } ],
    examples: [ { en:"He tends to obsess about small details instead of focusing on the bigger picture.", zh:"他容易對小細節念念不忘，而忽略了大局。" } ] },
  { id: "w945", english: "on edge", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["緊張不安的"] ] } ],
    examples: [ { en:"The entire team was on edge waiting for the client's final decision.", zh:"整個團隊都緊張不安地等著客戶的最終決定。" } ] },
  { id: "w946", english: "personal effects", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["個人隨身物品"] ] } ],
    examples: [ { en:"Employees were asked to remove their personal effects from the old office before the move.", zh:"員工被要求在搬遷前把個人物品從舊辦公室清出來。" } ] },
  { id: "w947", english: "propel", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["推動","促使前進"] ] } ],
    examples: [ { en:"Strong online sales propelled the company to record quarterly profits.", zh:"強勁的網路銷售推動該公司創下季度獲利新高。" } ] },
  { id: "w948", english: "recline", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vi", meaningGroups: [ ["向後靠","斜躺"] ] } ],
    examples: [ { en:"Business-class seats allow passengers to recline almost flat.", zh:"商務艙座位讓乘客幾乎可以完全躺平。" } ] },
  { id: "w949", english: "repository", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["儲藏處","存放地"] ] } ],
    examples: [ { en:"The shared drive serves as a repository for all department reports.", zh:"這個共用磁碟機作為所有部門報告的存放處。" } ] },
  { id: "w950", english: "seamless", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["無縫的","順暢無阻的"] ] } ],
    examples: [ { en:"The new system ensures a seamless transition between the old and new software.", zh:"這套新系統確保新舊軟體之間能順暢無阻地轉換。" } ] },
  { id: "w951", english: "sort", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["種類","類型"] ] } ],
    examples: [ { en:"We need a different sort of marketing strategy to reach younger customers.", zh:"我們需要不同類型的行銷策略來接觸年輕顧客。" } ] },
  { id: "w952", english: "supplementary", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["補充的","額外增加的"] ] } ],
    examples: [ { en:"The manual includes supplementary materials for advanced users.", zh:"這份手冊還附有給進階使用者的補充資料。" } ] },
  { id: "w953", english: "trivial", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["微不足道的","不重要的"] ] } ],
    examples: [ { en:"Don't dismiss customer complaints as trivial matters.", zh:"別把顧客的抱怨當作微不足道的小事而不理。" } ] },
  { id: "w954", english: "typewriter", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["打字機"] ] } ],
    examples: [ { en:"The museum displays an antique typewriter used in the company's early office.", zh:"博物館展示著這家公司早期辦公室使用過的一台古董打字機。" } ] },
  { id: "w955", english: "writing pad", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["便條紙本"] ] } ],
    examples: [ { en:"He keeps a writing pad on his desk for jotting down quick notes during calls.", zh:"他在桌上放一本便條紙本，方便通話時隨手記筆記。" } ] },
  { id: "w956", english: "written consent", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["書面同意","書面許可"] ] } ],
    examples: [ { en:"The clinic requires written consent from patients before any procedure.", zh:"診所在進行任何療程前，都要求病人提供書面同意。" } ] },
  { id: "w957", english: "aggravate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["使惡化","加重"] ] } ],
    examples: [ { en:"Delays in shipping only aggravated customers' frustration.", zh:"出貨延誤只讓顧客的不滿情緒更加惡化。" } ] },
  { id: "w958", english: "astute", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["精明的","敏銳的"] ] } ],
    examples: [ { en:"An astute investor recognized the opportunity before the market caught on.", zh:"一位精明的投資人在市場察覺之前就發現了這個機會。" } ] },
  { id: "w959", english: "be up late", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["很晚才睡","熬夜"] ] } ],
    examples: [ { en:"The team was up late finishing the presentation before the client meeting.", zh:"團隊為了在客戶會議前完成簡報，熬夜到很晚。" } ] },
  { id: "w960", english: "compartment", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["隔間","分隔的小空間"] ] } ],
    examples: [ { en:"Important documents are kept in a locked compartment in the filing cabinet.", zh:"重要文件放在檔案櫃中一個上鎖的隔間裡。" } ] },
  { id: "w961", english: "contingency", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["應變措施","意外事件"] ] } ],
    examples: [ { en:"The project manager prepared a contingency plan in case of supplier delays.", zh:"專案經理準備了一份應變計畫，以防供應商延誤。" } ] },
  { id: "w962", english: "customary", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["慣例的","習慣上的"] ] } ],
    examples: [ { en:"It is customary to tip the delivery staff during the holiday season.", zh:"在假期期間給外送人員小費是慣例。" } ] },
  { id: "w963", english: "drag", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["拖","拉"] ] } ],
    examples: [ { en:"Workers dragged the heavy equipment across the warehouse floor.", zh:"工人們把沉重的設備拖過倉庫地面。" } ] },
  { id: "w964", english: "draw a distinction between", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["區分","劃分"] ] } ],
    examples: [ { en:"The contract draws a distinction between full-time and part-time employees.", zh:"這份合約明確區分了全職與兼職員工。" } ] },
  { id: "w965", english: "draw the line at", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["堅決不做","設下底線"] ] } ],
    examples: [ { en:"The manager is flexible about deadlines, but he draws the line at missing safety inspections.", zh:"這位經理對截止日期有彈性，但在跳過安全檢查這件事上堅決不讓步。" } ] },
  { id: "w966", english: "evacuate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["疏散","撤離"] ] } ],
    examples: [ { en:"The building was evacuated immediately after the fire alarm went off.", zh:"火警警報響起後，這棟大樓立即被疏散。" } ] },
  { id: "w967", english: "formality", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["例行程序","形式上的手續"] ] } ],
    examples: [ { en:"Signing the visitor log is just a formality at this office.", zh:"在這間辦公室，登記訪客簽到只是一項形式上的手續。" } ] },
  { id: "w968", english: "give way to", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["讓步於","被取代"] ] } ],
    examples: [ { en:"Traditional paper filing has gradually given way to digital record-keeping.", zh:"傳統的紙本歸檔已逐漸被數位化的記錄方式取代。" } ] },
  { id: "w969", english: "in commemoration of", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["為紀念"] ] } ],
    examples: [ { en:"The company held a special dinner in commemoration of its fiftieth anniversary.", zh:"公司為紀念五十週年舉辦了一場特別的晚宴。" } ] },
  { id: "w970", english: "look up to", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["敬重","仰慕"] ] } ],
    examples: [ { en:"Junior staff members look up to her for her calm leadership style.", zh:"資淺員工都因她冷靜的領導風格而敬重她。" } ] },
  { id: "w971", english: "on probation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["處於試用期"] ] } ],
    examples: [ { en:"New hires are on probation for the first three months of employment.", zh:"新進員工在到職後的頭三個月處於試用期。" } ] },
  { id: "w972", english: "proofread", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["校對","校讀"] ] } ],
    examples: [ { en:"She proofreads every press release before it is sent to the media.", zh:"她會在每份新聞稿發送給媒體前先校對一遍。" } ] },
  { id: "w973", english: "recondition", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["翻修","整修"] ] } ],
    examples: [ { en:"The company sells reconditioned laptops at a discounted price.", zh:"這家公司以優惠價格出售翻修過的筆記型電腦。" } ] },
  { id: "w974", english: "segregate A from B", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["將某物與某物分開","隔離"] ] } ],
    examples: [ { en:"The firm segregates client funds from its own operating cash.", zh:"這家公司將客戶資金與自身的營運現金分開存放。" } ] },
  { id: "w975", english: "smock", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["罩衫","工作服"] ] } ],
    examples: [ { en:"Factory workers wear a smock to protect their clothes from grease.", zh:"工廠工人穿著罩衫以保護衣物不被油污弄髒。" } ] },
  { id: "w976", english: "stool", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["凳子"] ] } ],
    examples: [ { en:"There are several stools lined up along the reception counter.", zh:"接待櫃檯旁排了好幾張凳子。" } ] },
  { id: "w977", english: "timecard", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["打卡卡","工時記錄卡"] ] } ],
    examples: [ { en:"Employees must swipe their timecard when they arrive and leave.", zh:"員工到達和離開時都必須刷打卡卡。" } ] },
  { id: "w978", english: "wary of", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["對某事提防","不完全信任"] ] } ],
    examples: [ { en:"Investors remain wary of companies with inconsistent earnings reports.", zh:"投資人對財報數字不一致的公司仍保持提防。" } ] },
  { id: "w979", english: "artifact", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["文物","人工製品"] ] } ],
    examples: [ { en:"The exhibition features ancient artifacts recovered from the shipwreck.", zh:"這場展覽展出了從沉船中找到的古代文物。" } ] },
  { id: "w980", english: "artistic", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["藝術的"] ] } ],
    examples: [ { en:"The designer brought a strong artistic vision to the brand's new packaging.", zh:"這位設計師為品牌的新包裝帶來了強烈的藝術風格。" } ] },
  { id: "w981", english: "auditorium", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["禮堂","觀眾席"] ] } ],
    examples: [ { en:"The keynote speech will be held in the main auditorium.", zh:"主題演講將在主禮堂舉行。" } ] },
  { id: "w982", english: "be booked up", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["被預訂滿","訂位已滿"] ] } ],
    examples: [ { en:"The conference hotel is fully booked up for the entire week.", zh:"這家會議飯店整週的房間都已被預訂滿。" } ] },
  { id: "w983", english: "botanical garden", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["植物園"] ] } ],
    examples: [ { en:"The city's botanical garden hosts a popular flower festival every spring.", zh:"這座城市的植物園每年春天都會舉辦一場熱門的花卉節。" } ] },
  { id: "w984", english: "censorship", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["審查制度"] ] } ],
    examples: [ { en:"The report criticized the government's censorship of online news.", zh:"這份報告批評了政府對網路新聞的審查。" } ] },
  { id: "w985", english: "choir", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["合唱團"] ] } ],
    examples: [ { en:"The company choir performs at the annual holiday party.", zh:"公司合唱團在年度假日派對上表演。" } ] },
  { id: "w986", english: "contestant", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["參賽者"] ] } ],
    examples: [ { en:"Over a hundred contestants entered this year's innovation competition.", zh:"今年的創新競賽共有超過一百名參賽者參加。" } ] },
  { id: "w987", english: "enlightening", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["有啟發性的"] ] } ],
    examples: [ { en:"The workshop on data privacy was both enlightening and practical.", zh:"這場關於資料隱私的工作坊既有啟發性又實用。" } ] },
  { id: "w988", english: "excursion", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["短程旅遊","遠足"] ] } ],
    examples: [ { en:"The company organized a weekend excursion to the countryside for its staff.", zh:"公司為員工安排了一場週末的郊區短程旅遊。" } ] },
  { id: "w989", english: "flower bed", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["花圃","花壇"] ] } ],
    examples: [ { en:"Volunteers planted a new flower bed in front of the community center.", zh:"志工在社區中心前種了一個新的花圃。" } ] },
  { id: "w990", english: "grip", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["緊握","牢牢抓住"] ] } ],
    examples: [ { en:"Make sure to grip the railing tightly when walking down the stairs.", zh:"走下樓梯時務必緊握扶手。" } ] },
  { id: "w991", english: "head for", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vi", meaningGroups: [ ["朝某方向前進","前往"] ] } ],
    examples: [ { en:"After the meeting, the delegates headed for the airport.", zh:"會議結束後，代表們前往機場。" } ] },
  { id: "w992", english: "intermission", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["中場休息"] ] } ],
    examples: [ { en:"Refreshments will be available in the lobby during intermission.", zh:"中場休息時，大廳將提供茶點。" } ] },
  { id: "w993", english: "intriguingly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["引人好奇地","有趣地"] ] } ],
    examples: [ { en:"The report intriguingly suggests that remote workers are more productive.", zh:"這份報告有趣地指出，遠距工作者的生產力更高。" } ] },
  { id: "w994", english: "legroom", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["腿部空間"] ] } ],
    examples: [ { en:"Passengers pay extra for seats with more legroom.", zh:"乘客會額外付費以取得腿部空間更大的座位。" } ] },
  { id: "w995", english: "make yourself at home", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["別客氣","當自己家一樣自在"] ] } ],
    examples: [ { en:"\"Make yourself at home,\" the host said as she showed the guests into the living room.", zh:"主人一邊帶客人走進客廳一邊說：「別客氣，當自己家一樣。」" } ] },
  { id: "w996", english: "memoirs", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["回憶錄"] ] } ],
    examples: [ { en:"The retired executive is writing his memoirs about three decades in the industry.", zh:"這位退休高層正在撰寫他在業界三十年的回憶錄。" } ] },
  { id: "w997", english: "mural", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["壁畫"] ] } ],
    examples: [ { en:"A colorful mural now decorates the wall of the office lobby.", zh:"一幅色彩繽紛的壁畫如今裝飾著辦公室大廳的牆面。" } ] },
  { id: "w998", english: "oar", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["船槳"] ] } ],
    examples: [ { en:"He gripped the oars firmly and rowed the boat toward the shore.", zh:"他緊握船槳，把船划向岸邊。" } ] },
  { id: "w999", english: "out of order", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["故障","無法使用"] ] } ],
    examples: [ { en:"The elevator on the third floor has been out of order since Monday.", zh:"三樓的電梯從星期一起就故障了。" } ] },
  { id: "w1000", english: "paddle", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["用槳划"] ] },
      { pos: "nc", meaningGroups: [ ["短槳"] ] }
    ],
    examples: [
      { en:"They paddled the canoe across the calm lake.", zh:"他們用槳划著獨木舟穿過平靜的湖面。" },
      { en:"Each kayak comes with a lightweight paddle.", zh:"每艘輕艇都配有一支輕巧的短槳。" }
    ] },
  { id: "w1001", english: "pass the time", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["消磨時間"] ] } ],
    examples: [ { en:"Passengers played cards to pass the time during the long delay.", zh:"乘客們在長時間的延誤中打牌消磨時間。" } ] },
  { id: "w1002", english: "rake", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["耙子"] ] },
      { pos: "vt", meaningGroups: [ ["耙","用耙子整理"] ] }
    ],
    examples: [
      { en:"He grabbed a rake to clear the leaves from the yard.", zh:"他拿了一支耙子清理院子裡的落葉。" },
      { en:"The gardener raked the fallen leaves into a large pile.", zh:"園丁把落葉耙成一大堆。" }
    ] },
  { id: "w1003", english: "rally", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["拉力賽"] ] } ],
    examples: [ { en:"The automaker sponsors a team in the annual desert rally.", zh:"這家汽車製造商每年都贊助一支車隊參加沙漠拉力賽。" } ] },
  { id: "w1004", english: "roam around", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vi", meaningGroups: [ ["漫遊","四處走動"] ] } ],
    examples: [ { en:"During the layover, we roamed around the airport's duty-free shops.", zh:"轉機期間，我們在機場的免稅商店裡四處逛逛。" } ] },
  { id: "w1005", english: "running time", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["片長","播放時長"] ] } ],
    examples: [ { en:"The documentary has a running time of just under two hours.", zh:"這部紀錄片的片長略少於兩小時。" } ] },
  { id: "w1006", english: "sail", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vi", meaningGroups: [ ["航行","行駛"] ] } ],
    examples: [ { en:"The cargo ship sails from this port every Tuesday.", zh:"這艘貨船每週二從這個港口出發航行。" } ] },
  { id: "w1007", english: "slide down", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vi", meaningGroups: [ ["滑下","向下滑動"] ] } ],
    examples: [ { en:"Boxes slid down the delivery chute into the truck.", zh:"箱子順著送貨滑道滑下，進入卡車裡。" } ] },
  { id: "w1008", english: "sport tournament", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["體育錦標賽","運動賽事"] ] } ],
    examples: [ { en:"The company sponsors a regional sport tournament every summer.", zh:"這家公司每年夏天都贊助一場地區體育錦標賽。" } ] },
  { id: "w1009", english: "stadium", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["體育場","運動場"] ] } ],
    examples: [ { en:"The new stadium can seat up to fifty thousand spectators.", zh:"這座新體育場可容納多達五萬名觀眾。" } ] },
  { id: "w1010", english: "stay tuned", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["請繼續關注","敬請期待"] ] } ],
    examples: [ { en:"Stay tuned for further updates on the product launch date.", zh:"請持續關注產品上市日期的最新消息。" } ] },
  { id: "w1011", english: "stay up", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["很晚才睡","熬夜不睡"] ] } ],
    examples: [ { en:"The accounting team stayed up all night to close the books before the deadline.", zh:"會計團隊為了在截止日期前結帳而熬夜整晚。" } ] },
  { id: "w1012", english: "stroll", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vi", meaningGroups: [ ["散步","閒逛"] ] } ],
    examples: [ { en:"Visitors like to stroll through the exhibition hall before the seminar begins.", zh:"訪客喜歡在研討會開始前在展覽廳裡散步閒逛。" } ] },
  { id: "w1013", english: "touch up", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["修飾","稍加潤色"] ] } ],
    examples: [ { en:"The designer touched up the logo before sending it to the printer.", zh:"設計師在送印之前對商標稍作修飾。" } ] },
  { id: "w1014", english: "transferable", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["可轉移的","可轉調適用的"] ] } ],
    examples: [ { en:"The skills gained in this role are transferable to many other industries.", zh:"這個職位培養的技能可轉用到許多其他產業。" } ] },
  { id: "w1015", english: "unsanitary", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["不衛生的","不潔的"] ] } ],
    examples: [ { en:"Inspectors shut down the kitchen due to unsanitary conditions.", zh:"檢查員因不衛生的環境而勒令這間廚房停業。" } ] },
  { id: "w1016", english: "usher", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["引導","引領"] ] },
      { pos: "nc", meaningGroups: [ ["引座員","接待員"] ] }
    ],
    examples: [
      { en:"A staff member ushered the guests to their seats.", zh:"一名工作人員引導賓客就座。" },
      { en:"The usher handed out programs at the entrance of the hall.", zh:"接待員在大廳入口處分發節目單。" }
    ] },
  { id: "w1017", english: "vacate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["騰出","搬離"] ] } ],
    examples: [ { en:"Guests are required to vacate their rooms by noon on the day of checkout.", zh:"房客在退房當天必須在中午前騰出房間。" } ] },
  { id: "w1044", english: "all-out", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["全力的","徹底的"] ] } ],
  examples: [ { en:"The team made an all-out effort to meet the client's deadline.", zh:"團隊全力以赴以趕上客戶的截止日期。" } ]
},
  { id: "w1045", english: "all the way", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "phr.", meaningGroups: [ ["從頭到尾","完全地"] ] } ],
  examples: [ { en:"I'll support your proposal all the way if you decide to present it to the board.", zh:"如果你決定向董事會提出這項提案，我會全力支持你到底。" } ]
},
  { id: "w1046", english: "all walks of life", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "phr.", meaningGroups: [ ["各行各業","各界人士"] ] } ],
  examples: [ { en:"The conference attracted professionals from all walks of life.", zh:"這場研討會吸引了來自各行各業的專業人士。" } ]
},
  { id: "w1047", english: "as opposed to", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "phr.", meaningGroups: [ ["而不是","相對於"] ] } ],
  examples: [ { en:"We decided to launch the product in spring, as opposed to waiting until autumn.", zh:"我們決定在春季推出這項產品，而不是等到秋天。" } ]
},
  { id: "w1048", english: "astonishingly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adv", meaningGroups: [ ["驚人地","令人驚訝地"] ] } ],
  examples: [ { en:"Sales figures rose astonishingly fast after the marketing campaign began.", zh:"行銷活動開始後，銷售數字驚人地快速成長。" } ]
},
  { id: "w1049", english: "at a stretch", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "phr.", meaningGroups: [ ["連續不斷地","一口氣"] ] } ],
  examples: [ { en:"The technicians can work for eight hours at a stretch without a break.", zh:"技術人員可以連續工作八小時而不休息。" } ]
},
  { id: "w1050", english: "back up", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "vt", meaningGroups: [ ["證實","佐證"] ] },
    { pos: "vi", meaningGroups: [ ["回堵","堵塞"] ] }
  ],
  examples: [
    { en:"Her claims were backed up by solid financial data.", zh:"她的說法有可靠的財務數據佐證。" },
    { en:"Traffic began to back up for miles after the accident.", zh:"事故發生後，車流開始回堵數英里。" }
  ]
},
  { id: "w1051", english: "boldly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adv", meaningGroups: [ ["大膽地","勇敢地"] ] } ],
  examples: [ { en:"She boldly proposed a completely new marketing strategy at the meeting.", zh:"她在會議上大膽提出一項全新的行銷策略。" } ]
},
  { id: "w1052", english: "call on", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "phr.", meaningGroups: [ ["呼籲","號召"] ] } ],
  examples: [ { en:"The union called on management to reconsider the new overtime policy.", zh:"工會呼籲管理層重新考慮新的加班政策。" } ]
},
  { id: "w1053", english: "compilation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nu", meaningGroups: [ ["彙編","編纂"] ] } ],
  examples: [ { en:"The compilation of the annual report took the team almost a month.", zh:"彙編這份年度報告花了團隊將近一個月的時間。" } ]
},
  { id: "w1054", english: "comprehensible", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["可理解的","易懂的"] ] } ],
  examples: [ { en:"The instructions were rewritten to make them more comprehensible to new employees.", zh:"這些說明被重新撰寫，讓新員工更容易理解。" } ]
},
  { id: "w1055", english: "confiscation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nu", meaningGroups: [ ["沒收","查扣"] ] } ],
  examples: [ { en:"The customs office is authorized to order the confiscation of counterfeit goods.", zh:"海關有權下令沒收仿冒商品。" } ]
},
  { id: "w1056", english: "constitute", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vt", meaningGroups: [ ["構成","組成"] ] } ],
  examples: [ { en:"Overseas sales constitute nearly half of the company's total revenue.", zh:"海外銷售額幾乎占公司總營收的一半。" } ]
},
  { id: "w1057", english: "contend", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vi", meaningGroups: [ ["競爭","爭奪"] ] } ],
  examples: [ { en:"Three vendors are contending for the government contract.", zh:"三家廠商正在競爭這份政府合約。" } ]
},
  { id: "w1058", english: "definite", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["明確的","確定的"] ] } ],
  examples: [ { en:"We need a definite answer from the client before we can proceed.", zh:"我們需要客戶給出明確的答覆才能繼續進行。" } ]
},
  { id: "w1059", english: "drive up", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "phr.", meaningGroups: [ ["推高","使上漲"] ] } ],
  examples: [ { en:"Rising fuel costs have driven up shipping prices across the industry.", zh:"燃料成本上升已推高整個產業的運輸價格。" } ]
},
  { id: "w1060", english: "expectancy", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nu", meaningGroups: [ ["期待","期盼的心情"] ] } ],
  examples: [ { en:"There was a sense of expectancy in the office before the merger announcement.", zh:"在合併消息公布前，辦公室裡瀰漫著一種期待的氣氛。" } ]
},
  { id: "w1061", english: "feasibility study", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["可行性研究","可行性評估"] ] } ],
  examples: [ { en:"The company commissioned a feasibility study before expanding into the new market.", zh:"公司在拓展新市場前委託進行了一項可行性研究。" } ]
},
  { id: "w1062", english: "fixed price", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["固定價格","固定售價"] ] } ],
  examples: [ { en:"The supplier agreed to a fixed price for the next twelve months.", zh:"供應商同意在未來十二個月內維持固定價格。" } ]
},
  { id: "w1063", english: "forgetfully", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adv", meaningGroups: [ ["健忘地","粗心遺忘地"] ] } ],
  examples: [ { en:"He forgetfully left his laptop on the train after the conference.", zh:"他在會議結束後健忘地把筆電留在了火車上。" } ]
},
  { id: "w1064", english: "gauge", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vt", meaningGroups: [ ["測量","估量"] ] } ],
  examples: [ { en:"Managers use quarterly surveys to gauge employee satisfaction.", zh:"經理們利用季度調查來衡量員工滿意度。" } ]
},
  { id: "w1065", english: "have control over", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "phr.", meaningGroups: [ ["掌控","控制"] ] } ],
  examples: [ { en:"The new manager doesn't yet have control over the department's budget.", zh:"這位新任經理目前還無法掌控部門的預算。" } ]
},
  { id: "w1066", english: "in bloom", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "phr.", meaningGroups: [ ["開花","盛開"] ] } ],
  examples: [ { en:"The garden in front of the office is always in bloom during spring.", zh:"辦公室前的花園每逢春天總是繁花盛開。" } ]
},
  { id: "w1067", english: "in reference to", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "phr.", meaningGroups: [ ["關於","就…而言"] ] } ],
  examples: [ { en:"I am writing in reference to your inquiry about our shipping rates.", zh:"我這封信是關於您詢問的運費事宜。" } ]
},
  { id: "w1068", english: "intervention", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["介入","干預"] ] } ],
  examples: [ { en:"Government intervention helped stabilize the currency during the crisis.", zh:"政府的干預在危機期間有助於穩定貨幣。" } ]
},
  { id: "w1069", english: "irretrievable", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["無法挽回的","不可恢復的"] ] } ],
  examples: [ { en:"The damage to the client relationship was not irretrievable.", zh:"與客戶的關係雖受損，但並非無法挽回。" } ]
},
  { id: "w1070", english: "lose ground", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "phr.", meaningGroups: [ ["失去優勢","落後"] ] } ],
  examples: [ { en:"The company is losing ground to competitors who offer lower prices.", zh:"這家公司正逐漸在提供更低價格的競爭對手面前失去優勢。" } ]
},
  { id: "w1071", english: "make an assessment", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "phr.", meaningGroups: [ ["進行評估","做評估"] ] } ],
  examples: [ { en:"The consultants made an assessment of the factory's production efficiency.", zh:"顧問們對工廠的生產效率進行了評估。" } ]
},
  { id: "w1072", english: "market stall", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["市場攤位"] ] } ],
  examples: [ { en:"She rents a market stall to sell handmade jewelry on weekends.", zh:"她週末租了一個市場攤位來賣手工珠寶。" } ]
},
  { id: "w1073", english: "mediate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vi", meaningGroups: [ ["調解","斡旋"] ] } ],
  examples: [ { en:"A neutral third party was brought in to mediate between the two departments.", zh:"公司請來一位中立的第三方在兩個部門之間調解。" } ]
},
  { id: "w1074", english: "modestly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adv", meaningGroups: [ ["謙虛地","適度地"] ] } ],
  examples: [ { en:"She spoke modestly about her role in closing the deal.", zh:"她在談到自己在成交過程中的角色時顯得十分謙虛。" } ]
},
  { id: "w1075", english: "over the Internet", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "phr.", meaningGroups: [ ["透過網路","經由網際網路"] ] } ],
  examples: [ { en:"More customers now prefer to place orders over the Internet.", zh:"現在越來越多顧客傾向於透過網路下訂單。" } ]
},
  { id: "w1076", english: "perception", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["觀感","看法"] ] } ],
  examples: [ { en:"Public perception of the brand improved after the new ad campaign.", zh:"新的廣告活動推出後，大眾對這個品牌的觀感有所改善。" } ]
},
  { id: "w1077", english: "public profile", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["公眾形象","公開檔案"] ] } ],
  examples: [ { en:"The CEO has kept a low public profile since the scandal.", zh:"自那次醜聞以來，這位執行長一直保持低調的公眾形象。" } ]
},
  { id: "w1078", english: "setback", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["挫折","阻礙"] ] } ],
  examples: [ { en:"The delayed shipment was a major setback for the launch schedule.", zh:"延誤的貨運對上市時程來說是一大挫折。" } ]
},
  { id: "w1079", english: "set forth", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "vt", meaningGroups: [ ["陳述","列出"] ] },
    { pos: "vi", meaningGroups: [ ["出發","啟程"] ] }
  ],
  examples: [
    { en:"The terms of the contract are set forth in section three.", zh:"合約條款列於第三節。" },
    { en:"The delegation set forth on its tour of the new factory early in the morning.", zh:"代表團一大早就啟程前往參觀新工廠。" }
  ]
},
  { id: "w1080", english: "striking", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["顯著的","引人注目的"] ] } ],
  examples: [ { en:"There is a striking difference between the two suppliers' quality standards.", zh:"這兩家供應商的品質標準有著顯著的差異。" } ]
},
  { id: "w1081", english: "telling", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["顯露真相的","意味深長的"] ] } ],
  examples: [ { en:"His hesitation during the interview was a telling sign of his doubts.", zh:"他在面談中的猶豫是他內心疑慮的明顯跡象。" } ]
},
  { id: "w1082", english: "underlying", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["潛在的","根本的"] ] } ],
  examples: [ { en:"The report identifies the underlying causes of the production delays.", zh:"這份報告找出了生產延誤的根本原因。" } ]
},
  { id: "w1083", english: "with the exception of", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "phr.", meaningGroups: [ ["除…之外","除了…以外"] ] } ],
  examples: [ { en:"All departments met their targets, with the exception of sales.", zh:"除了業務部之外，所有部門都達成了目標。" } ]
},
  { id: "w1084", english: "abruptly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adv", meaningGroups: [ ["突然地","意外地"] ] } ],
  examples: [ { en:"The meeting ended abruptly when the fire alarm went off.", zh:"會議因火警警報響起而突然結束。" } ]
},
  { id: "w1085", english: "absorbing", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["引人入勝的","吸引人的"] ] } ],
  examples: [ { en:"The training video was surprisingly absorbing for a compliance course.", zh:"對於一堂法規遵循課程來說，這部訓練影片出乎意料地引人入勝。" } ]
},
  { id: "w1086", english: "assimilate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vi", meaningGroups: [ ["融入","被同化"] ] } ],
  examples: [ { en:"New employees are encouraged to assimilate into the company culture quickly.", zh:"公司鼓勵新員工盡快融入企業文化。" } ]
},
  { id: "w1087", english: "as well as", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "conj", meaningGroups: [ ["以及","不僅…而且"] ] } ],
  examples: [ { en:"The proposal covers cost savings as well as improved efficiency.", zh:"這項提案不僅涵蓋成本節省，還包括效率的提升。" } ]
},
  { id: "w1088", english: "at all costs", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "phr.", meaningGroups: [ ["不惜一切代價"] ] } ],
  examples: [ { en:"The manager insisted on meeting the deadline at all costs.", zh:"經理堅持要不惜一切代價趕上截止日期。" } ]
},
  { id: "w1089", english: "attend to", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "phr.", meaningGroups: [ ["接待","照料"] ] } ],
  examples: [ { en:"The receptionist attended to every visitor as soon as they arrived.", zh:"接待員一有訪客到達便立即接待招呼。" } ]
},
  { id: "w1090", english: "anxious to", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "phr.", meaningGroups: [ ["急切想要的","渴望的"] ] } ],
  examples: [ { en:"The sales team is anxious to close the deal before the quarter ends.", zh:"業務團隊急切想在本季結束前完成這筆交易。" } ]
},
  { id: "w1091", english: "boast", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vi", meaningGroups: [ ["誇耀","自誇"] ] } ],
  examples: [ { en:"The company likes to boast about its award-winning customer service.", zh:"這家公司喜歡誇耀自己屢獲殊榮的客戶服務。" } ]
},
  { id: "w1092", english: "bother", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vi", meaningGroups: [ ["費心","特意去做"] ] } ],
  examples: [ { en:"He didn't even bother to reply to the client's email.", zh:"他甚至沒有費心回覆客戶的電子郵件。" } ]
},
  { id: "w1093", english: "captivate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vt", meaningGroups: [ ["使著迷","吸引住"] ] } ],
  examples: [ { en:"Her presentation captivated the entire audience.", zh:"她的演講讓全場觀眾都為之著迷。" } ]
},
  { id: "w1094", english: "come across", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "phr.", meaningGroups: [ ["偶然遇到","偶然發現"] ] } ],
  examples: [ { en:"I came across an interesting article about supply chain management.", zh:"我偶然看到一篇關於供應鏈管理的有趣文章。" } ]
},
  { id: "w1095", english: "come along", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "phr.", meaningGroups: [ ["出現","一起來"] ] } ],
  examples: [ { en:"A great opportunity like this doesn't come along very often.", zh:"像這樣的好機會並不常出現。" } ]
},
  { id: "w1096", english: "come loose", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "phr.", meaningGroups: [ ["鬆脫","鬆動"] ] } ],
  examples: [ { en:"One of the shelf brackets had come loose and needed tightening.", zh:"其中一個層架支架鬆脫了，需要重新固定。" } ]
},
  { id: "w1097", english: "confront", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vt", meaningGroups: [ ["面對","正視"] ] } ],
  examples: [ { en:"The board had to confront the possibility of a major loss this quarter.", zh:"董事會必須正視本季可能出現重大虧損的情況。" } ]
},
  { id: "w1098", english: "contrive", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vi", meaningGroups: [ ["設法","策劃達成"] ] } ],
  examples: [ { en:"She contrived to finish the report despite the tight deadline.", zh:"儘管截止日期緊迫，她還是設法完成了報告。" } ]
},
  { id: "w1099", english: "culminate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vi", meaningGroups: [ ["達到高潮","最終導致"] ] } ],
  examples: [ { en:"Months of negotiation culminated in a signed partnership agreement.", zh:"數月的談判最終促成了一份正式簽署的合作協議。" } ]
},
  { id: "w1100", english: "defiance", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nu", meaningGroups: [ ["反抗","不服從"] ] } ],
  examples: [ { en:"In defiance of the new policy, some staff continued to work from home.", zh:"有些員工不顧新政策，仍然在家工作以示反抗。" } ]
},
  { id: "w1101", english: "deliberate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["故意的","蓄意的"] ] } ],
  examples: [ { en:"It was a deliberate decision to delay the announcement until after the audit.", zh:"延後到審計之後才公布，是一項刻意的決定。" } ]
},
  { id: "w1102", english: "depict", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vt", meaningGroups: [ ["描繪","描述"] ] } ],
  examples: [ { en:"The brochure depicts the product as eco-friendly and cost-effective.", zh:"宣傳手冊將這項產品描繪成環保又划算的選擇。" } ]
},
  { id: "w1103", english: "dissipate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vi", meaningGroups: [ ["逐漸消散","消失"] ] } ],
  examples: [ { en:"Employee concerns dissipated once management explained the new policy.", zh:"管理層說明新政策後，員工的疑慮便逐漸消散。" } ]
},
  { id: "w1104", english: "driven", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["有幹勁的","一心追求成功的"] ] } ],
  examples: [ { en:"She is a driven professional who always exceeds her sales targets.", zh:"她是個充滿幹勁的專業人士，總是超越自己的銷售目標。" } ]
},
  { id: "w1105", english: "eagerly awaited", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["令人期待已久的","備受期待的"] ] } ],
  examples: [ { en:"The eagerly awaited product launch finally took place this morning.", zh:"這場令人期待已久的產品發表會終於在今天早上舉行了。" } ]
},
  { id: "w1106", english: "elicit", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vt", meaningGroups: [ ["引出","獲得(反應或資訊)"] ] } ],
  examples: [ { en:"The survey was designed to elicit honest feedback from employees.", zh:"這份問卷的設計是為了引出員工誠實的回饋。" } ]
},
  { id: "w1107", english: "fortify", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vt", meaningGroups: [ ["加強","強化"] ] } ],
  examples: [ { en:"The new evidence fortified the company's position in the lawsuit.", zh:"新的證據強化了公司在這場訴訟中的立場。" } ]
},
  { id: "w1108", english: "get back to", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "phr.", meaningGroups: [ ["稍後回覆","再次聯繫"] ] } ],
  examples: [ { en:"I'll get back to you with the exact figures by tomorrow morning.", zh:"我明天早上前會再回覆您確切的數字。" } ]
},
  { id: "w1109", english: "gradual", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["逐漸的","漸進的"] ] } ],
  examples: [ { en:"There has been a gradual increase in online orders over the past year.", zh:"過去一年網路訂單量呈逐漸增加的趨勢。" } ]
},
  { id: "w1110", english: "a great deal", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "phr.", meaningGroups: [ ["大量","許多"] ] } ],
  examples: [ { en:"The new software has saved us a great deal of time on data entry.", zh:"這套新軟體為我們節省了大量的資料輸入時間。" } ]
},
  { id: "w1111", english: "inadequate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["不足的","不夠格的"] ] } ],
  examples: [ { en:"The current storage space is inadequate for the growing inventory.", zh:"目前的倉儲空間對於日益增加的庫存來說是不足的。" } ]
},
  { id: "w1112", english: "in a timely fashion", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "phr.", meaningGroups: [ ["及時地","適時地"] ] } ],
  examples: [ { en:"Please submit your expense reports in a timely fashion.", zh:"請及時提交您的費用報告。" } ]
},
  { id: "w1113", english: "make up one's mind", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "phr.", meaningGroups: [ ["下定決心","做出決定"] ] } ],
  examples: [ { en:"The board still hasn't made up its mind about the acquisition.", zh:"董事會對於這項收購案仍未做出決定。" } ]
},
  { id: "w1114", english: "mingle", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vi", meaningGroups: [ ["交際","混合"] ] } ],
  examples: [ { en:"Guests were encouraged to mingle with clients during the reception.", zh:"在酒會中，賓客們被鼓勵與客戶交際往來。" } ]
},
  { id: "w1115", english: "mobility", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nu", meaningGroups: [ ["流動性","移動能力"] ] } ],
  examples: [ { en:"The new laptop offers greater mobility for employees who travel often.", zh:"這款新筆電為經常出差的員工提供更高的移動性。" } ]
},
  { id: "w1116", english: "put a strain on", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "phr.", meaningGroups: [ ["對…造成壓力","對…造成負擔"] ] } ],
  examples: [ { en:"The sudden increase in orders put a strain on the production line.", zh:"訂單量突然增加對生產線造成了很大的負擔。" } ]
},
  { id: "w1117", english: "put up with", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "phr.", meaningGroups: [ ["容忍","忍受"] ] } ],
  examples: [ { en:"Customers shouldn't have to put up with such long waiting times.", zh:"顧客不應該要忍受這麼長的等待時間。" } ]
},
  { id: "w1118", english: "rave review", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["好評如潮的評論","讚譽有加的評論"] ] } ],
  examples: [ { en:"The new restaurant has received rave reviews from local critics.", zh:"這家新餐廳獲得了當地評論家好評如潮的讚譽。" } ]
},
  { id: "w1119", english: "reach for", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "phr.", meaningGroups: [ ["伸手去拿"] ] } ],
  examples: [ { en:"He reached for the phone the moment it started ringing.", zh:"電話一響，他立刻伸手去拿。" } ]
},
  { id: "w1120", english: "stark", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adj", meaningGroups: [ ["光禿禿的","空蕩蕩的","顯而易見的"] ] },
    { pos: "adv", meaningGroups: [ ["完全地","徹底地"] ] }
  ],
  examples: [
    { en:"The office was stark, with only a desk and a single chair.", zh:"這間辦公室十分空蕩，只有一張桌子和一張椅子。" },
    { en:"After weeks of overtime, he felt he would go stark raving mad.", zh:"連續加班數週後，他覺得自己快要徹底發狂了。" }
  ]
},
  { id: "w1121", english: "steadiness", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nu", meaningGroups: [ ["穩定性","持續不變"] ] } ],
  examples: [ { en:"Investors appreciated the steadiness of the company's quarterly earnings.", zh:"投資人很欣賞這家公司季度盈餘的穩定性。" } ]
},
  { id: "w1122", english: "televise", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vt", meaningGroups: [ ["電視轉播","播送"] ] } ],
  examples: [ { en:"The shareholders' meeting will be televised live for remote investors.", zh:"股東會將為遠端投資人進行電視現場轉播。" } ]
},
  { id: "w1123", english: "abate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vi", meaningGroups: [ ["減弱","平息"] ] } ],
  examples: [ { en:"Consumer demand for the product has not abated despite the price increase.", zh:"儘管漲價，消費者對這項產品的需求並未減弱。" } ]
},
  { id: "w1124", english: "brokerage", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nu", meaningGroups: [ ["仲介業務","經紀業務"] ] } ],
  examples: [ { en:"The firm's main business is insurance brokerage.", zh:"這家公司的主要業務是保險仲介。" } ]
},
  { id: "w1125", english: "business practice", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["商業慣例","經營方式"] ] } ],
  examples: [ { en:"The company updated its business practices to comply with the new regulations.", zh:"這家公司更新了其商業慣例以符合新法規。" } ]
},
  { id: "w1126", english: "conspicuously", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adv", meaningGroups: [ ["顯眼地","明顯地"] ] } ],
  examples: [ { en:"Sales figures were conspicuously lower than in the previous quarter.", zh:"銷售數字明顯低於上一季。" } ]
},
  { id: "w1127", english: "deteriorate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vi", meaningGroups: [ ["惡化","變差"] ] } ],
  examples: [ { en:"Relations with the supplier began to deteriorate after the delayed payment.", zh:"付款延誤後，與供應商的關係開始惡化。" } ]
},
  { id: "w1128", english: "entail", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vt", meaningGroups: [ ["需要","牽涉"] ] } ],
  examples: [ { en:"Expanding into overseas markets entails significant financial risk.", zh:"拓展海外市場需要承擔相當大的財務風險。" } ]
},
  { id: "w1129", english: "flourish", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vi", meaningGroups: [ ["蓬勃發展","興旺"] ] } ],
  examples: [ { en:"The startup has flourished since securing its first round of funding.", zh:"這家新創公司自取得第一輪資金以來蓬勃發展。" } ]
},
  { id: "w1130", english: "foremost", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["最重要的","首要的"] ] } ],
  examples: [ { en:"She is one of the foremost experts in supply chain management.", zh:"她是供應鏈管理領域最頂尖的專家之一。" } ]
},
  { id: "w1131", english: "forerunner", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["先驅","前身"] ] } ],
  examples: [ { en:"The old mainframe system was the forerunner of today's cloud platform.", zh:"那套舊的主機系統是如今雲端平台的前身。" } ]
},
  { id: "w1132", english: "have a monopoly on", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "phr.", meaningGroups: [ ["獨占","壟斷"] ] } ],
  examples: [ { en:"No single supplier has a monopoly on this raw material anymore.", zh:"現在已經沒有任何一家供應商能獨占這項原料了。" } ]
},
  { id: "w1133", english: "implicitly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adv", meaningGroups: [ ["含蓄地","不明說地"] ] } ],
  examples: [ { en:"The memo was implicitly critical of the sales team's performance.", zh:"這份備忘錄含蓄地批評了業務團隊的表現。" } ]
},
  { id: "w1134", english: "indifferent", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["漠不關心的","不感興趣的"] ] } ],
  examples: [ { en:"Some customers remained indifferent to the new loyalty program.", zh:"有些顧客對這項新的忠誠計畫仍然漠不關心。" } ]
},
  { id: "w1135", english: "marketable", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["適合銷售的","有市場的"] ] } ],
  examples: [ { en:"The firm redesigned the packaging to make the product more marketable.", zh:"公司重新設計包裝，讓這項產品更具市場銷售力。" } ]
},
  { id: "w1136", english: "menace", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vt", meaningGroups: [ ["威脅","危及"] ] } ],
  examples: [ { en:"The recall scandal menaced the brand's reputation for months.", zh:"這場召回醜聞威脅該品牌的聲譽長達數月之久。" } ]
},
  { id: "w1137", english: "multilateral", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["多邊的"] ] } ],
  examples: [ { en:"The three countries signed a multilateral trade agreement last year.", zh:"這三個國家去年簽署了一項多邊貿易協定。" } ]
},
  { id: "w1138", english: "perceptible", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["可察覺的","可感覺到的"] ] } ],
  examples: [ { en:"There was a perceptible improvement in customer satisfaction after the training.", zh:"培訓過後，客戶滿意度出現了可察覺的提升。" } ]
},
  { id: "w1139", english: "privatization", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["民營化","私有化"] ] } ],
  examples: [ { en:"The privatization of the state-owned airline sparked heated debate.", zh:"這家國營航空公司的民營化引發了激烈的爭論。" } ]
},
  { id: "w1140", english: "put forth", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "phr.", meaningGroups: [ ["提出","提議"] ] } ],
  examples: [ { en:"Several proposals were put forth during the strategy meeting.", zh:"在策略會議上提出了幾項提案。" } ]
},
  { id: "w1141", english: "ratio", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["比率","比例"] ] } ],
  examples: [ { en:"The ratio of managers to staff in this department is quite low.", zh:"這個部門經理與員工的比例相當低。" } ]
},
  { id: "w1142", english: "retrieval", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nu", meaningGroups: [ ["檢索","取回"] ] } ],
  examples: [ { en:"The new system allows for faster retrieval of customer records.", zh:"這套新系統能夠更快地檢索客戶資料。" } ]
},
  { id: "w1143", english: "runner-up", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["第二名","亞軍"] ] } ],
  examples: [ { en:"Our regional office was the runner-up in the company's innovation award.", zh:"我們的地區辦公室在公司創新獎中獲得第二名。" } ]
},
  { id: "w1144", english: "sluggish", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["遲緩的","不景氣的"] ] } ],
  examples: [ { en:"The retail sector has remained sluggish since the price hikes began.", zh:"自漲價開始以來，零售業一直呈現遲緩不振的狀態。" } ]
},
  { id: "w1145", english: "solitary", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["單獨的","孤獨的"] ] } ],
  examples: [ { en:"A solitary figure remained in the office long after everyone else had left.", zh:"大家都離開後，辦公室裡還留著一個孤獨的身影。" } ]
},
  { id: "w1146", english: "stationary", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["靜止不動的","不變的"] ] } ],
  examples: [ { en:"The delivery truck remained stationary in traffic for over an hour.", zh:"送貨卡車在車流中靜止不動了一個多小時。" } ]
},
  { id: "w1147", english: "synergy", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nu", meaningGroups: [ ["協同效應","合作效益"] ] } ],
  examples: [ { en:"The merger is expected to create synergy between the two companies' sales teams.", zh:"此次合併預期將在兩家公司的業務團隊之間創造協同效應。" } ]
},
  { id: "w1148", english: "synthesis", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["綜合","融合"] ] } ],
  examples: [ { en:"The new product is a synthesis of traditional design and modern technology.", zh:"這項新產品是傳統設計與現代科技的融合。" } ]
},
  { id: "w1149", english: "vicious cycle", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["惡性循環"] ] } ],
  examples: [ { en:"Late deliveries and customer complaints created a vicious cycle for the warehouse team.", zh:"延誤交貨與客戶抱怨為倉儲團隊帶來了惡性循環。" } ]
},
  { id: "w1150", english: "volatile", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["不穩定的","易變動的"] ] } ],
  examples: [ { en:"Currency exchange rates have been extremely volatile this quarter.", zh:"本季匯率波動極為劇烈。" } ]
},
  { id: "w1151", english: "apparel", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nu", meaningGroups: [ ["服飾","衣著"] ] } ],
  examples: [ { en:"The store specializes in outdoor apparel for hiking and camping.", zh:"這家店專門銷售登山露營用的戶外服飾。" } ]
},
  { id: "w1152", english: "at a discounted price", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "phr.", meaningGroups: [ ["以折扣價","以優惠價"] ] } ],
  examples: [ { en:"Employees can purchase company products at a discounted price.", zh:"員工可以以折扣價購買公司產品。" } ]
},
  { id: "w1153", english: "at a substantial discount", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "phr.", meaningGroups: [ ["以相當大的折扣","以大幅折扣"] ] } ],
  examples: [ { en:"Retailers who order in bulk can buy at a substantial discount.", zh:"大量訂購的零售商可以享有相當大的折扣。" } ]
},
  { id: "w1154", english: "at the moment", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "phr.", meaningGroups: [ ["目前","此刻"] ] } ],
  examples: [ { en:"The manager is unavailable at the moment, but she'll call you back.", zh:"經理目前無法接聽，但她稍後會回電給您。" } ]
},
  { id: "w1155", english: "by no means", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "phr.", meaningGroups: [ ["絕非","決不"] ] } ],
  examples: [ { en:"Reaching this quarter's target is by no means guaranteed.", zh:"達成本季目標絕非萬無一失。" } ]
},
  { id: "w1156", english: "cash register", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["收銀機"] ] } ],
  examples: [ { en:"The cash register malfunctioned during the store's busiest hour.", zh:"收銀機在商店最忙碌的時段故障了。" } ]
},
  { id: "w1157", english: "conversely", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adv", meaningGroups: [ ["相反地","反之"] ] } ],
  examples: [ { en:"Sales rose in the north region; conversely, they fell sharply in the south.", zh:"北區的銷售額上升；相反地，南區則急劇下滑。" } ]
},
  { id: "w1158", english: "cooking utensils", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["烹飪用具","廚具"] ] } ],
  examples: [ { en:"The kitchen was fully equipped with modern cooking utensils.", zh:"這間廚房配備了齊全的現代炊具。" } ]
},
  { id: "w1159", english: "dilute", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vt", meaningGroups: [ ["稀釋","沖淡"] ] } ],
  examples: [ { en:"The cleaning solution must be diluted with water before use.", zh:"這種清潔液使用前必須先用水稀釋。" } ]
},
  { id: "w1160", english: "embellish", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vt", meaningGroups: [ ["裝飾","美化"] ] } ],
  examples: [ { en:"The report seemed to embellish the actual sales figures.", zh:"這份報告似乎誇大美化了實際的銷售數字。" } ]
},
  { id: "w1161", english: "embroider", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vt", meaningGroups: [ ["刺繡","繡花"] ] } ],
  examples: [ { en:"The company logo was embroidered onto every staff uniform.", zh:"公司標誌被繡在每一件員工制服上。" } ]
},
  { id: "w1162", english: "exhilarating", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["令人興奮的","振奮人心的"] ] } ],
  examples: [ { en:"Closing the biggest deal of the year was an exhilarating experience.", zh:"談成年度最大的一筆交易是一次令人振奮的經驗。" } ]
},
  { id: "w1163", english: "exorbitant", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["過高的","過分的"] ] } ],
  examples: [ { en:"The vendor charged an exorbitant fee for a simple repair.", zh:"這家廠商為一項簡單的維修收取了過高的費用。" } ]
},
  { id: "w1164", english: "exposition", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["展覽會","博覽會"] ] } ],
  examples: [ { en:"The company showcased its new products at the trade exposition.", zh:"這家公司在貿易博覽會上展示了新產品。" } ]
},
  { id: "w1165", english: "extravagance", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nu", meaningGroups: [ ["奢侈","浪費"] ] } ],
  examples: [ { en:"The board criticized the executive's extravagance during business trips.", zh:"董事會批評這位主管出差時的奢侈浪費。" } ]
},
  { id: "w1166", english: "generic", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["通用的","無品牌的"] ] } ],
  examples: [ { en:"The pharmacy also sells generic versions of popular medications.", zh:"這家藥局也販售暢銷藥品的無品牌通用版。" } ]
},
  { id: "w1167", english: "glassware", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nu", meaningGroups: [ ["玻璃器皿"] ] } ],
  examples: [ { en:"The showroom displayed an elegant collection of glassware.", zh:"展示間陳列著一系列精緻的玻璃器皿。" } ]
},
  { id: "w1168", english: "lavish", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["豪華的","奢華的"] ] } ],
  examples: [ { en:"The company hosted a lavish dinner to celebrate its anniversary.", zh:"公司舉辦了一場豪華晚宴來慶祝週年紀念。" } ]
},
  { id: "w1169", english: "make no difference", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "phr.", meaningGroups: [ ["沒有影響","沒有差別"] ] } ],
  examples: [ { en:"It will make no difference whether we ship today or tomorrow.", zh:"無論是今天還是明天出貨都沒有差別。" } ]
},
  { id: "w1170", english: "observably", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adv", meaningGroups: [ ["明顯可見地","顯而易見地"] ] } ],
  examples: [ { en:"Customer wait times have observably decreased since the new system was installed.", zh:"自從新系統安裝後，顧客的等待時間明顯縮短了。" } ]
},
  { id: "w1171", english: "overcoat", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["大衣","外套"] ] } ],
  examples: [ { en:"He left his overcoat in the conference room after the meeting.", zh:"會議結束後，他把大衣忘在會議室裡了。" } ]
},
  { id: "w1172", english: "readership", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nu", meaningGroups: [ ["讀者群"] ] } ],
  examples: [ { en:"The magazine's readership has grown steadily since it went digital.", zh:"這份雜誌自轉為數位版以來，讀者群穩定成長。" } ]
},
  { id: "w1173", english: "readily", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adv", meaningGroups: [ ["容易地","欣然地"] ] } ],
  examples: [ { en:"Spare parts for this model are readily available online.", zh:"這款型號的備用零件在網路上很容易買到。" } ]
},
  { id: "w1174", english: "redeem", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vt", meaningGroups: [ ["兌換","贖回"] ] } ],
  examples: [ { en:"Customers can redeem their points for a discount on future purchases.", zh:"顧客可以用點數兌換未來購物的折扣。" } ]
},
  { id: "w1175", english: "shoelace", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["鞋帶"] ] } ],
  examples: [ { en:"A loose shoelace caused him to trip on the factory floor.", zh:"一條鬆脫的鞋帶讓他在工廠地板上摔了一跤。" } ]
},
  { id: "w1176", english: "showcase", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["展示櫃","陳列櫃"], ["展現特色的場合","展示的舞台"] ] } ],
  examples: [
    { en:"The jewelry was displayed in a locked showcase near the entrance.", zh:"珠寶陳列在入口附近一個上鎖的展示櫃裡。" },
    { en:"The trade fair served as a showcase for the region's latest technology.", zh:"這場貿易展成為展現該地區最新科技的舞台。" }
  ]
},
  { id: "w1177", english: "sleeve", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["衣袖","袖子"] ] } ],
  examples: [ { en:"The uniform's sleeves needed to be shortened for a better fit.", zh:"這件制服的袖子需要改短才會更合身。" } ]
},
  { id: "w1178", english: "stack", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["一疊","一堆"] ] } ],
  examples: [ { en:"A stack of unpaid invoices was sitting on the accountant's desk.", zh:"會計的桌上堆著一疊未付的發票。" } ]
},
  { id: "w1179", english: "storefront", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["店面","店頭"] ] } ],
  examples: [ { en:"The bakery renovated its storefront to attract more foot traffic.", zh:"這家麵包店翻修了店面以吸引更多人流。" } ]
},
  { id: "w1180", english: "tailor", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["裁縫師","裁縫"] ] } ],
  examples: [ { en:"The tailor adjusted the sleeves of the new uniform overnight.", zh:"裁縫師一夜之間就把新制服的袖子改好了。" } ]
},
  { id: "w1181", english: "take an order", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "phr.", meaningGroups: [ ["受理訂單","幫忙點餐"] ] } ],
  examples: [ { en:"The waiter came over to take our order as soon as we sat down.", zh:"我們一坐下，服務生就過來幫我們點餐。" } ]
},
  { id: "w1182", english: "undercharge", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vt", meaningGroups: [ ["少收費","收費過低"] ] } ],
  examples: [ { en:"The cashier accidentally undercharged the customer by ten dollars.", zh:"收銀員不小心少收了顧客十美元。" } ]
},
  { id: "w1183", english: "underline", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vt", meaningGroups: [ ["強調","凸顯"] ] } ],
  examples: [ { en:"The report underlines the need for better inventory control.", zh:"這份報告強調了改善庫存管理的必要性。" } ]
},
  { id: "w1184", english: "valid", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["有效的","有效力的"] ] } ],
  examples: [ { en:"Your parking permit is valid for one calendar year.", zh:"您的停車證在一個日曆年內有效。" } ]
},
  { id: "w1185", english: "watchband", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["錶帶"] ] } ],
  examples: [ { en:"He bought a leather watchband as a gift for his colleague.", zh:"他買了一條皮革錶帶作為送給同事的禮物。" } ]
},
  { id: "w1186", english: "wind", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vt", meaningGroups: [ ["上鏈","轉緊發條"] ] } ],
  examples: [ { en:"The old grandfather clock still needs to be wound by hand every week.", zh:"這座老爺鐘仍然需要每週手動上鏈。" } ]
},
  { id: "w1187", english: "wrap", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vt", meaningGroups: [ ["包裝","包裹"] ] } ],
  examples: [ { en:"The staff offered to wrap the present free of charge.", zh:"店員主動提議免費包裝這份禮物。" } ]
},
  { id: "w1188", english: "electronics", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nu", meaningGroups: [ ["電子學","電子產業"] ] } ],
  examples: [ { en:"The electronics industry has seen rapid growth in the past decade.", zh:"電子產業在過去十年間快速成長。" } ]
},
  { id: "w1189", english: "evolve", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "vi", meaningGroups: [ ["演化","逐漸發展"] ] },
    { pos: "vt", meaningGroups: [ ["使演化","使逐漸發展"] ] }
  ],
  examples: [
    { en:"The company's business model has evolved significantly over the years.", zh:"這家公司的商業模式多年來已顯著演變。" },
    { en:"New regulations are evolving the way logistics companies operate.", zh:"新法規正促使物流公司改變其運作方式。" }
  ]
},
  { id: "w1190", english: "exploration", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nu", meaningGroups: [ ["探勘","探索"] ] } ],
  examples: [ { en:"The firm invested heavily in the exploration of new energy sources.", zh:"這家公司在新能源的探勘上投入了大量資金。" } ]
},
  { id: "w1191", english: "implant", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vt", meaningGroups: [ ["植入"], ["灌輸","注入"] ] } ],
  examples: [
    { en:"A microchip was implanted in the device for tracking purposes.", zh:"這個裝置被植入一個微晶片以便追蹤。" },
    { en:"The mentor implanted a strong sense of responsibility in his interns.", zh:"這位導師在實習生心中灌輸了強烈的責任感。" }
  ]
},
  { id: "w1192", english: "intently", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adv", meaningGroups: [ ["專注地","全神貫注地"] ] } ],
  examples: [ { en:"She listened intently as the client explained the complaint.", zh:"她專注地聽著客戶說明這項投訴。" } ]
},
  { id: "w1193", english: "limited edition", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["限量版"] ] } ],
  examples: [ { en:"The brand released a limited edition of its bestselling watch.", zh:"該品牌推出了其暢銷手錶的限量版。" } ]
},
  { id: "w1194", english: "ornamental", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adj", meaningGroups: [ ["裝飾性的","裝飾用的"] ] },
    { pos: "nc", meaningGroups: [ ["裝飾品"] ] }
  ],
  examples: [
    { en:"Ornamental plants were placed throughout the lobby for the grand opening.", zh:"開幕典禮時，大廳各處擺放了裝飾性植物。" },
    { en:"Several ornamentals lined the entrance to the showroom.", zh:"展示間入口兩側擺了幾件裝飾品。" }
  ]
},
  { id: "w1195", english: "remnant", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["剩餘部分","殘餘"] ] } ],
  examples: [ { en:"The factory sells fabric remnants at a discounted rate.", zh:"這家工廠以優惠價出售剩餘的布料。" } ]
},
  { id: "w1196", english: "specimen", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["樣品","範例"], ["檢驗樣本"] ] } ],
  examples: [
    { en:"The lab kept a specimen of the defective material for testing.", zh:"實驗室保留了一份不良材料的樣本以供測試。" },
    { en:"Employees were asked to provide a urine specimen for the health check.", zh:"員工被要求提供尿液樣本以進行健康檢查。" }
  ]
},
  { id: "w1197", english: "staple", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["主要產品","必需品"] ] },
    { pos: "adj", meaningGroups: [ ["主要的","基本的"] ] }
  ],
  examples: [
    { en:"Rice remains a staple in many Asian diets.", zh:"米飯仍是許多亞洲飲食中的主食。" },
    { en:"Customer service training is a staple part of new employee orientation.", zh:"客服培訓是新員工訓練中不可或缺的基本項目。" }
  ]
},
  { id: "w1198", english: "apparatus", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["器械","裝置"] ] } ],
  examples: [ { en:"The engineers tested the new safety apparatus before installation.", zh:"工程師在安裝前先測試了這套新的安全裝置。" } ]
},
  { id: "w1199", english: "carry out", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "phr.", meaningGroups: [ ["執行","實施"] ] } ],
  examples: [ { en:"The audit was carried out by an independent accounting firm.", zh:"這項審計是由一家獨立會計事務所執行的。" } ]
},
  { id: "w1200", english: "be geared to", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "phr.", meaningGroups: [ ["針對…而設計","符合…需求"] ] } ],
  examples: [ { en:"The training program is geared to the needs of first-time managers.", zh:"這項培訓課程是針對初任經理人的需求而設計的。" } ]
},
  { id: "w1201", english: "bewildering", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["令人困惑的"] ] } ],
  examples: [ { en:"The new expense system was bewildering to most of the staff at first.", zh:"這套新的報帳系統起初讓大部分員工感到困惑。" } ]
},
  { id: "w1202", english: "bring out", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "phr.", meaningGroups: [ ["推出(產品)"] ] } ],
  examples: [ { en:"The company plans to bring out a lighter version of the model next year.", zh:"這家公司計畫明年推出這款產品的輕量版。" } ]
},
  { id: "w1203", english: "complementary", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["互補的"] ] } ],
  examples: [ { en:"The two departments play complementary roles in product development.", zh:"這兩個部門在產品開發中扮演互補的角色。" } ]
},
  { id: "w1204", english: "composition", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nu", meaningGroups: [ ["組成","構成"] ] },
    { pos: "nc", meaningGroups: [ ["作品","創作"] ] }
  ],
  examples: [
    { en:"The composition of the new alloy makes it more durable.", zh:"這種新合金的組成讓它更加耐用。" },
    { en:"This report is one of the analyst's most detailed compositions.", zh:"這份報告是這位分析師最詳盡的作品之一。" }
  ]
},
  { id: "w1205", english: "concurrently", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adv", meaningGroups: [ ["同時地"] ] } ],
  examples: [ { en:"The two projects were carried out concurrently to save time.", zh:"這兩個專案同時進行以節省時間。" } ]
},
  { id: "w1206", english: "configuration", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["配置","佈局"] ] } ],
  examples: [ { en:"The IT team tested several configurations before finalizing the network setup.", zh:"資訊團隊在敲定網路設置前測試了多種配置。" } ]
},
  { id: "w1207", english: "distill", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vt", meaningGroups: [ ["蒸餾"], ["提煉精華","濃縮精要"] ] } ],
  examples: [
    { en:"The whisky is distilled twice before it is aged in oak barrels.", zh:"這款威士忌在橡木桶中陳年之前會蒸餾兩次。" },
    { en:"The consultant distilled hours of research into a two-page summary.", zh:"這位顧問把數小時的研究提煉成一份兩頁的摘要。" }
  ]
},
  { id: "w1208", english: "dysfunction", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["功能失調","故障"] ] } ],
  examples: [ { en:"A dysfunction in the billing system caused several duplicate charges.", zh:"帳務系統的一項功能失調導致多筆重複扣款。" } ]
},
  { id: "w1209", english: "steer", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "vt", meaningGroups: [ ["駕駛","操控方向"], ["引導","導向"] ] } ],
  examples: [
    { en:"She carefully steered the forklift through the narrow warehouse aisle.", zh:"她小心地操控堆高機穿過狹窄的倉庫走道。" },
    { en:"The host steered the conversation back to the budget proposal.", zh:"主持人把話題引導回預算提案上。" }
  ]
},
  { id: "w1210", english: "sturdily", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adv", meaningGroups: [ ["堅固地","結實地"], ["堅定地","堅決地"] ] } ],
  examples: [
    { en:"The packaging was sturdily built to survive long-distance shipping.", zh:"這款包裝結構堅固，足以承受長途運送。" },
    { en:"He stated his position sturdily during the negotiation.", zh:"他在談判中堅定地表明了自己的立場。" }
  ]
},
  { id: "w1211", english: "transparent", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["透明的"] ] } ],
  examples: [ { en:"The new policy makes the promotion process more transparent.", zh:"這項新政策讓升遷流程變得更加透明。" } ]
},
  { id: "w1212", english: "trial period", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "nc", meaningGroups: [ ["試用期"] ] } ],
  examples: [ { en:"New software is offered with a 30-day trial period.", zh:"新軟體提供三十天的試用期。" } ]
},
  { id: "w1213", english: "vulnerable", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [ { pos: "adj", meaningGroups: [ ["易受傷害的","脆弱的"] ] } ],
  examples: [ { en:"Small businesses are particularly vulnerable to sudden market changes.", zh:"小型企業特別容易受到市場劇烈變動的影響。" } ]
},
  { id: "w1238", english: "arable", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["耕種的","適於耕作的"] ] } ],
    examples: [ { en:"This region has vast arable land suitable for growing wheat.", zh:"這個地區擁有大片適合種植小麥的耕地。" } ] },
  { id: "w1239", english: "broadly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["大體上","概括地說"] ] } ],
    examples: [ { en:"Broadly speaking, the new policy has been well received by employees.", zh:"大體而言，新政策受到員工的歡迎。" } ] },
  { id: "w1240", english: "combustible", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["易燃的","可燃的"] ] } ],
    examples: [ { en:"The warehouse stores combustible materials that require special handling.", zh:"這座倉庫存放需要特別處理的易燃物品。" } ] },
  { id: "w1241", english: "come apart", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["破裂","散開","裂成碎片"] ] } ],
    examples: [ { en:"The old packaging came apart as soon as we opened the box.", zh:"我們一打開箱子，舊包裝就散開了。" } ] },
  { id: "w1242", english: "continuity", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["連續性","持續性"] ] } ],
    examples: [ { en:"The company values continuity in its management team during the transition.", zh:"公司在過渡期間重視管理團隊的連續性。" } ] },
  { id: "w1243", english: "disassemble", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["拆卸","拆解"] ] } ],
    examples: [ { en:"Technicians disassembled the machine to locate the fault.", zh:"技術人員拆解機器以找出故障原因。" } ] },
  { id: "w1244", english: "fabricate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["捏造","虛構"], ["製造","生產(產品)"] ] } ],
    examples: [
      { en:"The employee fabricated an excuse for missing the deadline.", zh:"那名員工捏造了藉口來解釋錯過截止日期的原因。" },
      { en:"The parts are fabricated at our overseas factory before assembly.", zh:"這些零件是在我們海外工廠製造後再進行組裝。" }
    ] },
  { id: "w1245", english: "fitted", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["合身的","量身訂做的"], ["固定式的","嵌入式的"] ] } ],
    examples: [
      { en:"She wore a well-fitted suit to the client meeting.", zh:"她穿了一件合身的套裝去見客戶。" },
      { en:"The office has a fitted kitchen for staff use.", zh:"辦公室有一個固定式的廚房供員工使用。" }
    ] },
  { id: "w1246", english: "flow chart", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["流程圖"] ] } ],
    examples: [ { en:"The manager drew a flow chart to explain the approval process.", zh:"經理畫了一張流程圖來說明審核流程。" } ] },
  { id: "w1247", english: "gem", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["寶石","珠寶"], ["極好的人或事物","珍寶"] ] } ],
    examples: [
      { en:"The jeweler displayed a collection of rare gems.", zh:"珠寶商展示了一批稀有的寶石。" },
      { en:"Our new assistant is a real gem; she handles everything efficiently.", zh:"我們的新助理真是個寶，她把每件事都處理得很有效率。" }
    ] },
  { id: "w1248", english: "generator", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["發電機"] ] } ],
    examples: [ { en:"The factory installed a backup generator in case of power outages.", zh:"工廠安裝了一台備用發電機以應付停電情況。" } ] },
  { id: "w1249", english: "go out of production", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["停產"] ] } ],
    examples: [ { en:"That model went out of production last year.", zh:"那款產品去年已經停產了。" } ] },
  { id: "w1250", english: "grease", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["油脂","潤滑油"] ] } ],
    examples: [ { en:"Workers applied grease to the machine's moving parts.", zh:"工人在機器的運轉部件上塗抹潤滑油。" } ] },
  { id: "w1251", english: "identically", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["完全相同地","一模一樣地"] ] } ],
    examples: [ { en:"The two branches are decorated identically.", zh:"這兩家分店的裝潢完全相同。" } ] },
  { id: "w1252", english: "integration", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["整合","融合"] ] } ],
    examples: [ { en:"The merger required careful integration of the two companies' systems.", zh:"這次合併需要謹慎整合兩家公司的系統。" } ] },
  { id: "w1253", english: "liquidity", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["流動性","資金週轉能力"] ] } ],
    examples: [ { en:"The firm's liquidity improved after collecting overdue payments.", zh:"公司收回逾期款項後，資金流動性有所改善。" } ] },
  { id: "w1254", english: "made-to-order", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["訂製的","按客戶要求製作的"] ] } ],
    examples: [ { en:"The tailor specializes in made-to-order suits.", zh:"這位裁縫師專門製作訂製套裝。" } ] },
  { id: "w1255", english: "make an exception", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["破例","例外處理"] ] } ],
    examples: [ { en:"The manager agreed to make an exception for the late submission.", zh:"經理同意對這次逾期提交的情況破例處理。" } ] },
  { id: "w1256", english: "make public", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["公開","公布"] ] } ],
    examples: [ { en:"The company will make the quarterly results public next Monday.", zh:"公司將在下週一公開這份季報結果。" } ] },
  { id: "w1257", english: "makeup", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["組成","構成方式"] ] } ],
    examples: [ { en:"The board's makeup does not reflect the diversity of the workforce.", zh:"董事會的成員組成並未反映員工的多元性。" } ] },
  { id: "w1258", english: "miniature", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["微型的","縮小的"] ] } ],
    examples: [ { en:"The exhibit features a miniature model of the new headquarters.", zh:"展覽展示了新總部的一個微型模型。" } ] },
  { id: "w1259", english: "much to one's surprise", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["令人非常驚訝的是"] ] } ],
    examples: [ { en:"Much to our surprise, the client accepted the higher quote.", zh:"令我們非常驚訝的是，客戶接受了較高的報價。" } ] },
  { id: "w1260", english: "neatly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["整齊地"], ["巧妙地","精巧地"] ] } ],
    examples: [
      { en:"The files were neatly arranged on the shelf.", zh:"檔案整齊地排放在架子上。" },
      { en:"The announcement was neatly timed to coincide with the product launch.", zh:"這項公告的時間安排得很巧妙，正好配合產品上市。" }
    ] },
  { id: "w1261", english: "nimble", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["敏捷的","反應靈敏的"] ] } ],
    examples: [ { en:"Her nimble mind helped her solve the problem quickly during the meeting.", zh:"她敏捷的思維讓她在會議中迅速解決了問題。" } ] },
  { id: "w1262", english: "obfuscate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["使模糊不清","混淆"] ] } ],
    examples: [ { en:"The report seemed to obfuscate the real cause of the delay.", zh:"這份報告似乎故意模糊了延誤的真正原因。" } ] },
  { id: "w1263", english: "on the spot", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["當場","在事發現場"] ] } ],
    examples: [ { en:"The manager approved the refund on the spot.", zh:"經理當場批准了退款。" } ] },
  { id: "w1264", english: "outlast", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["比…更持久","比…存在得更久"] ] } ],
    examples: [ { en:"The company's brand reputation has outlasted several of its competitors.", zh:"這家公司的品牌聲譽比許多競爭對手存在得更久。" } ] },
  { id: "w1265", english: "output", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["產量","產出"] ] } ],
    examples: [ { en:"Factory output increased by ten percent last quarter.", zh:"工廠的產量在上個季度增加了百分之十。" } ] },
  { id: "w1266", english: "pack away", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["把…收起來","裝箱收好"] ] } ],
    examples: [ { en:"Please pack away the equipment after the presentation.", zh:"簡報結束後請把設備收拾裝箱。" } ] },
  { id: "w1267", english: "perturbed", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["不安的","煩擾的"] ] } ],
    examples: [ { en:"He seemed perturbed by the sudden change in schedule.", zh:"他似乎因行程突然改變而感到不安。" } ] },
  { id: "w1268", english: "pragmatic", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["務實的","實事求是的"] ] } ],
    examples: [ { en:"A pragmatic approach often works better than an idealistic one in business.", zh:"在商業上，務實的做法通常比理想化的做法更有效。" } ] },
  { id: "w1269", english: "precede", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["在…之前","先於"] ] } ],
    examples: [ { en:"A brief introduction should precede the main report.", zh:"主報告之前應該先有一段簡短的介紹。" } ] },
  { id: "w1270", english: "prevail", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vi", meaningGroups: [ ["獲勝","佔優勢"], ["盛行","普遍存在"] ] } ],
    examples: [
      { en:"Reason eventually prevailed over emotion in the negotiation.", zh:"在這次談判中，理性最終佔了上風。" },
      { en:"This attitude still prevails among senior staff.", zh:"這種態度在資深員工中仍然很普遍。" }
    ] },
  { id: "w1271", english: "ready-made", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["現成的","成品的"] ] } ],
    examples: [ { en:"The consultancy offers ready-made business plans for startups.", zh:"這家顧問公司為新創企業提供現成的商業計畫。" } ] },
  { id: "w1272", english: "recede", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vi", meaningGroups: [ ["後退","變得模糊"], ["下降","減少"] ] } ],
    examples: [
      { en:"The noise of the crowd receded as we walked away.", zh:"我們走遠後，人群的噪音漸漸變小消退了。" },
      { en:"Oil prices receded slightly before rising again the following week.", zh:"油價先略微下跌，隔週又再度上漲。" }
    ] },
  { id: "w1273", english: "reproduction", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["複製品","仿製品"] ] },
      { pos: "nu", meaningGroups: [ ["繁殖","生殖"] ] }
    ],
    examples: [
      { en:"The gallery sells reproductions of famous paintings.", zh:"這間畫廊出售名畫的複製品。" },
      { en:"The report includes research on reproduction in local wildlife.", zh:"這份報告包含了對當地野生動物繁殖的研究。" }
    ] },
  { id: "w1274", english: "scale model", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["比例模型","縮小模型"] ] } ],
    examples: [ { en:"The architects built a scale model of the new building for the client.", zh:"建築師為客戶製作了新大樓的比例模型。" } ] },
  { id: "w1275", english: "settle on", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["決定","選定"] ] } ],
    examples: [ { en:"The committee finally settled on a new logo design.", zh:"委員會最終選定了新的商標設計。" } ] },
  { id: "w1276", english: "sort out", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["整理","清理"] ] } ],
    examples: [ { en:"It took all afternoon to sort out the filing cabinet.", zh:"整理檔案櫃花了整個下午的時間。" } ] },
  { id: "w1277", english: "squeak", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vi", meaningGroups: [ ["發出吱吱聲"], ["勉強成功"] ] } ],
    examples: [
      { en:"The office chair squeaks every time someone sits down.", zh:"每次有人坐下，這張辦公椅就會發出吱吱聲。" },
      { en:"He squeaked through the certification exam on his last attempt.", zh:"他在最後一次考試中勉強通過了認證考試。" }
    ] },
  { id: "w1278", english: "synthetic", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["人工合成的","人造的"], ["虛假的","不真誠的"] ] } ],
    examples: [
      { en:"The company switched to synthetic materials to cut costs.", zh:"公司改用人造材料以降低成本。" },
      { en:"Customers criticized the brand's synthetic charm in its advertisements.", zh:"顧客批評該品牌廣告中那種虛假的魅力。" }
    ] },
  { id: "w1279", english: "tie up", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["把…綁緊","捆紮"] ] },
      { pos: "nc", meaningGroups: [ ["業務合作","合作協議"] ] }
    ],
    examples: [
      { en:"Make sure to tie up all the loose cables before the demo.", zh:"示範前請務必把所有鬆散的電線綁好。" },
      { en:"The publisher arranged a tie-up with an overseas distributor.", zh:"這家出版社與一家海外經銷商安排了合作協議。" }
    ] },
  { id: "w1280", english: "unfailingly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["始終不變地","一直"] ] } ],
    examples: [ { en:"She is unfailingly polite to every client, even the difficult ones.", zh:"她對每位客戶始終保持禮貌，即使是難相處的客戶也一樣。" } ] },
  { id: "w1281", english: "unmet", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["未滿足的","未達成的"] ] } ],
    examples: [ { en:"The survey revealed several unmet needs among customers.", zh:"這項調查揭露了顧客有幾項未被滿足的需求。" } ] },
  { id: "w1282", english: "upon", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "prep", meaningGroups: [ ["一…就…","於…之上"] ] } ],
    examples: [ { en:"Upon receiving the confirmation, we shipped the order immediately.", zh:"一收到確認，我們就立即出貨了。" } ] },
  { id: "w1283", english: "wear and tear", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["(正常使用造成的)損耗","磨損"] ] } ],
    examples: [ { en:"The warranty does not cover normal wear and tear.", zh:"保固不包含正常使用造成的損耗。" } ] },
  { id: "w1284", english: "welding", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["焊接"] ] } ],
    examples: [ { en:"The factory hired two specialists skilled in welding.", zh:"工廠聘用了兩位熟練的焊接技師。" } ] },
  { id: "w1285", english: "workbench", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["工作台"] ] } ],
    examples: [ { en:"He keeps all his tools organized on the workbench.", zh:"他把所有工具整齊地放在工作台上。" } ] },
  { id: "w1286", english: "deputy", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["副手","代理人"] ] } ],
    examples: [ { en:"She was appointed deputy manager after years of hard work.", zh:"她經過多年努力後被任命為副理。" } ] },
  { id: "w1287", english: "distress", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["痛苦","憂傷"] ] },
      { pos: "vt", meaningGroups: [ ["使痛苦","使苦惱"] ] }
    ],
    examples: [
      { en:"The layoffs caused considerable distress among the staff.", zh:"這次裁員讓員工感到相當痛苦。" },
      { en:"The unexpected audit distressed several employees.", zh:"這次突如其來的稽核讓好幾位員工感到苦惱。" }
    ] },
  { id: "w1288", english: "factually", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["在事實方面","就事實而言"] ] } ],
    examples: [ { en:"The press release must be factually accurate before it is published.", zh:"這份新聞稿在發布前必須確保事實正確無誤。" } ] },
  { id: "w1289", english: "faulty", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["有缺陷的","故障的"] ] } ],
    examples: [ { en:"The customer returned the faulty printer for a refund.", zh:"顧客退回了那台故障的印表機以要求退款。" } ] },
  { id: "w1290", english: "fleetingly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["短暫地","一閃而過地"] ] } ],
    examples: [ { en:"He glanced at the report only fleetingly before signing it.", zh:"他只是短暫瞥了一下報告就簽了名。" } ] },
  { id: "w1291", english: "graciously", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["親切地","有禮地"] ] } ],
    examples: [ { en:"The CEO graciously thanked all the volunteers for their effort.", zh:"執行長親切地感謝所有志工的付出。" } ] },
  { id: "w1292", english: "handheld", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["手持式的"] ] } ],
    examples: [ { en:"Warehouse staff use handheld scanners to track inventory.", zh:"倉庫員工使用手持式掃描器來追蹤庫存。" } ] },
  { id: "w1293", english: "intercept", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["攔截","截住"] ] } ],
    examples: [ { en:"The security team intercepted a suspicious package at the entrance.", zh:"保全人員在入口處攔截了一個可疑包裹。" } ] },
  { id: "w1294", english: "loaf", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["一條(麵包)"] ] } ],
    examples: [ { en:"She bought a loaf of whole wheat bread from the bakery.", zh:"她在麵包店買了一條全麥麵包。" } ] },
  { id: "w1295", english: "nourish", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["滋養","供給營養"], ["懷有(希望、想法等)"] ] } ],
    examples: [
      { en:"A balanced diet helps nourish the body and mind.", zh:"均衡的飲食有助於滋養身體與心智。" },
      { en:"She has long nourished the hope of starting her own business.", zh:"她長久以來一直懷有創業的夢想。" }
    ] },
  { id: "w1296", english: "pharmacist", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["藥劑師"] ] } ],
    examples: [ { en:"The pharmacist explained the correct dosage of the medicine.", zh:"藥劑師說明了藥物的正確劑量。" } ] },
  { id: "w1297", english: "affair", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["事務","事情"] ] } ],
    examples: [ { en:"She manages her financial affairs very carefully.", zh:"她非常謹慎地管理自己的財務事務。" } ] },
  { id: "w1298", english: "aggression", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["侵略性","攻擊性"] ] } ],
    examples: [ { en:"The negotiation team was trained to handle aggression calmly.", zh:"談判團隊受過訓練，能冷靜應對攻擊性的言行。" } ] },
  { id: "w1299", english: "bare", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["赤裸的","未遮蓋的"], ["最基本的","僅有的"] ] } ],
    examples: [
      { en:"Employees must wear shoes; bare feet are not allowed in the factory.", zh:"員工必須穿鞋，工廠內不允許赤腳。" },
      { en:"Just give me the bare facts of the report, not the details.", zh:"只要告訴我報告最基本的事實就好，不用細節。" }
    ] },
  { id: "w1300", english: "blemish", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["(外表上的)瑕疵"], ["(名聲、性格上的)污點"] ] } ],
    examples: [
      { en:"Quality control removes any product with a visible blemish.", zh:"品管會淘汰任何有明顯瑕疵的產品。" },
      { en:"His record remained without blemish throughout his career.", zh:"他整個職業生涯中的記錄都沒有污點。" }
    ] },
  { id: "w1301", english: "button up", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["扣上鈕釦","扣好"] ] } ],
    examples: [ { en:"He buttoned up his jacket before walking into the meeting.", zh:"他扣好外套鈕釦後才走進會議室。" } ] },
  { id: "w1302", english: "censure", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["嚴厲批評","譴責"] ] },
      { pos: "vt", meaningGroups: [ ["正式譴責"] ] }
    ],
    examples: [
      { en:"The manager's decision came under severe censure from the board.", zh:"經理的決定受到董事會嚴厲的譴責。" },
      { en:"The committee censured him for the lack of transparency.", zh:"委員會譴責他缺乏透明度。" }
    ] },
  { id: "w1303", english: "ceremonial", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["儀式的","典禮的"] ] } ],
    examples: [ { en:"The opening ceremony required everyone to wear ceremonial attire.", zh:"開幕典禮要求每個人都穿著儀式服裝。" } ] },
  { id: "w1304", english: "claims department", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["理賠部門"] ] } ],
    examples: [ { en:"Please contact the claims department to report your loss.", zh:"請聯絡理賠部門申報您的損失。" } ] },
  { id: "w1305", english: "compelling", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["令人信服的"], ["引人入勝的"] ] } ],
    examples: [
      { en:"She presented compelling evidence to support her proposal.", zh:"她提出了令人信服的證據來支持她的提案。" },
      { en:"The documentary about the company's history was compelling.", zh:"這部關於公司歷史的紀錄片非常引人入勝。" }
    ] },
  { id: "w1306", english: "cut back", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["削減","縮減"] ] } ],
    examples: [ { en:"The department had to cut back on travel expenses this year.", zh:"該部門今年必須削減旅行支出。" } ] },
  { id: "w1307", english: "depot", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["倉庫","貨運站","車輛停放場"] ] } ],
    examples: [ { en:"The delivery trucks return to the depot every evening.", zh:"送貨卡車每天晚上都會返回貨運站。" } ] },
  { id: "w1308", english: "prepaid", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["預付的"] ] } ],
    examples: [ { en:"Customers who order online can use a prepaid shipping label.", zh:"線上下單的顧客可以使用預付運費的標籤。" } ] },
  { id: "w1309", english: "retrospective", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["回顧展"] ] },
      { pos: "adj", meaningGroups: [ ["回顧性的","追溯的"] ] }
    ],
    examples: [
      { en:"The museum held a retrospective of the artist's fifty-year career.", zh:"博物館為這位藝術家五十年的生涯舉辦了一場回顧展。" },
      { en:"The company issued a retrospective pay increase for all staff.", zh:"公司為所有員工發布了一項追溯性的加薪。" }
    ] },
  { id: "w1310", english: "slip one's mind", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["被遺忘","忘記"] ] } ],
    examples: [ { en:"Sorry, the meeting completely slipped my mind.", zh:"很抱歉，我完全忘了這場會議。" } ] },
  { id: "w1311", english: "soak up", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["吸收(液體)"] ] } ],
    examples: [ { en:"Use a cloth to soak up the spilled coffee on the desk.", zh:"用布把桌上潑出來的咖啡吸乾。" } ] },
  { id: "w1312", english: "sparsely", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["稀疏地","稀少地"] ] } ],
    examples: [ { en:"The training session was sparsely attended due to the holiday.", zh:"由於是假期，這場訓練課程出席人數很稀少。" } ] },
  { id: "w1313", english: "swiftly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["迅速地"] ] } ],
    examples: [ { en:"Management responded swiftly to the customer complaint.", zh:"管理層迅速回應了客戶的投訴。" } ] },
  { id: "w1314", english: "testimonial", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["推薦信","推薦函"] ] } ],
    examples: [ { en:"He received a glowing testimonial from his former employer.", zh:"他收到了前雇主寫的一份熱情推薦信。" } ] },
  { id: "w1315", english: "unwavering", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["堅定不移的","不動搖的"] ] } ],
    examples: [ { en:"Her unwavering commitment to quality earned the team's respect.", zh:"她對品質堅定不移的堅持贏得了團隊的敬重。" } ] },
  { id: "w1316", english: "wardrobe", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["衣櫥","衣櫃"] ] } ],
    examples: [ { en:"The hotel room comes with a built-in wardrobe.", zh:"這間飯店房間附有一個內嵌式衣櫃。" } ] },
  { id: "w1317", english: "airsickness", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["飛行嘔吐感","暈機"] ] } ],
    examples: [ { en:"She took medication to prevent airsickness during the long flight.", zh:"她服用藥物以預防長途飛行時的暈機。" } ] },
  { id: "w1318", english: "barge", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["駁船","平底貨船"] ] } ],
    examples: [ { en:"The barge carried construction materials down the river.", zh:"這艘駁船沿河運送建築材料。" } ] },
  { id: "w1319", english: "be left unattended", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["無人看管","未受照看"] ] } ],
    examples: [ { en:"Passengers should not leave their luggage left unattended at the airport.", zh:"乘客在機場不應該讓行李無人看管。" } ] },
  { id: "w1320", english: "board a flight", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["登機"] ] } ],
    examples: [ { en:"Passengers should board the flight at least thirty minutes before departure.", zh:"乘客應該在起飛前至少三十分鐘登機。" } ] },
  { id: "w1321", english: "buckle up", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["扣上安全帶"] ] } ],
    examples: [ { en:"Please buckle up before the plane takes off.", zh:"請在飛機起飛前扣好安全帶。" } ] },
  { id: "w1322", english: "carousel", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["行李轉盤"] ] } ],
    examples: [ { en:"We waited by the carousel for our suitcases to arrive.", zh:"我們在行李轉盤旁等候我們的行李箱。" } ] },
  { id: "w1323", english: "charter", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["租用","包租(飛機、船等)"] ] } ],
    examples: [ { en:"The company chartered a plane to fly delegates to the conference.", zh:"公司包租了一架飛機載送代表前往會議。" } ] },
  { id: "w1324", english: "concourse", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["(車站、機場的)大廳","中央通道"] ] } ],
    examples: [ { en:"There is a currency exchange counter in the main concourse.", zh:"主大廳裡有一個貨幣兌換櫃台。" } ] },
  { id: "w1325", english: "confer", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vi", meaningGroups: [ ["商討","交換意見"] ] } ],
    examples: [ { en:"The lawyers conferred before presenting their final decision.", zh:"律師們在提出最終決定之前先進行了商討。" } ] },
  { id: "w1326", english: "deck", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["甲板"] ] } ],
    examples: [ { en:"Passengers gathered on the deck to watch the sunset.", zh:"乘客們聚集在甲板上觀賞日落。" } ] },
  { id: "w1327", english: "disembark", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vi", meaningGroups: [ ["下(船、飛機等)"] ] } ],
    examples: [ { en:"Passengers disembarked as soon as the plane reached the gate.", zh:"飛機一到閘口，乘客們就立刻下機了。" } ] },
  { id: "w1328", english: "dispense", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["分發","提供(物品)"] ] } ],
    examples: [ { en:"The information desk dispenses free maps to tourists.", zh:"服務台會發放免費地圖給遊客。" } ] },
  { id: "w1329", english: "fluid", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["液體"] ] } ],
    examples: [ { en:"Passengers with fever should drink plenty of fluids during the flight.", zh:"發燒的乘客在飛行途中應該多喝液體。" } ] },
  { id: "w1330", english: "harbor", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["港口","海港"] ] } ],
    examples: [ { en:"The hotel overlooks a small fishing harbor.", zh:"這間飯店可以俯瞰一個小漁港。" } ] },
  { id: "w1331", english: "impound", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["(依法)扣押","沒收"] ] } ],
    examples: [ { en:"Customs officers impounded the illegal goods at the border.", zh:"海關人員在邊境扣押了那些違法貨品。" } ] },
  { id: "w1332", english: "layover", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["(旅途中的)短暫停留"] ] } ],
    examples: [ { en:"We had a two-hour layover in Tokyo before the connecting flight.", zh:"我們在轉機前於東京短暫停留了兩小時。" } ] },
  { id: "w1333", english: "life preserver", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["救生圈","救生衣"] ] } ],
    examples: [ { en:"Each seat is equipped with a life preserver under the cushion.", zh:"每個座位的椅墊下都配有一個救生衣。" } ] },
  { id: "w1334", english: "lodging", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["住宿"] ] } ],
    examples: [ { en:"The travel budget covers airfare, meals, and lodging.", zh:"這筆旅行預算包含機票、餐飲和住宿費用。" } ] },
  { id: "w1335", english: "motion sickness", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["動暈症","乘車不適"] ] } ],
    examples: [ { en:"He always takes medicine to avoid motion sickness on long bus rides.", zh:"他在長途搭巴士時總會服藥以避免動暈症。" } ] },
  { id: "w1336", english: "presumable", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["可推測的","可能的"] ] } ],
    examples: [ { en:"The delay was presumable given the severe weather conditions.", zh:"考慮到惡劣的天氣狀況，這次延誤是可以推測到的。" } ] },
  { id: "w1337", english: "quarantine", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["隔離檢疫"] ] } ],
    examples: [ { en:"The imported animals were placed in quarantine for two weeks.", zh:"進口的動物被隔離檢疫了兩週。" } ] },
  { id: "w1338", english: "reclaim", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["取回","索回"] ] } ],
    examples: [ { en:"You can reclaim the tax on business equipment you purchase.", zh:"您可以就購買的商業設備申請退稅。" } ] },
  { id: "w1339", english: "remains", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["殘餘物","剩下的部分"], ["遺跡","遺址"] ] } ],
    examples: [
      { en:"The cleaning crew cleared away the remains of the buffet.", zh:"清潔人員清理掉了自助餐剩下的殘餘食物。" },
      { en:"Tourists visited the remains of an ancient temple nearby.", zh:"遊客參觀了附近一座古廟的遺址。" }
    ] },
  { id: "w1340", english: "remittance", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["匯款"] ] } ],
    examples: [ { en:"She sends a monthly remittance to support her family abroad.", zh:"她每月匯款支持在國外的家人。" } ] },
  { id: "w1341", english: "row the boat", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["划船"] ] } ],
    examples: [ { en:"They had to row the boat back to shore when the engine failed.", zh:"引擎故障後，他們必須划船回到岸邊。" } ] },
  { id: "w1342", english: "seasickness", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["船暈","海上暈船"] ] } ],
    examples: [ { en:"Some passengers suffered from severe seasickness during the crossing.", zh:"有些乘客在渡海途中出現嚴重的船暈。" } ] },
  { id: "w1343", english: "stall", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vi", meaningGroups: [ ["(引擎)突然熄火"] ] } ],
    examples: [ { en:"The engine stalled at the traffic light during rush hour.", zh:"尖峰時間，引擎在紅燈前突然熄火。" } ] },
  { id: "w1344", english: "stop over", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["中途停留"] ] } ],
    examples: [ { en:"We stopped over in Singapore on our way to Sydney.", zh:"我們前往雪梨途中在新加坡中途停留。" } ] },
  { id: "w1345", english: "swap", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["交換","互換"] ] },
      { pos: "nc", meaningGroups: [ ["交換","交換物"] ] }
    ],
    examples: [
      { en:"Can we swap seats so I can sit next to the window?", zh:"我們可以換座位嗎？這樣我就能坐在靠窗的位置。" },
      { en:"The two departments agreed to a staff swap for the summer.", zh:"這兩個部門同意在夏季進行員工交換。" }
    ] },
  { id: "w1346", english: "touch down", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["(飛機)著陸"] ] } ],
    examples: [ { en:"The flight touched down safely despite the storm.", zh:"儘管有暴風雨，班機仍安全著陸。" } ] },
  { id: "w1347", english: "turn up", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["出現","被找到"] ] } ],
    examples: [ { en:"The missing shipment finally turned up at the wrong warehouse.", zh:"遺失的貨物最終在錯誤的倉庫被找到了。" } ] },
  { id: "w1348", english: "unload", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["卸貨","卸下"] ] } ],
    examples: [ { en:"Workers unloaded the containers as soon as the ship docked.", zh:"船一靠岸，工人們就開始卸下貨櫃。" } ] },
  { id: "w1349", english: "annotated", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["附加註解的","有註釋的"] ] } ],
    examples: [ { en:"The manual includes an annotated diagram of the equipment.", zh:"這本手冊包含了一張附加註解的設備圖。" } ] },
  { id: "w1350", english: "arbitration", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["仲裁"] ] } ],
    examples: [ { en:"The dispute was resolved through arbitration instead of going to court.", zh:"這起糾紛透過仲裁解決，而非訴諸法院。" } ] },
  { id: "w1351", english: "be in agreement", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["意見一致","達成共識"] ] } ],
    examples: [ { en:"The board members were all in agreement about the new budget.", zh:"董事會成員對新預算都意見一致。" } ] },
  { id: "w1352", english: "beside the point", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["不相關的","離題的"] ] } ],
    examples: [ { en:"Whether he was late is beside the point; the report is still wrong.", zh:"他是否遲到並不重要；問題在於報告本身有誤。" } ] },
  { id: "w1353", english: "close a deal", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["達成交易"] ] } ],
    examples: [ { en:"The sales team worked overtime to close the deal before the deadline.", zh:"銷售團隊加班工作，只為了在截止前達成這筆交易。" } ] },
  { id: "w1354", english: "dial a number", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["撥打電話號碼"] ] } ],
    examples: [ { en:"You need to dial the extension number to reach the finance office.", zh:"您需要撥打分機號碼才能聯繫到財務部。" } ] },
  { id: "w1355", english: "down payment", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["頭期款","訂金"] ] } ],
    examples: [ { en:"We made a down payment on the new office equipment.", zh:"我們為新的辦公設備支付了頭期款。" } ] },
  { id: "w1356", english: "embark on", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["著手進行","開始從事"] ] } ],
    examples: [ { en:"The company is about to embark on a major expansion project.", zh:"公司即將著手進行一項重大的擴張計畫。" } ] },
  { id: "w1357", english: "enclosure", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["圍欄區域","圍場"], ["(信件中的)附件"] ] } ],
    examples: [
      { en:"The animals are kept in a secure enclosure at the sanctuary.", zh:"這些動物被安置在保育中心一個安全的圍場內。" },
      { en:"Please find the signed contract as an enclosure with this letter.", zh:"請查閱這封信隨附的已簽署合約。" }
    ] },
  { id: "w1358", english: "foil", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["阻止","挫敗(計畫)"] ] } ],
    examples: [ { en:"Security cameras helped foil the attempted theft.", zh:"監視器協助阻止了這次未遂的盜竊。" } ] },
  { id: "w1359", english: "for ages", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["很久","許久"] ] } ],
    examples: [ { en:"We have been waiting for ages for the delivery to arrive.", zh:"我們已經等這件貨品送達很久了。" } ] },
  { id: "w1360", english: "in appreciation of", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["為感謝","以表謝意"] ] } ],
    examples: [ { en:"The company gave out gift cards in appreciation of the staff's hard work.", zh:"公司發放禮物卡以感謝員工的辛勤付出。" } ] },
  { id: "w1361", english: "inconclusively", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["沒有明確結果地","不了了之地"] ] } ],
    examples: [ { en:"The negotiations ended inconclusively after three hours of discussion.", zh:"經過三小時的討論，這次談判卻沒有得出結論。" } ] },
  { id: "w1362", english: "in contrast", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["相比之下","對比之下"] ] } ],
    examples: [ { en:"Sales in the north grew steadily; in contrast, the south saw a decline.", zh:"北部的銷售穩定成長；相比之下，南部則出現下滑。" } ] },
  { id: "w1363", english: "in print", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["(書等)仍在印行","可購得"] ] } ],
    examples: [ { en:"The first edition of the manual is no longer in print.", zh:"這本手冊的第一版已經不再印行了。" } ] },
  { id: "w1364", english: "instrumental in", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["對…有重大作用","是…的關鍵因素"] ] } ],
    examples: [ { en:"She was instrumental in bringing the two companies together.", zh:"她在促成這兩家公司合作上發揮了關鍵作用。" } ] },
  { id: "w1365", english: "in summary", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["總而言之","總之"] ] } ],
    examples: [ { en:"In summary, the project was completed on time and under budget.", zh:"總而言之，這個專案準時完成，而且沒有超出預算。" } ] },
  { id: "w1366", english: "make a deposit", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["存入(款項、押金)"] ] } ],
    examples: [ { en:"You need to make a minimum deposit of five hundred dollars to open the account.", zh:"您需要存入至少五百美元才能開立這個帳戶。" } ] },
  { id: "w1367", english: "make a move", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["採取行動","動身離開"] ] } ],
    examples: [ { en:"It's getting late; I think it's time we made a move.", zh:"時間不早了，我想我們該動身離開了。" } ] },
  { id: "w1368", english: "mediation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["調解","斡旋"] ] } ],
    examples: [ { en:"The dispute was settled through mediation rather than litigation.", zh:"這起糾紛透過調解解決，而非訴訟。" } ] },
  { id: "w1369", english: "moderator", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["調解人","主持人"] ] } ],
    examples: [ { en:"An independent moderator was appointed to oversee the negotiations.", zh:"一位獨立的調解人被指派來監督這次談判。" } ] },
  { id: "w1370", english: "offend", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["犯罪","違法"] ] },
      { pos: "vt", meaningGroups: [ ["冒犯","使不悅"] ] }
    ],
    examples: [
      { en:"If an employee offends again, the company will take disciplinary action.", zh:"如果員工再次違規，公司將採取懲戒措施。" },
      { en:"Her blunt comment offended several colleagues.", zh:"她直白的言論冒犯了幾位同事。" }
    ] },
  { id: "w1371", english: "omission", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["遺漏","疏漏之處"] ] } ],
    examples: [ { en:"The audit found several omissions in the financial statements.", zh:"稽核在財務報表中發現了幾處遺漏。" } ] },
  { id: "w1372", english: "originate in", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["起源於","發源於"] ] } ],
    examples: [ { en:"This manufacturing technique originated in Germany.", zh:"這項製造技術起源於德國。" } ] },
  { id: "w1373", english: "pave", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["鋪(路面)"] ] } ],
    examples: [ { en:"The city plans to pave the road outside the new office park.", zh:"市政府計畫鋪設新辦公園區外的道路。" } ] },
  { id: "w1374", english: "portray", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["描繪","描寫"] ] } ],
    examples: [ { en:"The brochure portrays the company as an innovative leader in the industry.", zh:"這份宣傳手冊將公司描繪成業界創新的領導者。" } ] },
  { id: "w1375", english: "preferential treatment", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["優惠待遇","特殊優待"] ] } ],
    examples: [ { en:"Long-term clients receive preferential treatment on pricing.", zh:"長期客戶在價格上享有優惠待遇。" } ] },
  { id: "w1376", english: "provision", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["(法律或合約中的)條款"] ] } ],
    examples: [ { en:"The contract includes a provision for early termination.", zh:"這份合約中包含一項提前終止的條款。" } ] },
  { id: "w1377", english: "rational", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["理性的","合理的"] ] } ],
    examples: [ { en:"We need to make a rational decision based on the data, not emotion.", zh:"我們必須根據數據做出理性的決定，而非憑感覺。" } ] },
  { id: "w1378", english: "recollection", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["回憶","記憶中的事"] ] },
      { pos: "nu", meaningGroups: [ ["記憶力","回想能力"] ] }
    ],
    examples: [
      { en:"She has fond recollections of her first job.", zh:"她對第一份工作有著美好的回憶。" },
      { en:"His recollection of the meeting details was impressively accurate.", zh:"他對會議細節的記憶力精確得令人印象深刻。" }
    ] },
  { id: "w1379", english: "relinquish", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["放棄","交出(權利、責任等)"] ] } ],
    examples: [ { en:"He relinquished his position as director after the merger.", zh:"合併後，他辭去了董事的職位。" } ] },
  { id: "w1380", english: "remembrance", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["追悼","紀念"] ] } ],
    examples: [ { en:"A ceremony was held in remembrance of the company's founder.", zh:"公司舉行了一場儀式來紀念創辦人。" } ] },
  { id: "w1381", english: "replica", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["複製品","仿製品"] ] } ],
    examples: [ { en:"The showroom displays a replica of the original prototype.", zh:"展示間陳列著原始原型的複製品。" } ] },
  { id: "w1382", english: "rocky", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["艱難的","不穩定的"] ] } ],
    examples: [ { en:"The startup had a rocky first year before finding investors.", zh:"這家新創公司在找到投資人之前，第一年過得相當艱難。" } ] },
  { id: "w1383", english: "rough", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["粗糙的","不平坦的"] ] } ],
    examples: [ { en:"The road to the factory is rough and full of potholes.", zh:"通往工廠的路面粗糙且坑洞很多。" } ] },
  { id: "w1384", english: "sarcastic", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["諷刺的","挖苦的"] ] } ],
    examples: [ { en:"His sarcastic remark during the meeting made everyone uncomfortable.", zh:"他在會議中那句諷刺的話讓大家都感到不自在。" } ] },
  { id: "w1385", english: "security deposit", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["保證金","押金"] ] } ],
    examples: [ { en:"Tenants must pay a security deposit before moving in.", zh:"房客在入住前必須支付一筆保證金。" } ] },
  { id: "w1386", english: "solicit", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["請求","徵求(金錢、資訊或協助)"] ] } ],
    examples: [ { en:"It is against company policy to solicit donations from clients.", zh:"向客戶徵求捐款違反公司政策。" } ] },
  { id: "w1387", english: "under the contract", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["根據合約","依合約規定"] ] } ],
    examples: [ { en:"Under the contract, employees must give three months' notice before leaving.", zh:"根據合約規定，員工離職前必須提前三個月通知。" } ] },
  { id: "w1388", english: "virtual", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["幾乎的","實質上的"], ["虛擬的"] ] } ],
    examples: [
      { en:"Falling orders led to the virtual ruin of the small business.", zh:"訂單銳減幾乎讓這家小企業破產。" },
      { en:"The company now offers virtual reality training for new employees.", zh:"公司現在為新員工提供虛擬實境訓練。" }
    ] },
  { id: "w1389", english: "within reason", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["在合理範圍內"] ] } ],
    examples: [ { en:"You can order anything within reason for the office party.", zh:"辦公室派對上你可以在合理範圍內訂購任何東西。" } ] },
  { id: "w1390", english: "attain", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["達成","獲得"] ] } ],
    examples: [ { en:"She attained the sales target three months ahead of schedule.", zh:"她提前三個月達成了銷售目標。" } ] },
  { id: "w1391", english: "at the latest", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["最晚","最遲"] ] } ],
    examples: [ { en:"Please submit the report by Friday at the latest.", zh:"請最晚在星期五之前提交報告。" } ] },
  { id: "w1392", english: "barring", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "prep", meaningGroups: [ ["除非","若非(發生某事)"] ] } ],
    examples: [ { en:"Barring any delays, the shipment should arrive on Monday.", zh:"除非有延誤，這批貨應該會在星期一送達。" } ] },
  { id: "w1393", english: "barter", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["以物易物","用…交換"] ] } ],
    examples: [ { en:"Some small businesses still barter goods for services.", zh:"有些小型企業仍以物品換取服務。" } ] },
  { id: "w1394", english: "capitalize on", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["利用","憑藉…獲利"] ] } ],
    examples: [ { en:"The firm capitalized on the market trend to boost its sales.", zh:"這家公司利用了市場趨勢來提升銷售額。" } ] },
  { id: "w1395", english: "cast a ballot", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["投票"] ] } ],
    examples: [ { en:"Employees were encouraged to cast a ballot in the union election.", zh:"員工被鼓勵在工會選舉中投票。" } ] },
  { id: "w1396", english: "come to power", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["掌權","上臺執政"] ] } ],
    examples: [ { en:"The new management came to power after the board vote.", zh:"新的管理層在董事會投票後掌權。" } ] },
  { id: "w1397", english: "constituency", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["(某地區的)選民"], ["選區"] ] } ],
    examples: [
      { en:"The senator angered his constituency by voting against the bill.", zh:"這位參議員因為投票反對這項法案而激怒了他的選民。" },
      { en:"The candidate visited every town in her constituency before the election.", zh:"這位候選人在選舉前拜訪了她選區內的每個城鎮。" }
    ] },
  { id: "w1398", english: "contend with", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["應付","處理(困難的情況)"] ] } ],
    examples: [ { en:"The logistics team had to contend with severe delays at customs.", zh:"物流團隊必須處理海關嚴重延誤的問題。" } ] },
  { id: "w1399", english: "engrave", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["雕刻","刻(字或圖案)於"] ] } ],
    examples: [ { en:"The company engraved the retiring employee's name on a plaque.", zh:"公司把即將退休員工的名字刻在一塊獎牌上。" } ] },
  { id: "w1400", english: "exercise one's right", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["行使權利"] ] } ],
    examples: [ { en:"Every shareholder has the right to exercise their vote at the meeting.", zh:"每位股東都有權在會議上行使投票權。" } ] },
  { id: "w1401", english: "honorable", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["光榮的","正直可敬的"] ] } ],
    examples: [ { en:"He is known as an honorable businessman who always keeps his word.", zh:"他是一位以誠信著稱、值得敬重的商人。" } ] },
  { id: "w1402", english: "inclination", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["傾向","意願"] ] } ],
    examples: [ { en:"She showed no inclination to accept the transfer offer.", zh:"她顯露不出接受這次調職提議的意願。" } ] },
  { id: "w1403", english: "itemized", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["逐項列出的"] ] } ],
    examples: [ { en:"Please provide an itemized invoice for the office supplies.", zh:"請提供辦公用品的逐項列出的發票。" } ] },
  { id: "w1404", english: "lead up to", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["逐漸引導至","為…作鋪陳"] ] } ],
    examples: [ { en:"The weeks leading up to the product launch were extremely busy.", zh:"產品上市前的那幾週非常忙碌。" } ] },
  { id: "w1405", english: "parliament", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["國會","議會"], ["國會會期","議會任期"] ] } ],
    examples: [
      { en:"The bill was passed by parliament after months of debate.", zh:"這項法案經過數月的辯論後由國會通過了。" },
      { en:"The trade agreement was discussed in parliament this morning.", zh:"這項貿易協定今天上午在國會會期中被討論。" }
    ] },
  { id: "w1406", english: "peddler", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["小販","沿街叫賣者"] ] } ],
    examples: [ { en:"A street peddler was selling handmade crafts outside the office.", zh:"一名街頭小販在辦公室外販售手工藝品。" } ] },
  { id: "w1407", english: "perceptive", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["敏銳的","有洞察力的"] ] } ],
    examples: [ { en:"The consultant gave some perceptive insights into the company's weaknesses.", zh:"這位顧問對公司的弱點提出了一些敏銳的見解。" } ] },
  { id: "w1408", english: "predominantly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["主要地","大多"] ] } ],
    examples: [ { en:"The firm's clients are predominantly small businesses.", zh:"這家公司的客戶主要是小型企業。" } ] },
  { id: "w1409", english: "profoundly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["深切地","極其"] ] } ],
    examples: [ { en:"We are profoundly grateful for the team's dedication this year.", zh:"我們對團隊今年的付出深感感激。" } ] },
  { id: "w1410", english: "protocol", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["(國際間的)協議","公約"] ] } ],
    examples: [ { en:"The trade protocol was signed by representatives from both countries.", zh:"這項貿易協議由兩國代表簽署。" } ] },
  { id: "w1411", english: "reasonably priced", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["價格合理的"] ] } ],
    examples: [ { en:"The hotel offers reasonably priced rooms for business travelers.", zh:"這間飯店為商務旅客提供價格合理的房間。" } ] },
  { id: "w1412", english: "scarcity", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["缺乏","不足"] ] } ],
    examples: [ { en:"There is a scarcity of skilled workers in the manufacturing sector.", zh:"製造業中出現技術工人短缺的情況。" } ] },
  { id: "w1413", english: "step down", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["辭職","卸下職位"] ] } ],
    examples: [ { en:"The CEO announced plans to step down at the end of the year.", zh:"執行長宣布將於年底辭去職位。" } ] },
  { id: "w1414", english: "surrender", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vi", meaningGroups: [ ["投降","屈服"], ["屈服於(誘惑、情感)"] ] } ],
    examples: [
      { en:"The company refused to surrender to its competitor's pressure.", zh:"這家公司拒絕向競爭對手的壓力屈服。" },
      { en:"He finally surrendered to the temptation and signed the risky deal.", zh:"他最終屈服於誘惑，簽下了這筆高風險的交易。" }
    ] },
  { id: "w1415", english: "take inventory", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["盤點存貨"] ] } ],
    examples: [ { en:"The staff take inventory at the end of every month.", zh:"員工每個月底都會盤點存貨。" } ] },
  { id: "w1416", english: "write up", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["撰寫(完整報告)"] ] } ],
    examples: [ { en:"Can you write up the meeting minutes by tomorrow morning?", zh:"你能在明天早上之前寫好會議記錄嗎？" } ] },
  {
    id: "w1443", english: "accelerate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["加速","加快"] ] },
      { pos: "vt", meaningGroups: [ ["使加速","促進"] ] }
    ],
    examples: [
      { en:"Economists warn that inflation could accelerate sharply in the coming months.", zh:"經濟學家警告通膨在未來幾個月內可能急劇加速。" },
      { en:"The company plans to accelerate the launch of its new product line.", zh:"公司計畫加快推出新產品線的速度。" }
    ]
  },
  {
    id: "w1444", english: "as of", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["從…起","自…開始"] ] } ],
    examples: [
      { en:"As of next month, all employees will be required to submit weekly reports.", zh:"從下個月起，所有員工都必須提交週報。" }
    ]
  },
  {
    id: "w1445", english: "bilateral", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["雙邊的"] ] } ],
    examples: [
      { en:"The two countries signed a bilateral trade agreement to boost exports.", zh:"兩國簽署了一項雙邊貿易協定以促進出口。" }
    ]
  },
  {
    id: "w1446", english: "consulate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["領事館"] ] } ],
    examples: [
      { en:"She visited the consulate to renew her passport before the business trip.", zh:"她在出差前前往領事館更新護照。" }
    ]
  },
  {
    id: "w1447", english: "courier service", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["快遞服務","快遞公司"] ] } ],
    examples: [
      { en:"We used a courier service to deliver the contract overnight.", zh:"我們透過快遞服務在一夜之間送達合約。" }
    ]
  },
  {
    id: "w1448", english: "diplomat", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["外交官"] ] } ],
    examples: [
      { en:"The diplomat negotiated a new trade deal on behalf of her country.", zh:"這位外交官代表她的國家談判了一項新貿易協議。" }
    ]
  },
  {
    id: "w1449", english: "discard", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["丟棄","拋棄"] ] } ],
    examples: [
      { en:"Please discard any outdated documents before the audit.", zh:"請在稽核前丟棄任何過期的文件。" }
    ]
  },
  {
    id: "w1450", english: "drive off", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["開車離開"] ] } ],
    examples: [
      { en:"He loaded the boxes into the van and drove off toward the warehouse.", zh:"他把箱子裝進貨車後就開車朝倉庫離開了。" }
    ]
  },
  {
    id: "w1451", english: "drop off", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["把…送到（某處）"] ] } ],
    examples: [
      { en:"I'll drop off the documents at the client's office on my way home.", zh:"我回家途中會把文件送到客戶的辦公室。" }
    ]
  },
  {
    id: "w1452", english: "expatriate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["僑民","外派人員"] ] },
      { pos: "vt", meaningGroups: [ ["驅逐出境","使流亡"] ] }
    ],
    examples: [
      { en:"The company offers a generous relocation package for expatriates moving abroad.", zh:"公司為外派海外的員工提供優厚的搬遷津貼。" },
      { en:"The new regime expatriated several members of the former ruling family.", zh:"新政權將前統治家族的多名成員驅逐出境。" }
    ]
  },
  {
    id: "w1453", english: "expedite", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["加快處理","加速進行"] ] } ],
    examples: [
      { en:"We need to expedite this shipment so it arrives before the trade show.", zh:"我們需要加快處理這批貨物，以便能在展銷會前送達。" }
    ]
  },
  {
    id: "w1454", english: "handrail", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["扶手"] ] } ],
    examples: [
      { en:"Please hold the handrail while the escalator is in motion.", zh:"電扶梯運行時請握好扶手。" }
    ]
  },
  {
    id: "w1455", english: "inaugurate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["為…舉行就職典禮"] ] } ],
    examples: [
      { en:"The new CEO will be inaugurated at a ceremony next Monday.", zh:"新任執行長將於下週一舉行就職典禮。" }
    ]
  },
  {
    id: "w1456", english: "janitor", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["管理員","清潔工"] ] } ],
    examples: [
      { en:"The janitor cleans the office building every evening after hours.", zh:"這位管理員每天下班後都會清潔辦公大樓。" }
    ]
  },
  {
    id: "w1457", english: "lace", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["鞋帶","繩帶"] ] },
      { pos: "vt", meaningGroups: [ ["繫上鞋帶"] ] }
    ],
    examples: [
      { en:"One of her shoe laces came undone during the meeting.", zh:"她的一條鞋帶在會議中鬆開了。" },
      { en:"He knelt down to lace up his boots before the site inspection.", zh:"他蹲下來繫緊靴子的鞋帶，準備進行工地檢查。" }
    ]
  },
  {
    id: "w1458", english: "marginally", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["些微地","略微地"] ] } ],
    examples: [
      { en:"Sales figures were marginally higher than analysts had expected.", zh:"銷售數字略高於分析師的預期。" }
    ]
  },
  {
    id: "w1459", english: "oversight", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["疏忽","失察"] ] },
      { pos: "nu", meaningGroups: [ ["監督","督導"] ] }
    ],
    examples: [
      { en:"The missing signature was simply an oversight on our part.", zh:"少了簽名純粹是我們的疏忽。" },
      { en:"The finance director has oversight of all budget approvals.", zh:"財務總監負責監督所有預算的核准。" }
    ]
  },
  {
    id: "w1460", english: "packing tape", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["包裝膠帶"] ] } ],
    examples: [
      { en:"Make sure you seal every box with packing tape before shipping.", zh:"出貨前請確保每個箱子都用包裝膠帶封好。" }
    ]
  },
  {
    id: "w1461", english: "pavement", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["人行道"] ] } ],
    examples: [
      { en:"Delivery bikes are not allowed to park on the pavement outside the building.", zh:"外送機車不得停在大樓外的人行道上。" }
    ]
  },
  {
    id: "w1462", english: "pier", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["支柱","橋墩"] ] } ],
    examples: [
      { en:"Engineers reinforced the bridge's piers to withstand stronger typhoons.", zh:"工程師強化了橋樑的支柱，以承受更強的颱風。" }
    ]
  },
  {
    id: "w1463", english: "provided that", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["只要","如果"] ] } ],
    examples: [
      { en:"The shipment will arrive on schedule, provided that customs clearance goes smoothly.", zh:"只要海關通關順利，這批貨就會如期送達。" }
    ]
  },
  {
    id: "w1464", english: "reciprocal", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["互惠的","相互的"] ] } ],
    examples: [
      { en:"The two firms reached a reciprocal agreement to share market research.", zh:"這兩家公司達成了一項互惠協議，共享市場調查資料。" }
    ]
  },
  {
    id: "w1465", english: "registered mail", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["掛號信","掛號郵件"] ] } ],
    examples: [
      { en:"Important contracts should always be sent by registered mail.", zh:"重要合約應該一律以掛號信寄送。" }
    ]
  },
  {
    id: "w1466", english: "stow", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["收放","存放"] ] } ],
    examples: [
      { en:"Passengers must stow their carry-on luggage before takeoff.", zh:"乘客必須在起飛前將隨身行李收放好。" }
    ]
  },
  {
    id: "w1467", english: "strap", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["帶子","背帶"] ] },
      { pos: "vt", meaningGroups: [ ["用帶子固定"] ] }
    ],
    examples: [
      { en:"The strap on his laptop bag broke during the commute.", zh:"他的筆電包背帶在通勤途中斷了。" },
      { en:"Make sure the cargo is strapped down securely before the truck departs.", zh:"卡車出發前請確保貨物已用帶子牢牢固定。" }
    ]
  },
  {
    id: "w1468", english: "wheelbarrow", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["獨輪推車"] ] } ],
    examples: [
      { en:"Workers used a wheelbarrow to move the bricks across the site.", zh:"工人們用獨輪推車把磚塊搬運到工地各處。" }
    ]
  },
  {
    id: "w1469", english: "agreeably", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["愉快地","令人滿意地"] ] } ],
    examples: [
      { en:"The client was agreeably surprised by how quickly we resolved the issue.", zh:"客戶對我們如此迅速解決問題感到愉快又驚喜。" }
    ]
  },
  {
    id: "w1470", english: "as a courtesy", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["作為禮貌","出於好意"] ] } ],
    examples: [
      { en:"As a courtesy, the hotel offered a free upgrade to the delayed guests.", zh:"飯店出於好意，為延誤的房客提供了免費升等。" }
    ]
  },
  {
    id: "w1471", english: "atrium", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["中庭","大廳"] ] } ],
    examples: [
      { en:"The conference will be held in the atrium of the new office tower.", zh:"這場會議將在新辦公大樓的中庭舉行。" }
    ]
  },
  {
    id: "w1472", english: "chop", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["切碎","剁碎"] ] } ],
    examples: [
      { en:"The recipe asks you to chop the onions finely before cooking.", zh:"食譜要求先把洋蔥切碎再烹煮。" }
    ]
  },
  {
    id: "w1473", english: "cloakroom", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["衣物間","寄物處"] ] } ],
    examples: [
      { en:"Guests can leave their coats at the cloakroom near the entrance.", zh:"來賓可以把外套放在入口附近的寄物處。" }
    ]
  },
  {
    id: "w1474", english: "corridor", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["走廊","通道"] ] } ],
    examples: [
      { en:"Her office is located at the far end of the corridor.", zh:"她的辦公室位於走廊的最遠端。" }
    ]
  },
  {
    id: "w1475", english: "countertop", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["檯面","流理台"] ] } ],
    examples: [
      { en:"The showroom displayed several styles of kitchen countertops.", zh:"展示間陳列了好幾種風格的廚房檯面。" }
    ]
  },
  {
    id: "w1476", english: "decaffeinated", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["去咖啡因的"] ] } ],
    examples: [
      { en:"The café now offers a decaffeinated option for all its coffee drinks.", zh:"這家咖啡廳現在所有咖啡飲品都提供去咖啡因的選項。" }
    ]
  },
  {
    id: "w1477", english: "double occupancy", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["雙人住房"] ] } ],
    examples: [
      { en:"The conference rate is $120 per night, double occupancy.", zh:"會議優惠價為雙人住房每晚120美元。" }
    ]
  },
  {
    id: "w1478", english: "eat up", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["吃完","吃光"] ] } ],
    examples: [
      { en:"The kids happily ate up all the snacks at the office party.", zh:"孩子們在辦公室派對上開心地把點心都吃光了。" }
    ]
  },
  {
    id: "w1479", english: "forfeit", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["喪失","被沒收"] ] } ],
    examples: [
      { en:"If you cancel the reservation now, you will forfeit your deposit.", zh:"如果你現在取消預訂，你將會喪失訂金。" }
    ]
  },
  {
    id: "w1480", english: "frosting", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["糖霜"] ] } ],
    examples: [
      { en:"The bakery decorated the cake with a thick layer of chocolate frosting.", zh:"烘焙坊在蛋糕上裝飾了厚厚一層巧克力糖霜。" }
    ]
  },
  {
    id: "w1481", english: "garner", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["獲得","贏得"] ] } ],
    examples: [
      { en:"The new marketing campaign garnered a lot of positive attention online.", zh:"這次新的行銷活動在網路上贏得了許多正面關注。" }
    ]
  },
  {
    id: "w1482", english: "garnish", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["裝飾（食物）","點綴"] ] } ],
    examples: [
      { en:"The chef garnished each plate with a sprig of parsley.", zh:"主廚在每個盤子上都用一小枝香芹裝飾。" }
    ]
  },
  {
    id: "w1483", english: "gather up", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["收集起來","收拾"] ] } ],
    examples: [
      { en:"She gathered up all the handouts after the meeting ended.", zh:"會議結束後，她把所有的講義都收拾起來。" }
    ]
  },
  {
    id: "w1484", english: "grab a bite", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["隨便吃點東西","簡單吃一下"] ] } ],
    examples: [
      { en:"Let's grab a bite before the afternoon session starts.", zh:"我們在下午場次開始前先簡單吃點東西吧。" }
    ]
  },
  {
    id: "w1485", english: "gusty", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["風大的","陣風的"] ] } ],
    examples: [
      { en:"The outdoor event was postponed due to gusty winds.", zh:"由於風大，這場戶外活動被延期了。" }
    ]
  },
  {
    id: "w1486", english: "have a light dinner", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["吃一份清淡的晚餐"] ] } ],
    examples: [
      { en:"Most guests prefer to have a light dinner before the evening banquet.", zh:"大多數賓客偏好在晚宴前先吃一份清淡的晚餐。" }
    ]
  },
  {
    id: "w1487", english: "indigenous", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["本土的","原生的"] ] } ],
    examples: [
      { en:"The company sources indigenous crops directly from local farmers.", zh:"這家公司直接向當地農民採購本土農作物。" }
    ]
  },
  {
    id: "w1488", english: "kettle", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["水壺","茶壺"] ] } ],
    examples: [
      { en:"The office pantry has an electric kettle for making tea and coffee.", zh:"辦公室的茶水間有一個電熱水壺可以泡茶和咖啡。" }
    ]
  },
  {
    id: "w1489", english: "palate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["味覺","品味"] ] } ],
    examples: [
      { en:"The chef designed a tasting menu to suit a variety of palates.", zh:"主廚設計了一份試吃菜單，以迎合各種不同的味覺喜好。" }
    ]
  },
  {
    id: "w1490", english: "parlor", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["客廳","接待室"], ["…店","…館（提供特定服務或商品的店家）"] ] } ],
    examples: [
      { en:"Guests were welcomed into the parlor before the formal reception began.", zh:"賓客在正式接待開始前先被引進客廳等候。" },
      { en:"There's a new ice cream parlor opening next to the mall.", zh:"購物中心旁邊要開一家新的冰淇淋店。" }
    ]
  },
  {
    id: "w1491", english: "peel off", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["剝掉","撕下"] ] } ],
    examples: [
      { en:"The technician peeled off the protective film from the new screen.", zh:"技術人員把新螢幕上的保護膜撕下來。" }
    ]
  },
  {
    id: "w1492", english: "pick up the check", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["買單","付帳"] ] } ],
    examples: [
      { en:"The client insisted on picking up the check after the business lunch.", zh:"客戶在商務午餐後堅持要買單。" }
    ]
  },
  {
    id: "w1493", english: "potholder", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["隔熱手套","鍋墊"] ] } ],
    examples: [
      { en:"Always use a potholder when handling hot trays from the oven.", zh:"從烤箱取出熱托盤時，務必使用隔熱手套。" }
    ]
  },
  {
    id: "w1494", english: "preheat", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["預熱"] ] } ],
    examples: [
      { en:"Preheat the oven to 180 degrees before baking the samples.", zh:"烘烤樣品前，請先將烤箱預熱至180度。" }
    ]
  },
  {
    id: "w1495", english: "progressively", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["逐漸地","漸進地"] ] } ],
    examples: [
      { en:"The company's market share has grown progressively over the past five years.", zh:"這家公司的市佔率在過去五年間逐漸成長。" }
    ]
  },
  {
    id: "w1496", english: "room attendant", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["房務員"] ] } ],
    examples: [
      { en:"A room attendant cleans and restocks each guest room daily.", zh:"房務員每天負責打掃並補充每間客房的用品。" }
    ]
  },
  {
    id: "w1497", english: "sanitary", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["衛生的","清潔的"], ["（婦女）生理用的"] ] } ],
    examples: [
      { en:"All kitchen staff must follow strict sanitary procedures.", zh:"所有廚房人員都必須遵守嚴格的衛生規範。" },
      { en:"The store restocked its shelves with sanitary products this morning.", zh:"這家店今天上午補齊了架上的生理用品。" }
    ]
  },
  {
    id: "w1498", english: "seemingly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["看似","表面上"] ] } ],
    examples: [
      { en:"The negotiations reached a seemingly successful conclusion, but issues remained.", zh:"這場談判看似圓滿結束，但問題其實仍未解決。" }
    ]
  },
  {
    id: "w1499", english: "slurp", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["發出聲音地喝","啜飲"] ] } ],
    examples: [
      { en:"He slurped his coffee loudly during the video call.", zh:"他在視訊會議中大聲地啜飲咖啡。" }
    ]
  },
  {
    id: "w1500", english: "spoil", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vi", meaningGroups: [ ["變質","腐壞"] ] } ],
    examples: [
      { en:"The seafood will spoil quickly if it isn't refrigerated.", zh:"海鮮如果沒有冷藏很快就會變質。" }
    ]
  },
  {
    id: "w1501", english: "stove", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["爐子","炊具"] ] } ],
    examples: [
      { en:"The break room stove needs to be replaced before the renovation.", zh:"休息室的爐子在裝修前需要更換。" }
    ]
  },
  {
    id: "w1502", english: "tablecloth", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["桌布"] ] } ],
    examples: [
      { en:"The banquet hall was set with white tablecloths for the awards dinner.", zh:"宴會廳為頒獎晚宴鋪上了白色桌布。" }
    ]
  },
  {
    id: "w1503", english: "teapot", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["茶壺"] ] } ],
    examples: [
      { en:"She placed a fresh teapot on the table for the visiting clients.", zh:"她為來訪的客戶在桌上放了一壺新泡的茶。" }
    ]
  },
  {
    id: "w1504", english: "thickly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["厚厚地"] ] } ],
    examples: [
      { en:"The sample fabric was cut thickly to test its durability.", zh:"樣品布料被切得很厚以測試其耐用度。" }
    ]
  },
  {
    id: "w1505", english: "unpack", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["打開（行李、包裹）","拆封"] ] } ],
    examples: [
      { en:"Please unpack the new equipment and check it against the inventory list.", zh:"請將新設備拆封並依照庫存清單核對。" }
    ]
  },
  {
    id: "w1506", english: "vinegar", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["醋"] ] } ],
    examples: [
      { en:"The catering team ordered extra bottles of vinegar for the salad bar.", zh:"外燴團隊為沙拉吧多訂購了幾瓶醋。" }
    ]
  },
  {
    id: "w1507", english: "agile", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["敏捷的","靈活的"] ] } ],
    examples: [
      { en:"The startup's agile approach allows it to adapt quickly to market changes.", zh:"這家新創公司靈活的做法讓它能迅速適應市場變化。" }
    ]
  },
  {
    id: "w1508", english: "allotment", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["分配額","配額"] ] } ],
    examples: [
      { en:"Each department received its allotment of the annual training budget.", zh:"每個部門都收到了年度培訓預算的分配額。" }
    ]
  },
  {
    id: "w1509", english: "at a rapid rate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["快速地","迅速地"] ] } ],
    examples: [
      { en:"The company's customer base has grown at a rapid rate this year.", zh:"這家公司的客戶群今年迅速成長。" }
    ]
  },
  {
    id: "w1510", english: "coil", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["一圈","一捲"] ] },
      { pos: "vt", meaningGroups: [ ["把…捲成一圈"] ] }
    ],
    examples: [
      { en:"A coil of cable was left near the server room entrance.", zh:"伺服器機房入口附近留了一圈電纜線。" },
      { en:"The technician coiled the extra wire neatly before storing it.", zh:"技術人員在收納前把多餘的電線整齊地捲起來。" }
    ]
  },
  {
    id: "w1511", english: "dean", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["（大學）院長"], ["（同行中的）資深領袖，元老"] ] } ],
    examples: [
      { en:"The dean of the business school will speak at the graduation ceremony.", zh:"商學院院長將在畢業典禮上致辭。" },
      { en:"He is regarded as the dean of financial journalists in the city.", zh:"他被視為這座城市財經記者中的元老。" }
    ]
  },
  {
    id: "w1512", english: "deviate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vi", meaningGroups: [ ["偏離","背離"] ] } ],
    examples: [
      { en:"The actual budget deviated significantly from the original forecast.", zh:"實際預算明顯偏離了原先的預測。" }
    ]
  },
  {
    id: "w1513", english: "do damage", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["造成損害","造成傷害"] ] } ],
    examples: [
      { en:"The scandal did serious damage to the company's reputation.", zh:"這起醜聞對公司的聲譽造成了嚴重損害。" }
    ]
  },
  {
    id: "w1514", english: "downfall", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["垮台","衰敗（的原因）"] ] } ],
    examples: [
      { en:"Poor cash flow management was the downfall of the once-thriving business.", zh:"現金流管理不善是這家曾經蓬勃發展的企業垮台的原因。" }
    ]
  },
  {
    id: "w1515", english: "even out", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["使…平均","使…趨於平衡"] ] } ],
    examples: [
      { en:"Overtime pay helps even out income differences among shift workers.", zh:"加班費有助於平衡輪班員工之間的收入差異。" }
    ]
  },
  {
    id: "w1516", english: "file for bankruptcy", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["申請破產"] ] } ],
    examples: [
      { en:"The retailer was forced to file for bankruptcy after years of declining sales.", zh:"這家零售商在多年銷售下滑後被迫申請破產。" }
    ]
  },
  {
    id: "w1517", english: "gratify", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["使滿足","使高興"] ] } ],
    examples: [
      { en:"The manager was gratified by the team's outstanding performance this quarter.", zh:"經理對團隊本季的出色表現感到十分滿意。" }
    ]
  },
  {
    id: "w1518", english: "gross income", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["總收入","毛收入"] ] } ],
    examples: [
      { en:"The property generates a gross income of $3,000 a month.", zh:"這處房產每月產生3000美元的總收入。" }
    ]
  },
  {
    id: "w1519", english: "harsh", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["嚴厲的","嚴苛的"] ] } ],
    examples: [
      { en:"Employees felt the new attendance policy was overly harsh.", zh:"員工們覺得新的出勤規定過於嚴苛。" }
    ]
  },
  {
    id: "w1520", english: "hollow", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["空心的","中空的"], ["空洞的","不真誠的"] ] } ],
    examples: [
      { en:"The packaging uses hollow tubes to reduce shipping weight.", zh:"這款包裝使用中空的管子來減輕運送重量。" },
      { en:"His apology sounded hollow after the repeated delays.", zh:"在一再延誤之後，他的道歉聽起來很空洞。" }
    ]
  },
  {
    id: "w1521", english: "infusion", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["注入（資金等）"], ["（藥草、茶等的）沖泡飲品"] ] } ],
    examples: [
      { en:"The struggling firm needed a fresh infusion of capital to survive.", zh:"這家陷入困境的公司需要注入新的資金才能生存下去。" },
      { en:"She prefers an herbal infusion over coffee in the afternoon.", zh:"她下午比較喜歡喝花草茶而不是咖啡。" }
    ]
  },
  {
    id: "w1522", english: "insolvency", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["破產","無力償債"] ] } ],
    examples: [
      { en:"The firm narrowly avoided insolvency after securing an emergency loan.", zh:"這家公司在取得緊急貸款後，勉強避免了破產。" }
    ]
  },
  {
    id: "w1523", english: "literally", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["確實地","真的"], ["逐字地","照字面地"] ] } ],
    examples: [
      { en:"The new policy literally changed how every department operates.", zh:"這項新政策確實改變了每個部門的運作方式。" },
      { en:"Translating the contract too literally caused several misunderstandings.", zh:"把合約翻譯得太過逐字，導致了幾次誤解。" }
    ]
  },
  {
    id: "w1524", english: "loosely", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["鬆散地","不緊密地"] ] } ],
    examples: [
      { en:"The proposal was only loosely based on last year's budget plan.", zh:"這份提案只是鬆散地參考了去年的預算計畫。" }
    ]
  },
  {
    id: "w1525", english: "offset", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["抵銷","彌補"] ] } ],
    examples: [
      { en:"The rise in shipping costs was offset by higher sales volume.", zh:"運輸成本的上漲被較高的銷售量所抵銷。" }
    ]
  },
  {
    id: "w1526", english: "optimal", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["最理想的","最佳的"] ] } ],
    examples: [
      { en:"The consultant recommended the optimal staffing level for peak season.", zh:"顧問建議了旺季期間最理想的人力配置水準。" }
    ]
  },
  {
    id: "w1527", english: "outpace", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["超越","勝過（發展速度）"] ] } ],
    examples: [
      { en:"Demand for the new smartphone has outpaced production capacity.", zh:"新款智慧型手機的需求已經超過了生產產能。" }
    ]
  },
  {
    id: "w1528", english: "outsell", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["銷售量超過"] ] } ],
    examples: [
      { en:"The budget model has consistently outsold the premium version.", zh:"平價機型的銷量一直持續超過高階機型。" }
    ]
  },
  {
    id: "w1529", english: "piece by piece", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["一件一件地","逐步地"] ] } ],
    examples: [
      { en:"The auditors reviewed the expense report piece by piece.", zh:"審計人員逐項檢視了這份費用報告。" }
    ]
  },
  {
    id: "w1530", english: "profit margin", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["利潤率"] ] } ],
    examples: [
      { en:"The company's profit margin narrowed due to rising material costs.", zh:"由於原料成本上升，這家公司的利潤率縮小了。" }
    ]
  },
  {
    id: "w1531", english: "proportion", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["比例","部分"] ] } ],
    examples: [
      { en:"A large proportion of the budget is allocated to marketing this year.", zh:"今年的預算中有很大一部分是分配給行銷的。" }
    ]
  },
  {
    id: "w1532", english: "proportionate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["成比例的","相稱的"] ] } ],
    examples: [
      { en:"Bonuses should be proportionate to each employee's contribution.", zh:"獎金應該與每位員工的貢獻成比例。" }
    ]
  },
  {
    id: "w1533", english: "signify", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["表示","意味著"] ] } ],
    examples: [
      { en:"A green light on the dashboard signifies that the system is functioning normally.", zh:"儀表板上的綠燈表示系統運作正常。" }
    ]
  },
  {
    id: "w1534", english: "split", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["分割","分開"] ] },
      { pos: "nc", meaningGroups: [ ["裂縫","分裂"] ] }
    ],
    examples: [
      { en:"The manager split the team into two groups to handle the workload.", zh:"經理把團隊分成兩組來處理工作量。" },
      { en:"There was a noticeable split in opinion among the board members.", zh:"董事會成員之間出現了明顯的意見分裂。" }
    ]
  },
  {
    id: "w1535", english: "steeply", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["急劇地","陡峭地"] ] } ],
    examples: [
      { en:"Raw material prices have risen steeply over the past quarter.", zh:"原料價格在上一季急劇上漲。" }
    ]
  },
  {
    id: "w1536", english: "subside", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vi", meaningGroups: [ ["減弱","平息"] ] } ],
    examples: [
      { en:"Market volatility is expected to subside once the earnings reports are released.", zh:"一旦財報公布，市場的波動預期將會平息。" }
    ]
  },
  {
    id: "w1537", english: "swell", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vi", meaningGroups: [ ["膨脹","增加"] ] } ],
    examples: [
      { en:"The customer base has swelled since the app launched last spring.", zh:"自從這款應用程式去年春天上線以來，客戶群已大幅增加。" }
    ]
  },
  {
    id: "w1538", english: "timeline", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["時間表","時程"] ] } ],
    examples: [
      { en:"The project timeline was extended by two weeks due to supply delays.", zh:"由於供應延遲，這項專案的時程被延長了兩週。" }
    ]
  },
  {
    id: "w1539", english: "uncover", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["揭露","發現"] ] } ],
    examples: [
      { en:"The internal review uncovered several errors in the quarterly report.", zh:"內部審查揭露了季度報告中的幾項錯誤。" }
    ]
  },
  {
    id: "w1540", english: "vitally", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["極為重要地","不可或缺地"] ] } ],
    examples: [
      { en:"It is vitally important that all staff complete the safety training.", zh:"所有員工完成安全培訓是極為重要的事。" }
    ]
  },
  {
    id: "w1541", english: "adjournment", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["休會","暫停（會議、審訊）"] ] } ],
    examples: [
      { en:"The judge granted a brief adjournment to allow both sides to consult their lawyers.", zh:"法官批准短暫休庭，讓雙方諮詢各自的律師。" }
    ]
  },
  {
    id: "w1542", english: "amply", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["充分地","足夠地"] ] } ],
    examples: [
      { en:"Her years of experience have amply prepared her for the new role.", zh:"她多年的經驗讓她充分準備好接下這個新職位。" }
    ]
  },
  {
    id: "w1543", english: "back order", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["缺貨訂單","延期交貨訂單"] ] } ],
    examples: [
      { en:"The warehouse is currently unable to process any back orders for this item.", zh:"倉庫目前無法處理這項商品的任何缺貨訂單。" }
    ]
  },
  {
    id: "w1544", english: "bound for", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["前往…的","以…為目的地的"] ] } ],
    examples: [
      { en:"The shipment is bound for the port of Los Angeles.", zh:"這批貨物正運往洛杉磯港。" }
    ]
  },
  {
    id: "w1545", english: "break-even point", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["損益平衡點"] ] } ],
    examples: [
      { en:"The new product line is expected to reach its break-even point within a year.", zh:"這條新產品線預計在一年內達到損益平衡點。" }
    ]
  },
  {
    id: "w1546", english: "by contrast", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["相比之下","相對地"] ] } ],
    examples: [
      { en:"Sales in Europe grew steadily; by contrast, sales in Asia declined.", zh:"歐洲的銷售穩定成長；相比之下，亞洲的銷售則下滑了。" }
    ]
  },
  {
    id: "w1547", english: "collectively", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["共同地","集體地"] ] } ],
    examples: [
      { en:"The regional offices collectively generated over half of total revenue.", zh:"各地區辦公室共同創造了超過一半的總營收。" }
    ]
  },
  {
    id: "w1548", english: "digit", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["數字","位數"] ] } ],
    examples: [
      { en:"The account number consists of ten digits.", zh:"這個帳號由十個數字組成。" }
    ]
  },
  {
    id: "w1549", english: "displace", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["取代","使離開原位"] ] } ],
    examples: [
      { en:"Automated checkout systems have displaced many cashier positions.", zh:"自動結帳系統已取代了許多收銀員的職位。" }
    ]
  },
  {
    id: "w1550", english: "implicate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["牽連","涉及（於不當行為）"] ] } ],
    examples: [
      { en:"Internal emails implicated the manager in the reporting fraud.", zh:"內部電子郵件顯示這位經理涉及了報表造假。" }
    ]
  },
  {
    id: "w1551", english: "incrementally", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["逐步地","漸增地"] ] } ],
    examples: [
      { en:"The rollout will happen incrementally across all branch offices.", zh:"此次推行將在所有分公司逐步進行。" }
    ]
  },
  {
    id: "w1552", english: "ledger", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["帳簿","分類帳"] ] } ],
    examples: [
      { en:"The accountant reconciled the ledger before closing the fiscal year.", zh:"會計師在結算會計年度前核對了帳簿。" }
    ]
  },
  {
    id: "w1553", english: "levy", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["徵稅","稅捐"] ] } ],
    examples: [
      { en:"The government imposed a new levy on imported electronics.", zh:"政府對進口電子產品徵收了一項新稅捐。" }
    ]
  },
  {
    id: "w1554", english: "liability", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["責任","法律責任"] ] },
      { pos: "nc", meaningGroups: [ ["負債"] ] }
    ],
    examples: [
      { en:"The contractor denied any liability for the delayed shipment.", zh:"承包商否認對這次延遲出貨負有任何責任。" },
      { en:"The company's liabilities exceeded its assets by year end.", zh:"到年底時，這家公司的負債已超過其資產。" }
    ]
  },
  {
    id: "w1555", english: "outlay", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["支出","開支"] ] } ],
    examples: [
      { en:"The initial outlay for new equipment was higher than budgeted.", zh:"新設備的初期支出比預算高。" }
    ]
  },
  {
    id: "w1556", english: "overly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["過於","過度地"] ] } ],
    examples: [
      { en:"The sales forecast turned out to be overly optimistic.", zh:"這份銷售預測結果證明過於樂觀。" }
    ]
  },
  {
    id: "w1557", english: "precedent", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["先例","前例"] ] } ],
    examples: [
      { en:"The court's ruling set a precedent for future contract disputes.", zh:"法院的判決為未來的合約糾紛設下了先例。" }
    ]
  },
  {
    id: "w1558", english: "pretax", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["稅前的"] ] } ],
    examples: [
      { en:"The company reported pretax earnings of $13 million this quarter.", zh:"這家公司本季申報稅前盈餘為1300萬美元。" }
    ]
  },
  {
    id: "w1559", english: "rigorously", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["嚴格地","嚴謹地"] ] } ],
    examples: [
      { en:"All new hires are rigorously trained before working with clients.", zh:"所有新員工在與客戶接觸前都會接受嚴格的培訓。" }
    ]
  },
  {
    id: "w1560", english: "sequel", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["續集","後續篇"] ] } ],
    examples: [
      { en:"The publisher is planning a sequel to last year's bestselling business guide.", zh:"出版社正計畫推出去年暢銷商業指南的續集。" }
    ]
  },
  {
    id: "w1561", english: "side by side", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["並排地","並肩地"] ] } ],
    examples: [
      { en:"The two teams worked side by side to meet the tight deadline.", zh:"這兩個團隊並肩合作，以達成緊迫的截止期限。" }
    ]
  },
  {
    id: "w1562", english: "stringently", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["嚴格地","嚴密地"] ] } ],
    examples: [
      { en:"Safety regulations are enforced stringently at all manufacturing plants.", zh:"所有製造廠的安全規範都被嚴格執行。" }
    ]
  },
  {
    id: "w1563", english: "a string of", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["一連串的","一系列的"] ] } ],
    examples: [
      { en:"The company has faced a string of setbacks since the merger.", zh:"自合併以來，這家公司面臨了一連串的挫折。" }
    ]
  },
  {
    id: "w1564", english: "substantively", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["實質上地","在重要方面"] ] } ],
    examples: [
      { en:"The revised contract is substantively different from the original draft.", zh:"修訂後的合約在實質上與原始草案有很大差異。" }
    ]
  },
  {
    id: "w1565", english: "take after", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["與…相似","像（家人）"] ] } ],
    examples: [
      { en:"In terms of work ethic, she really takes after her father.", zh:"就工作態度來說，她真的很像她父親。" }
    ]
  },
  {
    id: "w1566", english: "well in advance", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["提前很多","事先充分準備"] ] } ],
    examples: [
      { en:"Travel arrangements should be made well in advance of the conference.", zh:"旅行安排應該在會議前提前很多做好準備。" }
    ]
  },
  {
    id: "w1567", english: "whereabouts", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["行蹤","下落"] ] } ],
    examples: [
      { en:"The shipment's exact whereabouts could not be confirmed by the courier.", zh:"快遞公司無法確認這批貨物的確切行蹤。" }
    ]
  },
  {
    id: "w1568", english: "advisory", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["顧問性質的","諮詢性質的"] ] },
      { pos: "nc", meaningGroups: [ ["官方通告（含建議、資訊或警告）"] ] }
    ],
    examples: [
      { en:"She serves the board in an advisory capacity on financial matters.", zh:"她在財務事務上以顧問身份為董事會提供服務。" },
      { en:"The agency issued a travel advisory due to the storm.", zh:"該機構因這場風暴發布了一則旅遊警示。" }
    ]
  },
  {
    id: "w1569", english: "allegedly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["據稱","傳聞中"] ] } ],
    examples: [
      { en:"The supplier allegedly falsified several shipment records.", zh:"據稱這家供應商曾經偽造了多份出貨紀錄。" }
    ]
  },
  {
    id: "w1570", english: "bump into", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["偶然遇到","碰見"] ] } ],
    examples: [
      { en:"I bumped into a former colleague at the trade show.", zh:"我在展銷會上偶然遇到了一位以前的同事。" }
    ]
  },
  {
    id: "w1571", english: "celebratory", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["慶祝的"] ] } ],
    examples: [
      { en:"The team went out for a celebratory dinner after closing the deal.", zh:"團隊在成交後出去吃了一頓慶祝晚餐。" }
    ]
  },
  {
    id: "w1572", english: "clout", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["權勢","影響力"] ] },
      { pos: "nc", meaningGroups: [ ["打擊","敲打"] ] }
    ],
    examples: [
      { en:"As the largest client, the firm has considerable clout with suppliers.", zh:"作為最大的客戶，這家公司對供應商擁有相當大的影響力。" },
      { en:"He gave the vending machine a clout when it jammed.", zh:"販賣機卡住時，他給它敲了一下。" }
    ]
  },
  {
    id: "w1573", english: "contingent upon", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["取決於","以…為條件"] ] } ],
    examples: [
      { en:"The final bonus is contingent upon meeting this quarter's sales targets.", zh:"最終的獎金取決於是否達成本季的銷售目標。" }
    ]
  },
  {
    id: "w1574", english: "correlation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["關聯性","相關性"] ] } ],
    examples: [
      { en:"There is a strong correlation between employee satisfaction and productivity.", zh:"員工滿意度與生產力之間存在強烈的關聯性。" }
    ]
  },
  {
    id: "w1575", english: "exemplify", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["是…的典型例子","體現"] ] } ],
    examples: [
      { en:"This campaign exemplifies the company's commitment to sustainability.", zh:"這次活動體現了公司對永續發展的承諾。" }
    ]
  },
  {
    id: "w1576", english: "exert pressure on", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["對…施加壓力"] ] } ],
    examples: [
      { en:"Investors exerted pressure on the board to replace the CEO.", zh:"投資人對董事會施加壓力，要求更換執行長。" }
    ]
  },
  {
    id: "w1577", english: "hinder", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["妨礙","阻礙"] ] } ],
    examples: [
      { en:"Outdated software continues to hinder the team's productivity.", zh:"過時的軟體持續阻礙著團隊的生產力。" }
    ]
  },
  {
    id: "w1578", english: "incline", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["傾斜"] ] },
      { pos: "nc", meaningGroups: [ ["斜坡"] ] }
    ],
    examples: [
      { en:"The conveyor belt inclines slightly toward the packing station.", zh:"這條輸送帶朝包裝站略微傾斜。" },
      { en:"Workers pushed the cart up a steep incline to the loading dock.", zh:"工人們把推車推上一段陡峭的斜坡到裝卸區。" }
    ]
  },
  {
    id: "w1579", english: "indefinitely", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["無限期地","不定期地"] ] } ],
    examples: [
      { en:"The product launch has been postponed indefinitely.", zh:"產品發布會已被無限期延後。" }
    ]
  },
  {
    id: "w1580", english: "inhabitant", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["居民"] ] } ],
    examples: [
      { en:"The new mall is expected to attract inhabitants from neighboring districts.", zh:"這座新購物中心預計會吸引鄰近地區的居民前來。" }
    ]
  },
  {
    id: "w1581", english: "instinctive", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["本能的","直覺的"] ] } ],
    examples: [
      { en:"Her instinctive reaction was to double-check the figures before submitting.", zh:"她的本能反應是在提交前再次檢查數字。" }
    ]
  },
  {
    id: "w1582", english: "interfere with", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["妨礙","干擾"] ] } ],
    examples: [
      { en:"The construction noise interfered with the client's video conference.", zh:"施工噪音干擾了客戶的視訊會議。" }
    ]
  },
  {
    id: "w1583", english: "intermittently", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["斷斷續續地","間歇性地"] ] } ],
    examples: [
      { en:"The server has been going down intermittently since the update.", zh:"自從更新後，伺服器一直斷斷續續地當機。" }
    ]
  },
  {
    id: "w1584", english: "landfill", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["垃圾掩埋場"] ] } ],
    examples: [
      { en:"The factory reduced the amount of waste sent to the landfill by 30 percent.", zh:"這家工廠將送往垃圾掩埋場的廢棄物減少了百分之三十。" }
    ]
  },
  {
    id: "w1585", english: "latent", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["潛在的","隱伏的"] ] } ],
    examples: [
      { en:"The survey revealed latent demand for eco-friendly packaging.", zh:"這項調查揭露了對環保包裝的潛在需求。" }
    ]
  },
  {
    id: "w1586", english: "look out", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["注意","留意"] ] } ],
    examples: [
      { en:"Staff were told to look out for counterfeit bills at the register.", zh:"員工被告知要在櫃台留意假鈔。" }
    ]
  },
  {
    id: "w1587", english: "lucid", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["清晰易懂的","條理清楚的"] ] } ],
    examples: [
      { en:"She gave a lucid explanation of the company's new pricing strategy.", zh:"她對公司新的定價策略做了清晰易懂的說明。" }
    ]
  },
  {
    id: "w1588", english: "makeshift", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["臨時的","權宜的"] ] } ],
    examples: [
      { en:"The team set up a makeshift office in the warehouse during renovations.", zh:"裝修期間，團隊在倉庫裡設置了一個臨時辦公室。" }
    ]
  },
  {
    id: "w1589", english: "momentarily", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["短暫地","片刻"], ["馬上","很快"] ] } ],
    examples: [
      { en:"The presenter was momentarily distracted by a technical glitch.", zh:"報告者因為一個技術故障而短暫地分心了。" },
      { en:"The manager will be with you momentarily.", zh:"經理馬上就會來見你。" }
    ]
  },
  {
    id: "w1590", english: "narrative", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["敘述","故事"], ["說法","論述角度"] ] } ],
    examples: [
      { en:"The annual report opens with a brief narrative of the company's history.", zh:"這份年報開頭簡短敘述了公司的歷史。" },
      { en:"Management pushed a positive narrative despite the disappointing earnings.", zh:"儘管財報表現令人失望，管理層仍推行正面的說法。" }
    ]
  },
  {
    id: "w1591", english: "outreach", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["外展服務","推廣服務"] ] } ],
    examples: [
      { en:"The nonprofit expanded its outreach to small businesses in rural areas.", zh:"這家非營利組織擴大了對鄉村地區小型企業的推廣服務。" }
    ]
  },
  {
    id: "w1592", english: "overstaffed", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["人員過多的","人力過剩的"] ] } ],
    examples: [
      { en:"The audit found that the customer service department was overstaffed.", zh:"稽核發現客服部門的人力過剩。" }
    ]
  },
  {
    id: "w1593", english: "rashly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["草率地","輕率地"] ] } ],
    examples: [
      { en:"He acted rashly by signing the contract without reading the fine print.", zh:"他沒看清楚細則就簽了合約，行事太草率了。" }
    ]
  },
  {
    id: "w1594", english: "renown", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["聲望","名望"] ] } ],
    examples: [
      { en:"The firm has gained international renown for its innovative designs.", zh:"這家公司因其創新設計而獲得了國際聲望。" }
    ]
  },
  {
    id: "w1595", english: "retreat", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vi", meaningGroups: [ ["撤退","退避"] ] } ],
    examples: [
      { en:"The company retreated from the overseas market after years of losses.", zh:"這家公司在虧損多年後退出了海外市場。" }
    ]
  },
  {
    id: "w1596", english: "rule out", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["排除","排除…的可能性"] ] } ],
    examples: [
      { en:"Management has not ruled out further layoffs this year.", zh:"管理層並未排除今年進一步裁員的可能性。" }
    ]
  },
  {
    id: "w1597", english: "scholar", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["學者"] ] } ],
    examples: [
      { en:"The panel included several scholars specializing in international trade.", zh:"這個座談小組包含了幾位專攻國際貿易的學者。" }
    ]
  },
  {
    id: "w1598", english: "sensible", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["明智的","合理的"], ["實用的（衣物等）"] ] } ],
    examples: [
      { en:"It would be sensible to back up all files before the system update.", zh:"在系統更新前備份所有檔案是明智的做法。" },
      { en:"Employees on the warehouse floor are required to wear sensible shoes.", zh:"在倉庫工作的員工必須穿著實用的鞋子。" }
    ]
  },
  {
    id: "w1599", english: "squeaky", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["發出尖銳聲音的","吱吱作響的"] ] } ],
    examples: [
      { en:"Maintenance was called in to fix the squeaky office chairs.", zh:"維修人員被叫來修理那些吱吱作響的辦公椅。" }
    ]
  },
  {
    id: "w1600", english: "succession", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["一連串","接連發生"] ] },
      { pos: "nu", meaningGroups: [ ["繼任","接班"] ] }
    ],
    examples: [
      { en:"A succession of delays pushed the launch date back by months.", zh:"一連串的延誤讓發布日期往後推了好幾個月。" },
      { en:"The board has yet to finalize its plan for executive succession.", zh:"董事會尚未確定高層接班計畫。" }
    ]
  },
  {
    id: "w1601", english: "succumb to", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["屈服於","抵擋不住"] ] } ],
    examples: [
      { en:"The startup eventually succumbed to pressure from larger competitors.", zh:"這家新創公司最終屈服於較大競爭對手的壓力。" }
    ]
  },
  {
    id: "w1602", english: "take a turn for the better", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["好轉","出現轉機"] ] } ],
    examples: [
      { en:"After the restructuring, the company's finances took a turn for the better.", zh:"重組之後，這家公司的財務狀況出現了轉機。" }
    ]
  },
  {
    id: "w1627", english: "abbreviate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["縮寫"] ] }
    ],
    examples: [
      { en:"In the report, \"Chief Executive Officer\" is usually abbreviated to \"CEO\".", zh:"在報告中，「執行長」通常縮寫為「CEO」。" }
    ]
  },
  {
    id: "w1628", english: "abridgment", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["節略本","縮寫版"] ] }
    ],
    examples: [
      { en:"The publisher released an abridgment of the classic novel for younger readers.", zh:"出版社為年輕讀者推出了這部經典小說的節略本。" }
    ]
  },
  {
    id: "w1629", english: "biweekly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adv", meaningGroups: [ ["每兩週一次地"] ] }
    ],
    examples: [
      { en:"The newsletter is distributed biweekly to all employees.", zh:"這份電子報每兩週發送一次給所有員工。" }
    ]
  },
  {
    id: "w1630", english: "clash", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["衝突","爭執"] ] }
    ],
    examples: [
      { en:"There was a clash between the two departments over budget allocation.", zh:"兩個部門在預算分配上發生了衝突。" }
    ]
  },
  {
    id: "w1631", english: "coherent", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["有條理的","前後一致的","易懂的"] ] }
    ],
    examples: [
      { en:"The manager gave a coherent explanation of the new policy.", zh:"經理對新政策做出了條理清晰的說明。" }
    ]
  },
  {
    id: "w1632", english: "counteroffer", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["還價","反提議"] ] }
    ],
    examples: [
      { en:"The company made a counteroffer to keep the talented employee from resigning.", zh:"公司提出了一個反提議，希望留住那位優秀的員工。" }
    ]
  },
  {
    id: "w1633", english: "disperse", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["散開","疏散"] ] },
      { pos: "vt", meaningGroups: [ ["使散開","驅散"] ] }
    ],
    examples: [
      { en:"The crowd began to disperse once the announcement ended.", zh:"公告結束後，人群開始散去。" },
      { en:"Security used loudspeakers to disperse the protesters outside the building.", zh:"保全人員用擴音器驅散了大樓外的抗議民眾。" }
    ]
  },
  {
    id: "w1634", english: "eloquent", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["能言善道的","口才流利的"] ] }
    ],
    examples: [
      { en:"She gave an eloquent speech at the shareholders' meeting.", zh:"她在股東會上發表了一場口才流利的演講。" }
    ]
  },
  {
    id: "w1635", english: "enthuse", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["熱切表達","讚不絕口"] ] },
      { pos: "vt", meaningGroups: [ ["使…產生熱情"] ] }
    ],
    examples: [
      { en:"The consultant enthused about the new marketing strategy during the meeting.", zh:"顧問在會議中對新的行銷策略讚不絕口。" },
      { en:"The coach tried to enthuse his team before the big presentation.", zh:"教練在重要簡報前試圖激起團隊的熱情。" }
    ]
  },
  {
    id: "w1636", english: "excerpt", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["節錄","摘錄"] ] }
    ],
    examples: [
      { en:"An excerpt from the annual report was shared with investors.", zh:"年度報告的一段摘錄已分享給投資人。" }
    ]
  },
  {
    id: "w1637", english: "faction", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["派系","小團體"] ] }
    ],
    examples: [
      { en:"There are two rival factions within the management team.", zh:"管理團隊內部存在兩個對立的派系。" }
    ]
  },
  {
    id: "w1638", english: "hold back", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["阻礙","抑制"] ] }
    ],
    examples: [
      { en:"Poor internet connectivity has been holding back the company's productivity.", zh:"網路連線不良一直在阻礙公司的生產力。" }
    ]
  },
  {
    id: "w1639", english: "inviting", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["吸引人的","誘人的"] ] }
    ],
    examples: [
      { en:"The lobby was redesigned to look more inviting to clients.", zh:"大廳重新設計後對客戶更具吸引力。" }
    ]
  },
  {
    id: "w1640", english: "on the off chance", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["萬一","以防萬一（雖然機會不大）"] ] }
    ],
    examples: [
      { en:"I called the supplier on the off chance that they still had the part in stock.", zh:"我試著打電話給供應商，希望萬一他們還有那個零件的庫存。" }
    ]
  },
  {
    id: "w1641", english: "pass around", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["傳遞","輪流傳閱"] ] }
    ],
    examples: [
      { en:"The editor passed the draft around for feedback before publishing.", zh:"編輯將草稿傳閱給大家徵求意見後才發布。" }
    ]
  },
  {
    id: "w1642", english: "presiding", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["主持的","主管的"] ] }
    ],
    examples: [
      { en:"The presiding officer opened the annual shareholders' meeting.", zh:"主持人開啟了年度股東會議。" }
    ]
  },
  {
    id: "w1643", english: "presumably", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adv", meaningGroups: [ ["據推測","大概"] ] }
    ],
    examples: [
      { en:"Presumably, the shipment was delayed due to the storm.", zh:"據推測，這批貨是因為暴風雨而延誤的。" }
    ]
  },
  {
    id: "w1644", english: "prop something against something", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["把…靠著…撐住"] ] }
    ],
    examples: [
      { en:"He propped the ladder against the warehouse wall before climbing up.", zh:"他把梯子靠在倉庫牆上撐好後才爬上去。" }
    ]
  },
  {
    id: "w1645", english: "put in an offer", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["出價（購買）","提出報價"] ] }
    ],
    examples: [
      { en:"They put in an offer for the office building before the deadline.", zh:"他們在截止日前對那棟辦公大樓提出了報價。" }
    ]
  },
  {
    id: "w1646", english: "reassure", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["使安心","使放心"] ] }
    ],
    examples: [
      { en:"The manager reassured the staff that no layoffs were planned.", zh:"經理向員工保證公司沒有計畫裁員，讓大家安心。" }
    ]
  },
  {
    id: "w1647", english: "run late", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["延誤","晚到"] ] }
    ],
    examples: [
      { en:"The shipment is running late because of the customs inspection.", zh:"由於海關檢查，這批貨延誤了。" }
    ]
  },
  {
    id: "w1648", english: "stare into", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["凝視","盯著看"] ] }
    ],
    examples: [
      { en:"He sat at his desk, staring into the screen, unable to focus.", zh:"他坐在桌前，盯著螢幕發呆，無法集中注意力。" }
    ]
  },
  {
    id: "w1649", english: "succinct", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["簡潔的","言簡意賅的"] ] }
    ],
    examples: [
      { en:"Please keep your email succinct and to the point.", zh:"請將你的電子郵件寫得簡潔扼要。" }
    ]
  },
  {
    id: "w1650", english: "symposium", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["研討會","座談會"] ] }
    ],
    examples: [
      { en:"Experts from around the world attended the symposium on renewable energy.", zh:"來自世界各地的專家出席了這場關於可再生能源的研討會。" }
    ]
  },
  {
    id: "w1651", english: "take part in", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["參與","加入"] ] }
    ],
    examples: [
      { en:"All department heads are expected to take part in the strategy meeting.", zh:"所有部門主管都應該參與這場策略會議。" }
    ]
  },
  {
    id: "w1652", english: "to start with", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["首先","一開始"] ] }
    ],
    examples: [
      { en:"To start with, let's review last quarter's sales figures.", zh:"首先，讓我們回顧一下上個季度的銷售數字。" }
    ]
  },
  {
    id: "w1653", english: "uphold", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["維護","堅持（原則、決定等）"] ] }
    ],
    examples: [
      { en:"The board voted to uphold the original decision on the merger.", zh:"董事會投票決定維持原先對合併案的決定。" }
    ]
  },
  {
    id: "w1654", english: "biannual", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["一年兩次的"] ] }
    ],
    examples: [
      { en:"The company holds a biannual review of employee performance.", zh:"公司每年舉行兩次員工績效考核。" }
    ]
  },
  {
    id: "w1655", english: "chronological", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["按時間順序的"] ] }
    ],
    examples: [
      { en:"Please arrange the invoices in chronological order.", zh:"請將這些發票按時間順序排列。" }
    ]
  },
  {
    id: "w1656", english: "citation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["引文","引述"], ["傳票","出庭通知"] ] }
    ],
    examples: [
      { en:"The report includes several citations from industry experts.", zh:"這份報告引用了幾位業界專家的話。" },
      { en:"He received a citation for parking in a restricted zone.", zh:"他因為在禁停區停車而收到一張罰單。" }
    ]
  },
  {
    id: "w1657", english: "credit someone with something", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["將…歸功於某人","認為某人具有（某特質）"] ] }
    ],
    examples: [
      { en:"Colleagues credited her with turning the failing project around.", zh:"同事們都認為是她讓這個失敗的專案重獲成功。" }
    ]
  },
  {
    id: "w1658", english: "discriminate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["歧視"], ["分辨","辨別"] ] }
    ],
    examples: [
      { en:"The company was accused of discriminating against older applicants.", zh:"這家公司被指控歧視年長的求職者。" },
      { en:"A good manager can discriminate between urgent and unimportant tasks.", zh:"優秀的經理能分辨緊急與不重要的任務。" }
    ]
  },
  {
    id: "w1659", english: "distort", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["扭曲","曲解"] ] }
    ],
    examples: [
      { en:"The press release seemed to distort the actual sales figures.", zh:"這份新聞稿似乎扭曲了實際的銷售數字。" }
    ]
  },
  {
    id: "w1660", english: "fringe benefit", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["附加福利","額外津貼"] ] }
    ],
    examples: [
      { en:"Health insurance is one of the fringe benefits offered to full-time staff.", zh:"健康保險是提供給正職員工的其中一項附加福利。" }
    ]
  },
  {
    id: "w1661", english: "give in to", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["向…讓步","屈服於"] ] }
    ],
    examples: [
      { en:"Management eventually gave in to the union's demands.", zh:"資方最終向工會的要求讓步。" }
    ]
  },
  {
    id: "w1662", english: "goodwill", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["善意","友好態度"] ] }
    ],
    examples: [
      { en:"The donation was seen as a gesture of goodwill toward the community.", zh:"這筆捐款被視為對社區展現善意的舉動。" }
    ]
  },
  {
    id: "w1663", english: "have the nerve to do something", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["有勇氣（或膽子）做某事"] ] }
    ],
    examples: [
      { en:"I didn't have the nerve to tell my boss about the mistake.", zh:"我沒有膽子告訴老闆這個錯誤。" }
    ]
  },
  {
    id: "w1664", english: "hearty", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["熱情的","衷心的"], ["豐盛的","大量的"] ] }
    ],
    examples: [
      { en:"The retiring manager received a hearty welcome at the farewell party.", zh:"即將退休的經理在歡送會上受到熱情的歡迎。" },
      { en:"The hotel offered a hearty breakfast buffet for guests.", zh:"飯店為客人提供豐盛的自助早餐。" }
    ]
  },
  {
    id: "w1665", english: "keep up to date", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["隨時更新","保持最新資訊"] ] }
    ],
    examples: [
      { en:"The HR team keeps the employee handbook up to date every year.", zh:"人資團隊每年都會將員工手冊更新到最新版本。" }
    ]
  },
  {
    id: "w1666", english: "knock off", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["下班","停止工作"] ] }
    ],
    examples: [
      { en:"Most staff knock off at six on Fridays.", zh:"大多數員工週五六點就下班了。" }
    ]
  },
  {
    id: "w1667", english: "know something like the back of your hand", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["對某事物非常熟悉","瞭若指掌"] ] }
    ],
    examples: [
      { en:"After ten years in the role, she knows the supply chain like the back of her hand.", zh:"她在這個職位十年了，對供應鏈瞭若指掌。" }
    ]
  },
  {
    id: "w1668", english: "laugh away", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["用笑聲化解（尷尬或不悅）"] ] }
    ],
    examples: [
      { en:"He laughed away the criticism instead of taking it seriously.", zh:"他用一笑置之的方式化解了那些批評，而不是認真對待。" }
    ]
  },
  {
    id: "w1669", english: "nursery", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["托兒所"], ["苗圃","花圃"] ] },
      { pos: "adj", meaningGroups: [ ["幼兒教育的"] ] }
    ],
    examples: [
      { en:"Many offices now provide an on-site nursery for employees' children.", zh:"許多辦公室現在為員工的孩子提供附設托兒所。" },
      { en:"The garden center runs a small nursery selling young trees.", zh:"這家園藝中心經營一個小苗圃，出售幼樹。" },
      { en:"The company expanded its benefits to include nursery education subsidies.", zh:"公司擴大了福利範圍，納入幼兒教育補助。" }
    ]
  },
  {
    id: "w1670", english: "off-peak", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["非高峰時段的","離峰的"] ] }
    ],
    examples: [
      { en:"Off-peak flights are usually much cheaper for business travelers.", zh:"離峰時段的班機通常對商務旅客來說便宜許多。" }
    ]
  },
  {
    id: "w1671", english: "overtime rate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["加班費率"] ] }
    ],
    examples: [
      { en:"The overtime rate is one and a half times the regular hourly wage.", zh:"加班費率是正常時薪的一點五倍。" }
    ]
  },
  {
    id: "w1672", english: "pending", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["懸而未決的","即將發生的"] ] },
      { pos: "prep", meaningGroups: [ ["在…之前（暫緩）","等待…期間"] ] }
    ],
    examples: [
      { en:"Her promotion is still pending approval from the board.", zh:"她的升遷仍在等待董事會的核准。" },
      { en:"The shipment was suspended pending a safety inspection.", zh:"這批貨物在等待安全檢查期間暫停出貨。" }
    ]
  },
  {
    id: "w1673", english: "pique", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["不悅","慍怒"] ] }
    ],
    examples: [
      { en:"He left the meeting in a fit of pique after his proposal was rejected.", zh:"他的提案被否決後，他氣憤地離開了會議。" }
    ]
  },
  {
    id: "w1674", english: "preservation area", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["保育區","自然保護區"] ] }
    ],
    examples: [
      { en:"The new factory site was rejected because it borders a preservation area.", zh:"新工廠選址因為緊鄰一個自然保護區而遭到否決。" }
    ]
  },
  {
    id: "w1675", english: "sabotage", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["蓄意破壞","暗中阻撓"] ] }
    ],
    examples: [
      { en:"An employee was accused of sabotaging the company's server systems.", zh:"一名員工被指控蓄意破壞公司的伺服器系統。" }
    ]
  },
  {
    id: "w1676", english: "safety drill", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["安全演習","應變演練"] ] }
    ],
    examples: [
      { en:"The office holds a fire safety drill twice a year.", zh:"這間辦公室每年舉行兩次消防安全演習。" }
    ]
  },
  {
    id: "w1677", english: "second", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["附議","正式表示支持"] ] }
    ],
    examples: [
      { en:"The proposal was seconded by the finance director before the vote.", zh:"這項提案在投票前獲得財務總監的附議。" }
    ]
  },
  {
    id: "w1678", english: "severance pay", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["遣散費"] ] }
    ],
    examples: [
      { en:"Employees who were laid off received three months of severance pay.", zh:"被裁員的員工獲得三個月的遣散費。" }
    ]
  },
  {
    id: "w1679", english: "sheltered housing", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["（為老年人或弱勢者提供的）安養住宅"] ] }
    ],
    examples: [
      { en:"The charity built sheltered housing for elderly residents in the district.", zh:"這個慈善機構在該地區為年長居民建造了安養住宅。" }
    ]
  },
  {
    id: "w1680", english: "spry", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["矯健的","老當益壯的"] ] }
    ],
    examples: [
      { en:"Despite his age, the retired founder remains remarkably spry.", zh:"儘管年事已高，這位退休的創辦人依然十分矯健。" }
    ]
  },
  {
    id: "w1681", english: "straightforward", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["簡單的","易懂的"], ["誠實直率的"] ] }
    ],
    examples: [
      { en:"The new software has a straightforward interface that requires no training.", zh:"這個新軟體介面簡單易懂，不需要培訓。" },
      { en:"Our supervisor is straightforward and always tells us exactly what she thinks.", zh:"我們的主管非常直率，總是直接說出她的想法。" }
    ]
  },
  {
    id: "w1682", english: "strong-willed", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["意志堅定的","固執己見的"] ] }
    ],
    examples: [
      { en:"The negotiator was strong-willed and refused to lower the price.", zh:"那位談判代表意志堅定，拒絕降價。" }
    ]
  },
  {
    id: "w1683", english: "take some time off", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["請假","休息一段時間"] ] }
    ],
    examples: [
      { en:"He decided to take some time off after finishing the big project.", zh:"他在完成這個大專案後決定請一段時間的假。" }
    ]
  },
  {
    id: "w1684", english: "terribly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adv", meaningGroups: [ ["非常","極其"] ] }
    ],
    examples: [
      { en:"We are terribly sorry for the delay in shipping your order.", zh:"我們對您訂單出貨延誤感到非常抱歉。" }
    ]
  },
  {
    id: "w1685", english: "yearn", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["渴望","嚮往"] ] }
    ],
    examples: [
      { en:"After years at a desk job, she yearned for a more creative career.", zh:"在辦公室工作多年後，她渴望能有更具創造力的職業。" }
    ]
  },
  {
    id: "w1686", english: "arm in arm", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["手臂勾著手臂地","手牽手地"] ] }
    ],
    examples: [
      { en:"The two retiring partners walked arm in arm into the farewell dinner.", zh:"兩位即將退休的合夥人手勾著手走進歡送晚宴。" }
    ]
  },
  {
    id: "w1687", english: "aspire to", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["渴望","有志於"] ] }
    ],
    examples: [
      { en:"Many young employees aspire to become managers within five years.", zh:"許多年輕員工渴望在五年內成為經理。" }
    ]
  },
  {
    id: "w1688", english: "cordially", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adv", meaningGroups: [ ["誠摯地","友善地"], ["謹啟（信函結尾用語）"] ] }
    ],
    examples: [
      { en:"You are cordially invited to attend our company's tenth anniversary gala.", zh:"誠摯邀請您出席本公司十週年慶祝晚會。" },
      { en:"We look forward to your reply. Cordially, John Smith.", zh:"期待您的回覆。謹啟，約翰·史密斯。" }
    ]
  },
  {
    id: "w1689", english: "degrade", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["貶低","侮辱"], ["使…品質下降","破壞"] ] }
    ],
    examples: [
      { en:"The advertisement was criticized for degrading female employees.", zh:"這則廣告因貶低女性員工而受到批評。" },
      { en:"Constant exposure to sunlight can degrade the quality of the packaging.", zh:"長期暴露在陽光下會使包裝的品質變差。" }
    ]
  },
  {
    id: "w1690", english: "delicate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["易碎的","脆弱的","需謹慎處理的"] ] }
    ],
    examples: [
      { en:"The negotiations are at a delicate stage, so please avoid public comments.", zh:"談判正處於敏感階段，請避免公開發表評論。" }
    ]
  },
  {
    id: "w1691", english: "deploy", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["部署","調度運用"] ] }
    ],
    examples: [
      { en:"The firm plans to deploy additional staff to handle the holiday rush.", zh:"公司計畫調派更多員工來應付假期業務高峰。" }
    ]
  },
  {
    id: "w1692", english: "dignitary", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["政要","顯要人物"] ] }
    ],
    examples: [
      { en:"Several foreign dignitaries attended the trade conference opening ceremony.", zh:"幾位外國政要出席了這場貿易會議的開幕典禮。" }
    ]
  },
  {
    id: "w1693", english: "disorient", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["使…迷失方向","使…困惑"] ] }
    ],
    examples: [
      { en:"The sudden change in management disoriented many employees.", zh:"管理層的突然變動讓許多員工感到困惑。" }
    ]
  },
  {
    id: "w1694", english: "empower", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["授權","賦予權力"] ] }
    ],
    examples: [
      { en:"The new policy empowers managers to approve small expenses on their own.", zh:"新政策授權經理可自行核准小額支出。" }
    ]
  },
  {
    id: "w1695", english: "extraordinary feat", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["非凡的成就","了不起的成果"] ] }
    ],
    examples: [
      { en:"Completing the merger within three months was an extraordinary feat.", zh:"三個月內完成這次合併是個了不起的成就。" }
    ]
  },
  {
    id: "w1696", english: "fill in for someone", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["代替某人（暫代職務）"] ] }
    ],
    examples: [
      { en:"I'll fill in for the receptionist while she's on maternity leave.", zh:"在她產假期間，我會代理接待員的工作。" }
    ]
  },
  {
    id: "w1697", english: "forage", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["尋找食物","覓食"] ] },
      { pos: "nu", meaningGroups: [ ["（家畜的）飼料"] ] }
    ],
    examples: [
      { en:"The survival team had to forage for food after the flight was delayed for days.", zh:"因班機延誤數日，求生團隊必須四處尋找食物。" },
      { en:"The farm stores winter forage for the cattle in a large barn.", zh:"這座農場在大型穀倉裡儲存牛群過冬用的飼料。" }
    ]
  },
  {
    id: "w1698", english: "gratis", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adv", meaningGroups: [ ["免費地"] ] },
      { pos: "adj", meaningGroups: [ ["免費的"] ] }
    ],
    examples: [
      { en:"The consulting firm offered the first session gratis to attract new clients.", zh:"這家顧問公司為吸引新客戶，第一次諮詢免費提供。" }
    ]
  },
  {
    id: "w1699", english: "heighten", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["加劇","增強"] ] }
    ],
    examples: [
      { en:"The delay in delivery only heightened the client's frustration.", zh:"交貨延誤只讓客戶更加不滿。" }
    ]
  },
  {
    id: "w1700", english: "hurdle", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["障礙","難題"], ["跨欄（賽跑用具）"] ] },
      { pos: "vt", meaningGroups: [ ["跨越（障礙）"] ] }
    ],
    examples: [
      { en:"Securing funding was the biggest hurdle for the startup.", zh:"籌措資金是這家新創公司最大的障礙。" },
      { en:"The athlete cleared every hurdle on the track with ease.", zh:"這位選手輕鬆越過了跑道上的每一個跨欄。" },
      { en:"The runner hurdled the final barrier and won the race.", zh:"這位跑者跨過最後一個障礙贏得了比賽。" }
    ]
  },
  {
    id: "w1701", english: "immensity", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["巨大","龐大規模"] ] }
    ],
    examples: [
      { en:"The immensity of the project made the team hesitant to start.", zh:"這個專案的龐大規模讓團隊遲遲不敢展開。" }
    ]
  },
  {
    id: "w1702", english: "incumbent", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["現任者"] ] },
      { pos: "adj", meaningGroups: [ ["現任的"] ] }
    ],
    examples: [
      { en:"The incumbent will step down at the end of this term.", zh:"現任者將在這個任期結束後卸任。" },
      { en:"The incumbent CEO announced her retirement plans yesterday.", zh:"現任執行長昨天宣布了她的退休計畫。" }
    ]
  },
  {
    id: "w1703", english: "in defiance of", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["不顧","公然違抗"] ] }
    ],
    examples: [
      { en:"The factory kept operating in defiance of the safety regulations.", zh:"這家工廠不顧安全規範，仍持續運作。" }
    ]
  },
  {
    id: "w1704", english: "irreversible", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["不可逆的","無法挽回的"] ] }
    ],
    examples: [
      { en:"Cutting the research budget could have an irreversible impact on innovation.", zh:"削減研究預算可能對創新造成無法挽回的影響。" }
    ]
  },
  {
    id: "w1705", english: "lingering", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["持續不去的","揮之不去的"] ] }
    ],
    examples: [
      { en:"There are still lingering doubts among investors about the merger.", zh:"投資人對這次合併仍存有揮之不去的疑慮。" }
    ]
  },
  {
    id: "w1706", english: "lose yourself in something", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["全神貫注於某事","沉浸其中"] ] }
    ],
    examples: [
      { en:"She often loses herself in her work and forgets to take breaks.", zh:"她常常全神貫注於工作而忘了休息。" }
    ]
  },
  {
    id: "w1707", english: "miscellaneous", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["各式各樣的","雜項的"] ] }
    ],
    examples: [
      { en:"The budget includes a small amount for miscellaneous office expenses.", zh:"預算中包含一小筆雜項辦公費用。" }
    ]
  },
  {
    id: "w1708", english: "namely", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adv", meaningGroups: [ ["也就是說","即"] ] }
    ],
    examples: [
      { en:"Two departments missed the deadline, namely marketing and logistics.", zh:"有兩個部門沒能趕上截止日期，也就是行銷部和物流部。" }
    ]
  },
  {
    id: "w1709", english: "pass up", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["錯過（機會）","放棄"] ] }
    ],
    examples: [
      { en:"He decided not to pass up the chance to lead the new project.", zh:"他決定不放棄領導這個新專案的機會。" }
    ]
  },
  {
    id: "w1710", english: "pavilion", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["展覽館","涼亭"] ] }
    ],
    examples: [
      { en:"Our company reserved a pavilion at the trade show this year.", zh:"我們公司今年在展覽會上租了一個展館。" }
    ]
  },
  {
    id: "w1711", english: "plunge", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["驟然跌落","突然下降"] ] },
      { pos: "nc", meaningGroups: [ ["暴跌","大幅下滑"] ] }
    ],
    examples: [
      { en:"The company's stock plunged after the disappointing earnings report.", zh:"令人失望的財報公布後，公司股價驟然下跌。" },
      { en:"Analysts predict a plunge in demand for the product next quarter.", zh:"分析師預測下季度該產品的需求將出現大幅下滑。" }
    ]
  },
  {
    id: "w1712", english: "preach", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["說教","訓誡"] ] }
    ],
    examples: [
      { en:"The manager kept preaching about punctuality during every meeting.", zh:"經理在每次會議中都不斷說教強調準時的重要。" }
    ]
  },
  {
    id: "w1713", english: "push back", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["推延","延後"] ] }
    ],
    examples: [
      { en:"The launch date has been pushed back due to supply shortages.", zh:"由於供應短缺，上市日期已被延後。" }
    ]
  },
  {
    id: "w1714", english: "put in for something", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["正式申請","提出要求"] ] }
    ],
    examples: [
      { en:"She put in for a transfer to the overseas branch.", zh:"她正式申請調到海外分公司。" }
    ]
  },
  {
    id: "w1715", english: "rear", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["後方","後部"] ] },
      { pos: "adj", meaningGroups: [ ["後方的","後面的"] ] }
    ],
    examples: [
      { en:"Deliveries should be made at the rear of the building.", zh:"送貨請走建築物的後方。" },
      { en:"The rear entrance is reserved for staff only.", zh:"後方入口僅供員工使用。" }
    ]
  },
  {
    id: "w1716", english: "reinstate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["恢復（職位）","使復職"] ] }
    ],
    examples: [
      { en:"The employee was reinstated after the investigation cleared his name.", zh:"調查證明他無罪後，這名員工恢復了職位。" }
    ]
  },
  {
    id: "w1717", english: "ritual", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["固定儀式","慣例"] ] }
    ],
    examples: [
      { en:"Reviewing the sales report every Monday morning has become a ritual for the team.", zh:"每週一早上檢視銷售報告已成為這個團隊的固定慣例。" }
    ]
  },
  {
    id: "w1718", english: "scheme", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["計畫","方案"] ] },
      { pos: "vi", meaningGroups: [ ["密謀","策劃陰謀"] ] }
    ],
    examples: [
      { en:"The city launched a new recycling scheme for local businesses.", zh:"該市為當地企業推出了一項新的回收計畫。" },
      { en:"Rumor had it that two managers were scheming to take over the department.", zh:"傳言有兩位經理正密謀奪取部門的控制權。" }
    ]
  },
  {
    id: "w1719", english: "scuff", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["刮傷","磨損（表面）"] ] },
      { pos: "nc", meaningGroups: [ ["磨損痕跡","刮痕"] ] }
    ],
    examples: [
      { en:"Please be careful not to scuff the newly polished floor.", zh:"請小心不要刮傷剛打磨好的地板。" },
      { en:"There were several scuffs on the conference table after the event.", zh:"活動結束後，會議桌上留下了好幾處刮痕。" }
    ]
  },
  {
    id: "w1720", english: "shred", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["撕碎","粉碎（文件）"] ] },
      { pos: "nc", meaningGroups: [ ["一點點","極少量"], ["碎片","細條"] ] }
    ],
    examples: [
      { en:"All confidential documents must be shredded before disposal.", zh:"所有機密文件在丟棄前都必須先碎紙處理。" },
      { en:"There isn't a shred of evidence to support the complaint.", zh:"沒有一絲一毫的證據能支持這項投訴。" },
      { en:"The old contract was cut into shreds after the new one was signed.", zh:"新合約簽署後，舊合約被剪成了碎片。" }
    ]
  },
  {
    id: "w1721", english: "speck", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["微小的痕跡","小顆粒","少量"] ] }
    ],
    examples: [
      { en:"Not a speck of dust was found on the newly cleaned equipment.", zh:"剛清潔過的設備上找不到一點灰塵。" }
    ]
  },
  {
    id: "w1722", english: "take early retirement", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["提早退休"] ] }
    ],
    examples: [
      { en:"Several senior staff chose to take early retirement during the restructuring.", zh:"在組織重組期間，好幾位資深員工選擇提早退休。" }
    ]
  },
  {
    id: "w1723", english: "underpass", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["地下道","地下通道"] ] }
    ],
    examples: [
      { en:"Workers will build a new underpass to connect the two office buildings.", zh:"施工人員將興建一條新的地下通道連接這兩棟辦公大樓。" }
    ]
  },
  {
    id: "w1724", english: "unwind", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["放鬆","舒緩壓力"] ] },
      { pos: "vt", meaningGroups: [ ["解開","鬆開"] ] }
    ],
    examples: [
      { en:"Many employees go for a walk to unwind after a stressful meeting.", zh:"許多員工在壓力大的會議後會去散步放鬆一下。" },
      { en:"She carefully unwound the cable before packing it into the box.", zh:"她小心地解開電線後才把它裝進箱子。" }
    ]
  },
  {
    id: "w1725", english: "upbeat", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["樂觀的","充滿希望的"] ] }
    ],
    examples: [
      { en:"The CEO remained upbeat about the company's prospects despite the slow quarter.", zh:"儘管這個季度表現平淡，執行長對公司前景仍保持樂觀。" }
    ]
  },
  {
    id: "w1726", english: "at full speed", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["以最快速度","全速地"] ] }
    ],
    examples: [
      { en:"The factory is running at full speed to meet the year-end order deadline.", zh:"這家工廠正全速運轉以趕上年終訂單的截止日期。" }
    ]
  },
  {
    id: "w1727", english: "bear", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["帶有","載有","懷有"] ] }
    ],
    examples: [
      { en:"This warranty card bears the date of purchase and the store's stamp.", zh:"這張保修卡上載明了購買日期以及店家的印章。" }
    ]
  },
  {
    id: "w1728", english: "be held up in traffic", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["被塞車耽誤","被交通堵塞困住"] ] }
    ],
    examples: [
      { en:"I'm sorry I'm late — I was held up in traffic on the highway.", zh:"很抱歉我遲到了，我在高速公路上被塞車耽誤了。" }
    ]
  },
  {
    id: "w1729", english: "be towed away", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["（車輛）被拖走"] ] }
    ],
    examples: [
      { en:"His car was towed away because it was parked in a no-parking zone.", zh:"他的車因為停在禁停區而被拖走了。" }
    ]
  },
  {
    id: "w1730", english: "bypass", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["環道","替代道路"], ["繞道手術"] ] }
    ],
    examples: [
      { en:"The new bypass has reduced traffic through the town center significantly.", zh:"這條新的環道大幅減少了穿越市中心的車流量。" },
      { en:"He underwent a coronary bypass last month and is recovering well.", zh:"他上個月接受了心臟繞道手術，目前恢復良好。" }
    ]
  },
  {
    id: "w1731", english: "carpool", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["共乘（汽車）"] ] },
      { pos: "nc", meaningGroups: [ ["共乘車隊","汽車共乘小組"] ] }
    ],
    examples: [
      { en:"Several colleagues carpool to the office to save on gas and parking.", zh:"幾位同事共乘上班以節省油錢和停車費。" },
      { en:"The company set up a carpool to help employees commute more efficiently.", zh:"公司成立了一個共乘小組以幫助員工更有效率地通勤。" }
    ]
  },
  {
    id: "w1732", english: "carriage", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["（火車）車廂"], ["馬車"] ] }
    ],
    examples: [
      { en:"Passengers were asked to move to the front carriage of the train.", zh:"乘客被要求移動到列車的前方車廂。" },
      { en:"Tourists can take a horse-drawn carriage around the old town.", zh:"遊客可以搭乘馬車遊覽舊城區。" }
    ]
  },
  {
    id: "w1733", english: "collide", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["碰撞","相撞"] ] }
    ],
    examples: [
      { en:"Two delivery trucks collided at the intersection near the warehouse.", zh:"兩輛送貨卡車在倉庫附近的十字路口相撞。" }
    ]
  },
  {
    id: "w1734", english: "come to a standstill", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["停頓","停滯不前"] ] }
    ],
    examples: [
      { en:"Production came to a standstill after the main machine broke down.", zh:"主要機器故障後，生產完全停頓下來。" }
    ]
  },
  {
    id: "w1735", english: "direct traffic", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["指揮交通"] ] }
    ],
    examples: [
      { en:"A security guard was directing traffic outside the venue during the event.", zh:"活動期間，一名保全人員在會場外指揮交通。" }
    ]
  },
  {
    id: "w1736", english: "drawbridge", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["活動橋","可升降的橋"] ] }
    ],
    examples: [
      { en:"The old castle still has a working drawbridge over its moat.", zh:"這座古老的城堡至今仍有一座可運作的護城河活動橋。" }
    ]
  },
  {
    id: "w1737", english: "driveway", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["私人車道"] ] }
    ],
    examples: [
      { en:"Please park your car in the driveway, not on the street.", zh:"請把車停在私人車道上，不要停在街上。" }
    ]
  },
  {
    id: "w1738", english: "emphatic", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["強調的","明確有力的"] ] }
    ],
    examples: [
      { en:"The director gave an emphatic denial of the rumors about the merger.", zh:"主管對合併的謠言做出了明確有力的否認。" }
    ]
  },
  {
    id: "w1739", english: "footrest", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["腳踏板","足部支撐架"] ] }
    ],
    examples: [
      { en:"The office chair comes with an adjustable footrest for extra comfort.", zh:"這款辦公椅配有可調式腳踏板，讓人坐得更舒適。" }
    ]
  },
  {
    id: "w1740", english: "gratuity", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["小費","服務費"] ] }
    ],
    examples: [
      { en:"A gratuity is usually included in the bill at this restaurant.", zh:"這家餐廳的帳單通常已經包含服務費。" }
    ]
  },
  {
    id: "w1741", english: "hastily", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adv", meaningGroups: [ ["匆忙地","倉促地"] ] }
    ],
    examples: [
      { en:"The report was written hastily and contained several errors.", zh:"這份報告寫得太匆忙，出現了好幾個錯誤。" }
    ]
  },
  {
    id: "w1742", english: "have a flat tire", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["輪胎沒氣了","爆胎"] ] }
    ],
    examples: [
      { en:"We were late for the client meeting because the van had a flat tire.", zh:"因為廂型車爆胎，我們去見客戶的會議遲到了。" }
    ]
  },
  {
    id: "w1743", english: "lane", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["車道","跑道"] ] }
    ],
    examples: [
      { en:"Trucks are required to stay in the right-hand lane on this highway.", zh:"這條公路上卡車必須行駛在右側車道。" }
    ]
  },
  {
    id: "w1744", english: "lean over the railing", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["倚靠或俯身在欄杆上"] ] }
    ],
    examples: [
      { en:"Visitors are asked not to lean over the railing at the observation deck.", zh:"觀景台的訪客被要求不要俯身靠在欄杆上。" }
    ]
  },
  {
    id: "w1745", english: "license plate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["車牌"] ] }
    ],
    examples: [
      { en:"Security recorded the license plate of every vehicle entering the lot.", zh:"保全人員記錄了每輛進入停車場車輛的車牌。" }
    ]
  },
  {
    id: "w1746", english: "march", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["行進","邁步前進"] ] }
    ],
    examples: [
      { en:"Employees marched to the parking lot during the fire drill.", zh:"消防演習期間，員工們列隊走到停車場。" }
    ]
  },
  {
    id: "w1747", english: "mileage", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["行駛里程","油耗里程"] ] }
    ],
    examples: [
      { en:"The delivery company tracks the mileage of every vehicle in its fleet.", zh:"這家貨運公司會追蹤車隊中每輛車的行駛里程。" }
    ]
  },
  {
    id: "w1748", english: "necessitate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["使…成為必要","需要"] ] }
    ],
    examples: [
      { en:"The rapid growth necessitated hiring additional warehouse staff.", zh:"快速的成長使得公司必須增聘更多倉儲人員。" }
    ]
  },
  {
    id: "w1749", english: "overnight express", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["夜間快車","隔夜快遞班次"] ] }
    ],
    examples: [
      { en:"We shipped the samples via overnight express to meet the client's deadline.", zh:"我們透過隔夜快遞寄送樣品，以趕上客戶的截止日期。" }
    ]
  },
  {
    id: "w1750", english: "passerby", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["路人","過路人"] ] }
    ],
    examples: [
      { en:"A passerby reported the broken storefront window to the police.", zh:"一名路人向警方報告了店面破損的窗戶。" }
    ]
  },
  {
    id: "w1752", english: "principal", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["主要的","首要的"] ] },
      { pos: "nc", meaningGroups: [ ["負責人","校長"] ] }
    ],
    examples: [
      { en:"Cost reduction is the principal reason for relocating the factory.", zh:"降低成本是遷廠的主要原因。" },
      { en:"The bank appointed a new principal to oversee the branch.", zh:"這家銀行指派了一位新的負責人來監督分行業務。" }
    ]
  },
  {
    id: "w1753", english: "pull into", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["（車輛）駛入並停靠"] ] }
    ],
    examples: [
      { en:"The delivery truck pulled into the loading dock right on schedule.", zh:"貨車準時駛入裝卸區停靠。" }
    ]
  },
  {
    id: "w1754", english: "ramp", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["斜坡","坡道"] ] }
    ],
    examples: [
      { en:"A wheelchair ramp was installed at the main entrance of the office.", zh:"辦公室的正門裝設了一個輪椅坡道。" }
    ]
  },
  {
    id: "w1755", english: "refurbish", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["翻新","重新裝修"] ] }
    ],
    examples: [
      { en:"The company plans to refurbish its headquarters lobby next year.", zh:"公司計畫明年翻新總部大廳。" }
    ]
  },
  {
    id: "w1756", english: "ridership", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["（大眾運輸的）乘客人數"] ] }
    ],
    examples: [
      { en:"Subway ridership dropped sharply during the holiday season.", zh:"假期期間地鐵的乘客人數大幅下降。" }
    ]
  },
  {
    id: "w1757", english: "spoke", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["（輪子的）輪輻"] ] }
    ],
    examples: [
      { en:"One of the spokes on the delivery bike's wheel was bent.", zh:"送貨腳踏車輪子上的一根輪輻彎曲了。" }
    ]
  },
  {
    id: "w1758", english: "steering wheel", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["方向盤"] ] }
    ],
    examples: [
      { en:"The driver gripped the steering wheel tightly in the heavy rain.", zh:"大雨中，司機緊緊握住方向盤。" }
    ]
  },
  {
    id: "w1759", english: "still", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["靜止不動的"] ] }
    ],
    examples: [
      { en:"Please remain still while the security camera captures your badge photo.", zh:"拍攝識別證照片時請保持靜止不動。" }
    ]
  },
  {
    id: "w1760", english: "storage compartment", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["儲物櫃","置物空間"] ] }
    ],
    examples: [
      { en:"She placed her laptop in the overhead storage compartment on the train.", zh:"她把筆電放進火車上方的置物櫃裡。" }
    ]
  },
  {
    id: "w1761", english: "streetcar", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["有軌電車"] ] }
    ],
    examples: [
      { en:"Tourists often take the streetcar to explore the downtown area.", zh:"遊客常搭乘有軌電車遊覽市中心。" }
    ]
  },
  {
    id: "w1762", english: "toll", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["通行費","過路費"] ] }
    ],
    examples: [
      { en:"Drivers must pay a toll to use this section of the highway.", zh:"駕駛人使用這段高速公路必須支付通行費。" }
    ]
  },
  {
    id: "w1763", english: "wagon", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["貨運馬車"], ["（火車）貨運車廂"] ] }
    ],
    examples: [
      { en:"The museum displays an old wagon once used to haul goods.", zh:"博物館展示了一輛曾用於運貨的老式馬車。" },
      { en:"The cargo was loaded onto three wagons at the freight yard.", zh:"這批貨物在貨運場被裝上了三個貨運車廂。" }
    ]
  },
  {
    id: "w1764", english: "windshield", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["擋風玻璃"] ] }
    ],
    examples: [
      { en:"A small crack appeared on the windshield after the storm.", zh:"暴風雨過後，擋風玻璃上出現了一道小裂痕。" }
    ]
  },
  {
    id: "w1765", english: "accounts payable", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["應付帳款"] ] }
    ],
    examples: [
      { en:"Accounts payable decreased significantly compared to last quarter.", zh:"應付帳款相較於上個季度大幅減少。" }
    ]
  },
  {
    id: "w1766", english: "accrue", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["累積","逐漸增加"] ] }
    ],
    examples: [
      { en:"Interest will accrue on the savings account at a rate of two percent a year.", zh:"這個儲蓄帳戶的利息將以每年百分之二的比率累積。" }
    ]
  },
  {
    id: "w1767", english: "alternate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["交替進行","輪流做"] ] }
    ],
    examples: [
      { en:"He alternates working from home with days in the office.", zh:"他在家工作與到辦公室上班交替進行。" }
    ]
  },
  {
    id: "w1768", english: "awfully", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adv", meaningGroups: [ ["非常","極其"] ] }
    ],
    examples: [
      { en:"It's awfully difficult to get an appointment with the branch manager this week.", zh:"這週要跟分行經理約時間非常困難。" }
    ]
  },
  {
    id: "w1769", english: "bank teller", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["銀行櫃員","出納員"] ] }
    ],
    examples: [
      { en:"The bank teller helped her set up a new savings account.", zh:"銀行櫃員協助她開了一個新的儲蓄帳戶。" }
    ]
  },
  {
    id: "w1770", english: "be amazed at", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["對…感到驚訝","對…感到驚奇"] ] }
    ],
    examples: [
      { en:"Investors were amazed at how quickly the company recovered from the loss.", zh:"投資人對這家公司能如此快速地從虧損中恢復感到十分驚訝。" }
    ]
  },
  {
    id: "w1771", english: "be caught in", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["被困在…裡","卡在…裡"] ] }
    ],
    examples: [
      { en:"Her flight was caught in a long delay because of the storm.", zh:"她的班機因為暴風雨而被困在長時間的延誤中。" }
    ]
  },
  {
    id: "w1772", english: "belatedly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adv", meaningGroups: [ ["延遲地","為時已晚地"] ] }
    ],
    examples: [
      { en:"The bank belatedly launched its mobile payment service, well after its rivals.", zh:"這家銀行比競爭對手晚了許久，才延遲推出行動支付服務。" }
    ]
  },
  {
    id: "w1773", english: "cluster", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["一群","一簇"] ] }
    ],
    examples: [
      { en:"A cluster of small businesses opened accounts at the new branch this month.", zh:"這個月有一群小型企業在新分行開設了帳戶。" }
    ]
  },
  {
    id: "w1774", english: "contender", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["競爭者","角逐者"] ] }
    ],
    examples: [
      { en:"She is considered a serious contender for the branch manager position.", zh:"她被視為角逐分行經理職位的有力競爭者。" }
    ]
  },
  {
    id: "w1775", english: "debit card", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["借記卡","轉帳卡"] ] }
    ],
    examples: [
      { en:"I paid for the office supplies with my debit card.", zh:"我用借記卡付了辦公用品的錢。" }
    ]
  },
  {
    id: "w1776", english: "deposit slip", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["存款單"] ] }
    ],
    examples: [
      { en:"Please fill out the deposit slip in pen, not in pencil.", zh:"請用鋼筆填寫存款單，不要用鉛筆。" }
    ]
  },
  {
    id: "w1777", english: "deterrent", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["嚇阻因素","威嚇手段"] ] }
    ],
    examples: [
      { en:"Higher fines act as a deterrent to late tax filing.", zh:"提高罰款金額對延遲申報稅務有嚇阻作用。" }
    ]
  },
  {
    id: "w1778", english: "direct deposit", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["直接轉帳存入","薪資轉帳"] ] }
    ],
    examples: [
      { en:"All employees are paid by direct deposit on the last Friday of the month.", zh:"所有員工的薪資都在每月最後一個星期五以直接轉帳的方式發放。" }
    ]
  },
  {
    id: "w1779", english: "forge", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["偽造","仿造"] ] }
    ],
    examples: [
      { en:"The clerk was arrested for forging the manager's signature on the checks.", zh:"這名職員因偽造經理在支票上的簽名而遭逮捕。" }
    ]
  },
  {
    id: "w1780", english: "forgery", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["偽造","偽造罪"] ] },
      { pos: "nc", meaningGroups: [ ["偽造品","仿製品"] ] }
    ],
    examples: [
      { en:"He was sentenced to two years in prison for forgery.", zh:"他因偽造罪被判處兩年徒刑。" },
      { en:"Bank staff are trained to spot forgeries among the checks they process.", zh:"銀行員都受過訓練，能在處理支票時識別偽造品。" }
    ]
  },
  {
    id: "w1781", english: "for the sake of", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["為了…的利益","為了…著想"] ] }
    ],
    examples: [
      { en:"The two firms agreed to merge for the sake of long-term stability.", zh:"這兩家公司為了長期的穩定而同意合併。" }
    ]
  },
  {
    id: "w1782", english: "fortnight", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["兩週","十四天"] ] }
    ],
    examples: [
      { en:"The audit is expected to take a fortnight to complete.", zh:"這次審計預計需要兩週才能完成。" }
    ]
  },
  {
    id: "w1783", english: "make a withdrawal", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["提款","提取存款"] ] }
    ],
    examples: [
      { en:"You can make a withdrawal from any branch nationwide with this card.", zh:"憑這張卡，你可以在全國任何一家分行提款。" }
    ]
  },
  {
    id: "w1784", english: "midtown", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["市中心區域"] ] }
    ],
    examples: [
      { en:"The firm's new office is located in midtown, close to several major banks.", zh:"這家公司的新辦公室位於市中心區域，鄰近幾家大型銀行。" }
    ]
  },
  {
    id: "w1785", english: "on standby", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["待命","隨時準備"] ] }
    ],
    examples: [
      { en:"An extra teller was kept on standby in case of long lines during the holiday.", zh:"為應付假期可能出現的長排隊人潮，額外安排了一名櫃員待命。" }
    ]
  },
  {
    id: "w1786", english: "overdrawn", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["透支的","超額提取的"] ] }
    ],
    examples: [
      { en:"His account was overdrawn by two hundred dollars, so the payment bounced.", zh:"他的帳戶透支了兩百美元，因此那筆款項付款失敗。" }
    ]
  },
  {
    id: "w1787", english: "public holiday", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["公共假日","國定假日"] ] }
    ],
    examples: [
      { en:"The branch will be closed on Monday for the public holiday.", zh:"由於國定假日，這家分行週一將休息。" }
    ]
  },
  {
    id: "w1788", english: "redemption", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["（債券、股份等的）贖回，變現"] ] }
    ],
    examples: [
      { en:"Redemptions of over $50,000 require a signature guarantee.", zh:"金額超過五萬美元的贖回申請需要簽名保證。" }
    ]
  },
  {
    id: "w1789", english: "remit", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["匯款","寄錢"] ] }
    ],
    examples: [
      { en:"He remits part of his monthly salary to his family overseas.", zh:"他每個月都會匯一部分薪水給海外的家人。" }
    ]
  },
  {
    id: "w1790", english: "scrutinize", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["仔細檢查","詳細審查"] ] }
    ],
    examples: [
      { en:"Auditors scrutinized every transaction in the account before approving the loan.", zh:"審計人員在核准貸款前，仔細審查了帳戶中的每一筆交易。" }
    ]
  },
  {
    id: "w1791", english: "secured", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["有擔保的","有抵押保障的"] ] }
    ],
    examples: [
      { en:"Her business loan is secured against the value of her house.", zh:"她的商業貸款以房屋價值作為擔保。" }
    ]
  },
  {
    id: "w1792", english: "spurious", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["虛假的","不實的"] ] }
    ],
    examples: [
      { en:"The bank rejected the claim after finding the receipts were spurious.", zh:"銀行發現這些收據是偽造不實的之後，駁回了這項理賠申請。" }
    ]
  },
  {
    id: "w1793", english: "sustain", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["維持","使持續"], ["支撐","維持（生存）"] ] }
    ],
    examples: [
      { en:"The bank hopes to sustain its growth in the coming year.", zh:"這家銀行希望在來年維持成長。" },
      { en:"A steady cash flow is essential to sustain a small business.", zh:"穩定的現金流對維持一家小企業的生存至關重要。" }
    ]
  },
  {
    id: "w1794", english: "take out a loan", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["申請貸款","借貸"] ] }
    ],
    examples: [
      { en:"They took out a loan to expand their restaurant business.", zh:"他們申請了一筆貸款來擴展餐廳生意。" }
    ]
  },
  {
    id: "w1795", english: "take out insurance", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "phr.", meaningGroups: [ ["投保","購買保險"] ] }
    ],
    examples: [
      { en:"The company took out insurance to cover any damage during shipping.", zh:"這家公司投保了保險，以理賠運送過程中可能發生的損害。" }
    ]
  },
  {
    id: "w1796", english: "trust company", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["信託公司"] ] }
    ],
    examples: [
      { en:"The estate is managed by a trust company on behalf of the family.", zh:"這筆遺產由一家信託公司代表家族管理。" }
    ]
  },
  {
    id: "w1797", english: "twofold", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["兩倍的"] ] },
      { pos: "adv", meaningGroups: [ ["兩倍地"] ] }
    ],
    examples: [
      { en:"There has been a twofold increase in loan applications this quarter.", zh:"這個季度的貸款申請量增加了兩倍。" },
      { en:"Demand for the service has grown twofold since last year.", zh:"這項服務的需求自去年以來已成長了兩倍。" }
    ]
  },
  {
    id: "w1798", english: "wire transfer", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["電匯"] ] }
    ],
    examples: [
      { en:"Payment for the overseas order will be made by wire transfer.", zh:"這筆海外訂單的款項將以電匯方式支付。" }
    ]
  },
  {
  id: "w1821", english: "accredit", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "vt", meaningGroups: [ ["認可","正式承認資格"] ] }
  ],
  examples: [
    { en:"The university has been accredited by the Ministry of Education to offer online degrees.", zh:"該大學已獲教育部認可提供線上學位課程。" }
  ]
},
  {
  id: "w1822", english: "approximation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["大略的估計","近似值"] ] }
  ],
  examples: [
    { en:"The manager gave a rough approximation of the project's total cost.", zh:"經理提供了這項專案總成本的粗略估計。" }
  ]
},
  {
  id: "w1823", english: "at one's disposal", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "phr.", meaningGroups: [ ["供某人隨意使用","任憑某人調度"] ] }
  ],
  examples: [
    { en:"The company put a car at his disposal for business trips.", zh:"公司提供一輛車供他出差時隨意使用。" }
  ]
},
  {
  id: "w1824", english: "attainable", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adj", meaningGroups: [ ["可達成的","可實現的"] ] }
  ],
  examples: [
    { en:"We need to set attainable goals for the sales team this quarter.", zh:"我們這一季需要為銷售團隊設定可達成的目標。" }
  ]
},
  {
  id: "w1825", english: "confusion", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nu", meaningGroups: [ ["混亂","困惑不清的狀態"] ] }
  ],
  examples: [
    { en:"There was some confusion among staff about the new reporting procedure.", zh:"員工們對新的報告流程感到有些困惑。" }
  ]
},
  {
  id: "w1826", english: "considerate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adj", meaningGroups: [ ["體貼的","體諒他人的"] ] }
  ],
  examples: [
    { en:"It was very considerate of you to reschedule the meeting for me.", zh:"你為我改期會議真是太體貼了。" }
  ]
},
  {
  id: "w1827", english: "consultation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["諮詢","商討會議"] ] }
  ],
  examples: [
    { en:"The new policy was drafted after consultation with several department heads.", zh:"這項新政策是在與多個部門主管商討後擬定的。" }
  ]
},
  {
  id: "w1828", english: "cutback", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["削減","縮減"] ] }
  ],
  examples: [
    { en:"The company announced further cutbacks in its marketing budget.", zh:"公司宣布進一步削減行銷預算。" }
  ]
},
  {
  id: "w1829", english: "deflate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "vt", meaningGroups: [ ["使貨幣貶值","使經濟緊縮"] ] },
    { pos: "vi", meaningGroups: [ ["物價下跌","經濟緊縮萎縮"] ] }
  ],
  examples: [
    { en:"The central bank's policy is designed to deflate an overheated economy.", zh:"央行的政策旨在讓過熱的經濟降溫緊縮。" },
    { en:"Housing prices deflated sharply after the financial crisis.", zh:"金融危機後房價大幅下跌。" }
  ]
},
  {
  id: "w1830", english: "deliberately", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adv", meaningGroups: [ ["故意地","蓄意地"] ] }
  ],
  examples: [
    { en:"He deliberately delayed the shipment to avoid extra costs.", zh:"他故意延遲出貨以避免額外成本。" }
  ]
},
  {
  id: "w1831", english: "devalue", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "vt", meaningGroups: [ ["使貨幣貶值"] ] }
  ],
  examples: [
    { en:"The government decided to devalue the currency to boost exports.", zh:"政府決定讓貨幣貶值以促進出口。" }
  ]
},
  {
  id: "w1832", english: "devastate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "vt", meaningGroups: [ ["使遭受重創","徹底破壞"] ] }
  ],
  examples: [
    { en:"The scandal devastated the company's reputation.", zh:"這場醜聞徹底摧毀了公司的名聲。" }
  ]
},
  {
  id: "w1833", english: "emergency evacuation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["緊急疏散","緊急逃生"] ] }
  ],
  examples: [
    { en:"The office conducted an emergency evacuation drill last Friday.", zh:"辦公室上週五進行了緊急疏散演習。" }
  ]
},
  {
  id: "w1834", english: "evoke", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "vt", meaningGroups: [ ["喚起","引起回憶或情感"] ] }
  ],
  examples: [
    { en:"The old photographs evoked fond memories of her childhood.", zh:"這些舊照片喚起了她對童年的美好回憶。" }
  ]
},
  {
  id: "w1835", english: "faithfully", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adv", meaningGroups: [ ["忠實地","忠誠地"] ] }
  ],
  examples: [
    { en:"He served the company faithfully for over thirty years.", zh:"他忠心耿耿地為公司服務超過三十年。" }
  ]
},
  {
  id: "w1836", english: "fictitious", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adj", meaningGroups: [ ["虛構的","假的"] ] }
  ],
  examples: [
    { en:"The report used fictitious names to protect the clients' identities.", zh:"這份報告使用虛構的姓名以保護客戶身分。" }
  ]
},
  {
  id: "w1837", english: "impair", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "vt", meaningGroups: [ ["損害","削弱功能或能力"] ] }
  ],
  examples: [
    { en:"Poor lighting can impair employees' ability to work safely.", zh:"照明不良會損害員工安全工作的能力。" }
  ]
},
  {
  id: "w1838", english: "intake", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nu", meaningGroups: [ ["攝取量","吸入量"] ] }
  ],
  examples: [
    { en:"Employees are encouraged to monitor their daily caffeine intake.", zh:"公司鼓勵員工留意每日的咖啡因攝取量。" }
  ]
},
  {
  id: "w1839", english: "in the vicinity of", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "phr.", meaningGroups: [ ["在…附近","大約"] ] }
  ],
  examples: [
    { en:"The new warehouse is located in the vicinity of the airport.", zh:"新倉庫位於機場附近。" }
  ]
},
  {
  id: "w1840", english: "leaky", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adj", meaningGroups: [ ["會漏水的","會漏氣的"] ] }
  ],
  examples: [
    { en:"The maintenance team fixed a leaky pipe in the basement.", zh:"維修團隊修好了地下室一條會漏水的管子。" }
  ]
},
  {
  id: "w1841", english: "legacy", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["從先人取得的遺產"], ["歷史遺風","前人留下的傳承"] ] }
  ],
  examples: [
    { en:"She received a small legacy from her grandfather.", zh:"她從祖父那裡繼承了一小筆遺產。" },
    { en:"The company's legacy of innovation continues to inspire new employees.", zh:"這家公司創新的傳承持續激勵著新進員工。" }
  ]
},
  {
  id: "w1842", english: "outlying", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adj", meaningGroups: [ ["偏遠的","外圍的"] ] }
  ],
  examples: [
    { en:"The courier service now covers outlying areas as well as the city center.", zh:"快遞服務現在也涵蓋偏遠地區，不只是市中心。" }
  ]
},
  {
  id: "w1843", english: "outweigh", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "vt", meaningGroups: [ ["比…更重要","超過"] ] }
  ],
  examples: [
    { en:"The benefits of the new system far outweigh its installation costs.", zh:"新系統的效益遠超過其安裝成本。" }
  ]
},
  {
  id: "w1845", english: "projected", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adj", meaningGroups: [ ["預計的","預測的"] ] }
  ],
  examples: [
    { en:"The projected revenue for next quarter looks promising.", zh:"下一季的預計營收看起來相當樂觀。" }
  ]
},
  {
  id: "w1846", english: "property line", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["地界線","產權界線"] ] }
  ],
  examples: [
    { en:"The fence was built exactly along the property line.", zh:"這道圍籬正好沿著地界線建造。" }
  ]
},
  {
  id: "w1847", english: "reexamine", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "vt", meaningGroups: [ ["重新審視","再次檢查"] ] }
  ],
  examples: [
    { en:"The board decided to reexamine the merger proposal in detail.", zh:"董事會決定重新詳細審視這項合併提案。" }
  ]
},
  {
  id: "w1848", english: "set aside", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "phr.", meaningGroups: [ ["撥出金錢或時間","保留"] ] }
  ],
  examples: [
    { en:"We should set aside part of the budget for unexpected expenses.", zh:"我們應該撥出一部分預算來應付意外支出。" }
  ]
},
  {
  id: "w1849", english: "take pride in", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "phr.", meaningGroups: [ ["以…為榮","對…感到自豪"] ] }
  ],
  examples: [
    { en:"Our staff take great pride in providing excellent customer service.", zh:"我們的員工以提供優質的客戶服務為榮。" }
  ]
},
  {
  id: "w1850", english: "tear", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "vt", meaningGroups: [ ["撕","扯破"] ] }
  ],
  examples: [
    { en:"Be careful not to tear the packaging when opening the box.", zh:"打開箱子時請小心不要撕破包裝。" }
  ]
},
  {
  id: "w1851", english: "wipe off", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "phr.", meaningGroups: [ ["擦掉","抹去"], ["使股票市值瞬間蒸發消失"] ] }
  ],
  examples: [
    { en:"A sudden market crash wiped billions off share prices worldwide.", zh:"一場突發的市場崩盤讓全球數十億元的股票市值瞬間蒸發。" }
  ]
},
  {
  id: "w1852", english: "annex", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["附屬建築","別館"] ] }
  ],
  examples: [
    { en:"The company built an annex next to the main office to house the new staff.", zh:"公司在主辦公室旁增建了一棟附屬建築以容納新員工。" }
  ]
},
  {
  id: "w1853", english: "archway", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["拱門","拱形通道"] ] }
  ],
  examples: [
    { en:"Visitors enter the exhibition hall through a grand archway.", zh:"訪客經由一座宏偉的拱門進入展覽館。" }
  ]
},
  {
  id: "w1854", english: "be mounted on", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "phr.", meaningGroups: [ ["被固定裝設於牆上或框架上"] ] }
  ],
  examples: [
    { en:"The new signage will be mounted on the wall near the entrance.", zh:"新的標示牌將被固定裝設在入口附近的牆上。" }
  ]
},
  {
  id: "w1855", english: "canopy", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["頂蓋","罩篷"] ] }
  ],
  examples: [
    { en:"A large canopy was set up over the outdoor stage in case of rain.", zh:"為防下雨，戶外舞台上方架設了一個大型頂蓋。" }
  ]
},
  {
  id: "w1856", english: "carpentry", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nu", meaningGroups: [ ["木工技術","木工手藝"] ] }
  ],
  examples: [
    { en:"He took evening classes to learn carpentry.", zh:"他上夜間課程學習木工技術。" }
  ]
},
  {
  id: "w1857", english: "cast a shadow", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "phr.", meaningGroups: [ ["為情況蒙上陰影","帶來不愉快的影響"] ] }
  ],
  examples: [
    { en:"The lawsuit cast a shadow over the company's annual meeting.", zh:"這場官司為公司的年度會議蒙上了一層陰影。" }
  ]
},
  {
  id: "w1858", english: "column", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["報刊專欄"], ["石柱","柱子"] ] }
  ],
  examples: [
    { en:"She writes a weekly business column for the local newspaper.", zh:"她為當地報紙撰寫每週的商業專欄。" },
    { en:"Marble columns line the entrance of the museum.", zh:"大理石柱排列在博物館的入口處。" }
  ]
},
  {
  id: "w1859", english: "courtyard", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["中庭","院子"] ] }
  ],
  examples: [
    { en:"Employees often eat lunch in the courtyard behind the office.", zh:"員工們常在辦公室後方的中庭吃午餐。" }
  ]
},
  {
  id: "w1860", english: "cupboard", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["碗櫃","儲物櫥"] ] }
  ],
  examples: [
    { en:"All the office supplies are kept in the cupboard by the printer.", zh:"所有的辦公用品都放在印表機旁的儲物櫥裡。" }
  ]
},
  {
  id: "w1861", english: "dedication ceremony", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["落成典禮","獻堂儀式"] ] }
  ],
  examples: [
    { en:"Hundreds of guests attended the building's dedication ceremony.", zh:"數百位賓客出席了這棟建築的落成典禮。" }
  ]
},
  {
  id: "w1862", english: "desirable", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adj", meaningGroups: [ ["令人想要的","理想的"] ] }
  ],
  examples: [
    { en:"A downtown location is considered highly desirable for retail stores.", zh:"市中心的地點被認為是零售店家非常理想的位置。" }
  ]
},
  {
  id: "w1863", english: "doorway", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["門口","門道"] ] }
  ],
  examples: [
    { en:"He stood in the doorway waiting for his appointment.", zh:"他站在門口等待他的約會。" }
  ]
},
  {
  id: "w1864", english: "dresser", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["梳妝台","衣櫃"], ["穿著特定風格的人"] ] }
  ],
  examples: [
    { en:"She keeps her jewelry in the top drawer of the dresser.", zh:"她把首飾放在梳妝台最上層的抽屜裡。" },
    { en:"He's known around the office as a sharp dresser.", zh:"他在辦公室裡以穿著講究聞名。" }
  ]
},
  {
  id: "w1865", english: "erect", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "vt", meaningGroups: [ ["建造","豎立"] ] },
    { pos: "adj", meaningGroups: [ ["直立的","挺直的"] ] }
  ],
  examples: [
    { en:"The construction crew erected scaffolding around the building.", zh:"建築工班在大樓周圍搭建了鷹架。" },
    { en:"He stood erect throughout the entire ceremony.", zh:"整場典禮他都站得筆直。" }
  ]
},
  {
  id: "w1866", english: "faucet", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["水龍頭"] ] }
  ],
  examples: [
    { en:"Please make sure the faucet is turned off before you leave.", zh:"離開前請確認水龍頭已經關好。" }
  ]
},
  {
  id: "w1867", english: "fitting room", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["試衣間"] ] }
  ],
  examples: [
    { en:"Customers can try on clothes in the fitting room near the entrance.", zh:"顧客可以在入口附近的試衣間試穿衣服。" }
  ]
},
  {
  id: "w1868", english: "fixture", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["固定裝置","固定設備"], ["固定不變的人或事物"] ] }
  ],
  examples: [
    { en:"All light fixtures will be replaced during the renovation.", zh:"所有的燈具設備在裝修期間都會被更換。" },
    { en:"After ten years, she has become a permanent fixture in this department.", zh:"十年後，她已成為這個部門裡不可或缺的常駐人物。" }
  ]
},
  {
  id: "w1869", english: "flooring", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nu", meaningGroups: [ ["地板材料"] ] }
  ],
  examples: [
    { en:"The company chose vinyl flooring for the new office due to its low cost.", zh:"公司因成本較低而為新辦公室選用了塑膠地板材料。" }
  ]
},
  {
  id: "w1871", english: "hedge", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["籬笆","綠籬"] ] },
    { pos: "vt", meaningGroups: [ ["嚴格限制"] ] },
    { pos: "vi", meaningGroups: [ ["迴避","不直接表態"] ] }
  ],
  examples: [
    { en:"A tall hedge separates the two office buildings.", zh:"一道高高的綠籬將兩棟辦公大樓隔開。" },
    { en:"When asked about the layoffs, the manager kept hedging.", zh:"被問及裁員問題時，經理一直迴避不肯明確回答。" }
  ]
},
  {
  id: "w1872", english: "insulation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nu", meaningGroups: [ ["隔熱","隔音","絕緣措施"], ["隔熱材料","絕緣材料"] ] }
  ],
  examples: [
    { en:"Better insulation can significantly reduce heating costs.", zh:"更好的隔熱設施能大幅降低取暖費用。" },
    { en:"Workers installed insulation in the roof of the warehouse.", zh:"工人們在倉庫的屋頂安裝了隔熱材料。" }
  ]
},
  {
  id: "w1873", english: "lamppost", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["路燈柱"] ] }
  ],
  examples: [
    { en:"A banner advertising the sale was tied to every lamppost on the street.", zh:"這條街上每根路燈柱都繫上了宣傳促銷的橫幅。" }
  ]
},
  {
  id: "w1874", english: "ledge", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["窄架","岩架","突出的窄台"] ] }
  ],
  examples: [
    { en:"A pigeon landed on the window ledge outside his office.", zh:"一隻鴿子降落在他辦公室外的窗台上。" }
  ]
},
  {
  id: "w1875", english: "light bulb", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["燈泡"] ] }
  ],
  examples: [
    { en:"Facilities staff replaced all the burned-out light bulbs in the hallway.", zh:"設施人員更換了走廊裡所有燒壞的燈泡。" }
  ]
},
  {
  id: "w1876", english: "locale", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["地點","場景"] ] }
  ],
  examples: [
    { en:"The filmmakers chose a coastal town as the locale for the commercial.", zh:"製片團隊選了一座海濱小鎮作為這則廣告的拍攝地點。" }
  ]
},
  {
  id: "w1877", english: "make the bed", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "phr.", meaningGroups: [ ["整理床鋪"] ] }
  ],
  examples: [
    { en:"Housekeeping staff make the bed in every room each morning.", zh:"客房清潔人員每天早上都會整理每間房的床鋪。" }
  ]
},
  {
  id: "w1878", english: "multistory", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adj", meaningGroups: [ ["多層樓的"] ] }
  ],
  examples: [
    { en:"The company parks its delivery vans in a multistory garage downtown.", zh:"公司將送貨車停放在市中心的一座多層停車場。" }
  ]
},
  {
  id: "w1879", english: "pole", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["桿","柱"], ["極","意見等的兩極端"] ] }
  ],
  examples: [
    { en:"A flag was raised on a tall pole outside the building.", zh:"建築物外的高桿上升起了一面旗子。" },
    { en:"The two managers represent opposite poles of opinion on the budget.", zh:"這兩位經理在預算問題上代表了截然相反的兩種意見。" }
  ]
},
  {
  id: "w1880", english: "porch", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["有頂門廊"] ] }
  ],
  examples: [
    { en:"Deliveries are usually left on the front porch.", zh:"送貨通常會留在前門的門廊上。" }
  ]
},
  {
  id: "w1881", english: "premises", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["房屋及土地","場所"] ] }
  ],
  examples: [
    { en:"Smoking is strictly prohibited on company premises.", zh:"公司場所內嚴禁吸菸。" }
  ]
},
  {
  id: "w1882", english: "reconfiguration", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["重新配置","調整"] ] }
  ],
  examples: [
    { en:"The reconfiguration of the office layout improved employee workflow.", zh:"辦公室配置的重新調整改善了員工的工作流程。" }
  ]
},
  {
  id: "w1883", english: "restoration", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["修復","復原"] ] }
  ],
  examples: [
    { en:"The restoration of the historic building took nearly two years.", zh:"這座歷史建築的修復工程花了將近兩年。" }
  ]
},
  {
  id: "w1884", english: "saw", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "vt", meaningGroups: [ ["用鋸子切割"] ] },
    { pos: "nc", meaningGroups: [ ["鋸子"] ] }
  ],
  examples: [
    { en:"The carpenter sawed the plank into three equal pieces.", zh:"木匠將這塊木板鋸成三段等長的部分。" },
    { en:"He used a power saw to cut through the beam.", zh:"他用電鋸切穿了這根樑木。" }
  ]
},
  {
  id: "w1886", english: "shockproof", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adj", meaningGroups: [ ["防震的","耐衝擊的"] ] }
  ],
  examples: [
    { en:"The camera comes with a shockproof case for outdoor use.", zh:"這台相機配有防震外殼，適合戶外使用。" }
  ]
},
  {
  id: "w1887", english: "staircase", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["樓梯"] ] }
  ],
  examples: [
    { en:"A wide staircase leads up to the reception area.", zh:"一座寬闊的樓梯通往接待區。" }
  ]
},
  {
  id: "w1888", english: "startle", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "vt", meaningGroups: [ ["使驚嚇","使嚇一跳"] ] }
  ],
  examples: [
    { en:"The sudden fire alarm startled everyone in the meeting room.", zh:"突然響起的火警警報把會議室裡的每個人都嚇了一跳。" }
  ]
},
  {
  id: "w1889", english: "symmetrically", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adv", meaningGroups: [ ["對稱地"] ] }
  ],
  examples: [
    { en:"The furniture was arranged symmetrically on both sides of the lobby.", zh:"家具對稱地擺放在大廳兩側。" }
  ]
},
  {
  id: "w1890", english: "tap", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["水龍頭"] ] }
  ],
  examples: [
    { en:"Turn off the tap tightly to avoid wasting water.", zh:"請把水龍頭關緊以免浪費水。" }
  ]
},
  {
  id: "w1891", english: "tear down", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "phr.", meaningGroups: [ ["拆除建築物"] ] }
  ],
  examples: [
    { en:"The city plans to tear down the old factory and build a park.", zh:"市政府計畫拆除這座舊工廠並興建一座公園。" }
  ]
},
  {
  id: "w1892", english: "uninhabited", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adj", meaningGroups: [ ["無人居住的"] ] }
  ],
  examples: [
    { en:"The company owns several uninhabited buildings on the outskirts of town.", zh:"公司在城郊擁有幾棟無人居住的建築物。" }
  ]
},
  {
  id: "w1893", english: "windowsill", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["窗台"] ] }
  ],
  examples: [
    { en:"She placed a small plant on the windowsill of her office.", zh:"她在辦公室的窗台上放了一株小盆栽。" }
  ]
},
  {
  id: "w1894", english: "woodwork", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nu", meaningGroups: [ ["建築物的木造部分"], ["木工手藝"] ] }
  ],
  examples: [
    { en:"The old woodwork around the doors needs repainting.", zh:"門邊老舊的木造部分需要重新上漆。" },
    { en:"He enjoys woodwork as a weekend hobby.", zh:"他喜歡把木工當作週末的興趣。" }
  ]
},
  {
  id: "w1895", english: "affirmative", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adj", meaningGroups: [ ["肯定的","表示同意的"] ] },
    { pos: "nc", meaningGroups: [ ["肯定的答覆","表示同意的話"] ] }
  ],
  examples: [
    { en:"She gave an affirmative response to the proposal.", zh:"她對這項提案給出了肯定的回應。" },
    { en:"He nodded in the affirmative.", zh:"他點頭表示肯定。" }
  ]
},
  {
  id: "w1896", english: "along the shore", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "phr.", meaningGroups: [ ["沿著海岸","沿著湖岸或河岸"] ] }
  ],
  examples: [
    { en:"Tourists enjoy walking along the shore at sunset.", zh:"遊客喜歡在日落時沿著海岸散步。" }
  ]
},
  {
  id: "w1897", english: "atmospheric", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adj", meaningGroups: [ ["大氣的","與空氣有關的"], ["有特殊氣氛的","神秘或浪漫的"] ] }
  ],
  examples: [
    { en:"Atmospheric pressure changes can affect flight schedules.", zh:"大氣壓力的變化可能影響航班時程。" },
    { en:"The dim lighting made the restaurant feel very atmospheric.", zh:"昏暗的燈光讓這間餐廳顯得氣氛十足。" }
  ]
},
  {
  id: "w1898", english: "body of water", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["水域"] ] }
  ],
  examples: [
    { en:"The resort is built beside a large body of water.", zh:"這間度假村建在一片大水域旁邊。" }
  ]
},
  {
  id: "w1899", english: "botanical", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adj", meaningGroups: [ ["植物學的","與植物有關的"] ] }
  ],
  examples: [
    { en:"The company sources ingredients from a botanical garden nearby.", zh:"這家公司從附近的植物園採購原料。" }
  ]
},
  {
  id: "w1900", english: "cliff", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["懸崖","峭壁"] ] }
  ],
  examples: [
    { en:"The hotel offers a stunning view of the cliff and the ocean.", zh:"這間飯店能欣賞到懸崖與海洋的絕美景色。" }
  ]
},
  {
  id: "w1901", english: "depletion", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nu", meaningGroups: [ ["耗盡","減少"] ] }
  ],
  examples: [
    { en:"The depletion of natural resources is a major concern for the industry.", zh:"自然資源的耗盡是這個產業的一大隱憂。" }
  ]
},
  {
  id: "w1902", english: "fade", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "vi", meaningGroups: [ ["褪色","逐漸消失"] ] }
  ],
  examples: [
    { en:"The colors on the billboard began to fade after months in the sun.", zh:"廣告看板上的顏色在陽光曝曬數月後開始褪色。" }
  ]
},
  {
  id: "w1903", english: "fertile", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adj", meaningGroups: [ ["肥沃的","豐產的"], ["能生育的","多產的"] ] }
  ],
  examples: [
    { en:"The region is known for its fertile farmland.", zh:"這個地區以肥沃的農地聞名。" },
    { en:"Fertile soil combined with a mild climate makes this area ideal for agriculture.", zh:"肥沃的土壤加上溫和的氣候，使這個地區非常適合農業發展。" }
  ]
},
  {
  id: "w1904", english: "fumes", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["刺鼻或有害的煙霧","廢氣"] ] }
  ],
  examples: [
    { en:"Workers wore masks to avoid inhaling toxic fumes.", zh:"工人們戴上口罩以避免吸入有毒的廢氣。" }
  ]
},
  {
  id: "w1905", english: "grazing", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nu", meaningGroups: [ ["放牧","牧草地"] ] }
  ],
  examples: [
    { en:"The farm reserves several acres for cattle grazing.", zh:"這座農場保留了好幾英畝的土地供牛群放牧。" }
  ]
},
  {
  id: "w1906", english: "hail", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nu", meaningGroups: [ ["冰雹"] ] },
    { pos: "vi", meaningGroups: [ ["下冰雹"] ] }
  ],
  examples: [
    { en:"Hail damaged several cars in the parking lot.", zh:"冰雹損壞了停車場裡好幾輛車。" },
    { en:"It hailed heavily during the outdoor event.", zh:"戶外活動期間下起了猛烈的冰雹。" }
  ]
},
  {
  id: "w1907", english: "inclement", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adj", meaningGroups: [ ["天氣惡劣的"] ] }
  ],
  examples: [
    { en:"The outdoor ceremony was postponed due to inclement weather.", zh:"由於天氣惡劣，戶外典禮被延期了。" }
  ]
},
  {
  id: "w1908", english: "irrigation system", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["灌溉系統"] ] }
  ],
  examples: [
    { en:"The farm installed a new irrigation system to save water.", zh:"這座農場安裝了新的灌溉系統以節省用水。" }
  ]
},
  {
  id: "w1909", english: "lakefront", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["湖濱地區"] ] }
  ],
  examples: [
    { en:"The company built its new headquarters on the lakefront.", zh:"這家公司把新總部建在湖濱地區。" }
  ]
},
  {
  id: "w1910", english: "logging", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nu", meaningGroups: [ ["伐木業"] ] }
  ],
  examples: [
    { en:"Logging has significantly reduced the forest area in the region.", zh:"伐木業已大幅減少了這個地區的森林面積。" }
  ]
},
  {
  id: "w1911", english: "mining", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nu", meaningGroups: [ ["採礦業"] ] }
  ],
  examples: [
    { en:"The country's economy relies heavily on the mining industry.", zh:"這個國家的經濟高度依賴採礦業。" }
  ]
},
  {
  id: "w1912", english: "mow the lawn", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "phr.", meaningGroups: [ ["割草","修剪草坪"] ] }
  ],
  examples: [
    { en:"The maintenance crew mows the lawn every Friday morning.", zh:"維護團隊每週五早上都會修剪草坪。" }
  ]
},
  {
  id: "w1913", english: "natural habitat", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["自然棲息地"] ] }
  ],
  examples: [
    { en:"Deforestation is destroying the natural habitat of many species.", zh:"濫伐森林正在破壞許多物種的自然棲息地。" }
  ]
},
  {
  id: "w1914", english: "nightfall", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nu", meaningGroups: [ ["黃昏","入夜時分"] ] }
  ],
  examples: [
    { en:"The search team hoped to find the missing hikers before nightfall.", zh:"搜救團隊希望能在入夜前找到失蹤的登山客。" }
  ]
},
  {
  id: "w1915", english: "nourishment", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nu", meaningGroups: [ ["營養","滋養"] ] }
  ],
  examples: [
    { en:"The soil provides essential nourishment for the crops.", zh:"這片土壤提供了作物所需的重要養分。" }
  ]
},
  {
  id: "w1916", english: "nurture", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "vt", meaningGroups: [ ["養育","照顧尤指兒童或植物"], ["培育","扶植計畫或人才"] ] }
  ],
  examples: [
    { en:"She wants to stay home to nurture her children.", zh:"她想待在家裡養育照顧她的孩子。" },
    { en:"Good managers nurture the talent within their teams.", zh:"優秀的主管會培育團隊內部的人才。" }
  ]
},
  {
  id: "w1917", english: "off the shore", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "phr.", meaningGroups: [ ["離岸不遠處的海面上"] ] }
  ],
  examples: [
    { en:"The cargo ship anchored just off the shore overnight.", zh:"這艘貨輪整夜停泊在離岸不遠的海面上。" }
  ]
},
  {
  id: "w1918", english: "outskirts", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["城鎮的郊區","外圍"] ] }
  ],
  examples: [
    { en:"The new distribution center is located on the outskirts of the city.", zh:"新的物流中心位於這座城市的郊區。" }
  ]
},
  {
  id: "w1919", english: "outwardly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adv", meaningGroups: [ ["表面上","外表上看來"] ] }
  ],
  examples: [
    { en:"Outwardly, the merger seemed to proceed smoothly.", zh:"表面上看來，這次併購進行得相當順利。" }
  ]
},
  {
  id: "w1920", english: "overflow", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "vi", meaningGroups: [ ["溢出","滿出來"] ] }
  ],
  examples: [
    { en:"The conference hall overflowed with attendees eager to hear the keynote.", zh:"會議廳裡擠滿了熱切想聽主題演講的與會者，幾乎座無虛席。" }
  ]
},
  {
  id: "w1921", english: "potted plant", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["盆栽植物"] ] }
  ],
  examples: [
    { en:"Several potted plants decorate the reception area.", zh:"接待區擺放了好幾株盆栽植物作裝飾。" }
  ]
},
  {
  id: "w1922", english: "precipitation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nu", meaningGroups: [ ["降水","雨或雪等"] ] }
  ],
  examples: [
    { en:"Heavy precipitation is expected to delay the outdoor shipment schedule.", zh:"預計將有大量降雨，這會延誤戶外的出貨時程。" }
  ]
},
  {
  id: "w1923", english: "promptness", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nu", meaningGroups: [ ["迅速","準時"] ] }
  ],
  examples: [
    { en:"The client praised the company's promptness in handling the complaint.", zh:"客戶讚賞這家公司處理投訴時的迅速效率。" }
  ]
},
  {
  id: "w1924", english: "react to", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "phr.", meaningGroups: [ ["對…做出反應"] ] }
  ],
  examples: [
    { en:"Investors reacted quickly to the company's earnings report.", zh:"投資人對這家公司的財報迅速做出反應。" }
  ]
},
  {
  id: "w1925", english: "residue", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["殘留物","剩餘物"], ["付清債務稅款後的遺產餘額"] ] }
  ],
  examples: [
    { en:"A sticky residue remained on the machine after cleaning.", zh:"清潔過後機器上仍留有一層黏稠的殘留物。" },
    { en:"The residue of the estate went to her granddaughter.", zh:"這筆遺產的餘額歸給了她的孫女。" }
  ]
},
  {
  id: "w1926", english: "revert", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "vi", meaningGroups: [ ["恢復","回到原狀或原話題"] ] }
  ],
  examples: [
    { en:"If payment is not received, ownership will revert to the original seller.", zh:"若未收到款項，所有權將恢復歸還原賣方。" }
  ]
},
  {
  id: "w1927", english: "revolve", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "vi", meaningGroups: [ ["繞著轉","圍繞旋轉"] ] }
  ],
  examples: [
    { en:"The entire discussion revolved around the budget cuts.", zh:"整場討論都圍繞著預算削減這個議題。" }
  ]
},
  {
  id: "w1928", english: "rugged", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adj", meaningGroups: [ ["崎嶇不平的"], ["粗獷強壯的","結實耐用的"] ] }
  ],
  examples: [
    { en:"The delivery truck is built to handle rugged terrain.", zh:"這輛送貨卡車專為應付崎嶇的地形而打造。" },
    { en:"Jeeps are rugged vehicles, designed for rough conditions.", zh:"吉普車是結實耐用的車輛，專為惡劣路況設計。" }
  ]
},
  {
  id: "w1929", english: "scenery", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nu", meaningGroups: [ ["自然風景","景色"] ] }
  ],
  examples: [
    { en:"Employees on the retreat admired the mountain scenery.", zh:"參加靜修活動的員工們讚嘆著山區的美麗風景。" }
  ]
},
  {
  id: "w1930", english: "scenic", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adj", meaningGroups: [ ["風景優美的"] ] }
  ],
  examples: [
    { en:"The company chose a scenic location for its annual retreat.", zh:"公司為年度靜修活動選了一處風景優美的地點。" }
  ]
},
  {
  id: "w1931", english: "sewage", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nu", meaningGroups: [ ["汙水","下水道廢水"] ] }
  ],
  examples: [
    { en:"The factory was fined for dumping untreated sewage into the river.", zh:"這家工廠因將未經處理的汙水排入河中而遭罰款。" }
  ]
},
  {
  id: "w1932", english: "sheer", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adj", meaningGroups: [ ["完全的","十足的"], ["極陡峭的","近乎垂直的"], ["布料輕薄透明的"] ] }
  ],
  examples: [
    { en:"Her success was due to sheer determination.", zh:"她的成功完全歸功於十足的決心。" },
    { en:"The trail runs along a sheer cliff edge.", zh:"這條步道沿著近乎垂直的懸崖邊緣延伸。" }
  ]
},
  {
  id: "w1933", english: "shrub", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["灌木","矮樹叢"] ] }
  ],
  examples: [
    { en:"Landscapers planted shrubs along the entrance walkway.", zh:"園藝人員在入口步道兩側種植了灌木。" }
  ]
},
  {
  id: "w1934", english: "slope", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["斜面","斜坡"] ] }
  ],
  examples: [
    { en:"The warehouse ramp has a gentle slope for easy loading.", zh:"倉庫的坡道斜度平緩，方便裝卸貨物。" }
  ]
},
  {
  id: "w1935", english: "splendor", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nu", meaningGroups: [ ["壯麗","光輝"] ] }
  ],
  examples: [
    { en:"The restored building was returned to its original splendor.", zh:"這棟修復後的建築恢復了原有的壯麗風貌。" }
  ]
},
  {
  id: "w1936", english: "stream", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["小溪","水流"] ] },
    { pos: "vi", meaningGroups: [ ["源源不斷地流出","湧入"] ] }
  ],
  examples: [
    { en:"A small stream runs behind the office park.", zh:"一條小溪流經辦公園區的後方。" },
    { en:"Customers streamed into the store during the sale.", zh:"促銷期間顧客源源不絕地湧入商店。" }
  ]
},
  {
  id: "w1937", english: "sustainable", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adj", meaningGroups: [ ["可持續的","能維持下去的","永續的"] ] }
  ],
  examples: [
    { en:"The firm is investing heavily in sustainable packaging solutions.", zh:"這家公司正大力投資永續包裝解決方案。" }
  ]
},
  {
  id: "w1938", english: "sweep", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "vt", meaningGroups: [ ["打掃","清掃"] ] },
    { pos: "vi", meaningGroups: [ ["快速蔓延","席捲"] ] },
    { pos: "nc", meaningGroups: [ ["迅速有力的動作","橫掃"] ] }
  ],
  examples: [
    { en:"Staff sweep the warehouse floor at the end of every shift.", zh:"員工在每個班次結束時都會清掃倉庫地板。" },
    { en:"A wave of layoffs swept through the industry last year.", zh:"去年一波裁員潮席捲了整個產業。" },
    { en:"With one sweep of her hand, she cleared the papers off the desk.", zh:"她一揮手就把桌上的文件掃到一邊。" }
  ]
},
  {
  id: "w1939", english: "tangible", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adj", meaningGroups: [ ["實際的","有形的","可具體感受到的"] ] }
  ],
  examples: [
    { en:"The training program produced tangible improvements in productivity.", zh:"這項培訓計畫帶來了實際可見的生產力提升。" }
  ]
},
  {
  id: "w1940", english: "terrestrial", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adj", meaningGroups: [ ["陸地的","陸生的"], ["地面廣播的","非衛星的"] ] }
  ],
  examples: [
    { en:"Terrestrial predators typically have four clawed limbs.", zh:"陸生的捕食動物通常有四隻帶爪的肢體。" },
    { en:"Terrestrial broadcasting was replaced by satellite technology in many regions.", zh:"許多地區的地面廣播已被衛星技術取代。" }
  ]
},
  {
  id: "w1941", english: "toxication", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nu", meaningGroups: [ ["中毒","毒化作用"] ] }
  ],
  examples: [
    { en:"The report examined how toxication occurs during drug metabolism.", zh:"這份報告探討了藥物代謝過程中毒化作用是如何發生的。" }
  ]
},
  {
  id: "w1942", english: "trimming", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["邊緣的裝飾物","鑲邊"] ] }
  ],
  examples: [
    { en:"She asked for a plain jacket with no fancy trimmings.", zh:"她要求一件沒有繁複裝飾鑲邊的簡單外套。" }
  ]
},
  {
  id: "w1943", english: "trunk", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["樹的主幹","血管或神經的主幹"] ] }
  ],
  examples: [
    { en:"The old oak's trunk was over a meter wide.", zh:"這棵老橡樹的樹幹寬度超過一公尺。" }
  ]
},
  {
  id: "w1944", english: "twilight", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nu", meaningGroups: [ ["黃昏","傍晚時分"] ] },
    { pos: "adj", meaningGroups: [ ["邊緣的","半明半暗的","近乎非法的"] ] }
  ],
  examples: [
    { en:"The delivery arrived just before twilight.", zh:"貨物在黃昏前不久送達。" },
    { en:"He drifted into the twilight world of underground trading.", zh:"他逐漸涉入地下交易那個灰色邊緣的世界。" }
  ]
},
  {
  id: "w1945", english: "acute", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adj", meaningGroups: [ ["嚴重的","劇烈的"], ["敏銳的"] ] }
  ],
  examples: [
    { en:"The company is facing an acute shortage of skilled workers.", zh:"這家公司正面臨嚴重的技術人力短缺問題。" },
    { en:"She has an acute sense of judgment when it comes to negotiations.", zh:"她在談判方面有著非常敏銳的判斷力。" }
  ]
},
  {
  id: "w1946", english: "ailment", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["疾病","小毛病"] ] }
  ],
  examples: [
    { en:"The clinic mainly treats minor ailments such as colds and headaches.", zh:"這間診所主要治療感冒、頭痛等小毛病。" }
  ]
},
  {
  id: "w1947", english: "ankle sprain", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["腳踝扭傷"] ] }
  ],
  examples: [
    { en:"He continued the match despite suffering an ankle sprain.", zh:"儘管腳踝扭傷，他仍堅持完成比賽。" }
  ]
},
  {
  id: "w1948", english: "asthma", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nu", meaningGroups: [ ["氣喘","哮喘"] ] }
  ],
  examples: [
    { en:"Her asthma tends to worsen in dusty environments.", zh:"她的氣喘在多塵的環境中往往會加重。" }
  ]
},
  {
  id: "w1949", english: "be on medication", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "phr.", meaningGroups: [ ["服藥中","正在服用藥物治療"] ] }
  ],
  examples: [
    { en:"He has been on medication for his high blood pressure for years.", zh:"他多年來一直服藥治療高血壓。" }
  ]
},
  {
  id: "w1950", english: "blurry", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adj", meaningGroups: [ ["模糊不清的"] ] }
  ],
  examples: [
    { en:"The security footage was too blurry to identify the suspect.", zh:"監視器畫面太模糊，無法辨識嫌疑人。" }
  ]
},
  {
  id: "w1951", english: "deter", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "vt", meaningGroups: [ ["阻止","使不敢做"] ] }
  ],
  examples: [
    { en:"Strict penalties are meant to deter employees from violating safety rules.", zh:"嚴厲的處罰旨在阻止員工違反安全規定。" }
  ]
},
  {
  id: "w1952", english: "epidemic", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["流行病","氾濫蔓延的現象"] ] },
    { pos: "adj", meaningGroups: [ ["流行的","猖獗的"] ] }
  ],
  examples: [
    { en:"The city struggled to contain a flu epidemic last winter.", zh:"這座城市去年冬天努力控制一場流感疫情。" },
    { en:"Corruption is epidemic in certain industries.", zh:"貪腐在某些產業中相當猖獗。" }
  ]
},
  {
  id: "w1953", english: "eradicate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "vt", meaningGroups: [ ["徹底消滅","根除"] ] }
  ],
  examples: [
    { en:"The company launched a program to eradicate workplace discrimination.", zh:"這家公司推出了一項根除職場歧視的計畫。" }
  ]
},
  {
  id: "w1954", english: "exhale", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "vi", meaningGroups: [ ["呼氣","吐氣"] ] }
  ],
  examples: [
    { en:"She took a deep breath and exhaled slowly before the presentation.", zh:"上台簡報前，她深吸一口氣後緩緩吐出。" }
  ]
},
  {
  id: "w1955", english: "first aid", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nu", meaningGroups: [ ["急救"] ] }
  ],
  examples: [
    { en:"All employees are required to complete a first aid training course.", zh:"所有員工都必須完成急救訓練課程。" }
  ]
},
  {
  id: "w1956", english: "heart attack", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["心臟病發作"] ] }
  ],
  examples: [
    { en:"He suffered a mild heart attack during the business trip.", zh:"他在出差期間輕微心臟病發作。" }
  ]
},
  {
  id: "w1957", english: "hiccup", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["打嗝"] ] },
    { pos: "vi", meaningGroups: [ ["打嗝"] ] }
  ],
  examples: [
    { en:"She couldn't stop hiccupping during the interview.", zh:"她在面試過程中一直打嗝停不下來。" }
  ]
},
  {
  id: "w1958", english: "inhale", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "vi", meaningGroups: [ ["吸入","吸氣"] ] },
    { pos: "vt", meaningGroups: [ ["狼吞虎嚥地吃"] ] }
  ],
  examples: [
    { en:"Workers must wear masks to avoid inhaling harmful chemicals.", zh:"工人必須戴口罩以避免吸入有害化學物質。" },
    { en:"He inhaled his lunch in five minutes before the meeting.", zh:"開會前他五分鐘內就把午餐狼吞虎嚥吃完了。" }
  ]
},
  {
  id: "w1959", english: "insomnia", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nu", meaningGroups: [ ["失眠症"] ] }
  ],
  examples: [
    { en:"Stress at work has caused her insomnia for weeks.", zh:"工作壓力讓她這幾週一直失眠。" }
  ]
},
  {
  id: "w1960", english: "intuitively", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adv", meaningGroups: [ ["憑直覺地"] ] }
  ],
  examples: [
    { en:"She intuitively understood what the client wanted without much explanation.", zh:"她憑直覺就明白了客戶想要的東西，不需要太多解釋。" }
  ]
},
  {
  id: "w1961", english: "lean back", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "phr.", meaningGroups: [ ["向後靠","向後傾斜"] ] }
  ],
  examples: [
    { en:"He leaned back in his chair while reviewing the contract.", zh:"他審閱合約時向後靠在椅子上。" }
  ]
},
  {
  id: "w1962", english: "life expectancy", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nu", meaningGroups: [ ["預期壽命"] ] }
  ],
  examples: [
    { en:"Improved healthcare has increased average life expectancy in the region.", zh:"醫療保健的改善提高了這個地區的平均預期壽命。" }
  ]
},
  {
  id: "w1963", english: "lifespan", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["壽命","使用年限"] ] }
  ],
  examples: [
    { en:"The lifespan of this equipment is estimated at about ten years.", zh:"這項設備的使用年限估計約為十年。" }
  ]
},
  {
  id: "w1964", english: "maternity ward", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["產科病房"] ] }
  ],
  examples: [
    { en:"The hospital recently renovated its maternity ward.", zh:"這家醫院最近整修了產科病房。" }
  ]
},
  {
  id: "w1965", english: "medicinal", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adj", meaningGroups: [ ["藥用的","有療效的"] ] }
  ],
  examples: [
    { en:"The plant is valued for its medicinal properties.", zh:"這種植物因其藥用價值而受到重視。" }
  ]
},
  {
  id: "w1966", english: "outpatient clinic", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["門診部","門診診所"] ] }
  ],
  examples: [
    { en:"The outpatient clinic offers consultations without an overnight stay.", zh:"這間門診診所提供不需住院的諮詢服務。" }
  ]
},
  {
  id: "w1967", english: "over the counter", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "phr.", meaningGroups: [ ["無需處方即可購買的","非處方的"] ] }
  ],
  examples: [
    { en:"You can buy most pain relievers over the counter.", zh:"大多數止痛藥都可以在藥局無需處方直接購買。" }
  ]
},
  {
  id: "w1968", english: "palpitation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["心悸"] ] }
  ],
  examples: [
    { en:"He went to the hospital after experiencing severe palpitations.", zh:"他因劇烈心悸而前往醫院就診。" }
  ]
},
  {
  id: "w1969", english: "paralysis", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nu", meaningGroups: [ ["麻痺","癱瘓"] ] }
  ],
  examples: [
    { en:"The accident left him with partial paralysis in his left leg.", zh:"這場意外讓他的左腿部分癱瘓。" }
  ]
},
  {
  id: "w1970", english: "perspire", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "vi", meaningGroups: [ ["流汗","出汗"] ] }
  ],
  examples: [
    { en:"Workers began to perspire heavily in the summer heat.", zh:"工人們在夏日的酷熱中開始大量流汗。" }
  ]
},
  {
  id: "w1971", english: "plausible", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adj", meaningGroups: [ ["似乎可信的","言之有理的"] ] }
  ],
  examples: [
    { en:"The manager gave a plausible explanation for the delay.", zh:"經理針對延誤提出了一個似乎相當合理的解釋。" }
  ]
},
  {
  id: "w1972", english: "practitioner", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["執業人員","尤指醫療專業人士"] ] }
  ],
  examples: [
    { en:"She was a medical practitioner before joining the pharmaceutical company.", zh:"她在加入這家製藥公司之前是一名執業醫師。" }
  ]
},
  {
  id: "w1973", english: "prolonged", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adj", meaningGroups: [ ["持續很久的","長期的"] ] }
  ],
  examples: [
    { en:"Prolonged exposure to loud noise can damage hearing.", zh:"長期暴露於巨大噪音之下可能損害聽力。" }
  ]
},
  {
  id: "w1974", english: "pulse", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["脈搏"] ] }
  ],
  examples: [
    { en:"The nurse checked the patient's pulse before the procedure.", zh:"護士在進行手術前先檢查了病患的脈搏。" }
  ]
},
  {
  id: "w1976", english: "recuperate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "vi", meaningGroups: [ ["康復","恢復健康"] ] }
  ],
  examples: [
    { en:"He is recuperating at home after the surgery.", zh:"他手術後正在家中休養康復。" }
  ]
},
  {
  id: "w1977", english: "recurring", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adj", meaningGroups: [ ["反覆發生的","週期性的"] ] }
  ],
  examples: [
    { en:"The accounting software automatically tracks recurring expenses.", zh:"這套會計軟體會自動追蹤週期性發生的費用。" }
  ]
},
  {
  id: "w1978", english: "resemble", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "vt", meaningGroups: [ ["與…相似","像"] ] }
  ],
  examples: [
    { en:"The new prototype closely resembles the original design.", zh:"這款新原型與原始設計非常相似。" }
  ]
},
  {
  id: "w1979", english: "respiratory system", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["呼吸系統"] ] }
  ],
  examples: [
    { en:"Poor air quality can harm the respiratory system.", zh:"空氣品質不佳可能損害呼吸系統。" }
  ]
},
  {
  id: "w1980", english: "respire", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "vi", meaningGroups: [ ["呼吸"] ] }
  ],
  examples: [
    { en:"Fish respire through their gills rather than lungs.", zh:"魚類透過鰓而非肺部來呼吸。" }
  ]
},
  {
  id: "w1981", english: "sterilize", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "vt", meaningGroups: [ ["消毒","殺菌"], ["使絕育","結紮"] ] }
  ],
  examples: [
    { en:"All surgical instruments must be sterilized before use.", zh:"所有手術器械在使用前都必須先消毒。" },
    { en:"After having five children, she decided to be sterilized.", zh:"生了五個孩子後，她決定接受結紮手術。" }
  ]
},
  {
  id: "w1982", english: "terminal", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "adj", meaningGroups: [ ["末期的","無法治癒的"] ] },
    { pos: "nc", meaningGroups: [ ["航廈","終點站"] ] }
  ],
  examples: [
    { en:"The patient was diagnosed with a terminal illness.", zh:"這名病患被診斷出患有末期疾病。" },
    { en:"International flights depart from Terminal 2.", zh:"國際航班從第二航廈起飛。" }
  ]
},
  {
  id: "w1983", english: "vaccination", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["疫苗接種"] ] }
  ],
  examples: [
    { en:"The company offered free flu vaccinations to all employees.", zh:"公司為所有員工提供免費的流感疫苗接種。" }
  ]
},
  {
  id: "w1984", english: "vocation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
  posGroups: [
    { pos: "nc", meaningGroups: [ ["天職","志業"] ] }
  ],
  examples: [
    { en:"Teaching is more than a job to her; it's a vocation.", zh:"對她來說，教書不僅是一份工作，更是一種天職。" }
  ]
},
  { id: "w2009", english: "abolish", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["廢除","廢止"] ] } ],
    examples: [ { en:"The city council voted to abolish the outdated parking regulation.", zh:"市議會投票決定廢除這項過時的停車規定。" } ] },
  { id: "w2010", english: "abstract", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["抽象的"] ] } ],
    examples: [ { en:"The professor's lecture on abstract economic theories confused many students.", zh:"教授關於抽象經濟理論的講座讓許多學生感到困惑。" } ] },
  { id: "w2011", english: "accomplished", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["熟練的","有才藝的"] ] } ],
    examples: [ { en:"She is an accomplished negotiator who rarely loses a deal.", zh:"她是一位熟練的談判高手，很少在交易中失利。" } ] },
  { id: "w2012", english: "accountable for", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["對…負有責任的"] ] } ],
    examples: [ { en:"Each department manager is accountable for the budget assigned to their team.", zh:"每位部門經理都要對分配給其團隊的預算負責。" } ] },
  { id: "w2013", english: "acquaint someone with something", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["使…熟悉","使…認識"] ] } ],
    examples: [ { en:"The orientation session is designed to acquaint new hires with company procedures.", zh:"這場新人訓練是為了讓新員工熟悉公司流程。" } ] },
  { id: "w2014", english: "adhere to", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["遵守","堅持"] ] } ],
    examples: [ { en:"All contractors must adhere to the safety guidelines on site.", zh:"所有承包商都必須遵守現場的安全規範。" } ] },
  { id: "w2015", english: "advisable", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["明智的","可取的"] ] } ],
    examples: [ { en:"It is advisable to back up your files before updating the software.", zh:"在更新軟體之前先備份檔案是明智的做法。" } ] },
  { id: "w2016", english: "after all", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["畢竟","終究"] ] } ],
    examples: [ { en:"The client decided to sign the contract after all, despite earlier concerns about the price.", zh:"儘管先前對價格有疑慮，客戶畢竟還是決定簽下合約。" } ] },
  { id: "w2017", english: "aim", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["打算","意圖"] ] }, { pos: "nc", meaningGroups: [ ["目標","目的"] ] } ],
    examples: [ { en:"The new marketing campaign aims to attract younger customers.", zh:"這項新的行銷活動旨在吸引年輕客群。" }, { en:"The primary aim of the meeting is to finalize next quarter's budget.", zh:"這次會議的主要目標是敲定下一季的預算。" } ] },
  { id: "w2018", english: "apprehensive", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["擔憂的","不安的"] ] } ],
    examples: [ { en:"Many employees felt apprehensive about the upcoming restructuring.", zh:"許多員工對即將進行的組織重組感到不安。" } ] },
  { id: "w2019", english: "aptitude", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["天賦","資質"] ] } ],
    examples: [ { en:"The recruiter looks for candidates with a strong aptitude for problem-solving.", zh:"招募人員在尋找具有強大解決問題天賦的候選人。" } ] },
  { id: "w2020", english: "array", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["一系列","一批(令人讚嘆的事物)"] ] } ],
    examples: [ { en:"The trade show featured an impressive array of the latest office technology.", zh:"這場貿易展展示了一系列令人驚嘆的最新辦公科技產品。" } ] },
  { id: "w2021", english: "as it is", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["已經如此","照現況來看"] ] } ],
    examples: [ { en:"We can't take on any new clients — our team is fully booked as it is.", zh:"我們無法再接新客戶了，我們團隊現在已經滿檔了。" } ] },
  { id: "w2022", english: "bend over", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["彎腰","俯身"] ] } ],
    examples: [ { en:"He had to bend over to pick up the documents that had fallen under the desk.", zh:"他必須彎腰去拿掉到桌子底下的文件。" } ] },
  { id: "w2023", english: "briefcase", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["公事包","手提箱"] ] } ],
    examples: [ { en:"She always carries her laptop and files in a leather briefcase.", zh:"她總是用一個皮製公事包裝她的筆電和文件。" } ] },
  { id: "w2024", english: "brisk", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["熱絡的","快速且有活力的"] ] } ],
    examples: [ { en:"Sales have been brisk since the company launched its online store.", zh:"自公司推出線上商店以來，銷售一直十分熱絡。" } ] },
  { id: "w2025", english: "by means of", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["藉由","透過…的方式"] ] } ],
    examples: [ { en:"The warehouse tracks inventory by means of a barcode scanning system.", zh:"倉庫透過條碼掃描系統來追蹤庫存。" } ] },
  { id: "w2026", english: "care for", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["愛慕","對…有好感(帶戀愛意味)"] ] } ],
    examples: [ { en:"It took him months to admit that he cared for his colleague.", zh:"他花了好幾個月才承認自己對那位同事有好感。" } ] },
  { id: "w2027", english: "cast", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["投擲","拋出(釣魚線等)"] ] } ],
    examples: [ { en:"The angler cast his line into the calm lake.", zh:"那位釣客把釣線拋向平靜的湖面。" } ] },
  { id: "w2028", english: "conceal", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["隱藏","掩飾"] ] } ],
    examples: [ { en:"The company was accused of concealing financial losses from its investors.", zh:"該公司被指控向投資人隱瞞財務虧損。" } ] },
  { id: "w2029", english: "concrete", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["具體的","確實的"] ] }, { pos: "nu", meaningGroups: [ ["混凝土"] ] } ],
    examples: [ { en:"The board wants a concrete plan before approving any new funding.", zh:"董事會希望在核准任何新資金前先看到具體的計畫。" }, { en:"The new warehouse floor is made of reinforced concrete.", zh:"新倉庫的地板是用鋼筋混凝土建造的。" } ] },
  { id: "w2030", english: "defy", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["違抗","不顧","挑戰"] ] } ],
    examples: [ { en:"The report defies conventional wisdom about how remote work affects productivity.", zh:"這份報告挑戰了關於遠距工作如何影響生產力的傳統看法。" } ] },
  { id: "w2031", english: "defy description", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["難以形容","無法形容"] ] } ],
    examples: [ { en:"The chaos in the shipping department after the system crash defied description.", zh:"系統當機後貨運部門的混亂景象簡直難以形容。" } ] },
  { id: "w2032", english: "disregard", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["忽視","不理會"] ] }, { pos: "nu", meaningGroups: [ ["漠視","不顧"] ] } ],
    examples: [ { en:"Management should not disregard employees' feedback on the new policy.", zh:"管理層不應忽視員工對新政策的意見。" }, { en:"His complete disregard for the deadline frustrated the entire team.", zh:"他完全不顧截止日期的態度讓整個團隊感到很沮喪。" } ] },
  { id: "w2033", english: "do one's utmost", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["竭盡全力"] ] } ],
    examples: [ { en:"The customer service team did its utmost to resolve the complaint quickly.", zh:"客服團隊竭盡全力盡快解決這起投訴。" } ] },
  { id: "w2034", english: "drastic", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["激烈的","極端的"] ] } ],
    examples: [ { en:"The company took drastic measures to cut costs after two years of losses.", zh:"公司在連續兩年虧損後採取了激烈的削減成本措施。" } ] },
  { id: "w2035", english: "fairly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["相當地","還算"] ] } ],
    examples: [ { en:"The proposal was fairly well received by the board of directors.", zh:"這項提案獲得董事會相當不錯的評價。" } ] },
  { id: "w2036", english: "favorably", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["正面地","順利地"] ] } ],
    examples: [ { en:"Investors reacted favorably to the company's quarterly earnings report.", zh:"投資人對該公司的季度財報反應正面。" } ] },
  { id: "w2038", english: "implication", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["暗示","含意"], ["(對未來的)影響","衝擊"] ] } ],
    examples: [ { en:"By implication, the memo criticized the entire finance department.", zh:"這份備忘錄暗指整個財務部門都有問題。" }, { en:"The new tariff has serious implications for small importers.", zh:"這項新關稅對小型進口商有嚴重的影響。" } ] },
  { id: "w2039", english: "improvise", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["臨時編造","即興創作"] ] } ],
    examples: [ { en:"When the projector failed, the presenter had to improvise her entire pitch.", zh:"投影機故障時，簡報者必須臨時即興完成整個提案。" } ] },
  { id: "w2040", english: "in compliance with", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["遵照","符合(規定)"] ] } ],
    examples: [ { en:"The factory upgraded its equipment in compliance with new safety regulations.", zh:"工廠為了符合新的安全規定而升級了設備。" } ] },
  { id: "w2041", english: "in total", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["總共"] ] } ],
    examples: [ { en:"In total, the merger will affect more than 300 employees.", zh:"這次合併總共將影響超過三百名員工。" } ] },
  { id: "w2042", english: "in use", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["正在使用中"] ] } ],
    examples: [ { en:"The conference room on the third floor is currently in use.", zh:"三樓的會議室目前正在使用中。" } ] },
  { id: "w2043", english: "keypad", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["鍵盤","按鍵盤"] ] } ],
    examples: [ { en:"Enter your access code on the keypad to unlock the office door.", zh:"在鍵盤上輸入你的通行碼以解鎖辦公室的門。" } ] },
  { id: "w2044", english: "lightly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["輕輕地"], ["(烹調)簡單地","稍微地"] ] } ],
    examples: [ { en:"She tapped lightly on the manager's door before entering.", zh:"她進去前先輕輕地敲了經理的門。" }, { en:"The chicken should be lightly seasoned before grilling.", zh:"雞肉在烤之前應該稍微調味一下。" } ] },
  { id: "w2045", english: "log on", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["登入"] ] } ],
    examples: [ { en:"Employees must log on with a secure password before accessing the database.", zh:"員工必須用安全密碼登入才能存取資料庫。" } ] },
  { id: "w2046", english: "mandate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["正式規定","授權"] ] }, { pos: "nc", meaningGroups: [ ["授權","委任"] ] } ],
    examples: [ { en:"The new law mandates that all restaurants display calorie information.", zh:"新法規定所有餐廳都必須標示卡路里資訊。" }, { en:"The committee was given a clear mandate to reform the pension system.", zh:"該委員會獲得明確的授權去改革退休金制度。" } ] },
  { id: "w2047", english: "mastermind", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["策劃者","幕後主謀"] ] }, { pos: "vt", meaningGroups: [ ["策劃","主導"] ] } ],
    examples: [ { en:"She was the mastermind behind the company's successful rebranding campaign.", zh:"她是這家公司成功品牌重塑活動背後的策劃者。" }, { en:"He masterminded the merger that doubled the firm's market share.", zh:"他策劃了這次讓公司市佔率翻倍的合併案。" } ] },
  { id: "w2048", english: "mounting", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["逐漸增加的"] ] } ],
    examples: [ { en:"Executives are under mounting pressure to boost quarterly profits.", zh:"高層主管正面臨越來越大的壓力，要提升季度利潤。" } ] },
  { id: "w2049", english: "on the wane", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["逐漸衰退","式微"] ] } ],
    examples: [ { en:"Demand for printed catalogs has been on the wane for years.", zh:"印刷型錄的需求多年來一直在逐漸衰退。" } ] },
  { id: "w2050", english: "paper jam", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["(印表機)夾紙","卡紙"] ] } ],
    examples: [ { en:"The office printer keeps having a paper jam every time we try to print in bulk.", zh:"每次我們嘗試大量列印時，辦公室印表機就會卡紙。" } ] },
  { id: "w2051", english: "shelf", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["架子","擱板"] ] } ],
    examples: [ { en:"Please restock the shelf with the new product samples.", zh:"請把新產品樣品補上架子。" } ] },
  { id: "w2052", english: "shovel", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["鏟子"] ] }, { pos: "vt", meaningGroups: [ ["用鏟子鏟"] ] } ],
    examples: [ { en:"The maintenance crew grabbed a shovel to clear the snow from the entrance.", zh:"維修人員拿了一把鏟子去清除入口的積雪。" }, { en:"Workers had to shovel gravel onto the delivery truck by hand.", zh:"工人必須用手把碎石鏟到貨車上。" } ] },
  { id: "w2053", english: "showing", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["(作品的)展示","(表現的)呈現"] ] } ],
    examples: [ { en:"The gallery organized a special showing of the artist's latest collection.", zh:"畫廊為這位藝術家的最新作品系列舉辦了一場特別展示。" } ] },
  { id: "w2054", english: "spare", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["備用的","多餘的"] ] } ],
    examples: [ { en:"Please keep a spare set of keys at the front desk in case of emergencies.", zh:"請在櫃檯放一副備用鑰匙以備緊急情況使用。" } ] },
  { id: "w2055", english: "spare no expense", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["不惜花費","不吝成本"] ] } ],
    examples: [ { en:"The company spared no expense in renovating its flagship store.", zh:"公司不惜花費重新裝修了旗艦店。" } ] },
  { id: "w2056", english: "subsequent", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["隨後的","接下來的"] ] } ],
    examples: [ { en:"The initial proposal was rejected, but a subsequent revision was approved.", zh:"最初的提案被否決了，但隨後修改的版本獲得了通過。" } ] },
  { id: "w2058", english: "affix", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["貼上","黏貼","蓋上(印章)"] ] } ],
    examples: [ { en:"Please affix the correct postage before mailing the package.", zh:"寄送包裹前請貼上正確的郵資。" } ] },
  { id: "w2059", english: "critical of", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["對…持批評態度的"] ] } ],
    examples: [ { en:"The consultant was highly critical of the company's outdated inventory system.", zh:"該顧問對公司過時的庫存系統提出強烈批評。" } ] },
  { id: "w2060", english: "liable for", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["應負(法律)責任的"] ] } ],
    examples: [ { en:"The manufacturer is liable for any defects found within the warranty period.", zh:"製造商須對保修期內發現的任何瑕疵負責。" } ] },
  { id: "w2061", english: "liable to", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["很可能(發生)的"] ] } ],
    examples: [ { en:"Shipments during the holiday season are liable to be delayed.", zh:"假期期間的貨運很可能會延誤。" } ] },
  { id: "w2062", english: "belt", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["皮帶","腰帶"] ] } ],
    examples: [ { en:"He tightened his belt before heading into the interview.", zh:"他在進入面試前繫緊了皮帶。" } ] },
  { id: "w2063", english: "subject to", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["視…而定的","須經…核准的"] ] }, { pos: "vt", meaningGroups: [ ["使遭受","使經歷"] ] } ],
    examples: [ { en:"All prices are subject to change without prior notice.", zh:"所有價格均可能隨時變動，不另行通知。" }, { en:"The new equipment was subjected to rigorous testing before release.", zh:"新設備在上市前經過了嚴格的測試。" } ] },
  { id: "w2064", english: "bid for", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["出價競標","投標"] ] } ],
    examples: [ { en:"Three construction firms placed a bid for the new office building contract.", zh:"三家營造公司針對新辦公大樓的合約進行投標。" } ] },
  { id: "w2065", english: "comforting", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["令人安心的","帶來慰藉的"] ] } ],
    examples: [ { en:"It was comforting to hear that the shipment had finally arrived safely.", zh:"聽到貨物終於安全抵達，讓人感到很安心。" } ] },
  { id: "w2066", english: "commission", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["委託","委任"] ] }, { pos: "nc", meaningGroups: [ ["委員會"], ["佣金"] ] } ],
    examples: [ { en:"The city commissioned an architect to design the new library.", zh:"市政府委託一位建築師設計新的圖書館。" }, { en:"An independent commission was set up to investigate the accident.", zh:"一個獨立委員會被成立來調查這場事故。" }, { en:"Sales staff earn a commission on every unit they sell.", zh:"銷售人員每賣出一件產品就能賺取一筆佣金。" } ] },
  { id: "w2067", english: "commitment to", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["對…的承諾","致力於"] ] } ],
    examples: [ { en:"The bank has a longstanding commitment to community development.", zh:"這間銀行長期致力於社區發展。" } ] },
  { id: "w2068", english: "commodity", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["商品","日用品"] ] } ],
    examples: [ { en:"Coffee is one of the most widely traded commodities in the world.", zh:"咖啡是全世界交易最廣泛的商品之一。" } ] },
  { id: "w2069", english: "counselor", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["顧問","輔導員"], ["律師"] ] } ],
    examples: [ { en:"The company hired a career counselor to help employees plan their next steps.", zh:"公司聘請了一位職涯顧問來協助員工規劃下一步。" }, { en:"She consulted her counselor before signing the settlement agreement.", zh:"她在簽署和解協議前先諮詢了她的律師。" } ] },
  { id: "w2070", english: "courier", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["快遞員","快遞公司"] ] }, { pos: "vt", meaningGroups: [ ["用快遞寄送"] ] } ],
    examples: [ { en:"The courier delivered the contract just before the deadline.", zh:"快遞員在截止時間前送達了合約。" }, { en:"I'll courier the signed documents to your office this afternoon.", zh:"我今天下午會用快遞把簽好的文件寄到你的辦公室。" } ] },
  { id: "w2071", english: "crate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["木箱","板條箱"] ] }, { pos: "vt", meaningGroups: [ ["把…裝箱"] ] } ],
    examples: [ { en:"The warehouse stacked several crates of imported wine near the loading dock.", zh:"倉庫在裝卸區附近堆放了幾箱進口葡萄酒。" }, { en:"The staff crated the fragile equipment before shipping it overseas.", zh:"員工在把易碎設備海運出國前先把它裝箱。" } ] },
  { id: "w2072", english: "critique", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["評論","評析"] ] } ],
    examples: [ { en:"The editor provided a detailed critique of the marketing proposal.", zh:"編輯針對這份行銷提案提供了詳細的評析。" } ] },
  { id: "w2073", english: "curtail", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["削減","限制"] ] } ],
    examples: [ { en:"The firm decided to curtail travel expenses during the economic downturn.", zh:"公司決定在經濟低迷期間削減旅遊支出。" } ] },
  { id: "w2074", english: "customarily", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["慣例上","通常"] ] } ],
    examples: [ { en:"Employees are customarily given a bonus at the end of the fiscal year.", zh:"員工在會計年度結束時通常會獲得獎金。" } ] },
  { id: "w2075", english: "cyclist", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["騎自行車的人"] ] } ],
    examples: [ { en:"The city added a dedicated lane for cyclists near the business district.", zh:"該市在商業區附近增設了一條自行車專用道。" } ] },
  { id: "w2076", english: "deadlock", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["僵局"] ] } ],
    examples: [ { en:"Negotiations between the union and management reached a deadlock.", zh:"工會和管理層之間的談判陷入了僵局。" } ] },
  { id: "w2077", english: "deficient", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["不足的","缺乏的"] ] } ],
    examples: [ { en:"The report was rejected because it was deficient in supporting data.", zh:"這份報告因缺乏支持數據而被駁回。" } ] },
  { id: "w2078", english: "detach", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["使分離","拆下"] ] } ],
    examples: [ { en:"Please detach the reply form and return it in the enclosed envelope.", zh:"請撕下回覆表格，並用隨附的信封寄回。" } ] },
  { id: "w2079", english: "dispute over", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["關於…的爭議","糾紛"] ] } ],
    examples: [ { en:"The dispute over unpaid overtime dragged on for several months.", zh:"這起關於未付加班費的爭議拖了好幾個月。" } ] },
  { id: "w2080", english: "encompass", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["包含","涵蓋"] ] } ],
    examples: [ { en:"The new policy encompasses all full-time and part-time employees.", zh:"這項新政策涵蓋所有全職與兼職員工。" } ] },
  { id: "w2081", english: "envision", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["預見","設想"] ] } ],
    examples: [ { en:"The CEO envisions the company expanding into three new markets next year.", zh:"執行長設想公司明年將拓展至三個新市場。" } ] },
  { id: "w2082", english: "exempt from", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["被豁免的","免除的"] ] } ],
    examples: [ { en:"Nonprofit organizations are exempt from certain local taxes.", zh:"非營利組織可豁免部分地方稅。" } ] },
  { id: "w2083", english: "firewood", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["柴火","木柴"] ] } ],
    examples: [ { en:"The lodge keeps a supply of firewood for guests during the winter.", zh:"這間小屋在冬季為住客準備了柴火。" } ] },
  { id: "w2084", english: "hold", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["容納"], ["舉行"] ] } ],
    examples: [ { en:"The new conference hall can hold up to five hundred people.", zh:"這間新的會議廳最多可以容納五百人。" }, { en:"The board will hold an emergency meeting on Friday.", zh:"董事會將於週五舉行一場緊急會議。" } ] },
  { id: "w2085", english: "hospitality industry", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["服務業","餐旅業"] ] } ],
    examples: [ { en:"She has worked in the hospitality industry for over a decade.", zh:"她在餐旅業已經工作了超過十年。" } ] },
  { id: "w2086", english: "imperative", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["極為重要的","必須的"] ] } ],
    examples: [ { en:"It is imperative that all staff complete the safety training by Friday.", zh:"所有員工都必須在週五前完成安全訓練，這是刻不容緩的。" } ] },
  { id: "w2087", english: "incidental", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["附帶的","次要的"] ] } ],
    examples: [ { en:"Please submit receipts for any incidental expenses incurred during the trip.", zh:"請提交此次出差期間任何附帶開支的收據。" } ] },
  { id: "w2088", english: "indication", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["跡象","顯示"] ] } ],
    examples: [ { en:"Rising customer complaints are an indication of declining service quality.", zh:"客訴增加是服務品質下降的一個跡象。" } ] },
  { id: "w2089", english: "indulge in", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vi", meaningGroups: [ ["沉溺於","耽於"] ] } ],
    examples: [ { en:"The team decided to indulge in a celebratory dinner after closing the deal.", zh:"團隊在完成這筆交易後決定去享用一頓慶祝晚餐。" } ] },
  { id: "w2090", english: "infuriate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["使…極為憤怒"] ] } ],
    examples: [ { en:"The sudden price increase infuriated many long-time customers.", zh:"突然的漲價讓許多老顧客感到非常憤怒。" } ] },
  { id: "w2091", english: "lay the foundation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["打下基礎","奠定基礎"] ] } ],
    examples: [ { en:"This partnership laid the foundation for years of successful collaboration.", zh:"這次合作為多年成功的合作關係打下了基礎。" } ] },
  { id: "w2092", english: "lid", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["蓋子"] ] } ],
    examples: [ { en:"Make sure the lid is sealed tightly before shipping the container.", zh:"出貨前請確認容器的蓋子已密封緊實。" } ] },
  { id: "w2093", english: "make progress", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["取得進展"] ] } ],
    examples: [ { en:"The negotiation team is finally making progress on the contract terms.", zh:"談判小組終於在合約條款上取得了進展。" } ] },
  { id: "w2094", english: "maneuver", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["操縱","巧妙地移動"] ] } ],
    examples: [ { en:"The driver skillfully maneuvered the delivery truck through the narrow alley.", zh:"司機熟練地把貨車操縱過那條狹窄的巷子。" } ] },
  { id: "w2095", english: "markedly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["顯著地","明顯地"] ] } ],
    examples: [ { en:"Customer satisfaction improved markedly after the new support system launched.", zh:"新的客服系統上線後，顧客滿意度顯著提升。" } ] },
  { id: "w2096", english: "midday", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["正午","中午"] ] } ],
    examples: [ { en:"The delivery is scheduled to arrive around midday.", zh:"這趟送貨預計在正午左右到達。" } ] },
  { id: "w2097", english: "modification", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["修改","調整"] ] } ],
    examples: [ { en:"The client requested several modifications to the original design.", zh:"客戶要求對原始設計做幾項修改。" } ] },
  { id: "w2098", english: "narrow down to", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["縮減至","篩選至"] ] } ],
    examples: [ { en:"The hiring committee narrowed the candidates down to three finalists.", zh:"招聘委員會將候選人縮減至三位入圍者。" } ] },
  { id: "w2099", english: "oblige", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["強制","使有義務"] ] } ],
    examples: [ { en:"The contract obliges both parties to give thirty days' notice before termination.", zh:"該合約規定雙方在終止合約前必須提前三十天通知。" } ] },
  { id: "w2100", english: "occupancy", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["(空間的)使用率","入住率"] ] } ],
    examples: [ { en:"Hotel occupancy usually peaks during the summer holiday season.", zh:"飯店的入住率通常在暑假旅遊季達到高峰。" } ] },
  { id: "w2101", english: "offload", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["卸貨","卸下"] ] } ],
    examples: [ { en:"Workers offloaded the containers as soon as the ship docked.", zh:"船一靠岸，工人就開始卸下貨櫃。" } ] },
  { id: "w2102", english: "omit", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["遺漏","省略"] ] } ],
    examples: [ { en:"The assistant accidentally omitted two names from the guest list.", zh:"助理不小心從賓客名單中遺漏了兩個名字。" } ] },
  { id: "w2103", english: "on consignment", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["以寄售方式"] ] } ],
    examples: [ { en:"The boutique sells several designers' clothes on consignment.", zh:"這家精品店以寄售方式銷售好幾位設計師的服裝。" } ] },
  { id: "w2104", english: "outgoing", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["即將離職的","外發的"] ] } ],
    examples: [ { en:"The outgoing manager spent her final week training her replacement.", zh:"即將離職的經理在她最後一週訓練她的接任者。" } ] },
  { id: "w2105", english: "perishable", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["易腐壞的"] ] } ],
    examples: [ { en:"Perishable goods must be shipped in refrigerated containers.", zh:"易腐壞的商品必須用冷藏貨櫃運送。" } ] },
  { id: "w2106", english: "pottery", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["陶器"] ] } ],
    examples: [ { en:"The gift shop sells handmade pottery crafted by local artisans.", zh:"這家禮品店販售當地工匠手作的陶器。" } ] },
  { id: "w2107", english: "proceed with", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["繼續進行"] ] } ],
    examples: [ { en:"The board agreed to proceed with the acquisition despite the risks.", zh:"董事會同意儘管有風險，仍要繼續進行這次收購。" } ] },
  { id: "w2108", english: "projection", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["預測","推估"] ] } ],
    examples: [ { en:"The sales projection for next quarter looks promising.", zh:"下一季的銷售預測看起來很有希望。" } ] },
  { id: "w2109", english: "renewal", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["續約","續簽"], ["更新","重建"] ] } ],
    examples: [ { en:"Please submit your lease renewal request by the end of the month.", zh:"請在月底前提交您的租約續簽申請。" }, { en:"The city launched an urban renewal project downtown.", zh:"該市在市中心啟動了一項城市更新計畫。" } ] },
  { id: "w2110", english: "rinse", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["沖洗","漂洗"] ] } ],
    examples: [ { en:"Rinse the equipment thoroughly before returning it to the storage room.", zh:"在把設備歸還到儲藏室之前請徹底沖洗乾淨。" } ] },
  { id: "w2111", english: "senior", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["階級較高的人","上級"], ["年長者"] ] }, { pos: "adj", meaningGroups: [ ["較高階的","資深的"] ] } ],
    examples: [ { en:"New employees are expected to show respect to their seniors.", zh:"新進員工被期望要對上級表示尊重。" }, { en:"He is ten years my senior, yet we get along very well.", zh:"他比我年長十歲，但我們相處得很好。" }, { en:"As the senior partner, she has final say on major decisions.", zh:"作為資深合夥人，她對重大決策擁有最終決定權。" } ] },
  { id: "w2112", english: "shift", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["使轉移","調動"] ] }, { pos: "vi", meaningGroups: [ ["轉移","改變"] ] } ],
    examples: [ { en:"The company shifted its production line to a new facility overseas.", zh:"公司把生產線調動到海外的新廠。" }, { en:"Consumer attention has shifted toward online shopping in recent years.", zh:"近年來消費者的注意力已經轉移到網路購物上。" } ] },
  { id: "w2113", english: "shortfall", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["短缺","差額"] ] } ],
    examples: [ { en:"The budget shortfall forced the department to postpone the project.", zh:"預算短缺迫使該部門延後這項專案。" } ] },
  { id: "w2114", english: "span", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["跨越","持續(一段時間)"] ] }, { pos: "nc", meaningGroups: [ ["期間","跨度"] ] } ],
    examples: [ { en:"Her career spans more than twenty years in international trade.", zh:"她的職業生涯在國際貿易領域已經跨越了二十多年。" }, { en:"Over a span of five years, the company tripled its revenue.", zh:"在五年的期間內，該公司的營收成長了三倍。" } ] },
  { id: "w2115", english: "spice", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["香料"] ] } ],
    examples: [ { en:"The restaurant imports most of its spices directly from India.", zh:"這家餐廳大部分的香料都是直接從印度進口的。" } ] },
  { id: "w2116", english: "spray", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["噴灑"] ] }, { pos: "nc", meaningGroups: [ ["噴霧","噴劑"] ] } ],
    examples: [ { en:"Workers sprayed disinfectant on all surfaces before reopening the office.", zh:"員工在辦公室重新開放前對所有表面都噴灑了消毒劑。" }, { en:"The warehouse keeps a bottle of insect spray near the loading area.", zh:"倉庫在裝卸區附近放了一瓶殺蟲噴劑。" } ] },
  { id: "w2117", english: "stipulation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["規定","條款"] ] } ],
    examples: [ { en:"One stipulation of the contract is that payment must be made within thirty days.", zh:"合約其中一項規定是付款必須在三十天內完成。" } ] },
  { id: "w2118", english: "stir", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["攪拌"] ] } ],
    examples: [ { en:"Stir the mixture slowly to avoid lumps forming.", zh:"慢慢攪拌這個混合物以避免結塊。" } ] },
  { id: "w2119", english: "trim", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["修剪","剪整齊"], ["削減","縮減"] ] } ],
    examples: [ { en:"The gardener trimmed the hedges outside the office lobby.", zh:"園丁修剪了辦公室大廳外的樹籬。" }, { en:"The finance team trimmed nearly 15 percent off the annual budget.", zh:"財務團隊把年度預算削減了將近百分之十五。" } ] },
  { id: "w2120", english: "volume", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["音量"], ["容量","體積"], ["(書的)冊","卷"] ] } ],
    examples: [ { en:"Could you turn down the volume during the conference call?", zh:"你可以在電話會議期間把音量調小一點嗎？" }, { en:"This container has a larger volume than the one we usually use.", zh:"這個容器的容量比我們平常用的那個大。" }, { en:"The second volume of the training manual covers advanced procedures.", zh:"這本培訓手冊的第二冊涵蓋了進階流程。" } ] },
  { id: "w2121", english: "adjacent to", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["鄰近的","緊鄰的"] ] } ],
    examples: [ { en:"The new distribution center is adjacent to the highway for easy access.", zh:"這座新的配送中心緊鄰高速公路，方便進出。" } ] },
  { id: "w2122", english: "alternatively", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["或者","換一種方式"] ] } ],
    examples: [ { en:"You can pay by credit card; alternatively, you may choose a bank transfer.", zh:"你可以用信用卡付款；或者，你也可以選擇銀行轉帳。" } ] },
  { id: "w2123", english: "arise", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vi", meaningGroups: [ ["發生","出現"] ] } ],
    examples: [ { en:"Several unexpected issues arose during the product launch.", zh:"產品發表會期間出現了幾個意想不到的問題。" } ] },
  { id: "w2124", english: "assent", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vi", meaningGroups: [ ["同意","准許"] ] }, { pos: "nu", meaningGroups: [ ["同意","批准"] ] } ],
    examples: [ { en:"The board finally assented to the proposed merger.", zh:"董事會終於同意了這項提議的合併案。" }, { en:"The project could not proceed without the president's assent.", zh:"沒有總裁的批准，這項專案就無法進行。" } ] },
  { id: "w2125", english: "attentive", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["專注聆聽的","細心的"] ] } ],
    examples: [ { en:"The sales representative remained attentive throughout the client's presentation.", zh:"那位銷售代表在整場客戶簡報中都保持專注聆聽。" } ] },
  { id: "w2126", english: "authorship", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["作者身分","著作權歸屬"] ] } ],
    examples: [ { en:"The authorship of the anonymous report was eventually traced back to a junior analyst.", zh:"這份匿名報告的作者身分最終被追查到是一位初階分析師。" } ] },
  { id: "w2127", english: "banking", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["銀行業","銀行業務"] ] } ],
    examples: [ { en:"She has spent her entire career working in international banking.", zh:"她整個職業生涯都在從事國際銀行業務。" } ] },
  { id: "w2128", english: "cautiously optimistic", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["謹慎樂觀的"] ] } ],
    examples: [ { en:"Analysts remain cautiously optimistic about the company's recovery next year.", zh:"分析師對該公司明年的復甦保持謹慎樂觀的態度。" } ] },
  { id: "w2129", english: "cavity", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["蛀牙","齲齒"], ["(物體內的)空洞","孔洞"] ] } ],
    examples: [ { en:"The dentist found a small cavity during her routine checkup.", zh:"牙醫在她的例行檢查中發現了一個小蛀牙。" }, { en:"Inspectors found a hidden cavity behind the wall during the renovation.", zh:"檢查人員在裝修期間發現牆後有一個隱藏的空洞。" } ] },
  { id: "w2130", english: "Celsius", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["攝氏(溫度)"] ] } ],
    examples: [ { en:"Please set the warehouse thermostat to twenty degrees Celsius.", zh:"請把倉庫的溫控器設定在攝氏二十度。" } ] },
  { id: "w2131", english: "chilly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["寒冷的"], ["(態度)冷淡的","不友善的"] ] } ],
    examples: [ { en:"It gets quite chilly in the office after the air conditioning is left on all night.", zh:"冷氣開整晚後辦公室會變得相當寒冷。" }, { en:"He received a rather chilly reception when he suggested cutting the marketing budget.", zh:"他提議刪減行銷預算時，得到的反應相當冷淡。" } ] },
  { id: "w2132", english: "collision", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["碰撞","相撞事故"] ] } ],
    examples: [ { en:"The delivery van was involved in a minor collision on its way to the warehouse.", zh:"那輛送貨車在前往倉庫的路上發生了一起輕微碰撞事故。" } ] },
  { id: "w2133", english: "compulsory", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["必須的","強制性的"] ] } ],
    examples: [ { en:"Attendance at the safety briefing is compulsory for all new employees.", zh:"所有新員工都必須參加這場安全簡報。" } ] },
  { id: "w2134", english: "consent", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["同意","許可"] ] } ],
    examples: [ { en:"The merger cannot proceed without shareholder consent.", zh:"沒有股東的同意，這次合併就無法進行。" } ] },
  { id: "w2135", english: "considerable", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["相當大的","可觀的"] ] } ],
    examples: [ { en:"The company invested considerable resources in employee training this year.", zh:"公司今年投入了相當可觀的資源在員工培訓上。" } ] },
  { id: "w2136", english: "convert into", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["轉換成","改建成"] ] } ],
    examples: [ { en:"The firm plans to convert the old warehouse into a modern office space.", zh:"該公司計劃把舊倉庫改建成現代化的辦公空間。" } ] },
  { id: "w2137", english: "deliberation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["商議","審議"] ] } ],
    examples: [ { en:"After lengthy deliberation, the committee approved the new hiring policy.", zh:"經過長時間的商議，委員會批准了這項新的招聘政策。" } ] },
  { id: "w2138", english: "delinquent", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["逾期未繳的","拖欠的"] ] } ],
    examples: [ { en:"The vendor suspended service on the delinquent account.", zh:"供應商暫停了這個逾期未繳帳戶的服務。" } ] },
  { id: "w2139", english: "deplete", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["耗盡","使減少"] ] } ],
    examples: [ { en:"The prolonged shortage depleted the company's raw material reserves.", zh:"長期的短缺耗盡了公司的原料庫存。" } ] },
  { id: "w2140", english: "deprivation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["匱乏","(生活必需品的)缺乏"] ] } ],
    examples: [ { en:"There were food shortages and other deprivations during the crisis.", zh:"危機期間出現了糧食短缺和其他各種匱乏的情況。" } ] },
  { id: "w2141", english: "determine the cause of", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["查明…的原因"] ] } ],
    examples: [ { en:"Engineers were sent to determine the cause of the production line failure.", zh:"工程師被派去查明生產線故障的原因。" } ] },
  { id: "w2142", english: "dirt", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["灰塵","污垃","泥土"] ] } ],
    examples: [ { en:"Workers wiped the dirt off the machinery before the inspection.", zh:"工人在檢查前把機器上的灰塵擦乾淨。" } ] },
  { id: "w2143", english: "discharge", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["排放(廢棄物)"], ["准許(病人)出院","解除職務"] ] } ],
    examples: [ { en:"The factory was fined for illegally discharging chemicals into the river.", zh:"這家工廠因非法向河中排放化學物質而被罰款。" }, { en:"He was discharged from his duties after the internal investigation concluded.", zh:"內部調查結束後，他被解除了職務。" } ] },
  { id: "w2144", english: "drape with", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["用(布)覆蓋","披掛"] ] } ],
    examples: [ { en:"The stage was draped with the company's banners for the product launch.", zh:"舞台上披掛著公司的橫幅，為產品發表會布置。" } ] },
  { id: "w2145", english: "duration", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["期間","持續時間"] ] } ],
    examples: [ { en:"Employees must wear identification badges for the duration of the conference.", zh:"員工在整個會議期間都必須佩戴識別證。" } ] },
  { id: "w2146", english: "dwell", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vi", meaningGroups: [ ["居住"] ] } ],
    examples: [ { en:"The company's founder once dwelt in a small apartment above his first store.", zh:"這家公司的創辦人曾經住在他第一間店樓上的小公寓裡。" } ] },
  { id: "w2147", english: "excessive", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["過度的","過多的"] ] } ],
    examples: [ { en:"The audit flagged excessive spending in the marketing department.", zh:"這次審計指出行銷部門存在過度支出的問題。" } ] },
  { id: "w2148", english: "expressly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["明確地"], ["特意","專門為了"] ] } ],
    examples: [ { en:"The manager expressly stated that overtime must be approved in advance.", zh:"經理明確表示加班必須事先獲得核准。" }, { en:"This meeting room was designed expressly for client presentations.", zh:"這間會議室是專門為客戶簡報而設計的。" } ] },
  { id: "w2149", english: "fireplace", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["壁爐"] ] } ],
    examples: [ { en:"The lobby features a large fireplace that guests love in winter.", zh:"大廳裡有一座住客在冬天很喜愛的大壁爐。" } ] },
  { id: "w2150", english: "hood", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["(汽車的)引擎蓋"] ] } ],
    examples: [ { en:"The mechanic opened the hood to check the engine.", zh:"技師打開引擎蓋來檢查引擎。" } ] },
  { id: "w2151", english: "humid", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["潮濕的"] ] } ],
    examples: [ { en:"The warehouse must be kept cool and dry, since humid conditions can damage the goods.", zh:"倉庫必須保持涼爽乾燥，因為潮濕的環境會損壞貨物。" } ] },
  { id: "w2152", english: "improbable", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["不太可能的","難以置信的"] ] } ],
    examples: [ { en:"It seems improbable that the project will be finished by next week.", zh:"這項專案似乎不太可能在下週前完成。" } ] },
  { id: "w2153", english: "induce", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["導致","引起"], ["說服","誘使"] ] } ],
    examples: [ { en:"The new sedative is known to induce drowsiness.", zh:"這種新的鎮定劑已知會引起嗜睡。" }, { en:"The recruiter induced her to accept the offer by promising flexible hours.", zh:"招募人員以承諾彈性工時來說服她接受這份工作。" } ] },
  { id: "w2154", english: "inducement", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["誘因","獎勵"] ] } ],
    examples: [ { en:"The company offered a signing bonus as an inducement to join the team.", zh:"公司提供簽約獎金作為加入團隊的誘因。" } ] },
  { id: "w2155", english: "inflict", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["使遭受","施加(損害)"] ] } ],
    examples: [ { en:"The scandal inflicted serious damage on the brand's reputation.", zh:"這場醜聞給該品牌的聲譽造成了嚴重的損害。" } ] },
  { id: "w2156", english: "informative", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["資訊豐富的","有幫助的"] ] } ],
    examples: [ { en:"The seminar was highly informative for anyone new to supply chain management.", zh:"這場研討會對任何剛接觸供應鏈管理的人來說都非常有幫助。" } ] },
  { id: "w2157", english: "informed", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["見聞廣博的","充分了解情況的"] ] } ],
    examples: [ { en:"Reading the quarterly report will help you make an informed decision.", zh:"閱讀這份季度報告將有助於你做出充分了解情況的決定。" } ] },
  { id: "w2158", english: "inherently", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["本質上","固有地"] ] } ],
    examples: [ { en:"Investing in emerging markets is inherently risky.", zh:"投資新興市場本質上就具有風險。" } ] },
  { id: "w2159", english: "inhibition", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["拘束","顧慮"] ] } ],
    examples: [ { en:"After a few team-building exercises, employees lost their inhibitions about speaking up in meetings.", zh:"經過幾次團隊建設活動後，員工在會議上發言不再有所顧慮。" } ] },
  { id: "w2160", english: "innate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["天生的","固有的"] ] } ],
    examples: [ { en:"He has an innate ability to read the market and predict trends.", zh:"他擁有解讀市場並預測趨勢的天生能力。" } ] },
  { id: "w2161", english: "intensively", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["密集地"] ] } ],
    examples: [ { en:"The new hires trained intensively for two weeks before joining the sales floor.", zh:"新員工在加入銷售一線前密集訓練了兩週。" } ] },
  { id: "w2162", english: "in the interest of", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["為了…的利益"] ] } ],
    examples: [ { en:"In the interest of safety, all visitors must wear a helmet on the construction site.", zh:"為了安全起見，所有訪客在建築工地上都必須戴上安全帽。" } ] },
  { id: "w2163", english: "inward", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["向內地"] ] } ],
    examples: [ { en:"Fold the edges of the packaging inward before sealing the box.", zh:"密封箱子前請把包裝的邊緣向內折。" } ] },
  { id: "w2164", english: "ironing", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["燙衣服"] ] } ],
    examples: [ { en:"The hotel offers an ironing service for business travelers.", zh:"這家飯店為商務旅客提供燙衣服務。" } ] },
  { id: "w2165", english: "lastingly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["持久地","長久地"] ] } ],
    examples: [ { en:"The reforms are expected to lastingly improve working conditions across the industry.", zh:"這些改革預期將長久改善整個產業的工作環境。" } ] },
  { id: "w2166", english: "payable to", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["(支票)應付給…的"] ] } ],
    examples: [ { en:"Please make the check payable to the supplier listed on the invoice.", zh:"請將支票開立給發票上列出的供應商。" } ] },
  { id: "w2167", english: "place an emphasis on", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["把重點放在","強調"] ] } ],
    examples: [ { en:"The training program places an emphasis on customer service skills.", zh:"這項培訓計畫把重點放在客戶服務技巧上。" } ] },
  { id: "w2168", english: "plaza", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["廣場"] ] } ],
    examples: [ { en:"The company's headquarters overlooks a busy downtown plaza.", zh:"該公司的總部俯瞰著一個熱鬧的市中心廣場。" } ] },
  { id: "w2169", english: "pleasing", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["令人滿意的","討人喜歡的"] ] } ],
    examples: [ { en:"The revised layout of the store is far more pleasing to customers.", zh:"這家店重新設計後的布局更讓顧客感到滿意。" } ] },
  { id: "w2170", english: "pollutant", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["污染物"] ] } ],
    examples: [ { en:"The factory installed new filters to reduce harmful pollutants in its emissions.", zh:"這家工廠安裝了新的濾網來減少排放中的有害污染物。" } ] },
  { id: "w2171", english: "premium", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["保險費"] ] } ],
    examples: [ { en:"Monthly insurance premiums will increase by ten percent next year.", zh:"每月的保險費明年將上漲百分之十。" } ] },
  { id: "w2172", english: "preside over", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["主持(會議、儀式等)"] ] } ],
    examples: [ { en:"The chairman will preside over tomorrow's shareholder meeting.", zh:"董事長將主持明天的股東會議。" } ] },
  { id: "w2173", english: "prevalent", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["普遍存在的","盛行的"] ] } ],
    examples: [ { en:"Remote work has become far more prevalent since the pandemic.", zh:"自疫情以來，遠距工作已變得更加普遍。" } ] },
  { id: "w2174", english: "prominently", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["顯著地","顯眼地"] ] } ],
    examples: [ { en:"The company's logo is displayed prominently on all delivery trucks.", zh:"該公司的標誌顯眼地展示在所有貨運卡車上。" } ] },
  { id: "w2175", english: "radically", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["徹底地","根本地"] ] } ],
    examples: [ { en:"The department was radically restructured after the merger.", zh:"這個部門在合併後被徹底重組。" } ] },
  { id: "w2176", english: "refutation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["反駁","駁斥"] ] } ],
    examples: [ { en:"The company issued a formal refutation of the allegations in the article.", zh:"該公司針對文章中的指控發布了正式的反駁聲明。" } ] },
  { id: "w2177", english: "refute", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["反駁","駁斥"] ] } ],
    examples: [ { en:"The spokesperson refuted claims that the product was unsafe.", zh:"發言人反駁了該產品不安全的說法。" } ] },
  { id: "w2178", english: "remedy", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["解決方法","補救措施"] ] } ],
    examples: [ { en:"Offering a full refund was the simplest remedy for the customer's complaint.", zh:"提供全額退款是解決這位顧客投訴最簡單的方法。" } ] },
  { id: "w2179", english: "rope", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["繩子"] ] }, { pos: "vt", meaningGroups: [ ["用繩子綑綁","拉攏"] ] } ],
    examples: [ { en:"Workers used a thick rope to secure the cargo on the truck.", zh:"工人用一條粗繩子把貨物固定在卡車上。" }, { en:"The manager roped a few volunteers into helping with the event setup.", zh:"經理拉了幾位志工來幫忙布置活動場地。" } ] },
  { id: "w2180", english: "safeguard", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["保障措施"] ] }, { pos: "vt", meaningGroups: [ ["保護","維護"] ] } ],
    examples: [ { en:"The new policy includes safeguards to prevent data leaks.", zh:"這項新政策包含防止資料外洩的保障措施。" }, { en:"The union works to safeguard the interests of all its members.", zh:"工會致力於維護所有會員的權益。" } ] },
  { id: "w2181", english: "seating chart", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["座位表"] ] } ],
    examples: [ { en:"The event planner prepared a seating chart for the annual gala.", zh:"活動策劃人為年度晚宴準備了一張座位表。" } ] },
  { id: "w2182", english: "smoking section", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["吸菸區"] ] } ],
    examples: [ { en:"The restaurant removed its smoking section after the new regulations took effect.", zh:"新規定實施後，這家餐廳撤除了吸菸區。" } ] },
  { id: "w2183", english: "solely", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["僅僅","單獨地"] ] } ],
    examples: [ { en:"The decision rests solely with the department head.", zh:"這項決定完全取決於部門主管。" } ] },
  { id: "w2184", english: "susceptible", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["易受影響的","容易受到…傷害的"] ] } ],
    examples: [ { en:"Small businesses are particularly susceptible to fluctuations in the exchange rate.", zh:"小型企業特別容易受到匯率波動的影響。" } ] },
  { id: "w2185", english: "take into account", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["將…納入考量"] ] } ],
    examples: [ { en:"The budget plan takes into account the rising cost of raw materials.", zh:"這份預算計畫將原物料成本上升納入了考量。" } ] },
  { id: "w2186", english: "unprecedented", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["前所未有的","空前的"] ] } ],
    examples: [ { en:"The company reported unprecedented growth in overseas sales this year.", zh:"該公司今年海外銷售額出現了前所未有的成長。" } ] },
  { id: "w2187", english: "veranda", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["陽台","走廊"] ] } ],
    examples: [ { en:"Guests can enjoy their morning coffee on the hotel's veranda.", zh:"住客可以在飯店的陽台上享用早晨咖啡。" } ] },
  { id: "w2188", english: "vested interest", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["(既得的)個人利益","私利"] ] } ],
    examples: [ { en:"As a major shareholder, he has a vested interest in the company's success.", zh:"作為一名主要股東，他對這家公司的成功抱有既得利益。" } ] },
  {
    id: "w2220", english: "accommodation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["住宿"] ] },
      { pos: "nc", meaningGroups: [ ["妥協","通融"] ] }
    ],
    examples: [
      { en:"The company provides accommodation for employees relocating overseas.", zh:"公司為外派海外的員工提供住宿。" },
      { en:"Both parties reached an accommodation after lengthy negotiations.", zh:"雙方經過長時間談判後達成了妥協。" }
    ]
  },
  {
    id: "w2221", english: "alternative", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["替代的","另一種的"] ] },
      { pos: "nc", meaningGroups: [ ["替代方案","另一種選擇"] ] }
    ],
    examples: [
      { en:"We need to find an alternative supplier for these parts.", zh:"我們需要為這些零件尋找一個替代供應商。" },
      { en:"Working from home is a popular alternative to commuting.", zh:"在家工作是通勤的熱門替代選擇。" }
    ]
  },
  {
    id: "w2222", english: "appliance", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["家用電器","器具"] ] } ],
    examples: [
      { en:"The store sells a wide range of kitchen appliances.", zh:"這家店販售各種廚房電器。" }
    ]
  },
  {
    id: "w2223", english: "approximately", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["大約","大概"] ] } ],
    examples: [
      { en:"The project will take approximately six months to complete.", zh:"這個專案大約需要六個月才能完成。" }
    ]
  },
  {
    id: "w2224", english: "campaign", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["宣傳活動","活動"] ] },
      { pos: "vi", meaningGroups: [ ["發起運動","進行遊說"] ] }
    ],
    examples: [
      { en:"The marketing team launched a new advertising campaign.", zh:"行銷團隊發起了一項新的廣告宣傳活動。" },
      { en:"Employees campaigned for better working conditions.", zh:"員工們為爭取更好的工作條件而發起運動。" }
    ]
  },
  {
    id: "w2225", english: "ceremony", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["典禮","儀式"] ] } ],
    examples: [
      { en:"The company held a ceremony to celebrate its 20th anniversary.", zh:"公司舉辦了一場典禮來慶祝二十週年。" }
    ]
  },
  {
    id: "w2226", english: "competence", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["能力","勝任能力"] ] } ],
    examples: [
      { en:"Her competence in financial analysis impressed the board.", zh:"她在財務分析方面的能力令董事會印象深刻。" }
    ]
  },
  {
    id: "w2227", english: "complete", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["完整的","十足的"] ] },
      { pos: "vt", meaningGroups: [ ["完成"] ] }
    ],
    examples: [
      { en:"Please submit a complete application form.", zh:"請提交一份完整的申請表。" },
      { en:"She completed the report ahead of schedule.", zh:"她提前完成了報告。" }
    ]
  },
  {
    id: "w2228", english: "comprehensive", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["詳盡的","全面的"] ] } ],
    examples: [
      { en:"The consultant provided a comprehensive analysis of the market.", zh:"顧問提供了一份詳盡的市場分析。" }
    ]
  },
  {
    id: "w2229", english: "convey", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["傳達","表達"] ] } ],
    examples: [
      { en:"The email failed to convey the urgency of the situation.", zh:"這封電子郵件未能傳達出情況的緊迫性。" }
    ]
  },
  {
    id: "w2230", english: "convincingly", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adv", meaningGroups: [ ["令人信服地","有說服力地"] ] } ],
    examples: [
      { en:"She argued convincingly for the new marketing strategy.", zh:"她令人信服地為新的行銷策略辯護。" }
    ]
  },
  {
    id: "w2231", english: "cooperation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["合作","配合"] ] } ],
    examples: [
      { en:"The merger requires close cooperation between both companies.", zh:"這次合併需要兩家公司密切合作。" }
    ]
  },
  {
    id: "w2232", english: "delegate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["代表"] ] },
      { pos: "vt", meaningGroups: [ ["委派","授權"] ] }
    ],
    examples: [
      { en:"Each department sent a delegate to the conference.", zh:"每個部門都派了一位代表參加會議。" },
      { en:"Managers should delegate tasks to their team members.", zh:"主管應該把任務授權給團隊成員。" }
    ]
  },
  {
    id: "w2233", english: "duplicate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["副本","複本"] ] },
      { pos: "vt", meaningGroups: [ ["複製","重複"] ] }
    ],
    examples: [
      { en:"Please make a duplicate of this document for our records.", zh:"請為這份文件製作一份副本供我們存檔。" },
      { en:"The system will duplicate the file automatically.", zh:"系統會自動複製這個檔案。" }
    ]
  },
  {
    id: "w2234", english: "enthusiasm", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["熱忱","熱情"] ] } ],
    examples: [
      { en:"The new employee showed great enthusiasm for the project.", zh:"這位新員工對這個專案展現出極大的熱忱。" }
    ]
  },
  {
    id: "w2235", english: "entitle", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["使有權利","給予資格"] ] } ],
    examples: [
      { en:"This coupon entitles you to a 20% discount.", zh:"這張優惠券讓你有權享有八折優惠。" }
    ]
  },
  {
    id: "w2236", english: "estimate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["估價","估計數"] ] },
      { pos: "vt", meaningGroups: [ ["估計","估算"] ] }
    ],
    examples: [
      { en:"The contractor gave us an estimate for the renovation.", zh:"承包商給了我們一份裝修估價。" },
      { en:"We estimate that sales will grow by 10% next year.", zh:"我們估計明年銷售額將成長百分之十。" }
    ]
  },
  {
    id: "w2237", english: "extracurricular", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["課外的"] ] } ],
    examples: [
      { en:"The school encourages students to join extracurricular activities.", zh:"學校鼓勵學生參加課外活動。" }
    ]
  },
  {
    id: "w2238", english: "etiquette", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["禮儀","禮節"] ] } ],
    examples: [
      { en:"Understanding business etiquette is important when meeting foreign clients.", zh:"了解商務禮儀對於會見外國客戶很重要。" }
    ]
  },
  {
    id: "w2239", english: "fuel", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["燃料"] ] },
      { pos: "vt", meaningGroups: [ ["刺激","助長"] ] }
    ],
    examples: [
      { en:"Rising fuel prices have increased shipping costs.", zh:"燃料價格上漲使運輸成本增加。" },
      { en:"The new investment fueled the company's rapid growth.", zh:"這筆新投資助長了公司的快速成長。" }
    ]
  },
  {
    id: "w2240", english: "impose", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["施加","強制實行"] ] },
      { pos: "vi", meaningGroups: [ ["打擾","造成不便"] ] }
    ],
    examples: [
      { en:"The government decided to impose a tax on imported goods.", zh:"政府決定對進口商品徵收稅款。" },
      { en:"I hope I'm not imposing by asking for a ride.", zh:"我希望我請你載我一程不會造成打擾。" }
    ]
  },
  {
    id: "w2241", english: "innovative", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["創新的","新穎的"] ] } ],
    examples: [
      { en:"The startup is known for its innovative solutions.", zh:"這家新創公司以其創新的解決方案聞名。" }
    ]
  },
  {
    id: "w2242", english: "intelligent", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["聰明的","有智慧的"] ] } ],
    examples: [
      { en:"The system uses intelligent software to detect fraud.", zh:"該系統使用智慧型軟體來偵測詐騙。" }
    ]
  },
  {
    id: "w2243", english: "invoice", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["發票","帳單"] ] },
      { pos: "vt", meaningGroups: [ ["開發票給"] ] }
    ],
    examples: [
      { en:"Please send the invoice to our accounting department.", zh:"請將發票寄給我們的會計部門。" },
      { en:"We will invoice the client once the project is complete.", zh:"專案完成後我們將向客戶開發票。" }
    ]
  },
  {
    id: "w2244", english: "launch", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["推出","發起"] ] },
      { pos: "nc", meaningGroups: [ ["推出","發行"] ] }
    ],
    examples: [
      { en:"The company will launch a new product line next month.", zh:"公司將於下個月推出新的產品系列。" },
      { en:"The product launch attracted a lot of media attention.", zh:"這次產品發表會吸引了大量媒體關注。" }
    ]
  },
  {
    id: "w2245", english: "manufacturer", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["製造商","廠商"] ] } ],
    examples: [
      { en:"The manufacturer offers a two-year warranty on all products.", zh:"這家製造商為所有產品提供兩年保固。" }
    ]
  },
  {
    id: "w2246", english: "layout", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["佈局","編排"] ] } ],
    examples: [
      { en:"The office layout was redesigned to improve collaboration.", zh:"辦公室的佈局重新設計以促進協作。" }
    ]
  },
  {
    id: "w2247", english: "maintenance", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["維修","保養"] ] } ],
    examples: [
      { en:"The building requires regular maintenance to stay safe.", zh:"這棟建築需要定期維修才能保持安全。" }
    ]
  },
  {
    id: "w2248", english: "occupation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["職業"] ] } ],
    examples: [
      { en:"Please state your occupation on the application form.", zh:"請在申請表上填寫你的職業。" }
    ]
  },
  {
    id: "w2249", english: "organization", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["機構","團體"] ] },
      { pos: "nu", meaningGroups: [ ["組織","安排"] ] }
    ],
    examples: [
      { en:"She works for a non-profit organization.", zh:"她在一家非營利機構工作。" },
      { en:"The organization of the conference took several months.", zh:"這次會議的籌辦花了好幾個月。" }
    ]
  },
  {
    id: "w2250", english: "philosophy", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["哲學"] ] },
      { pos: "nc", meaningGroups: [ ["理念","原則"] ] }
    ],
    examples: [
      { en:"He studied philosophy at university.", zh:"他在大學讀哲學。" },
      { en:"Customer satisfaction is at the core of our company philosophy.", zh:"顧客滿意度是我們公司理念的核心。" }
    ]
  },
  {
    id: "w2251", english: "permit", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["許可證"] ] },
      { pos: "vt", meaningGroups: [ ["允許","准許"] ] }
    ],
    examples: [
      { en:"Workers must obtain a permit before starting construction.", zh:"工人必須在開工前取得許可證。" },
      { en:"The policy does not permit employees to work remotely.", zh:"該政策不允許員工遠端工作。" }
    ]
  },
  {
    id: "w2252", english: "photography", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["攝影","攝影術"] ] } ],
    examples: [
      { en:"She took a course in commercial photography.", zh:"她上了一門商業攝影的課程。" }
    ]
  },
  {
    id: "w2253", english: "postage", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["郵資"] ] } ],
    examples: [
      { en:"The postage for international packages has increased.", zh:"國際包裹的郵資已經上漲了。" }
    ]
  },
  {
    id: "w2254", english: "potential", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["潛在的"] ] },
      { pos: "nu", meaningGroups: [ ["潛力"] ] }
    ],
    examples: [
      { en:"The firm identified several potential clients at the trade show.", zh:"該公司在貿易展上找到了幾位潛在客戶。" },
      { en:"The manager recognized her potential and promoted her.", zh:"經理看出了她的潛力並提拔了她。" }
    ]
  },
  {
    id: "w2255", english: "precise", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["精確的","準確的"] ] } ],
    examples: [
      { en:"We need precise figures before submitting the budget.", zh:"在提交預算之前我們需要精確的數字。" }
    ]
  },
  {
    id: "w2256", english: "presentation", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["簡報","報告"] ] },
      { pos: "nu", meaningGroups: [ ["呈現方式","外觀"] ] }
    ],
    examples: [
      { en:"She gave a presentation on the quarterly results.", zh:"她做了一場關於季度業績的簡報。" },
      { en:"The presentation of the dishes impressed the customers.", zh:"這些菜品的呈現方式令顧客印象深刻。" }
    ]
  },
  {
    id: "w2257", english: "priority", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["優先事項"] ] },
      { pos: "nu", meaningGroups: [ ["優先權"] ] }
    ],
    examples: [
      { en:"Reducing costs is our top priority this year.", zh:"降低成本是我們今年的首要任務。" },
      { en:"Members are given priority when booking tickets.", zh:"會員在訂票時享有優先權。" }
    ]
  },
  {
    id: "w2258", english: "procedure", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["程序","步驟"] ] } ],
    examples: [
      { en:"Please follow the correct procedure when filing a complaint.", zh:"提出投訴時請遵循正確的程序。" }
    ]
  },
  {
    id: "w2259", english: "purchase", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["購買"] ] },
      { pos: "nc", meaningGroups: [ ["購買的物品"] ] }
    ],
    examples: [
      { en:"The company plans to purchase new equipment next quarter.", zh:"公司計劃在下個季度購買新設備。" },
      { en:"Keep your receipt in case you need to return the purchase.", zh:"保留收據以便日後需要退回購買的商品。" }
    ]
  },
  {
    id: "w2260", english: "prior to", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "prep", meaningGroups: [ ["在…之前","先於"] ] } ],
    examples: [
      { en:"Please arrive prior to the scheduled meeting time.", zh:"請在預定的會議時間之前抵達。" }
    ]
  },
  {
    id: "w2261", english: "profile", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["個人資料","簡介"], ["形象","知名度"] ] } ],
    examples: [
      { en:"Please update your profile on the company website.", zh:"請更新你在公司網站上的個人資料。" },
      { en:"The CEO prefers to keep a low profile.", zh:"執行長偏好保持低調的形象。" }
    ]
  },
  {
    id: "w2262", english: "private", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["私人的","私密的"], ["私營的"] ] } ],
    examples: [
      { en:"Please keep this information private.", zh:"請將這項資訊保密。" },
      { en:"She works in the private sector as a consultant.", zh:"她在私營部門擔任顧問。" }
    ]
  },
  {
    id: "w2263", english: "projector", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["投影機"] ] } ],
    examples: [
      { en:"The technician set up the projector before the meeting.", zh:"技術人員在會議前架設好了投影機。" }
    ]
  },
  {
    id: "w2264", english: "red carpet", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["隆重的禮遇","貴賓待遇"] ] } ],
    examples: [
      { en:"The hotel rolled out the red carpet for VIP guests.", zh:"飯店為貴賓提供了隆重的禮遇。" }
    ]
  },
  {
    id: "w2265", english: "proposal", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["提案","建議"] ] } ],
    examples: [
      { en:"The team submitted a proposal for the new marketing plan.", zh:"團隊提交了新行銷計畫的提案。" }
    ]
  },
  {
    id: "w2266", english: "recognize", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["認出","辨識出"], ["承認","表彰"] ] } ],
    examples: [
      { en:"I didn't recognize him without his uniform.", zh:"沒穿制服的他,我沒認出來。" },
      { en:"The company recognized her contribution with an award.", zh:"公司以獎項表彰她的貢獻。" }
    ]
  },
  {
    id: "w2267", english: "punctual", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["準時的"] ] } ],
    examples: [
      { en:"Employees are expected to be punctual for meetings.", zh:"員工被要求開會要準時。" }
    ]
  },
  {
    id: "w2268", english: "receipt", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["收據"] ] },
      { pos: "nu", meaningGroups: [ ["收到"] ] }
    ],
    examples: [
      { en:"Please keep your receipt for warranty purposes.", zh:"請保留收據以便保固使用。" },
      { en:"We acknowledge receipt of your payment.", zh:"我們確認已收到你的付款。" }
    ]
  },
  {
    id: "w2269", english: "semester", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["學期"] ] } ],
    examples: [
      { en:"Tuition must be paid before the start of the semester.", zh:"學費必須在學期開始前繳交。" }
    ]
  },
  {
    id: "w2270", english: "reception", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["接待處"], ["招待會","歡迎會"] ] } ],
    examples: [
      { en:"Please check in at the reception desk.", zh:"請在接待處辦理登記。" },
      { en:"The company held a reception for new clients.", zh:"公司為新客戶舉辦了一場招待會。" }
    ]
  },
  {
    id: "w2271", english: "significant", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["重大的","顯著的"] ] } ],
    examples: [
      { en:"The new policy had a significant impact on sales.", zh:"這項新政策對銷售產生了重大影響。" }
    ]
  },
  {
    id: "w2272", english: "regret", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["後悔","對…感到遺憾"] ] },
      { pos: "nu", meaningGroups: [ ["懊悔","遺憾"] ] }
    ],
    examples: [
      { en:"We regret to inform you that your application was unsuccessful.", zh:"我們很遺憾地通知您,您的申請未獲通過。" },
      { en:"She expressed regret over the missed deadline.", zh:"她對錯過截止日期表示懊悔。" }
    ]
  },
  {
    id: "w2273", english: "slide", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ ["下滑","下跌"] ] },
      { pos: "nc", meaningGroups: [ ["投影片"] ] }
    ],
    examples: [
      { en:"Stock prices continued to slide throughout the day.", zh:"股價全天持續下跌。" },
      { en:"Please move to the next slide in the presentation.", zh:"請切換到簡報的下一張投影片。" }
    ]
  },
  {
    id: "w2274", english: "reliable", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["可靠的"] ] } ],
    examples: [
      { en:"We need a reliable supplier for these components.", zh:"我們需要一個可靠的供應商來提供這些零件。" }
    ]
  },
  {
    id: "w2275", english: "socialize", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vi", meaningGroups: [ ["交際","社交往來"] ] } ],
    examples: [
      { en:"Employees are encouraged to socialize during the company retreat.", zh:"員工們被鼓勵在公司靜修活動中交際。" }
    ]
  },
  {
    id: "w2276", english: "reminder", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["提醒","提醒事項"] ] } ],
    examples: [
      { en:"I sent a reminder about tomorrow's deadline.", zh:"我發了一封關於明天截止日期的提醒。" }
    ]
  },
  {
    id: "w2277", english: "squeeze", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["擠壓","壓縮"] ] },
      { pos: "nc", meaningGroups: [ ["緊縮","擠壓"] ] }
    ],
    examples: [
      { en:"Rising costs are squeezing the company's profit margins.", zh:"成本上升正在壓縮公司的利潤空間。" },
      { en:"The credit squeeze made it harder for firms to borrow.", zh:"信貸緊縮讓企業更難借到錢。" }
    ]
  },
  {
    id: "w2278", english: "representative", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "adj", meaningGroups: [ ["典型的","代表性的"] ] },
      { pos: "nc", meaningGroups: [ ["代表","業務員"] ] }
    ],
    examples: [
      { en:"The survey results are representative of the entire industry.", zh:"這項調查結果具有整個產業的代表性。" },
      { en:"A sales representative will contact you shortly.", zh:"一位業務代表將會盡快與您聯繫。" }
    ]
  },
  {
    id: "w2279", english: "storage", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nu", meaningGroups: [ ["儲存","倉儲"] ] } ],
    examples: [
      { en:"The company rents a warehouse for storage.", zh:"公司租用一間倉庫作為儲存空間。" }
    ]
  },
  {
    id: "w2280", english: "requirement", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["要求","必要條件"] ] } ],
    examples: [
      { en:"Applicants must meet the minimum requirements for the position.", zh:"應徵者必須符合這個職位的最低要求。" }
    ]
  },
  {
    id: "w2281", english: "strengthen", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "vt", meaningGroups: [ ["增強","加強"] ] } ],
    examples: [
      { en:"The firm plans to strengthen its position in the market.", zh:"該公司計劃強化其在市場上的地位。" }
    ]
  },
  {
    id: "w2282", english: "straw", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["吸管"] ] },
      { pos: "nu", meaningGroups: [ ["稻草"] ] }
    ],
    examples: [
      { en:"Please use a paper straw instead of a plastic one.", zh:"請使用紙吸管代替塑膠吸管。" },
      { en:"The roof of the barn was made of straw.", zh:"這間穀倉的屋頂是用稻草做的。" }
    ]
  },
  {
    id: "w2283", english: "strict", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["嚴格的","嚴厲的"] ] } ],
    examples: [
      { en:"The company has strict rules regarding attendance.", zh:"公司對出席有嚴格的規定。" }
    ]
  },
  {
    id: "w2284", english: "stress", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["壓力","緊張"] ] },
      { pos: "vt", meaningGroups: [ ["強調"] ] }
    ],
    examples: [
      { en:"Heavy workloads can cause a lot of stress.", zh:"繁重的工作量會造成很大的壓力。" },
      { en:"The manager stressed the importance of meeting deadlines.", zh:"經理強調了準時完成工作的重要性。" }
    ]
  },
  {
    id: "w2285", english: "submit", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ ["提交"] ] },
      { pos: "vi", meaningGroups: [ ["屈服","服從"] ] }
    ],
    examples: [
      { en:"Please submit your report by Friday.", zh:"請在星期五前提交你的報告。" },
      { en:"The union refused to submit to the company's demands.", zh:"工會拒絕屈服於公司的要求。" }
    ]
  },
  {
    id: "w2286", english: "strike", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["罷工"] ] },
      { pos: "vt", meaningGroups: [ ["打","擊中"], ["使突然想到"] ] }
    ],
    examples: [
      { en:"Workers went on strike to demand higher wages.", zh:"工人們罷工要求提高工資。" },
      { en:"It suddenly struck her that she had forgotten the meeting.", zh:"她突然想起自己忘了那場會議。" }
    ]
  },
  {
    id: "w2287", english: "summary", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["摘要","概要"] ] } ],
    examples: [
      { en:"Please provide a summary of the meeting minutes.", zh:"請提供會議記錄的摘要。" }
    ]
  },
  {
    id: "w2288", english: "supply", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ ["供應","供應量"] ] },
      { pos: "vt", meaningGroups: [ ["供應","提供"] ] }
    ],
    examples: [
      { en:"The supply of raw materials has decreased due to the shortage.", zh:"由於短缺,原材料的供應量已經減少。" },
      { en:"The vendor supplies office equipment to local businesses.", zh:"這家廠商為當地企業供應辦公設備。" }
    ]
  },
  {
    id: "w2289", english: "submission", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["提交物","投稿"] ] },
      { pos: "nu", meaningGroups: [ ["屈服","聽從"] ] }
    ],
    examples: [
      { en:"The deadline for submission of proposals is next Friday.", zh:"提案的提交截止日期是下週五。" },
      { en:"After weeks of pressure, the department showed submission to the new policy.", zh:"經過數週的壓力後,該部門對新政策表示了屈從。" }
    ]
  },
  {
    id: "w2291", english: "urgent", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "adj", meaningGroups: [ ["緊急的","迫切的"] ] } ],
    examples: [
      { en:"This is an urgent matter that requires immediate attention.", zh:"這是一件需要立即處理的緊急事務。" }
    ]
  },
  {
    id: "w2292", english: "take up", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "phr.", meaningGroups: [ ["佔用"], ["開始從事","著手進行"] ] } ],
    examples: [
      { en:"The new equipment takes up too much space in the office.", zh:"這台新設備在辦公室裡佔用了太多空間。" },
      { en:"She decided to take up a new hobby after retiring.", zh:"她退休後決定開始從事一項新的愛好。" }
    ]
  },
  {
    id: "w2293", english: "vet", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nc", meaningGroups: [ ["獸醫"] ] },
      { pos: "vt", meaningGroups: [ ["審查","核實"] ] }
    ],
    examples: [
      { en:"She took her dog to the vet for a checkup.", zh:"她帶她的狗去獸醫那裡做健康檢查。" },
      { en:"All candidates are carefully vetted before being hired.", zh:"所有應徵者在被錄用前都會經過仔細審查。" }
    ]
  },
  {
    id: "w2294", english: "vice president", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["副總裁","副總統"] ] } ],
    examples: [
      { en:"She was recently promoted to vice president of sales.", zh:"她最近被升為銷售部副總裁。" }
    ]
  },
  {
    id: "w2295", english: "video conference", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["視訊會議"] ] } ],
    examples: [
      { en:"The team held a video conference with clients overseas.", zh:"團隊與海外客戶舉行了一場視訊會議。" }
    ]
  },
  {
    id: "w2296", english: "voucher", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [ { pos: "nc", meaningGroups: [ ["禮券","憑證"] ] } ],
    examples: [
      { en:"Customers received a discount voucher after their purchase.", zh:"顧客購買後收到了一張折扣券。" }
    ]
  },
  {
    id: "w2323", english: "gravitate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ [ "受吸引","自然趨向" ] ] }
    ],
    examples: [
      { en:"Young professionals tend to gravitate toward companies with flexible work policies.", zh:"年輕專業人士傾向於被彈性工作政策的公司吸引。" }
    ]
  },
  {
    id: "w2324", english: "dictate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ [ "口述","聽寫" ], [ "規定","決定" ] ] }
    ],
    examples: [
      { en:"The manager dictated a memo to her assistant.", zh:"經理向她的助理口述了一份備忘錄。" },
      { en:"Market demand will dictate the company's production schedule.", zh:"市場需求將決定公司的生產排程。" }
    ]
  },
  {
    id: "w2325", english: "diminish", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vt", meaningGroups: [ [ "減少","縮小" ] ] },
      { pos: "vi", meaningGroups: [ [ "減少","變小" ] ] }
    ],
    examples: [
      { en:"The new policy diminished employees' overtime pay.", zh:"這項新政策減少了員工的加班費。" },
      { en:"Consumer confidence has diminished since the price hikes began.", zh:"自從漲價開始，消費者信心已經下降。" }
    ]
  },
  {
    id: "w2328", english: "adherence", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "nu", meaningGroups: [ [ "堅持","遵守" ] ] }
    ],
    examples: [
      { en:"Strict adherence to safety regulations is mandatory at the factory.", zh:"在這家工廠，嚴格遵守安全規定是強制性的。" }
    ]
  },
  {
    id: "w2329", english: "resonate", createdAt: new Date().toISOString(), wrongCount: 0, stats: null,
    posGroups: [
      { pos: "vi", meaningGroups: [ [ "引起共鳴","產生迴響" ] ] }
    ],
    examples: [
      { en:"The company's new slogan resonated well with younger customers.", zh:"這家公司的新標語很能引起年輕顧客的共鳴。" }
    ]
  }
]
```
