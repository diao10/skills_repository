# Superpowers

一个完整的 AI Agent 软件开发工作流框架，基于可组合的 "Skills" 和初始指令构建。

## 简介

Superpowers 是一套为编码 Agent 设计的完整软件开发方法论。当 Agent 检测到你在构建项目时，不会立即开始写代码，而是：

1. **需求澄清** - 通过对话深入了解你的真实需求
2. **设计确认** - 将设计分块展示，便于阅读和确认
3. **制定计划** - 创建清晰的实现计划，强调 TDD、YAGNI 和 DRY 原则
4. **子 Agent 开发** - 启动子 Agent 驱动开发流程，自动审查和推进任务

## 核心工作流

| 阶段 | Skill | 说明 |
|------|-------|------|
| 1 | brainstorming | 需求梳理，通过苏格拉底式提问细化设计 |
| 2 | using-git-worktrees | 创建隔离工作区，验证干净基线 |
| 3 | writing-plans | 将工作拆分为 2-5 分钟的小任务 |
| 4 | subagent-driven-development | 子 Agent 执行，两阶段审查 |
| 5 | test-driven-development | 强制 RED-GREEN-REFACTOR 循环 |
| 6 | requesting-code-review | 代码审查，按严重程度报告问题 |
| 7 | finishing-a-development-branch | 验证测试，提供合并/PR 选项 |

## Skills 库

### 测试
- **test-driven-development** - 红绿重构循环

### 调试
- **systematic-debugging** - 四阶段根因分析
- **verification-before-completion** - 确保问题真正解决

### 协作
- **brainstorming** - 苏格拉底式设计细化
- **writing-plans** - 详细实现计划
- **executing-plans** - 批量执行与检查点
- **dispatching-parallel-agents** - 并发子 Agent 工作流
- **requesting-code-review** - 审查前检查清单
- **using-git-worktrees** - 并行开发分支
- **subagent-driven-development** - 快速迭代与审查

### 元技能
- **writing-skills** - 创建新技能的最佳实践
- **using-superpowers** - Skills 系统介绍

## 安装方法

### Claude Code
```
/plugin install superpowers@claude-plugins-official
```

### Cursor
```
/add-plugin superpowers
```

### Codex
```
Fetch and follow instructions from https://raw.githubusercontent.com/obra/superpowers/refs/heads/main/.codex/INSTALL.md
```

### OpenCode
```
Fetch and follow instructions from https://raw.githubusercontent.com/obra/superpowers/refs/heads/main/.opencode/INSTALL.md
```

### GitHub Copilot CLI
```
copilot plugin marketplace add obra/superpowers-marketplace
copilot plugin install superpowers@superpowers-marketplace
```

### Gemini CLI
```
gemini extensions install https://github.com/obra/superpowers
```

## 更新

```
/plugin update superpowers
```

## 设计理念

- **测试驱动开发** - 始终先写测试
- **系统化优于随意** - 流程优于猜测
- **降低复杂度** - 简洁是首要目标
- **证据胜于宣称** - 验证后再宣告成功

## 相关链接

- **GitHub**: https://github.com/obra/superpowers
- **Issues**: https://github.com/obra/superpowers/issues
- **Discord**: 社区支持和交流
- **License**: MIT
