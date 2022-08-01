# Web-Development-Practice

Let's starts with HTML :

## HTML

### Anchor tag
- The `<a>` tag defines a hyperlink, which is used to link from one page to another. <br>
- The most important attribute of the `<a>` element is the `href` attribute, which indicates the link's destination. <br>
- E.g. `<a href="https://google.com">Go to Google</a>` <br>
- **Tip:** A linked page is normally displayed in the current browser window, unless you specify another target. <br>
 `<a href="https://google.com" target = "_blank">Go to Google</a>`
 
 ---
 
 ### Img tag
- The `<img>` tag is used to embed an image in an HTML page. <br>
- The `<img>` tag has two required attributes: <br>
   1. src - Specifies the path to the image 
   2. alt - Specifies an alternate text for the image, if the image for some reason cannot be displayed
- E.g. `<img src="google.jpg" alt="Google" width="100" height="132">`
-  **Tip:** To link an image to another document, simply nest the `<img>` tag inside an `<a>` tag (see example below). <br>
   `<a href="https://www.google.co.in/">` <br>
    `<img src="google.jpg" alt="Google" width="100" height="132">` <br>
    `</a>`
