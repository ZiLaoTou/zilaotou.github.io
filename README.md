# Ruike Cao / 曹瑞珂 · Academic Homepage

访问地址：**https://zilaotou.github.io/**

基于 [Guanting Dong 的主页](https://github.com/dongguanting/dongguanting.github.io) 定制，保留 Jekyll / AcadHomepage 模板的布局、SCSS 与字体资源。模板来源提交：`640d4c43158a7b3c9b914a092536250f0551198d`。原 MIT 许可证见 `LICENSE`。

## 更新内容

- `_pages/about.md`：个人简介、教育、实习单位、奖项。
- `_data/publications.yml`：论文题目、完整作者、会议/期刊、论文与代码链接；`type` 为 `publication` 或 `preprint`。
- `_config.yml`：姓名、学术邮箱、Google Scholar、GitHub 与网站地址。
- `images/avatar-20261106.jpg`：当前个人照片。
- `_data/navigation.yml`：顶部导航。
- `assets/css/custom.css`：在原模板上增加的样式与手机适配。

修改后提交并推送到 `main`，GitHub Pages 内置的 Jekyll 构建服务会自动构建并部署。可以在仓库的 **Actions** 中查看 `pages build and deployment` 的进度；仓库 **Settings → Pages → Source** 应为 **Deploy from a branch**，分支为 **main**，目录为 **/ (root)**。不需要维护自定义 Actions 工作流或额外的 workflow 授权。

## 本地预览

在安装了现代 Ruby 和 Bundler 的环境中执行：

```sh
bundle install
bundle exec jekyll serve
```

打开终端显示的本地地址（通常是 `http://127.0.0.1:4000`）。使用 GitHub Pages 发布不需要本机安装 Ruby。

## 内容来源

个人与教育信息依据本人提供的简历及 2026 年申请材料整理；论文信息核对了本人 [Google Scholar](https://scholar.google.com/citations?user=eJp0l-QAAAAJ&hl=en)、[ACL Anthology](https://aclanthology.org/2026.findings-emnlp.247/)、arXiv 和 DOI 页面。申请中的奖项没有作为已获奖项列出。引用数量会变化，页面通过 Scholar 链接提供最新数据。

公开仓库仅包含主页所需的学术介绍和照片，未包含原始申请表、签名、证件、学号、手机号或完整简历文件。
