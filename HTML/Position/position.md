# Position is CSS
It is used to specify where exactly the elements need to be positioned.

# There are 5 positions available in CSS
1. Static: static is the default position for every element.
it won't have any impact on top,left,right,bottom to provide the gaps /to move.

2. Relative: Relative is used to move the elements from its current position. It is used 


`postion`: Relative;
left:100px;
top:100px




3. absolute: absolute is used to move the elements based on body.
        `position`:absolute;
         right:0;
         bottom:0;
    moves the element bottom right corner. but it is scrollable.


4. fixed : fixed is used to move the element based on body but scrolling will not have effect on this.
     `position`:fixed;
      right:0;
      bottom:0;
   makes the element fixed always at bottom right corner.

5. sticky: sticky is similar to fixed but it intially follows relative. it stays as relative until position met its values and stays fixed untill the parent container is over
    `position`:stcky
     top: 0;
     makes the element fixed when it reaches top:0
