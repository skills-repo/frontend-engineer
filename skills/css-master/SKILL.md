---
name: css-master
description: CSS 布局：Tailwind/Grid/Flexbox、响应式设计、CSS 动画与过渡
source:
  type: original
  repo: skills-repo/frontend-engineer
  path: skills/css-master/SKILL.md
  version: 1.0.0
  updated: 2026-07-26
metadata:
  category: CSS
  platform: Web
  difficulty: 入门
---

# CSS 布局大师

> 写 CSS 不再靠猜。从布局方案选择到响应式断点，从 Grid 到 Tailwind，覆盖现代 CSS 核心技术。

## 能力

- **布局方案推荐**：根据设计稿推荐 Grid/Flexbox/Flow 布局组合
- **响应式设计**：移动优先、断点策略、容器查询
- **Tailwind 精通**：utility class 组合、自定义 theme、@apply 最佳实践
- **CSS 动画**：transition、keyframes、will-change 优化
- **浏览器兼容**：caniuse 查询、渐进增强、降级方案

## 使用方式

```
/css-master 实现这个 dashboard 布局（header + sidebar + main）
/css-master 这个 flex 布局在移动端溢出，帮我修
/css-master 给这个按钮加 hover 和 click 动画
```

## 工作流

1. 描述布局需求或展示设计稿截图
2. AI 推荐布局方案（Grid areas / Flex 方向）
3. 生成 CSS/Tailwind 代码
4. 标注响应式断点和兼容性注意事项

## 布局选择速查

| 需求 | 推荐方案 |
|------|---------|
| 页面整体布局 | CSS Grid |
| 一维排列（行/列） | Flexbox |
| 重叠/绝对定位 | position + z-index |
| 文字排版 | Flow + max-width |
| 自适应卡片网格 | Grid + auto-fill/minmax |

## 适用场景

- 从零搭建页面布局
- 响应式适配移动端
- Tailwind 项目中的复杂样式
- 动画和微交互实现

## 限制

- 不涉及 Canvas/WebGL 等非 CSS 渲染
- 复杂动画建议使用 Framer Motion 等库
- 生成的代码需在目标浏览器测试