# node-toolbox
some useful tool that help you write node projects

1. zeit/ncc - 一个打包 node 项目内 node-modules 的工具。
2. minimist - 一个轻量级解析 process.argv 的工具。
3. chalk - 一个可以给 node 输出着色的工具。
4. progress - 一个 node 输出框的步骤条。
5. inquirer - 一个在命令行页面对话的复杂交互。
6. npm - 
    npm update 更新包 
    npm root -g 查询全局包的路径 
    可以在 package.json 里配置 eslint 或者 babel 这个跟每个 dev 工具有关，查看对应的配置说明。
    npm list packageName --depth=0 - 查看第一层包
    npm view packageName version - 查看已安装的包版本
    npm view packageName versions - 查看可安装的包的版本信息
    npm uninstall packageName 从 node_modules 移除
    npm uninstall -S packageName 移除并在 dependency 删除 -S || --save
    npm uninstall -D packageName 移除并在 devdependency 删除 -D || --save-dev
    npm install --production 不安装 dev
7. cowsay
8. forever - 类似 pm2 一个启动 node 进程的工具
9. nodemon - 开发 node 热更新工具 https://nodemon.io/
10. npx 可以做很多事：本质上安装然后擦除
      1. 不安装的执行很多 commond line 包
      2. npx node@8 -v 不安装 nvm 等工具使用 node 的不同版本
      3. 通过 url 运行代码npx https://gist.github.com/zkat/4bc19503fe9e9309e2bfaa2c58074d32
11. 对比 node 和 浏览器的 event loop 不同
12. 区分 tasks microtasks quene job quene https://jakearchibald.com/2015/tasks-microtasks-queues-and-schedules/

