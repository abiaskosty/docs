---
$title: 修改呈现形式和布局
---

## 修改呈现形式

AMP 是一些网页；页面及其元素的任何样式设置操作都是使用常见 CSS 属性完成的。使用类或 `<head>` 中名为 `<style amp-custom>` 的内联样式表中的元素选择器来设置元素的样式：

[sourcecode:html]
<style amp-custom>
  /* any custom style goes here */
  body {
    background-color: white;
  }
  amp-img {
    background-color: gray;
    border: 1px solid black;
  }
</style>
[/sourcecode]

每个 AMP 页面都只有一个嵌入的样式表，并且还有一些不允许您使用的选择器。[了解所有样式设置相关信息]({{g.doc('/content/docs/design/responsive/style_pages.md', locale=doc.locale).url.path}})。

## 控制布局

在页面上进行元素布局时，AMP 遵循更严格的规则。在常规 HTML 页面上，您几乎完全使用 CSS 来设置元素布局。但是，出于性能原因，AMP 要求所有元素从一开始就必须设置显式的大小。

如需详细了解 AMP 如何渲染页面和设置页面布局，以及如何修改布局，请参阅[如何控制布局]({{g.doc('/content/docs/design/responsive/control_layout.md', locale=doc.locale).url.path}})。

<div class="prev-next-buttons">
  <a class="button prev-button" href="{{g.doc('/content/docs/getting_started/create/include_image.md', locale=doc.locale).url.path}}"><span class="arrow-prev">以前</span></a>
  <a class="button next-button" href="{{g.doc('/content/docs/getting_started/create/preview_and_validate.md', locale=doc.locale).url.path}}"><span class="arrow-next">下一个</span></a>
</div>
