# assignment-9-python
python
ef fibo(n):
    if n<2:
        return 1
    else:
        res = fibo(n-1) + fibo(n-2)
        sum = sum + res
        return res, sum

n=7
sum = 0
for i in range(1, n):
    print(fibo(i))

print("Suma", sum)
