# FavNum
t=int(input())
while t:
    a=int(input())
    if((a%2)==0 and (a%7)==0):
        print("ALICE")
    elif((a%2)!=0 and (a%9)==0):
        print("BOB")
    else:
        print("CHARLIE")
    t-=1
