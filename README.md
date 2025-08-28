

class Circle:
    def __init__(self, radius):
        self.radius = radius

    def calculate_area(self):
        return 3.1416 * (self.radius ** 2)  # Approximate value of π (pi)

    def calculate_perimeter(self):
        return 2 * 3.1416 * self.radius

    def display_details(self):
        print(f"Circle with radius: {self.radius}")
        print(f"Area: {self.calculate_area():.2f}")
        print(f"Perimeter: {self.calculate_perimeter():.2f}")

# Example Usage
radius = float(input("Enter the radius of the circle: "))
my_circle = Circle(radius)  # Creating an instance of the Circle class
my_circle.display_details()  # Display the results
