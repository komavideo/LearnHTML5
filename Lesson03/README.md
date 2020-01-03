HTML5-meta标记
=============

## 知识点（meta标记）

* name
* http-equiv
* content
* charset

### meta.name

指定要描述的信息的名称，比如：keywords,author等等，之后配合content属性描述内容

~~~html
<meta name="author" content="小马">
<meta name="description" content="HTML5的基础知识学习网页，这个网页中学习meta标记">
<meta name="keywords" content="html,html5,meta,seo">
~~~


### meta.http-equiv

设定网页的头信息，可以用于设置http协议传输时的头信息，也可以设定一些网页的行为。

~~~html
<!-- 网页300后自动刷新 -->
<meta http-equiv="refresh" content="300">
<!-- 网页30秒后跳转到other.html -->
<meta http-equiv="refresh" content="30;URL=other.html">
~~~

### meta.content

和name,http-equiv等属性配合使用，记载属性的描述内容。

**几种属性**

* content-type
* default-style
* refresh
* set-cookie

| 属性名 | 属性描述 |
|:------|:--------|
| content-type  | 指定http头部信息的文字编码 |
| default-style | 指定优先使用的样式单（stylesheet） |
| refresh       | 用于网页的自动刷新或者页面跳转 |
| set-cookie    | 设置页面的cookie，不过现在已经不推荐使用 |

### meta.charset

在head中描述，指定网页的文字编码，目前推荐使用utf8编码。

~~~html
<meta charset="utf-8">
~~~

## 综合例

为搜索引擎抓取机器人准备一些信息。

~~~html
<!-- 这段代码可以禁止搜索引擎缓存和跟踪咱们的网页 -->
<meta name="robots" content="noindex,nofollow">
~~~

## 源代码

https://github.com/komavideo/LearnHTML5

## 小马视频频道

http://komavideo.com
