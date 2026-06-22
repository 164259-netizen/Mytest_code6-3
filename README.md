print("Shape Calculator Program")

print("1. Rectangle")
print("2. Triangle")
print("3. Circle")

choice = int(input("Select a shape (1-3): "))

if choice == 1:
    width = float(input("Enter width: "))
    length = float(input("Enter length: "))
    area = width * length
    perimeter = 2 * (width + length)
    print("Area =", area)
    print("Perimeter =", perimeter)

elif choice == 2:
    base = float(input("Enter base length: "))
    height = float(input("Enter height: "))
    area = 0.5 * base * height
    print("Triangle area =", area)

elif choice == 3:
    radius = float(input("Enter radius: "))
    area = 3.14 * radius * radius
    circumference = 2 * 3.14 * radius
    print("Circle area =", area)
    print("Circumference =", circumference)

else:
    print("Invalid selection")
