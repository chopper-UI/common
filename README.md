# common

---

// description

---

## 演示

<link type="text/css" rel="stylesheet" media="screen" href="src/common.css">
<link type="text/css" rel="stylesheet" media="screen" href="src/ex.css">

__注意：__示例中以.ex开头的class在实际使用场景中是不必要的，此类class只为可视化文档的展示做辅助作用。

### 文本类

````html
<table class="ex-table">
    <caption>
        用来控制文本的表现形式
    </caption>
    <tbody>
        <tr>
            <td>.fn-text-wrap</td>
            <td>
                控制长单词断行，一般用作处理可能出现连续无空格的单词输出
<pre>
.fn-text-wrap{
    word-wrap: break-word;
}
</pre>
            </td>
            <td>
                <p class="fn-text-wrap">
                    asdfkjvoasdfajsldfjalsfjlanvslaskdfalskdjgalsgjasnlaskfasljhzcvhaskldfhlasdfalsdfhasldkfalskdfhalskdhfalskhdflakshdflaksdhfkashdflakshdflkashdflkhdsfalskdfhalsdfhasdflasdfh
                </p>
            </td>
        </tr>
        <tr>
            <td>.fn-text-notice</td>
            <td>
                表示一个需注意的文字
<pre>
.fn-text-notice{
    color: red!important;
}
</pre>
            </td>
            <td>
                带星号<span class="fn-text-notice">*</span>是<span class="fn-text-notice">必填</span>的
            </td>
        </tr>
        <tr>
            <td>.fn-text-stress</td>
            <td>
                表示强调的文字
<pre>
.fn-text-stress{
    font-weight: bold!important;
}
</pre>
            </td>
            <td>
                如果你需要发言，那么请<a class="fn-text-stress" href="">注册</a>一个帐号。
            </td>
        </tr>
    </tbody>
</table>
````

### 对齐类

````html
<table class="ex-table">
    <caption>
        简单方便将文字对齐的类
    </caption>
    <tbody>
        <tr>
            <td>.fn-align-left</td>
            <td>
                左对齐
<pre>
.fn-align-left{
    text-align: left!important;
}
</pre>
            </td>
            <td>
                <p class="fn-align-left">
                    文字在这里
                </p>
            </td>
        </tr>
        <tr>
            <td>.fn-align-right</td>
            <td>
                居中对齐
<pre>
.fn-align-center{
    text-align: center!important;
}
</pre>
            </td>
            <td>
                <p class="fn-align-center">
                    文字在这里
                </p>
            </td>
        </tr>
        <tr>
            <td>.fn-align-right</td>
            <td>
                右对齐
<pre>
.fn-align-right{
    text-align: right!important;
}
</pre>
            </td>
            <td>
                <p class="fn-align-right">
                    文字在这里
                </p>
            </td>
        </tr>
    </tbody>
</table>
````
