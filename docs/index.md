# 欢迎来到 Novi 文档

## 本地部署

请先确保安装了 [rye](https://rye-up.com/guide/installation/#installing-rye) 和 [Docker](https://docs.docker.com/get-docker/)。

克隆 [`novi`](https://github.com/project-novi/novi) 项目到本地，进入项目文件夹并使用以下命令启动服务：

```bash
rye build -a
docker build -t novi .
```
