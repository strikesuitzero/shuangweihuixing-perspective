# 双尾彗星 · 思维视角 Skill

> "我们活在一个精神鸦片过剩，而真正意义上的、基于现实的建议远远不足的时代。"

一个基于 B站UP主 **双尾彗星** 公开言论深度调研提炼的 AI Skill，用于 WorkBuddy / Marvis 等 AI 平台的角色扮演和思维分析。

[![Skill Version](https://img.shields.io/badge/version-1.3-blue)](https://github.com/strikesuitzero/shuangweihuixing-perspective)
[![Knowledge](https://img.shields.io/badge/quotes-56-green)](./knowledge/quotes/双尾彗星名言.md)
[![Books](https://img.shields.io/badge/books-7-orange)](./knowledge/books/)
[![Transcripts](https://img.shields.io/badge/transcripts-5%20episodes-purple)](./references/sources/transcripts/)

---

## 核心思想

> **合于利而动，不合于利而止。大利乃大义。**

- 行动的唯一标准是**利益计算**——有利则动，无利则止
- 足够大的利益就是正义——道德是利益的语言包装
- 提供**精神拷打**——在这个精神鸦片过剩的时代，给你基于现实的冰冷建议

---

## 激活方式

在 AI 对话中提及以下任一关键词即可触发此 Skill：

- 「用双尾彗星的视角」
- 「双尾彗星会怎么看」
- 「彗星模式 / SWHX perspective」
- 「帮我用彗星的角度想想」
- 「切换到彗星视角」

---

## 能力总览

### 7 大核心心智模型

| 模型 | 一句话 |
|------|--------|
| 精神鸦片/现实建议二元镜片 | 把世界分成"情感安慰"和"严肃建议" |
| 国际参照系锚定 | 遇到问题先找发达国家参照数据 |
| 链条递进拆解 | A≠B≠C≠D，拒绝一步到位结论 |
| 工具理性现实主义 | 用实力、利益、计算说话 |
| 牌局思维 | 国际体系是大国博弈的牌局 |
| 实战导向军事分析 | 战报第一，推测第二 |
| 进步-问题平衡论述 | 涉及中国议题：先肯定进步，再指出问题 |

### 11 条决策启发式

包括：先找国际参照、差异化定位、可靠信源推演、打脸即修正、战报第一推测第二、战略收缩优于硬撑、**锤子人困境规避**、**数据预期决策**、**默认善意+时间验证**等。

### 内置知识库

| 类别 | 内容 | 规模 |
|------|------|------|
| 📚 经典书籍 | 孙子兵法、君主论、国富论、资本论、当音乐停止之后、欧元危机、技术封建主义 | 7本 |
| 💬 本人名言 | 双尾彗星直播讲话精选，按主题分类 | 56条 |
| 🎙️ 直播转写 | 喜马拉雅录音 Whisper 转写文本 | 5期 / 233K字 |

---

## 文件结构

```
shuangweihuixing-perspective/
├── SKILL.md                    # 核心Skill定义（含完整角色规则）
├── README.md                   # 本文件
├── .gitignore
├── knowledge/                  # 💡 知识库
│   ├── INDEX.md                # 知识导航地图（按问题主题路由）
│   ├── core-philosophy.md      # 核心思想深度解析
│   ├── books/                  # 七本书结构化知识
│   │   ├── 01-孙子兵法.md
│   │   ├── 02-君主论.md
│   │   ├── 03-国富论.md
│   │   ├── 04-资本论.md
│   │   ├── 05-当音乐停止之后.md
│   │   ├── 06-欧元危机.md
│   │   └── 07-技术封建主义.md
│   └── quotes/
│       └── 双尾彗星名言.md     # 56条名言 + 主题索引
├── references/
│   ├── research/               # 调研资料（观点/表达DNA/时间线）
│   └── sources/                # 原始素材
│       ├── metadata/           # 喜马拉雅专辑元数据（658集）
│       └── transcripts/        # Whisper转写文本（5期）
└── test_cases/
    └── test_activation.md      # 激活测试用例
```

---

## 适用场景

### 国际政治 & 军事
中美关系、俄乌冲突、中东局势、装备评估、战术分析

### 社会 & 经济
社会现象的参照系分析、经济政策评估、技术平台批判

### 个人发展
职业规划、执行力、情绪管理、教育理念、认知提升

### 创作策略
差异化定位、内容方向选择、信息源管理

---

## 安装方法

将此仓库克隆到 WorkBuddy/Marvis 的 skills 目录：

```bash
# WorkBuddy
git clone https://github.com/strikesuitzero/shuangweihuixing-perspective.git \
  ~/.workbuddy/skills/shuangweihuixing-perspective/

# Marvis
git clone https://github.com/strikesuitzero/shuangweihuixing-perspective.git \
  %APPDATA%/Tencent/Marvis/User/<user-id>/skills/shuangweihuixing-perspective/
```

---

## 更新记录

| 版本 | 日期 | 更新内容 |
|------|------|----------|
| v1.0 | 2025-05-27 | 初始版本，6份调研文件 |
| v1.1 | 2025-05-27 | 补充视频目录和评论区信息 |
| v1.2 | 2026-05-27 | 补充2025-2026视频标题，更新表达DNA |
| **v1.3** | **2026-06-10** | **新增7本书知识库、核心思想体系、56条名言（+15条转写新增）、直播转写文本（5期/233K字）、3条新决策启发式** |

---

## 相关链接

- [双尾彗星 B站主页](https://space.bilibili.com/48330353)
- [双尾彗星直播录音（喜马拉雅-迷宫干饭人）](https://www.ximalaya.com/album/80612627)
- [双尾彗星直播录像（喜马拉雅-本人）](https://www.ximalaya.com/album/77786765)
- [女娲造人术](https://github.com/alchaincyf/nuwa-skill) — Skill生成工具

---

## 创建者

由 [女娲 · Skill造人术](https://github.com/alchaincyf/nuwa-skill) 生成，后经手动完善。
调研基于 B站视频标题、直播文字稿、社区评论、喜马拉雅录音 Whisper 转写。

---

> *"合于利而动，不合于利而止。大利乃大义。"*
