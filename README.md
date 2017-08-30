### nvm 安装 node(javascript运行环境)

* 安装 nvm
* curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.29.0/install.sh | bash
* 安装 node
* nvm install v5.10.1
* node -v 查看版本
  npm -v 查看版本
* 设置默认 node 版本
* nvm alias default 5.10.1
************
### NPM的使用方法

* npm init(项目包package.json)
* npm i jquery --save(装非工具包 例：jquery)
* npm uninstall jquery(卸载包)
* npm i jquery@1 --save(装新的jq版本)
* npm i webpack --save-dev(装工具包压缩版)
* npm i(下载所有包)
* 仓库下创建 .gitignore
* 全局安装
  npm install gulp -g
* 可以使用以下命令来查看所有全局安装的模块：
  npm ls -g

************
### 执行node

* node 文件
* nvm use stable
************
### 从npm中拿到下载的jquery包(第三方模块／核心模块)

* var $ =require('./node_modules/jquery')
* var $ =require('fs')
