# GreenFeather
speed 100
bk 100
pen darkgreen
fd 10 
rt 40
rt 30,700
rt 179
lt 30, 720
fill color
pu()
lt 180
fd 40
forever ->
  if pressed 'up'
    fd 5
  if pressed 'left'
    lt 1
  if pressed 'right'
    rt 1
  if pressed 'down'
    bk 5
  if pressed 'c'
     pen darkgreen
     rt 60
     fd 50
     bk 50
     lt 120
     fd 50
     bk 50
     rt 60
     pu()
