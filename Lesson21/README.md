HTML5-文字标记cite,q,dfn,abbr
============================

## 知识点

* cite（作品标题）
* q（语句引用）
* dfn（短语定义）
* abbr（略称）

### cite

cite标记表示书籍，电影，音乐，演讲等的标题。在HTML4以前，cite标记表示引用出处，但从HTML5开始不仅仅表示引用出处，还可以表示作品名称等等。

~~~html
<blockquote cite="urn:isbn:1234567890">
    <p>
    我非常喜欢<cite>深入浅出MFC</cite>这本书。
    </p>
</blockquote>
~~~

### q

q标记表示语句单位的引用。在HTML5的规范中，q标记的前后不用使用引用符号，浏览器会自动识别并正常显示。另外，如果引用段落时，请使用blockquote标记。

**使用属性**

* cite
 + 引用内容的出处（引用其他网站内容的话，则表示URL：如果引用某本书籍的话，则表示书名或书号）

~~~html
<p>
    <q cite="http://baike.baidu.com/link?url=S2DsDvVleWd710zjadL2K6Ycpi2RNsKkmQf_9EXsNvJgOMrmwYbrDPwyprG1-BRniRekg7XkjfZyj337dhklGxE-3NatuKrrr1ntiRbB86y">
    勇者斗恶龙系列（ドラゴンクエスト，Doragon Kuesuto，Dragon Quest）是由日本艾尼克斯（现为史克威尔艾尼克斯）研发的电子角色扮演游戏（RPG）系列，其作为游戏史上最畅销的长寿游戏系列之一，在日本具有“国民RPG”之称。
    </q>
</p>
~~~

### dfn

dfn标记表示短语的定义，一般用于一些专有名词。

* dfn标记如果有title属性时，则title属性表示短语的定义。
* 如果dfn标记内只有abbr子标记，且abbr标记有title属性的话，则abbr的title属性表示短语的定义。

~~~html
<p>
<dfn title="http服务器软件">Apache</dfn>是最流行的<dfn>Web</dfn>服务器。
</p>
~~~

### abbr

abbr标记表示略称或省略语，可以与dfn标记配合使用。

~~~html
<p>
我们一起学习<dfn><abbr title="HyperText Markup Language">HTML5</abbr></dfn>网页标记语言。
</p>
~~~

## 源代码

https://github.com/komavideo/LearnHTML5

## 小马视频频道

http://komavideo.com
