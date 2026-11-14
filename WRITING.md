# 博客使用说明

## 发布新文章

1. 在 GitHub 仓库进入 _posts 文件夹。
2. 点击 Add file → Create new file。
3. 文件名使用 YYYY-MM-DD-英文短标题.md，例如 2026-11-15-reading-notes.md。
4. 按下面格式填写文章，将日期改为实际发布日期：
   
```markdown
---
layout: post
title: "阅读笔记"
date: 2026-11-15 10:00:00 +0800
categories: 阅读
---

这里写文章摘要。

<!--more-->

## 正文

这里写文章内容。
```

5. 点击 Commit changes，提交到 main 分支。开启 Pages 后，更新会自动触发构建。
6. 请使用当前或过去的日期；未来日期的文章通常不会立即显示。

## 修改博客

- 名称和介绍：编辑 _config.yml 中的 title、description。
- 关于页：编辑 about.md。
- 首页介绍：编辑 index.md。
- 图片：上传到 assets/images，然后在文章中使用 ![说明](/assets/images/文件名.png)。

## 首次开启 GitHub Pages

进入仓库 Settings → Pages，在 Build and deployment 中：
- Source 选择 Deploy from a branch。
- Branch 选择 main，目录选择 / (root)。
- 点击 Save，等待 GitHub 构建完成。

网站地址：https://weinmanwodskow453-cpu.github.io

可在仓库 Actions 查看构建结果。不要上传密码或 API 密钥。
