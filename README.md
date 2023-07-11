# ShoeFit
# cook your dish here
t=int(input())
while t:
    a=list(map(int,input().split()))
    if((a+b)==1 or (b+c)==1 or (c+a)==1):
        print("1")
    else:
        print("0")
    t-=1
    
