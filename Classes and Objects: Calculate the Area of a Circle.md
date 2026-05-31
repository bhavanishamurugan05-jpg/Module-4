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
```
class cse:
    def mech(self):
        r = float(input("Enter radius: "))
        area = 3.14 * r * r
        print("Area of Circle =", area)

obj = cse()
obj.mech()
```

## Output
<img width="495" height="190" alt="image" src="https://github.com/user-attachments/assets/4fd8079f-1668-405c-aec2-e5871b4d0444" />

## Result
Thus, the Python program successfully calculates the area of a circle using a class and method based on the user-provided radius.
