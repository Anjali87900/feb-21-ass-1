n=int(input("enter n"))
asii_value=97
for i in range(1,n+1):
    for j in range(1,n+1):
        print(chr(asii_value),end=" ")
        asii_value+=1
    print("\n")    
