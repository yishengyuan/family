# 每日三餐

菲律宾就地取材，兼顾大人小孩，一天营养均衡的家庭三餐记录。

## 新增一天菜单

在 `_posts/` 下新建文件，文件名格式：`YYYY-MM-DD-标题.md`

例如：`_posts/2026-05-17-菲式番茄炒蛋.md`

front matter 模板：

```yaml
---
title: "2026-05-17 每日三餐"
date: 2026-05-17
summary: "Tinola 鸡汤 + 烤 Bangus"
tags: [家常, 儿童友好]
---
```

正文按 `## 早餐` / `## 午餐` / `## 晚餐` 三段写，每段建议含：
- 菜名（中英菲文对照）
- 食材清单
- 做法步骤
- 营养重点
- 儿童友好度（★ 1-5）

## 本地预览

```bash
gem install bundler jekyll
jekyll serve
```

部署在 GitHub Pages：push 到 `main` 自动触发。
