- š Hi, Iām @Nak7l
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
Nak7l/Nak7l is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

import turtle
import colorsys
t = turtle. Turtle()
s = turtle. Screen()
s.bgcolor("black")
t.speed(0)
n=36
h=0
for i in range(460):
    c-colorsys.hsv_to_rgb(h,1,0,9)
    h+=1/n
    t.color (c)
    t.left(145)
    for j in range(5):
        t.forward(300)
        t.left(150)
