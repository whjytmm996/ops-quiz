# 网络运维刷题宝典 · v74

6 阶段 39 课，工单驱动：先看现场与用途，再学判断和命令，最后进实验、做 6 题闭卷验收。整个应用是单文件 HTML，无构建依赖。

## 在线访问

GitHub Pages 地址：https://whjytmm996.github.io/ops-quiz/

发布源已准备为 `gh-pages` 分支 `/ (root)`。首次启用需仓库管理员在 `Settings → Pages` 选择一次 `Deploy from a branch`，之后每次推送到 `main` 自动同步。

## 本地使用

下载仓库根目录的 `index.html`，直接用浏览器打开。

## 版本基准

- 主文件：`index.html`
- 初版来源：v74
- SHA-256: `D3C51B7C6C59399739A59E02DDBAEE053789001C3320D7BF7305D916FD6E23E8`
- 内容：6 阶段 / 39 课 / 22 个实验 / 386 题题库
- 验收：内容审计 hard=0 errors=0；实验 22/22 pass

## 说明

`.github/workflows/deploy.yml` 只负责把 v74 单文件导入并同步到 `gh-pages` 分支；页面由 GitHub Pages 从该分支发布。
