Responsive design :
* Fluid design
* Media query
* Responsive image 

Fluid design means the size of elements and design depends on the viewport. Like `%`

Media queries will cause to break elements rows into rows with lower width 

Semantic web => use meaning ful tags .for example use `<header/>` instead of `<div/>`

Tags :
1- inline
2- block 

Inline stand in horizontal align and get the width of its text width. but blocks stand in vertical align it will fill all of its parent widths by default 

Block tags should not convert to inline. but inline can convert to block by `display: block`
Property and then can accept padding, width, and margin


Direction is better to config in `HTML` pages not in `css` 

Inline tags don't accept dimensions. also, margin and padding only work in horizontal 

The color property will read from the parent by default 

Margin auto will use the maximum possible value. Like a spring

user-agent stylesheet: styles that apply be browser by default 

To select the first element :
P:first-child{
...
} 

Margin collapsing in the vertical direction will ignore one of ex. Margins if two elements have the same vertical margin

to disappear dots before list items : 
<code>
    li:{
      list-style-type : none 
    } 
</code>

Display inline-block will use to show block elements inline. Because it can use padding and margin 

Text align center should pass to parent block element with inline elements 

Inline-block issue: will add a space because of enters between elements :\ 

box-sizing: border-box => means final width should be as width property not content size. It means where should apply width property