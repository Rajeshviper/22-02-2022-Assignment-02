# 22-02-2022-Assignment-02
n=int(input("enter no:"))

for i in range(1,n+1):

    for j in range(1,i+1):

        print(j,end=" ")

    print("\n")

for i in range(2,n+1):

    for j in range(1,n-i+2):

        print(j,end=" ")

    print("\n")
