print("\n===== WELCOME TO RUSHI'S STAR PATTERN GENERATOR =====\n")

size = int((input("Enter The Size Of The Patterns: ")))
print("\n===== STAR PATTERN GENERATED =====\n")

print("\nLeft-Aligned Number Pyramid:")
for i in range(1, size + 1):
    print(" ".join(str(j) for j in range(1, i + 1)))

print("\nInverted Left-Aligned Number Pyramid:")
for i in range(size, 0, -1):
    print(" ".join(str(j) for j in range(1, i + 1)))

print("\nHollow Left-Aligned Number Pyramid:")
for i in range(1, size + 1):
    if i == 1:
        print("1")
    elif i == size:
        print(" ".join(str(j) for j in range(1, i + 1)))
    elif i == 2:
        print("1" + " " + "2")
    else:
        print("1" + " " * ((2 * (i - 2))+1) + str(i))

print("\nSymmetric Number Pyramid:")
for i in range(1, size + 1):
    print(" " * ((size - i)*2) + " ".join(str(j) for j in range(1, i + 1)) + " " + " ".join(str(j) for j in range(i - 1, 0, -1)))

print("\nHollow Pyramid:")
for i in range(1, size + 1):
    if i == 1:
        print(" " * (size - i) + "1")
    elif i == size:
        print(" " * (size - i) + " ".join(str(j) for j in range(1, i + 1)))
    else:
        print(" " * (size - i) + "1" + " " * (2 * (i - 2) + 1) + str(i))

print("\nHollow Inverted Left-Aligned Pyramid:")
for i in range(size, 0, -1):
    if i == size or i == 1:
        print(" ".join(str(j) for j in range(1, i + 1)))
    elif i == 2:
        print("1" + " " + "2")
    else:
        print("1" + " " * ((2 * (i - 2))+1) + str(i))

print("\nIncreasing Number Pyramid:")
for i in range(1, size + 1):
    print(" " * (size - i) + (str(i) + " ") * i)

print("\nSlanted Number Pyramid:")
for i in range(1, size + 1):
    print(" " * (size - i) + " ".join(str(j) for j in range(1, i + 1)))

print("\nStar Pyramid:")
for i in range(1, size + 1):
    print(" " * (size - i) + "* " * i)

print("\nSymmetric Number Pyramid (again):")
for i in range(1, size + 1):
    print(" " * ((size - i)*2) + " ".join(str(j) for j in range(1, i + 1)) + " " + " ".join(str(j) for j in range(i - 1, 0, -1)))

print("\nInverted Symmetric Number Pyramid:")
for i in range(size, 0, -1):
    print(" " * ((size - i)*2) + " ".join(str(j) for j in range(i, 0, -1)) + " " + " ".join(str(j) for j in range(2, i + 1)))

print("\nInverted Star Pyramid:")
for i in range(size, 0, -1):
    print(" " * (size - i) + "* " * i)

print("\nDecreasing Number Pyramid:")
for i in range(size, 0, -1):
    print(" " * (size - i) + (str(i) + " ") * i)
