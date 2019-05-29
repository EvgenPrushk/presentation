Task: https://github.com/rolling-scopes-school/tasks/blob/2018-Q3/tasks/presentation.md

Presentation: https://evgenprushk.github.io/presentation/

Transcript: https://github.com/EvgenPrushk/presentation/edit/master/README.md
## Canvas
# slide1 
Today I will tell you about the <canvas> element, what it is for, what it gives to a developer and to users, what do you need and what you don’t need to display it properly, what you should do to make it work. Also we will have some fun with different methods and in the end, please, be ready for something exciting. 
# slide2 
Canvas API (Application Programming Interface) is one of the most popular features in HTML5. Developers like to use it for creating rich web applications and users may use those applications without using browser plug-ins like Adobe's flash player. Most of the modern browsers support it. In a moment we will see what canvas is able to and how you may use it. 
# slide3 
Officially a canvas is a resolution-dependent bitmap canvas which can be used to draw graphs, game graphics, animation, or other visual images on the fly. Among other things, it can be used for real-time video processing. Simply saying, with the help of JavaScript and HTML5 canvas element you may draw 2D shapes and bitmap images. 
# slide4 
A webpage may contain multiple canvas elements. Each canvas may have an id using which you may target a specific canvas through JavaScript. Each canvas element has a 2D Context. This again has objects, properties, and methods. Using these you may draw your stuff. To draw on a canvas, you need to refer the context of the canvas. The context gives you access to the 2D properties and methods that we’ll dive deeper into later. 
# slide5 
beginPath()- creates a new path. Once created, future drawing commands are directed into the path and used to build the path up 
closePath() - Adds a straight line to the path, going to the start of the current sub-path 
# slide6 
We can draw lines using method Lineto(), where we need to specify 
- x-axis coordinate of the line's end point 
- y-axis coordinate of the line's end point 
# slide7 
The code will look like this 
# slide8 
So that’s what we’ll see in the browser window - a line. 
# slide9 
But if we want to draw a - rectangle, we will use method Rect() and parameters, such as x, y, width and height. 
- x-axis coordinate of the rectangle's starting point. 
- y-axis coordinate of the rectangle's starting point
- The rectangle's width. Positive values are to the right, and negative to the left 
- The rectangle's height. Positive values are down, and negative are up 
# slide10 
The code will look like this 
#slide11 
So that’s what we’ll see in the browser window - rectangle
# slide12 
Talking about drawing figures, creating a circle will be the most complex thing on today’s presentation. We will take method ctx . arc and already 6 parameters in it: x, y, radius, startangle and endangle, anticlockwise. The last one is optional parameter. 
- x-axis (horizontal) coordinate of the arc's center 
- y-axis (horizontal) coordinate of the arc's center 
- The angle at which the arc starts, measured clockwise from the positive x-axis and expressed in radians 
# slide13 
- The angle at which the arc starts, measured clockwise from the positive x-axis and expressed in radians 
- The angle at which the arc ends, measured clockwise from the positive x-axis and expressed in radians 
- An optional Boolean which, if true, causes the arc to be drawn counter-clockwise between the start and end angles. The default value is false (clockwise) 
# slide14 
The code will look like this 
# slide15 
We will keep these rules in our minds and give the next code to the browser 
# slide16 
Now you know the basics of Canvas and I want to offer you a quiz1 
#slide 17 
two red line 
# slide18 
Somebody wrote this code and deleted the browser. The project is almost done and the big boss is waiting. So you need to understand what you will see. The countdown starts now! 
# slide19 
smile:)
