## HTML 基础- 4个实例

​		当涉及到HTML的基础实例，通常会涉及一些最常见和基本的HTML标签，比如标题、段落、链接和图像等。以下是四个HTML基础实例：

1. **标题（Headings）：**
   使用`<h1>`到`<h6>`标签来定义标题，其中`<h1>`表示最高级别的标题，`<h6>`表示最低级别的标题。标题用于给文档结构化，并且标题的级别决定了其重要性。

```html
<!DOCTYPE html>
<html>
<head>
    <title>HTML基础示例 - 标题</title>
</head>
<body>
    <h1>这是一级标题</h1>
    <h2>这是二级标题</h2>
    <h3>这是三级标题</h3>
</body>
</html>
```

2. **段落（Paragraphs）：**
   使用`<p>`标签来定义段落。段落用于组织和呈现文本内容。

```html
<!DOCTYPE html>
<html>
<head>
    <title>HTML基础示例 - 段落</title>
</head>
<body>
    <p>这是第一个段落。</p>
    <p>这是第二个段落。</p>
</body>
</html>
```

3. **链接（Links）：**
   使用`<a>`标签来创建链接，通过`href`属性指定链接的目标URL。

```html
<!DOCTYPE html>
<html>
<head>
    <title>HTML基础示例 - 链接</title>
</head>
<body>
    <p>这是一个链接到百度的网站：<a href="https://www.baidu.com">百度</a></p>
</body>
</html>
```

4. **图像（Images）：**
   使用`<img>`标签来插入图像，通过`src`属性指定图像的URL，`alt`属性用于在图像无法显示时显示替代文本。

```html
<!DOCTYPE html>
<html>
<head>
    <title>HTML基础示例 - 图像</title>
</head>
<body>
    <img src="example.jpg" alt="示例图像">
</body>
</html>
```

这些是HTML的四个基础实例，它们是构建网页的最基本组成部分。通过组合和扩展这些基础实例，可以创建出更加复杂和丰富的网页。随着CSS和JavaScript等技术的结合使用，可以为网页增加更多的样式和交互效果。

## HTML 元素

​		HTML元素是构成HTML文档的基本组成单元，它们由一对标签组成，通常包括一个开始标签和一个结束标签。开始标签和结束标签之间的内容被称为元素的内容，可以是文本、图像、链接等。HTML元素用于描述网页的结构和内容，使得网页可以被浏览器正确解析和显示。

### HTML 元素语法

- HTML 元素以**开始标签**起始
- HTML 元素以**结束标签**终止
- **元素的内容**是开始标签与结束标签之间的内容
- 某些 HTML 元素具有**空内容（empty content）**
- 空元素**在开始标签中进行关闭**（以开始标签的结束而结束）
- 大多数 HTML 元素可拥有**属性**

## HTML 属性

​		HTML属性是用于提供额外信息或配置HTML元素的特性。属性可以添加到HTML标签中，通过属性，我们可以控制元素的行为和样式，以及与其他元素之间的交互。属性通常以名称-值对的形式出现，名称和值之间使用等号 "=" 连接。

- HTML 元素可以设置**属性**
- 属性可以在元素中添加**附加信息**
- 属性一般描述于**开始标签**
- 属性总是以名称/值对的形式出现，**比如：name="value"**。

> html属性参考网址 https://www.runoob.com/tags/html-reference.html

以下是一些常见的HTML属性示例：

1. **id属性：**
   `id`属性用于给HTML元素指定一个唯一的标识符，方便在JavaScript或CSS中对该元素进行操作或样式设置。

```html
<div id="header">这是页眉</div>
```

2. **class属性：**
   `class`属性用于为HTML元素定义一个或多个样式类，可以通过CSS选择器来选中这些元素并应用样式。

```html
<p class="highlight">这是一个带有highlight类的段落。</p>
```

3. **src属性：**
   `src`属性用于指定图像、音视频或iframe的来源URL。

```html
<img src="example.jpg" alt="示例图像">
```

4. **href属性：**
   `href`属性用于指定链接的目标URL。

```html
<a href="https://www.example.com">这是一个链接</a>
```

5. **alt属性：**
   `alt`属性用于在图像无法显示时显示替代文本，也可用于辅助技术（如屏幕阅读器）读取。

```html
<img src="example.jpg" alt="示例图像">
```

6. **width和height属性：**
   `width`和`height`属性用于指定图像、表格或其他元素的宽度和高度。

```html
<img src="example.jpg" alt="示例图像" width="300" height="200">
```

7. **disabled属性：**
   `disabled`属性用于禁用表单元素，阻止用户输入或选择。

```html
<input type="text" disabled>
```

8. **target属性：**
   `target`属性用于指定链接在何处打开，如"_blank"表示在新窗口打开链接。

```html
<a href="https://www.example.com" target="_blank">在新窗口打开链接</a>
```

以上只是HTML属性的一些常见示例，HTML提供了许多属性用于控制元素的行为和样式。通过合理地使用属性，可以实现丰富多样的网页效果和交互。