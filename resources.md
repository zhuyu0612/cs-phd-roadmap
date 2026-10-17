# 资源汇总

> 所有链接集中在这里，README 里只放最常用的。

## 一、深度学习基础

| 资源 | 链接 | 用途 |
|---|---|---|
| 李沐《动手学深度学习》 | https://d2l.ai | 主线教材，B站"跟李沐学AI"配套视频 |
| 3Blue1Brown 深度学习 | B站搜索"3Blue1Brown 神经网络" | 建立直觉 |
| 3Blue1Brown 线代本质 | B站搜索"线性代数的本质" | 并行数学线 |
| CS231n | http://cs231n.stanford.edu | CV 基础（选学） |
| PyTorch 官方教程 | https://pytorch.org/tutorials | 60-min Blitz |

## 二、Transformer / 大模型

| 资源 | 链接 | 用途 |
|---|---|---|
| The Illustrated Transformer | https://jalammar.github.io/illustrated-transformer | 图解 Transformer，入门必读 |
| Karpathy nanoGPT | https://github.com/karpathy/nanoGPT | 手写 GPT |
| Karpathy "Let's build GPT" | YouTube / B站 | 视频版手写 |
| Attention is All You Need | https://arxiv.org/abs/1706.03762 | 原始论文 |
| Hugging Face Course | https://huggingface.co/learn | Transformers/PEFT/Accelerate |
| The Annotated Transformer | https://nlp.seas.harvard.edu/annotated-transformer | 逐行代码实现 |

## 三、时序预测大模型

| 资源 | 链接 | 用途 |
|---|---|---|
| Time-Series-Library (TSLib) | https://github.com/thuml/Time-Series-Library | 浙大，跑通所有 baseline |
| Chronos | https://github.com/amazon-science/chronos-forecasting | Amazon 时序基础模型 |
| TimesFM | https://github.com/google-research/timesfm | Google 时序基础模型 |
| Moirai (uni2ts) | https://github.com/SalesforceAIResearch/uni2ts | Salesforce 通用时序 |
| awesome-llm-time-series | https://github.com/lihuirui/awesome-llm-time-series-foundation-models-survey | 综述仓库，2026-09 更新 |
| 时序论文脉络 | Informer→Autoformer→FEDformer→PatchTST→iTransformer | 按顺序精读 |

## 四、AI4Science / 材料预测

| 资源 | 链接 | 用途 |
|---|---|---|
| DeePMD-kit | https://github.com/deepmodeling/deePMD-kit | 深度势能分子动力学 |
| DPA 大原子模型 | https://github.com/deepmodeling/dpa | 通用原子模型 |
| Uni-Mol | https://github.com/deepmodeling/uni-mol | 3D 分子表示学习 |
| Bohrium 玻尔 | https://bohrium.dp.tech | 深势科技一站式 AI4S 平台 |
| Materials Project | https://materialsproject.org | 材料数据库 |
| DeepModeling 社区 | https://github.com/deepmodeling | 鄂维南牵头 |

## 五、工具链

| 工具 | 链接 | 用途 |
|---|---|---|
| Weights & Biases | https://wandb.ai | 实验跟踪（学术免费） |
| Overleaf | https://overleaf.com | LaTeX 在线写作 |
| Zotero | https://zotero.org | 文献管理 |
| GitHub Student Pack | https://education.github.com/pack | 学生免费额度 |
| Connected Papers | https://connectedpapers.com | 论文关系图谱 |
| Papers with Code | https://paperswithcode.com | 论文+代码+SOTA |

## 六、985 CS 博士招生（2026 参考，每年更新）

| 院校 | 学院 | 链接 |
|---|---|---|
| 清华 | 人工智能学院 | https://collegeai.tsinghua.edu.cn |
| 北大 | 科学智能学院 | https://sai.pku.edu.cn |
| 上交 | 人工智能学院 | https://ai.sjtu.edu.cn |
| 浙大 | 计算机学院（TSLib 团队） | http://cs.zju.edu.cn |
| 中科大 | 计算机学院 | http://scs.ustc.edu.cn |
| 同济 | 人工智能学院 | https://cai.tongji.edu.cn |
| 华科 | 计算机学院 | http://cs.hust.edu.cn |
| 西交 | 计算机学院 | http://www.cs.xjtu.edu.cn |
| 哈工大 | 计算学部 | http://cs.hit.edu.cn |
| 南大 | 计算机学院（LAMDA） | http://cs.nju.edu.cn |

> ⚠️ 招生简章每年 9-12 月发布，每月 1 号刷一次目标校页面，把英语/论文/出身门槛抄进 Notion。

## 七、英语

| 资源 | 用途 |
|---|---|
| 墨墨背单词（已用） | 四级/六级/雅思词汇 |
| 四六级真题（星火/华研） | 只做真题，不做模拟 |
| 剑桥雅思真题 4-19 | 雅思备考 |
| BBC 6 Minute English | 听力精听 |
| The Economist | 阅读 |

## 八、AI 助手订阅方案（2026-10 核价，按阶段启用）

> 原则：先免费后付费；国内能直付的不折腾外币；每个阶段只加一个新订阅。

### P0 · 现在就配（月成本 ≈ 0~30 元）

| 工具 | 价格 | 用途 | 办理方式 |
|---|---|---|---|
| Gemini CLI 免费层 | ¥0 | D2L/PyTorch 答疑，1M 上下文吞整个 notebook | Google 账号 + 终端 npm 安装，详见 README/订阅指南 |
| GitHub Student Pack | ¥0 | 免费 Copilot Pro + 一堆云额度 | 东华 edu 邮箱申请 education.github.com/pack |
| DeepSeek API 按量 | 充 ¥20 起步 | 代码答疑备用，非高峰 1 元/M input | platform.deepseek.com 支付宝充值 |
| 智谱 GLM Coding Lite | ¥118/月（暂缓） | Claude Code 国内平替 | 跑 TSLib 大仓库时再开 |

### P1 · 2027 年初（Transformer 阶段）再评估

| 工具 | 价格 | 触发条件 |
|---|---|---|
| Claude Pro | $20/月（年付合 $17） | 开始写英文小论文 / 重度 Claude Code 使用 |
| Kimi 会员 / 豆包 | ¥49 / ¥68 | 不想折腾外币支付时的论文阅读替代 |

### 不订

- ChatGPT Plus + Perplexity 同时订（功能重叠）
- Cursor 订阅（学生 Copilot 免费够用）
- Claude Max / $100+ 档（个人学习用不到）

> ⚠️ 价格快照 2026-10，订阅前重看官方定价页；海外订阅记得关自动续费。
