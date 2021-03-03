[中文版](#fip-0002-%E6%96%B0%E8%B5%84%E4%BA%A7---mdx)

[English Version](#fip-0002-new-asset---mdx)

# FIP-0002 新资产 - MDX

### 提案内容

FIlDA 支持MDX借贷。
MDX质押率初始为0%，后续调整将经过DAO投票决定。


--------------------------------


附 MDX 借贷功能补充资料，便于 FilDA DAO 投票者增加对提案的了解。

### 1，增加 MDX 借贷功能上线动因：

MDEX 在 HECO 生态中有重要的不可替代作用，因独有的经济模型，MDX 的迅速在 HECO 上占据了 HECO 头部的 DEX 的位置。增加 MDX 借贷功能，可以丰富 FilDA 资产种类，满足更多用户借贷需求。

### 2，增加新资产借贷风险提示：

#### 1）价格波动风险
初始 MDX 质押率设置为0，即用户可存入MDX，MDX 可以被借出，MDX 不能作为质押品。
MDX 作为借出品时，即用户质押其他资产借出 MDX 时，可能因 MDX 价格快速上涨导致贷款使用率上涨，若贷款使用率达到 100%将引发清算。
用户借出 MDX 时需要注意相关价格波动及风险。

#### 2) 安全性风险
DeFi 项目由于本身的去中心化特性，安全性始终是较大的风险点。
MDX 目前已通过慢雾 SlowMist，灵踪科技 FairyProof，Certik 三家安全公司的审计，同时在上线以来经过大规模资金的使用，合约和资产安全风险相对较低，

#### 3）流动性风险
MDX 目前流动性深度约4.5亿美金，流动性风险低
数据参考 

https://info.mdex.com/#/token/0x25d2e80cb6b86881fd7e07dd263fb79f4abe033c


### 3，MDEX 利率设置相关说明
MDX 的借款利率模型与其他资产相比将波动更大，需平衡存款人与借款人的利益，以下数值可能由团队根据实际情况变化。

#### 1）基础利率：参考 MDEX 的 boardroom 里的 MDX 质押 APY，MDX 借款的初始基础利率设定为50%，后续将随着 MDX在 FilDA 平台存借实际情况而调整。
MDEX Boardroom

链接 https://mdex.com/#/boardroom

#### 2）MDX 拐点利率模型中，第一阶梯拐点增长为 MDX 资金使用率为 50%，资金使用率每上升1%，利率上涨 15%，第二阶梯拐点MDX资金使用率为 90%，每使用率每上升 1%，利率上涨 30%

利率模型介绍

https://docs.filda.io/ye-wu-liu-cheng/li-lv-mo-xing-interest-model


### 4，MDX 币种风控限制
为降低系统风险、保护用户权益，以下情况可能触发存款限制，即用户不可再存入MDX，期间可取款MDX或借走MDX。
1）24小时内 MDX 价格上涨超过50%，触发存款限制。
2）目前设置MDX总供应量等值1000万美金上限，触发存款限制。



### MDEX概况

#### 1，MDEX 介绍
MDEX 是 HECO 上基于自动化做市机制的去中心化交易产品。
根据 Coinmarketcap 及 Coingecko数据，Mdex 日交易量排名全球第一，为第二名到第四名Uniswap, Pancakeswap，Sushiswap 的总和。

Top Decentralized Exchanges by Trading Volume

https://coinmarketcap.com/rankings/exchanges/dex/

https://www.coingecko.com/en/dex

#### 2，MDEX数据概览
https://mdex.com/#/




#### 3，MDX代币
1）代币交易情况
https://www.defibox.com/markets/mdex?chain=heco

https://mdex.com/#/

2）代币总量等
![](./images/mdx_cmc.png)


# FIP-0002 New asset - MDX

