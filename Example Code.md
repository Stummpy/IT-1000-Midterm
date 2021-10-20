## This sample code displayed on this page is just one of the many assignments I was tasked with completing this semester in IT 1000. 
> The assignment focused on creating our own turtle graphic in Python. If you were to run this program, you will find the end result is a stoplight!

` import turtle

painter = turtle.Turtle()
animation_speed = 3

turtle.speed(animation_speed)

painter.pencolor ("black")
painter.fillcolor("black")
painter.begin_fill()
for i in range(1):
    painter.penup()
    painter.goto(150,-200)
    painter.pendown()
    painter.backward(300)
    painter.left(90)
    painter.forward(600)
    painter.left(90)
    painter.backward(300)
    painter.left(90)
    painter.forward(600)
    painter.left(90)
painter.end_fill()

painter.pencolor ("red")
painter.fillcolor("red")
painter.begin_fill()
for i in range(1):
    painter.penup()
    painter.goto(-0,200)
    painter.pendown()
    painter.circle(100)
painter.end_fill()

painter.pencolor ("yellow")
painter.fillcolor("yellow")
painter.begin_fill()
for i in range(1):
    painter.penup()
    painter.goto(0,0)
    painter.pendown()
    painter.circle(100)
painter.end_fill()
    
painter.pencolor ("green")
painter.fillcolor("green")
painter.begin_fill()
for i in range(1):
    painter.penup()
    painter.goto(0,-200)
    painter.pendown()
    painter.circle(100)
painter.end_fill()

turtle.done() `

