# GD50lab0

I made a few changes to the original source code. I added a self.dx attribute
to the paddle class to account for velocity horizontally and changed this
in the main.lua file in that section of code as well from player1.dy or player2.dy
to player1.dx etc. I also changed (reversed) a lot of the original velocities
for the collision parts of the main.lua file (ball.dx to ball.dy
or vice versa etc). I changed the coordinates and width and height when
initializing the paddles as well. I also tried to make the initial random
velocity of the ball to be a little slower at the start with the math.random function.
