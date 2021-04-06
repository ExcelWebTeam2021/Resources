# SVG Animations

### Videos

1. Understanding SVG  https://www.youtube.com/watch?v=emFMHH2Bfvo
2. How To Animate SVG With CSS  https://www.youtube.com/watch?v=KLU4PUd7N14
3. Make Awesome SVG Animations with CSS https://www.youtube.com/watch?v=emFMHH2Bfvo
4. Animate SVG image in CSS  https://www.youtube.com/watch?v=3ZEwMHWdhYA&list=PLFSEJJUB9G0MuThLyms5ZjZ3Eyk0-RwjI&index=4


### Codepen

1. https://codepen.io/johan_mathew99/pen/oNxEZKQ
2. https://codepen.io/johan_mathew99/pen/abNqpMm
3. https://codepen.io/johan_mathew99/pen/MWyQJGM
4. https://codepen.io/johan_mathew99/pen/PoNQWBe


### Sites

1. https://www.w3schools.com/graphics/svg_intro.asp
2. https://developer.mozilla.org/en-US/docs/Web/SVG/Tutorial
3. https://www.smashingmagazine.com/2019/05/svg-design-tools-practical-guide/


### Steps (from what I understood)

S1 : Pick an image from undraw (or any other site)  

S2 : Open the in figma and ungroup the vectors

S3 : Group related vectors together (Ctrl + G) and rename them accordingly (This will create a <g id='blah'>...</g> in the svg)

S4 : Export the final image as SVG (with id attribute selected from the ... menu.)

S5 : Using css or anime.js animate individual elements



### Notes

SVG has some predefined shape elements that can be used by developers:

    Rectangle <rect>
    Circle <circle>
    Ellipse <ellipse>
    Line <line>
    Polyline <polyline>
    Polygon <polygon>
    Path <path>
    
<br />    

#### path element
  
The <path> element is used to define a path. The first command is the "Move To" or M, which was described above. It takes two parameters, a coordinate (x) and coordinate (y) to move to. ``` M x y ```

There are three commands that draw lines. The most generic is the "Line To" command, called with L. L takes two parameters—x and y coordinates—and draws a line from the current position to a new position. ``` L x y ```

 "Close Path" command, mentioned with Z draws a straight line from the current position back to the first point of the path. It is often placed at the end of a path node, although not always. 

 
 
The following commands are available for path data:

    M = moveto
    L = lineto
    H = horizontal lineto
    V = vertical lineto
    C = curveto
    S = smooth curveto
    Q = quadratic Bézier curve
    T = smooth quadratic Bézier curveto
    A = elliptical Arc
    Z = closepath
