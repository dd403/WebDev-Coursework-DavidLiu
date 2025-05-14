In this lesson, I learned that JavaScript can make websites more interactive. I used `alert()` to show messages and linked JavaScript to a button using `onclick`. I also learned how to change text with `innerHTML` and update images using `getElementById().src`. Now I understand how JavaScript works with HTML to create dynamic web pages.

``` html
<script>
    function changeText() {
        document.getElementById('suprise').innerHTML = 'You clicked the button!';换文字
            }
    function changeimage() {
        document.getElementById('image').src = "test.png";换图片
            }
</script>

<body>
    <p id="suprise">Hello, world!</p> 写id=“name” 点击就能换
    <button onclick=changeText()>Click me!</button>
    <button onclick=changeimage()>Click me!</button>
</body>
```