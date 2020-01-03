HTML5-pre,code标记
=================

## 知识点

* pre
* code

### pre

pre标记显示格式化后的文本，包围在pre标记内的文本通常会保留空格和换行符，而文本也以等宽字体来显示。

通常的情况下，浏览器会按照下面的规则表示网页中自然段内的内容。

* 连续的半角空格会被压缩成1个半角空格
* Tab文字会被处理为1个半角空格
* 换行符会被处理为1个半角空格
* 自然段等文本会自动按照浏览器的宽度自动换行显示

而在pre标记中，以上的规则全是无效的，pre内文本的内容会按照html内固定的格式显示到浏览器上，不过会因为
浏览器的不同，显示效果也有小的差异。

### code

code标记是计算机语言代码的描述，如果在网页中有程序源代码等描述的话，则应该使用code标记，并且可以配合pre标记使用。

另外，根据程序语言的种类不同，我们可以为code标记加上［language-xxx］的class属性，是文档更加清晰话。

## 综合例

~~~html
<pre>
    <code class="language-javascript">
        var myStr = "Hello world!";
        var myInt = 1;
        
        if (myInt == 1) {
            alert(myStr);
        }
    </code>
</pre>
~~~

## 源代码

https://github.com/komavideo/LearnHTML5

## 小马视频频道

http://komavideo.com
