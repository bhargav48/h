# h
min 
l=[]
n=int(input('enter n:'))
for i in range(n):
    x=int(input())
    l.append(x)
    min=l[0]
    for j in range(n):
        if l[i]<min:
            min=l[i]
            print(min)
            l=[]
for i in range(n):
    x=int(input())
    l.append(x)
    max=l[0]
    for j in range(n):
        if l[i]>max:
            max=l[i]
            print(max)
