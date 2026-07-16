# 红外焊接文献综述

> 本仓库整理了 5 篇红外焊接（Infrared Soldering）领域文献的结构化阅读笔记与横向对比矩阵，用于课题组汇报。

## 📋 仓库内容

| 文件 | 说明 |
|------|------|
| [`matrix.md`](./matrix.md) | **文献对比矩阵** - 5 篇论文 × 9 维度的横向对比，含 LaTeX 公式 |

## 📊 对比矩阵预览

矩阵涵盖以下 9 个维度：

1. **基础信息** - 标题、作者、期刊、DOI、分区、机构
2. **核心研究问题** - 研究缺口与假设
3. **理论视角/机制** - 物理原理与理论框架
4. **研究方法** - 实验设计、设备、参数
5. **关键变量** - 自变量、因变量、控制变量、材料体系
6. **核心结论** - 具体数据与效应量
7. **批判/局限** - 作者声明与推断局限
8. **情境/背景** - 应用领域与前序工作
9. **定位/对比** - 5 篇论文间的关联与定位

👉 **[点击查看完整对比矩阵 ->](./matrix.md)**

## 📚 收录论文

| # | 简称 | 标题 | 期刊 | 年份 | 分区 |
|---|------|------|------|------|------|
| P1 | ADRC原型 | A prototype for infrared soldering of electronic devices using the active disturbance rejection control structure | Engineering Research Express | 2025 | ESCI Q3, IF=1.8 |
| P2 | 红外热源对比 | Comparative Effectiveness of Infrared Heat Sources for Mounting and Dismounting Electronic Modules | Surf. Eng. Appl. Electrochem. | 2017 | SCIE Q4, IF=0.7, EI |
| P3 | 热流方向 | Influence of heat flow direction on solder ball interfacial layer | Journal of Electrical Engineering | 2018 | SCIE Q4, IF=0.8, EI |
| P4 | FPCB台式炉 | Investigations of Infrared Desktop Reflow Oven with FPCB Substrate during Reflow Soldering Process | Metals | 2021 | SCIE Q2, IF=2.5, EI |
| P5 | 可变辐照掩模 | The effect of variable irradiation mask in Focused Infrared Light Soldering Systems for electronic components | Optik | 2021 | EI |

## 🔢 公式渲染说明

本文档中的数学公式使用 LaTeX 语法。在 GitHub 上：

- 行内公式：`` $`E = mc^2`$ `` -> $`E = mc^2`$
- 行间公式：`$$\frac{dT}{dt} = q$$` -> $$\frac{dT}{dt} = q$$

> ⚠️ GitHub 对**未登录用户**可能不渲染公式。如果公式显示为源码，请登录 GitHub 账号后刷新。

## 🔗 论文关联图

```
P2 热源选型基石 (2017)
  │
  ├──-> P5 光学整形/VIM (2021) ──-> P1 闭环控制/ADRC (2025)
  │         (UABC研究组)              (UABC研究组)
  │
  ├──-> P3 热流方向/IMC (2018)    P4 FPCB台式炉/CFD (2021)
  │    (微观组织互补)              (炉膛级系统建模)
```

- **P1 ↔ P5**：同属墨西哥 UABC 研究组，P1 是 P5 的后续（增加闭环控制）
- **P2 -> P5**：P2 指出卤素灯不均问题，P5 用光学匀化器+VIM 解决
- **P2 -> P3**：P3 使用陶瓷加热器，间接采用 P2 的均匀性结论
- **P3 ↔ P4**：P3 指出顶部加热 IMC 最厚，暗示 P4 可考虑增加底部加热

## 📅 更新日志

- 2026-07-16：使用 md2github-matrix skill 重新分析全部 5 篇文献，更新矩阵内容（146个公式，9维度全覆盖）
- 2026-07-15：初始版本，5 篇文献矩阵 + 阅读笔记
