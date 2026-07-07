# 第一次使用 GitHub Pages 发布个人 Blog

日期：2026-07-07

这次实践的目标是把个人 Blog 内容保存到 GitHub 仓库中，并通过 GitHub Actions 自动发布到 GitHub Pages。为了把流程先跑通，我选择使用静态 HTML 和 CSS 编写页面，这样不需要额外安装复杂的构建工具。

## 完成过程

我先在本地准备了 Blog 首页、文章页面和样式文件。随后为项目添加 GitHub Actions 工作流，让每次提交到 main 分支后自动上传站点文件并部署到 GitHub Pages。仓库推送到 GitHub 后，只需要在 Pages 设置中选择 GitHub Actions 作为发布来源，工作流成功运行后网站就可以访问。

## 本次收获

通过这次实践，我熟悉了公开仓库、静态页面、自动化部署和 Pages 发布之间的关系。GitHub Actions 不是只负责运行命令，它还可以把仓库中的页面文件作为发布产物交给 GitHub Pages。以后更新 Blog 时，只需要修改文章并提交，网站就会自动刷新。

