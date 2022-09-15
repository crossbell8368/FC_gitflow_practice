
# Meaning of Fibonacci

피보나치 수는 첫 번째와 두 번째 값이 1이고 다음부터는 그 전의 수와 그 전전의 수를 더하는 방식


# Shape of Fibonacci

첫 번째 값이 0으로 시작하는 경우도 있으며 아래와 같은 형태의 수열
(0), 1, 1, 2, 3, 5, 8, 13,...

2는 처음 1과 그다음의 1을 합쳐서 계산되며, 3 역시 1과 2의 합으로 계산되는 방식


# Fibonacci number recursive function (python) 

def fibo(num):
    if num == 0:
        return 0
    elif num == 1 or num == 2:
        return 1
    else:
        return fibo(num - 1) + fibo(num - 2)

