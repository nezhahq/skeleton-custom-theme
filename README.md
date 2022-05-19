# 哪吒主题开发环境

仅支持 `dashboard v0.13.16` 及更新版本。

1. 克隆当前仓库到本地
2. 修改 `data/config.yaml` oauth2 配置（回调连接可以填 `http://localhost` 的）
3. `docker-compose up`
4. 开始开发
5. 主题制作完成之后可以将 `theme-custom` 放置到服务器上的 `/opt/nezha/dashboard/theme-custom` 位置

## FAQ

- 如果不能使用 `80` 端口，在 `docker-compose.yaml` 中修改配置。
