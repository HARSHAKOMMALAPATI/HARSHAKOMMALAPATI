import turtle
def draw_square(size):
    for _ in range(4):
        turtle.forward(size)
        turtle.right(90)
def draw_rectangle(width, height):
    for _ in range(2):
        turtle.forward(width)
        turtle.right(90)
        turtle.forward(height)
        turtle.right(90)
def draw_triangle(size):
    for _ in range(3):
        turtle.forward(size)
        turtle.right(120)
turtle.speed(2)
draw_square(100)
turtle.penup()
turtle.goto(-50, 100)
turtle.pendown()
draw_triangle(100)
turtle.penup()
turtle.goto(-20, -50)
turtle.pendown()
draw_rectangle(40, 80)
turtle.penup()
turtle.goto(-30, 30)
turtle.pendown()
draw_square(30)
turtle.hideturtle()
turtle.done()

