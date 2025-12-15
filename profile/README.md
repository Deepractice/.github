<div align="center">

# Deepractice - Build for the Open Agent VM

**Born open, run free, agents unchained.**

<br/>

[![Stars](https://img.shields.io/github/stars/Deepractice?style=flat&color=yellow)](https://github.com/Deepractice)
[![Followers](https://img.shields.io/github/followers/Deepractice?style=flat&color=blue)](https://github.com/orgs/Deepractice/followers)
[![Website](https://img.shields.io/badge/Website-deepractice.ai-blue)](https://deepractice.ai)

</div>

---

## The Problem

Today's AI Agents are **prisoners**:

- GPTs locked in OpenAI
- Coze bots locked in ByteDance
- Dify agents locked in Dify

Your agents deserve freedom.

---

## The Solution

We're building the **open-source virtual machine** for AI Agents.

Like JVM runs Java anywhere, **Agent VM runs agents anywhere**.

```
┌─────────────────────────────────────────────────────────────┐
│                     Agent VM Stack                          │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│   DARP         Resource Protocol           arp://org@tool   │
│   ───────────────────────────────────────────────────────── │
│                           ↓                                 │
│   DPML         Markup Language         <agent>...</agent>   │
│   ───────────────────────────────────────────────────────── │
│                           ↓                                 │
│   PromptX      Context & Extensions       Nuwa · Luban      │
│   ───────────────────────────────────────────────────────── │
│                           ↓                                 │
│   AgentX       Runtime Engine          Event-driven Core    │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

---

## Core Projects

| Project | Role | What it does |
|---------|------|--------------|
| [**DARP**](https://github.com/Deepractice/darp) | Protocol | Universal addressing for agent resources |
| [**DPML**](https://github.com/Deepractice/dpml) | Standard | Write agents like HTML — declarative & portable |
| [**PromptX**](https://github.com/Deepractice/PromptX) | Extension | Create roles (Nuwa) & integrate tools (Luban) |
| [**AgentX**](https://github.com/Deepractice/AgentX) | Runtime | Event-driven engine with Docker-style lifecycle |

---

## What It Looks Like

```xml
<!-- assistant.dpml -->
<agent>
  <llm api-type="openai" model="gpt-4" />
  <prompt>You are a helpful assistant.</prompt>
</agent>
```

```bash
npx dpml agent chat assistant.dpml
```

**Or create with natural language:**

```
> @Nuwa create a travel planning expert
> @action travel-planner
> Plan a 3-day trip to Tokyo
```

---

## Why Deepractice?

|  | GPTs | Coze | LangChain | **Deepractice** |
|--|------|------|-----------|-----------------|
| Open Source | ❌ | ❌ | ✅ | ✅ |
| Self-hosted | ❌ | ❌ | ✅ | ✅ |
| Cross-LLM | ❌ | ❌ | ✅ | ✅ |
| Declarative Config | ❌ | ❌ | ❌ | ✅ |
| Standard Protocol | ❌ | ❌ | ❌ | ✅ |
| No Chain Required | — | — | ❌ | ✅ |

---

## Community

- 🌐 [Website](https://deepractice.ai)
- 💬 [DeepracticeX Community](https://x.deepractice.ai)
- 📺 [Bilibili](https://space.bilibili.com/277448879)
- 🎙️ [Podcast](https://www.xiaoyuzhoufm.com/podcast/67bc12b63347fd01f19109ab)
- 📱 WeChat: **deepracticex**

---

## Our Vision

We believe the future of AI belongs to **open standards**, not walled gardens.

Just as the Web flourished through HTML and HTTP, the Agent era needs open protocols that let innovation flow freely — across platforms, across models, across borders.

**We're not just building tools. We're building the foundation.**

---

<div align="center">

<br/>

**Open standard. Universal runtime. Agents, unchained.**

<br/>

</div>
