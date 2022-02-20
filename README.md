# feb-19-ass-1
Assignment-1
def myprime(n):
    x=n//2
    for i in range(2,x+1):
        if n%i==0:
            return False
    return True
t=int(input())
for i in range(t):
    x=input().split(' ')
    m=int(x[0])
    n=int(x[1])
    c=0
    for i in range(m+1,n):
        if myprime(i):
            c=c+1
    print(c)
