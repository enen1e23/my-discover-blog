# My Discover Blog 使用说明

## 📁 文件结构

```
my-discover-blog/
├── _config.yml         # 网站配置
├── index.md            # 首页
├── about.md            # 关于页（显示在导航栏）
├── Gemfile             # Ruby 依赖
├── .gitignore          # Git 忽略文件
├── categories/         # 分类页面
│   ├── index.md                      # 全部分类
│   ├── Physics_in_Everyday_Life.md   # 物理分类
│   ├── Life_Wisdom.md                # 智慧分类
│   └── Someday_Maybe.md              # 计划分类
└── _posts/             # 文章（按日期命名）
    └── 2025-12-15-welcome.md
```

## 🚀 本地预览

```bash
cd my-discover-blog
bundle install          # 首次运行
bundle exec jekyll serve
```

浏览器访问 http://localhost:4000

## 📝 写新文章

在 `_posts/` 文件夹创建文件，命名格式：`YYYY-MM-DD-标题.md`

```markdown
---
layout: post
title: "文章标题"
date: 2025-12-15
categories: Life_Wisdom   # 可选：Physics_in_Everyday_Life / Life_Wisdom / Someday_Maybe
---

文章内容...
```

## 🔄 更新到 GitHub

### 方法一：完全替换（推荐）

1. 删除本地 `my-discover-blog` 文件夹内的所有内容（保留 .git 文件夹！）
2. 把新文件复制进去
3. 运行命令：

```bash
cd F:\06实践\搭建博客\my-discover-blog
git add .
git commit -m "优化博客结构"
git push
```

### 方法二：只替换修改的文件

直接把新文件覆盖旧文件，然后：

```bash
cd F:\06实践\搭建博客\my-discover-blog
git add .
git commit -m "优化博客结构"
git push
```

## ⚙️ 自定义

### 修改导航栏

编辑 `_config.yml` 中的 `header_pages`：

```yaml
header_pages:
  - about.md              # 只显示"关于"
  # - categories/index.md # 取消注释可添加"全部分类"
```

### 修改网站标题/描述

编辑 `_config.yml` 顶部的 `title` 和 `description`
