# 网站性能优化项目

[GitHub Pages Demo](https://janicejiang.github.io/frontend-nanodegree-mobile-portfolio/)

# 安装
克隆本项目到本地, 打开index.html本地路径即可运行

# PageSpeed达标概述
- max-480px.css 和 print.css, 通过媒体查询避免阻塞渲染.
- async异步加载
- 优化图片资源/perfmatters.js
- WebFont加载字体
- 内联 style.css

# 去除卡顿概述
- 重构 changePizzaSizes function
- 添加will-change属性避免图层重绘
- 减少pizza数量

# 指南

####Part 1: 优化 index.html 的 PageSpeed Insights 得分

以下是几个帮助你顺利开始本项目的提示：

1. 将这个代码库导出
2. 你可以运行一个本地服务器，以便在你的手机上检查这个站点

```bash
  $> cd /你的工程目录
  $> python -m SimpleHTTPServer 8080
```

1. 打开浏览器，访问 localhost:8080
2. 下载 [ngrok](https://ngrok.com/) 并将其安装在你的工程根目录下，让你的本地服务器能够被远程访问。

``` bash
  $> cd /你的工程目录
  $> ./ngrok http 8080
```

1. 复制ngrok提供给你的公共URL，然后尝试通过PageSpeed Insights访问它吧！可选阅读：[更多关于整合ngrok、Grunt和PageSpeed的信息](http://www.jamescryer.com/2014/06/12/grunt-pagespeed-and-ngrok-locally-testing/)。

接下来，你可以一遍又一遍的进行配置、优化、检测了！祝你好运！
