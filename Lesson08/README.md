HTML5-template标记
=================

## 知识点

* tempalte

### tempalte

模版标记template可以定义一个HTML的代码片段， 然后通过脚本语言（javascript）向网页中
动态生成内容，减少html的重复编码，增加代码的复用性，从而提高工作效率。

## 综合例

~~~html
<table border="1">
    <thead>
        <tr>
            <th>学号</th>
            <th>姓名</th>
            <th>年龄</th>
        </tr>
    </thead>
    <tbody>
        <template id="myTemplateName">
            <tr>
                <td></td>
                <td></td>
                <td></td>
            </tr>
        </template>
    </tbody>
</table>

<script type="text/javascript">
var dataList = [
    { no:1, name:"章三", age:20 },
    { no:2, name:"李四", age:16 },
    { no:3, name:"王五", age:18 },
];

var template = document.querySelector("#myTemplateName");
for (var i = 0; i < dataList.length; i++) {
    var data = dataList[i];
    var cloneRow = template.content.cloneNode(true);
    var cells = cloneRow.querySelectorAll("td");
    cells[0].textContent = data.no;
    cells[1].textContent = data.name;
    cells[2].textContent = data.age;
    template.parentNode.appendChild(cloneRow);
}
</script>
~~~

## 源代码

https://github.com/komavideo/LearnHTML5

## 小马视频频道

http://komavideo.com
