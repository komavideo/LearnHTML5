HTML5-a标记
============

## 知识点

* a标记（网页链接）

### a标记

设置网页的链接，实现画面转移，当然也可以打开新的窗口显示网页。

**使用属性**

* href
 + 指定链接的网页网址URL或者符号（#）
* target
 + 链接网页的打开帧，即可以在新窗口打开，也可以在父帧打开等等
   * _blank：新窗口
   * _parent：父帧（frame）
   * _self：自窗口（自己帧）
   * _top：最顶层的帧（frame）
* rel
 + 链接网页与当前网页的关系
   * alternate：本网页的另一个版本，例如：打印专用等
   * author：该网页的作者网页
   * bookmark：该网页的书签
   * help：该网页的帮助
   * icon：图标
   * license：该网页的版权页
   * next：下一页
   * nofollow：不重要的链接网页，告诉搜索引擎不要跟踪这个链接
   * noreferrer：用户点击链接时，不发送referrer信息（http传输协议部分）
   * prefetch：链接网页事先缓存起来
   * prev：上一页
   * search：搜索功能
   * tag：本网页使用的tag信息网页
* media
 + 链接内容的媒体类型（screen:屏幕，print:打印机，projection:投影仪等等）
* hreflang
 + 链接内容的语言类型（en,zh等等）
* type
 + 链接内容的MIME类型

## 综合例

**导航条**

~~~html
<nav>
    <ul>
        <li><a href="http://www.sina.com.cn" target="_blank">新浪</a></li>
        <li><a href="http://www.163.com" target="_parent">网易</a></li>
        <li><a href="http://www.sohu.com" target="_self">搜狐</a></li>
        <li><a href="http://www.baidu.com" target="_top">百度</a></li>
        <li><a href="#taobao">淘宝</a></li>
    </ul>
</nav>
~~~

## 源代码

https://github.com/komavideo/LearnHTML5

## 小马视频频道

http://komavideo.com
