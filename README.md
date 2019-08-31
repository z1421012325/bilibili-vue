# bilibili-vue

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
## 新手上路 后端学习前端,提升竞争力
##先从最简单也是对后端程序员最好的vue-cli脚手架开始,不过html和js基础都还行,就是css不行,所以此项目难免会有一些样式辣眼睛,待我学成归来必有重构
## bilibili 仿制pc端页面




#1.记录使用vue-cli过程
1.1先下载node.js 其中vue和npm依赖于node,去官网下载完成安装包,安装完成查看版本安装情况
```$xslt
node -v
```
查看是否版本有安装,如果安装之后没有显示版本,查看是否为全局环境变量,如果还不行...emmm 请百度谷歌
[我还能怎么办](http://img.99danji.com/uploadfile/2017/0729/20170729114024311.jpg)

1.2 npm 属于node再带的安装程序,相当于python的pip,go的go get,以免万一也可以使用命令行查看版本情况
```$xslt
npm -v
```

1.3 下载vue
```$xslt
npm install vue
```
如果下载过慢,请使用国内淘宝源
```
npm config set registry=http://registry.npm.taobao.org
```

1.4 下载包管理工具,用于对之后的项目文件进行打包
```$xslt
npm install webpack -g
```
查看版本号
```$xslt
webpack -v
```

1.5 安装vue-cli
```$xslt
npm install --global vue-cli
```
查看版本号(大写V)
```$xslt
vue -V
```

在这之前差不多下载完成了,接下来就是搭建脚手架,快速进行一个项目搭建
#2vue-cli快速搭建
2.1 选择一个文件夹或者mkdir创建一个作为项目总文件夹
```$xslt
vue init webpack 项目名称
如果是vue3.0以上 则使用vue create 项目名
```
2.2项目创建选项
在进行项目创建时,vue会让用户选择怎么创建,是否遵循格式,以及包依赖下载,我习惯只安装vue-router和npm自动帮我安装,其他都是no(含有y/n),请他情况请根据实际情况来看,不懂请百度谷歌...我说的不是很让人懂

2.3 项目文件创建完成
```$xslt
# 根据命令行创建完成之后的提示cd进入项目文件中
cd 项目名
# npm install    安装一些package.json中指定的模块
```


#3 运行项目
```$xslt
npm run dev
```

#4 打包项目
```$xslt
# 进入src文件夹
npm run build
# 会在根目录生成dict的文件夹,其中的文件就是放置在生成环境的资源文件
```

