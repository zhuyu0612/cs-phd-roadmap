# 找论文、读论文的 Skills

更新：2026-10-21。主辅导者改为Codex，Zotero负责原文与批注。来源：[K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills)，本次GitHub API为53,384星，星数属于整个仓库。
固定版本：`593377bb048752abb0152deab9fbb1083a6087df`。安装位置在本机用户Skills目录，仓库记录方法与版本，不复制第三方源码。

| 优先级 | Skill | 用途与边界 |
|---|---|---|
| P0 | [paper-lookup](https://github.com/K-Dense-AI/scientific-agent-skills/tree/593377bb048752abb0152deab9fbb1083a6087df/skills/paper-lookup) | 检索文献和原始标识；不是全文阅读器 |
| P0 | [scientific-critical-thinking](https://github.com/K-Dense-AI/scientific-agent-skills/tree/593377bb048752abb0152deab9fbb1083a6087df/skills/scientific-critical-thinking) | 检查论证、方法、证据与局限；中文逐段辅导由下方阅读指令约束 |
| P1 | [literature-review](https://github.com/K-Dense-AI/scientific-agent-skills/tree/593377bb048752abb0152deab9fbb1083a6087df/skills/literature-review) | 本次新增；积累3—5篇后比较证据与研究问题，不对单篇强行跑系统综述 |
| P1 | [citation-management](https://github.com/K-Dense-AI/scientific-agent-skills/tree/593377bb048752abb0152deab9fbb1083a6087df/skills/citation-management) | 核验元信息、去重和BibTeX；不能代替检查引用是否支持正文论点 |

## 检索指令

> 使用paper-lookup。围绕工业过程质量预测检索，分别区分表格回归、序列到标量回归和未来时序预测。先列3组检索式，默认每组最多5篇；经典方法不限年份，近期工作重点查2024年以来。优先arXiv、OpenAlex/Semantic Scholar与正式发表页，记录日期、检索源和检索式。每篇给标题、作者、年份、DOI/arXiv、发表状态、原始链接、代码、相关理由、阅读难度。未知字段标为待核实。不要因标题有大模型就收录，也不要将API失败解释为没有论文。

## 阅读指令

> 使用scientific-critical-thinking，基于我提供或可取得的论文全文，用中文辅导。先核验题名与版本；只有摘要时先明确边界。第一轮只讲任务、输入输出、一句话方法和主结果。第二轮按方法小节解释符号、公式和张量形状，标注原文章节/图表定位；每次只讲一个模块并让我复述。第三轮检查数据划分、泄漏、基线公平性、消融、成本和局限。分开记录作者声称、实验支持和我的推断，不编造页码或未报告的实验。最后按精读模板形成笔记，并给一个适合初学者的最小复现任务。

## 引用指令

> 使用citation-management，核验已选论文的题名、作者、年份与DOI/arXiv。检查预印本和正式版是否重复；先查询元信息，再对照原始发表记录生成BibTeX，不能猜卷期页码。列出未解决字段与核验来源。

## 运行条件与验收

- 检索需要网络；paper-lookup附带脚本要求Python 3.11+。部分数据库的密钥可提升额度，缺少时先用可访问来源。
- 引用脚本要求requests；Google Scholar额外依赖可选，不作为主检索入口。
- 新安装Skills从下一轮对话可用。安装不代表数据库检索和PDF读取已通过测试。
- 成功标志：能追溯原始论文、区分摘要/全文、用自己的话解释方法，并明确不知道的内容。
- 首次检索时先做小规模验证，不发送公司或实验室未公开数据到文献服务。

## 本周入口

[两篇入门阅读与90分钟试行安排](reading-starter-20261021.md)。现有前三项保留，本次只新增literature-review；DeepPaperNote及其术语组件因当前基础与附加依赖暂不安装。星数不能代替适配与实际理解。
