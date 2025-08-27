# Bambu 快速学习

用于收集 3D 打印知识并管理模型文件的仓库。

## 目录结构
- `docs/` – 使用 MkDocs 构建的 Markdown 教程和笔记。
- `models/` – 可打印模型以及相关素材。
- `mkdocs.yml` – 文档站点的配置文件。
- `requirements.txt` – 构建站点所需的 Python 依赖。

请先将你的笔记添加到 `docs/`，并把模型文件放到 `models/` 下对应分类。

## 部署到 GitHub Pages

1. 安装依赖：`pip install -r requirements.txt`
2. 构建并发布到 `gh-pages` 分支：`mkdocs gh-deploy --force --remote-branch gh-pages`
3. 在 GitHub 仓库的 **Settings → Pages** 中选择 **Deploy from a branch**，并将分支设置为 `gh-pages`、路径为 `/`（首次部署后才会出现该分支）
4. 稍等片刻即可通过 `https://<用户名>.github.io/<仓库名>/` 访问站点

