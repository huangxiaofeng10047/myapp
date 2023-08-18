# Modern.js App

## Setup

Install the dependencies:

```bash
pnpm install
```

## Get Started

Start the dev server:

```
pnpm dev
```

Enable optional features or add a new entry:

```
pnpm new
```

Build the app for production:

```
pnpm build
```

Preview the production build locally:

```
pnpm serve
```

For more information, see the [Modern.js documentation](https://modernjs.dev/en).
生成目录结构
tree -L 3 -I "node_modules" > tree.md
基于node的tree-node-cli （推荐）
全局安装：npm install -g tree-node-cli
使用示例：tree -L 3 -I "node_modules" > tree.md

遍历三层目录结构，忽略node_modules，输出到tree.md
缺点:依赖node,得装tree-node-cli工具

基于moderjs创建的myapp的demo
