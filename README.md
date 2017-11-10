Open​ ​Source​ ​Development​ ​Lab 
Python 

SNAKE GAME
Dhwani Prajapati(14BCE025)
Drashti Dobariya(14BCE027)
 

Abstract: 
The game is an arcade game and it has very simple logic, which is why it is an ideal example to demonstrate how to build games with Pygame.
The player is represented as snake, which grows if it eats an apple. The goal of the game is to eat as many apples as possible without colliding into yourself.  This is very easy in the early phase of the game but is increasingly more difficult as the length of the snake grows.
Project Flow Diagram: 
Basic structure and event handling 
We define a class Player which holds the player’s position on the screen and the speed by which it moves. In addition we define the actions a Player instance can do (movements):A player object can be created and variables can be modified using the movement methods.After defining all the classes, we can define the movements of the player using arrow keys.

Building the player(snake)
The player controls a snake which has an initial length. This snake is always moving and changes the direction it moves when pressing an arrow key. So, after updating the player class we added delay to the game loop.
After doing this we update the length of the player snake by moving the head position of the snake each time an arrow key is pressed.
	
Developing game logic
	This game has some basic rules such as:
If the snake eats an apple, the apple moves to a new position.
If the snake eats an apple, the snake’s length grows.
If a snake collapses with itself, game over.	
Additionally, we create a new class named “Apple” through which we create an apple as and when the snake eats an apple.
In order to know if the snake’s position matches the apple’s position, we have to do collision detection verifying that the coordinates of the snake is intersecting with the coordinates of the apple. Hence, we created a method named “isCollision” which identifies whether there is collision between the two. The same collision method is used to determine whether the snake collides with itself.

Functions/Features of Python used:
In  this  game,  we  have  used  some of the features of python which are  listed​ ​below:  
Loops  
Conditional​ ​statements 
Single-dimensional​ ​array 
Multi-dimensional​ ​array  
Defining​ ​functions  
Calling​ ​functions​ ​by​ ​recursion  
Passing​ ​various​ ​parameters​ ​to​ ​functions 
Python​ ​in-built​ ​functions  
Event​ ​handling​ ​functions  
Displaying​ ​fonts 
Pygame Module

Limitations: 
The Game has the following limitations:
The GUI can be improved.
We could add more number of layers and as the level increases, we can increase the speed of the movement of the snake.
We can also include a time bound game.
We could also include pause and the restart button.

Conclusion:  
In this  python-based  game,  we  cleared  the  basic  concept  of  python.  We  learnt  various  syntaxes  of  python,  defining  functions,  displaying  colors,  handling  events  generated  on  user interaction. Also,  we came to know about bin-packing algorithm which basically provides  the​ ​way​ ​to​ ​minimize​ ​unutilised​ ​space.   

