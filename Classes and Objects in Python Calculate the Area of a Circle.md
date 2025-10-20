# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```c
import math
class Circle:
    def __init__(self, radius):
        self.radius = radius

    def area(self):
        return math.pi * self.radius ** 2

radius = float(input("Enter the radius of the circle: "))
circle_obj = Circle(radius)
print("The area of the circle with radius", radius, "is:", circle_obj.area())

```
## Output
<img width="627" height="43" alt="image" src="https://github.com/user-attachments/assets/a7cfc046-9703-4f86-aa8c-e5b4d4b05d40" />


## Result
Thus, the program has been executed successfully.

