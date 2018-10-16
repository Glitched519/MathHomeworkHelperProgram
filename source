import math
import datetime
import time

import self as self

numChars = 80
print("#" * numChars)
print("Welcome to the Math Problem Solver for Python 3.x!")
print(
    "This program will solve the math problem using its built-in functions included and will show a step-by-step process on how it was solved."
)
print("Created by: Partha Sarker")
print("#" * numChars)
"""
Note: exception handling (try-except) is included so that you don't see those bloody red errors that
popup in the shell when you don't input a number or get a vertical slope.
"""


class ArithmeticFormulas:
    def getallfactors(self):
        try:
            num = int(input("Enter an integer: "))
            factorCount = 0
            print("Here are the factors of " + str(num))
            for x in range(1, num + 1):
                if num % x == 0:
                    print(x)
                    factorCount += 1
            if factorCount == 2:
                print("Your number is prime!")
            else:
                print("Your number is composite!")
        except ValueError:
            print("x" * numChars)
            print("Please enter a positive integer.")

    def pi(self):
        print(
            "Pi is a number that you get from dividing the circumference by the diameter. This is pi to several digits:"
        )
        print(radians(180))

    def fibonacci(self):
        try:
            i = int(input("Enter how many terms you would like to see: "))
            number = 1
            last = 0

            print(number)

            for counter in range(0, i - 1):
                before_last = last
                last = number
                number = before_last + last
                print(number)
        except ValueError:
            print("x" * numChars)
            print("Please enter a number.")


class TrigonometricFormulas:
    def PythagoreanTheorem(self):
        try:
            print("The formula for pythagorean theorem is aÂ² + bÂ² = cÂ².")
            print(
                "If you are trying to calculate for 'a' or 'b', then you must subtract cÂ² from the other leg a or b."
            )
            a = float(input("Enter value for a: "))
            b = float(input("Enter value for b: "))
            print(
                "Adding the squares of both legs of the triangle will give you the square of the hypotenuse(c)."
            )
            print("The square of the hypotenuse is " + str(a**2 + b**2) +
                  " units.")
            print("The length of the hypotenuse is " + str(sqrt(a**2 + b**2)) +
                  " units.")
        except ValueError:
            print("x" * numChars)
            print("Please enter a number.")

    def sin(self):
        try:
            n = float(input("Enter value: "))
            print(
                "'sin' or sine is the ratio in a triangle for opposite/hypotenuse."
            )
            print("The degree is " + str(sin(n)))
        except ValueError:
            print("x" * numChars)
            print("Please enter a number.")

    def cos(self):
        try:
            n = float(input("Enter value: "))
            print(
                "'cos' or cosine is the ratio in a triangle for adjacent/hypotenuse."
            )
            print("The degree is " + str(cos(n)))
        except ValueError:
            print("x" * numChars)
            print("Please enter a number.")

    def tan(self):
        try:
            n = float(input("Enter value: "))
            print(
                "'tan' or tangent is the ratio in a triangle for opposite/adjacent."
            )
            print("The degree is " + str(tan(n)))
        except ValueError:
            print("x" * numChars)
            print("Please enter a number.")

    def typeofpolygon(self):
        try:
            sides = int(input("Enter number of sides on the polygon: "))
            shape = "polygon"
            anglesum = (sides - 2) * 180
            extangles = 360 / sides
            intangles = anglesum / sides
            if sides < 3:
                print("Sorry, the polygon must have at least 3 sides.")
            if sides == 3:
                shape = "triangle"
            if sides == 4:
                shape = "quadrilateral"
            if sides == 5:
                shape = "pentagon"
            if sides == 6:
                shape = "hexagon"
            if sides == 7:
                shape = "heptagon"
            if sides == 8:
                shape = "octagon"
            if sides == 9:
                shape = "nonagon"
            if sides == 10:
                shape = "decagon"
            if sides == 11:
                shape = "hendecagon"
            if sides == 12:
                shape = "dodecagon"
            if sides == 13:
                shape = "tridecagon"
            if sides == 14:
                shape = "tetradecagon"
            if sides == 15:
                shape = "pentadecagon"
            if sides == 16:
                shape = "hexadecagon"
            if sides == 17:
                shape = "heptadecagon"
            if sides == 18:
                shape = "octadecagon"
            if sides == 19:
                shape = "enneadecagon"
            if sides == 20:
                shape = "icosagon"
            if sides == 24:
                shape = "icositetragon"
            if sides == 30:
                shape = "tricontagon"
            if sides == 40:
                shape = "tetracontagon"
            if sides == 50:
                shape = "pentacontagon"
            if sides == 60:
                shape = "hexacontagon"
            if sides == 70:
                shape = "heptacontagon"
            if sides == 80:
                shape = "octacontagon"
            if sides == 90:
                shape = "enneacontagon"
            if sides == 100:
                shape = "hectagon"
            if sides == 1000:
                shape = "chiliagon"
            if sides == 10000:
                shape = "myriagon"
            if sides == 1000000:
                shape = "megagon"
            if sides > 1000000:
                shape = "apeirogon"
            print("The polygon is a", shape)
            print("THe sum of the angles is", anglesum, "degrees.")
            print("The measure of each exterior angle is", extangles,
                  "degrees.")
            print("The measure of each interior angle is", intangles,
                  "degrees.")
        except ValueError:
            print("x" * numChars)
            print("Please enter a positive integer.")


class ThreeDFormulas:
    def Vcube(self):
        try:
            l = float(input("Enter value for side length: "))

            print("You simply cube(Â³)", l, "(good pun)")
            print("The volume of the cube is", l**3, "cubic units.")
        except ValueError:
            print("x" * numChars)
            print("Please enter a number.")

    def SAcube(self):
        try:
            l = float(input("Enter value for side length: "))

            print("square", l, "then multiply it by 6")
            print("The surface area of the cube is", l**2 * 6, "square units.")
        except ValueError:
            print("x" * numChars)
            print("Please Enter a number.")

    def Vrectprism(self):
        try:
            l = float(input("Enter value for length: "))
            w = float(input("Enter value for width: "))
            h = float(input("Enter value for height: "))

            print("Multiply length, width and height together")
            print("The volume of the rectangular prism is", l * w * h,
                  "units.")
        except ValueError:
            print("x" * numChars)
            print("Please enter a number")

    def SArectprism(self):
        try:
            l = float(input("Enter value for length: "))
            w = float(input("Enter value for width: "))
            h = float(input("Enter value for height: "))

            print(
                "Multiply l with w, w with h, and l with h, then multiply it all by 2."
            )
            print(
                "The surface area of the rectangular prism is " + str(
                    (l * w + w * h + l * h) * 2), "square units.")
        except ValueError:
            print("x" * numChars)
            print("Please enter a number.")

    def Vtriprism(self):
        try:
            b = float(input("Enter value for area of the base: "))
            h = float(input("Enter the value for height: "))

            print(
                "Calculate the area of the base of the triangle by multiplying their two side lengths, then divide by 2."
            )
            print("Multiply the base by the height.")
            print("The volume of the triangular prism is " + str(b * h),
                  "cubic units.")
        except ValueError:
            print("x" * numChars)
            print("Please enter a number.")

    def SAtriprism(self):
        try:
            s1 = float(
                input(
                    "Enter value for the first side of the triangular face: "))
            s2 = float(
                input(
                    "Enter value for the second side of the triangular face: ")
            )
            s3 = float(
                input(
                    "Enter value for the third side of the triangular face: "))
            h = float(input("Enter value for the height of the prism: "))
            htri = float(
                input("Enter value for the height of the triangle face: "))

            print(
                "For each side, multiply them by the height, then add them together."
            )
            print("Multiply one side length with the height of the triangle.")
            print(
                "The surface area for the triangular prism is " +
                str(s1 * h + s2 * h + s3 * h + h * htri), "square units.")
        except ValueError:
            print("x" * numChars)
            print("Please enter a number.")

    def Vsquarepyramid(self):
        try:
            side = float(
                input("Enter value for the side of the base of the pyramid: "))
            h = float(input("Enter value for height of the pyramid: "))

            print("Square(Â²) the side length.")
            print("Multiply the base by 1/3 and the height.")
            print(
                "The volume of the square pyramid is " + str(
                    1 / 3 * h * side * side), "cubic units.")
        except ValueError:
            print("x" * numChars)
            print("Please enter a number.")

    def SAsquarepyramid(self):
        try:
            side = float(
                input("Enter value for the side of the base of the pyramid: "))
            slanth = float(input("Enter value for the slanted height: "))

            print("Square(Â²) the side length.")
            print(
                "Multiply 1/2 with the perimeter of the base with the slant height."
            )
            print(
                "Add the area of the base to the top part which was multiplied before."
            )
            print(
                "The surface area of the square pyramid is " +
                str(side * side + 1 / 2 * side * 4 * slanth), "square units.")
        except ValueError:
            print("x" * numChars)
            print("Please enter a number.")

    def Vcone(self):
        try:
            r = float(input("Enter value for the radius: "))
            h = float(input("Enter value for the height of the pyramid: "))

            print(
                "Square(Â²) the radius, then multiply by pi for the area of the base."
            )
            print("Multiply the base with 1/3 with the height.")
            print(
                "The volume of the cone is " + str(
                    round(r * r * pi * 1 / 3 * h, 2)), "cubic units.")
        except ValueError:
            print("x" * numChars)
            print("Please enter a number.")

    def SAcone(self):
        try:
            r = float(input("Enter value for the radius: "))
            slanth = float(input("Enter value for the slant height: "))

            print(
                "Square(Â²) the radius, then multiply by pi for the area of the base."
            )
            print("For circumference, double the radius and multiply by pi.")
            print("Multiply 1/2 with the circumference with the slant height.")
            print(
                "The surface area of the cone is " + str(
                    round(r * r * pi + 1 / 2 * 2 * r * pi + slanth, 2)),
                "square units.")
        except ValueError:
            print("x" * numChars)
            print("Please enter a number.")

    def Vsphere(self):
        try:
            r = float(input("Enter value for the radius: "))

            print("Cube(Â³) the radius, then multiply with pi with 4/3.")
            print(
                "The volume of the sphere is " + str(
                    round(4 / 3 * pi * r**3, 2)), "cubic units.")
        except ValueError:
            print("x" * numChars)
            print("Please enter a number.")

    def SAsphere(self):
        try:
            r = float(input("Enter value for the radius: "))

            print("Multiply 4 with pi with the square of radius.")
            print(
                "The surface area of the sphere is " + str(
                    round(4 * pi * r * r, 2)), "square units.")
        except ValueError:
            print("x" * numChars)
            print("Please enter a number.")


class GraphingFormulas:
    def Parabola(self):
        try:
            h = float(input("Enter value for x-coordinate of the vertex: "))
            k = float(input("Enter value for y-coordinate of the vertex: "))
            a = float(
                input("Enter the stretch/shrink value for the parabola: "))

            print("The formula for any parabola is y = (x - h)Â² + k.")

            print("=" * numChars)
            print("The formula of this parabola is y =",
                  str(round(a, 2)) + "(x +", "(" + str(h * -1) + ")" + ")Â² +",
                  str(round(k, 2)))
        except ValueError:
            print("x" * numChars)
            print("Please enter a number.")

    def Line(self):
        try:
            x1 = float(input("Enter value for x1:  "))
            y1 = float(input("Enter value for y1:  "))
            x2 = float(input("Enter value for x2:  "))
            y2 = float(input("Enter value for y2:  "))

            print("Using points (" + str(x1) + ", " + str(y1) + ")", "and",
                  "(" + str(x2) + ", " + str(y2) + ")")
            slope = (y2 - y1) / (x2 - x1)
            b = y1 - x1 * slope
            print("The formula for any line is y = mx + b")
            print("=" * numChars)
            print("The slope-y-intercept formula is y =",
                  str(round(slope, 2)) + "x +", round(b, 2))
        except ValueError:
            print("x" * numChars)
            print("Please enter a number.")
        except ZeroDivisionError:
            print("x" * numChars)
            print("Slope is undefined!")

    def length(self):
        try:
            x1 = float(input("Enter value for x1:  "))
            y1 = float(input("Enter value for y1:  "))
            x2 = float(input("Enter value for x2:  "))
            y2 = float(input("Enter value for y2:  "))

            print("Using points (" + str(x1) + ", " + str(y1) + ")", "and",
                  "(" + str(x2) + ", " + str(y2) + ")")
            length = sqrt((x2 - x1)**2 + (y2 - y1)**2)
            print("=" * numChars)
            print("The length is", round(length, 2), "units")

        except ValueError:
            print("x" * numChars)
            print("Please enter a number.")

    def slope(self):
        try:
            x1 = float(input("Enter value for x1:  "))
            y1 = float(input("Enter value for y1:  "))
            x2 = float(input("Enter value for x2:  "))
            y2 = float(input("Enter value for y2:  "))

            print("Using points (" + str(x1) + ", " + str(y1) + ")", "and",
                  "(" + str(x2) + ", " + str(y2) + ")")
            slope = (y2 - y1) / (x2 - x1)
            print("=" * numChars)
            print("The slope is", round(slope, 2))
        except ValueError:
            print("x" * numChars)
            print("Please enter a number.")
        except ZeroDivisionError:
            print("x" * numChars)
            print("Slope is undefined!")


class Extras:
    def Date(self):
        print("The date is", datetime.datetime.now().strftime("%m/%m/%Y"))

    def Time(self):
        print("The current time is", datetime.datetime.now().time())

    def hex(self):
        try:
            x = int(input("Enter an integer: "))
            print("The number in hexadecimal form is", hex(x))
        except ValueError:
            print("Please enter an integer.")

    def bin(self):
        try:
            x = int(input("Enter an integer: "))
            print("The number in binary form is", bin(x))
        except ValueError:
            print("Please enter an integer.")

    def ord(self):
        try:
            x = input("Enter a character: ")
            print("The character in number form is", ord(x))
        except ValueError:
            print("Please enter a character.")

    def chr(self):
        try:
            x = int(input("Enter an integer: "))
            print(
                "Some characters may not be visible as your system may not support it."
            )
            print("The number in character form is", chr(x))
        except OverflowError:
            print("No such character for this value exists.")
        except ValueError:
            print("Please enter an integer.")

    def oct(self):
        try:
            x = int(input("Enter an integer: "))
            print("The number in octal form is", oct(x))
        except ValueError:
            print("Please enter an integer.")


while 1:
    q = input(
        "What do want to calculate for?\n(Type in 'help' for more information.) "
    )
    if "typeof-polygon" in str.lower(q):
        print("You are determining for angle sizes and type of polygon.")
        TrigonometricFormulas.typeofpolygon(self)
        continue

    if "date" in str.lower(q):
        print("You are finding the current date.")
        Extras.Date(self)
        continue

    if "time" in str.lower(q):
        print("You are finding the current time.")
        Extras.Time(self)
        continue

    if "oct" in str.lower(q):
        print("You are finding the octal form of an integer.")
        Extras.oct(self)
        continue

    if "hex" in str.lower(q):
        print("You are finding the hexadecimal form of an integer.")
        Extras.hex(self)
        continue

    if "ord" in str.lower(q):
        print(
            "You are finding the character's order in the UTF-8 character sequence."
        )
        Extras.ord(self)
        continue

    if "bin" in str.lower(q):
        print("You are finding the binary form of an integer.")
        Extras.bin(self)
        continue

    if "chr" in str.lower(q):
        print(
            "You are finding the character that matches the number in the UTF-8 sequence."
        )
        Extras.chr(self)
        continue

    if "pi" in str.lower(q):
        print("You are finding the several digits of pi(Ï€).")
        ArithmeticFormulas.pi(self)
        continue

    if "pyth-theorem" in str.lower(q):
        print("You are calculating for pythagorean theorem.")
        TrigonometricFormulas.PythagoreanTheorem(self)
        continue

    if "factors-number" in str.lower(q):
        print("You are finding all factors of a particular number.")
        ArithmeticFormulas.getallfactors(self)
        continue

    if "fibonacci" in str.lower(q):
        print("You are finding the terms of the fibonacci sequence.")
        ArithmeticFormulas.fibonacci(self)
        continue

    if "sin" in str.lower(q):
        print("You are finding a ratio with sine.")
        TrigonometricFormulas.sin(self)
        continue

    if "cos" in str.lower(q):
        print("You are finding a ratio with cosine.")
        TrigonometricFormulas.cos(self)
        continue

    if "tan" in str.lower(q):
        print("You are finding a ratio with tangent.")
        TrigonometricFormulas.tan(self)
        continue

    if "v-cube" in str.lower(q):
        print("You are calculating for volume of cube.")
        ThreeDFormulas.Vcube(self)
        continue

    if "sa-cube" in str.lower(q):
        print("You are calculating for surface area of cube.")
        ThreeDFormulas.SAcube(self)
        continue

    if "v-rectprism" in str.lower(q):
        print("You are calculating for volume of rectangular prism.")
        ThreeDFormulas.Vrectprism(self)
        continue

    if "sa-rectprism" in str.lower(q):
        print("You are calculating for surface area of rectangular prism.")
        ThreeDFormulas.SArectprism(self)
        continue

    if "v-squarepyramid" in str.lower(q):
        print("You are calculating for volume of square pyramid.")
        ThreeDFormulas.Vsquarepyramid(self)
        continue

    if "sa-squarepyramid" in str.lower(q):
        print("You are calculating for surface area of square pyramid.")
        ThreeDFormulas.SAsquarepyramid(self)
        continue

    if "v-cone" in str.lower(q):
        print("You are calculating for volume of cone.")
        ThreeDFormulas.Vcone(self)
        continue

    if "sa-cone" in str.lower(q):
        print("You are calculating for surface area of cone.")
        ThreeDFormulas.SAcone(self)
        continue

    if "v-sphere" in str.lower(q):
        print("You are calculating for volume of sphere.")
        ThreeDFormulas.Vsphere(self)
        continue

    if "sa-sphere" in str.lower(q):
        print("You are calculating for surface area of sphere.")
        ThreeDFormulas.SAsphere(self)
        continue

    if "slope-line" in str.lower(q):
        print("You are calculating for slope of line.")
        GraphingFormulas.slope(self)
        continue

    if "len-line" in str.lower(q):
        print("You are calculating for length of line.")
        GraphingFormulas.length(self)
        continue

    if "form-line" in str.lower(q):
        print("You are calculating for formula of line.")
        GraphingFormulas.Line(self)
        continue

    if "form-parabola" in str.lower(q):
        print("You are calculating for formula of parabola.")
        GraphingFormulas.Parabola(self)
        continue

    if "exit" in str.lower(q) or "quit" in str.lower(q):
        print("OK Bye!")
        break

    if "help" in str.lower(q):
        print("Command | function | input parameters")
        print("'typeof-polygon' for polygon identification. [sides]")
        print("'pyth-theorem' for pythagorean theorem. [a, b]")
        print("'factors-number' for factors of a number. [num]")
        print("'sin' for sine ratio. [n]")
        print("'cos' for cosine ratio. [n]")
        print("'tan' for tangent ratio. [n]")
        print("'v-cube' for volume of a cube. [l]")
        print("'sa-cube' for surface area of a cube. [l]")
        print("'v-rectprism' for volume of a rectangular prism. [l, w, h]")
        print(
            "'sa-rectprism' for surface area of a rectangular prism. [l, w, h]"
        )
        print("'v-squarepyramid' for volume of a square pyramid. [side, h]")
        print(
            "'sa-squarepyramid' for surface area of a square pyramid. [side, slanth]"
        )
        print("'v-cone' for volume of a cone. [r, h]")
        print("'sa-cone' for surface area of a cone. [r, slanth]")
        print("'v-sphere' for volume of a sphere. [r]")
        print("'sa-sphere' for surface area of a sphere. [r]")
        print("'slope-line' for slope of a line. [x1, y1, x2, y2]")
        print("'len-line' for length of a line. [x1, y1, x2, y2]")
        print("'form-line' for formula of a line. [x1, y1, x2, y2]")
        print("'form-parabola' for formula of a parabola. [h, k, a]")
        print("'pi' for Pi(Ï€). []")
        print(
            "'ord' for order of a character's order in the UTF-8 sequence. [x]"
        )
        print(
            "'chr' for character that matches the number in the UTF-8 sequence. [x]"
        )
        print("'bin' for binary form of an integer. [x]")
        print("'hex' for hexadecimal form of an integer. [x]")
        print("'oct' for octal form of an integer. [x]")
        print("'date' for the current date. [x]")
        print("'time' for the current time. [x]")
        print("'exit' or 'quit' to terminate the program.\n")

    else:
        print("Command", "'" + str(q) + "'", "not found.\n")

print("$" * numChars)
print("Thank you for using my program!")
"""
Resources:
http://mdk12.msde.maryland.gov/share/pdf/hsa_math_reference_sheet_v2.pdf
https://www.youtube.com/watch?v=CShU2oP7OqY
http://www.informit.com/articles/article.aspx?p=459269&seqNum=7
http://www.pythonforbeginners.com/basics/python-datetime-time-examples
https://stackoverflow.com

"""
