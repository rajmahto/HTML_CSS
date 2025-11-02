# Box Model:
It is considered as "the heart of css". it is fundamental topic of design.

# Box Model contains 4 properties:
1. `border`: defines the border of element 
        border : width type color;
    type can be solid/dashed/dotted/groove/double
    color is defoult text color
    we can also provide border-left,border-right,border-top,border-bottom

2. `border-radius` : defines the corner radius of element's border. 50% of border can make circle for square elements.
               border-radius : width or %;
        we can also provide border-top-left-radius,border-top-right-radius etc..,

3. `padding` : it is the space between border and content of element. To solve this, 
             we can use "box-sizing:border-box"
             padding : size; it applies padding to all sides
             padding : top-bottom left-right;
             padding : top left-right bottom;
             padding : top right bottom left;

4. `margin` : it is the gap outside the border.
        it is similar to padding.
        margin : width;
        *margin : auto can make element center horizontally in its width


## Different units in CSS:
In CSS we can define sizes in different units such as

1. `px(pixels)` : it is smallest units like a dot that fills height and width of screen resolution.
2. `vh/vw` : vh stands for viewport height and vw stands for viewport width. It is the % of total screen height/width.
3. `percentage(%)` : percentage is used to get x% of parents properties. if child contains height:50% , means it is 50% of parents height.
4. `em(enumerated value) `: it is used to make all child property depends o single parent property (font-size)

            1em stands 1 time of parents font size

            we can also use rem which is root enumurated values. its values depends on body font size

            1rem stands for 1 time of body's font size.
5. `float` : float is used to arrange the elements either left or right , but the next element might occupy the space surrounded by the floating element
            float : left/right/none
    To clear the float , you can use clear:left/right/both/none.