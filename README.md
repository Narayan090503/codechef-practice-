# codechef-practice-
for x in range(int(input())):
    n=int(input())
    c=0
    for i in range(n):
        for j in range(i):
            if (i+j)%2==1:
                c+=2
    print(c)
