HTML5-title,base标记
===================

## 知识点

* title
* base

### title

设置网页的标题，可以显示在浏览器上。
title是head标记的子标记，所以要写在head标记当中。
这个也是搜索引擎优化（SEO）的一部分，所以给自己的网页起一个好的标题，
更容易被所有引擎找到。

~~~html
<html>
<head>
    <title>HTML5-title标记的用法</title>
</head>
</html>
~~~

### base

指定网页的基本路径或者目标帧，有两种基本的使用方法。

**注意点：**
base标记一定要写在head标记里面。

**href**

指定的网页跳转基准URL，如果不指定的话则默认为当前网站的当前路径。

~~~html
<base href="http://www.aaa.zzz/">
~~~

**target**

指定链接的跳转帧，如果不指定的话则是在当前页面中跳转。

~~~html
<base target="_blank">
~~~

## 综合例

~~~html
<base href="http://www.aaa.zzz/">
<base target="_blank">

<a href="index.html" target="_blank">主页</a>
<a href="news.html">新闻</a>
~~~

## 源代码

https://github.com/komavideo/LearnHTML5

## 小马视频频道

http://komavideo.com
