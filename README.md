# my_first_program_TURTLE
Learning functions while using turtle, all the while learning how to use GitHub
by Fub Lama
5.29.24
This progam draws a pair of simple houses with different colors, sizes and thickness of the walls and roof. To do so, it uses creates a fuction and then later calls it.
This version is an improvement on the last one whereby the output drawings are separated from ech other and are more distinct to each other. It also incorporates the conditional block "if __name__=='__main__': before the main(). 

import turtle
def triangle(len):
    # turtle.backward(50)
    # turtle.right(120)
    # turtle.backward(50)
    # turtle.right(120)
    # turtle.backward(50)
    # turtle.speed(2)
    for i in range(3):
        turtle.backward(len)
        turtle.right(120)
# triangle(100)

def square(len):
    for i in range(3):
        turtle.right(90)
        turtle.forward(len)
# square(100)

def house(len):
    triangle(len)
    square(len)

def main():
    turtle.speed(2)
    turtle.color("Orange")
    turtle.width(5)
    house(250)
    turtle.penup()
    turtle.right(90)
    turtle.forward(500)
    turtle.pendown()
    turtle.color("purple")
    turtle.width(10)
    house(175)
if __name__ == '__main__':
    main()



   
