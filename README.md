# Binary-Battles
# cook your dish here
for i in range (int(input())):
    n,a,b = map(int,input().split())
    c=0
    while(n>1):
        c+=1
        n=n/2
    print(c*a + (c-1)*b)
