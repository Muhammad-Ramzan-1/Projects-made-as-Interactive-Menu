while True:
    print("\n------------------------MENU------------------------\n")

    a = print("1. Ramu calculator")
    b = print("2. Weight calculator")
    c = print("3. Area of circle calculator\n")

    ask = input("Select an Option> A, B or C: ").lower().strip()
    if ask in ["quit", "q"]:
        break

    if ask == "a":
        print("Opening 'Ramu calculator'")
        print("\n------------------------Ramu calculator------------------------\n")
        ques = (input("Enter an operator to use (`+`, `-`, `*`, `/`): "))
        op1 = float(input("\nEnter a number: "))
        op2 = float(input("Enter a second number: "))
        print()
        if ques == ("+"):
            result = op1+op2
            print(result)
        elif ques == ("-"):
            result = op1-op2
            print(result)
        elif ques == ("*"):
            result = op1*op2
            print(result)
        elif ques == ("/"):
            result = op1/op2
            print(result)
        else:
            print(f"The entered {ques} is not a valid operator")

    elif ask == "b":
        print("Opening 'Weight calculator'")
        print("\n------------------------Weight calculator------------------------\n")
        weight = float(input("\nEnter a weight: "))
        if ask in ["k", "kg", "kilograms\n"]:
            weight *= 2.206
            print(round(weight))
        elif ask in ["p", "pounds"]:
            weight /= 2.206
            print(round(weight, 2))
        else:
            print("Please put a valid input\n")

    elif ask == "c":
        print("Opening 'Area of a circle calculator'")
        print("\n------------------------Area of a circle calculator------------------------\n")
        import math
        radius = float(input("Enter the radius of a circle: "))
        print(f"the value of pi is {math.pi}")
        area = math.pi*pow(radius, 2)
        print()
        print(
            f"\nThe rounded Area of the circle of the entered Radius is {round(area)}\n")
