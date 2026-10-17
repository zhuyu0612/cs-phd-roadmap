# CS PhD Roadmap · 时序大模型 + AI4S 方向

> 东华大学 材料与化工专硕 → 目标 985 计算机博士
> 方向：时序预测大模型 / AI for Science 材料性能预测
> 维护者：祝宇 · 始于 2026-10

这个仓库记录我从"材化专硕"跨到"985 CS 博士"的完整学习路径：路线图、论文精读笔记、复现代码、每周日志。

---

## 🎯 总目标

- **终点**：985 高校计算机博士（申请考核制），方向 = 时序预测大模型 + AI4S 材料/工业性能预测
- **硬通货**：研二上（2027-12 前）投出第一篇英文一作小论文（CCF-B 会议 / SCI 二区）
- **英语**：CET-4 425（2026-12）→ CET-6 425（2027-06）→ 雅思 6.0+（2027 暑假）
- **大论文**：《基于深度学习的 XXX 性能预测》——第 3/4 章拆成小论文，一鱼两吃

---

## 📅 四阶段路线图

### 阶段 1 · 基础重建（2026-10 ~ 2026-12）

- [ ] 李沐《动手学深度学习》PyTorch 版 Ch1-8（B站"跟李沐学AI" + d2l.ai）
- [ ] PyTorch 熟练：手写 CNN/RNN，训 CIFAR-10 到 85%
- [ ] 并行数学线：3Blue1Brown《线性代数的本质》《微积分的本质》
- [ ] Linux + Git + SSH + tmux 基础（能用实验室服务器）
- [ ] LaTeX（Overleaf）入门
- [ ] CET-4 冲 425（墨墨背单词 + 真题，12 月考试）

### 阶段 2 · Transformer 核心（2027-01 ~ 2027-03）

- [ ] 《The Illustrated Transformer》精读
- [ ] Karpathy "Let's build GPT from scratch" 手写 nanoGPT
- [ ] 精读《Attention is All You Need》
- [ ] Hugging Face Transformers / PEFT / Accelerate 官方教程
- [ ] 时序入门：Informer → Autoformer → PatchTST → iTransformer 论文精读
- [ ] CET-6 词汇打底

### 阶段 3 · 方向专项（2027-04 ~ 2027-09）

- [ ] 跑通 Time-Series-Library（TSLib）所有 baseline
- [ ] 微调时序基础模型：Chronos / TimesFM / Moirai（至少 1 个）
- [ ] AI4S 选修：DeePMD-kit / DPA / Uni-Mol
- [ ] Weights & Biases 实验跟踪
- [ ] 开题报告（LaTeX）+ 开题答辩
- [ ] 主实验：对比 + 消融
- [ ] CET-6 冲 425（6 月考试）

### 阶段 4 · 科研产出（2027-09 ~ 2028-06）

- [ ] 小论文 A 写作 + 投稿
- [ ] 小论文 B（系统/应用）投稿
- [ ] 大论文初稿（整合小论文 A+B）
- [ ] 联系博导（2028-03 起）+ 研究计划书（5000 字）
- [ ] 雅思首考 6.0+

---

## 📁 仓库结构

```
cs-phd-roadmap/
├── README.md              ← 你在这里（总路线图）
├── notes/                 ← 论文精读笔记（每篇一个 .md）
│   └── paper-note-template.md
├── code/                  ← 复现的项目（每个项目一个子目录）
├── log/                   ← 每周日志
│   └── week-template.md
└── resources.md           ← 资源链接汇总
```

---

## 🔗 核心资源

### 时序大模型
- Time-Series-Library (TSLib): https://github.com/thuml/Time-Series-Library
- Chronos: https://github.com/amazon-science/chronos-forecasting
- TimesFM: https://github.com/google-research/timesfm
- Moirai (uni2ts): https://github.com/SalesforceAIResearch/uni2ts

### AI4Science
- DeePMD-kit: https://github.com/deepmodeling/deePMD-kit
- Uni-Mol: https://github.com/deepmodeling/uni-mol
- Materials Project: https://materialsproject.org

### 学习
- 李沐《动手学深度学习》: https://d2l.ai （B站"跟李沐学AI"）
- Karpathy nanoGPT: https://github.com/karpathy/nanoGPT
- The Illustrated Transformer: https://jalammar.github.io/illustrated-transformer
- 3Blue1Brown 线代本质: B站搜索

---

## 📈 进度日志

| 周次 | 日期 | 完成 | 卡点 | 下周 |
|---|---|---|---|---|
| W1 | 2026-10-17 ~ | 配 SSH / 建 GitHub 仓库 / 首次 push | | |

（每周日更新，详细见 `log/`）
