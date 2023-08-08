## HTML 样式- CSS

​		CSS（层叠样式表）是一种用于控制网页样式和布局的标记语言，它与HTML一起用于设计和美化网页。CSS允许您控制文本的字体、颜色、间距，以及元素的大小、边框、背景等。以下是一些常见的CSS样式属性和用法：

1. **选择器（Selectors）：**
   选择器用于选择要应用样式的HTML元素。例如，`h1`表示选择所有`<h1>`标题元素，`.class`表示选择带有特定类的元素。

```css
h1 {
    color: blue;
}

.button {
    background-color: #ffcc00;
}
```

2. **属性（Properties）：**
   属性定义了要应用于元素的样式。例如，`color`属性定义文本颜色，`background-color`属性定义背景颜色。

```css
p {
    font-size: 16px;
    line-height: 1.5;
}

.header {
    padding: 20px;
    background-color: gray;
}
```

3. **值（Values）：**
   值是属性的具体设置。例如，`font-size: 16px`中的`16px`就是值，表示字体大小为16像素。

```css
h2 {
    font-size: 24px;
    font-weight: bold;
}
```

4. **盒模型（Box Model）：**
   盒模型定义了HTML元素的尺寸和外观。它包括内容区域、内边距、边框和外边距。

```css
.box {
    width: 200px;
    height: 150px;
    padding: 10px;
    border: 1px solid #ccc;
    margin: 20px;
}
```

5. **文本样式：**
   您可以设置文本的样式，如字体、颜色、对齐和行高。

```css
p {
    font-family: Arial, sans-serif;
    color: #333;
    text-align: center;
    line-height: 1.6;
}
```

6. **背景和边框：**
   您可以设置元素的背景颜色、图像，以及边框的样式、颜色、圆角等。

```css
.section {
    background-color: #f5f5f5;
    background-image: url("bg.jpg");
    border: 2px solid #ddd;
    border-radius: 5px;
}
```

7. **浮动和定位：**
   使用`float`属性进行元素的浮动，使用`position`属性进行元素的定位。

```css
.image {
    float: left;
    margin-right: 10px;
}

.sidebar {
    position: absolute;
    top: 0;
    right: 0;
}
```

8. **媒体查询（Media Queries）：**
   媒体查询用于根据不同的屏幕尺寸或设备类型应用不同的样式，实现响应式设计。

```css
@media (max-width: 768px) {
    .menu {
        display: none;
    }
}
```

这些示例只是CSS中的一小部分。CSS非常强大，允许您以各种方式控制网页的外观和布局。通过合理使用CSS，您可以创建出各种各样的视觉效果，提升用户体验。

## HTML 颜色

在 HTML 中，您可以使用颜色来装饰和样式化网页的内容。颜色可以应用于文本、背景、边框等元素。HTML 支持多种颜色表示方式，包括颜色名称、十六进制值和 RGB 值。

以下是一些在 HTML 中使用颜色的示例：

1. **颜色名称：**
   HTML 提供了一些预定义的颜色名称，例如 `"red"`（红色）、`"blue"`（蓝色）、`"green"`（绿色）等。

```html
<p style="color: red;">这是红色文本。</p>
<p style="color: blue;">这是蓝色文本。</p>
<p style="color: green;">这是绿色文本。</p>
```

2. **十六进制颜色值：**
   使用六位十六进制值来表示颜色，格式为 `#RRGGBB`，其中 RR、GG 和 BB 分别表示红、绿和蓝的分量。

```html
<p style="color: #FF0000;">这是红色文本。</p>
<p style="color: #0000FF;">这是蓝色文本。</p>
<p style="color: #00FF00;">这是绿色文本。</p>
```

3. **RGB 颜色值：**
   使用 `rgb(R, G, B)` 格式来表示颜色，其中 R、G 和 B 分别表示红、绿和蓝的分量，取值范围为 0 到 255。

```html
<p style="color: rgb(255, 0, 0);">这是红色文本。</p>
<p style="color: rgb(0, 0, 255);">这是蓝色文本。</p>
<p style="color: rgb(0, 255, 0);">这是绿色文本。</p>
```

除了文本颜色，您还可以使用类似的方式为背景颜色、边框颜色等元素设置颜色。通过在 HTML 元素的 `style` 属性中指定颜色，您可以实现页面的样式化和装饰效果。请注意，使用适当的颜色可以增强用户体验，并提高页面的可读性。

## HTML 颜色名

https://www.runoob.com/html/html-colornames.html

## HTML 颜色值

https://www.runoob.com/html/html-colorvalues.html