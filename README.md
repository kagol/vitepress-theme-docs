# vitepress-theme-docs

用于开源项目搭建文档系统的 VitePress 主题，在 VitePress 默认主题基础上增加了更多实用功能和美观样式。

## 快速开始

在 `.vitepress` 目录新增 `theme/index.ts` 文件，添加以下代码：

```typescript
import DocsTheme from 'vitepress-theme-docs'
import 'vitepress-theme-docs/dist/style.css'

export default {
  ...DocsTheme
}
```

## 本地启动

```shell
# 安装依赖
pnpm i

# 效果预览
pnpm dev
```
