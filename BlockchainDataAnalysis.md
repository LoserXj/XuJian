# 区块链和数据分析
## 研究内容
随着区块链的发展，区块链规模越来越庞大，对区块链中的交易等数据的分析能更好的了解和管理区块链网络。
目前有一些研究聚焦于使用图神经网络（GNN等）方法对区块链网络进行建模分析，但目前大多数研究还停留在使用静态图的阶段，没有同时考虑区块链的不断增长的动态性。
基于此，我们考虑使用动态图的方式对区块链进行建模、交易模式分析及可视化。
## 相关论文
1. 综述：Blockchain Data Analysis from the Perspective of Complex Networks: Overview : https://ieeexplore.ieee.org/document/9837004
2. 综述：A Survey on Blockchain Data Analysis： https://ieeexplore.ieee.org/document/9529901
3. 综述：A Survey on Blockchain Anomaly Detection Using Data Mining Techniques： https://link.springer.com/chapter/10.1007/978-981-15-2777-7_40#Sec3
4. 论文：Anti-Money Laundering in Bitcoin: Experimenting with Graph Convolutional Networks for Financial Forensics：https://arxiv.org/abs/1908.02591 ，论文代码：https://github.com/Rufaim/EvolveGCN (tensorflow版本), https://github.com/advaitrane/GCN_Elliptic-Dataset (pytorch版本)
## 图神经网络
1. 李毅宏深度学习(p30,p31)：https://www.bilibili.com/video/BV1m3411p7wD?p=30&vd_source=3fc2ca25dd07964a42b87b158d07eeed
2. 图神经网络论文解读：https://www.bilibili.com/video/BV1iT4y1d7zP?spm_id_from=333.337.search-card.all.click&vd_source=3fc2ca25dd07964a42b87b158d07eeed

# 实验
## 数据集(选择其中一到两个，优先考虑第一个)
1. *http://xblock.pro/#/dataset/6
2. http://xblock.pro/#/dataset/13
3. http://xblock.pro/#/dataset/9
4. http://xblock.pro/#/dataset/7
## Baseline模型
1. ML分类模型
    - KNN
    - Random Forests
    - Decision Tree
    - SVM
    - Logistic Regression
2. 图网络
    - GCN
    - E-GCN
3. 聚类分析及可视化
## 性能指标
1. AUC
2. Recall
3. Precision
4. F1-Score
## 参考文献
1. *Supervised learning model for identifying illegal activities in Bitcoin
2. Phishing Scam Detection on Ethereum: Towards Financial Security for Blockchain Ecosystem
3. TTAGN: Temporal Transaction Aggregation Graph Network for Ethereum Phishing Scams Detection
4. Phishing Scams Detection in Ethereum Transaction Network
5. T-EDGE: Temporal WEighted MultiDiGraph Embedding for Ethereum Transaction Network Analysis
6. *Anti-Money Laundering in Bitcoin: Experimenting with Graph Convolutional Networks for Financial Forensics

# 论文写作
参考论文3(TTAGN)的格式
## 1.Introduction
1. 区块链介绍，以太坊介绍
2. 钓鱼检测( Phishing Scams Detection)很重要，会造成什么危害
3. 现有钓鱼工作总结
4. 本文的工作
## 2.Problem Definition
1. 问题定义
2. 符号定义
## 3. Model
## 4.Experiments
1. 数据集介绍
2. baseline模型介绍
3. 实验结果展示
4. 实验结果分析
## 5.Conclusion
1. 对本文工作总结
2. 存在的问题
3. 未来改进的方向

# 计划安排
## 0929
1. 开题报告和PPT
2. 下载数据集并进行初步简单分析
    - 数据集的构成，
    - 有多少个节点，多少条边，有多少个正样本，多少个负样本
    - 每个节点有哪些属性，时间跨度
    - 将分析结果上传到github
3. 使用基本的ML模型进行分类
4. 特征工程
5. 聚类分析及可视化
6. 使用图网络分类