During this lesson, I learned how to add links to a web page, understood the difference between absolute and relative links, and practiced styling links using CSS. I successfully added and styled a link on my client’s web page to make it beautiful and easy to use. In addition, I learned how to add a favicon to the browser tab. I used internal CSS to improve the appearance of images and used the HTML `<span>` tag to apply unique styles to specific words. I thought these small but meaningful improvements helped polish the client’s web page and made the final product more attractive.

## Format about add a link

`<a href="https://www.microsoft.com/" target="_blank">Visit one of my favorite websites!</a>`

If there is no target="_blank", clicking on the link will open a new website on the current page (replacing the original page).

If target="_blank" is added, clicking on the link will open a new tab with the new website, and the original page will still be there.

## Change the style about the link

```html
 <style>
        a:link {//link's color链接颜色
            color: red;
            background-color: transparent;
            text-decoration: underline;
        }
        a:hover {//link's color when you hover over it当光标移在上面时链接的颜色
            color: green;
            background-color: blue;
            text-decoration: none;
        }
        a:active {//link's color when you click on it当点击的时候链接的颜色
            color: yellow;
            background-color: purple;
            text-decoration: none;
        }
        a:visited {//当访问过后链接的颜色
            color: pink;
            background-color: transparent;
            text-decoration: underline;
        }
    </style>
 
```

## Change the style about the picture

```html
 <style>
        img {
            border-width: 20px;//边框粗细

            border-style: solid dotted dashed double;//边框类型

            border-color: purple red orange blue;//边框颜色，从上开始顺时针

            border-radius: 25px 40px 60px 1000px;//边框长短

            width: 200px;//图片宽度

            height: 200px;//图片高度
        }
    </style>
```

## Span

```html
 <span style="color: red;">This text is red.</span>
```

Just a inline element, can be used to style text
