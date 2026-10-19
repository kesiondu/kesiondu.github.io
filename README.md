# Roadster 2026 Notes

中文原创博客，主题为 Tesla Roadster 2026 与飞行汽车 AI 视频创作。

- 网站：https://kesiondu.github.io/
- 关联项目：https://flyingcar-ai.app/
- 使用 GitHub Pages 内置 Jekyll 构建；无需本地安装依赖即可在 GitHub 编辑发布。

## 发布文章

在 `_posts/` 创建 `YYYY-MM-DD-english-slug.md`，参考现有文章填写：

```yaml
---
title: 文章标题
description: 一句话摘要
category: 创作笔记
---
```

下面使用 Markdown 写正文，提交到 main 后自动发布。文章日期不能晚于站点当天日期。使用原创内容，在相关段落自然插入项目链接。

## 编辑网站

- `_config.yml`：站名、简介、域名。
- `index.html`：首页。
- `projects.md`：项目介绍与外链。
- `assets/style.css`：响应式样式。
- `_layouts/`：页面布局。

GitHub 仓库 Settings → Pages 应配置为 Deploy from a branch，main 分支的根目录。Jekyll 自动生成 canonical、站点地图与 RSS。代码仓库为公开仓库。

网站部署成功不等于被搜索引擎收录，也不保证外链排名效果。后续可以在 Google Search Console 验证站点后提交 sitemap.xml。
