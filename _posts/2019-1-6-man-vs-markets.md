---
layout:     post
title:       Man v.s. Markets (1)
date:       2019-1-6
summary:    
categories:  inve
---

* 書名：《Man v.s. Markets》金融市場比喻
* 作者：Paddy Hirsch
* 目標：了解金融市場的基本詞彙與遊戲規則



## 一。股票、股份與股權交易

* 股份：部分的所有權，又稱股票、股權
* 公開上市公司：將股權賣給市場上不認識的一堆投資人
* 私人股權企業：將股權賣給認識的特定人
* 投資標的：有很多種，股票是其中一種
* 交易所：NASDAQ、紐約證交所
  * 大公司的公開上市，通常是「在交易所掛牌」作為判斷標準
* 店頭市場：小公司私下賣，規範不嚴謹、接觸客戶少
* 不具流動性：舞池的領舞者沒有舞伴願意跟隨，只能站在一旁看
* 指數：由很多公司的股份組成，這些成分股可以是「不同交易所」掛牌的企業
  * 例如道瓊工業指數（大企業們）、標準普爾五百指數、NASDAQ 100 （科技公司們）
  * 就像一張清單，羅列了 costco, 頂好, 家樂福最暢銷的商品，追蹤這些商品的銷售總成績
* 波動性：從事交易的人少、缺乏「流動性」、由少數人決定走向
  * 就像舞池只有三個人，大家有很大的空間跳舞。如果舞池很擠、就沒辦法
  * 波動性小、成交量會下滑、交易者容易影響個股走向
  * 就像舞廳人很少、你可以帶著你的舞伴到處轉，「由交易者決定走向」
* 證券 v.s. 股票：證券（Security）用來證明持有人享有的某種特定權益的憑證。如股票、債券、本票、匯票、支票、保險單、存款單、借據、提貨單等各種票證單據都是證券。



* 多頭：看好某股的行情
* 空頭：看差某股的行情
* 斷頭：從事信用交易時，都會有一個「擔保維持率」，以融資為例，當投資人的保證金低於這個值，融資機構會在當天下午發出追繳令、通知投資人在「 2 日」內補繳差額，若投資人未能於限期補足差額，融資機構為確保其債權，會主動將客戶的股票賣出。
* 做多（long）：看漲。跟券商買進股票、持有一段時間，漲了後賣掉
  * 你手上只有 2 元。
  * 例如股票 A 目前 5 元。你買了一張、但你錢不夠只好跟券商借 3 元。
  * 股票 A 漲到 10 元，你把它賣掉
  * 拿回現金後，把 3 元還給券商
  * +3 -5 +10 -3 = +5, 共賺了 5 元
* 做空（short）：看跌。你手上沒有股票，先向券商借股票來賣出（付一筆保證金），以後再買回股票還給券商
  * 你手上有 19 元。
  * 例如股票 A 目前 10 元。你借一張、同時付保證金 9 元（抵押品）。
  * 把股票 A 賣掉。
  * 股票 A 跌到 5 元，此時買進（這稱為 回補空單 cover the short）
  * 還給券商、拿回保證金（這稱為 平倉 close the position）
  * -9 + 10 - 5 + 9 = +5 ，共賺了 5 元
* 無券放空：台股沒這個玩法，台股要放空、你要先借到券才能放空。
* 融券：屬於信用交易，向券商借股票的行為，需要付保證金 90% （9 元）
* 融資：屬於信用交易，向券商借錢的行為，需要自付 40 %（5 元中的 2 元，相當於**融資成數 60 %**）
* （以上的融券、融資尚未考慮利息問題，真實情況更複雜）
* 信用戶：想融資融券，你就得先開立「信用戶」



* 當沖：就是「當日沖銷」﹙Day Trading﹚，進階概念先跳過
* 追繳保證金通知（marginal call）
  * 融資，你明明是看漲的、但股價跌了
  * 當股價低於某值，就需要補保證金，不補的話就會被券商斷頭
* 擔保品追繳通知（collateral call）
  * 融券，你明明是看跌的、但股價漲了
  * 當股價高於某值，就需要補保證金，不補的話就會被券商斷頭



### 追繳保證金通知（融資）舉例

比如融資買進一張 100 塊的股票，融資成數六成

融資維持率 = 100 * 1000 (張) / 60000= 167%

X / 60000 = 120%，X = 72 塊，主管機關訂定的擔保維持率 = 120%

所以當股價低於 72 塊就需要補保證金，不補的話就會被斷頭。

所以，快速的算法是，融資的股票價錢 * 0.72 就是會被斷頭的價錢。

比如說，融資買 50 塊的股票，在 50 * 0.72 = 36 塊時會被斷頭。



- 套牢：買進股票後，股價下跌拾不得賣出，看好後市，或不甘賠錢買出者，就是被股票套牢

- 軋空：融資做空的投資人互相折磨。原因在於，原本看跌結果卻漲了。

  - 當股價上漲，為了不要賠太多、對股票的需求 UP，造成股價上升
  - 券商因應股價變高，就會做「擔保品追繳通知」
  - 其他賣空的投資人，被要求做更多擔保
  - 這些投資人為了不要賠太多、對股票的需求 UP，造成股價上升...
  - 越多投資人回補不了、就軋得越緊

  

- 普通股：擁有公司的比例有多少，持股人對董事會的決策有投票權。像是房子的磚瓦，重要缺一不可

- 優先股：股息固定（無論公司的盈利水平如何變化，該股息率不變）、配息優先、清償優先，順序在普通股的前面。沒有投票權。這像是房子的外觀裝潢、有價值但沒啥用。這是企業為了從投資人身上拿到資金的好管道

- 固定的股息收益降低了優先股的風險，然而，當公司盈利多時，相比普通股而言，優先股獲利更少，因此，普通股具有較高風險和較高收益的特徵。 

- 股票分割：目的在降低股票每股價格，使流通在外的股數比例增加，但股本總值不變。公司想創造更多股數給投資大眾、又不想改變現有投資人持股價值。通常在股價過高時公司會採取股票分割，使每股價格下降，以增加流通性（e.g., 小額投資人也買得起）

  - 原本市場上總共 3 股，每股 2000 元，三人各擁有一股
  - 分割後變成 6 股，每股 1000 元，三人各擁有兩股

- 稀釋股權：除了現有股份以外、另外發行新股。稀釋股份會讓股東不開心、因為手上股份價值變少了（EPS 會下降）

  - 原本市場上 6 股，現在再發行 6 新股，總共 12 股
  - 每股價格變成 500 元，三人仍是各擁有兩股，新的 6 股拿去市場賣

- 每股盈餘（EPS）：公司一年內總獲利、除以股份總數

- 次級發行：在第一次發行後，任何發行新股活動都稱之。次級發行讓企業能募得更多資金、但現有持股人會不開心，因為被稀釋股權了。

## 二。借貸、利率、債券市場

* 負債：又稱槓桿（**Leverage**）雖然賺得快但也賠得快
* 債券：借錢有很多方法。如果金額夠大、債券（**Bond**）市場是一種選擇
* 債權人：有權力討債，例如銀行把錢借出、賺利息
* 債務人：有義務還債，例如投資人借錢投資
* 本金（principle）、借貸期間（term）、到期日（maturity）、固定利率（interest rate）、條件書（term sheet, 借據）、收益率（yield）
* 本票（promissory note）：債券的用詞，用來承諾一定會付款的憑證
* 息票（coupon）：債券的用詞，指說「將定期支付利息的承諾」
* 債券和貸款大多很像。主要差別在於，債券市場通常涉及多個「放款人」（就是你這筆債、是跟很多人共同借的），而貸款則是一位借款人、一位放款人就解決了。債券甚至會需要「發債巡迴說明會」，跟每位投資人一個個談。
* 正常收益率：（首次定價）限定時間內的固定利息，以原始貸款的金額百分比來表示
* 當前收益率：「債券的年息」除以「息票債券價格」所計算出的收益率。$$i_c = \frac{C}{P_b}$$
* 次級市場：不影響原本「債務人」該還的還是要還、不多也不少，**負債額度不變**，只是還的對象變了。至於債權人之間會做「債券轉移」當前收益率可能改變
* 銀行貸款：放款速度快、需要擔保抵押
* 債券：無擔保、所以利息較高、而且時間較慢（需要統籌各投資人意見）



* 槓桿收購（LBO, Leverage Buyout）：一群人集資、不夠的跟銀行借、買進一家公司、上法讓一家公司轉虧為盈。
* 私募股權基金（private equity fund）：利用 LBO 的方式的基金。

  * 假設一間公司 1000 萬，共有十人，每人出 50 萬
  * 剩下 500 萬去跟銀行貸款，收購此公司
  * 成功經營起來（到可以支付利息的程度）後，假設賣出 2000 萬
  * 還銀行 500 萬，剩下 1500 萬給十人分，每人分到 150 萬、扣到成本一人淨賺 100 萬！
* 要說服銀行不容易，要拿出過往的管理顧問經歷、良好信用才可以。如果「違約」（default）銀行可以透過約定事項（covenant）把公司接收
* 聯貸（syndicate）：單一銀行難以應付這麼龐大的公司收購價格，風險太高、現金也不夠。所以通常會多個放款人一起來投資。
* 聯貸也可以在次級市場交易、就像債券一樣
* 浮動利率：基本利率（prime）加上邊際利率（margin）。例如浮動利率貸款是基本利率加上 3 % 的邊際利率時，假設此時基本利率是 5% ，那就必須付出 8%。但當基本利率跌到  1 % 就只需要付出 4%。
* 指數型利率：可怕的 2008 美國次貸危機房市泡沫。因為指數一開始利率很低、但是一成長上去就高到無力支付，所以很多中下階層不懂事就會買。


## References

1. [融資融券](https://www.sinotrade.com.tw/ec/wm/Article.aspx?ID=136&dirtype=706)

2. [揭開有著「富人遊戲」之稱、全球企業併購背後的神秘推手—私募股權基金](https://kopu.chat/2017/08/04/%E4%BB%80%E9%BA%BC%E6%98%AF%E7%A7%81%E5%8B%9F%E8%82%A1%E6%AC%8A%E5%9F%BA%E9%87%91/)

    