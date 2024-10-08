# py-draw-a-staircase

"    # Draw start of staircase

    The line starting with a # symbol is known as a comment. It doesn’t tell the turtle to do anything, but is a way of documenting what the code does. In this case, it says that this is a program to produce a picture or diagram of the start of a staircase.
    from turtle import *

    Informally, you can think of the next line as saying we want to be able to work with turtles. More technically, the line is stating that we will be working with commands that apply to a turtle. When we use the commands later on, this line is how the system makes sense of what we write. The lines that follow are operations that have been made available to us in this way.
    forward(40)

    The next line tells the turtle to move forward by 40 units. (The operation actually works in terms of pixels, but we will refer to units to keep things more general.) The turtle always starts pointing horizontally to the right (by default in the middle of the window), so this line results in the turtle drawing a horizontal line from left to right of length 40 units.
    left(90)

    The next line tells the turtle to turn to the left by 90 degrees, so it will then point upwards.
    forward(40)

    The next line results in the drawing of a vertical line of 40 units in length.
    right(90)

    The next line turns the turtle to the right by 90 degrees, so it will then be pointing horizontally to the right again.
    forward(40)

    Finally, the last line draws a line from left to right – again a length of 40 units."
