---
title: 学习记录
date: 2022-01-22
cover: https://cdn.jsdelivr.net/gh/cxjwuu/ImgHosting@master/img-db1f631f0eb33ecff99a70fd1fa0d2d0.6b3oggtl8680.webp
---
welcome to 藏小剑的小居

## 今天是写markdown的第二天 
### 学习记录 以修改为主题`nexmoe`为例
1. 首先是主题的选择 在hexo的主页中主题中选择自己喜欢的 我选择的是nexmoe这个主题（主要是首页的动漫头像有点好看）
2. 点击主题后，进入到该主题后，点击使用说明 

![](https://cdn.jsdelivr.net/gh/cxjwuu/ImgHosting@master/image.13iix8hfo7ek.webp)

3. 按照快速说明中的，在根目录下运行代码`npm i hexo-theme-nexmoe`

>题外话 在根目录下调用windows terminal 输入指令 `code .`可以快捷将博客文件用vscode打开，我觉得有点小酷。

4. 在安装主题后，运行终端指令`npm i --save hexo-wordcount`
这个是获得Wordcount的支持
5. 安装后我们来到vscode的博客文件夹，在根目录`_config.nexmoe.yml`中修改我们博客的名字阿什么的

![](https://cdn.jsdelivr.net/gh/cxjwuu/ImgHosting@master/image.1rt2zh6rjtb4.webp)

6. 虽然下一步就是运行`hexo s --debug`来对我们的主题进行运行，但是实际我们下一步我们要在文件夹`themes`中建立一个文件`_config.nexmoe.yml`我们需要在这个文件夹中对主题元素进行配置，很多功能和文字的颜色和字体都在里面配置。

至此我们的博客大致上配置好了，但是最关键的是构建我们的图床和将博客链接网络
## 图床的构建
1. 首先我们需要在github构建我们的储存空间

![](https://cdn.jsdelivr.net/gh/cxjwuu/ImgHosting@master/image.24hgot8idtuo.webp)

2. 在建立好我们的仓库以后，我们需要在`setting`中找到`开发者setting`领取我们的`access tokens` 
3. 然后再pixc中输入我们的access tokens 允许它访问我们的仓库
这样我们的图床就进行了初步搭建

>题外话 其实vscode中的插件也可以进行图片插入，但是不知道为啥我电脑不行，怪事。

