---
name: web-performance
description: Web 性能优化：Core Web Vitals 提升、bundle 分析、资源加载策略、渲染性能
source:
  type: original
  repo: skills-repo/frontend-engineer
  path: skills/web-performance/SKILL.md
  version: 1.0.0
  updated: 2026-07-26
metadata:
  category: 性能
  platform: Web
  difficulty: 进阶
---

# Web 性能优化

> 让页面快起来。从测量到优化，覆盖 Core Web Vitals 三指标和加载性能全链路。

## 能力

- **性能测量**：Lighthouse/PageSpeed Insights 报告解读
- **Core Web Vitals**：LCP（加载）、INP（交互）、CLS（布局偏移）优化策略
- **Bundle 分析**：webpack-bundle-analyzer、tree-shaking、code splitting
- **资源加载**：懒加载、预加载（preload/prefetch）、CDN 策略、图片优化
- **渲染性能**：避免 layout thrashing、虚拟列表、debounce/throttle

## 使用方式

```
/web-performance 分析这个页面的 Lighthouse 报告
/web-performance 首页 LCP 超过 4 秒，怎么优化？
/web-performance 这个 bundle 有 2MB，帮我做 code splitting
```

## 优化决策树

```
LCP 高 → 检查服务器响应/资源加载/渲染阻塞
INP 高 → 检查长任务/事件处理/主线程阻塞
CLS 高 → 检查无尺寸图片/动态注入内容/Web Font
```

## 工作流

1. 获取 Lighthouse 报告或性能数据
2. 识别瓶颈（网络/渲染/JS 执行）
3. 按影响大小排序优化建议
4. 生成具体代码修改
5. 预估优化后的指标改善

## 适用场景

- 页面加载慢需要排查
-  Lighthouse 评分低需要提升
- 移动端性能优化
- 大 bundle 需要拆分

## 限制

- 不涉及后端/服务器性能优化
- 不涉及 CDN/网络基础设施配置
- 建议的优化方案需要在实际设备上验证