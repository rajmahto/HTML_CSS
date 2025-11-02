# 1. Background Properties:
we can set colours to the background of an element using background-colour 
-> background-color:colour_name;

# Total colours can be represented in 6 ways mostly

1. hexCode: unique hexa decimal code with #
2. rgb(): mix of red,green,blue where each colours goes from 0 to 255
3. rgba() : a stands for alpha(0,0-1,0) which represents lightness to dark.
4. hsl(hue,Saturation,lightness):hue is degree in color wheel,saturation is % towards dark, lightness % towards lightness.


# Background Images
1. background-image : it is used to set backgound images or gradients
2. background-image :url('path')
3. background-postion : it is used to adjust the position of background-image such as left right, center center etc..
4. background-repeat : by defoult, background will be repeated, to stop we can use no-repeat/repeat-x/repeat-y.
5. background-size : used to adjust image to screen
              contain -- adjust to screen portrait






# Gradient
1. linear-gradeint : it contains multiple colors from one direction to another direction.
     background-image:linear-gradeint(to right,color1,color2);
 instead of to right, we can also provide x deg, to left, to top and to bottom.
2. radial-gradient : it contains multiple colours from center of circle to circumference.
     background-image: radial-gradient(color1,color2);
3. conic-gradient : it contains multiple colors in a cone shape 
     background-image: conic-gradient(from x deg,color1,color2);

background-attachment: fixed  makes the website backgound fixed.

# Text Properties
We can make the text in diffrent design using below text properties
      i.   color: sets the color of text.
      ii.  text transform: used to transform the text (uppercase/lowercase/captialize).
      111. text decoration : size shape color position.
            size can be any pixels. shape can be underline/overline/line-through
      iv.  text-align: aligns the text -- left , right , center, justify
      v.   line-height:
   
# Font-properties:
We can assign different families(serif, sans-serif, monospace, cursive, fantashy) to the elements using below properties.
font-family: fontName, familyName;
font-size:xpx -- defines the size of font.
font-weight:100-900/bold/oblique

we can assign google fonts by going to 'google fonts' --> select a font --> click get font --> click "import" --> copy import url and paste in css --> mention font name elements.

There are other famous websites like dafont, 1001 fonts

homeWork: Make a intresting website and Host in netlify