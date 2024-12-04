# awesome-zkevm

## 文章 - 视频

### Rollup

* [未完的Rollup指南](https://vitalik.ca/general/2021/01/05/rollup.html) - Vitalik 介绍 Rollup。
* [以Rollup为核心的以太坊路线图](https://ethereum-magicians.org/t/a-rollup-centric-ethereum-roadmap/4698) - Vitalik 提出的 Rollup 以太坊路线图。
* [Zk-Rollups如何工作](https://medium.com/fcats-blockchain-incubator/how-zk-rollups-work-8ac4d7155b0e) - Barry WhiteHat 介绍 Zk-Rollup 的工作原理。

### zkEVM

* [zkEVM](https://hackmd.io/@yezhang/S1_KMMbGt) - Scroll zkEVM 介绍。
* [zkEVM架构](https://twitter.com/LuozhuZhang/status/1538166119785111552?s=20&t=o9hnHeP1na00u6gldaxnCw) - Scroll 与 EF zkEVM架构分析。
* [ZKVerse：深入了解 Polygon Hermez 2.0](https://blog.polygon.technology/zkverse-deep-dive-into-polygon-hermez-2-0/) - 深入研究 Polygon Hermez zkEVM。
* [zkEVM电路算术化](https://www.youtube.com/watch?v=DT8g3veR17k&t=910s) - 解析 zkEVM 和 EVM 电路，Ye Zhang 讲解。
* [不同类型的ZK-EVM](https://vitalik.ca/general/2022/08/04/zkevm.html)

### zk硬件

* [零知识证明硬件加速](https://www.paradigm.xyz/2022/04/zk-hardware) - 专门为ZKP设计的硬件加速技术。

### 零知识证明

#### zk-SNARK

* [zk-SNARK简介与示例](https://media.consensys.net/introduction-to-zksnarks-with-examples-3283b554fc3b) - 通过示例了解 zk-SNARK。
* [为什么以及如何zk-SNARK工作](https://medium.com/@imolfar/why-and-how-zk-snark-works-1-introduction-the-medium-of-a-proof-d946e931160) - 深入讲解 zk-SNARK 工作机制。

#### Plonk

* [理解PLONK](https://vitalik.ca/general/2019/09/22/plonk.html)
* [ZK学习俱乐部 - Plonk与Zac Williamson](https://www.youtube.com/watch?v=NqrVcDuQ8hM)
* [PLONK中的多集检查与Plookup](https://hackmd.io/@arielg/ByFgSDA7D)

#### Halo2

* [Halo及其更多：探索增量验证与没有配对的SNARK](https://vitalik.ca/general/2021/11/05/halo.html)

## 资源 - 库与工具

### 早期Rollup实现

* [idn3 rollup](https://github.com/iden3/rollup) - iden3实现的rollup。
* [barryWhiteHat rollup](https://github.com/barryWhiteHat/roll_up) - BarryWhiteHat实现的第一个rollup。

### Scroll与Appliedzkp（PSE）

* [zkEVM规范](https://github.com/privacy-scaling-explorations/zkevm-specs)
* [zkEVM电路](https://github.com/privacy-scaling-explorations/zkevm-circuits)
* [zkEVM文档](https://privacy-scaling-explorations.github.io/zkevm-docs/)
* [Scroll架构](https://scroll.mirror.xyz/nDAbJbSIJdQIWqp9kn8J0MVS4s6pYBwHmK7keidQs-k)

### Polygon Hermez

* [Polygon Hermez zkEVM](https://github.com/0xPolygonHermez/zkevm-prover)
* [Hermez文档](https://docs.hermez.io/zkEVM/Overview/Overview/)

### Polygon Zero

* [Plonky2](https://github.com/mir-protocol/plonky2)

### zkSync

* [zkSync v1](https://github.com/matter-labs/zksync) - zkSync v1源代码。
* [compiler-solidity](https://github.com/matter-labs/compiler-solidity) - zkSync v2编译器。
* [zkSync v2门户](https://portal.zksync.io/) - zkSync v2水龙头，Goerli网络。

### StarkWare

* [Awesome-starknet](https://github.com/gakonst/awesome-starknet) - StarkNet资源汇总。
* [Warp：将Solidity转为Cairo](https://github.com/NethermindEth/warp)

### 零知识证明

* [Awesome-zkps](https://github.com/matter-labs/awesome-zero-knowledge-proofs) - 零知识证明资源汇总。

### Halo2

* [Halo2仓库](https://github.com/zcash/halo2)
* [Halo2文档](https://zcash.github.io/halo2/)
* [Halo2在PSE和Scroll中的应用](https://github.com/privacy-scaling-explorations/halo2)

### ZKP加速

* [supranational](https://github.com/supranational)
* [supranational - sppark](https://github.com/supranational/sppark)

## 不同解决方案

### 原生zkEVM

* [PSE（前身为appliedzkp）](https://github.com/privacy-scaling-explorations)
* [Scroll](https://scroll.io/)
* [Polygon Hermez](https://docs.hermez.io/zkEVM/Basic-Concepts/introduction/)
* [Polygon Zero](https://polygon.technology/solutions/polygon-zero/)

### 基于编译器的zkEVM

* [zkSync v2](https://blog.matter-labs.io/zksync-2-0-public-testnet-is-live-de870ba9632a)

### 基于转译器的zkEVM

* [StarkNet](https://medium.com/starkware/starknet-alpha-2-4aa116f0ecfc)
* [Miden](https://github.com/maticnetwork/miden)

### 其他

* [Consensys zkEVM](https://ethresear.ch/t/a-zk-evm-specification/11549)
* [Consensys zkEVM 2.0](https://ethresear.ch/t/a-zk-evm-specification-part-2/13903)
