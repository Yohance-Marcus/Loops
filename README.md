# Loops
#num = 10
#print ("Table of 10")
#for i in range (1,11):
    #mul = num*i
    #print("10 x %d =%d" % (i, mul))
#n = int(input("enter number of rows"))
n = 5
for i in range(0, n):
    for j in range(0, i+1):
        print("*", end="")

    print("\n")
