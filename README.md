# Responsive Business Webpage Using Flexbox

This is Codecademy project, part of the full-stack developer learning path, which includes:

* html and css files to implement a responsive webpage per specs
* images created using Canva to satisfy the specs

## Note

This is my first responsive webpage.

## Highlight

Applying the DRY (don't repeat yourself) principle, I have spun off any repeated property value pairs in the CSS into their own class. I have written about this here:

https://medium.com/@abhilashc24/the-best-way-to-write-css-and-html-0917cb4dabe6

The advantage of this is that when we look at the html, elements have descriptive classes which give a good idea of what the styling would like without looking at the css file. So, it's a way to visualize both structure and style of the page by 
looking at only the html file. 

It's also great for testing cases where you think you might have styled elements that have already inherited the same style. Simply delete the descriptive class for the element in the html file to verify.

Unfortunately, this approach doesn't scale when many media queries are used to make the webpage responsive. Since only two media queries are used, that too using html tags as selectors instead of classes, it works here.
