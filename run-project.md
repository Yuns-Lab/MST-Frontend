# 运行指南

此项目基于 Node.JS 开发，但你在本仓库看到的是打包后的结果

---

1. 下载 Release 中的最新版代码

2. 打开 mst.config.js，修改其中的配置项
    - server_https：如果你的服务器允许使用 https 链接，请设置为 true 否则设置为 false
    - server_host：你的服务器的 IP 或者域名
    - server_port：你的服务开放的端口

3. 将整个项目作为网页部署即可
    - 在 Linux 上建议使用 OpenResty 部署