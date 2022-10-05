# Games
- Snake_Game 
Prerequisites:

1.Turtle Module
- Turtle is a pre-installed library in Python that is similar to the virtual canvas that we can draw pictures and attractive shapes. It provides the onscreen pen that we can use for drawing.

2.Random Module
- Python Random module is an in-built module of Python which is used to generate random numbers. These are pseudo-random numbers means these are not truly random. This module can be used to perform random actions such as generating random numbers, print random a value for a list or string, etc.

3.Time Module
- The Python time module provides many ways of representing time in code, such as objects, numbers, and strings. It also provides functionality other than representing time, like waiting during code execution and measuring the efficiency of your code.

STEPS REQUIRED FOR THE IMPLEMENTATION

1. Importing Required modules
- We require turtle, random, and time module to import

2. Creating Game Screen

- title() will set the desired title of the screen
-setup() used to set the height and width of the screen
-tracer(0) will turn off the screen update
-bgcolor() will set the background color
-forward() will use to move the turtle in a forwarding direction for a specified amount
-right() used to turn the turtle clockwise and left() used to turn the turtle anticlockwise
-penup() will not draw while its move

3. Creating snake and food
-Turtle() will be used to create a new turtle object
-hideturtle() will use to hide the turtle
-goto() used to move the turtle at x and y coordinates

4. Keyboard Binding
- If the Up key will press then the snake will move in up direction.

-If the Down key is pressed then the snake will move in the down direction.

-If Left key will press then the snake will move in left direction.

-If the Right key will press then the snake will move in the right direction

5. Snake and Fruit Collision
If the snake touches the fruit then the fruit will go at any random position and score will increase and the size of the snake will also increase.

6. snake and Border Coliision
-If the snake touches the border of the game then the game will over.

7. snake touching himself
