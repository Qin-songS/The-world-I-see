---
type: system
generated: true
---

# 推荐的 Obsidian 图谱设置

为了让主图只表达“思想 → 领域 → 抽象层 → 具体例子”，建议在 Graph view 右上角齿轮中：

## Filters → Search files

```text
-path:"Records" -path:"_SYSTEM" -file:README
```

同时关闭 **Orphans**，这样学习记录、系统说明和没有进入主结构的孤立课程不会干扰主图。

## Display

打开 **Arrows**。本 Vault 的主层级链接原则是“父节点写向子节点”，所以箭头表示从更上位的思想向更具体的结构展开。

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

优先从 `[[复杂系统由基础规则逐层构造]]` 打开 **Local Graph**，Depth 先设为 3–4；需要看完整结构时再打开 Global Graph。
