---
name: component-builder
description: React/Vue 组件开发最佳实践：设计模式、Props/State 管理、可访问性、测试策略
source:
  type: original
  repo: skills-repo/frontend-engineer
  path: skills/component-builder/SKILL.md
  version: 1.0.0
  updated: 2026-07-26
metadata:
  category: 组件开发
  platform: Web
  difficulty: 进阶
---

# 组件构建器

> 设计可维护、可复用、可测试的前端组件。从 Props 设计到组合模式，覆盖组件开发的完整生命周期。

## 能力

- **组件设计模式**：Compound Components、Render Props、HOC、Hooks 组合
- **Props 设计**：类型安全、默认值、受控/非受控模式选择
- **状态管理**：local state vs lifted state vs context vs store — 选型决策树
- **可访问性**：ARIA 标签、键盘导航、焦点管理、语义化 HTML
- **组件测试**：单元测试（render + interaction）、快照测试、可访问性测试

## 使用方式

```
/component-builder 设计一个可复用的 Modal 组件
/component-builder 审查这个组件的 Props 设计
/component-builder 为这个表单组件添加键盘可访问性
```

## 工作流

1. 描述组件需求和交互行为
2. AI 推荐设计模式（Compound / Render Props / Hooks）
3. 生成组件骨架代码（含类型定义）
4. 补充可访问性和测试
5. 输出完整组件文件

## 适用场景

- 新功能需要设计可复用组件
- 已有组件 Props 混乱需要重构
- 组件缺少可访问性支持
- 新人需要组件开发规范指导

## 限制

- 生成的代码需根据实际项目调整样式和业务逻辑
- 不涉及 SSR/RSC 特定模式（那是框架层面的考量）
- 不替代设计系统的组件库（如 shadcn/ui）