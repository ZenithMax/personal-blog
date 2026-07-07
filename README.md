# Personal Blog

这是“开源软件开发”课程实践 1 的个人 Blog 项目。项目使用静态 HTML/CSS 编写，并通过 GitHub Actions 发布到 GitHub Pages。

## 页面

- 首页：`index.html`
- 第一篇文章：`posts/first-post.html`
- Markdown 源稿：`posts/first-post.md`

## 发布方式

1. 在 GitHub 创建公开仓库 `personal-blog`。
2. 将本目录内容推送到仓库 `main` 分支。
3. 在仓库 Settings -> Pages 中选择 `gh-pages` 分支作为发布来源。
4. 推送后等待 Actions 中 `Deploy blog to GitHub Pages` 运行成功，工作流会把站点文件同步到 `gh-pages` 分支。
