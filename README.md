# my_first_program_TURTLE
Learning functions while using turtle, all the while learning how to use GitHub
by Fub Lama
5.29.24
This progam draws a pair of simple houses with different colors, sizes and thickness of the walls and roof. To do so, it uses creates a fuction and then later calls it.

import turtle
# def sq(side):
#     for i in range(4):
#         turtle.speed(1)
#         turtle.color("orange")
#         turtle.forward(side)
#         turtle.right(90)
# sq(50)
# turtle.Screen().exitonclick()
def tr(len):
    for i in range (3):
        turtle.forward(len)
        turtle.left(120)
def sq(len):
    turtle.right(90)
    for i in range(3):
        turtle.forward(len)
        turtle.left(90)
    turtle.left(180)


def house(len):
    tr(len)
    sq(len)
    

def main():
    turtle.speed(2)
    turtle.color("purple")
    turtle.width(3)
    house(150)
    turtle.penup()
    turtle.color("green")
    turtle.width(3)
    turtle.backward(200)
    turtle.pendown()
    house(50)
main()
turtle.Screen().exitonclick()

