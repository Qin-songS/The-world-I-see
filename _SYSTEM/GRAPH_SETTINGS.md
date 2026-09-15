---
type: system
generated: true
---
# Obsidian 浏览策略

## 主界面：Breadcrumbs Tree
日常不要从 Global Graph 找知识。打开 `[[知识导航]]`，按需展开某一支；各结构页也内嵌了只沿 `down` 遍历的折叠树。

## Global Graph：只做鸟瞰
如果需要看整体连接密度，再打开关系图谱。建议过滤：

```text
-path:"Records" -path:"_SYSTEM" -file:README
```

关闭 **Orphans**，打开 **Arrows**。

## Local Graph：检查邻域
当你已经定位到某个具体节点时，用 Local Graph 看它附近 1–2 层的横向关系，而不是拿它当层级导航。

## 方向约定
主树沿 `down` 从 **整体 / 复杂 / 上位 → 组成 / 简单 / 具体** 展开。比如计算机分支是：软件 → ISA/微体系结构 → 状态与时序 → 数字逻辑 → 电路 → 半导体。

## 数据边界
Notion Relation 是事实源；Breadcrumbs Tree、Global Graph、Local Graph 都只是不同投影。不要为了某个视图复制知识节点。
