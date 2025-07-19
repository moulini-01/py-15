# py-15
hollow trapezium printing using python
n=5
for i in range(n):
	for j in range(n-i-1):
	    print(" ",end="")
	for k in range(n+i):
	    if (i==0 or j==n-i-1 or k==0 or k==n+i-1):
	        print("*",end=" ")
	    else:
  	 	    print(" ",end=" ")
	print( )
