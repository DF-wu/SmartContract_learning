#  區塊鏈技術學習part2 ---solidity hello world
###### tags: `tutorials` `blockchain` `ethereum` `smart contract` `solidity`
> [name=WU D.F] 


> [time=Thu, Mar 26, 2020 10:21 AM]
> [TOC]

作者：廢物@dfder

> 沒有part1 除非我哪天想到回去補



## index

1. 取得錢包 
2. 測試網路
3. 取得測試網路之以太幣
4. Remix 簡介
5. 在Remix上撰寫solidity 之smart contract
6. hello world!
7. Smart Contract running 過程cost分析

---
### 1. 取得錢包

- [官方之錢包介紹頁面](https://ethereum.org/wallets/)
- ![Imgur](https://imgur.com/zHIOiXv.jpg)
- 何謂錢包
    > What is an Ethereum wallet, and which one should I use?
    >> Wallets are applications that make it easy to hold and send ETH, as well as interact with applications built on Ethereum.



- 目前最多人用的錢包似乎是 [MetaMask](https://metamask.io/)
    - 支援平台多 方便
    - 支援測試網路 (blockchain TESTNET)
    - ~~google教學最多最方便~~

- 我使用的是MetaMask的ChromeExtension
    - ![img](https://imgur.com/T7rV06v.jpg)



---

### 2. 測試網路
- [測試網路簡介](https://www.samsonhoi.com/677/blockchain-ethereum-testing-network)

>眾所周知，區塊鏈的其中一個特性是"不可篡改"，所以在將智能合約（Smart Contract）上鏈前，需要確保智能合約沒有任何問題，但我當時就出現一個迷思："如果我是一個區塊鏈的初學者，不可能第一次完美地就把智能合約寫好，肯定需要多次調試修改，如果直接上鏈，但又不能修改，怎麼辦？而且每次在以太坊上鏈都需要花費 Gas，完成一個智能合約豈不要浪費我很多錢，怎麼辦？" 放心，這些都能透過以太坊的測試網絡解決。

>>以太坊共有四個公開的測試網絡，目前仍在運行共有三個測試網絡（Testing Network，又簡稱 Testnets ）予所有開發者進行開發及測試，而且在這些測試網絡上鏈所需要用到的 Token，都可以很容易地獲得，而不需花費真金白銀去購買。
- 
- ![img](https://www.samsonhoi.com/wp-content/uploads/2018/10/testnets-ethereum-1024x733.png)
- 我用的網路[Rinkeby](https://www.rinkeby.io/#stats)

>由以太坊官方提供的測試網絡，於2017年4月啟動，Rinkeby 這個名字是以斯德哥爾摩的地鐵站命名的，使用了PoA(Clique PoA)的共識機制。以太坊團隊提供了Rinkeby的PoA共識機制文檔，所以在理論上任何以太坊錢包都可以按照這個文檔，從而兼容 Rinkeby 測試網絡。

| 共識機制 | 出塊時間 |
| -------- | -------- | 
| PoA(Clique PoA)     | 約15秒     |



| 優點 | 缺點| 
| -------- | -------- |
| 由於由可信的權威節點控制 Token 的供應，所以會對垃圾攻擊"免疫"    | 只支援 geth     | 

[Explorer](https://rinkeby.etherscan.io/)：找節點資料？~~trivago~~

[GitHub](https://github.com/ethereum/EIPs/issues/225)：開源Repo

[Token 來源](https://faucet.rinkeby.io/)：只能從這個網址獲得貨幣


    - ![Imgur](https://imgur.com/NhSY3BV.png)
    - ~~介面炫炮~~
    - 免費貨幣好拿(待會說明)
    - 多個錢包直接支援

- 在MetaMask錢包中切換至測試網路
    - ![Imgur](https://imgur.com/xd4Migv.png) 




---


### 3. 取得測試網路之以太幣

- 在rinkeby TESTNETS中 取得以太幣的方法相當簡單 
- ***僅能使用FB或twitter之貼文取得***
    1. 複製你的錢包Account address![](https://i.imgur.com/FTzxbdN.png)

    2. 在twitter或FB發出一篇含有你Account address的**公開**貼文 ![](https://i.imgur.com/4dZ6Gd0.png)

    3. 複製該貼文的URL (Direct link)
    4. [使用此網址](https://faucet.rinkeby.io/) 貼上![](https://i.imgur.com/3v3kzNe.png)

    5. **BANG!** ![](https://i.imgur.com/NrJ7ay5.png)
    6. ~~讓子彈飛一會兒~~讓區塊練計算這筆交易一下
    7. Magic!出現啦!~~我是有錢人啦~~ ![](https://i.imgur.com/ehMDH6I.png)
- 領貨幣有CD的喔 在Faucet頁面的取得按鈕即有說明多少貨幣有多少CD時間
    

---
### 4.




---
>Reference
>Smart Contract 開發 
>https://ithelp.ithome.com.tw/articles/10200900








