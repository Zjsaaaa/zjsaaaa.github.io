# zjsaaaa.github.io

张家硕的个人主页，托管于 GitHub Pages。

**线上地址**：https://zjsaaaa.github.io

## 内容

单文件静态站点，无构建步骤、无运行时依赖：

| 文件 | 作用 |
| --- | --- |
| `index.html` | 整个站点（内联全部 CSS 与少量 JS） |
| `.nojekyll` | 跳过 GitHub Pages 的 Jekyll 预处理 |

页面结构：身份首屏 → 数据证据（bento 网格）→ 代表项目 → 技术栈 → 教育背景与实习 → 联系方式。

设计方向取自 Linear.app 的 bento 网格风格：深色底、单一点缀色、1px 描边替代阴影、小字号密排。

## 本地预览

直接用浏览器打开 `index.html` 即可，不需要起服务。

## 修改

改 `index.html` 后提交推送，GitHub Pages 会自动重新构建（约 1–2 分钟生效）：

```bash
git add index.html
git commit -m "docs: 更新个人主页内容"
git push
```

## 技术说明

- 字体走 Google Fonts CDN（Inter + IBM Plex Mono），需要联网；离线时会回退到系统字体栈
- 响应式已验证 1440 / 768 / 375 三个断点，无横向溢出
- 不含任何追踪脚本、分析代码或第三方依赖
