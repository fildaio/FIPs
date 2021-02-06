[中文版](#filda-dao-v10-%E4%B8%AD%E6%96%87%E7%89%88)

[English Version](#filda-dao-v1-english-version)


# FilDA DAO V1.0 (中文版)

FilDA DAO V1.0 参考了以太坊 DeFi 先驱们 AAVE 及 Curve 等 DAO 治理模型，在此致敬。

自2021年1月5日20点（UTC +8）上线以来，FilDA 存借资金规模高峰3.7亿美元，感谢社区用户的青睐和信任，也让 FilDA 开发团队感受到肩上沉甸甸的责任。

作为一个去中心化的借贷协议，存款用户希望获得更高利息，贷款用户希望支付更低利息，仅靠 FilDA 开发团队很难做出正确的判断，或者说“正确”定义一个普世标准。随着资金规模增长，为了 FilDA 能持续公平公正的运转，让 FilDA 开发团队决策尽量能代表大多数用户和资金的利益，让各方诉求可以被倾听，通过市场机制进行博弈实现最优解，这是 FilDA DAO 治理的核心目的。

FilDA 存贷用户、持有者、LP 提供者、开发团队有各自的权利与义务，伴随 FilDA 的发展，FilDA 重要决策将逐步通过 DAO 治理流程来重新定义和验证，由长期利益相关者来决定 FilDA 协议的长期发展方向。在此框架下，开发者团队负责维护系统安全可靠和持续运行，并不停创新和迭代产品，团队的使命是让 FilDA 成为 HECO 首选的成本低、效率高的用户友好型的借贷平台。社区通过 DAO 投票来完成对关键运营参数的设置，让资金使用者决定平衡点在哪里。



## FilDA DAO 治理框架

#### DAO Pool

DAO 治理的第一步是先支持 DAO V1.0投票，即将保险池 Insurance Pool 升级为 DAO Pool。FilDA 持有者将 FilDA 质押到 DAO Pool 后，将获得 DAO 治理的投票权，并仍将获得原保险池的 FilDA 激励。 DAO Pool 针对路线图及重大事项进行投票，第一次治理将投票是否通过 FilDA DAO。

FilDA 需要一群愿意长期一起成长、发展的伙伴来共同参与，希望大家共同走得更远。FilDA DAO V1.0将会是现阶段的初始原型，FilDA DAO V2.0或将参考更多成熟项目的 DAO 治理创新，比如 Curve，用户质押 FilDA 时可以选择质押周期，周期越长，其与协议共同承担的风险越大，则相应的 FilDA 也将激励长期同行者，相同数量的 FilDA 获得的投票权重越大、协议权益更大。

#### 创世治理

FilDA 创世治理第一步实现信息透明，信息透明是协议进化的基础，是各方利益平衡的润滑剂。创世团队一直秉持透明原则，让协议各项信息公开，也是火币 HECO 网络第一个上线就公开代币分配、挖矿参数、利率模型等的借贷协议。目前，FilDA 已经完成了包括 HBTC、USDT-HECO、HUSD、ETH、HT、ELA-HECO、HBCH、HBSV、HLTC、HDOT、HPT、HXTZ 13种资产，借贷总额峰值已经超过3.5亿美金。由于每一种资产的增减将都直接关系到 FilDA 参与存借用户的直接相关利益，未来 FilDA 产品的重大创新中包括不限于增加创新区币种借贷，增加机枪池等功能等、未来 FilDA 挖矿代币分配、挖矿参数、利率模型等重大调整将均通过 DAO 投票决定是否进行变更和调整。

#### 市场治理

FilDA 的市场模型基本采取参考行业业界头部的 DEFI 借贷协议，如 Compound、AAVE 等以及 CEFI 头部协议的相关参数标准。

为了倾听更多用户的声音并兼顾用户体验，FilDA 将逐步开放借贷市场的 DAO 治理，包括不限于资产种类、基础利率、利率模型、资产质押率、借贷参数投票治理。

#### 协议治理

以上未涉及到的针对协议各项参数调整，包括但不限于 DAO Pool 各类参数与 DAO 规则等相关参数通过 DAO 来治理。

#### 投票规则

任何人都可以在社区内广泛征集意见并充分讨论形成提案，在指定仓库（https://github.com/fildaio/FIPs）打开一个 pull request 来提交提案内容。在目前阶段，由 FilDA 开发团队提交提案。未来将逐步支持任一地址可提交提案，投票治理权重也与用户在 DAO 池锁定时长有关。

目前提案表决分为 Yes/No 两个选项，所有在 DAO 池锁定 FilDA 代币的用户均可参与投票。以 DAO 池代币数量作为票数（已申请提币的数量不计入）。投票结束以后，Yes 选项得票数超过 No 选项得票数，即表示通过，否则表示被拒绝。被拒绝的提案在一周（从此次发起时间计算）内不能再次发起投票。

#### DAO 池分红

为了激励 FilDA 用户参与 DAO 治理，平台将协议的保留资金池收入的20%每周分红给 DAO 池用户。





## FilDA DAO 治理下的多级风控体系

加密数字货币市场波动大，借贷协议若不做足风险控制，将给协议及用户带来损失。

FilDA DAO 的风控体系4层框架如下：

#### 资产治理框架

市场中的资产须在 HECO DEX 或 Huobi Global 中有足够的交易深度，可以被清算的资产才可以被质押。

#### 协议治理框架

FilDA 上线初期为了控制风险，并为了保护用户财产安全，设置的资产质押率仅为10%，在平稳发展一段时期后，FilDA 才参考 Huobi Global 来调整质押率，且平均质押率均低于市场头部前三交易所和头部 DeFi 借贷协议。质押率等参数将逐渐开放支持 DAO 治理。

#### 清算治理框架

FilDA 清算市场完全开放，代码开源，文档开放，任何链上清算合约均可以在规则内进行清算，让市场充分竞争，清算过程顺畅，避免风险。

#### DAO 池治理框架

DAO 池由原保险池升级而来，自愿选择参与 DAO 池的用户，享有 FilDA 挖矿、投票治理、分红权益，也有承担市场最后承保人的责任。当市场出现极端行情，市场流动性出现问题，存款用户遭受损失时，DAO 池的部分资产按比例将对储户进行适当补偿。DAO 治理可以设置比例参数，最大50%，最低20%。






 

# FilDA DAO V1 (English Version)

FilDA DAO V1 is a revision based on the DAO governance model of AAVE, Curve and other Defi pioneers on Ethereum mainchain. Firstly I would like to show my greatest appreciation and respect to the teams who created these pioneer projects.

After it was launched at 20:00（UTC +8）on Jan 5th, 2021, Filda has made phenomenal success and the deposit and loan assets reached a peak of $370 million. . Thank the community participants for their trust and engagement which has greatly motivated us to fulfill more ambitious goal. 

As a decentralized lending and borrowing platform, users who deposit assets prefer higher interest rates, and users who loan assets urge to have lower interest rates. It is difficult for the FilDA development team to make the best judgments or “correctly” define a universal standard. As the asset size grows, in order for FilDA to continue to operate fairly and impartially, it is necessary for the FilDA development team to make decisions that represent the interests of most users and their funds as much as possible, so that the appeals of all parties can be consideredThis requires a market mechanism to find an optimal solution, which is the core purpose of FilDA DAO governance.

FilDA deposit and loan users, holders, LP providers, and development teams have their respective rights and obligations. With the development of FilDA, important decisions of FilDA will gradually be redefined and verified through the DAO governance process. In another word,the FilDA holders will decide the long term development strategy for FilDA. . With this governance framework, the development team is responsible for system maintenance to ensure the safe, reliable and sustainable operation, and provide more innovative and iterating products. The team is committed to make FilDA the top one DeFi platform on Heco with low-cost,high-efficiency and high user-friendliness. The community decides the setting of key operating parameters through DAO voting.



## FilDA DAO governance framework



#### DAO Pool

The first step in DAO governance is to implement DAO V1.0 that upgrades the Insurance Pool to DAO Pool. After FilDA holders stakeFilDA to the DAO Pool, they will get voting power in DAO governance while still receiving the FilDA incentives from the original insurance pool. DAO Pool will vote for the roadmap and major decisions in the future. The first decision to vote is whether to pass FilDA DAO.

FilDA welcomes any members or paties who are willing to grow and develop with us to achieve further success.. FilDA DAO V1.0 will be the initial prototype at this stage. FilDA DAO V2.0 may refer to the DAO governance models of more mature projects, such as Curve. Users can choose the pledge period when they pledge Filda. The longer the period, the more risk the users take as the protocol does, in which the users obtain more Filda as the incentives and also have more voting power for each Filda. 



#### Genesis governance

The first step in FilDA creation governance is to achieve information transparency. Information transparency is the cornerstone for protocol evolution and the lubricant for balancing the interests of all parties. The genesis team has always adhered to the principle of transparency to release all the information about the protocol. It is also the first Defi platform on the HECO network to disclose token distribution, mining parameters, interest rate models, etc. At present, FilDA has added 13 assets including HBTC, USDT-HECO, HUSD, ETH, HT, ELA-HECO, HBCH, HBSV, HLTC, HDOT, HPT, HXTZ. peak TVL has exceeded US$350 million. Since the increase or decrease of each asset will directly affect the interests of FilDA's participants who deposit or loan these assets.the major innovations of FilDA's products in the future include but are not limited to the features such as token lending in the innovation zone, and machine gun pool . In the future, major adjustments such as the distribution of mining tokens, mining parameters, and interest rate models will all be decided by DAO.



#### Market governance

The market model of FilDA basically refers to the parameters setting of the top DeFi projects in this space such as Compound, AAVE, etc.

Considering both user needs and user experience , FilDA will gradually launch the DAO governance mechanism that includes but , but not limited to asset types, base interest rates, interest rate models, and asset pledge rates, etc.



#### Protocol governance

The adjustments to the parameters of the protocol that are not mentioned above, including but not limited to various parameters about DAP Pool and other related parameters are governed by DAO.



#### Voting Rules

Anyone can collect opinions from the community and createa proposal. Please submit the proposal using a pull request in this repository (https://github.com/fildaio/FIPs). At this point, the FilDA development team submits the proposal. As planned in the future, you can use any address to submit a proposal. The voting power is also related to the length of time the user locks their assets in the DAO pool.

There are currently two options for voting on the proposal:Yes/No. All users who lock FilDA tokens in the DAO pool can vote for the proposal. . The number of tokens in the DAO pool is used as the number of votes ( withdrawals is not counted). After the voting is over, if the number of votes for the Yes option exceeds the number of votes for the No option, it means that the proposal is passed, otherwise the proposal is rejected. A rejected proposal cannot be voted again within one week (calculated from the time when the proposal is submitted).



#### DAO Pool Dividend

In order to incentivize FilDA users to participate in DAO governance, the platform will distribute 20% of reserved platform income to DAO pool users every week.



##Multi-level risk control system under the governance of FilDA DAO

The crypto market is volatile, and if the protocoldoes not implement sufficient risk control, it can cause losses to both the protocol and users.FilDA's risk control system has a four-layer framework as follows:



#### Asset governance framework

The assets in the market must have sufficient trading depth in HECO DEX or Huobi Global, and the assets that can be liquidated can be pledged.



#### Governance framework for pledge rate selection

In the initial stage of FilDA’s launch, in order to control risks and protect user property safety, the asset pledge rate was only 10%. After a period of steady operation, FilDA adjusted the pledge rate with reference to Huobi Global, and the average pledge rate was lower than that of the top 3 exchanges as well as top Defi projects. Parameters such as pledge rate will gradually open toDAO governance.



#### Liquidation governance framework

The FilDA liquidation market is completely open, the code is open source, and the documents are open. Any on-chain liquidation contract can be processed within the rules to ensure fair market competition, smooth liquidation process and minimum risk. 



#### DAO Pool Governance Framework

The DAO pool is upgraded from the original insurance pool. Users who voluntarily choose to participate in the DAO pool enjoy the rights of FilDA mining, voting governance, and dividends, as well as the liability as of the final insurer in the market. For extreme market conditions andmarket liquidity problems, if deposit users suffer losses, part of the assets of the DAO pool will compensate depositors with a specific proportion. DAO governance can set proportion parameters, the maximum is 50%, and the minimum is 20%.


 

 
