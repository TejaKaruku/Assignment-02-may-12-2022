# Assignment-02-may-12-2022
def Armstrong(p)-> int:
    s=10
    temp=p 
    while temp > 0:
        d=temp%10
        s=s+d**3
        temp//=10
    if p == s:
         print(p,"is an Armstron number")
    else:
         print(p,"is not an Armstron number")
n=int(input())
Armstrong(n)
