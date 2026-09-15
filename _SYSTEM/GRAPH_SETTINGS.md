---
type: system
generated: true
---

# 推荐的 Obsidian 图谱设置

为了让主图表达“上位问题 / 复杂系统 → 更简单的组成与机制 → 具体知识”，建议在 Graph view 右上角齿轮中：

## Filters → Search files

```text
-path:"Records" -path:"_SYSTEM" -file:README
```

同时关闭 **Orphans**，这样学习记录、系统说明和没有进入主结构的孤立课程不会干扰主图。

## Display

打开 **Arrows**。本 Vault 的主层级链接原则是：**复杂、上位、整体的节点指向更简单、更底层或更具体的节点**。

例如计算机主线按下面方向阅读：

```text
操作系统与软件
→ 微体系结构与 ISA
→ 时序与状态
→ 数字逻辑
→ 电路
→ 半导体器件
```

箭头表达的是“继续往下拆，会看到什么”，不是“底层向上构造”的时间顺序。

## Groups（可选）

可以按属性建立几组：

```text
[node_role:principle]
[node_role:domain_projection]
[node_role:mechanism OR abstraction_map OR abstraction_layer]
[node_role:example_cluster OR concrete_example]
```

颜色只用于辅助辨认，不代表新的知识分类。

## 阅读方式

优先从一个高层节点打开 **Local Graph**，沿箭头向下追踪；需要看完整结构时再打开 Global Graph。
