# Math formulas library
## General info
> This library will help you with some mathematical evaluations, related with basic
> geometric figures as: circle, rectangle, square, triangle. Library functionality includes
> calculating area and perimeter of mentioned figures.
## Documentation on functions
> - **circle.area(r)**  
    Returns area of a circle with given radius r
> - **circle.perimeter(r)**  
    Returns perimeter of a circle with given radius r
> - **rectangle.area(a, b)**  
    Returns area of a rectangle with given sides.  
    Parameters:  
        a (int): length of one side  
        b (int): length of second side  
> - **rectangle.perimeter(a, b)**  
    Returns perimeter of a rectangle with given sides.  
    Parameters:  
        a (int): length of one side  
        b (int): length of second side
> - **square.area(r)**  
    Returns area of a square with given radius r
> - **square.area(r)**  
    Returns perimeter of a square with given radius r
> - **triangle.area(a, h)**  
    Returns area of a triangle with side and height.  
    Parameters:  
        a (int): length of a side  
        h (int): length of height passed to the side a
> - **triangle.perimeter(a, b, c)**  
    Returns perimeter of a triangle with given sides.  
    Parameters:  
        a, b, c (int): length of three sides
## Examples
|  Module   |      Function      | Return |
|:---------:|:------------------:|:------:|
 |  circle   |      area(4)       |  16π   |
 | rectangle |  perimeter(1, 2)   |   6    |
 |  square   | perimeter(1, 2, 3) |   6    |
 | triangle  |     area(2, 3)     |   3    |
## Formulas used
### Area
> - Circle: S = πR²
> - Rectangle: S = ab
> - Square: S = a²
> - Triangle: S = ah/2

### Perimeter
> - Circle: P = 2πR
> - Rectangle: P = 2a + 2b
> - Square: P = 4a
> - Triangle: P = a + b + c
## Commits history
- **2f6aa60** - Added rectangle.py
- **fc7342b** - Added triangle.py and fixed rectangle.py
- **50265f5** - Added functions docs for circle.py and square.py
- **55ebb72** - Added functions docs to rectangle.py and triangle.py
- **2f6aa60** - Fixed triangle.py function docs
## Some cat content
![gif](https://media.tenor.com/5BYK-WS0__gAAAAM/cool-fun.gif)
