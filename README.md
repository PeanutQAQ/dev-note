# Node.js Deploy

#### 部署前准备
0. 安装 git & vscode 等
1. 安装 nvm 管理 Node 版本
2. 安装 pm2 启动 Node 程序
3. 安装 Nginx 管理各个 Node 项目的端口
  + 运行 nginx -t 查找 nginx 安装位置
  + 区分 conf.d 与 nginx.conf 的关系
  + 在 conf.d 中拆分不同服务的 Nginx 配置
  + 增加 https 证书
4. 采用 NginxConfig 生成 Nginx 配置文件
5. 安装 serve 做静态服务器


  项目   |  架构
:--------:|:-------:
Medium  | 前后端一个仓库 后端 express
blog-FE | 前端代码 用 serve 起一个静态服务
blog-BE | 后端代码 Koa


#### 第三方快速部署工具
https://app.netlify.com/teams/peanutqaq/sites netlify 快速部署自己的项目
https://ngrok.com/ ngrok 把自己本地项目反向代理到网上
