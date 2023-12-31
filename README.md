# GitHub学习笔记
## 第一阶段
1.仓库（Repository） 是 GitHub 最基本的元素。 它们很容易被想象为项目的文件夹。 仓库包含所有项目文件（包括文档），并存储每个文件的修改历史记录。 仓库可以有多个协作者，仓库可以是公开的，也可以设置为私有的。

2.分支（Branch）是仓库的并行版本。默认情况下，您的仓库具有一个名为 main 的主分支。我们可以复制主分支创建其他分支，您安全地进行任何更改而不会影响”线上“主分支。 完成所需更改后，可以将分支合并回主分支以发布你的更改。

3.拉取请求（pull request）是 GitHub 上协作的核心。 拉取请求向他人展示你分支中发生的修改，并允许其他人接受、拒绝或者增加其他修改建议。 通过side by side 比较方式，显示两个分支中内容的差异，此拉取请求将保留您刚刚在分支上所做的修改，并提议将它们合并到main分支上。

4.合并（merge） 此操作将拉取请求中的修改合并到main分支中。

Markdown是一种轻量级标记语言，设计用于简化文档的编写，使其更容易阅读、编写和编辑。以下是一些基本的Markdown语法规范和操作：
标题
在文字前加 # 符号表示标题，# 的数量表示标题级别，最多支持六级标题。
# 一级标题
## 二级标题
### 三级标题

列表
无序列表
使用 *、+ 或 - 来表示无序列表。
* 项目一
* 项目二
  * 子项目
* 项目三

有序列表
使用数字和点表示有序列表。
1. 第一项
2. 第二项
   1. 子项
3. 第三项

引用
使用 &gt; 表示引用。
&gt; 这是引用的文本。

链接
使用 [显示文本](链接地址) 来创建链接。
[OpenAI](https://www.openai.com/)

图片
使用 ![替代文本](图片链接) 来插入图片。
![图片描述](https://example.com/image.jpg)

粗体和斜体
使用 **文本** 表示粗体，*文本* 表示斜体。
**粗体文本**
*斜体文本*

代码
使用 ` 将文本包裹起来表示行内代码，使用三个 ` 表示多行代码块。
`行内代码`

多行
代码块
### 分割线
使用三个或更多的 `-`、`*` 或 `_` 来创建水平分割线。

markdown
### 表格
使用 `|` 和 `-` 来创建表格。

markdown
| 头部1 | 头部2 |
| ------ | ------ |
| 单元格1 | 单元格2 |
| 单元格3 | 单元格4 |
```

## 第二阶段
1. 打开一个拉取请求
  
2.分配给自己
  
3.发布评论
  
4.添加修改建议
  
5.批准修改

6.合并拉取请求
![940822fc-2c9f-4e01-9d2b-2baaf9f4dcd1](file:///C:/Users/32449/Pictures/Typedown/940822fc-2c9f-4e01-9d2b-2baaf9f4dcd1.png)


#### 初始化Git仓库
要在项目中使用Git，首先需要将其初始化为一个Git仓库。
git init

#### 克隆仓库
如果你想在本地创建一个现有的远程仓库的副本，可以使用克隆命令。
git clone &lt;远程仓库URL&gt;

#### 添加文件到暂存区
要将文件添加到Git仓库，需要将其先添加到暂存区。
git add &lt;文件名&gt;

#### 提交更改
将暂存区的文件提交到本地仓库。
git commit -m "提交说明"

#### 查看状态
查看工作区、暂存区和本地仓库的状态。
git status

#### 查看提交历史
查看提交历史记录。
git log

#### 创建分支
创建新的分支来开发新功能或修复bug。
git branch &lt;分支名&gt;

#### 切换分支
切换到不同的分支。
git checkout &lt;分支名&gt;

#### 合并分支
将一个分支的更改合并到另一个分支。
git merge &lt;要合并的分支名&gt;

#### 拉取远程更改
从远程仓库获取最新更改。
git pull origin &lt;分支名&gt;

#### 推送更改到远程仓库
将本地仓库的更改推送到远程仓库。
git push origin &lt;分支名&gt;


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

### 伪类用于向某些选择器添加特殊效果。例如，:hover表示鼠标悬停时的状态。

 JavaScript 基本语法及数据类型:

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

I.表示空值或没有值。

II.例如：let myNull = null;

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

# Win回收站机制
1、第一个8 bytes是$I文件的头部 2、第二个8 bytes保存了被删除文件的尺寸 3、第三个8 bytes保存了删除文件的时间 4、后面的520 bytes内容是文件被删除之前的完整路径以及原文件名。

删除文件时，系统会在当前用户当前分区的回收站中创建一个文件$IXXXXXX.EXT，同时将删除的文件重命名为$RXXXXXX.EXT并移动至回收站

## 防火墙(Firewall)
定义：一种Network安全设备或软件，根据预定的安全规则监视和控制（接受、拒绝、丢弃）着传入与传出的网络流量。

IP

PORT

数据包（Data Packet）

流量

网络策略：控制进出网络的流量的处理方式。

数据包过滤

高级身份验证

应用程序网关

### 形态分类：

网络（硬件）、主机（软件）

### 功能分类：

包过滤、状态检查、代理

Next-Generation Firewall

杀毒软件
