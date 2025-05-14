In these lessons, I learned how to use CSS with `<div>` and class attributes to organize and style web pages. I explored the box model and different `position` types like `static`, `relative`, and `absolute`, and saw how they affect layout. I also learned about `display` values like `block`, `inline`, `flex`, and `grid` to control element layout. Finally, I understood the difference between responsive and adaptive design, and why it’s important to make websites work well on all screen sizes. These skills help make my websites more organized, flexible, and user-friendly.

# Div

```html
<div>
  <!-- 网页内容 -->
</div>
```

# Class (can be use on any elemnrt not only div)

```html
<div class="bright">...</div>
<p class="dark">...</p>
```

# define class in style

```html
<style>
  .bright {
    color: red;
    background-color: yellow;
  }

  .dark {
    color: white;
    background-color: black;
  }
</style>
```

`inline-block` 非常适合用在 **需要一行显示多个元素，并控制每个元素样式** 的场景。

`display: block` 表示这个元素会 **单独占一整行** ，左右自动拉满，不管内容多少。

`<h1>`、`<p>`、`<div>` 默认都是 block。

`display: flex` 是一种强大的布局方式，用来 **在一行或一列中对多个元素进行排列** 。

`display: grid;` 把这个 div 变成一个网格容器。

`grid-template-columns: repeat(3, 1fr);` 网格分成 3 列，每列占 1 等分

`grid-gap: 10px;` 网格之间的间距10px

`max-width: 100%; height: auto;` 图片自适应

`.container {width: 100%;} .column {float: left; width: 33.33%;}` 三列布局

`@media (max-width: ?px)` 媒体查询，当屏幕宽度小于?px时，应用下面的样式
