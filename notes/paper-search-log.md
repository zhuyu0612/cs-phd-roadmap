# 论文检索日志

尚未执行主题检索；下方已有一次指定论文核验记录。复制下方记录块后填写，不把示例检索词当搜索结果。

## 检索批次

- 日期/Skill固定版本：
- 任务与范围（年份、数据形态、数量上限）：
- 数据源与完整检索式/筛选参数：
- 返回数量/已获取数量/是否分页：
- 保留与排除标准：
- 去重方式（DOI/arXiv与发表版本）：
- 原始链接/结果文件：
- 失败或覆盖不足：
- 下一步精读对象及理由：

## 2026-10-20：第一篇教学样例核验

- 目的：查指定论文2205.13504，不是系统综述或最新论文排名。
- arXiv API：GET https://export.arxiv.org/api/query ，参数id_list=2205.13504、max_results=1；本次HTTP 429，未取得API记录，不伪称解析成功。
- 回退：核对https://arxiv.org/abs/2205.13504 与正式发表页https://ojs.aaai.org/index.php/AAAI/article/view/26317 。正式页搜索式：site:ojs.aaai.org “Are Transformers Effective for Time Series Forecasting”。
- 获取：下载https://arxiv.org/pdf/2205.13504v3 ，实际打开15页，提取文本并渲染核对方法与表2。
- 数量：一篇指定论文；无分页，无穷尽性声明。
- 选择理由：能衔接线性回归，练习基线比较；不代表研究方向已确定。
- Zotero按标识符检索失败，改用RIS＋本地PDF导入。
