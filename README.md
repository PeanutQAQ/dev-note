# Node.js Deploy

#### 部署前准备
0. 安装 git & vscode 等
1. 安装 nvm 管理 Node 版本
2. 安装 pm2 启动 Node 程序
3. 安装 Nginx 管理各个 Node 项目的端口
  + 运行 nginx -t 查找 nginx 安装位置
  + 区分 conf.d 与 nginx.conf 的关系
4. 采用 NginxConfig 生成 Nginx 配置文件


  项目   |  架构
:--------:|:-------:
Medium  | 后端用 Koa
pure-Fe | 后端用 Serve 
