构建前后端 Docker 镜像并推送到 Docker Hub 仓库 iruiiii。

1. 构建后端镜像: docker build -t iruiiii/clawith-backend:latest ./backend
2. 构建前端镜像: docker build -t iruiiii/clawith-frontend:latest ./frontend
3. 推送后端镜像: docker push iruiiii/clawith-backend:latest
4. 推送前端镜像: docker push iruiiii/clawith-frontend:latest

前后端构建可以并行执行。完成后报告两个镜像的 digest。
