def add(num1, num2):
    return num1 + num2


def subtract(num1, num2):
    return num1 - num2


def multiply(num1, num2):
    return num1 * num2


def divide(num1, num2):
    return num1 / num2


def percentage(num1, num2):
    return num1 + num2 / marks * 100


def square(num1):
    return num1 ** 2


def square(num2):
    return num2 ** 2


def squareroot(num1):
    return num1 ** 0.5


def squareroot(num2):
    return num2 ** 0.5


def cube(num1):
    return num1 ** 3


def cube(num2):
    return num2 ** 3


def cuberoot(num1):
    return num1 ** (1 / 3)


def cuberoot(num2):
    return num2 ** (1 / 3)


def remainder(num1, num2):
    return num1 % num2
name = str(input("please enter your name to use this calculator : "))

number_1 = int(input("Enter first number: "))
number_2 = int(input("Enter second number: "))

select = int(input("press 0 to exit \n"
                   "press 1 for addition  \n"
                   "press 2 for subtraction \n "
                   "press 3 for multiplication \n "
                   "press 4 for division \n "
                   "press 5 for percentage \n "
                   "press 6 for square \n"
                   "press 7 for square root \n"
                   "press 8 for cube \n"
                   "press 9 for cube root : "))
if select == 0:
    exit()
elif select == 1:
    print(number_1, "+", number_2, "=",
          add(number_1, number_2))

elif select == 2:
    print(number_1, "-", number_2, "=",
          subtract(number_1, number_2))

elif select == 3:
    print(number_1, "*", number_2, "=",
          multiply(number_1, number_2))

elif select == 4:
    print(number_1, "/", number_2, "=",
          divide(number_1, number_2))

    print("remainder", "=",
          remainder(number_1, number_2))
elif select == 5:
    marks = int(input("enter total marks for this calculation: "))
    print(number_1, "+", number_2, "/", marks, "*", 100, "=",
          percentage(number_1, number_2))
elif select == 6:
    print(number_1, "**", "2", "=",
          square(number_1))
    print(number_2, "**", "2", "=",
          square(number_2))
elif select == 7:
    print(number_1, "**", "0.5", "=",
          squareroot(number_1))
    print(number_2, "**", "0.5", "=",
          squareroot(number_2))
elif select == 8:
    print(number_1, "**", "3", "=",
          cube(number_1))
    print(number_2, "**", "3", "=",
          cube(number_2))
elif select == 9:
    print(number_1, "**", "1/3", "=",
          cuberoot(number_1))
    print(number_2, "**", "1/3", "=",
          cuberoot(number_2))

else:
    print("pleasse enter a valid number")
rating = input("please provide a rating to my calculator between 1 to 10 : ")

print("thank you for using my calculator")
print("*" * 100)
