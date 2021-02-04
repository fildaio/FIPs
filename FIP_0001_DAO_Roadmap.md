

[中文版](#filda-dao-v1-%E4%B8%AD%E6%96%87%E7%89%88)

[English Version](#filda-dao-v1-english-version)


# FilDA DAO V1.0 (中文版)

FilDA DAO V1.0 参考了以太坊 DeFi 先驱们AAVE及Curve等 DAO 治理模型，在此致敬。

## 愿景

自2021年1月5日20点（UTC +8）上线以来，FilDA存借资金规模高峰3.7亿美元，感谢社区用户的青睐和信任，也让 FilDA 开发团队感受到肩上沉甸甸的责任。

作为一个去中心化的借贷协议，存款用户希望获得更高利息，贷款用户希望支付更低利息，仅靠 FilDA 开发团队很难做出正确的判断，或者说“正确”定义一个普世标准。随着资金规模增长，为了 FilDA 能持续公平公正的运转，让 FilDA 开发团队决策尽量能代表大多数用户和资金的利益，让各方诉求可以被倾听，通过市场机制进行博弈实现最优解，这是FilDA DAO治理的核心目的。

FilDA 存贷用户、持有者、LP 提供者、开发团队有各自的权利与义务，伴随FilDA的发展，FilDA重要决策将逐步通过DAO治理流程来重新定义和验证，由长期利益相关者来决定FilDA协议的长期发展方向。在此框架下，开发者团队负责维护系统安全可靠和持续运行，并不停创新和迭代产品。团队的愿景是让 FilDA 成为 HECO 首选的成本低、效率高的用户友好型的借贷平台。社区通过 DAO 投票来完成对关键运营参数的设置，让资金使用者决定平衡点在哪里。

## FilDA DAO 治理框架

#### DAO Pool

​      DAO治理的第一步是先支持 DAO V1.0投票，即将保险池 Insurance Pool 升级为 DAO Pool。FilDA 持有者将FilDA质押到 DAO Pool 后，将获得 DAO 治理的投票权，并仍将获得原保险池的 FilDA 激励。 DAO Pool 针对路线图进行投票及重大事项的投票，第一次治理将投票是否通过FilDA DAO。

FilDA 需要一群愿意长期一起成长、发展的伙伴来共同参与，希望大家共同走得更远。FilDA DAO V1.0将会是现阶段的初始原型，FilDA DAO V2.0或将参考更多成熟项目的 DAO 治理创新，比如 Curve，用户质押FilDA时可以选择质押周期，周期越长，其与协议共同承担的风险越大，则相应的FilDA也将激励长期同行者，相同数量的FilDA获得的投票权重越大、协议权益更大。

#### 创世治理

FilDA创世治理第一步实现信息透明，信息透明是协议进化的基础，是各方利益平衡的润滑剂。创世团队一直秉持透明原则，让协议各项信息公开，也是火币HECO网络第一个上线就公开代币分配、挖矿参数、利率模型等的借贷协议。目前FilDA已经完成了包括HBTC、USDT-HECO、HUSD、ETH、HT、ELA-HECO、HBCH、HBSV、HLTC、HDOT、HPT、HXTZ 13种资产，借贷总额峰值已经超过3.5亿美金。由于每一种资产的增减将都直接关系到FilDA参与存借用户的直接相关利益，未来FilDA的产品的重大创新其中包括不限于增加创新区币种借贷，增加机枪池等功能等、未来FilDA挖矿代币分配、挖矿参数、利率模型等重大调整将均通过DAO投票决定是否进行变更和调整。

#### 市场治理

FilDA的市场模型基本采取参考行业业界头部的 DEFI 借贷协议,如Compound、AAVE等以及CEFI头部协议的相关参数标准。

为了倾听更多用户的声音并兼顾用户体验，FilDA将逐步开放借贷市场的 DAO 治理，包括不限于资产种类、基础利率、利率模型、资产质押率。借贷参数投票治理。

#### 协议治理

以上未涉及到的针对协议各项参数调整，包括但不限于DAO Pool各类参数与DAO规则等相关参数通过DAO来治理。

#### 投票规则

任何人都可以在社区内广泛征集意见并充分讨论形成提案，在指定仓库（https://github.com/fildaio/FIPs）打开一个pull request来提交提案内容。在目前阶段，由FilDA开发团队提交提案。未来将逐步支持任一地址可提交提案，投票治理权重也与用户在DAO池锁定时长有关。

目前提案表决分为Yes/No两个选项，所有在DAO池锁定FilDA代币的用户均可参与投票。以DAO池代币数量作为票数（已申请提币的数量不计入）。投票结束以后，Yes选项得票数超过No选项得票数，即表示通过，否则表示被拒绝。被拒绝的提案在一周（从此次发起时间计算）内不能再次发起投票。

#### DAO池分红

为了激励FilDA用户参与DAO治理，平台将协议的保留资金池收入的20%每周分红给DAO池用户。



## FilDA DAO治理下的多级风控体系

加密数字货币市场波动大，借贷协议若不做足风险控制，将给协议及用户带来损失。

FilDA DAO的风控体系3层框架如下：

#### 资产治理框架

市场中的资产须在HECO DEX或Huobi Global中有足够的交易深度，可以被清算的资产才可以被质押。

#### 协议治理框架

FilDA上线初期为了控制风险，并为了保护用户财产安全，设置的资产质押率仅为10%，在平稳发展一段时期后，FilDA才参考Huobi Global来调整质押率，且平均质押率均低于市场头部前三交易所和头部DEFI借贷协议。质押率等参数将逐渐开放支持DAO治理。

#### 清算治理框架

FilDA清算市场完全开放，代码开源，文档开放，任何链上清算合约均可以在规则内进行 清算，让市场充分竞争，清算过程顺畅，避免风险。

#### DAO池治理框架

DAO池由原保险池升级而来，自愿选择参与DAO池的用户，享有FilDA挖矿、投票治理、分红权益，也有承担市场最后承保人的责任。当市场出现极端行情，市场流动性出现问题，存款用户遭受损失时，DAO池的部分资产按比例将对储户进行适当补偿。DAO治理可以设置比例参数，最大50%，最低20%。





 

# FilDA DAO V1 (English Version)



FilDA DAO V1 is a reference to AAVE and Curve's DAO governance model, which is a tribute to the pioneers of Ethernet DeFi.

## Overview

Since the launch on January 5, 2021 at 20:00 (Beijing time), the platform has peaked at $370 million in deposited and loaned funds, which is far more than we expected. We are grateful for the favor and trust of our community users, but we also feel unparalleled pressure and responsibility.

As a lending platform, it is difficult for us to make the right judgments as deposit users want higher interest rates and loan users want to pay lower interest rates, and as the size of our funds grows, it makes us even more fearful to make decisions alone, or we will inevitably be limited by our own limitations and make wrong judgments, which may even lead to corruption.

In order to operate in a fair and just manner, FilDA can represent the interests of the majority of people and funds, so that the demands of all parties can be heard and the optimal solution can be achieved by playing the market mechanism, which is the core purpose of FilDA DAO governance.

FilDA holders, LP providers, and the development team have their own rights and obligations. Along with the gradual development of FilDA user platform, important decisions of FilDA platform will be redefined and verified through the DAO governance process, and the long-term stakeholders will decide the long-term development direction of FilDA protocol.

The team is responsible for maintaining a safe, reliable and continuously running system, and constantly innovating and iterating the product. The team's mission is to make FilDA the lowest cost and most efficient funding platform. The community accomplishes the setting of key operational parameters through DAO voting, allowing funding users to decide where the balance lies.

## FilDA DAO Governance Program:

#### DAO Pool

The first step in DAO governance is to first support DAO V1.0 voting, which upgrades the Insurance Pool to a DAO Pool. FilDA holders who pledge FilDA to the DAO Pool will receive voting rights for DAO governance and will still receive FilDA incentives from the original Insurance Pool. The DAO Pool votes on roadmaps and major matters against the roadmap, and the first governance will vote on whether to adopt the FilDA DAO.

FilDA needs a group of partners who are willing to grow and develop together for a long time, the further we look, the further we go together.FilDA DAO V1.0 will be the initial prototype at this stage, FilDA DAO V2.0 may refer to more mature projects of DAO governance innovation, such as Curve, users can choose the pledge period when pledging FilDA. The longer the cycle, the greater the risk it shares with the agreement, then the corresponding FilDA will also incentivize long-term peers, and the same number of FilDAs receive greater voting weight and greater agreement equity.

#### Genesis Governance

The first step of FilDA Genesis governance is to achieve information transparency, which is the basis for the evolution of the agreement and the lubricant for balancing the interests of all parties. The Genesis team has been upholding the principle of transparency and making all information of the agreement public. It is also the first lending agreement in the Firecoin HECO network to disclose token allocation, mining parameters, interest rate model, etc. when it is launched. Currently FilDA has completed 13 assets including HBTC, USDT-HECO, HUSD, ETH, HT, ELA-HECO, HBCH, HBSV, HLTC, HDOT, HPT, HXTZ, and the total current lending amount has exceeded $350 million. As the increase or decrease of each asset will be directly related to the direct relevant interests of FilDA participating deposit and debit users, the future major innovations of FilDA's products which include not limited to the increase of innovative zone coin lending, increase of machine gun pool and other functions, etc., the future FilDA mining token allocation, mining parameters, interest rate model and other major adjustments will all be decided through DAO voting whether to make changes and adjustments.

#### Market Governance

FilDA's market model basically takes reference to the industry's head DEFI lending protocols, such as Compound, AAVE and other relevant parameters of CEFI head protocols.

In order to listen to more users' voices and take into account the user experience, FilDA will gradually open up the DAO governance of the lending market, including but not limited to asset types, prime rates, interest rate models, asset pledge rates. Lending parameters voting governance.

#### Protocol Governance

The above is not involved in the adjustment of various parameters for the agreement, including but not limited to DAO Pool various parameters and DAO rules and other related parameters through DAO to governance.

#### Voting Rules

Anyone can open a PR in this repository to submit a proposal after a wide call for input and full discussion in the community. At this stage, the FilDA team will review the proposal content and submit it. After smooth operation and smooth process, the FilDA team will upgrade the system to support the community to submit proposals spontaneously.

At present, there are two options of Yes/No for proposal voting, and all users who have locked FilDA tokens in the DAO pool can participate in the voting. The number of tokens in the DAO pool will be used as the number of votes (the number of tokens that have been requested to be withdrawn will not be counted). After the vote is closed, the Yes option will be passed if the number of votes exceeds the number of votes for the No option, otherwise it will be rejected. Rejected proposals cannot be voted on again for one week (counting from the time of this launch).

#### DAO Pool Dividend

In order to incentivize FilDA users to participate in DAO governance while sharing in the growth of the platform, the platform will share 20% of the weekly revenue of the agreed reserved pool to the DAO pool users.



## FilDA DAO governance under a multi-level risk control system

The cryptocurrency market is volatile, and lending agreements that do not have adequate risk control will bring losses to the agreement and its users.

FilDAO's risk control system has a 3-tier framework as follows.

#### Asset Type Selection Governance Framework

Assets in the market must have sufficient trading depth in HECO DEX or Huobi Global to be liquidated before they can be pledged.

#### Pledge Rate Selection Governance Framework

At the beginning of FilDA's launch, in order to control risk and to protect users' property, the pledge rate of assets was set at 10% only. After a period of smooth development, FilDA adjusted the pledge rate by referring to Huobi Global, and the average pledge rate was lower than the top three exchanges and the top DEFI lending agreements at the head of the market.

#### FilDA DAO Governance Pool Framework

The FilDA DAO Governance Pool was upgraded from the original FilDA Insurance Pool. In the event of extreme market conditions, a portion of the DAO Governance Pool's assets (currently set at a maximum of 50%) will compensate depositors when they suffer a loss of principal.





 

 
