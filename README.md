# 戈壁与代码 - 个人博客

这是一个使用 Hugo 静态网站生成器和 GitHub Pages 托管的个人博客。

## 快速开始

### 本地预览

1. 安装 Hugo Extended 版本
2. 进入博客目录
3. 运行 `hugo server`
4. 打开 http://localhost:1313

### 发布文章

在 `content/posts/` 目录下创建 `.md` 文件，Front Matter 格式：

```markdown
---
title: "文章标题"
date: 2024-01-15
draft: false
categories: ["分类名"]
tags: ["标签1", "标签2"]
image: "封面图片URL"
---

文章内容...
```

## 自动部署

推送到 GitHub 后，GitHub Actions 会自动构建并部署到 GitHub Pages。

访问地址：https://yananliu007-art.github.io/

## 自定义

- 配置文件：`hugo.toml`
- 主题：Stack V3
- 更多配置请参考 Hugo 文档