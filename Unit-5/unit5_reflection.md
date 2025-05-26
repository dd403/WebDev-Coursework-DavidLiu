In Unit 5, I learned about CSS and how it improves website design. I findjk that CSS helps style web pages by adding things like font size, font family, colors, and backgrounds. I practiced using CSS to size an image and applied this to my client’s web page, making it look better. I also learned the difference between inline, internal, and external CSS, and why a web designer might pick each one—inline for quick changes, internal for single pages and external for multiple pages.

* CSS
  * `style="width:400px; height:600px; border:10px solid blue;"`
  * `style="font-size: 20px; color: red;"`
  * `style="font-family: Arial, sans-serif;"`
  * `style="background-color: yellow;"`
* Internal CSS

```
        <style>
            body {
                background-image: url('VSCodeIcon.png');
                background-size: cover;
                background-position: center;
            }
            h1 {
                color: red;
            }
            p {
                color: blue;
                font-size: 14px;
                font-family: Arial, Helvetica, sans-serif;
            }
        </style>
```

* External CSS
  `<link rel="stylesheet" href="styles.css">` link to css file in html file.
  same as internal css just in css file.
