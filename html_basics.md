# HTML Basics
#### HTML Tags:
Tags are used to mark up the beginning and end of an HTML element.

Almost everything in HTML needs to start and end with a tag
Everything is wrapped like layers of an onion, `<opened>` and `</closed>`
- e.g. `<div>”Hello!”</div>`
- *Note: not every tag is like this!*

###### Common Tags:
- `<html></html>` designates document as HTML
- `<div></div>` notes a block element in the page
- `<a></a>` anchor, activates a link in the page
- `<head></head>` contains meta information
- `<body></body>` contains browser information
- `<span></span>` notes an inline element
- `<aside></aside>` notes a side section in the page

###### Tags that are usually seen together (lists):
- `<ul></ul>` designates the boundaries of an unordered list element.
- `<ol></ol>` designates the boundaries of an ordered list element.
- `<li></li>` list item, will normally be inside of `<ul></ul>` or `<ol></ol>`

###### Tags that are usually seen together (tables):
- `<table></table>` designates the boundaries of a table element.
- `<tr></tr>` designates the boundaries of a table row element.
- `<td></td>` table date, this is where your "stuff" goes.

###### Tags used for text editing:
- `<b></b>` <b>Bolds the text between the tags</b>
- `<i></i>` <i>Italics the text between the tags</i>
- `<u></u>` <u>Underlines the text between the tags</u>
- `<h#></h#>` H1 - H4 are used to increase the size of the text
-

###### Irregular Tags:
- `<img />` creates an image in the page
- `<br />` creates a big break in the page
- `<hr />` creates a horizontal line
- `<link />` connects this to related documents
- `<input />` creates an input field

#### HTML Attributes:
HTML attributes inform the browser on what to do with a tagged piece of content.
Attributes generally appear as name-value pairs.
```
<p class="foo">This is the content of an element with class.</p>
```
###### The most common attributes are:
- id="" - id is used on only a single element"
- class="" - class can be used on multiple elements"
- href=”” - hyperlink reference to an internal or external link
- src=”” - source file to an image, video, etc.
- style=”” - add some color, font, margins, etc.
- ^ *There’s a MUCH better way to do this via CSS - more on that later!*

How do we check elements for whether they're talking to the browser? Use the **inspect element** feature!

But... how do we make HTML... better?

[CSS Basics](css_basics.md)
