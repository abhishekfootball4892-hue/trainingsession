r = int(input("no of rats"))
unit = int(input(" amount of food each rat consumes"))
n = int(input("no of houses"))
arr = list(map(int, input().split()))
required = r * unit
sum = 0
for i in range(n):
    sum += arr[i]
    if sum >= required:
        print(i + 1)
        break
else:
    print(0)
