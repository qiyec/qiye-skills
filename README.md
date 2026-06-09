<div align="center">

# 🧰 Qiye Skills

#### 一个 Java 后端老兵的 AI Skill 工具箱

[![License](https://img.shields.io/badge/License-MIT-3B82F6?style=for-the-badge)](./LICENSE)
[![Skills](https://img.shields.io/badge/Skills-1-10B981?style=for-the-badge)](#-skills)
[![AgentSkills](https://img.shields.io/badge/AgentSkills-Standard-8B5CF6?style=for-the-badge)](https://agentskills.io)

![Claude Code](https://img.shields.io/badge/Claude_Code-Skill-D97706?style=flat-square&logo=anthropic&logoColor=white)
![Codex](https://img.shields.io/badge/Codex-Skill-10B981?style=flat-square&logo=openai&logoColor=white)
![OpenCode](https://img.shields.io/badge/OpenCode-Skill-3B82F6?style=flat-square)
![OpenClaw](https://img.shields.io/badge/OpenClaw-Skill-8B5CF6?style=flat-square)

</div>

遵循 [Agent Skills](https://agentskills.io) 开放标准，Claude Code、Codex、OpenCode、OpenClaw 都能直接装。

---

## 📋 Skills 一览

| Skill | 干什么用的 |
|---|---|
| ✍️ [**qiye-writer**](#-qiye-writer) | 让 Agent 模仿我的风格写技术博客 |

---

## 📦 怎么装

跟你装其他 Skill 一样，在 Agent 里说一句话就行：

```
帮我装一下 https://github.com/qiyec/qiye-skills/tree/main/qiye-writer
```

Agent 会自动把文件拉到对的目录，不需要你手动操作。

---

## ✨ Skills 详细介绍

<a id="-skills"></a>

<table>
<tr><td>

### ✍️ qiye-writer

> *「一个在技术浪潮里折腾的普通人，认真地跟你聊一个他刚搞明白的技术问题。」*

这是我写技术博客用的写作 Skill。风格内核就一句话——说人话，讲真话，亲自下场。

装上之后 Agent 会继承我的一整套写作体系，包括风格规则、禁区词表、四层自检流程，还有从真实文章里提炼的风格示例库。

**这个 Skill 的立场**

它不是「通用好文笔生成器」，而是有明确偏好的。它会主动拒绝这些东西：

- ❌ 「首先...其次...最后」这类八股文结构
- ❌ 「在当今 AI 快速发展的时代」这类空话开头
- ❌ 「说白了 / 本质上 / 换句话说」这类 AI 味高频词
- ❌ 中文冒号、破折号、双引号
- ❌ 教科书式的知识科普方式

如果你喜欢那种一本正经的技术文章风格，这个 Skill 可能不适合你。

**覆盖的能力**

- 🎯 **选题判断** — HKR 质检法（Hands-on / Knowledge / Resonance）
- 🎨 **五种文章类型** — 踩坑记录、深度解析、工具评测、方法论、折腾记录，每种写法重心不同
- 🗣️ **风格基因** — 节奏感、口语化转场、句式断裂、技术升维、英雄之旅叙事弧
- 🔍 **四层自检** — 硬性规则 → 风格一致性 → 内容质量 → 活人感终审

**怎么触发**

直接用自然语言跟 Agent 说就行，不需要记特殊命令：

```
帮我写一篇关于 xxx 的技术博客
用 qiye-writer 的风格写一篇文章
我想写一篇 xxx 的踩坑记录
帮我润色一下这篇文章，用我的风格
```

也可以直接丢素材给它——一段报错日志、一个想法、一段踩坑经历，它会自己判断属于哪种文章类型，然后按对应的方式写。

→ [SKILL.md](./qiye-writer/SKILL.md) · [博客 qiyec.site](https://qiyec.site)

</td></tr>
</table>

---

## 🌟 关于

我是 Qiye，一名在 AI 浪潮中进化的 Java 工程师，现专注于 AI 全栈开发。

这个仓库会持续更新，我用到什么好的工作流就往上加。如果你也有类似的折腾经历，或者觉得哪个 Skill 可以改进，欢迎来 Issues 里聊。

---

<div align="center">

[MIT License](./LICENSE) · 随便用，随便改

Made by [@qiyec](https://github.com/qiyec)

</div>
