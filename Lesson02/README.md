HTML基本要素
===========

## 知识点

* DOCTYPE
* html
* head
* body

### DOCTYPE

文档类型，就是这个网页使用的HTML版本，简单地说就是在这个网页中能够使用哪些标记tag。

网页中可以使用的tag都是在DTD（Document Type Definition）中定义的，每个版本的DTD文档
所定义的标记是不同的，对于初学者来说理解DTD的概念可能有一点难，不过也不用担心，
HTML5的网页是不记述DTD的，所以对于初学HTML5的朋友来说，你完全可以当它不存在。

**使用例**

html4:
~~~html
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
~~~

html5:
~~~html
<!DOCTYPE html>
~~~

### html

HTML网页文档的根要素，或者叫做根标记，是网页文档中最外层的标记。

**使用例**

~~~html
<html 属性="属性值">
〜〜〜
</html>
~~~

**特殊属性**

* manifest
 + 指定网页缓存文件，可以让用户在离线的时候（比如说在飞机上时）也能够访问页面。
~~~html
<html manifest="example.appcache"></html>
~~~
* xmlns
 + 设置html文档的名空间，比如把网页设置成xhtml的时候可以用这个属性
~~~html
<html xmlns="http://www.w3.org/1999/xhtml"></html>
~~~
* lang
 + 设置网页描述语言，比如设置成中文：
~~~html
<html lang="zh"></html>
~~~

### head

网页头部的信息描述区域，比如：网页的标题title，和网页信息描述标记meta等等网页头部信息。

**使用例**

~~~html
<head>
〜〜〜
</head>
~~~

### body

网页具体内容部分，在html标记内只能有一个body标记。

**使用例**

~~~html
<body>
〜〜〜
</body>
~~~

## 综合例

~~~html
<!DOCTYPE html>
<html lang="zh">
    <head>
        <meta charset="utf-8">
        <title>网页标题（显示在浏览器上）</title>
        <meta name="description" content="网页内容的简单描述">
        <meta name="keywords" content="网页关键词（用逗号分隔开）">
        <link rel="/css/style.css">
        <script src="/js/myscript.js"></script>
    </head>
    <body>
        <header>网页头部内容</header>
        <main>网页主要内容</main>
        <nav>网页的导航内容</nav>
        <footer>网页的页脚内容</footer>
    </body>
</html>
~~~

## 源代码

https://github.com/komavideo/LearnHTML5
