# Python-import-turtle-Advance-Art-104
Create python use import turtle graphics code
import turtle as t 
import time as T 
import colorsys
s=t.Screen()
t.title("Satyam Shorrf")
t.bgcolor('black')
t.tracer(2)
m = 0.5
n=10
t.pensize(1.4)
T.sleep(2)


for i in range(160):
    c = colorsys.hsv_to_rgb(m,1,1)
    m +=0.005
    t.pencolor(c)
    t.right(20)
    t.forward(i)
    t.left(70)
    t.forward(i)
    t.circle(m, 1)
    t.hideturtle()

t.done()
    
