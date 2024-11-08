# Block and Inline 

### Block vs inline
Controled by argument display : block / inline / inline-block
- block = start at a new line and take the whole line. ie <h1>, <p>, etc.
- inline = is inside the line with other content (if they are inline). ie <em>, <strong>, <a>
- inline-block = behave like inline elements but with block padding and margin (Not used in practice, you will use flexbox)

### Divs and spans
Contrary to <em>, <strong>, <p>, div and spans are generic boxes that give no particular meaning to their content.
Use cases : 
- Style some specific elements
- Style a group of related elements

#### Div
Div is a block element but default. 
It is used as a container element to group other elements. 
We can them apply some styling to these groups. 
#### Span
Span is an inline element by default. 
Used to group text contentnor other inline html elements for styling. 
It should only be used when no other html element is appropriate.

To do : 
Read the recommanded articles : 
- https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Normal_Flow
- https://www.w3schools.com/html/html_blocks.asp
- https://www.digitalocean.com/community/tutorials/css-display-inline-vs-inline-block

### Normal flow 
Noraml flow = layout without any CSS 
Starting with a solid, well-structured document that's readable in normal flow 
is the best way to begin any webpage

### List of block level elements
<address><article><aside><blockquote><canvas><dd><div><dl><dt><fieldset>
<figcaption><figure><footer><form><h1>-<h6><header><hr><li><main><nav><noscript>
<ol><p><pre><section><table><tfoot><ul><video>

### List of inline level elements
<a><abbr><acronym><b><bdo><big><br><button><cite><code><dfn><em><i><img><input>
<kbd><label><map><object><output><q><samp><script><select><small><span><strong>
<sub><sup><textarea><time><tt><var>


### Inline vs inline-block vs block : https://www.digitalocean.com/community/tutorials/css-display-inline-vs-inline-block
- Inline-block allows to set a width and height on the element
- with display: inline, top and bottom margins & paddings are not respected
- with display: block, a line break happens after the element, so a block element 
    doesn’t sit next to other elements

### Knowledge check
What is the difference between a block element and an inline element?
    - block = take the whole line and can accept width and height
    - inline = stay in the line and dont accept width and height

What is the difference between an inline element and an inline-block element?
    - inline-block = a block that is in the line and accept width and height 

Is an h1 block or inline?
    - block

Is button block or inline?
    - inline

Is div block or inline?
    - block

Is span block or inline?
    - inline