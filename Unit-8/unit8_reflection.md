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
