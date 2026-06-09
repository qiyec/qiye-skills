<div align="center">

# 🧰 Qiye Skills

#### 我自己每天在用的一些 AI Skill，开源在这里

[![License](https://img.shields.io/badge/License-MIT-3B82F6?style=for-the-badge)](./LICENSE)
[![Skills](https://img.shields.io/badge/Skills-1-10B981?style=for-the-badge)](#-skills)
[![AgentSkills](https://img.shields.io/badge/AgentSkills-Standard-8B5CF6?style=for-the-badge)](https://agentskills.io)

![Claude Code](https://img.shields.io/badge/Claude_Code-Skill-D97706?style=flat-square&logo=anthropic&logoColor=white)
![Codex](https://img.shields.io/badge/Codex-Skill-10B981?style=flat-square&logo=openai&logoColor=white)
![OpenCode](https://img.shields.io/badge/OpenCode-Skill-3B82F6?style=flat-square)
![OpenClaw](https://img.shields.io/badge/OpenClaw-Skill-8B5CF6?style=flat-square)

</div>

都是在自己项目里跑通了一段时间，确实省事，才搬出来开源的。

这里的每个 Skill 都是 Agent 能直接加载的结构化指令集，遵循 [Agent Skills](https://agentskills.io) 开放标准。Claude Code、Codex、OpenCode、OpenClaw 都能装。

---

## 📋 目录

| 名字 | 一句话 |
|---|---|
| ✍️ [**qiye-writer（Qiye 写作）**](#-qiye-writerqiye-写作) | 装上之后，Agent 用我的口吻和节奏写技术博客 |

---

## 📦 安装方式

在 Claude Code、Codex、OpenClaw 等支持 Skill 的 Agent 里，直接说：

```
帮我安装这个 skill：https://github.com/qiyec/qiye-skills/tree/main/<skill-name>
```

把 `<skill-name>` 换成你想装的那个，比如 `qiye-writer`。Agent 会自己 clone 到对应目录，不用你操心路径。

---

## ✨ Skills

<a id="-skills"></a>

<table>
<tr><td>

### ✍️ qiye-writer（Qiye 写作）

> *"一个在技术浪潮里折腾的普通人，认真地跟你聊一个他刚搞明白的技术问题。"*

我自己写技术博客的那套写作 skill。装上之后，Agent 写出来的东西就是我的口吻、我的节奏、我的禁忌词全在里面。

**适合**

你看过我博客 qiyec.site 的文章，觉得风格还行，想让你的 AI 也照着这个调子写东西。比如丢一个技术问题、一段踩坑经历、一个折腾故事，让它写成技术博客。

**不适合**

你想要的是"通用好文笔"。这个 skill 是有立场的——它会**拒绝**写「首先...其次...最后」、**拒绝**「在当今 AI 快速发展的时代」、**拒绝**「说白了 / 本质上 / 换句话说」、**拒绝**中文冒号和破折号。如果你的目标读者就好这一口，那这个 skill 不适合你。

**它会做什么**

- 完整的写作风格规则（节奏感、口语化转场、亲自下场、技术升维）
- 四层自检体系（硬性规则、风格一致性、内容质量、活人感终审）
- 一套风格示例库和修改对比
- 内容方法论（选题 HKR 质检法、五种文章类型写法）

**五种文章类型**

- 环境搭建 / 踩坑记录 — 核心是「我帮你趟过这条河了」
- 技术原理 / 深度解析 — 核心是「这个东西到底怎么运作的」
- 工具对比 / 评测 — 核心是「我帮你试过了，你该怎么选」
- 工作流 / 方法论 — 核心是「这套方法我跑通了，你可以直接用」
- 实战项目 / 折腾记录 — 核心是「跟我一起做」

→ [SKILL.md](./qiye-writer/SKILL.md)

</td></tr>
</table>

---

## 🌟 关于

我是 Qiye，一个 Java 后端老兵，正在向 AI 全栈开发转型。博客在 [qiyec.site](https://qiyec.site)，签名写着「若暗夜终临，吾必立于万万人前」。

这些 skill 都是我自己每天在用的，开源出来如果对你有帮助，给个 ⭐ 就行。有问题或建议，欢迎在 Issues / Discussions 里说一声。

---

<div align="center">

[MIT License](./LICENSE) · 自由使用 / 修改 / 再分发

Made by [@qiyec](https://github.com/qiyec)

</div>
