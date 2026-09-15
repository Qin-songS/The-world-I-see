# Breadcrumbs｜主浏览方式

## 目标
Global Graph 只做全局鸟瞰；日常浏览从 `[[知识导航]]` 的可折叠树进入。

## 手机 / 桌面首次设置
1. Obsidian → 设置 → 第三方插件 → 浏览，安装并启用 **Breadcrumbs**。
2. 打开命令面板，运行 **Breadcrumbs: Rebuild Graph**。
3. 打开 `[[知识导航]]`。
4. 以后优先展开需要的分支；Global Graph 只在需要看全局连接密度时使用。

## 生成约定
- `down`：从整体、上位、复杂节点指向组成、下位或更具体节点。
- `up`：返回上位节点；一个节点可以有多个 `up`。
- `down` 是树视图的主要遍历方向。
- 领域地图只是 projection，不等于逻辑前提。
- Notion Relation 仍是事实源；这里的 up/down 可以由编译器重新生成。
