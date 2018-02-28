# Template webpage

1. Download the files by clicking the green button and selecting download zip.

2. Open the `index.html` file in a web browser to see the webpage template you will be editing.

3. Open the `index.html` and `style.css` files in a text editor as you will be working on them.

4. Any time you make a change to either file, you will need to save and then refresh the screen in the browser to see it take effect.

## The HTML

The `index.html` is the content of your webpage.

[Basic HTML structure explained](https://www.w3schools.com/html/html_basic.asp)

[Basic HTML elements explained](https://www.w3schools.com/html/html_elements.asp)

The HTML elements we are using in this template are:

* `<body>`...`</body>` - A body tag wraps the page content (only ever one on a page) 
* `<div>`...`</div>` - div tags are used all the time to wrap anything
* `<h2>`...`</h2>` - h2 (heading 2) tag is for a heading
* `<p>`...`</p>` - p (paragraph) tag is for general text
* `<a href="/path/to/link">`...`</a>` - an 'a' (link) tag can wrap text or an image and the location of the link should be set in the `href` attribute.
* `<img src="/path/to/image.png" />` - img (image) tags are self closing and the location of the image needs to be set in the `src` attribute.

## The CSS

The `styles.css` file contains the styling for your webpage.

Each set of style rules corresponds to a HTML element, which can either be targetted by the tagname eg `<p>` would be `p`.

Or to be more specific, you can add a class attribute to the HTML element `<p class="copyright">` and in the styles you would use a dot to signify it is a class `.copyright`.


## The Task

### Add your own logo

* Put your cut out logo in the images folder.
* In the HTML file, find where the current logo is `<img class="logo" src="./images/logo.jpg" alt="Spiral" />` and replace the file name `logo.jpg` with your own, and also the `alt` attribute text with the name and slogan (this will be hidden but is needed for accessibility and SEO etc).
* In the CSS file, find where it says `.logo` - these are the style rules that define what the logo looks like on the page. You can change the width here to suit your logo.

### Add your own app image

* Same steps as above for the app image. Can you work it out?

### Add your own text content

* Find the text in the HTML which will be wrapped in `<p>` and `<h2>` tags, and replace with your own content. So this should be the heading, text and copyright text.

### Add your own font

* Find a font you like from [Google web fonts](https://fonts.google.com/)
* Once you click on the red plus icon, the font will appear in a black box at the bottom. Click the box to view the font you have selected (making sure it is just one font).
* It gives code snippets for both the HTML and the CSS. Find the similar code snippets in this template and replace with your own.

### Have a play with styling of the page...

[Lists of style rules](https://www.w3schools.com/css/default.asp) - links on the left

The main styles we will be changing are:

* `color` : #000000; (applies to text)
* `background-color` : #FFFFFF; (applies to the background colour)
* `font-size` : 14px;
* `width` : 100px; (can be px or %)
* `height` : 200px; (if the width is set, the height doesn't usually need to be)
* `border-bottom` : 1px dotted #CCCCCC (3 values should be given - thickness, type of border, colour)

### Extra task - add fake links for the Apple Store and Google Play buttons

These links are created by and image wrapped by a link tag `<a>` and the link needs to be set in the `href` attribute on the links.

* Can you add links to these in the HTML and see them working?