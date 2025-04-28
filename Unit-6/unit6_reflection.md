## Format about add a link

`<a href="https://www.microsoft.com/" target="_blank">Visit one of my favorite websites!</a>`

If there is no target="_blank", clicking on the link will open a new website on the current page (replacing the original page).

If target="_blank" is added, clicking on the link will open a new tab with the new website, and the original page will still be there.

## Change the style about the link

```html
 <style>
        a:link {//link's color
            color: red;
            background-color: transparent;
            text-decoration: underline;
        }
        a:hover {//link's color when you hover over it
            color: green;
            background-color: blue;
            text-decoration: none;
        }
        a:active {//link's color when you click on it
            color: yellow;
            background-color: purple;
            text-decoration: none;
        }
        a:visited {//
            color: pink;
            background-color: transparent;
            text-decoration: underline;
        }
    </style>
 
```
