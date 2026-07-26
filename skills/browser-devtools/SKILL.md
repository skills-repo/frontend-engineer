---
name: browser-devtools
description: 浏览器 DevTools 精通：元素检查、网络分析、性能剖析、Console、Memory
source:
  type: original
  repo: skills-repo/frontend-engineer
  path: skills/browser-devtools/SKILL.md
  version: 1.0.0
  updated: 2026-07-26
metadata:
  category: 调试
  platform: Web
  difficulty: 入门
---

# 浏览器 DevTools 精通

> Chrome/Edge DevTools 是你的第二个编辑器。学会用 DevTools 调试，而不是满屏 console.log。

## 能力

- **Elements 面板**：DOM 检查、样式实时编辑、CSS 选择器测试、布局可视化
- **Console**：高级 console API（table/group/trace/assert）、Live Expression
- **Network 面板**：请求过滤、瀑布图分析、请求阻塞/重放、性能瓶颈定位
- **Performance 面板**：录制分析、火焰图解读、长任务定位、FPS 分析
- **Memory 面板**：堆快照对比、内存泄漏定位、Detached DOM 检测
- **Application 面板**：Storage 检查（Cookie/LocalStorage/IndexedDB）、Service Worker 调试

## 使用方式

```
/browser-devtools 页面加载时有个请求特别慢，帮我分析
/browser-devtools 这个页面滚动卡顿，用 Performance 面板排查
/browser-devtools 怀疑有内存泄漏，帮我做 heap snapshot 分析
```

## 常用技巧

| 场景 | DevTools 功能 |
|------|-------------|
| CSS 调试 | Elements → Styles 面板实时编辑 |
| 网络慢 | Network → 按时间排序找长请求 |
| JS 卡顿 | Performance → 录制 → 找长任务 |
| 内存涨 | Memory → 两次 heap snapshot → 对比 |
| 接口挂了 | Network → 右键请求 → Replay XHR |
| 样式覆盖 | Elements → Computed → 看最终生效样式 |

## 工作流

1. 描述遇到的问题（慢/卡/错/内存涨）
2. AI 指导用哪个面板、如何操作
3. 解读面板输出
4. 定位根因并给出修复建议

## 适用场景

- 前端 bug 排查
- 页面性能分析
- 网络请求调试
- 内存泄漏排查

## 限制

- 仅覆盖 Chrome/Edge DevTools，Firefox/Safari 有差异
- 不涉及后端/服务器端调试
- 不替代 APM 监控工具（Sentry/Datadog）