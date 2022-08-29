# 私钥管理

每位验证人需要使用如下两个地址私钥来管理验证人相关操作：
* Singer地址
* Owner地址


## Singer地址
Signer地址用于签名Bttc层区块、检查点和其他相关操作。为了保证上述签名操作能被执行，Signer地址的私钥必须保存在验证人节点的机器上。


Signer地址无法管理质押、奖励和委托相关操作。

验证人在TRON/BSC/Ethereum网络上的Signer地址需有一定数量的TRON/BSC/ETH，用来支付提交检查点交易的费用。


## Owner地址
Owner地址是用于在TRON网络上进行质押、追加质押、修改Signer地址、提取奖励等操作，所有通过Owner地址的交易都在TRON网络上进行。

Signer地址密钥保存在节点上，通常被认为是热钱包，而Owner地址密钥需要确保非常安全，由于不经常使用，通常被认为是冷钱包。 质押资金由Owner地址密钥控制。

Signer地址和Owner地址之间职责分离是为了确保在安全性和易用性之间作出的权衡。

这两个密钥都是与TRON 兼容地址。