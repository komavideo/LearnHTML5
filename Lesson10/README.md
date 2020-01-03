HTML5-nav,aside标记
==================

## 知识点

* nav（导航）
* aside（补充说明）

### nav

nav标记表示网页内导航的部分，比如说页头的导航条，页面两侧的边条等等，
或者是文章的轮廓（outline）部分的内容。

~~~html
<nav>
    <h1>主菜单</h1>
    <ul>
        <li><a href="index.html">主页</a></li>
        <li>新闻</li>
        <li>博客</li>
        <li>我们</li>
    </ul>
</nav>
~~~

### aside

aside标记是补充说明，脚注，注解等与页面主要内容没有直接关系，仅仅是一些附加说明性的内容。

~~~html
<article>
    <p>这是html5制作的网页，它能够实现很多以前用flash(*1)才能实现的效果。</p>
</article>
<aside>
    <h3>名词解释</h3>
    <p>*1:flash是adobe公司出品的一种网页插件，可以实现更多的网页多媒体效果。</p>
</aside>
~~~

## 综合例

博客边条的例子

~~~html
<aside>
    <nav>
        <h3>最近博文</h3>
        <ul>
            <li>学习html5有感</li>
            <li>昨天的日记</li>
            <li>新的一年</li>
        </ul>
    </nav>
    <nav>
        <h3>博文分类</h3>
        <ul>
            <li>技术文章(5)</li>
            <li>生活随笔(3)</li>
        </ul>
    </nav>
</aside>
~~~

## 源代码

https://github.com/komavideo/LearnHTML5

## 小马视频频道

http://komavideo.com
