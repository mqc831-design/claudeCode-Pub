# MITRE ATT&CK 学习资料

> 发布方说明：以下参考资料均由 **MITRE** 的 **ATT&CK Evaluations** 项目发布（官网 evals.mitre.org）。
> ATT&CK 是 MITRE 维护的攻击战术与技术知识库（框架），本身不是发布机构。

## 一、参考资料与对应笔记

| 编号 | 资料 | 笔记文件 | 建议学习顺序 |
|---|---|---|---|
| [1] | Enterprise 2026（ER8）官方说明与时间线 | [01_ER8_Enterprise2026说明与时间线.md](01_ER8_Enterprise2026说明与时间线.md) | 3 |
| [2] | ATT&CK Evaluations 方法概览 | [02_方法概览.md](02_方法概览.md) | 1 |
| [3] | TES 与 IQI 评分细则 | [03_TES与IQI评分细则.md](03_TES与IQI评分细则.md) | 4 |
| [4] | ATT&CK Evaluations 官方 FAQ | [04_官方FAQ.md](04_官方FAQ.md) | 2 |

学习路线：先学 [2] 打基础，再看 [4] 了解评测的边界、防止误读，然后看 [1] 的本轮内容，最后啃 [3] 评分细则。

## 二、资料可信度说明（重要）

当前笔记**并非基于官方原文逐段整理**：整理时所在环境无法直接访问 evals.mitre.org，内容来自网页搜索摘要、第三方解读，以及往年评测的公开知识。笔记中按以下标记区分：

| 标记 | 含义 |
|---|---|
| 【官方】 | 来自 evals.mitre.org / mitre.org 页面（经搜索摘要转述，未读到全文） |
| 【第三方】 | 来自媒体、博客或厂商文章；厂商可能是参评方或利益相关方，需谨慎 |
| 【推断】 | 整理者的理解或推断，不是事实 |
| 【待核实】 | 来源矛盾或缺失，需要对照原文 |

## 三、目录结构

```
MITRE_ATT&CK/
├── README.md                          本文件：索引与说明
├── 01_ER8_Enterprise2026说明与时间线.md
├── 02_方法概览.md
├── 03_TES与IQI评分细则.md
├── 04_官方FAQ.md
├── 05_结果解读方法与待核实清单.md
└── 原文资料/                           官方原文（PDF + 纯文本，2026-10-21 抓取）
```

## 四、官方链接

- [1] https://evals.mitre.org/enterprise/er8/
- [2] https://evals.mitre.org/methodology-overview
- [3] https://evals.mitre.org/methodology-specification/ （完整方法规范，含 TES / DQI / PQI / IQI 评分细则）
- [4] https://evals.mitre.org/FAQ/
- 首页：https://evals.mitre.org/
- 上一轮 ER7（2025）：https://evals.mitre.org/enterprise/er7
