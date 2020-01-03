HTML5-link标记
=============

## 知识点

* link

### link

link标记是链接外部文件时使用的标记，它能把外部文件的内容引用到当前的网页中来，
使当前的网页能够实现更多的功能。

**使用属性**

* href
> 指定链接外部文件的路径和文件名
* rel
> 引用资源(文件)的类型定义

| 属性名 | 属性描述 |
|:------|:--------|
| alternate  | 代替文档（种子，其他语言版本，其他格式等等） |
| author     | 网页的作者 |
| help       | 帮助文件的链接 |
| icon       | 网页的图标 |
| license    | 网页的版权 |
| next       | 如果是连续网页的时候，指定下一个网页 |
| prefetch   | 把链接外部资源时提前缓存起来 |
| prev       | 如果是连续网页的时候，指定上一个网页 |
| search     | 检索功能 |
| stylesheet | 样式单类型 |

* media
> 链接文件或资源属于哪一种媒体(media)，比如：screen,print,projection等等
* hreflang
> 链接文件的语言种类，比如在中文网页链接英文网页的时候，就要指定一下英文语言类型，让浏览器知道该如何解析网页的内容。
* type
> 指定链接文件的MIME类型。(比如：图片，图标，文本文件等等。关于MIME的概念，请参照一下百度百科)
* sizes
> 根据link链接文件的不同种类指定文件的大小。比如rel="icon"指定的时候，sizes就可以指定为［宽X高］的格式，
例如：[16x16]这种写法。

## 综合例

**链接外部样式单**
~~~html
<link rel="stylesheet">

<!-- 使用例 -->
<link rel="stylesheet" href="style1.css" media="screen">
<link rel="stylesheet" href="style2.css" title="主题样式文件">
<link rel="alternate stylesheet" href="style3.css" title="可选样式单">
~~~

**网站的图标指定，可以显示在浏览器的图标栏，也可以被手机读取作为网站的图标存入收藏夹**
~~~html
<link rel="icon">

<!-- 使用例 -->
<link rel="icon" type="image/png" href="img/favicon.png">
<link rel="shortcut icon" type="image/x-icon" href="img/favicon.ico">
<link rel="apple-touch-icon" type="image/png" href="img/apple-touch-icon.png">
~~~

**网站RSS种子指定**
~~~html
<link rel="alternate" type="application/rss+xml">
~~~

**网页作者个人的URL**
~~~html
<link rel="author" href="（例:http://自己的帐号的URL）">
~~~

**为搜索引擎的准备的网页的URL**
~~~html
<link rel="canonical">

<!-- 使用例 -->
<link rel="canonical" href="http://www.aaa.zzz/help.html">
~~~

## 源代码

https://github.com/komavideo/LearnHTML5

## 小马视频频道

http://komavideo.com
