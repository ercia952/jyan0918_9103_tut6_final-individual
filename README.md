# jyan0918_9103_tut6_final-individual
We choose "Apple Tree" as our reference to create the artwork. 

I use p5.js perlin noise to create the artwork.

TITLE - "Candy Apple Tree"

1. Overview
The aim of this animation is to showcase smooth, organic movement using Perlin noise, enhancing the natural feel of the animation. A variety of colors, opacity levels, and layered compositions add depth and dynamic changes to the display.
This project demonstrates an iterative design of an apple tree composed of circles and lines, which I've developed into a dynamic, animated visualization. The elements smoothly animate across the canvas, creating a unique, lively visual experience. Using Perlin noise to drive the movement, the animation has a natural and continuous feel, and the entire display scales proportionally with the window size for responsive adaptation.

2. Code Structure

   2.1 Dynamic Elements
Circles: Multiple instances of circles, each with custom-defined position, size, and color properties. Their movement is controlled by Perlin noise for smooth, continuous animation.
Lines: A range of lines with customizable endpoints, colors, and thicknesses, all animated in sync with the circles using Perlin noise to establish a cohesive, structured layout.

   2.2 Scaling and Responsive Design
The canvas scales proportionally with the window size to ensure a consistent look across different screen dimensions. The scaleFactor variable dynamically adjusts element sizes and positions, allowing responsive scaling.

   2.3 Frame Design
Both an outer and an inner frame are drawn on the canvas, each scaling proportionally with the canvas size, providing additional structure and focus to the dynamic elements.

   2.4 Variables
"elements": An array storing all Circle and Line instances, used for rendering in the animation loop.
"scaleFactor": Dynamically adjusts based on window dimensions to maintain responsive scaling.
"Circle": A class representing a circle with attributes for position, size, and color. Each instance moves using Perlin noise and has a slight rotation effect.
"Line": A class representing a line with defined endpoints, color, and thickness properties, animated with Perlin noise and slight rotation to match the circles’ motion.

    2.5 Functions
setup(): Initializes the canvas and populates the elements array with Circle and Line instances.
draw(): Continuously renders the background and updates each element on the canvas using an update() function.
drawFrame(): Draws the inner and outer frames around the canvas to enhance visual composition.
windowResized(): Updates the canvas and recalculates scaleFactor on window resize for responsive scaling.


3. Iteration Process
    3.1 Iteration 1
   
   <img width="448" alt="Iteration1" src="https://github.com/user-attachments/assets/e96541af-7266-4b03-b465-ffc961033b1b">  
   
In this version of the candy tree, the visual effect dosen't do well, lacking the visual shock. I’m planning to adjust this code to make it more engaging. So I added more elements and adjust the parameter of noise.
    3.2 Iteration 2
    
   <img width="449" alt="Iteration2" src="https://github.com/user-attachments/assets/7f935c2f-8eb2-4c8d-b049-1d55fd21725c">
   
In this version, the elements is lack in the colour contrast with the background. So I need change the background colour from dark blue to light grey.
    3.3 Iteration 3
    
   <img width="448" alt="Iteration3" src="https://github.com/user-attachments/assets/8d9f97df-6fc1-4db0-b9e8-5634c4f60276">
   
So come to the last Version, everything is doing well.

