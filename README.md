import math

def calculate_circle_area(radius):
    area = math.pi * (radius ** 2)
    return area

# Example usage
radius = 5
circle_area = calculate_circle_area(radius)
print("The area of the circle is:", circle_area)
