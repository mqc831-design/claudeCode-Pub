# [1] Enterprise 2026（ER8）官方说明与时间线

> 官方页面：https://evals.mitre.org/enterprise/er8/
> 可信度标记说明见 [README](README.md)。

## 一、本轮概要

| 项目 | 内容 | 来源 / 可信度 |
|---|---|---|
| 攻击场景 | 以利益为目的的犯罪团伙手法（Financially Motivated Tradecraft）+ 中国背景的间谍组织手法（PRC Espionage Group Tradecraft） | 【官方】首页摘要 |
| 参评产品类型 | EDR、XDR、MDR、MSSP、SIEM、AI SOC，**使用同一套场景、同一套指标** | 【官方】 |
| 评分 | 首次引入统一量化分数 TES（详见 [03](03_TES与IQI评分细则.md)） | 【官方】 |
| 覆盖范围 | 终端、云、身份、邮件、Windows、Linux、混合环境 | 【第三方】FieldCISO |
| 报名截止 | 2026-04-30 | 【官方】 |
| 结果发布 | 2026 年 12 月 | 【官方】 |
| 当前状态 | ER8 页面有一处写"已完成"，首页又写"即将开始"，互相矛盾 | 【待核实】 |
| 参评厂商 | 未找到公开名单 | 【待核实】 |

## 二、与往年相比的变化

1. **合并评测类别**：往年企业产品和托管服务（MDR 等）是分开评测的，2026 合并为同一套评测。【官方】
2. **从二元判断转向质量评分**：不再只看"检测到 / 没检测到"，而是衡量告警质量、分析精度、平台速度、阻断时机、误报表现，并按技术的重要程度加权。【官方】
3. **首次给出分数**：这与往年 FAQ"不打分、不排名"的立场存在冲突，见 [04](04_官方FAQ.md)。

## 三、背景：上一轮 ER7（2025）

- 场景：以 Scattered Spider 为原型的场景 + Mustang Panda（中国背景的国家级组织）场景。【官方】
- 结果发布：2025-12-10。【第三方】SecurityWeek
- 参评厂商：Acronis、AhnLab、CrowdStrike、Cyberani、Cybereason、Cynet、ESET、Sophos、TrendAI、WatchGuard、WithSecure。【第三方】
- Microsoft、Palo Alto Networks、SentinelOne 退出了 2025 年评测；MITRE 表示会在 2026 年前重建厂商论坛。【第三方】Infosecurity Magazine

## 四、理解要点

- 【推断】ER8 的场景延续了 ER7"犯罪团伙 + 国家级间谍"两条线的思路。
- 场景主题决定了结果的适用面：如果你的威胁模型与这两类攻击者差别较大，结果的参考价值会下降。
- 某厂商没参加不等于能力差，只意味着没有可比数据。
