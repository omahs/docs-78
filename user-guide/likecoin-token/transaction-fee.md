---
description: 目前轉帳 LikeCoin 每筆所需的手續費大約 0.059 LIKE，約等於 0.0006 美元，便宜到可被忽略，大家不用擔心
---

# LikeCoin 手續費

自2021年3月9日起，LikeCoin chain 秉承 Cosmos Hub 疊代更新同步調整 Gas 參數與 Cosmos Hub 其他項目看齊。Gas 用於表達每項動作和交易對區塊所造成的壓力，亦是運行和讀寫內容到區塊鏈所需要花費的勞動力的表達方式。不單止是 Cosmos Hub，其他區塊鏈平台如以太坊 \( Ethereum \) 亦使用 Gas 作為計算單位。

### 手續費的重要性

[LikeCoin chain](https://docs.like.co/v/zh/user-guide/liquid-democracy/likecoin-chain) 按照用戶執行不同類型的動作和交易 \( transaction – tx \) 所需要的程式運算步驟而衍生的 Gas 收取 Gas Fee，又可稱為 Transaction Fee 或手續費作為系統運作資源。假設毋須收取手續費而導致有人使用程式碼產生大量動作和交易佔據擠塞網絡，將嚴重影響 LikeCoin chain 的運作甚至造成惡意的無限迴圈 \( hostile infinite loops \)，是以手續費能幫助提升 LikeCoin chain 的安全性。

### 手續費的估算方式

手續費是按照執行每項動作和交易估算所需的 Gas 而計算。由於不同動作和交易進行的時候區塊鏈網絡環境都有所不同，以下為估算的手續費數值：

* [轉帳 \( LIKE pay \)](https://docs.like.co/v/zh/user-guide/likecoin-token/like-pay)：約 0.059 LIKE
* [委託](https://docs.like.co/v/zh/user-guide/liquid-democracy/delegation-of-likecoin)：約 0.19 LIKE
* [取回委託](https://docs.like.co/v/zh/user-guide/liquid-democracy/undelegation-of-likecoin)：約 0.32 LIKE 
* [領取收益](https://docs.like.co/v/zh/user-guide/liquid-democracy/delegation-of-likecoin#bu-zhou-san-tang-zhu-zuan-hui-bao-ba)： 約 1.25 LIKE

在 Liker Land 手機應用程式的錢包確認轉帳、委託、耶回委託或領取收益前都會顯示「詳細資料」，可點擊查看手續費的估算數值。

![](../../.gitbook/assets/transaction-fee.png)

### 重要事項

{% hint style="danger" %}
建議錢包時常預留 2 至 10 LikeCoin 作手續費之用。
{% endhint %}

因為你可能會在一些邊緣情況因為不夠錢支付手續費導致無法執行指令，例如：

* 無法把錢包中所有 LikeCoin 轉出，因為最少要留下少量 LIKE 支付手續費。如若錢包中只有 1 LIKE，最高只可轉帳約 0.94 LIKE 左右。
* 全數 LikeCoin 進行了委託後，無法領回，因為要留下少量 LIKE 支付委託操作的手續費。同樣道理，也無法把錢包中全數 LikeCoin 委託。
* 領取收益時必須確保錢包中有足夠手續費。

#### 手續費的詳盡計算方式可參考

> [談談轉帳 LikeCoin 的 gas 費用](https://matters.news/@edmond/%E8%AB%87%E8%AB%87%E8%BD%89%E5%B8%B3-like-coin-%E7%9A%84-gas-%E8%B2%BB%E7%94%A8-bafyreiaj5bbeu72rlt3bh5ukvaghzij6xhchswtckeza7kbzcqwbsuqqze)
