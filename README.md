# GitHub学习笔记
## 第一阶段
1.仓库（Repository） 是 GitHub 最基本的元素。 它们很容易被想象为项目的文件夹。 仓库包含所有项目文件（包括文档），并存储每个文件的修改历史记录。 仓库可以有多个协作者，仓库可以是公开的，也可以设置为私有的。

2.分支（Branch）是仓库的并行版本。默认情况下，您的仓库具有一个名为 main 的主分支。我们可以复制主分支创建其他分支，您安全地进行任何更改而不会影响”线上“主分支。 完成所需更改后，可以将分支合并回主分支以发布你的更改。

3.拉取请求（pull request）是 GitHub 上协作的核心。 拉取请求向他人展示你分支中发生的修改，并允许其他人接受、拒绝或者增加其他修改建议。 通过side by side 比较方式，显示两个分支中内容的差异，此拉取请求将保留您刚刚在分支上所做的修改，并提议将它们合并到main分支上。

4.合并（merge） 此操作将拉取请求中的修改合并到main分支中。

## 第二阶段
1. 打开一个拉取请求
  
2.分配给自己
  
3.发布评论
  
4.添加修改建议
  
5.批准修改

6.合并拉取请求
![940822fc-2c9f-4e01-9d2b-2baaf9f4dcd1](file:///C:/Users/32449/Pictures/Typedown/940822fc-2c9f-4e01-9d2b-2baaf9f4dcd1.png)

## 第三阶段

### Web相关领域的基础-HTML//JavaScript//CSS

### HTML 学习及常用标签：

HTML（HyperText Markup Language）是用于构建网页结构的标记语言。Web相关领域的基础-HTML//JavaScriptWeb相关领域的基础-HTML//JavaScriptWeb相关领域的基础-HTML//JavaScript`CSS``CSS``CSS`

1.<div>： 用于定义文档中的一个区域或节（division）。

2.<p>： 表示段落。

3.<a>： 创建链接。

4.<button>： 创建按钮。

### 理解块级元素与内联元素:

HTML元素可分为块级元素和内联元素。块级元素在页面上以块的形式展现，而内联元素则在行内显示。例如，<div>是块级元素，而<span>是内联元素。理解它们的特性对于页面布局和样式设置至关重要。

### HTML标签的样式：

学习如何使用HTML标签的样式是重要的一步。这可能包括文本样式（如字体、颜色）和布局样式（如边距、填充）。

### CSS 学习及基础概念：
CSS（Cascading Style Sheets）用于定义网页的样式。重点包括：

I.CSS的作用: 控制网页的布局和外观。II.理解CSS选择器: 通用选择器、元素选择器、类选择器、ID选择器等。

### 利用CSS设置基础样式:

学习如何使用CSS设置元素的基础样式，包括大小、颜色、字体等。

### 理解CSS盒模型:

盒模型描述了每个HTML元素在页面上所占空间的方式。包括内容、内边距、边框和外边距。

1.通用选择器 (*):

I.通用选择器匹配页面中的所有元素。II.例如，如果你希望设置页面上所有元素的边框为1像素，可以使用通用选择器：* { border: 1px solid black; }。

2.元素选择器:

I.元素选择器选择特定的HTML元素。II.例如，如果你想选择所有段落元素 &lt;p&gt; 并将它们的颜色设置为红色，可以使用元素选择器：p { color: red; }。

3.类选择器 (.class):

I.类选择器通过指定类名选择元素。类名前面加上点 (.)。II.例如，如果你有一个类为 "highlight" 的元素，你可以使用类选择器来设置它的样式：.highlight { background-color: yellow; }。

4.ID选择器 (#id):

I.ID选择器通过指定元素的ID来选择元素。ID名前面加上井号 (#)。II.例如，如果你有一个ID为 "header" 的元素，你可以使用ID选择器来设置它的样式：#header { font-size: 24px; }。

在CSS中，选择器的组合使用可以非常灵活地选择文档中的元素并应用样式。例如，你可以结合使用元素选择器和类选择器来选择特定类型的元素，或者使用通用选择器来设置全局样式。以下是一个简单的例子，演示如何使用这些选择器：/* 通用选择器，设置所有元素的边框 */

* {border: 1px solid black;}

/* 元素选择器，设置段落元素的颜色 */p { color: red;}

/* 类选择器，设置具有 "highlight" 类的元素的背景颜色 */.highlight { background-color: yellow;}

/* ID选择器，设置具有 "header" ID的元素的字体大小 */#header { font-size: 24px;}

### CSS的5种position定位:

Istatic: 默认定位。
II.relative: 相对于元素自身的位置定位。
III.absolute: 相对于最近的已定位的父元素进行定位。
IV.fixed: 相对于浏览器窗口进行定位。
V.sticky: 根据用户的滚动位置来定位。

### 了解CSS常用布局方式:

I.Flexbox: 弹性布局。
II.Grid: 网格布局。

### CSS伪类：

### 伪类用于向某些选择器添加特殊效果。例如，:hover表示鼠标悬停时的状态。 JavaScript 基本语法及数据类型:

JavaScript是一种用于网页交互的脚本语言。学习基本语法和数据类型，包括字符串、数字、布尔、Null、Undefined、对象和数组。

1.字符串（String）:

I.表示文本数据。
II.用单引号 (') 或双引号 (") 包裹。
III.例如：let myString = "Hello, World!";

2.数字（Number）:

I.表示数值。II.包括整数和浮点数。III.例如：let myNumber = 42;

3.布尔（Boolean）:

I.表示逻辑值，只有两个可能的值：true 或 false。II.常用于条件语句。III.例如：let myBoolean = true;

4.Null:

I.表示空值或没有值。II.例如：let myNull = null;

5.Undefined:

I.表示声明了变量但没有给它赋值。II.例如：let myUndefined;

6.对象（Object）:

I.表示复杂的数据结构，可以包含多个键值对。II.用花括号 {} 定义。III.例如： javascript let myObject = { key1: 'value1', key2: 'value2', // ... };

7.数组（Array）:

I.表示有序的集合。II.用方括号 [] 定义。III.例如： javascript let myArray = [1, 2, 3, 4, 5];

### HTML/CSS/JavaScript 三者之间的关系:

HTML用于结构，CSS用于样式，JavaScript用于交互。它们共同工作，构建出完整的网页。

### 静态页面 YQW-NNYU.github.io
[Upload<IDOCTYPE html>
<html>
<head>
<meta charset="utf-8">
</head>
<body>
<p>听话的便当</p >
</bodvs
</html>ing index.html…]()

