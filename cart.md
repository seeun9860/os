     c = input("기호를 입력하세요.(+,-,*,/,q(종료)> "))
    
    elif c == "*":
        print("{} * {} = {}".format(a, b, a * b))
    elif c == "/":
        if b != 0:  # 0으로 나누는 경우를 방지
            print("{} / {} = {}".format(a, b, a / b))
        else:
            print("0으로 나눌 수 없습니다.")