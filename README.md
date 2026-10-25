# tu-MOLO.github.io

这是 [tu-molo.github.io](https://tu-molo.github.io/) 的发布仓库。

## 这个网站是什么

张昊（MOLO）的个人博客，主要记录自己动手做的项目和一些技术笔记。目前收录的内容包括：

- **AI 培智教学平台**：面向特殊教育的个别化教育计划工作台，FastAPI + React 全栈
- **岭南丝竹工尺谱**：用 Web Audio 做零采样物理建模的民乐交互系统
- **ESP-Hi 灯光集群控制**：ESP 系列设备的局域网集群控制与校准
- **论文批量下载工具**：按 DOI / 题名批量抓取开放获取论文并整理命名

站点还提供[归档](https://tu-molo.github.io/archives/)、[关于](https://tu-molo.github.io/about/)、[友链](https://tu-molo.github.io/links/)和全站搜索。

## 为什么这里没有源码

本仓库只存放构建好的静态文件，不存放 Markdown 原文和主题配置。想读源码、看主题定制或参考写作配置，请访问：

- 站点源码：[tu-MOLO/hugo-main](https://github.com/tu-MOLO/hugo-main)

发布由 [.github/workflows/pages.yml](.github/workflows/pages.yml) 自动完成：拉取 `hugo-main` 的 `main` 分支，用 Hugo 构建后发布到 GitHub Pages。每次源码更新后由定时任务同步，也可以在本仓库手动触发 `pages` 工作流。

## 技术栈

| 部分 | 使用 |
|---|---|
| 静态站点生成 | Hugo 0.168.0 extended |
| 主题 | [hugo-theme-stack](https://github.com/CaiJimmy/hugo-theme-stack)（内置在源码仓库中） |
| 公式 | KaTeX |
| 托管 | GitHub Pages（GitHub Actions 构建部署） |

## 联系

- GitHub：[@tu-MOLO](https://github.com/tu-MOLO)
- 站点：[tu-molo.github.io](https://tu-molo.github.io/)

## 版权

站内文章除特别注明外均为本人原创，转载请署名并附原文链接。仓库中的主题与第三方依赖遵循各自的开源协议。
