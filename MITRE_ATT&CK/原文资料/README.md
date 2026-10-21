# 原文资料

MITRE ATT&CK Evaluations 官方页面原文，抓取于 **2026-10-21**（UTC），来源均为 evals.mitre.org。

## 获取方式

官网是单页应用（页面内容由脚本渲染），因此用无头浏览器（Chromium）打开页面，在渲染完成后：
- **`.pdf`**：页面打印版，保留排版；
- **`.txt`**：页面纯文本，便于搜索和对照。包含页眉导航、页脚等页面元素，未做删改。

未做任何翻译或改写。如需核对，以官网当前版本为准（页面可能更新）。

## 文件清单

| 编号 | 资料 | 原始地址 | 文件 |
|---|---|---|---|
| [1] | Enterprise 2026（ER8）说明与时间线 | https://evals.mitre.org/enterprise/er8/ | `1_ER8_Enterprise2026.txt`<br>`1_ER8_Enterprise2026_SCENARIO_1.pdf`<br>`1_ER8_Enterprise2026_SCENARIO_2.pdf` |
| [2] | 方法概览 | https://evals.mitre.org/methodology-overview/ | `2_Methodology_Overview.txt`<br>`2_Methodology_Overview_ALL_READERS.pdf`<br>`2_Methodology_Overview_FOR_CUSTOMERS.pdf`<br>`2_Methodology_Overview_FOR_VENDORS.pdf` |
| [3] | TES 与 IQI 评分细则（完整方法规范） | https://evals.mitre.org/methodology-specification/ | `3_Methodology_Specification.txt`<br>`3_Methodology_Specification.pdf` |
| [4] | 官方 FAQ | https://evals.mitre.org/FAQ/ | `4_FAQ.txt`<br>`4_FAQ.pdf` |

## 注意事项

1. **[1] 有两个场景标签页**：两份 PDF 的差别主要在"技术范围"部分（场景 1：56 个技术；场景 2：67 个技术）。txt 中依次包含两个标签页的全文，因此大部分内容重复。
2. **[2] 有三个读者标签页**（所有读者 / 客户 / 厂商），PDF 各一份，txt 中依次合并。
3. **[4] FAQ 是折叠式问答**，页面一次只展开一题：
   - `4_FAQ.txt`：逐题展开后合并，22 题完整；
   - `4_FAQ.pdf`：只是页面快照，**只有最后一题的答案是展开的**，完整答案以 txt 为准。
4. **[3] 评分细则**：官网没有单独的"TES 与 IQI 评分细则"页面，相关内容都在 Methodology Specification（完整方法规范）里，包括 TES、DQI、PQI、IQI 的公式、分级定义、权重和算例。
5. **未能获取**：[1] 页面上"Download JSON"按钮对应的技术范围文件（`er8_scenario_1.json` / `er8_scenario_2.json`），MITRE 的 CDN 返回 403（服务器端拒绝）。技术清单可以在 [1] 的页面正文中看到。
