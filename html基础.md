## html基础 （2017.10.20）
1. `标题（Heading）是通过 <h1> - <h6> 标签进行定义的`
```
<h1> 定义最大的标题
<h6> 定义最小的标题
```
2. 
```
<br> 标签只是简单地开始新的一行
```
3. 
```
<fieldset> 标签可以将表单内的相关元素分组。
<fieldset> 标签会在相关表单元素周围绘制边框
```
4. 
```
<legend> 标签为 <fieldset> 元素定义标题
```
5. `示例`
```
<form>
  <fieldset>
    <legend>Personalia:</legend>
    Name: <input type="text"><br>
    Email: <input type="text"><br>
    Date of birth: <input type="text">
  </fieldset>
</form>
```
* 运行结果：
[代码示例运行结果](http://www.runoob.com/try/try.php?filename=tryhtml_fieldset)
6. 
* ` <ul>` : `表示无序列表,支持 HTML 中的全局属性,支持 HTML 中的事件属性`
* <li> 标签`定义列表项目`
* <li> 标签可用在`有序列表 (<ol>)` 和`无序列表 (<ul>) 中`
* `href`是`HypertextReference`的缩写，意思是`超文本引用`
* 运行结果
[代码示例运行结果](http://www.w3school.com.cn/tiy/t.asp?f=html_list_unordered)
7. `<a>`
* <a> 标签定义超链接，用于从一张页面链接到另一张页面。
* <a> 元素最重要的属性是 href 属性，它指示链接的目标。
```
在所有浏览器中，链接的默认外观是：
未被访问的链接带有下划线而且是蓝色的
已被访问的链接带有下划线而且是紫色的
活动链接带有下划线而且是红色的
```
8. `<em>`
* <em> 标签告诉浏览器把其中的文本表示为强调的内容。对于所有浏览器来说，这意味着要把这段文字用斜体来显示
* 如果你只想使用斜体字来显示文本的话，请使用 <i> 标签