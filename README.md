Download Link: https://assignmentchef.com/product/solved-coen290-assignment-1
<br>
In this assignment, you are going to draw circle. there are 3 parts of this assignments.

<ol>

 <li>Use the circle rasterization algorithm introduced in lecture to draw a circle like this:</li>

</ol>

you define Radius  yourself. and color yourself

<ol start="2">

 <li>Fill the circle with color, like this:</li>

 <li>add anti-aliasing</li>

</ol>

you can come up with your own idea of creating anti-aliasing effect.

You will be using Python to implement this.  You don’t need to write rendering part.




You are provided with a rendering code in Python. This code will draw a single pixel on screen. All you need to do, is to add the algorithm to produce all the (x, y) coordinates for rendering function

<strong>This is a the pixel rendering code.
 </strong>




<strong>from PIL import Image</strong> <strong>img = Image.new(‘RGB’, (320, 240))</strong> <strong>pixels = img.load()</strong> <strong>pixels[100,100] = (255,0,0)</strong> <strong>img.show</strong>




Save this code into a .py file. Then add your algorithm code to this code.




(if you don’t know Python, google the basic grammar, you don’t need to use complicated Python features)




Write comment in your code to explain your algorithm.




Zip your source code.  and 3 result images. name your zip file
 with your name and assignment number