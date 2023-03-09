# 搭建自己的博客网站

## 下载安装`node`

[点击打开node网站](https://nodejs.org/en/)

> https://nodejs.org/en/

[点击下载](https://nodejs.org/dist/v18.14.2/node-v18.14.2-x64.msi)

* 安装略
* 一直`next`就齐活了

## 采用前端`vuepress`制作博客网站

* 打开vuepress中文网

[点击打开](https://www.vuepress.cn/)

> https://www.vuepress.cn/

教程位置

> https://www.vuepress.cn/guide/getting-started.html

## 搭建环境

第一步:创建一个WebBlog目录(名字可以自己起)

第二步:用命令进行配置

``` shell
cd WebBlog # 终端进入你创建目录
# 可以利用vscode内置终端操作
npm init -y # 初始化你的目录 不加-y需要自己配置
# 执行完毕项目目r录多出一个package.json文件
npm install -D vuepress # 安装vuepress 

```

第三步:`WebBlog`目录下创建`docs`目录

> docs是系统名称 你所有的`Markdown`文档都是在这里放的