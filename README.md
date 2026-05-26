# Dynasty Skills

Dynasty 的个人 Agent Skills 集合 — 实战导向、工作流驱动。

## Skills

### 软件开发类

- **harness-engineering** — 大型/跨会话任务的工程化脚手架。Initializer 开局、功能清单约束、开工仪式、独立评审、上下文重置。源自 Anthropic Harness Engineering 实践。

## 安装

### Hermes Agent

将此仓库 clone 到 Hermes skills 目录：

```bash
git clone https://github.com/NewDynasty/skills.git ~/.hermes/skills/external/newdynasty
```

### Claude Code

```bash
/plugin marketplace add NewDynasty/skills
```

## 设计原则

1. SKILL.md 负责核心逻辑，细节拆到 references/scripts/assets
2. description 同时写清：做什么、什么时候触发、不适用的场景
3. 先交付初稿，不自动做超出预期的后续动作
4. 需要高影响操作时，先说明再执行
5. 持续沉淀 Gotchas，降低翻车概率

## License

CC BY-NC-SA 4.0
