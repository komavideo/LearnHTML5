HTML5-h1~h6,header,footer,address标记
====================================

## 知识点

* h1~h6（标题）
* header（头部区）
* footer（脚部区）
* address（地址）

### h1~h6

h1,h2,h3,h4,h5,h6是各种区块（section）的标题，根据标题的标识数字不同，
显示的字体的大小，代表的意思也都不同。h1表示最重要的标题，一般用于表示整个
网页的主要内容，而h6表示最底层的小标题，仅仅说明文章某一个部分的内容。
我们应该根据页面的情况，选择使用不同大小的标题。

~~~html
<body>
    <article>
        <header>
            <h1>这里是文章的大标题</h1>
        </header>
        <section>
            <h2>这是副标题1</h2>
            <p>...</p>
            <p>...</p>
            <p>...</p>
        </section>
        <section>
            <h2>这是副标题2</h2>
            <p>...</p>
            <p>...</p>
            <p>...</p>
        </section>
    </article>
</body>
~~~

### header

header标记是表示文章或区块（section）的头部，通常与h1~h6标记配合使用，在页面导航，
文章结构描述等场合最为适用。

**文章的头部**

~~~html
<article>
    <header>
        <h1>文章的标题</h1>
        <p><time datetime="2016-01-15T00:00:00+09:00">发表日：2016年1月15日</time></p>
    </header>
</article>
~~~

**导航条**

~~~html
<body>
    <header>
        <nav>
            <h1>主菜单</h1>
            <ul>
                <li>主页</li>
                <li>新闻</li>
                <li>军事</li>
                <li>游戏</li>
            </ul>
        </nav>
    </header>
</body>
~~~

### footer

footer标记与header相反，它是表示文章或区块的脚部，比如描述作者信息，文章出处，URL链接等等。

~~~html
<footer>
    <h3>作者：小马</h3>
    <p>网址：http://xxx.xxx.xxx/xxx.html</p>
</footer>
~~~

### address

address标记一般用于联系方式的描述，比如住址，邮件等等信息。

~~~html
<footer>
    <address>
        如果你想什么问题，请与我联系。(<a href="mailto:aaa@aaa.com">给我发邮件</a>)
    </address>
</footer>
~~~

## 源代码

https://github.com/komavideo/LearnHTML5

## 小马视频频道

http://komavideo.com
