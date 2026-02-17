# Separate-positive-and-negative-numbers-in-lists
NumList = []
Positive = []
Negative = []
Number = int(input("Please enter the Total Number of List Elements: "))
for i in range(1, Number + 1):
    value = int(input(f"Please enter the Value of {i} Element: "))
    NumList.append(value)
for j in NumList:
    if j >= 0:
        Positive.append(j)
    else:
        Negative.append(j)
print("Elements in Positive List:", Positive)
print("Elements in Negative List:", Negative)

OUTPUT:
Please enter the Total Number of List Elements: 6
2
-3
-5
9
-8
7
Elements in Positive List: [2, 9, 7]
Elements in Negative List: [-3, -5, -8]
