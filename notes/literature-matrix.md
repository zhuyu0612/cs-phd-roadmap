# 文献矩阵

状态：已核验3篇：2篇入门训练文章＋1篇DLinear教学样例，尚未完成实际课题的主题检索。每篇一行；没有全文标“摘要初筛”，未知信息标“待核实”。

| 题名与原始链接 | 年份/发表状态 | 任务/输入输出 | 数据与划分 | 方法/基线 | 指标与证据定位 | 局限 | 代码与版本 | 阅读状态/下一步 |
|---|---|---|---|---|---|---|---|---|
| [Are Transformers Effective for Time Series Forecasting?](https://ojs.aaai.org/index.php/AAAI/article/view/26317) | AAAI 2023；附件为2022 arXiv v3 | 历史序列→未来序列 | 9个预测基准；划分需逐项核对 | Linear/DLinear/NLinear；对照当时Transformer | MSE/MAE，v3 p5表2；窗口见p9 | 不能外推全部架构与工业任务 | cure-lab/LTSF-Linear；未运行 | AI导读已准备，待本人阅读 |
| [How to Read a Paper](https://svr-sk818-web.cl.cam.ac.uk/keshav/papers/07/paper-reading.pdf) | 2007原始发表；附件2016-02-17修订 | 阅读方法短文；无预测任务 | 不适用，不是实验论文 | 分层阅读建议；非算法比较 | PDF p1 §2.1、p2 §2.3 | 经验性方法，不证明普遍最优 | 不适用 | R01，AI导读已准备，待本人阅读 |
| [A Few Useful Things to Know about Machine Learning](https://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf) | CACM 2012，55(10):78–87 | 教学综述；分类举例 | 不是新的统一预测基准 | 模型/评价/优化；泛化意识 | 附件p2、p3–4；过拟合p4–5 | 历史入门材料，不代表当前最优方法 | 不适用，不派复现 | R02，AI导读已准备，待本人选读 |
