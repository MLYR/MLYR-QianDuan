## HTML 表单

HTML 表单（form）用于收集用户输入的数据。通过表单，用户可以向服务器发送数据，例如提交评论、进行注册、搜索内容等。表单由多个输入字段组成，比如文本框、单选框、复选框等。

### HTML 表单标签

HTML 表单使用一系列的标签来创建各种输入元素和组件，以便用户输入和提交数据。以下是一些常用的 HTML 表单标签：

1. `<form>`：定义一个表单，用于收集和提交用户输入的数据。
2. `<input>`：创建各种输入字段，如文本框、密码框、单选按钮、复选框等。
3. `<textarea>`：创建多行文本输入框。
4. `<select>`：创建下拉菜单。
5. `<option>`：定义 `<select>` 元素中的选项。
6. `<label>`：为输入元素添加标签，用于提供用户友好的描述。
7. `<button>`：创建按钮，可以用于提交表单或执行其他操作。
8. `<fieldset>`：将相关的表单元素组合在一组，并添加标题。
9. `<legend>`：为 `<fieldset>` 元素添加标题。
10. `<optgroup>`：将 `<option>` 元素分组。
11. `<datalist>`：定义一个预定义的选项列表，供用户从中选择。
12. `<output>`：显示计算的结果。

## HTML 脚本

在 HTML 中，您可以使用 `<script>` 标签来嵌入 JavaScript 代码，以在网页中实现交互、动态内容和其他功能。以下是一些关于在 HTML 中使用脚本的示例和说明：

1. **内联脚本：**
   您可以直接在 HTML 文件中使用 `<script>` 标签嵌入 JavaScript 代码。这些代码会在浏览器加载和解析页面时执行。

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <title>脚本示例</title>
</head>
<body>

<h1>内联脚本示例</h1>

<script>
    // JavaScript 代码
    alert("欢迎访问我的网页！");
</script>

</body>
</html>
```

2. **外部脚本：**
   为了使代码更清晰和可维护，您可以将 JavaScript 代码保存在外部文件中，然后通过 `<script>` 标签的 `src` 属性引用外部脚本文件。

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <title>脚本示例</title>
    <script src="script.js"></script>
</head>
<body>

<h1>外部脚本示例</h1>

</body>
</html>
```

在 `script.js` 文件中：

```javascript
// script.js
alert("欢迎访问我的网页！");
```

3. **异步加载脚本：**
   使用 `async` 属性可以异步加载脚本，这允许页面在加载脚本的同时继续渲染。例如：

```html
<script src="script.js" async></script>
```

4. **延迟加载脚本：**
   使用 `defer` 属性可以将脚本延迟到文档解析完毕后再执行，通常在 `</body>` 之前。这对于确保脚本在正确的上下文中执行很有用。例如：

```html
<script src="script.js" defer></script>
```

通过使用 `<script>` 标签，您可以将 JavaScript 代码嵌入到 HTML 中，实现各种交互和动态功能，从而增强用户体验和网页功能。

### HTML`<noscript>` 标签

`<noscript>` 标签是 HTML 中的一个特殊标签，用于在浏览器不支持 JavaScript 或用户禁用 JavaScript 时提供替代内容。在一些情况下，您可能希望在用户无法执行 JavaScript 代码时显示一些备用内容，或者向用户提供一些关于启用 JavaScript 的提示。

`<noscript>` 标签应该被放置在包含 JavaScript 代码的 `<script>` 标签的后面，如下所示：

```html
<script>
    // JavaScript 代码
</script>

<noscript>
    <!-- 当用户禁用 JavaScript 或不支持时显示的内容 -->
    <p>您的浏览器不支持或已禁用 JavaScript。</p>
</noscript>
```

在上面的示例中，当用户的浏览器不支持 JavaScript 或已禁用 JavaScript 时，`<noscript>` 内的内容将会显示在页面上。您可以在 `<noscript>` 内放置任何 HTML 内容，以便在需要时向用户提供合适的替代方案。

请注意，`<noscript>` 标签通常用于一些简单的提示信息，而不应该用于主要的页面内容。在现代的 Web 开发中，大部分页面都依赖于 JavaScript 来实现交互和动态功能，因此考虑到用户体验和可访问性，尽量鼓励用户启用 JavaScript。