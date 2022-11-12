# python-
python recursion(problem sum of digit )
wihout recuersion and with recursion


Recrsion
def ssum(num):
    if num != 0:
        digit = num % 10
        n = int(num // 10)
        sumf = digit + ssum(num)
    else:
        return 0
    return sumf


n = int(input("enter the number"))
s = ssum(n)
print(s)

without recoursion
n = input("enter the number")
temp = 0
for i in range(len(n) + 1):
 a = i % 10
 temp = a + temp
 print(temp)
