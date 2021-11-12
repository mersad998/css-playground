# positions: 

In normal flow, the movement of one element will cause to push other elements to its transition side.
if you want to manipulate the flow, you can use positions

# positions :
* relative: it means to react to movements from the current position in normal flow without manipulating other elements
* in other words, `relative` will cause to do transitions based on its position 

* absolute :
  it means to react to movements based on its parents, actually it will search for one of its parents which has the relative position and react base of that, and if cannot find react based of `HTML` tag!. also, it set width to its minimum (its content).
- in absolute position elements, if an element has 0,0,0,0 offsets (top, right, bottom, left),
  and has height and width and has margin auto in horizontal and vertical sides, it will appear in the center of its relative parent!

* fixed :
it means to react to only viewport, not flow, not parents

- `z-index` will use to set the priority of elements that has custom positions
- `z-index` by default is `1`
- if you don't set `z-index`  for two element's, the element which has been written after another element in `HTML` is more important
  and will appear on top of another one.
- `stack in context`: it means if two elements came from different parents, and one of their parents has `z-index` upper that another one, always its child's will appear top of another parents child's. even second parents child's has more `z-index` than first parents child's!

to prevent the content of the page to go under the fixed header, it's better to set padding to body instead of set margin to content
