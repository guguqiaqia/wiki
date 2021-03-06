# 初链——打造承载未来商用去中心化应用的公链（三）
明白了区块链的朋友可能还是无法深入体会区块链在哪一块给人类社会带来了便捷，今天这一篇我想谈谈区块链工作的整体流程、初链和传统区块链的应用场景的对比以及初链是如何保持一致性的。在下一篇文章中我会重点谈谈初链的挖矿知识。
## 1 区块链工作的整体流程
我认为较为经典的区块链工作流程就如下图所示，说白了区块链的工作其实就是记录交易的一个过程，通过新交易的产生，节点通过广播获得交易信息，通过计算尝试加入新节点获取相应的币的一个过程，首先会产生一笔新交易，一笔新交易产生时，会先被广播到区块链网络中的其它参与节点，各节点将数笔新交易放进区块并且决定由谁来验证这些交易，各节点进行工作量证明的计算来决定谁可以验证交易，由最快算出结果的节点来验证交易。取得验证权的节点将区块广播给所有节点，各节点会验证并接上新区块
其他节点会确认这个区块所包含的交易是否有效，如果有效，接受该区块，此时区块才正式接上区块链，这样
交易才算完成，相信这样通俗的解释能够对区块链的工作有一定的了解，而我们初链提出来的整体就是一个高性能去中心化公开账本，同样也会记录所有的交易信息，也需要通过同样类似的工作流程完成工作，所以能够了解区块链的工作流程对认识Truechain也很有帮助。

![avatar](https://github.com/truechain/wiki/blob/master/analysis/truechain-consensus-core/img/3.1.png)

## 2 初链和传统区块链的应用场景的对比
区块链并不是一个凭空产生的技术，而是通过实践和完善进行不断的充实，想想而知，在联盟链和私链上该项技术得到了肯定和应用，但是在公链上还是一项不小的挑战，然而只有通过不断的寻求应用场景才能体现技术的可行性和存活期。区块链要想找到合适的应用场景其实并不难，区块链的特点是如何在不涉及第三方参与的情况下可以提供去中心化、安全不被篡改的服务，通过不断的实践分析区块链的应用场景有：金融、资源共享、投资管理、物联网和供应链等等。然而TrueChain在此基础上将应用场景设计到更多地领域包括：保险、医疗、游戏、公益、资产证券化、数字广告行业、小额支付、价值传输、数字版权等等，并且初链利用其节点的可扩充性与共识机制的高效性、安全性，可以更多地应用到移动数字汇票平台、证券交易等金融业态及物联网、供应链管理、产权追踪、数字证书等领域。我想通过表格对比更能突显TrueChain的场景优势。

![avatar](https://github.com/truechain/wiki/blob/master/analysis/truechain-consensus-core/img/3.2.png)

我想说的是每个区块链都有自己的特色，但是如何能够深入到更多领域中去也代表着一个区块链能够更好的生存下去，我想TrueChain在应用领域方面已经足够优先。同时我也期待初链能够继续扩展应用到更多的领域，将是区块链史上的一大创造。
## 3 一致性
初链是想打造一个高性能并且去中心化的公链，那么在这样的系统当中如何让多个节点保持一致性（这里的一致性指的是系统对外呈现的状态是否一致），那么为什么要保持一致性呢？我想学过计算机的人都应该知道，首先节点之间的网络通信并不是那么可靠的，因为还存在着网络的延迟和其他因素；其次节点之间也可能存在着错误，比如宕机；等等这些因素都可能造成系统不能正常完成工作，所以保持一致性是非常必要的。在传统的计算机网络当中采取的是通过某种共识算法来实现，当然创新离不开基础，我们的初链也就是采用我之前提到过很多次的混合共享机制来完成的。对于任何领域一致性是必须的，当然交易也是一样的，简单的买飞机票的事例就能说明，一张票被在一个机场卖出去就不能再被其他机场售卖，这就更加突出了一致性，在这里，一笔交易完成就不能重复交易也是一样的道理，所以初链的特色之一也是保证了良好的一致性。
## 说明
在这片文章当中我主要介绍了区块链工作的整体流程、初链和传统区块链的应用场景的对比，因为衡量一个技术是否能立足就是看它能够具有使用价值，我想通过我的一些分享大部分人对TrueChain有了更高的期待和思考，如开头所说，下一篇文章我会详细介绍区块链中的挖矿以及TrueChain中的挖矿，望能相互交流和分享。

作者：刘乐元
