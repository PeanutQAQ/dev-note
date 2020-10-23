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

TODO
1. docker 容器化
2. 使用 express
3. 制作脚手架生成前后端技术 template

#### 第三方快速部署工具
https://app.netlify.com/teams/peanutqaq/sites netlify 快速部署自己的项目
https://ngrok.com/ ngrok 把自己本地项目反向代理到网上
通过把 win10 的公钥上传到远程主机 摆脱了每次都要输入密码的问题：
原理参考：https://www.ruanyifeng.com/blog/2011/12/ssh_remote_login.html
windows无 copy-ssh-id解决：https://xmanyou.com/windows-10-ru-he-zai-widnows10shang-yong-sshdeng-lu-ubuntu/
