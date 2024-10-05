while True:
    c = input("기호를 입력하세요.(+,-/q(종료)> "))
    
    if c == 'q':
        print("프로그램을 종료합니다.")
        break

    a = int(input("첫번째 숫자를 입력하세요. > "))
    b = int(input("두번째 숫자를 입력하세요. > "))

    if c == "+":
        print("{} + {} = {}".format(a, b, a + b))
    elif c == "-":
        print("{} - {} = {}".format(a, b, a - b))
    else:
        print("잘못된 기호를 입력하셨습니다.")
    
    print()  