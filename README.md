# Python

>_[Training](https://gitlab.com/simplon-co/training) / Python_

![Python](python.png)

## Exercises

* [Playing Turtle](https://gitlab.com/simplon-co/python-playing-turtle) _Playing with a tiny turtle so cute :turtle: !_
* [Challenges](https://gitlab.com/simplon-co/python-challenges) _It will maybe hurt a bit, but for your good! :cactus:_

## Ressources

* https://gitlab.com/simplon-co/learn-python
* https://gitlab.com/simplon-co/on-the-road-to-python
* https://developers.google.com/edu/python/
* https://openclassrooms.com/courses/apprenez-a-programmer-en-python
* http://www.learnpython.org/
* http://campus.codeschool.com/courses/try-python/

https://github.com/vinta/awesome-python

_To be continued.._

## Code snippets

### `Triangle.py`

```python
#! /usr/bin/python

def Line(x):
    return "#" * x

def Triangle(N):
    # Draw a triangle with print
    for i in range(N + 1):
        print Line(i)

Triangle(3)
Triangle(5)
```

### `Snowflake.py`

```python
import turtle
 
def draw(length, depth):
   if depth == 0:
     turtle.forward(length)
   else:
     draw(length/3, depth-1)
     turtle.right(60)
     draw(length/3, depth-1)
     turtle.left(120)
     draw(length/3, depth-1)
     turtle.right(60)
     draw(length/3, depth-1)
 
draw(500, 4)
```
