# Grid
grid is used to create a grid-based layout system with rows and columns, making it easier to design web pages without having to use floats and positining.

# parent properties
  These Properties are used to make the parent container as grid 
  `display`:grid ---> container becomes the grid
  `grid-template-columns`:column1-width column2-width....
  we can mention each columns width in px or % or fr (fractions)
  eg: grid-template-columns: 100px 200px; create 2 columns with specific widths
             grid-template-columns:1fr 2fr 3fr; creates 3 columns with each width 1/6,2/6 and 3/6.
             gris-template-columns:10% 20% 50%; creates 3 columns of respective percentages

        we can even mix widths and we can use repeat funtions to repeat widths 
        grid-template-columns:repeat(3,1fr); creates 3 columns each width 1/3.
  `grid-template-rows`: it is similar       

   

   justify-content: used to move elements along rows
   align-items: used to move elements along columns, we can even use place-items and  place-items and place-content instead 





# child properties:
These Properties are used to make the child adjust in grid.
grid-column-start: starting-column-line
grid-column-end: ending-column-line
grid-column:grid-column-start/grid-column-end
grid-row-start:starting-row-line
grid-row-end:ending-row-line
grid-row: grid-row-start/grid-roe-end

grid-area: grs/gcs/gce

order