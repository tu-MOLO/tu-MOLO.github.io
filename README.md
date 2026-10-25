# tu-MOLO.github.io

这个仓库只负责**发布**，不存放站点源码。

发布流程由 [.github/workflows/pages.yml](.github/workflows/pages.yml) 完成：

1. 拉取源码仓库 [tu-MOLO/hugo-main](https://github.com/tu-MOLO/hugo-main) 的 `main` 分支
2. 用 Hugo（0.168.0 extended）构建到 `public/`
3. 通过 GitHub Pages 发布

## 触发方式

- 在本仓库推送任意提交
- 每天 02:00（北京时间）自动构建
- 在 Actions 页面手动运行 `pages` 工作流

写作与本地预览的说明见文章：<https://tu-molo.github.io/p/how-to-write/>
