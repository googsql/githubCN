# GithubCN

> 原作者因精力有限已暂停更新；本仓库由社区接手维护，会持续补充与更新汉化词条。

Github 浏览器中文汉化插件

## 安装 && 使用

支持的浏览器|使用方式
---|---
Edge|[Edge 应用商店](<https://microsoftedge.microsoft.com/addons/detail/githubcn/onlodfoebaobhmlhgcbddjngjbkdbfaj>)
Google Chrome|下载源代码拖放至扩展页

## 如何补充翻译词条？

所有的翻译内容都在在`src/js/content.js`中

```js
const allData = [
  [`English`, `英文`],
]
```

## 2026 维护说明

- 已补充近两年 GitHub 新版页面常见文案（如 Copilot、Actions、Discussions、Security、Rulesets、Codespaces 等）。
- 已增强运行时替换逻辑：支持更多属性（如 `aria-label`、`title`）、大小写兼容，以及动态数字文案（如 `3 days ago`）。
- 如仍有未汉化内容，建议在 `src/js/content.js` 的 `allData` 中继续追加精确词条，优先添加完整短语而非单词，避免误替换。
