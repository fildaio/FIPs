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
Additional information on MDX  lending/borrowing is attached to facilitate FilDA DAO voters to decide.

### 1. Motivation of supporting MDX :

MDEX plays an important and irreplaceable role in the HECO ecology. Due to its unique economic model, MDX quickly occupied the position of HECO’s head of DEX on HECO. Adding the MDX lending function can enrich FilDA's asset types and meet the needs of users.

### 2. Add new asset loan risk reminder:

#### 1) Price fluctuation risk
The initial MDX pledge rate is set to 0%, that is, users can deposit MDX, MDX can be borrowed, but MDX cannot be used as mortage.
When MDX is used as a loan product, that is, when users pledge other assets to lend MDX, the rapid increase in the price of MDX may cause the loan utilization rate to rise. If the loan utilization rate reaches 100%, liquidation will be triggered.
Users need to pay attention to relevant price fluctuations and risks when lending MDX.

#### 2) Security risk
Due to the decentralized nature of the DeFi project, security is always a greater risk point.
MDX has passed the audits of SlowMist, FairyProof, and Certik. At the same time, it has undergone large-scale use of funds since its launch, and the security risks of contracts and assets are relatively low.

#### 3) Liquidity risk
MDX's current liquidity depth is about 450 million US dollars, with low liquidity risk
Data reference https://info.mdex.com/#/token/0x25d2e80cb6b86881fd7e07dd263fb79f4abe033c


### 3. Description of MDEX interest rate setting
MDX's borrowing interest rate model will fluctuate more than other assets. It is necessary to balance the interests of depositors and borrowers. The following values ​​may be changed by the team based on actual conditions.

#### 1) Basic interest rate: Refer to the MDX pledge APY in MDEX's boardroom. The initial basic interest rate of MDX loans is set at 50%, which will be adjusted in accordance with the actual situation of MDX's deposits on the FilDA platform.
MDEX Boardroom link https://mdex.com/#/boardroom

#### 2) In the MDX turning point interest rate model, the first tier turning point increases as the MDX capital utilization rate is 50%, and the capital utilization rate increases by 1%, and the interest rate rises 15%. The second tier turning point MDX capital utilization rate is 90%, per utilization rate For every 1% increase, the interest rate increases by 30%

Introduction to interest rate models
https://docs.filda.io/ye-wu-liu-cheng/li-lv-mo-xing-interest-model


#### 4. MDX currency risk control restrictions
In order to reduce system risks and protect users' rights and interests, the following conditions may trigger deposit restrictions, that is, users can no longer deposit MDX, and can withdraw or borrow MDX during the period.
1) The price of MDX has risen by more than 50% within 24 hours, triggering the deposit limit.
2) Currently, an upper limit of USD 10 million equivalent to the total supply of MDX is set, triggering the deposit limit.



### MDEX overview

#### 1. Introduction to MDEX
MDEX is a decentralized trading product based on an automated market-making mechanism on HECO.
According to coinmarketcap and coingecko data, Mdex's daily trading volume ranks first in the world, and is the sum of Uniswap, Pancakeswap, and sushiswap from second to fourth.

Top Decentralized Exchanges by Trading Volume
https://coinmarketcap.com/rankings/exchanges/dex/
https://www.coingecko.com/en/dex

#### 2. MDEX data overview
https://mdex.com/#/


#### 3. MDX tokens
1) Token transaction situation
https://www.defibox.com/markets/mdex?chain=heco

2) Total amount of tokens, etc.

![](./images/mdx_cmc.png)
