### nvm 安装 node

* 安装 nvm
* curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.29.0/install.sh | bash
* 安装 node
* nvm install v5.10.1
* node -v 查看版本
    npm -v 查看版本
* 设置默认 node 版本
* nvm alias default 5.10.1

### NPM的使用方法

* npm init(项目包package.json)
* npm i jquery --save(非工具包 例：jquery)
* npm uninstall jquery(卸载包)
* npm i jquery@1 --save(装新的jq版本)
* npm i webpack --save-dev(工具包压缩)
* npm i(下载所有包)
* 仓库下创建.gitignore
