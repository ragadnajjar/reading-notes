#  Layout
## css treats each html element as if it is in its own box. this box will either ba a block-level box or an inline box.
* css has the following "positioning schemes that allo you to control the layout od a page,you specify the positioning scheme using the position property in css 
1. normal flow: in normal flow,each block-leve element sits on top of the next one 
2. relitive position: this one moves an element in relation to where it would have been in normal flow  
3. absolute position: when the position proparty is given a value of absolute,the box is taken out of normal flow and no longer effects the position of other elements on the page 
### overlapping elements 
* when you use relative,fixed or absolute positioning,boxes can overlap
* if you want o site which element on top you can use the "z-index" property
* the z-index is something referred to as the " stacking context"
#### clearing floats 
* clear : the clear proparty allows you to say that no element should touch the left or right sides of a box 
* left : the left-hand side of the box should not touch any other elements appearing in the same containing element
* right : the right-hand side of the box will not touch element appearing in the same containing element
* both neither the left nor right-hand side of the box will not touch element appearing in the same containing element
* none : elements can touch either side 
###### creating multi-column layouts with floats 
 many web pages use multiple columns in their design a `<div>` element to represnts easch column
 1. width 
 * this sets the width of the columns 
 2. float 
 * this positions the columns next to each othr 
 3. margin 
 * this creats a gab between the columns 
