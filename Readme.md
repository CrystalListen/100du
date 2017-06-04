# 电子商务网站--100du
===============================

## 简介

这是妙味课堂实战练习的一个项目，通过构建完整的电子商务网站，熟悉HTML布局和CSS样式管理。此外，由JavaScript实现了某些功能，例如，搜索功能。

## 如何执行

最简单的运行方式是直接双击'index.html'文件，然后在浏览器中运行。因为这个项目中还没有涉及到与后台的交互，因此，可以直接双击运行

也可以通过服务器运行。安装NodeJS服务器，并使用'http-server'运行该项目，方法如下：

首先，确保安装了全局的'npm'
参照[文章](https://www.digitalocation.com/community/tutorials/how-to-install-node-js-with-nvm-node-version-manager-on-a-vps) 安装npm或者打开[Node.js 官网](https://github.com/creationix/nvm)

其次，安装全局的'http-server'服务
```bash
npm install -g http-server
cd 100du #确保在项目根目录下运行
http-server -c-1 -o # -c-1 禁用缓存 -o 服务器打开后立即打开浏览器运行项目
```



