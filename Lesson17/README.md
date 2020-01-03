HTML5-div,hr标记
===============

## 知识点

* div（流布局文字块）
* hr（水平线）

### div

div标记表示流布局的文字块内容。div标记本身没有特殊的意义，一般配合class,lang,title属性一起使用。
可以把div标记的意义理解为小于自然段标记p，但又大于文字块span的中间标记。（p＞div＞span）

PS：
在Bootstrap中经常使用div标记来进行页面布局等操作。

~~~html
<div lang="ja" class="japanese-part">
ここは日本語の訳文です。
</div>
~~~

### hr

hr标记是段落间的水平线，用于分割不同内容的段落。

~~~html
<p>...</p>
<hr/>
<p>...</p>
~~~

## 综合例

~~~html
<p>我爱唱小苹果。</p>
<hr/>
<p>
以上内容翻译成日语。
<div lang="ja">僕は【小ちゃいりんご】という歌が好きです。</div>
</p>
~~~

## 源代码

https://github.com/komavideo/LearnHTML5

## 小马视频频道

http://komavideo.com
