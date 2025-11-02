# Display
       : display is used to arrange the elements. block elements always appears in new line. inline elements 
         always continues in the same line but we can change this using display property.
    i.   display :block --> make the element block
    ii.  display :inline --> make the element inline
    iii. display :inline-block --> make the element inline-block(it is similar to inline but also contains height & width).
    iv.  display: none  --> disappers the element (visiblity : hidden also disappers the element but hold the space).
         

        div.child.child$*8

# Flex
Flex Container: flex is used to adjest child items or arrange child items in single direction(row/column).
Apply the flex properties to parents 
        parent properties:
          `display` : flex --> it automatically arrange child items into row direction 
           `flex-direction` : column/row/row-reverse/column-reverse;
           the direction in which items are adjusted is called main axis and opposite one is called cross axis
           `justify-content`: left/right/start/end/center/space-betweeen/ space-evenly/ space-around.
           it adjust the child item around main access.
           `align-items`:left/start/right/end/center
           `gap`:it is used to provide gap between the items 
           `flex-wrap`:nowrap/wrap/wrap-reverse-> it is used to arrange element in multiple row/column
           `align-content`: left/right/start/end/center/space-between/space-evenly/space-around
           it is used to adjust gap between row/columns   

# Child properties
here are the child properties :->
     `order` : used to arrange child item in an encreasing order. by default order is 0.
     `flex-grow` :it is used to make element grow when space is available.
     `flex-shrink` :it is used to  make element shrink when space is not available.
     `flex-basis`: it is used to keep an element in specific size.
     `align-self` : left/right/start/end/center--> it is used to move single element in cross axis.


