# CSS Basics
## Overview of CSS

What Does CSS Stand for?
- Cascading - prioritizing certain values over others
- Style - focusing on layout, colors, fonts, etc.
- Sheet - another name for the file we use here

The internet used to be ugly. Enter CSS - a consolidated way to make it prettier.

#### Three primary objects:
- Elements: e.g. h1, div, body, a - default HTML (already reviewed)
- Classes: everything that starts with a “.”
- IDs: everything that starts with a “#”

#### Syntax of CSS:
```
/* this is either an element, class, or ID
   syntax is name: value;
   hexadecimal, RGB, etc.
*/

h1 {
	font-size: 24px;
	font-weight: bold;
	color: #000000;
}
```
Space doesn’t matter, but “onion” rules apply

#### What are IDs?
IDs are attributes that are used only on one element ONLY and noted with a “#” symbol in CSS
e.g.
```
HTML:
<img id=poster ></img>

CSS:
#poster {
	height: 100%;
  width: 100%;
}
```
IDs are used to direct functions to unique elements in the HTML so that there’s no confusion

*e.g clicking to a specific part of page*

#### What are Classes?

Classes are attributes something to multiple elements on a page noted with a “.” symbol in CSS.
```
HTML:
<img class="movie-scenes" ></img>

CSS:
.movie-scenes {
  height: 200px;
  width: 200px;
  padding: 10px;
}
```
Classes are used to change or affect multiple items in an HTML document at once

*e.g. everything with class=”movie-scenes” should have the same attributes*

In tandem, you can do a lot with HTML & CSS! Let's give it a shot!

[Back to main](README.md)
