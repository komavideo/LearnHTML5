HTML5-script,noscript标记
========================

## 知识点

* script
* noscript

### script

客户端脚本的代码区（javascript），同时也可以指定外部的脚本文件。

**使用属性**

* src
引用的外部javascript脚本文件的路径（URL）
* async和defer
当指定了src外部脚本参照文件时，async和defer属性用来指定javascript脚本的执行时间点。
这两个属性设置都是指当整个网页被浏览器装载完成后，执行脚本的内容。
如果两个属性同时指定时，async优先于defer属性执行。
* type
外部文件的MIME多媒体类型指定，比如：text/javascript
* charset
指定外部文件的文字编码，当网页编码和外部脚本编码不一致的时候，需要制定外部文件的编码，
否则会出现网页乱码的问题。

### noscript

noscript标记设置当客户端浏览器不支持脚本（javascript）时所显示的网页内容。
当然在支持脚本（javascript）的环境中，noscript标记里的内容会被浏览器忽略。

## 综合例

~~~html
<aside>
    <h1>广告区</h1>
    <noscript><p>您的网页不支持javascript脚本功能，请检查您的浏览器设置。</p></noscript>
    <div>
        <script type="text/javascript">
            var myStr = "Hello world!";
            alert(myStr);
        </script>
        <script src="/js/myscript.js"></script>
    </div>
</aside>
~~~

## 源代码

https://github.com/komavideo/LearnHTML5

## 小马视频频道

http://komavideo.com
