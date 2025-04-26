# COFFEE JAM GAME MECHANICS
# What I did
# SlidableTrays.cs
• Added Colliders and Rigidbody to detect physical collision
• Took offset distance according to the object side so it won't go out from the checkerboard
• Logics for doing such things when it is colliding with an another object
• Implemented changeable things like ‘slide speed', ‘collision tightly' and ‘frame magnitude'
  1. Slide speed - it can change the speed of dragging the objects
  2. Collision tightly - the values can detect collision before or after the time
  3. Frame magnitude – decrease or increase the frame of an object, it will affect on speed
• Logics for doing ‘HorizontalDeltaBlock', ‘VerticalDeltaBlock' and ‘DiagonalDeltaBlock'

# CheckerBoardManager.cs
• Created grid cells according to coloum and row 6×8
• All the cells data in Dictionary
• Managed all the grid cells to check if it is occupied or not
• Included reset button to reset the Trays position and grid cells registered

# Gameplay loading....
![coffeeJameGif20sec](https://github.com/user-attachments/assets/3a7a6666-2f25-43b8-9c74-97eac03a32ee)
