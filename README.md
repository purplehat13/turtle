# turtle

import turtle
import math

lilac = turtle.Turtle()

lilac.color("#FBC740", "#C8A2C8")
lilac.speed(10)

lilac.begin_fill()
for i in range(37):
    lilac.forward(200)
    lilac.left(170)
lilac.end_fill()

turtle.done()

------------------------------------------

import turtle

lilac = turtle.Turtle()

lilac.color("#FBC740", "#eac4ff")

lilac.begin_fill()
for i in range(11):    
    lilac.forward(100)
    lilac.right(60)
    lilac.forward(100)
    lilac.right(120)
    lilac.forward(100)
    lilac.right(60)
    lilac.forward(100)
    lilac.right(12)
lilac.end_fill()
    
    


turtle.done()

