HTML5-p,blockquote标记
=====================

## 知识点

* p（自然段）
* blockquote（内容引用）

### p

p标记是英文paragraph，表示文章的自然段。

### blockquote

blockquote标记是以自然段为单位的引用，主要是记述从其他地方引用来的内容。

* cite
 + 引用出处的描述，如果引用的内容是来自某一个网站的话，则在这里标出网站的URL，
 如果是引用一些书籍的内容，可以把书号（ISBN）也一起写进来。

## 综合例

~~~html
<article>
    <header>
        <h1>文章标题</h1>
    </header>
    <p>文章自然段1...</p>
    <p>文章自然段2...</p>
    <p>文章自然段3...</p>
    <blockquote cite="urn:isbn:1234567890">
        <p>引用内容自然段1...</p>
        <p>引用内容自然段2...</p>
        <p>引用内容自然段3...</p>
    </blockquote>
</article>
~~~

## 源代码

https://github.com/komavideo/LearnHTML5

## 小马视频频道

http://komavideo.com
