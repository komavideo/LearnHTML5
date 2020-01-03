HTML5-style标记
==============

## 知识点

* style

### style

style标记描述CSS样式单的定义。（样式单文件的引用使用link标记）

**CSS样式**

指的是字体颜色，大小，粗细，背景色，边线颜色，边白，余白等等装饰性属性，提高页面的可读性。

**使用属性**

* media
指定使用样式单的媒体类型，例：
~~~html
<style media="projection" type="text/css">
    body {
        color: black;
        background: white;
    }
    em {
        font-style: normal;
        color: red;
    }
</style>
~~~
* type
样式单的MIME多媒体属性的制定，如果省略的话则是“text/css”。
* scoped(Firefox)
局部区域内的样式单设定，是样式单的内容仅仅在网页中的一部分区域生效。
不过目前仅仅Firefox支持scoped，希望今后有更多的浏览器支持这个属性。

## 综合例(Firefox)

~~~html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>scoped属性例子</title>
        <style type="text/css">
        div {
            border: solid 1px blue;
            margin: 20px;
        }
        </style>
    </head>
    <body>
        <div>
            <p>全局样式单的样式</p>
            <div>
                <style scoped="true">
                div {
                    border: solid 3px red;
                    background: gray;
                }
                </style>
                <p>scoped属性指定的样式单的样式</p>
            </div>
        </div>
    </body>
</html>
~~~

## 源代码

https://github.com/komavideo/LearnHTML5

## 小马视频频道

http://komavideo.com
